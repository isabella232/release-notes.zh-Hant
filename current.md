---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 34940c585feab93f47f7915f4b45fa4a555cd235

---


# 搶先使用 - Adobe Experience Cloud 發行說明 - 2020 年 4 月

![橫幅](/assets/experience-cloud-banner-3.png)

[!DNL Adobe Experience Cloud] 中的新功能及修正。

>[!IMPORTANT]
>
>此頁面含有搶先版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期：2020 年 4 月**

(特定解決方案的發行日期可能不盡相同)

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面與核心服務](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (發&#x200B;**行日期變更——請參閱4月15日的更新**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html) (解決方案說明頁面連結)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) (解決方案說明頁面連結)

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/zh-Hant/experience-cloud/user-guides/home.html)。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

**新功能**

* 使用 Adobe ID 即可訂閱事件通知，並擁有更精細的控制能力，包括可針對產品和附加元件層級選擇所需通知。此外，在我們的最新版本中，自助訂閱程序現在會根據您的產品權限，為您建議一系列產品和服務選項。這項功能可減少確定訂閱所需的決策或點擊次數，進而簡化訂閱程序，更重要的是，此功能會傳送更符合需求的通知到您的收件匣。若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 依權限提供個人化訂閱 | <ul><li>根據使用者的 DX 權限預先選取訂閱建議。</li><li>建議訂閱項目會醒目顯示在產品清單頂端，以便快速掌握重點。</li><li>使用者收到的電子郵件通知會更切合自己的產品權限。</li></ul> |
| 管理訂閱項目更輕鬆 | <ul><li>**[!UICONTROL 「管理訂閱」]**&#x200B;提供新的使用者體驗，可同時管理產品和事件訂閱。</li><li>使用者可利用新選項分別檢視與編輯產品和事件訂閱。</li><li>**[!UICONTROL 「刪除」]**&#x200B;選項可讓您取消訂閱產品或事件訂閱項目。</li><li>產品訂閱項目皆提供一鍵式&#x200B;**[!UICONTROL 「全部取消訂閱」]**&#x200B;選項。</li><li>網頁/行動裝置/平板電腦介面配備 UX 支援，且提供 19 種語言版本。</li></ul> |

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 介面與核心服務 {#ecloud}

Experience Cloud 介面新增功能並修正錯誤，包括管理和核心服務 (客戶屬性、對象、觸發器、Cookie 等)：

* 淘汰 Experience Cloud[!UICONTROL 「摘要」]頁面。(EXC-8505)
* Experience Cloud 登入頁面更新，反映新的品牌元素。(EXC-10747)

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html) 說明。

### 統一產品網域

Adobe 正在更新網域和介面標題，以統一及提升您在所有 Experience Cloud 應用程式中的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會變更您目前的工作流程。

更新包括：

* 新解決方案 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * 瀏覽器支援：支援的瀏覽器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera] (最新版本)。**注意：**&#x200B;雖然 Experience Cloud 介面可支援這些瀏覽器，但個別解決方案可能不會支援所有瀏覽器(例如 [Analytics](https://docs.adobe.com/content/help/zh-Hant/analytics/admin/sys-reqs.translate.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hant/target/using/implement-target/before-implement/supported-browsers.translate.html) 不支援 [!DNL Safari])。
   * (僅限 [!DNL Safari]) 網域變更可能導致 [!DNL Safari] 發生 Cookie 問題。在 [!DNL Safari] 的「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Experience Cloud 在這個新的網域中運作。
* 在組織或不同應用程式之間更輕鬆地切換。
* 改良產品說明：[!UICONTROL Experience League] 已整合至產品中，因此搜尋說明內容時，搜尋範圍會包含社群論壇和影片內容。這項變更可讓您輕鬆存取更多內容，協助您充份運用 Experience Cloud。此外，按一下&#x200B;**[!UICONTROL 「說明]** > **[!UICONTROL 意見回饋」]**&#x200B;即可回報問題，或與 Adobe 分享您的想法。

## ![圖示](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!UICONTROL Experience Platform]、[!UICONTROL Experience Platform Launch]、[!UICONTROL 身分服務]、Journey Orchestration、Mobile Services 和安全性佈告欄的發行說明。

### 歷程協調 {#journey}

不論客戶處於哪個歷程階段，Adobe Experience Platform 能聰明地即時預測每個人的需求，以便能大規模協調不同體驗管道的客戶歷程。

