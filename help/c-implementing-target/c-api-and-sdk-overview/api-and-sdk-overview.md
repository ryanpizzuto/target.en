---
keywords: server side;server-side;api;sdk;node.js;nodejs;node js;recommendations api;api:apis
description: Learn about the Adobe Target server-side delivery APIs, SDKs, and Target Recommendations APIs.
title: Where Can I Learn About Target Server-Side Delivery APIs and SDKs?
feature: Implement Server-side
role: Developer
---

# Server Side: implement Target

Information about [!DNL Adobe Target] server-side delivery APIs, SDKs, and [!DNL Target Recommendations] APIs.

The following process occurs in a server-side implementation of [!DNL Target]:

1. A client device makes a request for an experience through your server.
1. Your server sends that request to [!DNL Target].
1. [!DNL Target] sends the response back to your server.
1. Your server makes the decision on which experience to deliver to the client device for it to render.

The experience does not need to display in a browser. The experience can display in an email or kiosk, via a voice assistant, or through some other non-visual experience or non-browser-based device. Because your server sits between the client and [!DNL Target], this type of implementation is also ideal if you need greater control and security or have complex backend processes that you want to run on your server.

>[!NOTE]
>
>A first-time visitor can be initialized only on the client-side. A first-time visitor *cannot* be initialized on the server-side.

The following sections provide more information about the various APIs and the NodeJS SDK:

## Server Side Delivery APIs

Link: [Server Side Delivery APIs](https://developers.adobetarget.com/api/delivery-api/)

`/rest/v1/delivery`

Through the [!DNL Target] Delivery API, you can:

* Deliver experiences across web, including SPAs, and mobile channels as well as non-browser based IoT devices, such as connected TVs, kiosks, or in-store digital screens.
* Deliver experiences from any server-side platform or application that can make HTTP/s calls.
* Deliver consistent and personalized experiences to a visitor regardless of which channel or devices the visitor used to engage with your business.
* Cache experiences for a visitor within a session on your server so that multiple API calls can be avoided, which achieves better performance.
* Seamlessly integrate with [!DNL Adobe Experience Cloud] products, such as [!DNL Adobe Analytics], [!DNL Adobe Audience Manager] (AAM), and the [!DNL Experience Cloud ID Service] from the server side.

## Server Side SDKs

Link: [Adobe Target SDKs](https://adobetarget-sdks.gitbook.io/docs/)

The [!DNL Adobe Target] server-side SDK documentation portal helps you implement [!DNL Target] on your servers in your language of choice.

## Target Recommendations APIs

Link: [Target Recommendations APIs](https://developers.adobetarget.com/api/recommendations) and [Adobe Recommendations API Overview](https://experienceleague.adobe.com/docs/target-learn/recommendations-api-tutorial/recs-api-overview.html).

The Recommendations APIs let you programmatically interact with [!DNL Target] recommendations servers. These APIs can be integrated with a range of application stacks to perform functions that you would typically do via the [!DNL Target] user interface.
