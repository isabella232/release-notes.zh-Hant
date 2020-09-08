---
title: Adobe Experience Cloud 發行說明
description: Adobe Experience Cloud 發行說明
doc-type: release notes
last-update: September 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 113528f8e43d06e75d9fbb9db8bc229056e6f0f2
workflow-type: tm+mt
source-wordcount: '6762'
ht-degree: 39%

---


# 提早存取- Adobe Experience Cloud發行說明- 2020年9月

![橫幅](/assets/experience-cloud-banner-3.png)

此頁面主要說明 [!DNL Adobe Experience Cloud] 的新功能、修正項目和重要注意事項。此外還有最新文件、訓練課程和教學課程影片，協助您充份運用 Experience Cloud。

>[!IMPORTANT]
>
>此頁面含有搶先版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>訂閱 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。

**發行日期: 2020 年 9 月 10 日**

產品的發行日期可能不盡相同。請時常回訪以取得更新內容。

最新更新： **2020年9月4日**

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Primetime]](https://docs.adobe.com/content/help/zh-Hant/primetime/release-notes/home.html)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/tw/)。

如需 [最新發行資訊，請參閱Adobe系統狀態](https://docs-stg.corp.adobe.com/content/help/en/release-notes/experience-cloud/previous/2020/05212020.html#status) - 2020年5月21日。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 介面 {#ecloud}

如需 [Experience Cloud介面的最新發行資訊](https://docs.adobe.com/content/help/en/core-services/interface/release-notes/release-notes.html) （客戶屬性、觀眾、使用者和產品管理），請參閱累計發行說明。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

[!DNL Experience Platform] 和應用程式服務的發行說明，內容包括 [!DNL Experience Platform Launch,] [!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services]、安全性公告。

發行日期：**2020 年 8 月 12 日**

Adobe Experience Platform現有功能的更新：

* [資料科學工作區](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#dsw)
* [目的地](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#destinations)
* [來源](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#sources)

如需 Experience Platform 的最新資訊，請參閱 [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)。

### 體驗平台與服務教學課程與課程

針對Experience Platform和服務發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 17 日 | [除錯啟動實作](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | 影片 | 簡介為Launch實作除錯的一些常用工具和技巧。 瞭解如何使用瀏覽器的開發人員主控台和Experience Platform Debugger擴充功能來識別和疑難排解Launch實作的主要方面。 |
| 2020 年 8 月 17 日 | [建立Launch Cloud服務設定](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | 影片 | 瞭解如何建立新的Launch Cloud服務設定。 然後，Launch Cloud服務設定便可套用至現有的網站，而且在「作者」和「發佈」環境中都可看到載入Launch程式庫。 |
| 2020 年 8 月 17 日 | [使用Adobe I/O將AEM與Launch連接](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | 影片 | 瞭解如何使用Adobe I/O建立IMS設定，以便使用Launch API驗證AEM。 在此整合完成後，AEM將可透過Launch API通訊以存取Launch屬性。 |
| 2020 年 8 月 17 日 | [同意管理- Google IAB TCF 2.0支援](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-iab-transparency-and-consent-framework-2.html) | 影片 | 本視訊顯示Adobe的即時客戶資料平台如何協助品牌在客戶參與數位財產時，尊重其同意。 透過IAB的「透明與同意框架2.0」的支援，品牌在如何與消費者互動方面獲得更大的彈性，同時讓消費者更能控制其同意。 |
| 2020 年 8 月 17 日 | [Google客戶符合](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-google-customer-match.html) | 影片 | 本視訊顯示Adobe的即時CDP和Google的「客戶符合」功能如何協助品牌在Google自有及營運的物業上與客戶互動，以提升其業務目標，進而提升其推廣活動。 |
| 2020 年 8 月 17 日 | [Adobe Experience Platform for Data Engineers快速入門課程簡介](https://video.tv.adobe.com/v/39478?captions=chi_hant) | 影片 | 資料工程師 [Adobe Experience Platform快速入門課程的入門影片](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) 。 |
| 2020 年 8 月 17 日 | [Adobe Experience Platform資料工程師快速入門](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) | 課程 | 瞭解如何在Adobe Experience Platform中完成主要資料工程師工作。 此入門級課程使用視訊和親力訓練，讓您開始使用Web SDK擷取串流資料、執行查詢等。 |
| 2020 年 8 月 17 日 | [資料架構師Adobe Experience Platform快速入門課程簡介](https://video.tv.adobe.com/v/39477?captions=chi_hant) | 影片 | 此影片提供您Adobe資料架構 [師體驗平台快速入門課程的概觀](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) 。 |
| 2020 年 8 月 17 日 | [資料架構師專用的Adobe Experience Platform快速入門](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) | 影片 | 瞭解如何在Adobe Experience Platform中完成主要資料架構設計工作。  本入門課程使用影片和親身體驗，讓您開始將模型資料建立在XDM架構中，為資料加上標籤，以便將資料整合在即時客戶個人檔案中，並建立細分等。 |

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

不論客戶處於哪個歷程階段，Adobe Experience Platform 均可聰明地即時預測每個人的需求，以便大規模協調不同體驗管道的客戶歷程。

### 新產品版本

* August release - [Read more](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#august-release)

### [!UICONTROL 歷程協調] (Journey Orchestration)課程與教學課程

針對「歷程協調」發佈的新影片、教學 [!UICONTROL 課程和課程]。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 10 日 | [使用區段資格事件](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/using-segment-qualification-events.html) | 影片 | This video gives you a brief introduction on how to create a journey with a [!UICONTROL Segment Qualification] event as entry or exit point. |

### Journey Orchestration 的其他資源

[文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/zh-Hant/journey-orchestration-learn/tutorials/understanding-journey-orchestration.translate.html)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Media Analytics 新功能](#media-aa)
* [Adobe Analytics 修正項目](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [Analytics課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ------- |
| [!UICONTROL 跨裝置分析]：歐洲、中東和非洲地區及亞太地區的上市情況 | 2020 年 8 月 31 日 | [跨裝置分析](https://docs.adobe.com/content/help/zh-Hant/analytics/components/cda/overview.html) 和私人圖表適用於EMEA和亞太地區的客戶。 |
| 跨裝置分析中欄位裝訂 [!UICONTROL 的增強功能] （全球提供） | 2020 年 8 月 31 日 | 透過這套簡化的[!UICONTROL 跨裝置分析]新客戶實作方案，您可選擇根據 Analytics 欄位 (prop 或 eVar) 所儲存的使用者 ID，執行結合作業，而不使用裝置圖表 (co-op 或私密圖表)。此增強功能移除了實作 ECID 與以 CDA 為目的而實作 ID 同步的需求(部分功能仍需同步 ECID 和 ID)。 |
| China Data Collection，第2階段 | 2020 年 9 月 1 日 | 擴充支援第一方SSL。 |
| 工作區中的新日期範圍 | 2020 年 9 月 10 日 | 我們新增了5個日期範圍，因此您可以從不包含今天部分日期資料的日期範圍中選擇：最近7個完整天、最近14個完整天、最近30個完整天、最近60個完整天、最近90個完整天 |
| Workspace：下載單一維度的 50,000 個項目 | 2020 年 9 月 17 日 | 您將能以自由格式表格，針對單一維度下載 50,000 個項目，並套用區段和篩選條件。這可讓您存取 Analysis Workspace 以外超過 400 列的資料。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/curate-share/download-send.html#download-items) |
| 工作區：Line視覺化 [!UICONTROL 增強功能] | 2020 年 9 月 17 日 | <ul><li>You can show or hide the x-axis and y-axis of any [!UICONTROL Line] visualization. This can be especially helpful when your [!UICONTROL Line] visualizations are more compact.</li><li>You can overlay a minimum and maximum value label on any [!UICONTROL Line] visualization to quickly highlight the peaks and valleys in a metric.</li><li>You can overlay different regression trend lines on any [!UICONTROL Line] visualization to more easily see the trend in the data. Options include [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] and [!UICONTROL Quadratic].</li></ul> [更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/visualizations/line.html) |

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ----- |
| 客戶歷程分析權限的變更 | 2020 年 9 月 9 日 | CJA將不再將所有使用者視為管理員。 只有在 [Adobe Admin Console中指定為產品管理員的使用者](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/manage-users-and-products/admin-getting-started.html) ，才能執行下列動作：<ul><li>建立／更新／刪除連 [!UICONTROL 線] 或資 [!UICONTROL 料檢視]</li><li>更新／刪除其他使用者建立的專案、篩選或計算量度</li><li>將工作區專案共用給所有使用者</li></ul>[更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-overview/cja-overview.html#admin-access-permissions) |
| 支援[!UICONTROL 異常偵測] | 2020 年 9 月 10 日 | [!UICONTROL 異常偵測] (Anomaly Detection)可讓您識別哪些統計波動很重要，哪些不重要。客戶歷程分析現在支 [!UICONTROL 援此功能]。 |
| 工作區中的新日期範圍 | 2020 年 9 月 10 日 | 我們新增了5個日期範圍，因此您可以從不包含今天部分日期資料的日期範圍中選擇： [!UICONTROL 最近7天]，最 [!UICONTROL 近14天]，最 [!UICONTROL 近30天整天]，最 [!UICONTROL 近60天整天][!UICONTROL ，最近90天整天] |
| 工作區：Line視覺化 [!UICONTROL 增強功能] | 2020 年 9 月 17 日 | <ul><li>You can show or hide the x-axis and y-axis of any [!UICONTROL Line] visualization. This can be especially helpful when your [!UICONTROL Line] visualizations are more compact.</li><li>You can overlay a minimum and maximum value label on any [!UICONTROL Line] visualization to quickly highlight the peaks and valleys in a metric.</li><li>You can overlay different regression trend lines on any [!UICONTROL Line] visualization to more easily see the trend in the data. Options include [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] and [!UICONTROL Quadratic].</li></ul> [更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/visualizations/line.html) |

### [!UICONTROL Media Analytics] 新功能{#media-aa}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ---------- |
| 工作區的「媒體並行檢視者」面板 | 2020 年 9 月 17 日 | The [!UICONTROL Media Concurrent Viewers] panel enables you to understand where peak concurrency occurred or where drop-offs happened. 這項功能提供內容品質和檢視者互動的重要分析，有助於疑難排解或依數量/規模完成規劃。[更多詳情...](https://docs.adobe.com/content/help/en/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Adobe Analytics 修正項目 {#aa-fixes}

* 修正無法依「未指定」維 [!UICONTROL 度篩選] 「工作區」欄的問題。 (AN-222393)
* 修正「排程專案」無法傳送 [!UICONTROL 的連線逾時] 問題。 (AN-223916)
* 修正虛擬報表套 [!UICONTROL 裝中] ，瀏覽 [!UICONTROL 區段無法正常運作] 的問題。 (AN-225719)
* 修正Adobe Report Builder中的Chrome瀏覽器版本問題。 (AN-226718)
* 修正已組織的虛 [!UICONTROL 擬報表套裝] ，仍可依VRS中的任何維度／量度劃分的問題。 (AN-228035)
* 修正「區段管理員」單元中的搜尋功能 [!UICONTROL 運作正常] 的問題。 (AN-226954)
* 修正在嘗試與一或兩位以上的使 [!UICONTROL 用者共用專案時] ，工作區中出現逾時錯誤的問題。 (AN-229443)
* 修正API請求引發系統故障錯誤的問題。 (AN-229537)
* 修正「 [!UICONTROL 分類規則產生器] 」導致索引鍵值未分類的問題。 (AN-229786、AN-230300、AN-230563)
* 修正「資料插入  API」未報告部分資料的問題。 (AN-230587)
* 修正Data Warehouse請  求無法取得並驗證具有基本名稱的檔案的問題。 (AN-230642)
* (客[!UICONTROL 戶歷程分析])修正在CJA中共用專案的權限問題。 (AN-226592)

#### 其他 Adobe Analytics 修正項目

AN-215683;AN-216894;AN-226370;AN-227138;AN-227154;AN-227328;AN-227486;AN-227672;AN-228264;AN-228960;AN-229031;AN-229274;AN-229319;AN-229353;AN-229537;AN-229610;AN-229975;AN-230008;AN-230015;AN-230347;AN-230468;AN-230473;AN-231326;AN-231329;AN-231345;AN-231509;AN-231795;AN-231901

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 從 `omniture.com` 移轉至 `adobe.com` 網域 | 2020 年 8 月 21 日 | 2020 年 8 月 13 日，Adobe Analytics 將前端架構從 `omniture.com|http://omniture.com/` 移轉至 `adobe.com|http://adobe.com/` 網域。此變更應可紓解 2020 年 5 月 28 日初次統一產品網域後發生的第三方 Cookie 問題。As a result of this update, the browser may prompt users to trust the new an `.adobe.com|http://an.adobe.com/` or `experience.adobe.com|http://experience.adobe.com/` domain. |
| 更新 Ad Hoc Analysis Java 8 相容性 | 2020 年 8 月 21 日 | Ad Hoc Analysis 目前與 Java 8 1.8.0_261 以後的版本不相容。為確保您在[產品生命週期](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)結束前能順利存取此工具，建議您持續使用 1.8.0_261 之前的 Java 8 版本。 |
| Adobe Data Connectors 終止服務 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 的舊技術已無法使用或不再支援。[Adobe Exchange 合作夥伴計畫已推出一項新標準](https://partners.adobe.com/tw/exchangeprogram/experiencecloud)，任何希望能繼續使用服務及取得支援的整合項目，都應採用此標準。確切日期仍未決定，但預計未來 12 至 18 個月內 (2021 年中至 2021 年底) 將會正式終止服務。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/import/dataconnectors/data-connectors-eol.html) |
| 報告套裝對應至 IMS 組織 | 2020 年 7 月 | 報告套裝對應工具將於 2020 年 11 月終止提供。此功能可提升 Advertising Analytics 和 Experience Cloud 在 Adobe Analytics 中發佈區段的整合程度。報告套裝必須與 IMS 組織對應，才能啟用各項服務。較新的報告套裝會在建立時自動完成對應。然而，先前的報告套裝必須以手動方式與 IMS 組織對應。請參閱 Experience Cloud 介面 (核心服務) 使用指南中的[「將報表套裝對應至組織」](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/about-core-services/report-suite-mapping.html)，確認所有報表套裝均有歸屬的 IMS 組織。 |
| 移轉至統一的產品網域 | 生效日期：2020 年 5 月 28 日 | 從 2020 年 1 月開始，Adobe Analytics 就開始移轉至統一的產品網域，相關作業已於 2020 年 5 月 28 日完成。雖然 Adobe Analytics 已著手從架構中移除所有 `omniture.com` 網域參考，但請務必將 `omniture.com` 放入協力廠商 Cookie 允許清單。完整架構即將移轉完成，作業完成後我們會透過發行說明通知您，到時您就不需再執行此允許清單步驟。請參閱這份建議 IP 位址和網域的[完整清單](https://helpx.adobe.com/tw/analytics/kb/adobe-ip-addresses.html)，這些位址和網域均應列入允許清單。<br>如果貴組織封鎖第三方 Cookie，請洽詢客戶服務人員，以重新取得 Adobe Analytics 的存取權限。 |
| 全新 Adobe Analytics 預設登陸頁面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日起，Adobe Analytics 的預設登陸頁面將從[!UICONTROL 報告]變更為[!UICONTROL 工作區]。未設定自訂登陸頁面的使用者，將一律適用此變更。 |
| 協力廠商技術允許清單 | 2020 年 3 月 12 日 (生效日期) | Adobe Analytics 已開始運用協力廠商技術進行功能推出管理和產品內支援。下列 URL 應新增至任何必要的網路防火牆允許清單，確保完整的功能存取權限：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| 改善 [!UICONTROL Analysis Workspace] 可用性的備援 | 2020 年 5 月 21 日 | 為確保 [!UICONTROL Analysis Workspace] 的可用性，我們新增次要 CDN (內容傳遞網路) 以改善備援。應將下列 URL 新增至任何必要的網路防火牆允許清單：<ul><li>`https://aaui-879784980514.s3.us-east-2.amazonaws`</li><li>`https://d30ln29764hddd.cloudfront.net`</li><li>`https://awaascicdprodva7.blob.core.windows.net`</li><li>`https://aauicdnva7.azureedge.net`</li></ul> |
| 變更[!UICONTROL 工作區]計算[!UICONTROL 輸入/結束]次數的方式 | 2020 年 4 月 7 日 | 自 2020 年 3 月起，[!UICONTROL Analysis Workspace] 已變更&#x200B;_「無」_&#x200B;值與[!UICONTROL 輸入/結束]動作的互動方式。由於您現在可以在 [!UICONTROL Analysis Workspace] 中開啟或關閉&#x200B;_「無」_，因此我們會在使用者輸入或結束後套用&#x200B;_「無」_，但 (eVars) 以往都是在輸入或結束之前就先套用。例如，假設造訪事件的第一次點擊未輸入 eVars 的值，但第二次點擊則有輸入。在 [!UICONTROL Reports &amp; Analytics] 中，第一次點擊的輸入會顯示為&#x200B;_「未指定」_，但在 [!UICONTROL Analysis Workspace] 中則會顯示第二次點擊的值。 |
| **[!UICONTROL 控制面板封存]**&#x200B;確定汰除 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，[!UICONTROL Reports &amp; Analytics] 中&#x200B;**[!UICONTROL 「管理控制面板」]**&#x200B;底下的&#x200B;**[!UICONTROL 「檢視封存」]**&#x200B;設定將不再提供使用。 |
| Analytics Legacy API 終止服務 | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy OAuth 驗證 (OAuth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問題集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy OAuth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 若為倫敦和新加坡的客戶，我們將不再於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間支援資料代理。<br/><ul><li>如果您是在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果您是在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意終止 Ad Hoc Analysis 服務。我們將會在確定後公佈服務終止日期。如需詳細資訊，請造訪[探索工作區](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### AppMeasurement {#appm}

如需 AppMeasurement 發行的最新消息，請參閱[適用於 JavaScript 的 AppMeasurement 發行說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。

### Analytics courses and tutorials {#tutorials-analytics}

New courses, tutorials, and articles in [!DNL Analytics] and [!UICONTROL Customer Journey Analytics].

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 30 日 | [在分析工作區中儲存、共用和協作專案](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/saving-sharing-and-collaborating-on-projects-in-analysis-workspace.html) | 影片 | 在分 [!UICONTROL 析工作區中]，瞭解如何新增文字說明至表格、建立專案的直接連結，並加以分享。 |
| 2020 年 8 月 28 日 | [課程簡介——將價值歸因於客戶歷程中的數位觸點](https://video.tv.adobe.com/v/39380?captions=chi_hant) | 影片 | 在本入門影片中，瞭解客戶歷程課程中將價值歸因 [於數位觸點的先決條件和課程內容](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) 。 |
| 2020 年 8 月 28 日 | [將價值歸因於客戶歷程中的數位觸點](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) | 課程 | 瞭解網站訪客的來源、如何為網站上的轉換分配評價至不同的通道，甚至瞭解網站上的其他項目如何推動轉換，從而瞭解網站訪客。 本課程教您顯示此分析的主要視覺化，以及如何使用 [!UICONTROL Attribution IQ] ，在分析中指派歸因模型。 |
| 2020 年 8 月 21 日 | [使用跨標籤分析探索分析工作區中的基本行銷歸因](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/attribution-iq/using-cross-tab-analysis-to-explore-basic-marketing-attribution-in-analysis-workspace.html) | 影片 | 您有許多方法可以透過Adobe Analytics將歸因方法提升到新的層次。 在此影片中，我們強調您如何使用工作區中的跨標籤分析，從 [!UICONTROL 「行銷渠道] 」報表獲得更深入的 [!UICONTROL 見解]。 |
| 2020 年 8 月 21 日 | [按一下滑鼠右鍵以提高工作區效率](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/right-click-for-workspace-efficiency.html) | 影片 | 瞭解我們最愛的分析工作區所有滑鼠右鍵，以及如何使用這些滑鼠。 從自由表格到流失視覺化，按一下滑鼠右鍵可讓您更有效率並熟悉工作區。 |

### Analytics 說明資源

* [Adobe Analytics 教學課程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 產品文件](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)

## ![圖示](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 的新功能、修正項目、說明文件和教學課程。

發行日期: **2020 年 9 月 20 日**

### Adobe Audience Manager 新功能和修正項目

* 修正「匯整報 [!UICONTROL 告」下無法使用測試區段人口的] Audience Lab問題 。 (AAM-54553)
* 修正使用第三方演算法模型的區段未顯示在「觀眾市集」的「區 [!UICONTROL 段使用] 」檢視 [!UICONTROL 中的問題]。 (AAM-54595)
* 修正即使沒有特徵或區段對應至資料來源，但某些使用者嘗試刪除資料來源時仍發生錯誤的問題。 (AAM-55609)
* 修正「訪客資料檢視器」報表中無法顯示區段的問題。 (AAM-55780)
* 修正「目標」清單頁面上的問題，在「量度」篩選的「 **[!UICONTROL 回顧視窗」中選取「期限」後]****** ，會傳回空白頁面。 (AAM-49732)
* 修正特徵控制面板中，從「所有特徵」篩選至任何篩選(以規則為基礎 **[!UICONTROL 、已登入等]**********)時，量度會更新，但特徵名稱和ID不會更新的問題。 (AAM-55823)
* 修正以人員為 [!UICONTROL 基礎的目的地]，由於API呼叫中遺失欄位，映射至Facebook的區段無法 `traitAlias` 更新的問題。 (AAM-55952)
* 修正趨勢報 [!UICONTROL 告中] ，切換特徵和區段時圖表無法重新整理的問題(AAM-54736)
* 修正類似模型 [!UICONTROL 中按「暫停]**** 」控制項不會暫停模型，而是關閉模型的問題。 (AAM-56121)
* 整個介面的協助工具有多處改良。(AAM-48950、AAM-48957、AAM-49022、AAM-49026、AAM-49044、AAM-49069、AAM-49370、AAMaam-55989、AAM-55990)。

### Audience Manager courses and tutorials {#tutorials-aam}

為Audience Manager發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 17 日 | [將Audience Manager區段對應至目標](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/mapping-audience-manager-segments-to-destinations.html) | 影片 | 瞭解Audience Manager中的不同目標類型，以及將區段對應至每個目標類型的詳細資訊。 |
| 2020 年 8 月 14 日 | [充份運用描述檔合併規則——秘訣、訣竅和策略](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/customer-tips-getting-the-most-out-of-profile-merge-rules.html) | 文章 | Varun Kalra，多解決方案顧問， [!DNL Accordant]提供選擇和使用描述檔合 [!UICONTROL 並規則的秘訣]。 |
| 2020 年 8 月 14 日 | [特徵和區段最佳實務](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/customer-tips-traits-and-segments-best-practices.html) | 文章 | Matt Vittorioso，資深行銷專 [!DNL Ally Financial]員，提供管理特性的秘訣。 |
| 2020 年 8 月 12 日 | [瞭解和設定Google客戶符合以人為本的目的地](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-google-customer-match-pbd.html) | 影片 | 此視訊會逐步帶您瞭解Google Customer Match [!UICONTROL People-Based Destination]（Google客戶符合人員型目標）的詳細資訊和使用案例，並包含建立區段並對應至目標的逐步說明。 此外，它還會顯示觀眾在Google Ad Console中的登陸。 |
| 2020 年 8 月 13 日 | [課程簡介——受眾細分建立與策略](https://video.tv.adobe.com/v/39091?captions=chi_hant) | 影片 | 在此影片中，請在「觀眾區隔建立與策略」課程中瞭解您期待的內容。 |
| 2020 年 8 月 13 日 | [建立區段時使用程式碼檢視 ](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-code-view-when-building-segments.html) | 影片 | 瞭解如何使用程式碼檢視來定義區段，讓您建立複雜特徵組合，包括使用時近和頻率。 |
| 2020 年 8 月 21 日 | [受眾細分建立與策略](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.2) | 課程 | 在本課程中，請學習從A到Z的細分。瞭解如何建立、管理和啟動檔案給目標合作夥伴。 查看一些有用的使用案例，甚至從客戶那裡獲得一些提示和秘訣。 |

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品更新

* **AEM 6.5.6.0** AEM 6.5,Service Pack 6（2020年9月3日發行的6.5.6.0）是重要的更新，其中包含新功能、重要客戶增強功能、改善的效能、穩定性和安全性，自2019年4月AEM 6.5全面上市以來已推出。
   * [發行說明](https://helpx.adobe.com/tw/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms 發行交付項目](https://helpx.adobe.com/tw/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.2** AEM 6.4、Service Pack 8、Cumulative Fix Pack 2（2020年9月3日發行的6.4.8.2）是重要的更新，其中包含自AEM 6.4、Service Pack 8(6.4.8.0)於3月20日全面推出以來的數項內部和客戶修正20.
   * [發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms 發行交付項目](https://helpx.adobe.com/tw/aem-forms/kb/aem-forms-releases.html)

### 產品發行

* **[!UICONTROL AEM 雲端服務]**

   What is new on [!UICONTROL AEM as a Cloud Service]? 精選重點包括：

   * 在 [!UICONTROL AEM中以Cloud Service][形式將頁面和子頁面（頁面樹狀結構）還原為舊版](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/features/page-versions.html#reinstating-versions)。
   * 資產微型服務現在支援視訊轉碼， [!UICONTROL Processing Profiles] （處理設定檔）畫面中有新的 [!UICONTROL Video] （視訊）區段支援視訊位元速率和尺寸的設定（輸出格式為MP4，含H.264 codec）。 如需詳細資訊，請參 [閱「管理視訊資產」。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/manage/manage-video-assets.html#transcode-video) 若需更多轉碼選項和視訊 [!UICONTROL 傳送，可使用Dynamic Media] add-on。
   * 全新的資產下載體驗可讓
      * 非同步下載以進行大量下載，讓使用者不必等待。
      * 開發人員擴充性的全新模組化API。
   * 您現在可以將CDN（內容傳送網路）快取直接從 [!UICONTROL AEM的] Dynamic Media [!UICONTROL (Content Delivery Network)停用為雲端服務] (而非使用 [!UICONTROL Dynamic Media Classic])，以確保在數分鐘內提供最新資產，而非數小時。 請參 [閱透過動態媒體使CDN快取失效。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)
   * Assets中的使用者介面控制項、導覽、瀏覽和搜尋體驗已新增增強的協助工具支援。
   * AEM Desktop App 2.0.3版現已推出，可改善與AEM 6.5、Service Pack 5(AEM 6.5.5)的相容性，並更新用戶端作業系統相容性清單（移除10.14之前的Windows 7和MacOS版本）。
   * [!UICONTROL AEM] Commerce現在提供「產品主控台」功能， [!UICONTROL 做為雲端服務]。 這可讓AEM中的行銷人員和作者檢視並導覽儲存在商務後端的類別和產品。 也提供產品主控台中類別和產品 [!UICONTROL 屬性的支援] 。
   * [!UICONTROL 產品] 和類  別選擇器已改進，可讓行銷人員透過SKU選擇產品，或透過類別ID選擇類別。
   * [!UICONTROL 「內容審核] 」是在 [!UICONTROL Cloud Manager Sites Production Pipelines上啟用的功能]。 使用 [!UICONTROL Sites] 的程式的Production Pipeline [!UICONTROL （生產管道）設定現在包含第三個標籤，名為「內] 容審核」 ****。 每當生產管道執行時，在自訂功能測試後，管道中就會包含新的「內容審核  」步驟，以根據多項維度評估網站，包括效能、搜尋引擎最佳化(SEO)、協助功能、最佳實務和PWA（漸進式網頁應用程式）。
請參閱 [內容審核測試。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/content-audit-testing.html)
   * Assets程式中新建 [!UICONTROL 的環境] ，現在會自動設定 [!UICONTROL Smart Content Services]。
   * 高眠環境可以從Cloud Manager的「概述」頁面中解除高 **[!UICONTROL 眠]** 。
   * 能夠在頁面上執行Experience Checks(由 [!DNL Google Lighthouse]. 作為 [!UICONTROL Cloud Manager] pipeline的一部分，最多可以根據體驗KPI檢查和驗證25頁，分數會顯示在 [!UICONTROL Cloud Manager] UI。
   * See the [AEM as a Cloud Service release notes.](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

* **Experience Manager[!UICONTROL Desktop App]2.0.3.2**

   此次發行包含下列內容：
   * 修正Windows案頭應用程式2.0.2版無法搭配AEM 6.5.5執行個體運作的問題。
   * 將支援的作業系統平台更新為Win 10（含最新的Service Pack）和Mac OS 10.14或更新版本。
   * See the [release notes.](https://docs.adobe.com/content/help/zh-Hant/experience-manager-desktop-app/using/release-notes.translate.html)

* **[!UICONTROL AEM Assets Brand Portal]**

   此版本包含下列內容：
   * 檔案檢視器，提供增強的PDF檢視體驗。
   * 下載資產設定和體驗的增強功能。
   * 重大產品問題的修正。
   * See the [release notes.](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### **自助式**

* **AEM雲端服務轉[!UICONTROL 換的新工具]**

   * AIO-CLI增效模組已推出，以統一程式碼重構工具，讓開發人員可從單一位置叫用並執行程式碼重構工具。 如需詳細資 [訊，請參閱GitHub資源aio-cli-plugin-aem-cloud-service-migration](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration) 。
   * [!UICONTROL AEM Dispatcher Converter] extended可支援將內部部署和Adobe  Managed Services Dispatcher組態轉換為AEM，做為Cloud Service相容的Dispatcher組態。 如需詳細資訊，請 [參閱GitHub資源AEM Cloud Service Dispatcher Converter](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/dispatcher-converter) 。
   * AEM Dispatcher Converter已重新寫入node.js，並與AIO-CLI外掛程式整合。

* **動態媒體中的CDN[!UICONTROL 失效]**

   您現在可以在 [!UICONTROL Dynamic Media中傳送要求] ，讓CDN快取在數分鐘內到期。 當您更新資產，並希望這些變更立即在您的網站上生效時，此功能很有用。

   請參 [閱透過動態媒體使CDN快取 [!UICONTROL 失效]。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)

* **發佈頁面的開啟與關閉時間**

   使用「開啟和關 [閉時間」發佈頁面時](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/page-properties.html#basic)，請參閱「頁面屬性」的「基本」標籤，您現 [在可以預先設定自動複製](https://docs.adobe.com/help/en/experience-manager-cloud-service/operations/replication.html#on-and-off-times-trigger-configuration)。

* **[!UICONTROL Core Components]**

   [!UICONTROL 核心元件] 2.11.0版提供AMP支援，現在也提供製作說明檔案 [](https://docs.adobe.com/content/help/zh-Hant/experience-manager-core-components/using/introduction.html) ，以及GitHub上 [的開發人員詳細資訊和專案下載。](https://github.com/adobe/aem-core-wcm-components)

* **[!UICONTROL 表單]**

   * 更新 [的Gov和We.Finance參考網站有提供](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) 。 您可以使用這些參考網站來學習端對端工作流程，以建立並傳遞適合政府與金融產業的表單。
   * 現 [在提供Save as Draft SPI的示例實現](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#sample-ccrDocumentInstance-spi) 。 您可以使用此範例來實 [!UICONTROL 作互動式通訊代理] UI [!UICONTROL 的「另存為草稿」功能]。 它可協助代理程式儲存和擷取草稿，以加速互動式通訊的產生。
   * 有說 [明在安裝](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/installing-configuring-aem-forms-osgi.html#automatic-installation-visual-studio-redistributables) AEM Forms  add-on套件時安裝和驗證Visual C++可轉散發套件的安裝。 這有助於減少與Visual C++可轉發套件安裝和配置相關的錯誤。
   * [使用最適化表單檔案來設定Adobe Sign](https://docs.adobe.com/content/help/en/experience-manager-65/forms/adaptive-forms-advanced-authoring/adobe-sign-integration-adaptive-forms.html) ，將經過徹底的測試和改版。 現在包含其他指示，可協助您順利使用最適化表單來設定Adobe Sign。
   * (僅[!UICONTROL 限AEM Forms] on JEE)適用於Rights Management服務 [的「邀請外部使用者處理常式](https://docs.adobe.com/content/help/en/experience-manager-65/forms/developer-reference/programming-aem-forms-jee/developing-spis-aem-forms/creating-invite-external-users-handler.html) 」檔案已推出。

### **社群**

* **Experience League 的最新 AEM 內容**

   此為 Adobe 提供之數位體驗技術內容的官方來源。若需參閱完整清單，請前往[此處](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)。

### 最新 Experience Manager 課程與教學課程 

過去一個月內發佈的新影片、教學課程和課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 8 月 31 日 | [設定XDP範本以利用AEM Forms和Adobe Sign整合](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/using-xdp-templates-with-adobe-sign.html) | 影片 | 將現有的XDP範本與 [!UICONTROL AEM Forms] and Sign整合在一起。 |
| 2020 年 8 月 17 日 | [審查和配置已轉換的最適化表單](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-converted-adaptive-form.html) | 影片 | 設定由自動表單服務建立的最適化表單，使用Adobe Sign整合。 依您的需求變更面板標題並重新排列某些欄位。 |
| 2020 年 8 月 25 日 | [為2位簽署者設定最適化表單](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-adaptive-form-for-two-signers.html) | 影片 | 使用Adaptive Forms介面配置多個簽署者並指定順序（循序或並行）。 |
| 2020 年 8 月 17 日 | [設定AEM的存取權](https://video.tv.adobe.com/v/39230?captions=chi_hant) | 影片 | 探索使用者如何以雲端服務的形式，將Adobe IMS驗證 [!UICONTROL AEM] ，以及如何使用Adobe IMS使用者、使用者群組和產品設定檔來控制AEM的存取權及其功能。 |
| 2020 年 8 月 17 日 | [設定AEM逐步存取權](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/walk-through.html) | 影片 | 在Adobe [!UICONTROL Admin Console中設定Adobe IMS使用者、使]用者群組  和產品設定 [!UICONTROL 檔的簡介]。 此外，瞭解如何在  AEM Author中運用這些Adobe IMS抽象化來定義和管理特定的群組權限。 |
| 2020 年 8 月 17 日 | [AEM使用者、群組和權限](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/aem-users-groups-and-permissions.html) | 影片 | Adobe Experience Manager以Adobe IMS使用者、使用者群 [!UICONTROL 組和產品設定檔為基礎],  提供AEM的可自訂存取權。 瞭解如何定義AEM群組和權限，以及它們如何與Adobe IMS抽象化搭配運作，以提供順暢且可自訂的AEM存取。 |
| 2020 年 8 月 17 日 | [除錯啟動實作](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | 影片 | 簡介為Launch實作除錯的一些常用工具和技巧。 瞭解如何使用瀏覽器的開發人員主控台和 [!UICONTROL Experience Platform Debugger] extension來識別和疑難排解Experience Platform Launch實作的主要方面。 |
| 2020 年 8 月 17 日 | [建立Launch Cloud服務設定](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | 影片 | 瞭解如何建立新的Experience Platform Launch Cloud Services設定。 然後，Launch Cloud服務設定便可套用至現有的網站，而且在「作者」和「發佈」環境中都可看到載入Launch程式庫。 |
| 2020 年 8 月 17 日 | [使用Adobe I/O將AEM與Launch連接](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | 影片 | 瞭解如何使用Adobe I/O建立IMS設定，以便使用Experience Platform Launch API驗證AEM。 在此整合完成後，AEM將可透過Launch API通訊以存取Launch屬性。 |
| 2020 年 8 月 17 日 | [建立 Launch 屬性](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-property.html) | 影片 | 瞭解如何建立具備設定其餘整合所需最低配置的Launch屬性。 使用者將會進入Launch UI，並瞭解擴充功能、規則和發佈工作流程。 |
| 2020 年 8 月 17 日 | [整合Experience Platform Launch和AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/overview.html) | 影片 | Experience Platform Launch是Adobe的新一代標籤管理平台，也是部署Adobe Analytics、Audience Manager和更多解決方案的 [!DNL Target]最佳方式。 概觀Experience Platform Launch，並建議與Adobe Experience Manager整合。 |
| 2020 年 8 月 17 日 | [為管理員設定 AEM Assets](https://video.tv.adobe.com/v/37647?captions=chi_hant) | 影片 | 在此影片中，管理員可以瞭解如何設 [!UICONTROL 定AEM Assets]。 |
| 2020 年 8 月 12 日 | [以AEM做為雲端服務SDK進行本機開發](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/develop.html) | 影片 | 瞭解如何為 [!UICONTROL AEM Commerce和] AEM [!UICONTROL a Cloud Service] SDK設定本機開發環境。 |
| 2020 年 8 月 17 日 | [使用表單資料模型預先填寫最適化表單](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.forms) | 課程 | 您可以使用現有資料預先填寫最適化表單的欄位。 在本課程中，請學習使用表單資料模型的request屬性來預先填寫欄位。 |
| 2020 年 8 月 17 日 | [Adobe IMS產品設定檔](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-product-profiles.html) | 影片 | Adobe IMS產品設定檔讓使用者有權登入AEM Author服務，並根據新增的產品設定檔提供存取基準。 |
| 2020 年 8 月 17 日 | [Adobe IMS使用者群組](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-user-groups.html) | 影片 | Adobe IMS使用者群組會建立接觸AEM的使用者邏輯集，可在此處利用他們來定義AEM使用者的微調權限。 |
| 2020 年 8 月 17 日 | [Adobe IMS使用者](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-users.html) | 影片 | 瞭解Adobe IMS使用者的身分，以及如何在Admin Console中存取和管理他們，以及如何使用他們以雲端服務的身分登入AEM。 |
| 2020 年 8 月 17 日 | [開發人員適用的HTML5 Forms快速入門](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.forms) | 課程 | HTML5表格提供HTML5格式的XFA表格範本轉換功能。 這項功能可讓您在不支援XFA PDF的行動裝置和案頭瀏覽器上轉換表單。 |

### Experience Manager 發行資訊

所有 Experience Manager 的發行說明都會保留在以下頁面：

* [AEM 雲端服務發行資訊](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Automated Forms Conversion Service 發行說明](https://docs.adobe.com/content/help/zh-Hant/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [AEM 6.4 Cumulative Fix Pack 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM Assets Dynamic Media 發行說明](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [AEM 桌面應用程式發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-desktop-app/using/release-notes.translate.html)
* [AEM Dispatcher 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Adobe Primetime 發行說明](https://docs.adobe.com/content/help/zh-Hant/primetime/release-notes/home.html)
* [Livefyre 發行說明](https://docs.adobe.com/content/help/zh-Hant/livefyre/using/release-notes/c-rn.translate.html)

### AEM 其他說明資源

* [AEM 雲端服務使用手冊](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
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

Campaign Classic、Campaign Standard 和控制面板的發行資訊。

#### Campaign Classic

* 20.2.2 版 - [深入了解](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### 最新 Campaign 課程與教學課程

過去一個月內發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 解決方法 | 說明 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 8 月 10 日 | [結合查詢結果以精確目標](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-combining-query-results.html) | Campaign Classic | 瞭解如何使用交叉點或聯合活動在工作流程中結合查詢結果來調整目標。 |
| 2020 年 8 月 10 日 | [使用更新清單活動建立具有工作流的清單](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/using-the-update-list-activity.html) | Campaign Classic | 瞭解Adobe Campaign Classic中清單的概念，並瞭解如何使用工作流程中的更新清單活動來建立清單。 |
| 2020 年 8 月 20 日 | [通過排除查詢結果來細化目標](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-excluding-query-results.html) | Campaign Classic | 瞭解如何透過將標準排除套用至工作流程來調整目標。 您也將學習如何建立預先定義的篩選，以及如何拍攝工作流程。 |
| 2020 年 8 月 25 日 | [建立直接郵件傳送](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | 瞭解直效郵件在Adobe Campaign中的運作方式，並瞭解如何建立、格式化及執行直效郵件傳送。 |  | 2020 年 8 月 25 日 | [建立直接郵件傳送](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | 瞭解直效郵件在Adobe Campaign中的運作方式，並瞭解如何建立、格式化及執行直效郵件傳送。 |

### 說明資源

* Adobe Campaign Standard：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/campaign-standard-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/campaign-classic-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 作法影片

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 發行說明。

* [Advertising Cloud DSP 新功能](#adcloud-dsp)
* [Advertising Cloud Search 新功能](#adcloud-search)

### [!UICONTROL Advertising Cloud DSP] 新功能{#adcloud-dsp}

| 功能 | 說明 |
| -----------| ---------- |
| 延長互動式影片前置內容的時間，加入 VAST 詳細目錄支援 | 現在，每個互動式影片前置內容版位和廣告均可支援 VPAID 和 VAST 詳細目錄。**注意：** 如果您的主要KPI是檢視能力，請繼續建立個別的VPAID和VAST位置和廣告，因為VAST廣告無法提供檢視印象。 |

### [!UICONTROL Advertising Cloud Search] 新功能 {#adcloud-search}

**8 月 8 日**&#x200B;發行

| 功能 | 說明 |
| ----------- | ---------- |
| [!UICONTROL 產品組合] | 產品組合設定不再提供產品組合層級的位置限制。先前建立的所有位置限制均已移除。 |
| [!UICONTROL 限制] | 不再支援以位置為基礎的限制和限制條件：<br/> <ul><li>[!UICONTROL 「最小位置] 」和「 [!UICONTROL 最大位置」限制已不再提供，且已從所有先前建立的「競價與位置」限制和「印象共用] 」限制中移除  。</li><li>Existing [!UICONTROL Bid &amp; Position] constraints that included position constraints but no bid constraints were paused. 上述限制仍可在 UI 和報表中使用。</li><li>[!UICONTROL 「競價與位置」限制已重新命名為「競價」限制。]</li><li>All position-based conditions (using [!UICONTROL Average Position], [!UICONTROL Weighted Average Position], or [!UICONTROL Last Known Pos] metrics) in any type of constraint were removed.</li></ul> <br/> **注意：**&#x200B;如果從搜尋引擎能取得位置資料，系統仍會繼續將其填入。Microsoft Ads 將於 2020 年 9 月終止「位置」功能。 |
| [!UICONTROL 行銷活動] | (Google Ads 行銷活動) Advertising Cloud Search 現在支援在回應式搜尋廣告 (RSA) 中自訂廣告。之前，RSA 以外的所有廣告類型皆已支援此功能。 |

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是銷售機會管理的完整解決方案，適合 B2B 行銷人員使用，而透過該解決方案，他們可參與複雜購買歷程的每個階段，從中推動客戶體驗轉型。

### Marketo Engage 核心更新

如需最新版本的資訊，請參閱 [!DNL Marketo] [發行說明](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720)。

### 即將推出的功能

本季預計推出下列功能：

| 功能 | 說明 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>全新的帳戶型細分</li><li>儲存儀表板專有的篩選器</li><li>將 Bizible 儀表板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 淘汰

* **資產 API「_method」參數：** 2020 年 9 月後，資產 API 端點將不再接受於 POST 主體中使用 `_method` 傳遞查詢參數，以略過 URI 長度限制。
* **停止支援 Internet Explorer：**&#x200B;自 2020 年 7 月 31 日推出的版本開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

如需彙整資料和過往的發行說明，請參閱 [Marketo 發行說明](https://docs.marketo.com/x/CgA6Ag)。
