---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 26ff9349ed0c5dc19167e4d21c03f5261f802e73

---


# 提早存取- Adobe Experience Cloud發行說明- 2020年4月

![橫幅](/assets/experience-cloud-banner-3.png)

[!DNL Adobe Experience Cloud] 中的新功能及修正。

>[!IMPORTANT]
>
>此頁面含有搶先版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期:  年 4 月 2020 日**

（特定解決方案的發行日期可能有所不同）。

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面與核心服務](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html) （解決方案說明頁面的連結）
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) （解決方案說明頁面的連結）

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/zh-Hant/experience-cloud/user-guides/home.html)。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

**新功能**

* 使用 Adobe ID 即可訂閱事件通知，並擁有更精細的控制能力，包括可針對產品和附加元件層級選擇所需通知。此外，在我們的最新版本中，自訂程式現在會根據您的產品權益，建議您選擇一系列產品和服務。 這應會減少建立訂閱所需的決策或點按次數，進而簡化訂閱程式，更重要的是，還能在您的收件匣中傳送更相關的通知。 若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 基於權利的個人化訂閱 | <ul><li>根據用戶的DX權限預選的訂閱建議。</li><li>建議的訂閱會在產品清單頂端反白顯示，以便快速視覺化。</li><li>收到的電子郵件通知與使用者的產品權益相關。</li></ul> |
| 更輕鬆地管理訂閱 | <ul><li>**[!UICONTROL 「管理訂閱]** 」有新的使用者體驗，可管理產品和事件訂閱。</li><li>新選項，可分別檢視和編輯產品與事件訂閱。</li><li>「刪 **[!UICONTROL 除]** 」選項可讓您取消訂閱產品或事件訂閱。</li><li>單鍵取消訂 **[!UICONTROL 閱]** ，產品訂閱即可使用。</li><li>UX支援Web/Mobile/Tablet介面，並提供19種語言的本地化。</li></ul> |

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 介面與核心服務 {#ecloud}

Experience Cloud介面中的新功能和修正，包括管理和核心服務（客戶屬性、觀眾、觸發器、Cookie等）:

* Experience Cloud動 [!UICONTROL 態消息] 頁面已過時。 (EXC-8505)
* 已更新Experience Cloud登入頁面，以反映新的品牌元素。 (EXC-10747)

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
* [作法影片](https://docs.adobe.com/content/help/zh-Hant/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services 與 Mobile SDK {#mobile}

Android 4.18.2（2020年4月3日）:

* 應用程式內傳訊：出於安全原因， [!UICONTROL SDK所建立的WebViews] 現在會將屬性 `setAllowFileAccess` 設為 _false_。

iOS 4.19.2（2020年3月24日）:

* 一般：已修正程式碼中的 [!DNL Target] 部分漏洞。

Unity 4.19.0（2020年3月10日）:

* 更新 [!UICONTROL Unity Plugin] ，以使用iOS 4.19.0版和4.18.0版或 [!DNL Android]。
* 公開新的贏取方 [!DNL Android] 法，允許處理反向連結API提 [!DNL Google Play] 供的URL。

### 其他Experience Platform發行資訊

* [Experience Platform Launch發行說明](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)。
* [Experience Platform發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [安全性佈告和諮詢](https://helpx.adobe.com/tw/security.html) (所有 Adobe 產品)

## ![圖示](/assets/analytics.png) [!DNL Analytics] {#analytics}

發行日期: **2020 年 4 月 16 日**

* [Adobe Analytics 的新功能、增強功能和修正項目](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices) (更新日期：2020 年 4 月 7 日)
* [AppMeasurement](#appm)
* [全新Analytics教學課程](#tutorials-analytics)

### Adobe Analytics 的新功能、增強功能和修正項目 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 客戶歷程分析]:自動 [!UICONTROL 化資料集回填] | 此新選項可讓您匯入「客戶歷程分析」中連線的所 [!UICONTROL 有歷史資料]。 （後續檔案） |
| Experience Edge的分 [!UICONTROL 析支援] | 您現在可以將傳送至 [!UICONTROL Experience Edge的資料轉送] 至Analytics。 |
| [!UICONTROL 工作區]:從空白狀態自動建立自由表格 | 以前，您無法直接將元件拖放到空白專案或空白麵板中；您必須先新增自由表格。 您現在可以直接將元件拖放至空白的專案或面板，並會自動以建議的格式為您建立自由表格。 此外，對混合元件類型（例如維度和量度）在一起放入空白自由表格時的處理方式做了改進。 |

#### Analytics修正

* 修正Audience Manager中遺失Analytics區段資料的問題。 (AN-206221)
* 修正Data Sources處理 [!UICONTROL 顯示錯誤日期] 的問題。 (AN-213604)
* 修正分類檔案無法正確上傳至FTP的問題。 (AN-214102)
* 修正API方法未傳回完 `Segments.Get` 整回應的問題。 (AN-206210)
* 修正表格行項目在 [!DNL Workspace] PDF下載中轉換為特殊字元的問題。 (AN-196153)
* 修正Adobe Analytics API 1.4呼叫無法正 `visattrcustomeridcustomerattributes` 常運作的問題。 (AN-186873)
* 修正資料顯示在報表中但在資料饋送中遺失的 [!UICONTROL 問題]。 (AN-211923)
* 修正無法複製產品設定檔權 [!UICONTROL 限的問題] 。 (AN-211113)
* 已修正具有Federated ID的使用者無法登入報告建立工具的問題。 (AN-207750)
* 修正AdWords資料無 [!UICONTROL 法顯示在][!UICONTROL Advertising Analytics中的問題]。 (AN-213249)
* 修正分類資料未顯示在趨勢檢視中的問題。 (AN-212761)
* 修正「區段管理員」中發佈的區段計數不正確 [!UICONTROL 的問題]。 (AN-213374)

#### 其他Analytics修正

AN-212151;AN-214343;AN-215017;AN-115525;AN-123869;AN-101871;AN-152580;AN-160480;AN-199299;AN-209486;AN-212961;AN-211539;AN-213095;AN-212653;AN-211826;AN-206948;AN-208607;AN-204286;AN-214401;AN-212130;AN-211943;AN-212709;AN-212833;AN-211550;AN-212977;AN-213422;AN-213450;AN-214528;AN-213827;AN-214094;AN-214153;AN-214234;AN-214355;AN-214427;AN-214642;AN-214691;AN-214924;AN-215080;AN-215212

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace] | 2020 年 4 月 7 日 | In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. 例如，假設瀏覽的第一次點擊對eVar沒有任何值，但第二次點擊對eVar沒有值。 In [!UICONTROL Reports &amp; Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| **[!UICONTROL 「轉換級別」]**&#x200B;設定確定汰除 | 2020 年 3 月 3 日 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/zh-Hant/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| **[!UICONTROL 控制面板封存]**&#x200B;確定汰除 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，[!UICONTROL Reports &amp; Analytics] 中&#x200B;**[!UICONTROL 「管理控制面板」]**&#x200B;底下的&#x200B;**[!UICONTROL 「檢視封存」]**&#x200B;設定將不再提供使用。 |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 開始移動至新網域 - `https://experience.adobe.com/analytics.`<br>**注意：**凡是使用 Adobe ID 或 Enterprise ID 存取 Analytics 的所有使用者，均適用這項變更。<ul><li>這項網路異動可能會在 Safari 中載入 Analytics 時造成 Cookie 問題。在 「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Analytics 在這個新的 Adobe Experience Cloud 網域中運作。[!DNL Safari]只有 [!DNL Safari] 使用者會受此問題影響，使用其他瀏覽器不會發生問題。</li><li>網域變更可能會導致 [!UICONTROL Activity Map] 在[部分特定情況下](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/activity-map/activity-map.html)停止運作。</li></ul> |
| 終止服務 - Analytics Legacy API | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy Oauth 驗證 (Oauth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy Oauth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 若為倫敦和新加坡的客戶，我們將不再於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間支援資料代理。<br/><ul><li>如果您是在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果您是在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意終止 Ad Hoc Analysis 服務。我們將會在確定後公佈服務終止日期。如需詳細資訊，請造訪[探索 Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。2.20.0 版已於 2020 年 3 月 5 日發行。

### 全新Analytics教學課程 {#tutorials-analytics}

| 內容 | 說明 |
| -----------| ---------- |
| [Adobe Analytics的Adobe Labs（技術預覽）](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs（技術預覽）可讓您與新興技術互動，發掘寶貴的見解，並影響未來的功能 [!DNL Analytics] 開發與優先順序。 |
| [改善的Experience Cloud觀眾發佈](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | 已對 [!UICONTROL Experience Cloud Audience Publishing進行改進]。 您現在可以發佈觀眾（區段），並將其提供速度加快6倍。 這會根據流量和區段大小，將目前的延遲時間從48小時縮短至約8小時，而且可能會更快。 |
| [分析工作區中的多個報表套裝](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | 在單一工作區專案中，您可在面板層級選 [!UICONTROL 取報表套裝] ，以分析多個報表套裝。 這可讓您對不同的資料集進行並排面板分析。 |

如需 [產品檔案，請參閱Adobe Analytics說明首頁](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html) 。

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Adobe Audience Manager中的新功能和修正：

| 功能 | 說明 |
| -----------| ---------- |  
| [主要客戶支援問題](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | 我們在檔案入口網站中新增了一個章節，其中包含客戶支援團隊最常收到的問題解答。 |

* 修正包含行動裝置ID之區段的「可尋 [址對象](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) 」報告不正確的問題。 在此更新後，您可能會看到「可定址對象」 [增加](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html)。
* 修正導致Audience Lab中「重複 [!UICONTROL 測試] 」和「重複配 [!UICONTROL 置範本」按鈕] 無法運作的問題。 (AAM-53388)
* 修正當目標設定為 [!UICONTROL 匯出UUID時，「比對率] 」和「區段可定址對象  」顯示為0的問題。 「比 [!UICONTROL 對率] 」和「 [!UICONTROL 區段可定址對象] 」現在會顯示為100%。 (AAM-51615)
* 修正包含特殊字元的特徵名稱HTML編碼兩次的問題。 (AAM-54001)
* 修正部分使用者無法從使用者介面切換至其他Adobe Experience Cloud解決方案 [!DNL Audience Manager] 的問題。 (AAM-52917)
* 修正部分使用者無法建立SHA256資料來源以供人員型目的地使用的問題。 (AAM-53525)
* 跨介面提供多種協助工具改良功能。 (AAM-48986、AAM-49009、AAM-48984、AAM-48939、AAM-48940、AAM-48964、AAM-49032、AAM-49360)

## ![圖示](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 自助資源

* **AEM電子報**

   請參閱最新 [的Adobe Experience Manager電子報](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)。

* **AEM as a Cloud Service - Configuring Dynamic Media Cloud Service**

   當您設定Dynamic Media Cloud服務時，會提供新選項：

   **選擇性發佈** -當您選取此選項時，表示資產會自動發佈，僅供安全預覽，而且可明確發佈至AEM，而不需發佈至DMS7以便在公共網域中傳送。

   請參 [閱設定動態媒體雲端服務](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)。

* **動態媒體——智慧型影像**

   整個Smart Imaging幫助主題都已更新，其中包含了描述添加的Smart Imaging優化的影像資產示例。

   請參閱 [智慧型影像](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html)。

* **設定動態媒體- Scene7模式**

   「工具>雲端服務」中的「動態媒體設定」頁面現在提供新的「同步所有內 **[!UICONTROL 容」選項]**。

   請參 [閱建立動態媒體設定](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)。

* **AEM Assets品牌入口網站支援AEM Assets作為雲端服務**

   您現在可以將AEM Assets中的資產當做雲端服務發佈至AEM Assets品牌入口網站。

   請參 [閱「使用品牌入口網站設定AEM資產](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) 」 [和「發佈資產至品牌入口網站」](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html)。

* **Adobe Asset Link 2.0已發行**

   Adobe Asset Link 2.0支援與多個AEM環境搭配使用，並支援AEM做為雲端服務。 AEM支援行銷人員在資產使用Adobe Asset Link上傳至檔案夾時，設定資產處理工作流程的自動執行需求。

   See [Adobe Asset Link](https://helpx.adobe.com/tw/enterprise/using/adobe-asset-link.html).

### 全新Experience Manager教學課程

| 內容 | 說明 |
| -----------| ---------- |  
| [設定本地調度器工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | 瞭解如何協助在本機配置、驗證和模 [!UICONTROL 擬Dispatcher] 。 |
| [設定AEM專案的開發工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Adobe Experience Manager(AEM)開發需要在開發人員機器上安裝和設定最少的開發工具集。 這些工具支援AEM Projects的開發與建立。 |
| [設定本機AEM執行階段](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager(AEM)可以使用AEM作為雲端服務SDK的QuickStart Jar在本機 [!UICONTROL 執行]。 這可讓開發人員在將自訂程式碼、組態和內容提交至來源控制項之前，先進行部署和測試，然後將它部署至AEM做為雲端服務環境。 |
| [導覽](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | 探索導覽AEM Assets的基本概念。 |
| [版本](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | 探索AEM如何建立和維護資產版本。 |
| [AEM —— 使用Commerce Integration Framework進行的[!DNL Magento] [!UICONTROL 整合]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | 此影片會逐步帶您瞭解AEM與之間的整合設定 [!DNL Magento]。 |
| [AEM架構堆疊簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF專案原型會建立最小的Adobe Experience Manager(AEM)CIF專案，做為使用CIF核心元件之客戶專案的起點。 |
| [OSGi簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | OSGi簡介，這是Java應用程式的動態模組化架構，是Adobe Experience Manager的基礎。 |
| [Java Content Repository(JCR)簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Adobe Experience Manager使用的[Java內容存放庫(JCR)簡介。 |
| [Sling簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Adobe Experience Manager基 [!DNL Sling]礎技術堆疊的開放原始碼REST風格網頁架構簡介。 |
| [作者與發佈層簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Adobe Experience Manager架構 [!UICONTROL 中Author][!UICONTROL 和Publish] 層簡介。 |
| [Dispatcher簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | 介紹作為AEM架構一部分的Dispatcher的功能和功能。 |
| [元件開發簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | 使用Adobe Experience Manager Sites開發元件的概觀。 包含Dialogs [!UICONTROL 、]Sling Models [!UICONTROL 、]HTL Scripts [!UICONTROL 和]Client-Side Libraries的簡介。 |
| [AEM 專案原型](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEM Project包含實作的所有程式碼和設定。 The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [瞭解核心元件](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL Core Components] 是要與Adobe Experience Manager搭配使用的標準元件。 |
| [使用AEM快速入門](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | 瞭解如何使用 [!UICONTROL AEM Quickstart jar在幾分鐘內安裝及執行Adobe Experience Manager的本機執行個體]。 |

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

### 新的Campaign Standard教學課程 {#tutorials-acs}

| 內容 | 說明 |
| -----------| ---------- |  
| [描述檔替代——使用目標描述檔測試電子郵件訊息](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | 使用描述檔替代功能測試您的電子郵件訊息。 |

### 其他促銷活動說明資源

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

如需詳 [!DNL Marketo] 細資 [訊，請參](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) 閱版本注意事項。

### 即將推出的功能

本季預計推出下列功能：

| 功能 | 說明 |
|------|---------|
| [!DNL Bizible] | <ul><li>全新的帳戶型分段</li><li>儲存控制面板專有的篩選器</li><li>將 Bizible 控制面板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 公告

**Marketo Engage Success Center：**&#x200B;預計於 2020 年 2 月推出。Success Center 是產品內的說明中心，可讓您搜尋產品檔案和社群、啟動操作指南、存取採用內容等等。注意：此功能將會以測試版的形式在澳洲與紐西蘭推出，並預計於本季末在北美地區推出。

### 淘汰

* **資產API &quot;_method&quot;參數：** 在2020年9月之後，資產API端點將不再接受在POST內 `_method` 文中傳遞查詢參數，以略過URI長度限制。
* **Internet Explorer 支援淘汰：**&#x200B;從 2020 年 7 月 31 日推出的七月版開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

如需彙整資料和過往的發行說明，請參閱 [Marketo 發行說明](https://docs.marketo.com/x/CgA6Ag)。
