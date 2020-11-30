---
layout: post
title: Migrate of StorSimple data to Azure Files 
categories: [Apps,Infra]
excerpt: Migrate of StorSimple data to Azure Files
---

StorSimple 8000 mainstream support will end on July 1 2020. A good alternative for StorSimple is the use of Azure Files in combination with Azure File Sync. This gives a similar solution to StorSimple:
Tiered file storage for on-premise use
Backup in Azure via snapshots of the file share

Besides these cool features, a smart migration method from StorSimple to Azure Files was developed by the Azure Files product team and presented at Ignite 2019. This migration method is "smart" because:
It is has, besides a very short "switch over moment", no impact on the ongoing StorSimple 8000 operation.
It is done in Azure using virtual resources that can be discarded after the migration.

[View original post](https://github.com/joostm1/storsimple-exit)
