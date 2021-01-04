---
keywords: Release notes;new features;releases;updates;update;release;enhancement;enhancements;fixes;bug fixes;updates
description: These release notes provide information about features, enhancements, fixes, and known issues for each Adobe Target Standard and Target Premium release.
title: Adobe Target release notes (current) 
feature: release notes
---

# Target release notes (current)

These release notes provide information about features, enhancements, and fixes for each Target Standard and Target Premium release. In addition, release notes for Target APIs, SDKs, the JavaScript library (at.js), and other platform changes are also included, when applicable.

>[!IMPORTANT]
>
>* **mbox.js end-of-life**: On March 31, 2021, Adobe Target will no longer support the mbox.js library. Post March 31, 2021, all calls made from mbox.js will gracefully fail and impact your pages that have Target activities running by serving default content. We recommend that all customers migrate to the most recent version of the at.js library before this date to avoid any potential issues with your sites. For more information, see [How At.js Works](/help/c-implementing-target/c-implementing-target-for-client-side-web/c-how-atjs-works/how-atjs-works.md) and [Adobe Target Skill Builder: Developer chat, migrate Adobe Target's mbox.js to at.js](https://seminars.adobeconnect.com/ptdo6mfo6qn6/?proto=true).
>
>   Although, mbox.js is currently supported, we have not provided feature updates to this library since July 2017. The newer at.js provides many advantages over mbox.js. Among other benefits, at.js improves page load times for web implementations, improves security, and provides better implementation options for single page applications.
>
>   By moving all customers to at.js, our engineers and support staff will be able to provide you with new functionality and offer the support you have come to expect from Adobe.
>
>* **Target Announcements**: See the Target announcements page for information about upcoming events, including Target Skill Builder sessions, developer chats, webinars, and Target Coffee Break sessions. For more information, see [Target announcements](/help/r-release-notes/target-announcements.md).

The issue numbers in parentheses are for internal [!DNL Adobe] use.

## at.js 2.3.3 (November 13, 2020)

This release of at.js is a maintenance release and includes the following fix:

* Fixed an issue related to mbox click tracking and A4T.

## Target Standard/Premium 20.10.1 (October 27, 2020)

This release contains the following new features:

|Feature|Details|
| --- | --- |
|[On-device decisioning](https://adobetarget-sdks.gitbook.io/docs/on-device-decisioning/introduction-to-on-device-decisioning)|On-device decisioning lets both marketers and product developers deliver experimentation and Machine Learning-driven personalization from within a user's device, across channels, at near-zero latency.<br>Speed and performance matters--in customer insights and user satisfaction.<br>On-device decisioning lets you compile key personalization and experimentation instructions in A/B Test and Experience Targeting (XT) activity types into "optimization artifacts:" JSON objects that are loaded onto customer devices via the CDN. And because on-device decisioning connects natively with [!DNL Adobe Experience Cloud] products, [!DNL Target] users get rapid analysis and faster experience iterations.<br>For more information, see *[On-device decisioning](/help/c-implementing-target/c-api-and-sdk-overview/on-device-decisioning.md).|

This release contains the following enhancements, fixes, and changes:

* Fixed an issue that prevented [!UICONTROL Average Lift Confidence Interval] and [!UICONTROL Confidence] from displaying in [!DNL Auto-Target] reporting for the [!UICONTROL Total] row. Measurements displayed correctly for all individual experiences. (TGT-37301)
* Fixed an issue that impacted [!DNL Adobe Target Premium] users’ [!UICONTROL Auto-Target] reporting from September 15, 2:30 p.m. (PDT) to October 6, 9:25 a.m. (PDT). When viewing reports for the impacted conversion metrics (configured using either the "[!UICONTROL Viewed a page]” or “[!UICONTROL Clicked on mbox]” option), the conversions rates are incorrectly reported. There is no known delivery issue at this time. For information about how to resynchronize and correct your reporting, see [Auto-Target reporting](/help/r-release-notes/known-issues-resolved-issues.md#at-metrics) under *Resolved issues* in *Known issues and resolved issues*.
* Added a selectable [!UICONTROL Last Updated At] column in the [!UICONTROL Catalog Search] table and a [!UICONTROL Last Updated At] filter. This enhancement saves time and effort because you don't have to open each individual item to see when it was last updated and you can filter by date the items were last updated.

  ![Last Updated at column and filter illustration](/help/r-release-notes/assets/column-and-filter.png)

* Updates were made to help make the Target UI compliant with [Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/) 2.0 Level A and AA Success Criteria (WCAG 2.0 AA). (TGT-34384 & TGT-24679)
* Made Content Security Policy (CSP) improvements. (TGT-37035)
* Introduced a way to specify the client code as a parameter for customers using CNAME. (TNT-38571)
* [!DNL Adobe Experience Cloud] documentation is moving to [!DNL Experience League]. During October, all release notes, articles, videos, and tutorials will move from their current location at `docs.adobe.com` to [!DNL Experience League]. This move ensures that all learning, self-help, enablement, and community content is served from a single location. When this change occurs, there is nothing you need to do, as all links will be redirected to [!DNL Experience League]. We will update the release notes when the cutover begins.

## Additional release notes and version details

|Resource|Details|
|--- |--- |
|[at.js version details](/help/c-implementing-target/c-implementing-target-for-client-side-web/target-atjs-versions.md)|Details about changes in each version of the [!DNL Adobe Target] at.js JavaScript library.|

## Documentation Changes, Past Release Notes, and Experience Cloud Release Notes

In addition to the notes for each release, the following resources provide additional information:

|Resource|Details|
|--- |--- |
|Documentation changes|View detailed information about updates to this guide that might not be included in these release notes.<br>For more information, see [Documentation Changes](/help/r-release-notes/doc-change.md#reference_366123CF00994BACBBF9BBDF2C4D840C).|
|Release notes for previous releases|View information about new features and enhancements in previous releases of Target Standard and Target Premium.<br>For more information, see [Release notes for previous releases](/help/r-release-notes/release-notes-for-previous-releases.md).|
|Adobe Experience Cloud release notes|View the latest release notes for the Adobe Experience Cloud solutions.<br>For more information, see [Experience Cloud Release Notes](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html).|

## Prerelease Information {#section_5D588F0415A2435B851A4D0113ACA3A0}

The following resources let you see what's coming in the next Target release.

|Resource|Details|
|--- |--- |
|Adobe Priority Product Update list|To receive advance notifications about upcoming product enhancements to Target and other Adobe Experience Cloud solutions, sign up for the Adobe Priority Product Update:<br>[https://www.adobe.com/subscription/priority-product-update.html](https://www.adobe.com/subscription/priority-product-update.html)|
|Upcoming release notes|For information about the current month's Target releases, including prerelease information, see the [Target Release Notes - Prerelease](/help/r-release-notes/target-release-notes.md) page.|
