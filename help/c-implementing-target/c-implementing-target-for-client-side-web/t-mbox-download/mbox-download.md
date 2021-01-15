---
keywords: implementation;mbox;download mbox.js;download api;mbox.js api
description: To use Adobe Target Standard or Target Premium, add one line of code to call mbox.js.
title: mbox.js implementation
feature: 
---

# mbox.js implementation

To use [!DNL Adobe Target Standard] or [!DNL Target Premium], add one line of code to call mbox.js.

 You can use either of two library references: the [!DNL Adobe Experience Platform Web SDK] or [!DNL at.js]. [Benefits of at.js](/help/c-implementing-target/c-implementing-target-for-client-side-web/t-mbox-download/c-target-atjs-implementation/target-atjs-implementation.md#benefits) explains the differences between the mbox.js and at.js libraries.

>[!IMPORTANT]
>
>**mbox.js end-of-life**: On March 31, 2021, [!DNL Adobe Target] will no longer support the mbox.js library. Post March 31, 2021, all calls made from mbox.js will gracefully fail and impact your pages that have [!DNL Target] activities running by serving default content. We recommend that all customers migrate to the most recent version of the new [!DNL Adobe Experience Platform Web SDK] or the at.js JavaScript library before this date to avoid any potential issues with your sites.
>
>* **Adobe Experience Platform Web SDK**: The [!UICONTROL Adobe Experience Platform Web SDK] lets you interact with the various services in the [!DNL Experience Cloud] (including [!DNL Target]) through the Adobe Experience Edge Network. If you choose to migrate to the [!DNL Adobe Experience Platform Web SDK], see [What is Adobe Experience Platform Web SDK](/help/c-implementing-target/c-implementing-target-for-client-side-web/aep-web-sdk.md), in the *Web SDK Guide*.
>
>* **at.js**: The at.js JavaScript library provides many advantages over mbox.js. Among other benefits, the at.js improves page load times for web implementations, improves security, and provides better implementation options for single page applications. If you choose to migrate to at.js, see [How At.js Works](/help/c-implementing-target/c-implementing-target-for-client-side-web/c-how-atjs-works/how-atjs-works.md) and [Adobe Target Skill Builder: Developer chat, migrate Adobe Target's mbox.js to at.js](https://seminars.adobeconnect.com/ptdo6mfo6qn6/?proto=true).
>
>Although, mbox.js is currently supported (until March 31, 2021), we have not provided feature updates to this library since July 2017. By moving all customers to the [!UICONTROL Adobe Experience Platform Web SDK] or at.js, our engineers and support staff will be able to provide you with new functionality and offer the support you have come to expect from Adobe.

The single reference to [!DNL mbox.js] on each page provides the libraries needed for all of your activities. [!DNL mbox.js] calls [!DNL Target] from every page that references the [!DNL mbox.js] file. This enables [!DNL Target] to do the following:

* Deliver Target activities 
* Track clicks 
* Track most success metrics

>[!TIP]
>
>To simplify implementation, you could reference [!DNL mbox.js] in your global header.

You do not need to maintain different activity-specific versions of the file. 

1. Reference [!DNL mbox.js] in the `<head>` section of each page on your site.

   `<script src="/ *`directory`*/ *`scripts`*/mbox.js"></script>`

   Where ` *`directory`*/ *`scripts`*` is the directory where you saved your [!DNL mbox.js] file after downloading it. 
If you already have mboxes on your page from a legacy implementation, these mboxes can still be used in the new interface. The updated [!DNL mbox.js] file is still required, but these mboxes can be selected for activities and edited using the [!UICONTROL Visual Experience Composer].