---
keywords: release notes;releases;updates;future release;enhancements;new features;fixes;updates;prerelease
description: Learn about the new features, enhancements, and fixes included in the upcoming release of Adobe Target, including SDKs, APIs, and JavaScript libraries.
title: What New Features Are Included in the Upcoming Release?
feature: Release Notes
---

# Target release notes (prerelease)

This article contains prerelease information. Release dates, features, and other information are subject to change without notice. 

**Last Updated: January 14, 2021**

To view information about the current release, see [Target Release Notes](release-notes.md). The information on these pages might be the same, depending on the timing of releases. The issue numbers in parentheses are for internal [!DNL Adobe] use.

>[!IMPORTANT]
>
>**mbox.js end-of-life**: On March 31, 2021, [!DNL Adobe Target] will no longer support the mbox.js library. Post March 31, 2021, all calls made from mbox.js will gracefully fail and impact your pages that have [!DNL Target] activities running by serving default content.
>
>We recommend that all customers migrate to the most recent version of the new [!DNL Adobe Experience Platform Web SDK] or the at.js JavaScript library before this date to avoid any potential issues with your sites. For more information, see [Overview: implement Target for client-side web](/help/c-implementing-target/c-implementing-target-for-client-side-web/implement-target-for-client-side-web.md).

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

## Prerelease information {#section_7B9D4AAFC6A74388B9D7DEF0658D8B63} 

To receive advance notifications about upcoming product enhancements to Target and other Adobe Experience Cloud solutions, sign up for the Adobe Priority Product Update:

[https://www.adobe.com/subscription/priority-product-update.html](https://www.adobe.com/subscription/priority-product-update.html) 