* [文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html)
* [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html)
* [作法影片](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services 與 Mobile SDK {#mobile}

Android 4.18.2 (2020 年 4 月 3 日)：

* 應用程式內傳訊：基於安全考量，SDK 建立的 [!UICONTROL WebViews] 現在會將屬性 `setAllowFileAccess` 設為等同於 _false_。

iOS 4.19.2 (2020 年 3 月 24 日)：

* 一般：修正 [!DNL Target] 程式碼中的部分漏洞。

iOS 4.19.0 (2020 年 3 月 10 日)：

* [!UICONTROL Unity Plugin] 更新為使用 iOS 4.19.0 版和 4.18.0 版或 [!DNL Android]。
* 推出新的 [!DNL Android] 擷取方法，允許處理 [!DNL Google Play] 反向連結 API 提供的 URL。

### 其他 Experience Platform 發行資訊

* [Experience Platform Launch 發行說明](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)
* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [安全性佈告和諮詢](https://helpx.adobe.com/tw/security.html) (所有 Adobe 產品)

## ![圖示](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>Adobe Analytics 4月維護髮行已移至2020年5月21日。 如需最新的Analytics發行資訊，請參閱3 [月發行說明](c-legacy-releases\2020\03122020.md)

<!-- * [New features, enhancements, and fixes in Adobe Analytics](#aa-features)
* [Important notices for Analytics administrators](#aa-notices) (Updated April 7, 2020)
* [AppMeasurement](#appm) -->

* [客戶歷程分析](#cust-journey)
* [全新 Analytics 教學課程](#tutorials-analytics)

<!-- ### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
|[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212

### Important notices for [!DNL Analytics] administrators {#aa-notices}

| Notice | Date Added or Updated  | Description |
| -----------| ---------- | ---------- |
|Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace]|April 7, 2020|In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. For example, assume the first hit of a visit has no value for eVars, but the second hit does. In [!UICONTROL Reports & Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit.|
|EOL of **[!UICONTROL Conversion Level]** setting|March 3, 2020|The non-functioning [Conversion Level](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] will no longer be available as of October, 2020.|
|End of Support for TLS 1.1 | October 3, 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data.|
|New Adobe Analytics domain|Dec. 18, 2019|On January 16, 2020, Adobe Analytics began moving to a new domain - `https://experience.adobe.com/analytics.`<br>**Note:** This change applies to all users accessing Analytics with their Adobe ID or Enterprise ID. <ul><li>The domain change may cause cookie issues when loading Analytics in Safari. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>The domain change may cause [!UICONTROL Activity Map] to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul>|
|End of Life - Analytics Legacy APIs|January 9, 2020|In November 2020, the following Analytics Legacy API services will reach their end-of-life and will be shutdown. Current integrations built using these services will stop working. <ul><li>1.3 Analytics APIs</li><li>1.4 SOAP Analytics APIs</li><li>Legacy OAuth Authentication (OAuth and JWT)</li></ul>We have provided a [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) to help answer your questions and provide guidance on how to proceed. API integrations that employ these services can migrate to the [1.4 Analytics REST APIs](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) or the [2.0 Analytics APIs](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth accounts can migrate to an [Adobe IO](https://console.adobe.io/home?mv=email) Analytics integration account, which can be used to access both the 1.4 Analytics APIs and 2.0 Analytics APIs.|
|San Jose FTP Broker Ending for London and Singapore|July 2020|For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL of Ad Hoc Analysis|Aug 6, 2018|Adobe announced the intention to end-of-life Ad Hoc Analysis. An end-of-life date will be shared once available. For more information, visit [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

See [AppMeasurement for Javascript release notes](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 was released on March 5, 2020. -->

### 客戶歷程分析 {#cust-journey}

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]：[!UICONTROL 自動化資料集回填] | 此新選項可讓您將連線的所有歷史資料匯入 [!UICONTROL Customer Journey Analytics]。(後續文件) |

### 全新 Analytics 教學課程{#tutorials-analytics}

| 內容 | 說明 |
| -----------| ---------- |
| [Adobe Analytics 開始提供 Adobe Labs (技術預覽)](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs (技術預覽) 可讓您與新興技術互動，發掘有價值的深入分析，並影響未來的 [!DNL Analytics] 功能開發與上線順序。 |
| [Experience Cloud 對象發佈功能改良](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | [!UICONTROL Experience Cloud 對象發佈]功能已經過改良。現在發佈對象 (區段) 後，能以 6 倍速度提供使用。這項改良會根據流量和區段大小，將延遲時間從目前的 48 小時縮短至 8 小時左右，甚至可能更快。 |
| [Analysis Workspace 提供多個報表套裝](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | 您可以在面板層級選取多個報表套裝，於同一個 [!UICONTROL Workspace] 專案中分析多個報表套裝。這項功能可讓您在不同資料集之間執行並排式的面板分析。 |

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)。

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Adobe Audience Manager 的新功能和修正項目：

| 功能 | 說明 |
| -----------| ---------- |  
| [主要客戶支援問題](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | 我們在檔案入口網站中新增了一個章節，其中包含客戶支援團隊最常收到的問題解答。 |

* 修正包含行動裝置ID之區段的「可尋 [址對象](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) 」報告不正確的問題。 在此更新後，您可能會看到「可定址對象」 [增加](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html)。
* 修正 [!UICONTROL Audience Lab] 中[!UICONTROL 「重複測試」]和[!UICONTROL 「重複配置範本」]按鈕無法運作的問題。(AAM-53388)
* 修正當目標設定為匯出 UUID 時，[!UICONTROL 「比對率 」]和[!UICONTROL 「區段可定址對象」]顯示為 0 的問題。[!UICONTROL 「比對率」]和[!UICONTROL 「區段可定址對象」]現在已顯示為 100%。(AAM-51615)
* 修正含有特殊字元的特徵名稱會經過兩次 HTML 編碼的問題。(AAM-54001)
* 修正部分使用者無法從 [!DNL Audience Manager] 使用者介面切換至其他 Adobe Experience Cloud 解決方案的問題。(AAM-52917)
* 修正部分使用者無法為以人員為根據的目的地建立 SHA256 資料來源的問題。(AAM-53525)
* 整個介面的協助工具有多處改良。(AAM-48986、AAM-49009、AAM-48984、AAM-48939、AAM-48940、AAM-48964、AAM-49032、AAM-49360)

## ![圖示](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 自助資源

* **AEM 電子報**

   請參閱最新的 [Adobe Experience Manager 電子報](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)。

* **AEM 雲端服務 - 設定 Dynamic Media 雲端服務**

   設定 Dynamic Media 雲端服務時，有新選項可用：

   **選擇性發佈** - 選取此選項，表示資產會自動發佈，但僅供安全預覽，而且可明確發佈至 AEM，不需發佈到 DMS7 再傳遞至公共網域。

   請參閱[設定 Dynamic Media 雲端服務](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)。

* **Dynamic Media - 智慧影像處理**

   整個智慧影像處理說明主題均已更新為全新資訊，其中包含示範智慧影像處理最佳化新功能的影像資產範例。

   請參閱[智慧影像處理](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/dynamic/imaging-faq.html)。

* **設定 Dynamic Media - Scene7 模式**

   **[!UICONTROL 「工具 > 雲端服務」]**&#x200B;中的「Dynamic Media 設定」頁面現在新增「同步所有內容」選項。

   請參閱[建立 Dynamic Media 設定](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)。

* **AEM Assets Brand Portal 支援 AEM Assets 雲端服務**

   您現在可以將 AEM Assets 雲端服務中的資產發佈至 AEM Assets Brand Portal。

   請參閱[使用 Brand Portal 設定 AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) 和[將資產發佈到 Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html)。

* **Adobe Asset Link 2.0 正式發行**

   Adobe Asset Link 2.0 支援與多種 AEM 環境搭配使用，亦支援 AEM 雲端服務。資產經由 Adobe Asset Link 上傳至檔案夾後，AEM 可支援行銷人員設定資產處理工作流程的自動執行需求。

   請參閱 [Adobe Asset Link](https://helpx.adobe.com/tw/enterprise/using/adobe-asset-link.html)。

### 全新 Experience Manager 教學課程

| 內容 | 說明 |
| -----------| ---------- |  
| [設定本機 Dispatcher 工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | 了解如何加速本機設定、驗證和模擬 [!UICONTROL Dispatcher] 等作業。 |
| [設定 AEM 專案的開發工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | 展開 Adobe Experience Manager (AEM) 的開發作業前，開發人員的電腦上需先安裝與設定一套簡單的開發工具。這些工具可支援 AEM 專案的開發與建立作業。 |
| [設定本機 AEM 執行階段](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) 可透過 AEM 雲端服務 SDK 的 [!UICONTROL QuickStart Jar] 在本機上執行。如此一來，開發人員就能在將自訂程式碼、設定和內容送交來源控制項前，先行部署和測試，然後再部署至 AEM 雲端服務環境。 |
| [導覽](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | 說明 AEM Assets 導覽的基本概念。 |
| [版本](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | 說明 AEM 如何建立和維護資產版本。 |
| [AEM - 透過 [!UICONTROL Commerce Integration Framework] 整合 [!DNL Magento] ](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | 這部影片會帶您逐步了解 AEM 與 [!DNL Magento] 之間的整合設定。 |
| [AEM 架構堆疊簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF 專案原型會建立簡單的 Adobe Experience Manager (AEM) CIF 專案，作為客戶專案的起點。 |
| [OSGi 簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | 介紹 Java 應用程式動態模組化架構 OSGi，此架構是 Adobe Experience Manager 的建置基礎。 |
| [Java Content Repository (JCR) 簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | 介紹 Adobe Experience Manager 所採用的 Java Content Repository (JCR)。 |
| [Sling 簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | 介紹開放原始碼 RESTful Web 架構的 [!DNL Sling]，此架構隸屬於 Adobe Experience Manager 基礎技術堆疊的一部分。 |
| [「作者」與「發佈」階層簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | 介紹 Adobe Experience Manager 架構中的[!UICONTROL 「作者」]和[!UICONTROL 「發佈」]階層。 |
| [Dispatcher 簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | 介紹 AEM 架構中 Dispatcher 的功能和特性。 |
| [元件開發簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | 概述如何以 Adobe Experience Manager Site 開發元件，內容包括[!UICONTROL 對話方塊]、[!UICONTROL Sling 模型]、[!UICONTROL HTL 指令碼]和[!UICONTROL 用戶端資料庫]的相關簡介。 |
| [AEM 專案原型](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEM 專案包含實作所需的所有程式碼和設定。AEM [!UICONTROL 專案原型]會依最佳作法建立簡化的 Adobe Experience Manager 專案，作為您專屬 AEM 專案的開端。 |
| [了解核心元件](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL 核心元件]是與 Adobe Experience Manager 搭配使用的標準元件。 |
| [使用 AEM Quickstart Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | 了解如何使用 [!UICONTROL AEM Quickstart Jar] 快速安裝，並執行 Adobe Experience Manager 的本機執行個體。 |

### 其他說明資源

* [AEM 雲端服務](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)
* [AEM 6.4 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-4.html)
* [AEM 6.3 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-3.html)
* [AEM 6.2 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/tw/experience-manager/cloud-manager/user-guide.html)
* [舊版 AEM 文件](https://helpx.adobe.com/tw/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/zh_TW/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![圖示](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html)

### 全新 Campaign Standard 教學課程 {#tutorials-acs}

| 內容 | 說明 |
| -----------| ---------- |  
| [設定檔替代 - 使用目標設定檔測試電子郵件訊息](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | 使用「設定檔替代」功能測試電子郵件訊息。 |

### 其他 Campaign 說明資源

* Adobe Campaign Standard：[文件](https://helpx.adobe.com/tw/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/tw/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文件](https://helpx.adobe.com/tw/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![圖示](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是銷售機會管理的完整解決方案，也適合 B2B 行銷人員使用，而透過該解決方案，他們可參與複雜購買歷程的每個階段，從中轉變客戶體驗。

### Marketo Engage 核心更新

如需詳細資訊，請參閱 [!DNL Marketo] [發行說明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)。

### 即將推出的功能

本季預計推出下列功能：

| 功能 | 說明 |
|------|---------|
| [!DNL Bizible] | <ul><li>全新的帳戶型分段</li><li>儲存控制面板專有的篩選器</li><li>將 Bizible 控制面板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 公告

**Marketo Engage Success Center：**&#x200B;預計於 2020 年 2 月推出。Success Center 是產品內的說明中心，可讓您搜尋產品檔案和社群、啟動操作指南、存取採用內容等等。注意：此功能將會以測試版的形式在澳洲與紐西蘭推出，並預計於本季末在北美地區推出。

### 淘汰

* **資產 API「_method」參數：** 2020 年 9 月後，資產 API 端點將不再接受於 POST 主體中使用 `_method` 傳遞查詢參數，以略過 URI 長度限制。
* **Internet Explorer 支援淘汰：**&#x200B;從 2020 年 7 月 31 日推出的七月版開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

如需彙整資料和過往的發行說明，請參閱 [Marketo 發行說明](https://docs.marketo.com/x/CgA6Ag)。
