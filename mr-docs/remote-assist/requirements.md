---
author: jevertt
description:  Technical requirements for deploying and using Microsoft Dynamics 365 Remote Assist
ms.author: jevertt
ms.date: 4/01/2019
ms.service: crm-online
ms.topic: article
title: Requirements for Dynamics 365 Remote Assist
ms.reviewer: v-brycho
---

# Requirements for setting up Dynamics 365 Remote Assist

The following tables list technical requirements for deploying and using
[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] throughout your organization.

## Device requirements

| **Device**               | **OS requirements**                                                                                                                                                  | **Details**                                                                                                                                                                                                                    |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-hololens](../includes/pn-hololens.md)]                 | Build 10.0.14393.0 or later. [!include[pn-hololens](../includes/pn-hololens.md)] build 10.0.14393.0 is the minimum that supports [!include[pn-remote-assist](../includes/pn-remote-assist.md)]. We recommend updating [!include[pn-hololens](../includes/pn-hololens.md)] to newer versions when available. | See [Manage updates to HoloLens](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) for instructions on using [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update for Business, Mobile Device Management (MDM), and [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS). |
| [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC (optional) | Any [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 build.| A [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC can collaborate with [!include[pn-hololens](../includes/pn-hololens.md)] using [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].|
|Mobile device (optional)|Any iOS or [!include[tn-android](../includes/tn-android.md)  phone or tablet running [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)  Mobile.|A phone or tablet running [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md) Mobile can collaborate with [!include[pn-hololens](../includes/pn-hololens.md)].|

## Licensing and product requirements

| **Product required**|**Details**|**Learn more**|
|---------------|-------------------------------------------------------|----------------------------------------------------------|
|[!include[pn-remote-assist](../includes/pn-remote-assist.md)]|[!include[pn-remote-assist](../includes/pn-remote-assist.md)] software<br></br>**Note** [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] is included in the [!include[pn-remote-assist](../includes/pn-remote-assist.md)] subscription for individuals using a [!include[pn-remote-assist](../includes/pn-remote-assist.md)] license on [!include[pn-hololens](../includes/pn-hololens.md)]. A [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] license is also required for individuals (experts) who communicate with a [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user on [!include[pn-hololens](../includes/pn-hololens.md)]. [!include[pn-teams](../includes/pn-teams.md)] may be available [as a free download](https://teams.microsoft.com/downloads) for these users.| [Buy and deploy Remote Assist](../licensing/buy-and-deploy.md)|
|[!include[pn-azure](../includes/pn-azure.md)] Active Directory ([!include[pn-azure](../includes/pn-azure.md)] AD) account|Required for: <ul><li>Purchasing subscription and assigning licenses. You’ll need an [!include[pn-azure](../includes/pn-azure.md)] AD account for each licensed user. </li><li>Distributing apps through [!include[cc-microsoft](../includes/cc-microsoft.md)] Store for Business. </li><li>Users when signing in to the app. </ul> | [Get started with Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/get-started-azure-ad) |
| [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] (optional). **Note** that [!include[pn-field-service](../includes/pn-field-service.md)] version 8.2 or later is required. |[!include[pn-remote-assist](../includes/pn-remote-assist.md)] requires a [!include[pn-dyn-365](../includes/pn-dyn-365.md)] license if you want to view [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] bookings in [!include[pn-remote-assist](../includes/pn-remote-assist.md)]. To view [!include[pn-power-bi](../includes/pn-power-bi.md)] dashboards linked to [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] bookings in [!include[pn-remote-assist](../includes/pn-remote-assist.md)], users must have a valid [!include[pn-power-bi](../includes/pn-power-bi.md)] license. | [Learn more about Dynamics 365 for Field Service](https://dynamics.microsoft.com/en-us/field-service/overview/)|

## Network requirements

The recommended bandwidth for optimal performance of [!include[pn-remote-assist](../includes/pn-remote-assist.md)] is 1.5 MB/s.
Though audio/video calls might be possible in environments with reduced
bandwidth, you might experience [!include[pn-hololens](../includes/pn-hololens.md)] feature degradation, limiting the user
experience. To test your company’s network bandwidth, follow these steps:

1.  Have a [!include[pn-teams](../includes/pn-teams.md)] user start a video call with another [!include[pn-teams](../includes/pn-teams.md)] user.

2.  Add a separate video call between a third and fourth user, and another for a
    fifth and sixth user.

3.  Continue adding video callers to stress-test your network bandwidth until
    you’re confident that multiple users can successfully connect on video calls
    at the same time.

See [Prepare your organization’s network for Microsoft
Teams](https://docs.microsoft.com/en-us/MicrosoftTeams/prepare-network) to learn
more.

### See also
[Overview of Remote Assist](index.md)<br/>
[Try Remote Assist for free](try-remote-assist-free.md)<br/>
[Buy and deploy Remote Assist](buy-and-deploy-remote-assist.md)<br>
[User guide](user-guide.md)<br/>
[Set up and use Microsoft Teams with Remote Assist](use-microsoft-teams-with-remote-assist.md)<br/>
[How-to videos](videos.md)<br/>
[FAQ](faq.md)<br/>
