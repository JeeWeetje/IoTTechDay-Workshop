# From device to acting on insights with the Azure IoT platform 
## IoT Tech Day 2017 - IoT Hands-on Lab

![IoT Tech Day 2017](img/logos/iottechday2017.png)

The workshop will simulate a remote located machine malfunctioning and getting restarted based on the received telemetry and created insights based on the telemetry data. You will be creating all components to get the malfunctioning machine back up running again. All of that within 2 hours.
In this hands-on lab, you will be creating the complete chain from configuring, connecting a device via packet radio technology to The Things Network cloud, to bridging the gap between the TTN cloud and the Microsoft Azure IoT platform, creating actionable insights on the Microsoft Azure IoT platform and sending commands all the way back to the device. This includes assembling hardware, configuring hardware and configuring software and coding the missing logic to a complete IoT solution.

Technologies used during the hands-on lab; `Arduino development boards`, `sensors`, `The Things Network` cloud (`LoRa` & `LoraWAN`) and Microsoft Azure IoT Platform including: `Azure Web Jobs`, `Azure IoT Hub`, `Azure Stream analytics`, `Azure Event hub`, `Azure Blob storage` and Azure Functions.

This hands-on lab will be guided by Jan Willem Groenenberg & Sander van de Velde , so attendees have on site support for questions. We will also provide background information about the used components in the hands-on lab. The hands-on lab is created in conjunction with Atos who will provide most the hardware used in the hands-on lab, the rest of the hardware will be provided by Microsoft Nederland. 

**Hardware used will *remain property* of Atos and/or Microsoft.**

## Team of experts

During the workshop the following experts will be present to guide you through the workshop:

- [Jan Willem Groenenberg](http://iottechday.nl/speakers/jan-willem-groenenberg/); IoT Solution Architect [ ![Twitter](img/social/twitter.png) ](https://twitter.com/jeeweetje) [ ![LinkedIn](img/social/linkedin.png) ](https://www.linkedin.com/in/jwgroenenberg/) [ ![LinkedIn](img/social/wordpress.png) ](https://jeeweetje.net)
- [Sander van de Velde](http://iottechday.nl/speakers/sander-van-de-velde/); MVP, Microsoft Consultant 
[ ![Twitter](img/social/twitter.png) ](https://twitter.com/svelde) [ ![LinkedIn](img/social/linkedin.png) ](https://www.linkedin.com/in/sandervandevelde/) [ ![LinkedIn](img/social/wordpress.png) ](https://sandervandevelde.wordpress.com)

## Workshop schedule at IoT Tech Day 2017

| Location | Start Time |  Room  |
| -------- | ---------- | ------ |
| Utrecht, Jaarbeurs, April 19 2017 | 11.30h | Glow |

## Let's dive into the workshop

The workshop consists of several chapters. The first two chapters will guide you through the essentials we want you to get your hands on. The other chapters are optional/extra if you have time left.

1. Connecting a device to the Azure IoT Platform

    | Choose the device to connect      ||||
    | :---: | :---: | :---: | :---: |
    | [![Getting started with the The Things Uno device and The Things Network](img/Options/arduino.png)](TheThingsNetwork.md) | [![Connecting to an IoT Hub using a UWP app device simulation](img/Options/windows.png)](UwpToIotHub.md) | [![Connecting to an IoT Hub using a NodeJs (JavaScript) app device simulation](img/Options/nodejs.png)](NodeJsToIotHub.md) | [![Connecting to an IoT Hub using a Java app device simulation](img/Options/java.png)](JavaToIotHub.md) |

2. Receiving and handling telemetry in Azure

    |       |       |       |
    | :---: | :---: | :---: |
    | ![The Things Network](img/Options/arduino.png) | ![Universal Windows Platform](img/Options/windows.png) | ![NodeJS](img/Options/nodejs.png) |

    1. [Receiving and handling telemetry in Azure, sent by a TheThingsUno](AzureTTN.md)
    1. [Receiving and handling telemetry in Azure, sent by a UWP app device simulation](AzureUWP.md)
    1. [Receiving and handling telemetry in Azure, sent by a NodeJs (JavaScript) app device simulation](AzureNodeJs.md)
3. Passing commands back to actual devices or simulated devices
    1. [Passing commands back to a The Things Uno device](CommandsTTN.md)
    2. [Passing commands back to a UWP app device simulation](CommandsUwp.md)
    3. [Passing commands back to a NodeJs (JavaScript) app device simulation](CommandsNodeJs.md)
4. Bonus
   1. [Deploying The Things Network Bridge to Azure as a WebJob](Webjob.md)
   2. [Add basic monitoring to the IoT platform](IoTPatformMonitoring.md)


