---
layout: post
title:  ASR-zone-to-zone with Proximity Placement Groups
categories: [Apps,Infra]
excerpt: a code example how to implement an Azure zone to zone Disaster Recovery solution.
---

This repository provides a code example how to implement an Azure zone to zone Disaster Recovery solution. This example shows a failover and failback of a virtual machine between 2 availability zones in a single region including the use of Proximity Placement Groups (PPG) so the Virtual Machine also failovers to another PPG and failbacks to its original PPG. The Virtual Machine uses a static ip address to show that the virtual machines keeps it's own ip address during the failover and failback and therefore it's also a good scenario for applications that cannot handle an ip address change during a DR situation.

[View original post](https://github.com/MarcvanHouten/ASR-zone-to-zone-with-ppg)
