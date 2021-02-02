---
keywords: Release notes;new features;releases;updates;update;release;enhancement;enhancements;fixes;bug fixes;updates
description: What new features are included the current release?
title: Release Notes (Current)
feature: Release Notes
---

# Target release notes (current)

These release notes provide information about features, enhancements, and fixes for each Target Standard and Target Premium release. In addition, release notes for Target APIs, SDKs, the JavaScript library (at.js), and other platform changes are also included, when applicable.

>[!IMPORTANT]
>
>**mbox.js end-of-life**: On March 31, 2021, [!DNL Adobe Target] will no longer support the mbox.js library. Post March 31, 2021, all calls made from mbox.js will gracefully fail and impact your pages that have [!DNL Target] activities running by serving default content.
>
>We recommend that all customers migrate to the most recent version of the new [!DNL Adobe Experience Platform Web SDK] or the at.js JavaScript library before this date to avoid any potential issues with your sites. For more information, see [Overview: implement Target for client-side web](/help/c-implementing-target/c-implementing-target-for-client-side-web/implement-target-for-client-side-web.md).

(The issue numbers in parentheses are for internal [!DNL Adobe] use.)

## Target Standard/Premium 21.1.1 (January 19, 2021)

This maintenance release contains the following enhancements, fixes, and changes.

The issue numbers in parentheses are for internal [!DNL Adobe] use.

* Added a warning when selecting an [!DNL Adobe Analytics] metric when using [!UICONTROL Analytics as the reporting source] (A4T) in an [!UICONTROL Auto-Target] activity. [!UICONTROL Auto-Target] models are optimized to work with binary (conversion-based) metrics. Selecting a continuous metric, such as revenue, might have sub-optimal outcomes and the [!UICONTROL Personalization Insights] reports might not be accurate. (TGT-38926)
* Added a status icon in the [!UICONTROL Auto-Target Summary] report for [!UICONTROL Auto-Target] activities that use A4T. The green check icon next to each experience in the report indicates that a personalized machine-learning model has been generated for that experience. The clock icon indicates that not enough traffic has been served to build the model. (TGT-38925)
* The [!UICONTROL Automated Segments] and [!UICONTROL Important Attributes] reports for [!UICONTROL Auto-Target] activities that use A4T and [!DNL Analytics] conversion metrics are generated and look the same as when using [!DNL Target] as the reporting source. (TGT-38931)
* Added an environment filtering option to the [!UICONTROL Recommendations] [!UICONTROL Collections] list. (TGT-38353)
* Fixed an issue that caused the incorrect product count to display in [!UICONTROL Recommendations] collections. (TGT-39162)
* Added a [!UICONTROL Last Updated] filter to the [!UICONTROL Recommendations] [!UICONTROL Catalog Search]. (TGT-38340)
* Fixed an issue in [!UICONTROL Recommendations] that caused the [!UICONTROL Create Sequence] page to hang after changing the industry vertical. (TGT-38160)
* Fixed an issue that prevented the activity from being saved if Device Co-op was enabled and the user changed from [!DNL Target] as the reporting source to [!DNL Analytics] (A4T). (TGT-38163)
* Fixed an issue that prevented users from removing an audience from an offer in an [!UICONTROL Automated Personalization] (AP) activity. (TGT-39058)
* Fixed an issue that caused the incorrect time frame (start and end dates) to display in [!UICONTROL Audience Info] cards for some customers. (TGT-39150)
* Fixed an issue that prevented some customers from seeing the list of activities in the [!UICONTROL Default Workspace]. (TGT-38526)

## at.js 2.4.0 (January 14, 2021)

This release of at.js is a maintenance release and includes the following fixes:

* Adds support for unified profile/platform id to delivery API customerIds.
* Fixes invalid style tag injection.

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
