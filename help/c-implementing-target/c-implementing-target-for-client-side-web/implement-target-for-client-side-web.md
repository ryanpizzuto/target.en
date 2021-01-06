---
keywords: implement;implementation;at.js;adobe experience platform web sdk;aep web sdk
description: Information about implementing Adobe Target for client-side web using at.js.
title: Implement Adobe Target for client-side web
feature: at.js
---

# Overview: implement Target for client-side web

In a client-side implementation of [!DNL Adobe Target], [!DNL Target] delivers the experiences associated with an activity directly to the client browser. The browser decides which experience to display and displays it. With a client-side implementation, you can use a WYSIWYG editor, the [Visual Experience Composer](/help/c-experiences/c-visual-experience-composer/visual-experience-composer.md) (VEC), or a non-visual interface, the [Form-based Experience Composer](/help/c-experiences/form-experience-composer.md), to create your activity and personalization experiences.

To implement [!DNL Adobe Target] client-side, you must use the [Adobe Experience Platform Web SDK](https://experienceleague.adobe.com/docs/experience-platform/edge/home.html), [at.js](/help/c-implementing-target/c-implementing-target-for-client-side-web/c-how-atjs-works/how-atjs-works.md) or mbox.js library.

>[!IMPORTANT]
>
>**mbox.js end-of-life**: On March 31, 2021, [!DNL Adobe Target] will no longer support the mbox.js library. Post March 31, 2021, all calls made from mbox.js will gracefully fail and impact your pages that have [!DNL Target] activities running by serving default content. We recommend that all customers migrate to the most recent version of the new [!DNL Adobe Experience Platform Web SDK] or the at.js JavaScript library before this date to avoid any potential issues with your sites.
>
>* **Adobe Experience Platform Web SDK**: The [!UICONTROL Adobe Experience Platform Web SDK] lets you interact with the various services in the [!DNL Experience Cloud] (including [!DNL Target]) through the Adobe Experience Edge Network. If you choose to migrate to the [!DNL Adobe Experience Platform Web SDK], see [What is Adobe Experience Platform Web SDK](https://experienceleague.adobe.com/docs/experience-platform/edge/home.html), in the *Web SDK Guide*. See [Target overview](https://experienceleague.adobe.com/docs/experience-platform/edge/personalization/adobe-target/target-overview.html) for [!DNL Target]-specific information.
>
>* **at.js**: The at.js JavaScript library provides many advantages over mbox.js. Among other benefits, the at.js improves page load times for web implementations, improves security, and provides better implementation options for single page applications. If you choose to migrate to at.js, see [How At.js Works](/help/c-implementing-target/c-implementing-target-for-client-side-web/c-how-atjs-works/how-atjs-works.md) and [Adobe Target Skill Builder: Developer chat, migrate Adobe Target's mbox.js to at.js](https://seminars.adobeconnect.com/ptdo6mfo6qn6/?proto=true).
>
>Although, mbox.js is currently supported (until March 31, 2021), we have not provided feature updates to this library since July 2017. By moving all customers to the [!UICONTROL Adobe Experience Platform Web SDK] or at.js, our engineers and support staff will be able to provide you with new functionality and offer the support you have come to expect from Adobe.
