---
title: Adobe Experience Cloud 發行說明
description: Adobe Experience Cloud 發行說明
doc-type: release notes
last-update: July 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 079138eeaeb4a61ab892abaff66b15d51b751bf4
workflow-type: tm+mt
source-wordcount: '4321'
ht-degree: 58%

---


# 提早存取- Adobe Experience Cloud發行說明- 2020年7月

![橫幅](/assets/experience-cloud-banner-3.png)

此頁面主要說明 [!DNL Adobe Experience Cloud] 的新功能、修正項目和重要注意事項。此外還有最新文件、訓練課程和教學課程影片，協助您充份運用 Experience Cloud。

>[!IMPORTANT]
>
>此頁面含有搶先版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>訂閱 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。

**發行日期: 2020 年 7 月 16 日**

產品的發行日期可能不盡相同。請時常回訪以取得更新內容。

最新更新： **2020年7月13日**

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [客戶歷程分析](#cust-journey) （2020年7月13日更新）
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [行銷活動](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) (Primetime 說明頁面連結)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

發行日期：**2020 年 5 月 21 日**

**新功能**

* 使用 Adobe ID 即可訂閱事件通知，並擁有更精細的控制能力，包括可針對產品和附加元件層級選擇所需通知。為協助您縮短設定訂閱的時間，自助訂閱程序現在會根據您的產品權限，為您建議一系列產品和服務項目。這樣應可減少您收到的電子郵件數量，您的收件匣將會收到與您更切身相關的通知。若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 更理想的訂閱和使用者通知體驗 | <ul><li>系統現在會根據您所選取的產品清單，篩選 [!DNL Marketo Engage] 區域位置。</li><li>[!DNL Marketo Engage] 電子郵件通知與使用者的地區、位置和環境偏好設定相關。</li></ul> |
| 事件訂閱確認 | <ul><li>現在訂閱進行中的單一事件更新時，會收到電子郵件確認。</li></ul> |
| 全域導覽可用性增強功能 | <ul><li>頂層導覽功能表提供與 `Adobe.com` 一致的使用者體驗。</li></ul> |

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 介面 {#ecloud}

Experience Cloud 介面的一般更新。

**更新的介面選單**

在Experience Cloud中，2020年7 **月16日發行** ，會更新「應用程式切換器」下拉式選單。 它已簡化，因此解決方案標誌已移除，而功能表只會顯示您可存取的應用程式和服務。

如需範例，請參 [閱Experience Cloud介面產品檔案](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html) 。

**統一產品網域**

Adobe 持續更新網域和介面標題，以統一及提升您使用所有 Experience Cloud 應用程式的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會改變目前的工作流程。

更新包括：

* 新應用程式 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * 瀏覽器支援：支援的瀏覽器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera] (最新版本)。**注意：**&#x200B;雖然 Experience Cloud 介面可支援這些瀏覽器，但個別解決方案可能不會支援所有瀏覽器。(例如 [Analytics](https://docs.adobe.com/content/help/zh-Hant/analytics/admin/sys-reqs.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hant/target/using/implement-target/before-implement/supported-browsers.html) 不支援 [!DNL Safari])。
   * (僅限 [!DNL Safari]) 網域變更可能導致 [!DNL Safari] 發生 Cookie 問題。在 [!DNL Safari] 的「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Experience Cloud 在這個新的網域中運作。
* 在不同組織或應用程式之間更輕鬆地切換。
* 改良產品說明：[!UICONTROL Experience League] 已整合至產品中，因此搜尋說明內容時，搜尋範圍會包含社群論壇和影片內容。這項變更可讓您輕鬆存取更多內容，協助您充份運用 Experience Cloud。此外，按一下&#x200B;**[!UICONTROL 「說明]** > **[!UICONTROL 意見回饋」]**&#x200B;即可回報問題，或與 Adobe 分享您的想法。

下列應用程式會使用新的 experience.adobe.com 網域：

| 應用程式或服務 | 網域 |
| -----------| ---------- |
| Experience Cloud 首頁 | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| 歷程管理 | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 控制面板 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| 管理工具 (測試版) | `experience.adobe.com/admin` |

>[!NOTE]
>
>[!UICONTROL Marketing Cloud Assets] 選取器中的舊版篩選器&#x200B;**[!UICONTROL 「展示板和系列」]**&#x200B;即將終止服務。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

[!DNL Experience Platform] 和應用程式服務的發行說明，內容包括 [!DNL Experience Platform Launch,] [!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services]、安全性公告。

Latest release date: **June 10, 2020**

如需 [Experience Platform的最新資訊](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) ，請參閱Experience Platform發行說明。

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

不論客戶處於哪個歷程階段，Adobe Experience Platform 均可聰明地即時預測每個人的需求，以便大規模協調不同體驗管道的客戶歷程。

### Journey Orchestration 的其他資源

[文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期: **2020 年 7 月 16 日**

* [Adobe Analytics 的新功能](#aa-features)
* [Customer Journey Analytics 的新功能](#cust-journey)
* [Media Analytics 的新功能](#media-aa)
* [Adobe Analytics 的修正項目](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices) (更新日期：2020 年 7 月 13 日)
* [最新 Adobe Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 的新功能 {#aa-features}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| -----------| ---------- |-------|
| 工作區： 新的日期範圍預設集 | 新增4個新的日期範圍(_本週／月/季／年_ （除今天外）)，讓使用者可以從不包含今天部分日期資料的日期範圍中選擇。 |
| 資料修復API —— 公開測試版 | 「資料修復API」提供自助選項，讓客戶刪除Adobe Analytics資料的欄。 發行公開測試版後，API將支援刪除Activity Map資料。 稍後將推出其他功能。 請連絡客戶服務以取得此API的存取權。 |

### Customer Journey Analytics 的新功能 {#cust-journey}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| -----------| ---------- |-----|
| 本月無新功能 |  |  |

### [!UICONTROL Media Analytics] 的新功能{#media-aa}

更新日期： **2020年7月16日**

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| -----------| ---------- | ---------- |
| [支援的裝置和平台](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/supported-devices.html) | 2020 年 6 月 18 日 | 含 AEP SDK 的 Media Launch 擴充功能現在支援下列 OTT 裝置：<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [支援的裝置和平台](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/supported-devices.html) | 2020 年 6 月 18 日 | 含 AEP SDK 的 Media Launch 擴充功能現在支援下列 OTT 裝置：<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [播放器狀態追蹤](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/player-state-tracking/player-state-overview.html) | 2020 年 5 月 29 日 | [!UICONTROL Media Analytics] 客戶可使用全螢幕、隱藏式字幕、靜音、子母畫面和觀看中的標準解決方案變數集，擷取檢視者在播放時的互動。您也可以彈性建立自訂播放器狀態。「播放器狀態追蹤」變數現在可用於 [!UICONTROL Analysis Workspace] 中的報告。此功能需有下列任一個項目： <ul><li>Media [!DNL JavaScript] SDK 3.0 或更新版本</li><li>與 [!DNL Adobe Experience Platform] (AEP) SDK 搭配使用：</li><li>[!UICONTROL Media Analytics 擴充功能] (適用於網頁)：[!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 或更新版本</li><li>[!UICONTROL Media Analytics 擴充功能] (適用於行動裝置)：[!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 或更新版本</li><li>[!UICONTROL 媒體收集]</li></ul> |

### Adobe Analytics 的修正項目 {#aa-fixes}

* 修正切換至使用不同貨幣的報表套裝後所發生的問題。 工 [!UICONTROL 作區] 折線圖未反映正確貨幣。 (AN-216655)
* 已修正下載PDF中無法閱讀視覺化的問題。 (AN-217949)
* 修正將階層變數新增至報表套裝時發生錯誤的問題。 (AN-211974)
* 修正編輯與報表套裝關聯的資料饋送時，與目前選取的報表套裝時區不同的 [!UICONTROL 問題] 。 (AN-222474)
* 修正「分類規則產生 [!UICONTROL 器」無法運作] 的問題。 (AN-219662)
* 修正分類和分類規則的多個問題。 (AN-223492、AN-220654、AN-219662、AN-223260)
* 修正相同區段在虛擬報表套裝中傳回與父報表套裝不同資料的問題。 (AN-201074)
* 修正無法下載報表套裝設定的問題。 (AN-223690)
* 修正「智慧型警 [!UICONTROL 報」中] ,「選擇退出此排 __ 程」電子郵件連結無法運作的問題。 (AN-223875)
* 修正虛擬報表套裝顯示錯誤貨幣的問題。 (AN-224781)
* 修正虛擬報表套 _裝中遺失元件_ 錯誤的問題。 (AN-224782)
* 修正當與具有參與率配置集的計算量度搭配使用時，將維度分類劃分為另一個維度可能會傳回空白結果的問題。 (AN-214089)

#### 其他 Adobe Analytics 修正項目

AN-222672、AN-222813; AN-222892; AN-223272,AN-223432; AN-224062; AN-224108; AN-224163; AN-224339; AN-224456; AN-224449; AN-224552; AN-224553; AN-224786

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| Adobe Data Connectors的EOL | 2020 年 7 月 13 日 | Adobe Data Connectors採用已不再可行或不受支援的舊式技術。 我們在 [Adobe Exchange合作夥伴計畫中有一項新標準](https://partners.adobe.com/exchangeprogram/experiencecloud) ，對於任何希望繼續提供和支援的整合，都應採用此標準。 正式的終止日期仍有待確定，但我們預計未來12-18個月（2021年中至2021年底）將終止。 [更多詳情...](https://docs.adobe.com/content/help/en/analytics/import/dataconnectors/data-connectors-eol.html) |
| 報表套裝對應至IMS組織 | 2020 年 7 月 | 報表套裝對應工具將於2020年11月中止。 此功能可促進整合，例如Adobe Analytics中的Advertising Analytics和Experience Cloud細分發佈。 報表套裝必須對應至IMS組織，才能啟用這些和其他服務。 較新的報表套裝會在建立時自動對應。 不過，舊版報表套裝必須手動對應至IMS組織。 請參 [閱核心服務使用指南中的](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/about-core-services/report-suite-mapping.html) 「將報表套裝對應至組織」，以確定所有報表套裝都屬於IMS組織。 |
| 移轉至統一的產品網域 | 生效日期：2020 年 5 月 28 日 | 從 2020 年 1 月開始，Adobe Analytics 就開始移轉至統一的產品網域，相關作業已於 2020 年 5 月 28 日完成。雖然 Adobe Analytics 已著手從架構中移除所有 `omniture.com` 網域參考，但請務必將 `omniture.com` 放入協力廠商 Cookie 允許清單。完整架構即將移轉完成，作業完成後我們會透過發行說明通知您，到時您就不需再執行此允許清單步驟。請參閱這份建議 IP 位址和網域的[完整清單](https://helpx.adobe.com/tw/analytics/kb/adobe-ip-addresses.html)，這些位址和網域均應列入允許清單。<br>如果貴組織封鎖第三方 Cookie，請洽詢客戶服務人員，以重新取得 Adobe Analytics 的存取權限。 |
| 全新 Adobe Analytics 預設登陸頁面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日起，Adobe Analytics 的預設登陸頁面將從[!UICONTROL 報告]變更為[!UICONTROL 工作區]。未設定自訂登陸頁面的使用者，將一律適用此變更。 |
| 協力廠商技術允許清單 | 2020 年 3 月 12 日 (生效日期) | Adobe Analytics 已開始運用協力廠商技術進行功能推出管理和產品內支援。下列 URL 應新增至任何必要的網路防火牆允許清單，確保完整的功能存取權限：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| 改善 [!UICONTROL Analysis Workspace] 可用性的備援 | 2020 年 5 月 21 日 | 為確保 [!UICONTROL Analysis Workspace] 的可用性，我們新增次要 CDN (內容傳遞網路) 以改善備援。應將下列 URL 新增至任何必要的網路防火牆允許清單：<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| 變更[!UICONTROL 工作區]計算[!UICONTROL 輸入/結束]次數的方式 | 2020 年 4 月 7 日 | 自 2020 年 3 月起，[!UICONTROL Analysis Workspace] 已變更&#x200B;_「無」_&#x200B;值與[!UICONTROL 輸入/結束]動作的互動方式。由於您現在可以在 [!UICONTROL Analysis Workspace] 中開啟或關閉&#x200B;_「無」_，因此我們會在使用者輸入或結束後套用&#x200B;_「無」_，但 (eVars) 以往都是在輸入或結束之前就先套用。例如，假設造訪事件的第一次點擊未輸入 eVars 的值，但第二次點擊則有輸入。在 [!UICONTROL Reports &amp; Analytics] 中，第一次點擊的輸入會顯示為&#x200B;_「未指定」_，但在 [!UICONTROL Analysis Workspace] 中則會顯示第二次點擊的值。 |
| **[!UICONTROL 控制面板封存]**&#x200B;確定汰除 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，[!UICONTROL Reports &amp; Analytics] 中&#x200B;**[!UICONTROL 「管理控制面板」]**&#x200B;底下的&#x200B;**[!UICONTROL 「檢視封存」]**&#x200B;設定將不再提供使用。 |
| Analytics舊版API的EOL | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy OAuth 驗證 (OAuth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問題集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy OAuth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 若為倫敦和新加坡的客戶，我們將不再於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間支援資料代理。<br/><ul><li>如果您是在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果您是在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意終止 Ad Hoc Analysis 服務。我們將會在確定後公佈服務終止日期。如需詳細資訊，請造訪[探索工作區](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

#### AppMeasurement

如需 AppMeasurement 發行的最新消息，請參閱[適用於 JavaScript 的 AppMeasurement 發行說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。

#### Analytics 說明資源

* [Adobe Analytics 教學課程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 產品文件](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)

## ![圖示](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 的新功能、修正項目、說明文件和教學課程。

發行日期: **2020 年 7 月 16 日**

### Adobe Audience Manager 的新功能和修正項目

* 修正客戶無法將部分區段對應至Amazon目的地的問題。 (AAM-54373)
* 修正當客戶在新標籤中開啟區段時，瀏覽器畫面會凍結的問題。 (AAM-55213)
* 修正「上線狀 [態報表」中](https://docs.adobe.com/help/en/audience-manager/user-guide/reporting/onboarding-status-report.html)，客戶在按一下圖表中的橫條時，會看到日期與表格中的日期不符的問題。 (AAM-55235)
* 修正「管理」區段中，當客戶嘗試刪除使用者時，使用者介面會顯示錯誤圖示，而非確認訊息的錯誤。 (AAM-55186)
* 修正Swagger API的問題，此 `x-api-key` 問題不會將標題新增至捲動請求。 (AAM-55392)
* 改進在目標檢視中對應至目標之區段的預設排序順序。 現在，已映射的區段會依區段對應的開始日期，接著依區段ID排序。 (AAM-38494)
* 整個介面的協助工具有多處改良。(AAM-48956、AAM-49012、AAM-49364、AAM-49363、AAM-49374、AAM-49579、AAM-55037).

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品更新

* **Dynamic Media Classic**

   Dynamic Media Classic使用者現在可以存取新的案頭應用程式體驗，而不再依賴瀏覽器的Adobe Flash技術。 此新應用程式現已針對Windows和macOS提供。

   請參 [閱Adobe Dynamic Media Classic案頭應用程式——現已推出。](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/new-ui-2020.html)

* **新增3D資產支援至動態媒體**

   AEM 6.5和AEM中的Dynamic Media（雲端服務）現在可讓您上傳、管理、檢視和傳遞3D資產，成為身歷其境的體驗。

   * 在AEM as a Cloud Service，請參閱「在 [動態媒體中使用3D資產」。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/assets-3d.html)
   * In AEM 6.5, see [Working with 3D assets in Dynamic Media.](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/assets-3d.html)

### 自助資源

* **AEM 6.5.5 Forms檔案更新**

   * 6.5.5版中的新功能和改進：

      * [自訂Adobe Experience Manager「收件匣」欄](https://docs.adobe.com/content/help/en/experience-manager-65/authoring/essentials/inbox.html#inbox-admin-control)。
      * [將互動式通訊儲存為草稿。](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#save-as-draft)
      * Oracle WebLogic應用程式伺服器支援 [單台伺服器](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-single-server.pdf)[和群集安裝](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-cluster.pdf) 。
      * [改善協助工具.](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#accessibility-improvements)
      * [X-509憑證式驗證，適用於表單資料模型中以SOAP為基礎的Web服務。](https://docs.adobe.com/content/help/en/experience-manager-65/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Oracle RAC支援。](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#other-improvements)
      * [已改善交易報告中的錯誤記錄。](https://docs.adobe.com/content/help/en/experience-manager-65/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)
   * 6.4.8.1版中的新功能和改進：
      * [X-509憑證式驗證，適用於表單資料模型中以SOAP為基礎的Web服務。](https://docs.adobe.com/content/help/en/experience-manager-64/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [已改善交易報告中的錯誤記錄。](https://docs.adobe.com/content/help/en/experience-manager-64/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)

### **社群**

* **AEM 社群討論**

   現在起，您可以集中檢視所有 AEM 公告，以及有趣的內部和外部部落客參考資訊。請參閱 AEM 社群的[「討論」區段](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)。

### 最新 Experience Manager 課程與教學課程 

過去一個月內發佈的新視訊、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 6 月 25 日 | [最適化表單快速入門](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/creating-your-first-adaptive-form/adaptive-forms-getting-started-tutorial-use.html) | 影片 | 這些教學課程會逐步引導您完成建立多標籤式最適化表單的相關步驟。 瞭解如何使用表格、accordion版面配置和規則編輯器來編寫業務規則。 |
| 2020 年 6 月 25 日 | [在AEM Forms中建立審核工作流程](https://video.tv.adobe.com/v/35821/quality=9?captions=chi_hant) | 影片 | 瞭解如何建立從作用中表單提交來審核提交資料的工作流程。 |
| 2020 年 6 月 23 日 | [處理設定檔](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/processing-profiles.html) | 影片 | 處理設定檔會將要在AEM中為資產建立的轉譯定義為Cloud Service。 |
| 2020 年 6 月 23 日 | [Dynamic Media Classic最佳實務](https://docs.adobe.com/content/help/en/experience-manager-learn/dynamic-media-classic-tutorial/overview.html) | 文章 | 目前和新使用者可以瞭解Dynamic Media Classic、其核心功能，以及 _建立_、 _製作_&#x200B;和傳 _送工作_ 流程。 |
| 2020 年 6 月 23 日 | [將AEM除錯為雲端服務建立與部署](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/build-and-deployment.html) | 文章 | 瞭解如何對AEM的建置和部署進行除錯(Cloud Service)。 |
| 2020 年 6 月 16 日 | [使用記錄將AEM除錯為雲端服務](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/logs.html) | 文章 | 瞭解如何使用記錄檔將AEM除錯為雲端服務。 記錄檔是除錯AEM應用程式的前線，但需視部署的AEM應用程式中的適當登入而定。 |
| 2020 年 6 月 10 日 | [搭配AEM資產使用動態媒體3D](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-3d-feature-video.html) | 影片 | Adobe Experience Manager的動態媒體3D支援可讓您輕鬆自訂並大規模提供互動式3D架構體驗。 |
| 2020 年 6 月 5 日 | [SPA編輯器項目](https://docs.adobe.com/content/help/en/experience-manager-learn/spa-react-tutorial/create-project.html) | 文章 | 瞭解如何使用Adobe Experience Manager(AEM)Project原型來產生多模組Maven專案，做為與AEM SPA編輯器整合之React應用程式的起點。 |
| 2020 年 6 月 3 日 | [處理HTML5表單提交——教學課程](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/html5-forms/handle-mobile-form-submission.html) | 文章 | 瞭解如何在自訂提交處理常式中存取已提交的資料。 |

### Experience Manager發行資訊

所有Experience Manager發行說明都會保留在下列頁面：

* [AEM作為雲端服務發行資訊](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Automated Forms Conversion Service發行說明](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [AEM 6.4 Cumulative Fix Pack發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM Assets Dynamic Media發行說明](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal版本注意事項](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [AEM案頭應用程式版本注意事項](https://docs.adobe.com/content/help/zh-Hant/experience-manager-desktop-app/using/release-notes.translate.html)
* [AEM Dispatcher發行說明](https://docs.adobe.com/content/help/en/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Adobe Primetime發行說明](https://docs.adobe.com/content/help/en/primetime/release-notes/home.html)
* [Livefyre 發行說明](https://docs.adobe.com/content/help/zh-Hant/livefyre/using/release-notes/c-rn.translate.html)

### AEM的其他說明資源

* [AEM as a Cloud Service使用指南](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)
* [AEM 6.4 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-4.html)
* [AEM 6.3 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-3.html)
* [AEM 6.2 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/tw/experience-manager/cloud-manager/user-guide.html)
* [舊版 AEM 文件](https://helpx.adobe.com/tw/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-classic/using/home.html)

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 新產品版本

Campaign Classic、Campaign Standard和控制面板的發行資訊。

#### Campaign Classic

* 全新金本位穩定版本。 [深入了解](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

#### Campaign 控制面板

* 子網域傳遞能力審核——詳 [細內容](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)

* GPG金鑰管理——閱 [讀更多](https://docs.adobe.com/content/help/en/control-panel/using/instances-settings/gpg-keys-management.html)

### 最新 Campaign 課程與教學課程

過去一個月內發佈的新視訊、教學課程或課程。

| 已發佈 | 名稱 | 解決方法 | 說明 |
| ----------- | ----------- | ---------- | ---------- |  
| 2020 年 6 月 26 日 | [探索Adobe Campaign Classic UI](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/exploring-the-adobe-campaign-classic-user-interface.html) | Campaign Classic | 此影片說明主要的Adobe Campaign Classic使用者介面，並示範如何導覽主要功能。 |
| 2020 年 7 月 8 日 | [安裝和設定 Adobe Campaign Client](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Campaign Classic | 了解如何下載和安裝 Adobe Campaign Client 主控台、建立和管理您與多個環境的連線，以及驗證 Adobe Campaign Client 主控台的存取權。 |
| 2020 年 6 月 19 日 | [Adobe Campaign Classic簡介](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/introduction-to-adobe-campaign-classic.html) | Campaign Classic | 瞭解Adobe Campaign Classic如何融入Adobe Digital Experience作品集，以及主要功能。 |
| 2020 年 6 月 12 日 | [部署臨機電子郵件傳送範本](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/deploying-ad-hoc-email-delivery-template.html) | Campaign Classic | 瞭解如何部署臨機電子郵件範本 |
| 2020 年 6 月 12 日 | [設定傳送範本](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/configuring-a-delivery-template.html) | Campaign Classic | 瞭解如何設定電子郵件範本 |
| 2020 年 6 月 12 日 | [設定傳送範本屬性](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/setting-delivery-template-properties.html) | Campaign Classic | 瞭解如何設定電子郵件範本屬性 |
| 2020 年 6 月 12 日 | [GPG密鑰管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management-overview.html) | Campaign Classic/控制面板 | 瞭解如何產生和安裝用於資料加密的公用／私用GPG金鑰對，以及如何匯入和安裝用於資料解密的公用金鑰。 |
| 2020 年 6 月 26 日 | [Adobe Campaign Standard中的UI快速入門](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/getting-started/getting-started-with-the-ui.html) | Campaign Standard | 此影片提供Adobe Campaign Standard使用者介面的概觀，並說明如何導覽至主要功能和核心功能。 |
| 2020 年 6 月 26 日 | [GPG密鑰管理](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/gpg-key-management-overview.html) | 促銷活動標準／控制面板 | 瞭解如何產生和安裝用於資料加密的公用／私用GPG金鑰對，以及如何匯入和安裝用於資料解密的公用金鑰。 |

### 說明資源

* Adobe Campaign Standard：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/campaign-standard-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/campaign-classic-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 作法影片

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud的發行說明。

### [!UICONTROL Advertising Cloud Search] 新功能 {#adcloud-search}

2020 **年7月8日** ,7月11日發行更新。

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 警報測試版] | 您現在可以開啟包含任何警報資料的唯讀篩選檢視，然後在相關促銷活動管理檢視中開啟實體的篩選檢視，您可從中編輯實體記錄。 |
| [!UICONTROL 產品組合] | 限制和投資組合設定中以職位為基礎的量度的取代已延遲至8月8日。 |

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是銷售機會管理的完整解決方案，適合 B2B 行銷人員使用，而透過該解決方案，他們可參與複雜購買歷程的每個階段，從中推動客戶體驗轉型。

### Marketo Engage 核心更新

如需最新版本的資訊，請參閱 [!DNL Marketo] [發行說明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)。

### 即將推出的功能

本季預計推出下列功能：

| 功能 | 說明 |
|------|---------|
| [!DNL Bizible] | <ul><li>全新的帳戶型細分</li><li>儲存儀表板專有的篩選器</li><li>將 Bizible 儀表板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 公告

**Marketo Engage Success Center：**&#x200B;預計於 2020 年 2 月推出。Success Center 是產品內的說明中心，可讓您搜尋產品檔案和社群、啟動操作指南、存取採用內容等等。注意：此功能將會以測試版的形式在澳洲與紐西蘭推出，並預計於本季末在北美地區推出。

### 淘汰

* **資產 API「_method」參數：** 2020 年 9 月後，資產 API 端點將不再接受於 POST 主體中使用 `_method` 傳遞查詢參數，以略過 URI 長度限制。
* **Internet Explorer 支援淘汰：**&#x200B;從 2020 年 7 月 31 日推出的七月版開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

如需彙整資料和過往的發行說明，請參閱 [Marketo 發行說明](https://docs.marketo.com/x/CgA6Ag)。
