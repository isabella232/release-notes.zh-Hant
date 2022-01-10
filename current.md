---
title: 最新版本注意事項
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關 [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 最新的說明與教學課程
doc-type: release notes
last-update: November 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 8908cbcaf8fa0dbcc2f85cb9bbe8386dc9b68adb
workflow-type: tm+mt
source-wordcount: '4903'
ht-degree: 98%

---

# Adobe Experience Cloud 發行說明 - 2021 年 11 月

![橫幅](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] 應用程式和服務每月都會更新。 此頁面是尋找 [!DNL Experience Cloud] 和 [!DNL Experience Platform] 的最新版更新、文件與教學課程的中央位置。 您也可以尋找適用於 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 的新文件。

>[!NOTE]
>
>訂閱每月 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)，以接收此頁面更新的電子郵件通知。此頁面會在整個月進行維護，請定期回來查看是否有 Adobe 企業產品和 Experience League 文件的更新。

發行月： **2021年11月/12月**

最新更新：**2022 年 1 月 4 日**

* [[!DNL Experience League] 活動](#events) (2021 年 11 月 15 日更新)
* [[!DNL Experience Cloud Central Interface Components] 與管理](#ecloud)
* [Adobe [!UICONTROL 系統狀態]](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics) (**2022 年 1 月 4 日更新**)
* [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud) (**2021 年 10 月 27 日**)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/experience-league.png) [!DNL Experience League]活動 {#events}

若想了解 Adobe 產品專家的答案，Experience League Events 會是個好選擇。以下是可用的活動：

* [Experience League Live](#exl-live)：YouTube 上的直播和隨選視訊活動
* [社群問答咖啡會](#coffee)：在社群論壇中與產品經理聊天
* [Adobe Developer&#39;s Live](#dev-live)：Experience League 提供的隨選視訊活動

時間表和活動如下：

### Experience League Live{#exl-live}

[Experience League LIVE](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hant) 是 Experience League 團隊製作的直播串流節目。您可以藉此機會與 Adobe 產品專家交流，並學到您可以透過 Adobe Experience Cloud 應用程式應用可落實的秘訣、技巧和策略。

即將到來的活動：

| 活動日期 | 時間 | 活動名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021 年 11 月 18 日 | 下午 12 點 (EST) | [透過 Adobe Experience Manager 中的快速網站建立，以前所未有的速度直播](https://www.youtube.com/watch?v=7-Lcw5PejhI) | 即時視訊活動 | 只需幾天即可內部署功能豐富的個人化 Web 體驗，而無需後端開發。了解如何使用低程式碼方法，利用預先定義的[!UICONTROL 網站範本]在 Adobe Experience Manager 中建立網站。加入我們，與 Adobe 產品經理 Shankari Panchapakesan、Gabriel Walt 和 Danny Gordon 一起進行現場說明和示範。您甚至有機會看到現場編碼！ |

{style=&quot;table-layout:auto&quot;}

若想了解過去的影片內容，請參閱 [Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en)。

### 社群問答咖啡會{#coffee}

與特邀嘉賓共度一小時，並在 Experience League Communities 中提交您的問題，即可獲得 Adobe 產品專家的解答！

| 活動名稱 | 日期與時間 | 應用程式 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| Adobe Target — 設定和管理UI、A4T整合、AEM整合、一般UI | 12月8日星期三上午8點PT | Adobe Target | 論壇問答 | Adobe Target 資深產品經理 Robert Calangiu (也就是 @Robert_Calangiu) 將與我們一起進入 Adobe Target 社群，直接和您討論有關他專業領域的 Adobe Target 問題。<br>[詳細資訊](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-12-8-21-8am-pt-robert-calangiu/td-p/426697) |
| Adobe Campaign - 透過其他應用程式匯入資料 | 太平洋時間 2021 年 12 月 2 日星期四上午 8 點 | Adobe Campaign | 論壇問答 | 透過其他應用程式匯入資料 — 透過高級技術顧問Zariely Garcia，使用技術工作流程透過SFTP/API匯入資料的最佳實務。 <br>[詳細資訊](https://forms.office.com/Pages/ResponsePage.aspx?id=Wht7-jR7h0OUrtLBeN7O4UuYOxSr9BdGsLPtk3ITDIdUMFYwT0REQTk5RDZPTjlEWFlSUk1XWTBHVy4u&amp;wdLOR=cEEEC3C73-227C-457C-AA83-44CC08D697B9)。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Developer&#39;s Live{#dev-live}

| 活動名稱 | 日期與時間 | 主題 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2021 年 10 月 4 日至 5 日 | 隨選 | [Adobe Developers Live](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=zh-Hant) | 影片 | 錯過活動或尋找特定會議重播嗎？請在 Experience League 上尋找。Developers Live 會展示最新的技術進展和開發人員工具，藉以促進各產業的設計、內容創作工作流程、文件服務和客戶體驗管理。檢視專題演講、了解 Analytics API、客戶資料層、Adobe I/O 開放原始碼專案等等。 |

{style=&quot;table-layout:auto&quot;}

如需更多影片，請造訪 YouTube 上的 [Adobe Experience League 頻道](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)。

## ![圖示](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 與管理 {#ecloud}

| 功能 | 說明 |
| ------- | ------- |
| 首頁 | Experience Cloud 首頁頁尾資訊已移至用戶個人資料卡片，包括偏好設定中的法律注意事項和語言選擇。 |
| AEP 儀表板 | [!DNL Helios Lite]在 Experience Platform Widget 建立工作流程中提供圖表推薦。指定資料選擇 (目前為單一變數資料選擇)，[!DNL Helios] 會推薦適當的視覺化來配合該資料選擇。 |
| AEP 儀表板 | [!DNL Instory] 為圖表提供機器學習式書面敘述和字幕。它會在 AEP 儀表板頁面中裝飾圖表，並用相關的要點標註圖形資料中的主要變化和事件。 |

{style=&quot;table-layout:auto&quot;}

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理**&#x200B;的說明資源

* [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant)和使用者管理的管理說明
* [地點 - 定位服務](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)的協助和版本注意事項
* [人員 - 客戶屬性和對象庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hant)說明

## ![圖示](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

(如需 [!DNL Adobe System Status]的最新版本資訊，請參閱 [2020 年 5 月 21 日](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hant)版本注意事項。)

## ![圖示](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

包含 Experience Platform 和 [!UICONTROL Mobile SDK]  的版本更新資訊和新文件。

**2021年11月17日**

如需所有詳細資訊，請參閱 [Experience Platform 版本注意事項](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)。

### Experience Platform 教學課程與其他課程 {#tutorials-platform}

針對 Experience Platform 和服務所發佈的最新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [ 在第一方資料內容中的資料共同作業 ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/industry/data-collaboration-in-the-first-party-data-context.html?lang=zh-Hant#) | 影片 | 實踐體驗承諾，存取較少的資料。無論您是否為廣告商、發佈者或機關，此網路研討會有助於未來在無第三方 Cookies 的情況下解放共同作業機會。 |
| 2021 年 10 月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | 課程 | 了解 Experience Platform 的管理活動，包括權限和沙箱管理。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2021 年 10 月 28 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Adobe Analytics 中的修正](#aa-fixes)
* [Analytics 管理員重要通知](#aa-notices) (2022 年 1 月 4 日更新)
* [Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | 說明 | [全面發佈](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=zh-Hant) - 目標日期 |
| ----------- | ---------- | ------- |
| 在 Analysis Workspace 中分鐘層級的日期範圍 | 您可以在面板行事曆的進階設定下或在建立字訂日期範圍時，套用分鐘層級的日期範圍。如果您報告橫跨許多天的日期範圍，開始時間會套用至第一天，結束時間套用至您範圍中的最後一天。 | 2021 年 10 月 18 日 |
| [!UICONTROL 媒體播放時間] | Adobe 串流媒體播放[!UICONTROL 時間]提供寶貴的觀眾參與度深入分析，並可讓媒體組織透過進階花費時間分析及時段功能，以每分鐘的使用者參與度取得更深入、更細微的分析。您可以觀察在特定時間點觀看您的媒體串流所花費的時間多寡。您可以依不同的資料粒度 (包括新的 5 分鐘、15 分鐘和 30 分鐘資料粒度) 分割播放持續時間。[了解更多](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=zh-Hant) | 2021 年 10 月 18 日 |
| 快速[!UICONTROL 區段產生器] | 允許業務使用者快速在簡化的內嵌專案工作流程套用基本區段。無須前往「[!UICONTROL 區段生產器]」。[了解更多](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=zh-Hant) | 2021 年 10 月 21 日 |
| Analysis Workspace 左側邊欄搜尋改進 | 除了繼續說明元件造訪間隔和相關性之外，左側邊欄搜尋將 1) 以完全相符的搜尋結果為優先，優先程度高於廣泛的搜尋結果。2) 它會醒目提示符合的字元，以讓搜尋結果更能理解。3) 更輕鬆找到與維度相關的分類。4) 最後支援萬用字元 (`*`) 搜尋，以便更輕鬆找到所需的特定元件。注意：萬用字元搜尋在維度項目層級尚不可用。 | 2021 年 10 月 21 日 |
| 深色主題 | [深色主題](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/user-preferences.html?lang=zh-Hant#dark-theme)會作為顯示選項提供。 | 2021 年 10 月 21 日 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | 說明 | [全面發佈](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=zh-Hant) - 目標日期 |
| ----------- | ---------- | ----- |
| 在 Analysis Workspace 中分鐘層級的日期範圍 | 您可以在面板行事曆的進階設定下或在建立字訂日期範圍時，套用分鐘層級的日期範圍。如果您報告橫跨許多天的日期範圍，開始時間會套用至第一天，結束時間套用至您範圍中的最後一天。 | 2021 年 10 月 18 日 |
| 快速[!UICONTROL 篩選產生器] | 允許業務使用者快速在簡化的內嵌專案工作流程套用基本區段。無須前往「[!UICONTROL 篩選產生器]」。[了解更多](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=zh-Hant) | 2021 年 10 月 21 日 |
| Analysis Workspace 左側邊欄搜尋改進 | 除了繼續說明元件造訪間隔和相關性之外，左側邊欄搜尋將 1) 以完全相符的搜尋結果為優先，優先程度高於廣泛的搜尋結果。2) 它會醒目提示符合的字元，以讓搜尋結果更能理解。3) 更輕鬆找到與維度相關的分類。4) 最後支援萬用字元 (`*`) 搜尋，以便更輕鬆找到所需的特定元件。注意：萬用字元搜尋在維度項目層級尚不可用。 | 2021 年 10 月 21 日 |
| 深色主題 | [深色主題](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-workspace/user-preferences.html?lang=zh-Hant#dark-theme)會作為顯示選項提供。 | 2021 年 10 月 21 日 |
| 維度位置的回顧視窗 | 最多 90 天的回顧視窗新增至資料檢視設定中持續性下方的維度配置設定。[了解更多](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html?lang=zh-Hant) | 2021 年 10 月 28 日 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 中的修正 {#aa-fixes}

* 已修正無法在警報管理器中刪除警報的問題。(AN-270656)
* 已修正 Data Warehouse 要求斷斷續續失敗的問題。(AN-273713、AN-272790)
* 已修正分類未更新的問題。(AN-272211)

### Customer Journey Analytics 中的修正 {#cja-fixes}

* 已修正 CJA 效能問題 (載入專案時的錯誤訊息)。(AN-269451、AN-270649)
* 已修正在 CJA 中工作階段開始不符合頁面名稱流量項目的問題。(AN-273501)
* 已修正 CJA 中流失報告未正常作用的問題。(AN-269761)

#### Adobe Analytics 中的其他修正

AN-263327；AN-267807；AN-269757；AN-272789；AN-272888；AN-273155；AN-273320；AN-273369；AN-273405；AN-273469；AN-273581；AN-273642；AN-273688；AN-273988；AN-274007；AN-274030；AN-274156；AN-274188；AN-274226

#### CJA 中的其他修正

AN-270649

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| Reports &amp; Analytics 生命週期結束 | 2022 年 1 月 4 日 | 自 **2023 年 12 月 31 日**&#x200B;起生效，Adobe 計畫停止支援 Reports &amp; Analytics 及其隨附的報告和功能。支援 Reports &amp; Analytics 的報告、視覺效果和基礎技術不再符合 Adobe 的技術標準。大部分的 Reports &amp; Analytics 功能都可在 [Analysis Workspace](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/home.html?lang=zh-Hant) 中使用。自 Analysis Workspace 在 2015 年發佈以來，Reports &amp; Analytics 功能已移至 Analysis Workspace 並已達到工作流程同位臨界值。[本通知](https://spark.adobe.com/page/6WnF8JK6IRDhf)說明生命週期結束程序。 |
| 「全球 + 中國」RDC 類型 | 2021 年 11 月 22 日 | 「全球 + 中國」是一種新的地區資料收集 (RDC) 類型，它使用[!UICONTROL 中國效能最佳化附加元件套件]簡化了全球客戶的流量路由。在過去，您必須決定資料應該路由至中國收集端點或其中一個全球收集端點。現在您可以選擇這個 RDC **類型**，讓 Adobe 根據用戶的地理位置來決定最佳收集端點。 |
| 三個 Analytics API 服務生命週期結束 | 2021 年 9 月 16 日 | 下列 Analytics Legacy API 服務將在 **2021 年 10 月 20 日**&#x200B;結束生命週期並關閉。 目前使用這些服務建立的所有整合功能都將於當天停止運作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy OAuth 驗證 (OAuth 和 JWT)</li></ul>Adobe提供 [舊版API EOL常見問題集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) 以協助回答您的問題，並提供如何進行的指引。 採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy OAuth 帳戶可移轉為 [Adobe I/O](https://developer.adobe.com/console) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| 資料來源中完整處理的生命週期結束 | 2021 年 10 月 18 日 | 在 **2022 年 1 月 31 日**，Adobe 將終止完整處理的服務。此服務可讓用戶將離線點擊資料擷取至 Analytics。此功能透過 [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) 提供。[了解更多](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=zh-Hant?lang=zh-Hant) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

如需 AppMeasurement 發行版本 (版本 2.22.2) 的最新更新，請參閱 [AppMeasurement for JavaScript 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)。

### Analytics 課程與教學課程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 的最新課程、教學課程和文章。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [Adobe Analytics 中的區段容器](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-containers.html?lang=zh-Hant) | 影片 (已更新) | 在此影片中，了解如何使用容器並聆聽每種容器類型的部分範例。 |
| 2021 年 11 月 | [Adobe Analytics 中的順序分段](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/sequential-segmentation.html?lang=zh-Hant#) | 影片 (已更新) | 了解如何依據您的網站上或應用程式中的行為順序，在 Analysis Workspace 中建立區段。 |
| 2021 年 11 月 | [在順序分段中的前/後順序](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/before-after-sequences-in-sequential-segmentation.html?lang=zh-Hant) | 影片 (已更新) | 了解如何在 Adobe Analytics 中分段，以便於僅從特定用戶路徑前或後取得資料。 |
| 2021 年 11 月 | [適用於 Customer Journey Analytics 的 Report Builder](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/report-builder-for-customer-journey-analytics.html?lang=zh-Hant) | 影片 | 透過 Report Builder 簡單靈活拖放 UI，就能在 Excel 中從 Customer Journey Analytics 資料建立複雜的資料查詢和自訂報表。 |
| 2021 年 10 月 | [使用視覺效果訴說您的資料故事](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | 課程 | 學習視覺效果的基本知識，包括如何將視覺效果新增至專案、讓資料融入視覺效果，以及每個視覺效果可以向您顯示的內容。了解如何進行設定，以取得您所需的確切資料。此外，取得一些秘訣和使用案例，協助您讓視覺效果為定期分析助一臂之力。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 說明資源

* [Adobe Analytics 產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修正與改良。

* 已解決在透過 Swagger 介面執行時導致所有 API 呼叫傳回 `Undocumented` 錯誤的問題。(AAM-59190)
* 已解決在某些情況下導致指派錯誤的用戶角色給合作夥伴的問題。(AAM-59451)
* 已解決導致 API 要求區分大小寫驗證標題的問題。(AAM-58528)

## ![圖示](/assets/aem.png) Experience Manager {#aem}

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以掌握最新的版本資訊。

### 版本總覽影片

* [2021 年 12 月版本總覽](https://video.tv.adobe.com/v/339278)新功能影片。
* [2021 年 10 月版本總覽](https://video.tv.adobe.com/v/338253) 新功能影片。
* [2021 年 9 月版本總覽](https://video.tv.adobe.com/v/337381) 新功能影片。

### 社群

* [Adobe Developers Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021 年 10 月 4-5 日，7:00 PDT

   Adobe Developers Live 匯集多元背景的 Adobe 開發人員和有經驗的建置者，其目的只有一個，就是創造令人驚艷的端對端體驗。此雙向會議提供重要的開發人員更新、技術研討會，以及社群交流機會。

   橫跨 Experience Cloud、Document Cloud 和 Creative Cloud 的 Adobe 產品團隊會展示最新的技術進展和開發人員工具，藉以促進各產業的設計、內容創作工作流程、文件服務和客戶體驗管理。

   Adobe 已規劃 20 場 Experience Manager 研討會。宣傳訊息！

   * [完整的研討會清單](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [免費註冊 – 登入 RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe Developers Live Community](https://experienceleaguecommunities.adobe.com:443/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-4th-amp-5th/td-p/422127)

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 說明 | 類型 | 版本 |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021 年 11 月 | [Adobe Experience Manager Sites 基本知識](https://experienceleague.adobe.com/docs/experience-manager-skill-builder/skill-builder/2021/authoring-fundamentals.html?lang=zh-Hant) | 影片系列 | 在此 5 節的網路研討會系列，了解如何在 Adobe Experience Manager 中打造豐富、精彩的客戶體驗。從內容製作的組成要素開始，同時學習基礎概念與作業。學習網站管理功能與在 AEM 內處理數位資產的基本知識。之後透過重複使用內容並在通路間提供內容的方式，探索有助於節省時間、變得更有效率的功能。 | AEM Sites |
| 2021 年 11 月 | [規劃邁向 AEM as a Cloud Service 之旅](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2021.1.migration) | 課程 | 了解邁向 AEM as a Cloud Service 的考量及簡化程序的可用工具。 | AEM CS |
| 2021 年 11 月 | [邁向 AEM as a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2021.1.migration) | 課程 | 了解如何從 AEM 6 成功邁向 Experience Manager as a Cloud Service。 | AEM CS |
| 2021 年 11 月 | [下載互動式 DoR](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/generate-interactive-dor.html?lang=zh-Hant#create-custom-servlet) | 影片 | 了解如何下載包含 Adaptive Form 資料的互動式 DoR。 | AEM Forms |
| 2021 年 11 月 | [Adobe Experience Manager as a Cloud Service 專家系列](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/aem-experts-series.html?lang=zh-Hant) | 影片系列 | 向建置 Adobe Experience Manager (AEM) as a Cloud Service 的 Adobe 專家工程師與提供該產品的 Professional Services 團隊學習。加入 Adobe 專家的行列，探索什麼是 AEM as a Cloud Service、其與 AEM 6 的比較，以及如何從 AEM 6 邁向 AEM as a Cloud Service。 | AEM CS |
| 2021 年 11 月 | [服務用戶](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/advanced/service-users.html?lang=zh-Hant)  | 影片 | 了解如何在您的 AEM 程式碼中建立和使用服務用戶，以提供 AEM 存放庫的受控制程式設計存取權。 | AEM CS |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 版本資訊 {#aem-links}

在此提供 Experience Manager 的版本注意事項和其他版本資訊連結：

* [[!DNL Experience Manager as a Cloud Service] 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=zh-Hant)
* [[!DNL Experience Manager as a Cloud Service] 版本資訊](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=zh-Hant)
* [[!DNL Experience Manager Cloud Manager] 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hant)
* [Automated Forms Conversion Service 版本注意事項](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hant)
* [Experience Manager 6.5 Service Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=zh-Hant)
* [Experience Manager 6.4 Cumulative Fix Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hant)
* [[!DNL Experience Manager Assets Dynamic Media] 版本注意事項](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hant)
* [[!DNL Experience Manager Brand Portal] 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hant)
* [Experience Manager 桌面應用程式版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hant)
* [[!DNL Experience Manager Dispatcher] 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hant)
* [Adobe Primetime 版本注意事項](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hant)
* [Livefyre 版本注意事項](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hant)

### 適用於 Experience Manager 的其他說明資源

* [[!DNL Experience Manager as a Cloud Service] 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=zh-Hant)
* [Experience Manager 6.5 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hant)
* [Experience Manager 6.4 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hant)
* [Experience Manager 6.3 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant)
* [Experience Manager 6.2 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant#previous-updates)
* [舊版 Experience Manager 文件](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] 使用手冊](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hant)
* [[!DNL Dynamic Media Classic] 說明首頁](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hant)
* [Experience Manager 文件：最近更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hant#aem-as-a-cloud-service)

## ![圖示](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教學課程 {#commerce-tutorials}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [Adobe Commerce 影片和教學課程](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/overview.html?lang=zh-Hant) | 教學課程首頁 | 這些教學課程資源包括提供主題高階檢視的影片系列，以及針對特定任務和程序的個別影片。此系列旨在為後端開發人員、前端開發人員、系統管理員、商家及您組織中的其他角色，提供實用的內容 。 |

## ![圖示](/assets/target.png) [!DNL Target] {#target}

最近更新日期：**2022 年 1 月 6 日**

如需最新版本資訊，請參閱 [[!DNL Target]  版本注意事項](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品發行版

進一步了解已發行的最新功能、改良與修正：

* [Campaign v8 版本注意事項](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=zh-Hant)
* [Campaign Classic v7 版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)
* [Campaign Standard 版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant)

### 最新 [!UICONTROL Campaign] 課程與教學課程 {#tutorials-campaign}

針對 Adobe Campaign 的最新教學課程和課程。

| 已發佈 | 名稱 | 說明 | 類型 | 版本 |
| -----------| ---------- | ---------- |---------- | ---------- |
| 2021 年 11 月 | [將 Campaign 連線至 Experience Platform 作為目的地](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/connect-campaign-to-experience-platform-as-destination.html?lang=zh-Hant) | 影片 | 了解如何使用 Amazon S3 連線類型啟用 Adobe Experience Platform 區段至目的地。 | AEP &amp; Campaign V8 |
| 2021 年 11 月 | [與 Experience Platform 整合 — 概覽](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/overview.html?lang=zh-Hant) | 影片 | 了解如何在 Campaign 和 Experience Cloud 之間共用資料。 | AEP與行銷活動V8 |
| 2021 年 11 月 | [從 Experience Platform 匯入收件者資料並傳送電子郵件](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-platform/import-experience-platform-data-into-campaign/import-recipient-data-from-platform.html?lang=zh-Hant) | 影片 | 了解如何在 Adobe Campaign 中設定外部帳戶，將收件者資料從 Adobe Experience Platform 匯入至 Campaign。 了解如何建立工作流程來上傳和定位從 Experience Platform 接收的收件者。 | AEP與行銷活動V8 |
| 2021 年 11 月 | [在工作流程中使用 SOAP API](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=zh-Hant) | 教學影片 | 了解如何使用 Adobe Campaign Soap API 並根據透過 API 接收的資料建立進階傳送工作流程。 | Campaign V8 |

{style=&quot;table-layout:auto&quot;}

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [發行說明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=zh-Hant) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 做法影片

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

有了 Adobe Journey Optimizer，您就可以從單一應用程式為幾百萬名客戶管理排程的全通道行銷活動及一對一時刻，還有智慧型決策和見解讓整個旅程最佳化。

### 最新 Journey Optimizer 產品發行版

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

### Journey Optimizer 教學課程和課程 {#tutorials-ajo}

最新的 Journey Optimizer 教學課程：

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [針對資料工程師設定並管理  [!DNL Journey Optimizer]  中的資料](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | 課程 | 了解如何設定並管理 Journey Optimizer 中歷程管理所需的資料。 |
| 2021 年 10 月 | [開始使用 Journey Administrators 和 Managers 的  [!DNL Journey Optimizer] ](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | 課程 | 了解建立第一個歷程所需的每件事。 |
| 2021 年 10 月 | [設定 Journey Administrators 的 [!DNL Journey Optimizer] ](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | 課程 | 了解 [!DNL Journey Optimizer] 架構和整合點。了解如何設定 [!DNL Journey Optimizer]。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hant)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

運用 Experience Platform 聰明地即時預測每個人的需求，在不同體驗管道大規模地協調客戶歷程。

### 最新 [!DNL Journey Orchestration] 產品發行版

進一步了解 [[!DNL Journey Orchestration]  版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

#### [!DNL Journey Orchestration] 的更多資源

* [Journey Orchestration 文件](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是適用於潛在客戶管理以及想要透過參與複雜購買旅程的每個階段來轉換客戶體驗的 B2B 行銷人員的完整應用程式。

### Marketo Engage 核心更新

如需最新發行排程資訊和版本注意事項，請參閱「[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)」。

## ![圖示](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] 是統一的工作管理應用程式，用於共用構想、建立內容、管理複雜的流程並執行其最佳工作。

請參閱 [[!DNL Workfront]  發行版本](https://one.workfront.com/s/product-releases)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 版本注意事項。

* [ [!DNL Advertising Cloud] 的新功能](#adcloud-all)
* [ [!DNL Advertising Cloud DSP] 中的新功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新功能](#adcloud-search)

### [!DNL Advertising Cloud] 的新功能 {#adcloud-all}

最新更新：**2021 年 10 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| Analytics for Advertising Cloud | 如果您的組織想從使用舊版 Adobe Analytics `visitorAPI.js`資料庫切換到使用 Adobe Experience Platform 資料庫 (`alloy.js`) 進行資料彙集，您需要進行一些變更以啟用識別碼拼接。請參閱「[在 Adobe Experience Platform 中使用  [!DNL Last Event Service] JavaScript 資料庫 [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=zh-Hant)」。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud DSP] 中的新功能 {#adcloud-dsp}

最新更新：**2021 年 10 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| 自訂報告 | 您現在可以為自訂報告建立和管理 [!DNL Amazon S3] 和不同類型的 FTP 傳送位置，稱為 *[!DNL report destinations]*。設定報告目標後，您可以將每個新的自訂報告設為傳送到單一目標類型的一個或多個位置，或傳送到電子郵件收件者。更新您的 [!DNL Amazon S3]，則 FTP 認證將不會中斷報告傳遞。<br>您現有的報告仍會傳送到指定的電子郵件收件者。若要設定傳遞到不同的報告目標，請使用新目標建立新報告。 |
| [!UICONTROL 套件]，[!UICONTROL 位置]，和 [!UICONTROL 廣告]檢視 | 當您查看某一天的資料時，趨勢圖表將包括每小時資料。將游標放在任意點上可查看該小時的資料。 |
| [!UICONTROL 位置] | 位置[!UICONTROL 檢查]現在包含[!UICONTROL 詳細目錄]標籤，顯示位置的所有交易及其相關指標。使用這些資訊進行快速調整或疑難排解問題，而無需產生自訂報告。 |
| [!UICONTROL 廣告] | (有權在其廣告中包含 Clearcastclock 數字的用戶) 如果您使用附加到其他廣告的時鐘數字，DSP 將不再顯示錯誤。**請注意：**&#x200B;最佳實務是為每個廣告影片使用唯一的時鐘數字。否則，發佈者將不會核准所有廣告。 |
| [!UICONTROL 交易識別碼] | [!UICONTROL 交易識別碼]設定和用戶界面中的其他地方反映了 [!DNL Magnite]SSP 的新品牌：<ul><li>SSP「[!DNL Tremor]」([!DNL Telaria]) 現為「[!DNL Magnite CTV]」。</li><li>在接下來的幾週內，「[!DNL Rubicon]」將變更為「[!DNL Magnite DV+]」，其中 [!DNL DV+] 代表顯示、影片和其他格式，例如音訊。</li></ul> |
| [!DNL Freewheel]程式化預留交易 | 現在您可以從[!UICONTROL 廣告]檢視中找到 [!DNL Freewheel] 程式化預留交易的廣告狀態。以前您只能從[!UICONTROL 交易]檢視中查看狀態。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

最新更新：**2021 年 10 月 7 日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 報告]、[!UICONTROL 通知中心] | (10 月 9 日發行) 報告的所有電子郵件通知目前都由[!UICONTROL 通知中心]處理。這些通知是 Advertising Cloud Search 在自訂或排程報告完成或失敗時傳送。報告預設為啟用電子郵件通知與 Web 通知預設，但您可以選擇變更通知設定。進行此變更：<ul><li>電子郵件收件者限為已註冊的用戶、已驗證身分的 Advertising Cloud Search 用戶，以及存取廣告商帳戶的用戶。此功能可確保不會將機密資訊傳送給未經授權的用戶。</li><li>電子郵件的格式與內容使用[!UICONTROL 通知中心]範本，其中包括報告的詳細資訊與所有報告格式的直接下載連結。</li><li>報告通知是[!UICONTROL 通知中心]中新的通知類型，有自己的通知偏好設定。</li></ul>如果您有任何從電子郵件通知提取報告的自動化作業，您可能需要更新篩選邏輯，以確保程序不中斷。 |
| 廣告分析 | Beta 版模式提供其他深入分析。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

針對 Adobe Document Cloud 發佈的新影片、教學課程或其他課程。

### Document Cloud 課程與教學課程 {#tutorials-doc-cloud}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 11 月 | [工作區基本知識](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/get-to-know-the-acrobat-dc-interface.html?lang=zh-Hant) | 影片 (已更新) | 了解 Acrobat DC 介面如何讓您在桌面、網頁和行動裝置之間輕鬆存取檔案和工具，並享有一致的工作區體驗。 |
| 2021 年 11 月 | [使用網頁版 Acrobat 隨時隨地工作](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/acrobatweb.html?lang=zh-Hant) | 影片 | 了解如何在瀏覽器中使用網頁版 Acrobat 工具隨時隨地處理企業文件要求。 |
| 2021 年 11 月 | [在 Office 網頁版中建立 PDF ](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/createofficeweb.html?lang=zh-Hant) | 影片 | 了解即使離開網頁應用程式的 Microsoft® Office，也能建立 PDF 檔案。此附加元件需要適用於團隊的 Acrobat DC 訂閱或適用於企業的 Acrobat DC 訂閱。 |
| 2021 年 11 月 | [即時共同作業](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/collaborate.html?lang=zh-Hant) | 影片 | 隨時隨地即時收集註釋、共同處理回應及追蹤文件的進度，推展您的專案。 |
| 2021 年 11 月 | [ 機動生產力](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/productivity.html?lang=zh-Hant) | 影片 | 使用 Acrobat Reader 行動應用程式，以平板電腦或手機完成更多工作。 |

{style=&quot;table-layout:auto&quot;}

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) 適用於企業的 Creative Cloud {#creative-cloud}

如需了解最新教學課程，請參閱「[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hant)」。
