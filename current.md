---
title: Experience Cloud和Experience Platform的發行說明
description: 瞭解Experience Cloud和Experience Platform的最新發行說明、新功能和新檔案。 尋找適用於企業的Creative Cloud和Document Cloud的新說明和教學課程。
doc-type: release notes
last-update: February 2021
author: mfrei
translation-type: tm+mt
source-git-commit: d24a0044604b068dd1a8b4a19084d982ed9f22ac
workflow-type: tm+mt
source-wordcount: '6309'
ht-degree: 33%

---


# Adobe Experience Cloud 版本說明 - 2021 年 2 月

![橫幅](/assets/experience-cloud-banner-3.png)

Experience Cloud解決方案和服務每月更新一次。 本頁是您尋找[!DNL Experience Cloud]和Experience Platform最新版本更新、檔案和教學課程的中心位置。 您也可以找到[!DNL Creative Cloud for Enterprise]和[!DNL Document Cloud]的新檔案。

>[!IMPORTANT]
>
>本頁包含搶鮮版內容，並可能在發行日期之前有所變更。

>[!NOTE]
>
>訂閱每月 [Adobe 優先產品更新](https://www.adobe.com/subscription/priority-product-update.html)，接收本頁面更新的電子郵件通知。本頁面會在整個月中維護，因此請定期回訪，以取得Adobe企業產品和Experience League檔案的更新。

最新更新：**2021年2月12日**

* [Adobe 系統狀態](#status)
* [Experience Cloud 服務與管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey)`
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/tw/)。

本月無更新。

如需最新發行資訊，請參閱 [Adobe 系統狀態 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hant/release-notes/experience-cloud/previous/2020/05212020.html#status)。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 服務與管理 {#ecloud}

[Experience Cloud 服務與管理](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html)文件包含客戶屬性、對象庫 ([!UICONTROL People] 服務) 啟用、使用者和產品管理，以及 Experience Cloud Cookie。

**2021 年 2 月 4 日**

* **登入更新： Experience Cloud的** 更新會移除初始的Experience Cloud登入簡介畫面。從2月4日起，您將直接從`https://experience.adobe.com/login`傳送至Adobe登入畫面。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

包含 Experience Platform 和 Experience Platform Launch 的版本更新資訊。

* [Experience Platform 發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant). (2021 年 1 月 27 日)
* [Experience Platform Launch 發行說明](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html). (2021 年 1 月 13 日)

### Experience Platform教學課程和課程

針對 Experience Platform 和服務所發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 10 日 | [配置Azure Blob目標](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | 影片 | 瞭解如何逐步瞭解在即時客戶資料平台（即時CDP）中設定和配置以及Azure Blob儲存目標所需的步驟。 |
| 2021 年 2 月 4 日 | [檢視身分圖](https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/view-identity-graphs.html) | 影片 | 如何使用身分圖表檢視器功能來搜尋、探索及篩選身分圖表以進行驗證和除錯。 |
| 2021 年 2 月 3 日 | [批次資料擷取概觀](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/batch-ingestion-overview.html) | 影片 | Adobe Experience Platform中的批次資料擷取概觀。 瞭解如何使用API來內嵌批次資料。 |
| 2021 年 2 月 3 日 | [將資料啟動至非Adobe應用程式](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/activate-data-to-non-adobe-applications.html) | 影片 | 瞭解Adobe的即時CDP如何協助您為受眾建立真正的個人化策略。 此外，瞭解它如何整合到您現有的Microsoft、Google和Facebook生態系統和非Adobe應用程式中。 |
| 2021 年 1 月 21 日 | [行銷人員智慧型服務入門課程簡介](https://video.tv.adobe.com/v/330805?quality=12&learn=on) | 影片 | 行銷人員智慧服務快速入門課程簡介。 |
| 2021 年 1 月 13 日 | [行銷人員選件決策快速入門簡介](https://video.tv.adobe.com/v/330520?quality=12&learn=on) | 影片 | 以及行銷人員選件決策入門課程簡介。 |
| 2021 年 1 月 31 日 | [使用配方建立工具範本來訓練、分數並提高模型的生產力](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/train-score-and-productize-models.html) | 影片 | 瞭解如何使用更新的方式產生器範本，使用零售銷售結構和資料集建立方式。 |
| 2021 年 1 月 31 日 | [在JupyterLab筆記型電腦中載入資料](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/load-data-in-jupyterlab-notebooks.html) | 影片 | 瞭解Data Science Workspace中的JupyterLab。 |
| 2021 年 1 月 12 日 | [建立合併策略](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/create-merge-policies.html) | 影片 | 瞭解如何在Adobe Experience Platform中建立合併原則。 |

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

運用 Adobe Experience Platform 聰明地即時預測每個人的需求，在不同體驗管道大規模地協調客戶歷程。

### 最新產品版本

進一步瞭解[歷程協調發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html)中的最新功能、改進和修正。

### 最新 Journey Orchestration 課程與教學課程

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 1 月 22 日 | [跳到另一段歷程](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/jumping-to-another-journey.html) | 影片 | 瞭解如何將個人從一個歷程推向另一個歷程。 |

### 更多的歷程協調資源

[文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/zh-Hant/journey-orchestration-learn/tutorials/understanding-journey-orchestration.translate.html)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期: **2021 年 2 月 18 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Adobe Analytics 修正項目](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ------- |
| Analysis Workspace – 選取元件 | 2021 年 2 月 4 日 | [!UICONTROL Workspace] 的所有拖放區域已新增 [!UICONTROL Quick Insights] 的下拉/拖放區域元件。有了這項增強功能，您就能從相容元件的下拉式清單中挑選項目，或繼續將該空間作為拖放區域使用。 |
| Analytics控制面板語言選擇 | 2021 年 1 月 14 日 | 您現在可以在Analytics儀表板中選取語言。 |

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ----- |
| Analysis Workspace – 選取元件 | 2021 年 2 月 4 日 | [!UICONTROL Workspace] 的所有拖放區域已新增 [!UICONTROL Quick Insights] 的下拉/拖放區域元件。有了這項增強功能，您就能從相容元件的下拉式清單中挑選項目，或繼續將該空間作為拖放區域使用。 |
| CJA API | 2021 年 2 月 18 日 | CJA API現在已可供使用。 這些API可讓您以程式設計方式編輯元件並擷取報表。 如需詳細資訊，請參閱CJA API檔案（後續連結）。 |

### Adobe Analytics 修正項目 {#aa-fixes}

* 修正導致Adobe Analytics 2.0 API閘道逾時增加至300秒（5分鐘）的問題。 (AN-232335)
* 修正工作區、API 2.0和Adobe報告建立工具報告的效能問題(AN-245644、AN-244504、AN-243060)
* 修正在Analytics [!UICONTROL 資料饋送]中按一下&#x200B;**Add**&#x200B;時造成錯誤的問題。 (AN-243171)
* 修正分類無法分類資料的問題。 (AN-243823、AN-247049、AN-244114)
* 修正排程專案的問題：客戶只能看到他們擁有的專案，但無法看到所有排程的專案(AN-246955)
* 修正[!UICONTROL Workspace]中A4T面板造成專案無法開啟的問題。 (AN-246881)
* 修正[!UICONTROL Workspace]引發與A4T [!UICONTROL 計算量度]相關錯誤的問題。 (AN-247082)
* 修正資料倉庫API請求無法傳回資料的問題。 (AN-236931)
* 修正虛擬報表套裝的存取權與父報表套裝的存取權結合的問題。 (AN-247042)
* 修正將專案從[!UICONTROL 臨機分析]轉換為[!UICONTROL 工作區]時發生錯誤的問題。 (AN-221215)
* 修正「工作區專案管理員」[!UICONTROL 中顯示的篩選專案數目錯誤的問題。 ](AN-244934)

#### 其他 Adobe Analytics 修正項目

AN-224987;AN-229009;AN-239750;AN-239765;AN-241620;AN-242996;AN-243577;AN-243774;AN-244509;AN-244746;AN-244763;AN-244868;AN-244960;AN-245016;AN-245097;AN-245727;AN-246141;AN-246283;AN-246340;AN-246532;AN-246669;AN-246744;郵編：246763;AN-246892;AN-246898;AN-246961;AN-247643;AN-247048;AN-247134;AN-247758;AN-247774;AN-248179;AN-248226;AN-248297;AN-248300;AN-248303;AN-248376;AN-248495;AN-248647

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 終止 Ad Hoc Analysis 服務 | 2021年1月 | [!UICONTROL 臨機分] 析將於2021年3月1日結束生命週期。如需詳細資訊，請造訪[探索工作區](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |
| 三個 Analytics API 服務終止運作 | 2021 年 1 月 6 日 | 下列 Analytics Legacy API 服務預計在 2021 年 4 月 30 日結束生命週期並關閉。所有目前使用這些服務建立的整合功能將於當天停止運作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy OAuth 驗證 (OAuth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問題集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)來協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy OAuth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| Adobe Data Connectors 終止服務 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 的舊技術已無法使用或不再支援。[Adobe Exchange合作夥伴計畫](https://partners.adobe.com/tw/exchangeprogram/experiencecloud)中提供了新標準。 您可以針對任何整合使用該標準，以繼續提供並支援。 正式終止日期為2021年8月1日。 [深入了解...](https://docs.adobe.com/content/help/zh-Hant/analytics/import/dataconnectors/data-connectors-eol.html) |
| 為所有傳入的 HTTPS 要求加上 HSTS 標題 | 2020 年 9 月 29 日 | 自2020年9月29日起，Adobe開始將HSTS標題新增至所有使用HTTPS的傳入請求。 此標題會指示瀏覽器或用戶端在HTTPS中提出所有未來要求，這被視為安全性最佳實務。 目前，Adobe不會針對使用HTTP傳入的要求強制執行此動作。 |
| 變更 [!UICONTROL Experience Cloud ID 服務] Cookie 設定 | 2020 年 9 月 22 日 | 一項針對 Chrome 80 版本隱私權設定的更新影響 Adobe Analytics 追蹤部分檢視 Google AMP 頁面之使用者的能力。具體來說，這項更新會防止跨網域追蹤檢視 Google 託管 AMP 頁面的使用者。如此可能導致不重複訪客的數量增加。此修正可讓使用者透過變更 ECID Cookie 設定來解決此問題。<br>目前，Analytics 的 Experience Cloud ID (ECID) 服務 Cookie 設定為 `SameSite = Lax`，而此設定在 Chrome 80 版本之前皆允許進行跨網域追蹤。但如今情況有變。使用者可透過這項變更將 ECID Cookie 的 SameSite 設定更新為 `None`。<br>這項變更可讓Analytics Cookie在更多情況下共用，但Analytics Cookie不包含敏感資訊。此外，選擇這項設定時，Cookie 必須設定為 `Secure`，才能僅透過 HTTPS 連線傳送資料。如果您想要進行此項變更，受支援的使用者可以向客戶服務開啟票證。 |

### AppMeasurement {#appm}

如需 AppMeasurement 發行的最新消息，請參閱[適用於 JavaScript 的 AppMeasurement 發行說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。

### Analytics 課程與教學課程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 的最新課程、教學課程和文章。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日 | [新增趨勢線至線條視覺化](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/adding-trendlines-to-line-visualizations.html?lang=en) | 影片 | 在「視覺化設定」中，您可以選擇將回歸或移動平均趨勢線新增至行系列。 此功能有助於在資料中描繪更清晰的圖樣。 |
| 2021 年 2 月 8 日 | [在Platform Launch中新增實施外掛程式](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/implementation/via-adobe-launch/adding-implementation-plug-ins-in-launch.html?lang=en#implementation) | 影片 | 實作外掛程式是JavaScript程式碼的一部分，您可將這些程式碼新增至Analytics實作，以追蹤其他自訂資料。 在此影片中，瞭解如何在Platform Launch中新增程式碼，以及在何處新增程式碼。 |
| 2021 年 1 月 6 日 | [Analysis Workspace 中的「媒體同時檢閱者」面板](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) | 影片 | 瞭解並行授權數量最高的地區，或下降的地區。 取得內容品質和檢視器參與度的寶貴洞見，並協助疑難排解或規劃容量和規模。 |

### Analytics 說明資源

* [Adobe Analytics 產品文件與教學課程](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![圖示](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager中的新功能、修正、檔案和教學課程。

| 功能 | 新增或更新日期 | 說明 |
|----|----|----|
| [Audience Manager使用者移轉至Admin Console](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/admin-console-migration.html) | 2020 年 2 月 1 日 | Audience Manager使用者帳戶管理正移轉至Adobe Admin Console，以簡化整個Adobe解決方案的使用體驗。 <br>請依照本文所述的步驟，協助使用者移轉。所有Audience Manager管理員應盡快開始將其使用者帳戶移轉至Adobe Admin Console。 |

### 修正和改良 {#aam-fixes-and-improvements}

* 修正[入門狀態報表](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html)中的問題。 在此問題中，報表中的記錄與上線合作夥伴上傳的檔案中的記錄不一致。 (AAM-57415)
* 修正「預測性觀眾」功能中&#x200B;**[!UICONTROL Model]**&#x200B;仿製的問題。 ****(AAM-56775)
* 已修正複製特徵和區段的問題，這些特徵或區段會遭到複製。 (AAM-57351)
* 修正使用者無法點選&#x200B;**[!UICONTROL 「模型>排除特徵」>中的「全選]**」核取方塊的問題。 ****(AAM-57366)
* 修正&#x200B;**[!UICONTROL 區段產生器]**&#x200B;中，**[!UICONTROL 選擇all]**&#x200B;核取方塊無法選取所有特徵的問題。 (AAM-55640)

### Audience Manager 課程與教學課程 {#tutorials-aam}

針對 Audience Manager 發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 5 日 | [擷取檔案式資料的步驟](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/steps-for-ingesting-file-based-data.html?lang=en#integrating-offline-data) | 影片 | 瞭解當離線資料上傳至Audience Manager時，您必須考慮的步驟，包括資料檔案的檔案名稱要求。 |
| 2021 年 2 月 5 日 | [格式化和收錄以檔案為基礎的資料](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/formatting-and-ingesting-file-based-data.html?lang=en#integrating-offline-data) | 影片 | 當將第一方資料匯入Audience Manager以更好地瞭解並鎖定客戶時，資料的格式設定需求會有所增加。 瞭解一些主要選項，以及如何取得更多資訊。 |
| 2021 年 2 月 5 日 | [建立跨裝置資料來源並驗證](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/data-sources/creating-a-cross-device-data-source-and-authenticating.html?lang=en#setup-and-admin) | 影片 | 瞭解如何建立跨裝置資料來源，以儲存CRM ID和資料，並將您的第一方CRM資料匯入Audience Manager。 此影片會示範如何進行登入，以及如何在Experience Platform Launch中設定`setCustomerIDs()`方法。 |
| 2021 年 2 月 3 日 | [課程簡介——在Audience Manager中建立和管理資料啟動](https://video.tv.adobe.com/v/331001) | 影片 | 除非您實際對受眾做些什麼，否則受眾細分並不值錢。 本課程教您如何使用受眾來自訂使用體驗。 此介紹影片可協助您開始前往。 |
| 2021 年 1 月 28 日 | [特徵建立和管理](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.3) | 課程 | 瞭解從內建產品[!UICONTROL 特徵產生器]到[!UICONTROL 批量管理]工具建立和組織特徵的精髓與訣竅。 同時也瞭解如何使用[!UICONTROL 資料總管]工具來發現傳入Audience Manager的重要訊號，並為其建立特徵。 |
| 2021 年 1 月 22 日 | [使用受眾最佳化報告來瞭解媒體效能](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/using-audience-optimization-reports-to-understand-media-performance.html?lang=en#reports) | 影片 | 瞭解如何使用「對象最佳化報表」來改善您的促銷活動，瞭解如何投資行銷資金以及停止投資的位置。 此外，也瞭解如何在這些報告中決定最佳頻率上限並尋找其他優點。 |
| 2021 年 1 月 15 日 | [瞭解具有重疊報表的相關對象](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/understand-related-audiences-with-overlap-reports.html?lang=en#reports) | 影片 | 重疊報表可讓您查看特徵和區段對象如何彼此重疊（多個特徵或區段中的相同訪客），以便您知道可以在何處處理資料，以增加轉換或專注於擴大觸及面。 |
| 2021 年 1 月 12 日 | [使用資料匯出標籤來控制資料流](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/data-activation/destinations-basics/using-data-export-labels-to-control-data-flow.html?lang=en#data-activation) | 影片 | 「資料匯出標籤」可讓您在Audience Manager中控制不同資料類型／來源的流程，以符合您的隱私權要求。 瞭解如何設定「資料匯出控制」和「資料匯出標籤」，以及如何與何處搭配運作。 |
| 2021 年 1 月 22 日 | [從Adobe Analytics將區段匯入Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/import-aa-segments-into-aam.html?lang=en#build-and-manage-audiences) | 影片 | 除了將即時資料從Adobe Analytics轉送至Audience Manager外，您也可以透過Experience Cloud將包含Analytics後處理資料的區段匯入Audience Manager。 |

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

 Experience Manager 的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

>[!NOTE]
>
>Adobe建議造訪[Experience Manager發行更新和規劃藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)頁面，以隨時掌握最新的發行資訊。

### 產品發行

* **Experience Manager as a Cloud Service**

   Experience Manager雲端服務的新功能

   * **Experience Manager Assets 雲端服務**

      * **無頭內容管理服務**

         * [內容片段傳送的GraphQL API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-api-content-fragments.html):能夠使用GraphQL語法查詢內容片段，並根據內容片段模型來結構，以便以JSON格式輸出。
         * [GraphQL API請求的驗證支援](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-authentication-content-fragments.html):能夠使用伺服器端API的存取Token來驗證GraphQL API請求。
         * [RemotePage元件](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html):新增支援使用在AEM中檢視和編輯外部SPA。
         * [在AEM中編輯外部SPA](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html):已新增將單機版單頁應用程式上傳至AEM例項、新增可編輯的內容區段以及啟用編寫功能的能力。
         * 從GraphQL API增強JSON輸出，包括以JSON格式和地區設定輸出豐富型文字的功能。
         * 支援巢狀內容片段模型，以允許透過多行文字欄位中的專屬內容片段參考資料類型或內容片段參考，建立巢狀內容片段結構。
         * 更多適用於內容片段模型資料類型的驗證規則，包括「唯一」、「必要」和「可翻譯」。
         * 可標籤內容片段模型，並允許在資料夾中依標籤或路徑建立內容片段原則。
         * 內容片段編輯器中的可用性增強功能，包括發佈動作和片段所依據的模型顯示。
         * 可直接在內容片段編輯器中預覽JSON輸出。
      * **漸進式網頁應用程式(PWA)**

         * [現在，可透過簡單的設定，在專](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/enable-pwa.html?lang=en) 案層級啟用網站的漸進式網頁應用程式(PWA)版本。
   * **Experience Manager Assets 雲端服務**

      * Experience Manager作為雲端服務，可擴充「智慧標籤」功能，以支援識別文字資產中的關鍵字和實體。 文字會被識別、建立索引，並可做為中繼資料使用，以改善搜尋體驗，而不需進行任何設定。 請參閱[智慧型標籤](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/smart-tags.html)。
      * 現在支援MXF檔案格式。 請參閱[支援的檔案格式](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/file-format-support.html#video-formats)。
   * **Experience Manager Commerce as a Cloud Service**

      * **新功能?**

         * 產品體驗管理：資產和體驗片段的新「商務」屬性標籤。 此標籤可讓您將產品／類別連結至資產和體驗片段。 此標籤也會顯示連結產品／類別的即時資料，以及在產品主控台中顯示詳細資料的連結。
         * 發佈的CIF Venia參考網站- 2021.02.02，其中包含最新的CIF核心元件1.7.0版。如需詳細資訊，請參閱[CIF Venia參考網站](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.02)。
         * 已發佈CIF核心元件v1.7.0。有關詳細資訊，請參閱[CIF核心元件](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.7.0)。
      * **SDK建置分析器**

         Experience Manager（Cloud Service SDK Build Analyzer Maven增效模組）可偵測主要專案中的問題，包括缺少相依性。 它為開發人員提供了在本機開發期間發現問題的機會，而遠在使用Cloud Manager部署至雲端環境之前。

         此版本新增了兩個分析器：

         * 重點分析器
         * bundle-nativecode

         如需詳細資訊，請參閱說明檔案[這裡](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html#developing)。
   * **雲端轉換工具**

      * **內容傳輸工具的新增功能**

         * 內容傳輸工具——使用者對應工具新增功能和UI。 這項功能會自動將現有的使用者和群組對應至其Adobe Identity Management System ID，做為內容移轉活動的一部分。
請參閱[使用用戶映射工具](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-user-mapping-tool.html)。
         * 內容傳輸工具現在會移轉移移集（包括子系）中參考的所有群組和使用者。
         * 在建立遷移集時，允許用戶選擇`/etc`下的某些路徑。







### **社群**

* **Adobe Developers Live 2021 |完整作業清單**

   依常見要求，[此處](https://adobe.ly/3cldljt)是Adobe Developers Live中所有Experience Manager工作階段的匯總清單。 每個作業的所有錄制和問答都會張貼至其各自的內容相關執行緒。

* **Experience League最新Adobe Experience Manager內容清單 | 2021年1月**

   Adobe製作的數位體驗技術內容的官方來源。 請參閱[此處](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)的完整清單。

### Experience Manager 發行資訊

所有 Experience Manager 的發行說明都會保留在以下頁面：

* [Experience Manager 版本更新和藍圖](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager作為雲端服務的發行資訊](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/home.html)
* [Experience Manager Cloud Manager發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Automated Forms Conversion Service 發行說明](https://docs.adobe.com/content/help/zh-Hant/aem-forms-automated-conversion-service/using/release-notes.html)
* [Experience Manager 6.5 Service Pack發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager 6.4 Cumulative Fix Pack發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-64/release-notes/cfp-release-notes.html)
* [Experience Manager資產動態媒體發行說明](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Experience Manager Brand Portal發行說明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hant)
* [Experience Manager案頭應用程式版本注意事項](https://docs.adobe.com/content/help/zh-Hant/experience-manager-desktop-app/using/release-notes.translate.html)
* [Experience Manager Dispatcher發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre 發行說明](https://docs.adobe.com/content/help/zh-Hant/livefyre/using/release-notes/c-rn.translate.html)

### Experience Manager課程與教學課程

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 11 日 | [從外部應用程式驗證AEM為雲端服務](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | 課程 | 瞭解外部應用程式如何使用[!UICONTROL 本機開發存取Token]和[!UICONTROL 服務認證]，以程式設計方式透過HTTP驗證Experience Manager的雲端服務。 |
| 2021 年 2 月 11 日 | [關聯及取消關聯資產](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | 影片 | 瞭解如何在Experience Manager中建立和管理資產之間的關係。 |
| 2021 年 2 月 8 日 | [AEM Sites - WKND教學課程](https://docs.adobe.com/content/help/en/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html) | 教學課程 | 歡迎使用專為Experience Manager新手開發人員所設計的多部分教學課程。 本教學課程將逐步介紹Experience Manager網站對虛擬生活品牌WKND的實作。 |
| 2021 年 2 月 1 日 | [建立您的第一個OSGi Bundle](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/create-your-first-osgi-bundle.html?lang=en) | 文章 | 瞭解如何使用maven和eclipse建立您的第一個OSGi套件。 |
| 2021 年 2 月 1 日 | [發佈資產](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/publish.html) | 影片 | 瞭解如何從Experience Manager Author發佈資產及其轉譯至AEM Publish。 |
| 2021 年 2 月 4 日 | [地方開發](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/local-development-environment.html) | 影片 | 瞭解如何使用Experience Manager做為雲端服務SDK來下載並設定本機開發環境。 |
| 2021 年 2 月 4 日 | [專案結構](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/project-structure.html) | 影片 | 探索將AEM的Experience Manager Maven專案建構為雲端服務的最佳實務。 |
| 2021 年 2 月 4 日 | [遷移Dispatcher配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/dispatcher-configuration.html) | 影片 | 概述Dispatcher配置的差異，以及將Dispatcher從Adobe Managed Services(AMS)移轉至Experience Manager作為雲端服務的秘訣與訣竅。 |
| 2021 年 2 月 2 日 | [AEM SDK簡介](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/aem-sdk.html) | 影片 | 將Experience Manager的SDK當做雲端服務使用及設定。 |
| 2021 年 2 月 2 日 | [什麼是AEM Cloud服務](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/what-is-aem-as-a-cloud-service.html) | 影片 | 探索Experience Manager的雲端服務，以及它與其他Adobe Experience Manager版本的不同之處。 |
| 2021 年 2 月 2 日 | [Cloud Manager的角色](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/cloud-manager.html) | 影片 | 瞭解[!UICONTROL Cloud Manager]的用途，以及它如何與Experience Manager搭配使用作為雲端服務。 |
| 2021 年 2 月 2 日 | [AEM雲端服務的演變](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/evolution.html) | 影片 | 探索Experience Manager的歷史，以及內部部署Experience Manager、Adobe Managed Services AEM和Experience Manager作為雲端服務之間的差異。 |
| 2021 年 2 月 2 日 | [Assets as a Cloud Service 架構](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/architecture.html) | 影片 | 探索Experience Manager作為雲端服務的基礎架構和重要部分。 深入探討Cloud Manager和API。 |
| 2021 年 2 月 2 日 | [使用Cloud Manager API](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/cloud-manager-apis.html) | 影片 | 探索如何使用Cloud Manager API來擴充並整合其他系統。 |
| 2021 年 2 月 2 日 | [分析測試結果](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/analyze-test-results.html) | 影片 | 探索程式碼中的任何編譯錯誤，以及此程式碼是否遵循Experience Manager雲端服務的最佳實務 |
| 2021 年 2 月 2 日 | [配置管線](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/configure-pipelines.html) | 影片 | 在Cloud Manager中探索不同類型的管道，以及如何為成功的項目配置管道。 |
| 2021 年 2 月 2 日 | [管理Dispatcher配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/dispatcher-configurations.html) | 影片 | 使用最佳實務和範例來探索Dispatcher如何與Experience Manager搭配使用，如Cloud Service和Cloud Manager。 |
| 2021 年 2 月 2 日 | [持續整合與Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/continuous-integration.html) | 影片 | 瞭解使用Adobe Cloud Manager的最佳實務和持續整合。 |
| 2021 年 2 月 2 日 | [使用Cloud Manager合併AEM專案以進行部署](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/merge-projects.html) | 影片 | 探索如何將多個專案合併為單一專案，以便使用Cloud Manager以雲端服務的形式部署至Experience Manager。 |
| 2021 年 2 月 2 日 | [部署Cloud Manager專案](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/deploy-code.html) | 影片 | 將Cloud Manager Git儲存庫與外部Git儲存庫整合，並將項目作為Cloud服務部署到Experience Manager。 |
| 2021 年 2 月 2 日 | [內容發佈](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/content-publishing.html) | 影片 | 探索Experience Manager中以雲端服務形式發佈內容的運作方式，包括內容分發和Adobe管道的概念。 |
| 2021 年 2 月 2 日 | [Token型驗證——服務憑證](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials.html?lang=en#authentication) | 影片 | 瞭解Experience Manager雲端服務整合的代號式驗證。 |
| 2021 年 2 月 2 日 | [簽署多個表格](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/introduction.html?lang=en#sign-multiple-documents) | 教學課程 | 不論您是申請抵押或開立新的銀行帳戶，都必須填寫並簽署多份表格。 Experience Manager Forms與Adobe Sign的整合讓填寫和簽署多個表單變得輕鬆。 |
| 2021 年 1 月 28 日 | [Token型驗證——本機開發存取Token](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/local-development-access-token.html?lang=en#authentication) | 影片 | 瞭解Experience Manager的Developer Console如何讓開發人員自行產生暫時存取Token，以程式設計方式存取Experience Manager。 |
| 2021 年 1 月 28 日 | [AEM雲端服務的Token型驗證](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | 影片 | 瞭解外部應用程式如何使用存取Token，以程式設計方式驗證Experience Manager並透過HTTP與Cloud Service互動。 |
| 2021 年 1 月 24 日 | [建立主表單以觸發流程](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/create-initial-form.html) | 文章 | 初始表單（再融資表單）用於簽署多個表單，方法是觸發[!UICONTROL 簽署多個表單AEM]工作流程。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager CI/CD生產管道執行](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | 影片 | CI/CD Production Pipeline配置定義啟動管線的觸發器、控制生產部署的參數以及效能測試參數。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager活動](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/activity.html) | 影片 | Cloud Manager提供方案活動的整合檢視，列出所有CI/CD Pipeline執行，包括生產和非生產。 此功能可讓使用者檢視目前進行中的管道，並檢視先前的部署。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager CI/CD非生產管道](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-non-production-pipeline.html) | 影片 | CI/CD非生產管道分為代碼質量管道和部署管道兩類。 程式碼品質會從Git分支輸入所有程式碼，以根據Cloud Manager的程式碼品質掃描來建立和評估。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager CI/CD生產管道配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | 影片 | CI/CD Production Pipeline配置定義啟動管線的觸發器、控制生產部署和效能測試參數的參數。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager環境](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/environments.html) | 影片 | Cloud Manager環境由Experience Manager Author、Experience Manager Publish和Dispatcher服務組成。 不同的環境支援角色，可使用不同的CI/CD管道參與。 Cloud Manager環境通常有一個生產環境、一個階段環境和一個開發環境。 |
| 2021 年 1 月 8 日 | [無頭圖QL概述](https://internal.adobedemo.com/content/demo-hub/en/demos/internal/aem-headless-graphql.html) | 示範 | Experience Manager的GraphQL API會將內容從Experience Manager內容片段公開到下游應用程式。 GraphQL API可用於無頭和混合使用案例。 |
| 2021 年 1 月 8 日 | [Adobe Cloud Manager計畫](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/programs.html) | 影片 | Cloud Manager計畫代表一組Experience Manager環境，支援邏輯的業務計畫集，通常對應於購買的服務級別協定(SLA)。 |
| 2021 年 1 月 8 日 | [代號型驗證](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | 影片 | Cloud Manager計畫代表一組Experience Manager環境，支援邏輯的業務計畫集，通常對應於購買的服務級別協定(SLA)。 |
| 2021 年 1 月 8 日 | [大量匯入](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html) | 影片 | Experience Manager的Bulk Import（Cloud服務）工具可讓管理員以安全且有效率的方式，從雲端儲存空間（Azure Blob儲存空間或Amazon S3）大量匯入資產。 |

### Experience Manager的其他說明資源

* [Experience Manager雲端服務指南](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)
* [Experience Manager 6.4學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-4.html)
* [Experience Manager 6.3學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-3.html)
* [Experience Manager 6.2學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/tw/experience-manager/cloud-manager/user-guide.html)
* [舊版Experience Manager檔案](https://helpx.adobe.com/tw/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-classic/using/home.html)

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新產品版本

進一步瞭解發行的最新功能、改進和修正：

* [Campaign Standard 發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html)
* [Campaign Classic 發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html)

### 最新 Campaign 課程與教學課程

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 解決方法 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 5 日 | [適用於商業使用者的Adobe Campaign Classic快速入門](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.classic) | Campaign Classic | 完成本課程後，您將瞭解Adobe Campaign Classic的概念，並瞭解如何建立您的第一個行銷宣傳。 |
| 2021 年 2 月 1 日 | [多通道和跨通道簡介](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/introduction-to-cross-and-multi-channel-campaigns.html) | Campaign Classic | 瞭解多通道和跨通道促銷活動之間的差異，以及多通道和跨通道促銷活動的使用案例。 |
| 2021 年 2 月 1 日 | [建立簡訊傳送](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/sms-channel/create-a-sms-delivery.html) | Campaign Classic | 瞭解如何建立簡訊傳送。 |
| 2021 年 2 月 1 日 | [建立跨通道促銷活動](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/cross-channel-campaigns.html) | Campaign Classic | 瞭解如何建立和執行跨通道促銷活動。 |
| 2021 年 1 月 29 日 | [使用控制群組](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/use-control-groups.html) | Campaign Classic | 瞭解控制群組的概念，並瞭解如何使用控制群組進行傳送。 |
| 2021 年 1 月 28 日 | [傳送及驗證校樣](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/send-and-validate-proofs.html) | Campaign Classic | 瞭解如何傳送及驗證證明。 |
| 2021 年 1 月 28 日 | [設計電子郵件，以提供傳遞能力](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/design-emails-for-deliverability.html) | Campaign Classic | 瞭解如何套用傳遞能力最佳實務。 |
| 2021 年 1 月 28 日 | [建立和設計電子郵件傳送](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/create-and-design-email-deliveries.html) | Campaign Classic | 瞭解建立電子郵件傳送的程式，並瞭解如何設計和個人化電子郵件內容。 |
| 2021 年 1 月 27 日 | [建立事件觸發的促銷活動](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/getting-started/create-event-triggered-campaigns.html) | Campaign Classic | 瞭解如何建立事件觸發的促銷活動並瞭解其用途。 |

### 說明資源

* Adobe Campaign Standard：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/campaign-standard-home.html) - [發行說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/campaign-classic-home.html) - [發行說明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 作法影片

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 發行說明。

* [Advertising Cloud DSP 新功能](#adcloud-dsp)
* [Advertising Cloud Search 新功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新功能{#adcloud-dsp}

最新更新：**2020 年 10 月 28 日**

| 功能 | 說明 |
| -----------| ---------- |
| 新增說明 | (10 月 28 日發行) 舊版說明已更換為更新頁面，您可以透過 DSP 主功能表的「說明」連結加以存取，也可以隨時前往 [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) 參閱內容。 |
| Campaigns | (10 月 28 日發行) 先前的 Campaigns 測試版檢視現已成為 Campaigns 預設檢視，能提供更快速的深入分析、簡潔的工作流程和自訂檢視。 |
| 私人詳細目錄 | (10 月 15 日發行) 所有使用者現在都能使用新交易 ID 表單來設定及編輯交易 ID 詳細資訊，此表單是舊版[!UICONTROL 「智慧型廣告服務」]表單的簡化版本。若要設定新交易 ID 詳細資訊，請前往&#x200B;**[!UICONTROL 「詳細目錄 > 交易」]**，按一下&#x200B;**[!UICONTROL 「建立」]**，然後按一下&#x200B;**[!UICONTROL 「交易 ID 測試版」]**。 |
| 刊登版位預測 | (10 月 15 日發行) 若刊登版位具有從刊登版位層級調整的設計，其設定的[!UICONTROL 「預測」]區段現已加入新的[!UICONTROL 「預估上限」]區段，能顯示目前的鎖定目標設定有多少容量可用。 |

### [!DNL Advertising Cloud Search] 中的新功能{#adcloud-search}

更新日期：**2021 年 1 月 22 日 (1 月 23 日發行)**

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 搜尋 Campaigns]<br>報表 | Advertising Cloud Search 不再針對 Microsoft Advertising 促銷活動的新平均位置資料製作報表。從 1 月 23 日開始，「平均位置」欄的值會一律顯示為 0。這是為了因應 Microsoft 在 2021 年 1 月汰除平均位置資料所做的準備。<br>報表中仍會提供截至 1 月 22 日前所收集的平均位置資料。 |

### Ad Cloud 教學課程和課程

更新日期：**2020 年 12 月 2 日**

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需最新發行資訊，請參閱Magento Commerce和Open Source [發行說明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)。

## ![圖示](/assets/target.png)[!DNL Target] {#target}

如需最新版本的資訊，請參閱 [[!DNL Target]  發行說明](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html)。

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是銷售機會管理和B2B行銷人員的完整應用程式，希望透過參與複雜購買歷程的每個階段來轉變客戶體驗。

### Marketo Engage 核心更新

如需最新版本的資訊，請參閱 [!DNL Marketo Engage] [發行說明](https://docs.marketo.com/display/public/DOCS/Release+Notes)。

### 即將推出的功能

本季預計推出下列功能：

| 功能 | 說明 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>全新的帳戶型細分</li><li>儲存儀表板專有的篩選器</li><li>將 Bizible 儀表板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 淘汰

* **資產 API「_method」參數：** 2020 年 9 月後，資產 API 端點將不再接受於 POST 主體中使用 `_method` 傳遞查詢參數，以略過 URI 長度限制。
* **停止支援 Internet Explorer：**&#x200B;自 2020 年 7 月 31 日推出的版本開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

## ![圖示](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

針對 Adobe Document Cloud 發佈的新影片、教學課程和其他課程。

### Acrobat 教學課程

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日 | [Acrobat概觀登陸](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html) | 學習中心 | 歡迎使用Adobe Acrobat學習中心。 您將會發現以Adobe Acrobat為主的各種學習體驗。 我們的教學課程、網路研討會和使用案例旨在讓初學者和進階使用者都能快速上手使用Adobe Acrobat。 |

### Adobe Sign教學課程

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 8 日 | [概述著陸——支援資產](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html) | 學習中心 | 歡迎使用Adobe Sign學習中心。 您將會發現以Adobe Sign為主的各種學習體驗。 我們的教學課程、網路研討會和使用案例旨在讓初學者和管理員都能快速上手使用Adobe Sign。 |

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=en)
* [Adobe Sign 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=en)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![圖](/assets/creative-cloud-24.png) 示Creative Cloud Enterprise  {#creative-cloud}

Creative Cloud Enterprise的新教學課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 2 月 3 日 | [使用Photoshop製作電影](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/cinemagraphps.html?lang=en#cceoverview) | 影片 | 瞭解如何結合Adobe Stock的視訊與Photoshop中聰明的遮色片技巧，來建立栩栩如生的像片。 |
| 2021年2月3日 | [使用Adobe Stock和Photoshop for iPad建立獨特的構圖](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/compositepsipad.html?lang=en) | 影片 | 透過重新設計的觸控式介面，瞭解如何以全新方式使用您最愛的Creative Cloud應用程式。 |
| 2021 年 2 月 3 日 | [使用Dimension和Adobe Stock自訂3D模型並建立品牌](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/3ddimensionstock.html?lang=en) | 影片 | 使用材質、環境屬性、光線和攝影，在Dimension中自訂並品牌化3D模型，為任何設計專案建立逼真的影像。 |
| 2021 年 2 月 2 日 | [熟悉Adobe XD中的元件](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/xdoverview/components.html) | 影片 | 瞭解如何使用元件，讓您以前所未有的彈性，將速度和一致性套用至設計工作流程。 |
| 2021 年 2 月 2 日 | [CGI中控制3D光源的技巧與技巧](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/mastering3dlighting.html?lang=en) | 文章 | 瞭解3D光源以及如何建立可完全改變電腦產生的場景以及物件外觀的不同光線條件。 |
| 2021 年 2 月 2 日 | [使用3D彩現演算和構圖功能建立逼真的虛擬攝影](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/photorealistic.html?lang=en#3doverview) | 文章 | 瞭解如何使用3D彩現演算和構圖來建立逼真的虛擬攝影。 |
| 2021 年 1 月 29 日 | [CCE快速參考指南](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/overview-ref.html) | 快速參考指南 | 取用快速參考指南，協助您瞭解Creative Cloud的新功能。 |
