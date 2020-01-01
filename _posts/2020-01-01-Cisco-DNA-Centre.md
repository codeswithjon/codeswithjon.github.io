---
layout: post
title: The 101 of Cisco's DNA Centre
---

It will please some of you that I almost titled this article “Cisco DNA Centre for folks who hate marketing” because the approach I took for writing this article was from the eyes of an Enterprise Customer who wants to know what Cisco’s DNA Centre is but may not want to know all the technical aspects of deployment, implementation or RFC standards that are littered across countless technical articles and marketing material.

The best way I personally can convey the answer to the popular question of “What is DNA Centre” is with the two bullet points below:

- DNA Centre is a physical controller that you deploy in your Network which then creates a “Controller-Fabric” overlay topology by linking in with your existing Cisco Routers and Switches. The “Controller-Fabric” design means you start thinking and managing your Network as one unit rather than a thousand or so individual pizza boxes.

- DNA Centre is for customer’s who are planning to go down the Software Defined Solution for their Network. Cisco has future proofed their customer’s by designing DNA Centre from the ground up with API’s to ensure customer’s can take advantage of Network DevOps.

Below are some of the top features that you gain as part of the DNA Centre Solution:

- ZTP (Zero Touch Provisioning). This means the thousand/s of switches and routers across your campus’s and branches can be centrally provisioned by the DNA Controller. No longer will your technical teams need to sit in a cold build room and cut and paste configuration onto boxes. Simply plug in your newly acquired switch/router and the DNA Controller will install a pre-determined configuration to that device.

- Assurance (This is one that Cisco wears as a badge of honour). Assurance does telemetry and metrics to produces information that you may not otherwise be allowed to see without spending quite a few dollars with top end monitoring systems. Clients, Network Devices and Applications are all monitored by Assurance to provide real-time feedback to Application owners and Network Administrators about issues that may be impacting business critical services. One particular feature within Assurance that I love is that you gain snapshots of your Network when there are issues so you can rewind the clock and dig into what issues were experienced at 2am when you were fast asleep.

- SDA (Software Defined Access). DNA Centre allows you to connect in with the Cisco Identify Services Engine (ISE) product to allow Network Administrators to create profiles for particular clients, business units or VIP’s in order to lock down who within the network can access what within the network. I must stress that this feature doesn’t mean you turn off your Firewalls or Proxy’s but it provides another abstract layer for permission based access. Think of it like an intelligent ACL thats on a particular switchport or Wireless AP defined only for that particular Client or Server. 

One thing I must stress for any Enterprise customer looking at the DNA Solution by Cisco is to do a couple of activities with your Network Team to make sure this is the right solution for you. Some activities I’d recommend are:

* Take stock of your Network Equipment and ensure all devices are Cisco branded. I don’t have much faith that a juniper switch will happily comply with a DNA Controller.

* Ensure all Cisco Network Equipment is on the latest IOS and is compatible with NETCONF (NETCONF was released back in 2006 so any switches made before then may have a hard time playing with this DNA Solution).

* Create as many templates for your configuration and document as much as possible. This will only help when you deploy DNA Centre but also standardise your network and bring it inline with an intent that aligns with the business.

* Bring your Application Owners and Helpdesk Staff along for the journey. This solution will give value to other areas of your ICT department than just the Network Team. 

That just about does it for this particular article. Keep in mind that my blog posts are fluent so if there are points I’ve missed or particular facts I’ve muddled up then I encourage you to let me know in the comments below and I’ll be sure to include them where I can.

Thanks!
