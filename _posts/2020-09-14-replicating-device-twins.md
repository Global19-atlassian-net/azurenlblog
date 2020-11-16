---
layout: post
title: Replicating Device Twins outside an IoT Hub Gateway
categories: [Data,AI]
excerpt: Using IoT Hub, Cosmos DB, Event Hub and Azure Functions
---

Cloud gateway services provide the ability to ingest and manage all communication from and to your devices. Within those services, typically every physical device has a digital representation inside a registry where information is stored about the device, such as its device id, connection status and other properties that describe its latest known information. This device data is relevant to end users as it shows important device health information which in many cases needs to be handled upon. Therefore, it is important to have the freedom to build applications that consume this data without being constrained by scalability and accessing underlying storage according to your development needs.

[View original post](https://github.com/machteldbogels/devicetwinsync)
