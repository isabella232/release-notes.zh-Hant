---
title: 最新版本注意事項
description: 了解 [!DNL Experience Cloud] 產品和服務的最新發行說明、新功能和新檔案。 尋找關於 [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud]的新說明和教學課程。
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 2ad6cb4ae1ae0c9a9414df7c1360a3d4d428f1e5
workflow-type: tm+mt
source-wordcount: '5271'
ht-degree: 39%

---

# Adobe Experience Cloud 發行說明 - 2021 年 10 月

![橫幅](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] 應用程式和服務每月都會更新。 此頁面是尋找 [!DNL Experience Cloud] 和 [!DNL Experience Platform] 的最新版更新、文件與教學課程的中央位置。 您也可以尋找適用於 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 的新文件。

>[!NOTE]
>
>訂閱每月 [Adobe 優先產品更新](https://www.adobe.com/subscription/priority-product-update.html)，以接收此頁面更新的電子郵件通知。此頁面會在整個月進行維護，請定期回來查看是否有 Adobe 企業產品和 Experience League 文件的更新。

最近更新：**2021 年 10 月 1 日**

* [[!DNL Experience League] 直播活動](#events)
* [[!DNL Experience Cloud Central Interface Components] 與管理](#ecloud)
* [Adobe [!UICONTROL 系統狀態]](#status)
* [[!DNL Adobe Analytics]](#analytics) 和 [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/experience-league.png) [!DNL Experience League] 直播活動 {#events}

[!DNL Experience League] 直播活動是與 Adobe 專家和特別來賓的討論會，這些人會向您介紹 Adobe 技術。 請參閱以下時間表並加入我們的直播活動，或是觀看之前錄製的活動。

| 活動日期 | 活動名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 9 月 23 日 | [讓您的假日行銷活動脫穎而出的專家秘訣](https://www.youtube.com/watch?v=bsU1lAv0xes) | 直播視訊活動 | 就像開始您的節日購物永遠都不嫌早一樣，開始規劃大獲成功的節日行銷活動也永遠都不嫌早。 有了 Adobe Campaign，您可以設計、規劃及執行行銷活動，好讓貴組織的所有節日願望都成真。<br>但您知道在一年結束時，要推出哪些宣傳技巧嗎？與桑德拉一起參加一場現場討論，三位Adobe專家在這方面擁有豐富的集體經驗。 |
| 2021 年 8 月 26 日 | [讓您的下一個受眾區段比以往都還要聰明](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=zh-Hant) | 活動錄製 | 每一個出色的行銷活動的成功都取決於精確鎖定您的對象。 有了全新的 Adobe Experience Platform [!UICONTROL 區段產生器]，您可以使用各個管道中的個人檔案資料及取決於時間的用戶行為來建立您的下一個受眾區段。 沒有比這個更好的方式可確保您的訊息能傳達給最需要聽到的人了。 |
| 2021 年 7 月 29 日 | [我最愛的三個 Adobe Analytics 實作秘訣](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=zh-Hant) | 活動錄製 | 他之前曾經出現在 Summit 的講台上。 他也曾經在 Adobe Insider Tour 中分享專家建議。 您或許也曾經在自己的 Adobe Analytics 實作中跟他合作過而受益。 現在，Eric Matisoff 帶著他最愛的三個 Adobe Analytics 實作秘訣來參加這場獨家的 Experience League 直播討論會。 |

{style=&quot;table-layout:auto&quot;}

如需更多影片，請造訪 YouTube 上的 [Adobe Experience League 頻道](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw)。

## ![圖示](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 與管理 {#ecloud}

| 功能 | 說明 |
| ------- | ------- |
| 整合式搜尋 | 統一搜索繼續將對象類型添加到搜索索引中。 在此更新中，全域搜尋現在會跨Experience League內容和下列Journey Optimizer物件類型進行搜尋： <ul><li>資料集</li><li>目的地</li><li>查詢</li><li>方案</li><li>區段</li><li>來源</li><li>優惠</li><li>元件</li><li>訊息</li><li>歷程</li></ul> |
| 產品使用資料同意 | 初次登入時，系統會要求您根據Experience Cloud產品使用資料，提交偏好設定，以了解Adobe如何能為您提供實用的個人化內容，例如教學課程、指南、快速提示、建議、學習影片等。 此請求也包含您在<https://experience.adobe.com/preferences>收集和使用這些資料偏好設定的更新。 |
| Experience Cloud[!UICONTROL 觸發器]導覽 | [Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) 觸發器可供布建使用者從標題中的應用程式切換器直接導覽。 |
| **通知：** 計畫的介面導航更新 | 2021年11月，_[!UICONTROL 前往Launch /資料收集]_&#x200B;導覽功能將從<https://experience.adobe.com/implement>中移除。 |

{style=&quot;table-layout:auto&quot;}

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理**&#x200B;的說明資源

* [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant)和使用者管理的管理說明
* [地點 - 定位服務](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)的協助和版本注意事項
* [People — 客戶屬性和受眾程式庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)相關說明

## ![圖示](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

(如需 [!DNL Adobe System Status]的最新版本資訊，請參閱 [2020 年 5 月 21 日](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hant)版本注意事項。)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2021 年 10 月 7 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Adobe Analytics 中的修正](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | 說明 | [全面發佈](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=zh-Hant) - 目標日期 |
| ----------- | ---------- | ------- |
| Analytics控制面板的視覺效果 | Analytics [!UICONTROL 控制面板]推出三種新的視覺效果，讓執行人員和決策者更容易了解其資料。 新的[!UICONTROL Dougnut]、[!UICONTROL Line]和[!UICONTROL Horizontal]長條圖都使查看單個維項的資料更加容易，而無需開啟詳細資訊視圖。 （後續檔案連結） | 2021 年 10 月 7 日 |
| [!UICONTROL 媒體播放逗留時間] | Adobe串流媒體播放[!UICONTROL 逗留時間]提供檢視者參與的寶貴分析，並可讓媒體組織透過具有日劃分功能的進階逗留時間分析，針對每分鐘的使用者參與，取得更深入、更精細的深入分析。 您可以觀察在特定時間點檢視媒體資料流所花費的時間。 您可以依不同的粒度來分割播放持續時間，包括新的5分鐘、15分鐘和30分鐘粒度。 [了解更多](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 2021 年 10 月 18 日 |
| 快速[!UICONTROL 區段產生器] | 可讓商務使用者以簡化的串列專案工作流程，快速套用基本區段。 無需前往[!UICONTROL 區段產生器]。 [了解更多](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 2021 年 10 月 21 日 |
| Analysis Workspace左側邊欄搜尋改善 | 除了繼續考慮元件時近和相關性外，左側邊欄搜尋會1)將完全相符的項目排在廣泛相符項目之上。 2)突出顯示匹配的字元，使搜索結果更易理解。 3)更容易找到與維度相關的分類。 4)最後，它支援通配符(`*`)搜索，以便更輕鬆地查找所需的特定元件。 注意：尚未在維度項目層級使用萬用字元搜尋。 | 2021 年 10 月 21 日 |
| Analysis Workspace暗主題 | 深色主題可作為顯示選項使用。 | 2021 年 10 月 21 日 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | 說明 | [全面發佈](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - 目標日期 |
| ----------- | ---------- | ----- |
| Report Builder支援 | Report Builder是Microsoft® [!DNL Excel]增益集，可讓您使用Customer Journey Analytics資料輕鬆建立、編輯和重新整理自訂報表。 透過Report Builder和Excel，您可以使用簡單但有彈性的拖放UI，輕鬆建立複雜的資料請求。 使用Report BuilderCustomer Journey Analytics，您可以：<ul><li>參考現有的工作表儲存格，以取得完美的列順序、日期範圍或篩選</li><li>使用日曆、儲存格參考或日期數學建立自訂日期</li><li>使用熟悉的Excel格式工具設計表格和視覺效果</li><li>在macOS、Microsoft 365(Web)和Microsoft Windows上提供</li></ul> | 2021 年 10 月 7 日 |
| Analytics控制面板的視覺效果 | Analytics [!UICONTROL 控制面板]推出三種新的視覺效果，讓執行人員和決策者更容易一目瞭然地了解其資料。 新的環圈圖、折線圖和水準條圖都可讓您更輕鬆地查看個別維度項目的資料，而無須開啟詳細資訊檢視。 （後續檔案連結） | 2021 年 10 月 7 日 |
| Customer Journey Analytics稽核記錄（僅限API） | 審核日誌是安全合規性以及審核資料和用戶操作的重要部分。 | 2021 年 10 月 7 日 |
| 快速[!UICONTROL 篩選產生器] | 可讓商務使用者以簡化的串列專案工作流程，快速套用基本區段。 無需前往[!UICONTROL 篩選產生器]。 [了解更多](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 2021 年 10 月 21 日 |
| Analysis Workspace左側邊欄搜尋改善 | 除了繼續考慮元件時近和相關性外，左側邊欄搜尋會1)將完全相符的項目排在廣泛相符項目之上。 2)突出顯示匹配的字元，使搜索結果更易理解。 3)更容易找到與維度相關的分類。 4)最後，它支援通配符(`*`)搜索，以便更輕鬆地查找所需的特定元件。 注意：尚未在維度項目層級使用萬用字元搜尋。 | 2021 年 10 月 21 日 |
| Analysis Workspace暗主題 | 深色主題可作為顯示選項使用。 | 2021 年 10 月 21 日 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 中的修正 和 CJA {#aa-fixes}

* 修正排程報表的Customer Journey Analytics錯誤。 (AN-271721)
* 修正[!UICONTROL Workspace]中的[!UICONTROL 搜尋元件]未產生完全相符的問題。 (AN-253937；AN-271707)

#### Adobe Analytics 中的其他修正

AN-256136;AN-265420;AN-268455;AN-269768;AN-270276;AN-270287;AN-271601;AN-271969;AN-272056;AN-272111;AN-272457

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 三個 Analytics API 服務生命週期結束 | 2021 年 9 月 16 日 | 2021年10月28日&#x200B;**當天，下列Analytics Legacy API服務將到期並關閉。**&#x200B;所有目前使用這些服務建立的整合功能將於當天停止運作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy OAuth 驗證 (OAuth 和 JWT)</li></ul>Adobe 提供了[舊版 API 生命週期結束常見問答](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)來回答您的問題，並指引您展開後續操作。 採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy OAuth 帳戶可移轉為 [Adobe I/O](https://developer.adobe.com/console) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

如需 AppMeasurement 發行版本 (版本 2.22.2) 的最新更新，請參閱 [AppMeasurement for JavaScript 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)。

### Analytics 課程與教學課程 {#tutorials-analytics}

[!DNL Analytics]和[!UICONTROL Customer Journey Analytics]的最新課程、教學課程和文章。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [使用視覺效果來講述您的資料故事](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | 課程 | 誰想逐個清理表格，只是試圖從資料中提取見解？ 不是你！ 在本課程中，您將了解視覺效果的基本知識，包括如何將視覺效果新增至專案、將資料匯入專案，以及每個視覺效果可顯示的內容。 了解如何配置設定以取得您所需的確切資料。 此外，您也可以取得一些秘訣和使用案例，協助您讓視覺效果切合日常分析之實際。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 說明資源

* [Adobe Analytics 產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html)

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的新功能 - 更新日期：**2021 年 9 月 14 日**：

| 功能 | 說明 |
| ------- | ------- |
| 行動身分識別資料收集同意權 | 已新增對行動身分識別資料收集同意權的支援。 若要受益於這項更新，客戶必須升級到 [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) 或更新版本。 |

## ![圖示](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

包含Experience Platform和[!UICONTROL 行動SDK]的發行更新資訊和新檔案。

**2021 年 9 月 29 日**

| 功能 | 說明 |
| ------- | ------- |
| [[!UICONTROL 資料登陸區]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL 資料著] 陸區是布 [!DNL Platform]建的Azure  [!UICONTROL Blob] 儲存區，可讓每個沙箱一個安全的暫時儲存，將檔案帶入Experience Platform。 |
| [資料準備](https://www.adobe.com/go/monitor-streaming-dataflows-en)的串流來源支援 | 串流來源現在支援資料準備，可讓您提供JSON來源結構，將不相容XDM的來源資料對應至目標XDM結構。 |
| [未到期的憑據](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | [!UICONTROL 查詢服務]使用者的非到期憑證允許更永久地連線至外部用戶端，而非每24小時續約一次憑證。 |
| [[!UICONTROL 目的地SDK]](https://www.adobe.com/go/destination-sdk-overview-en) | 使用[!UICONTROL 目標SDK]與[!DNL Platform]整合，並貢獻不斷成長的目標目錄。 只有Experience Platform啟用客戶才能存取此功能。 |

如需所有詳細資訊，請參閱 [Experience Platform 版本注意事項](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)。

### Experience Platform 教學課程與其他課程 {#tutorials-platform}

針對Experience Platform和服務發佈的最新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [[!DNL Platform] 管理](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | 課程 | 了解Experience Platform的管理活動，包括權限和沙箱管理。 |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)中最新功能、改良功能和修復。

### Journey Optimizer教學課程和課程 {#tutorials-ajo}

最新Journey Optimizer教學課程：

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [為資料工程師配 [!DNL Journey Optimizer] 置和管理資料](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | 課程 | 了解如何設定及管理Journey Optimizer中歷程管理所需的資料。 |
| 2021 年 10 月 | [歷程管 [!DNL Journey Optimizer] 理員和管理員快速入門](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | 課程 | 了解建立第一個歷程所需了解的一切。 |
| 2021 年 10 月 | [ [!DNL Journey Optimizer] 為歷程管理員進行設定](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | 課程 | 了解[!DNL Journey Optimizer]架構和整合點。 了解如何配置[!DNL Journey Optimizer]。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer]的更多資源

[說明中心](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

運用 Experience Platform 聰明地即時預測每個人的需求，在不同體驗管道大規模地協調客戶歷程。

### 最新[!DNL Journey Orchestration]產品發行

進一步了解 [[!DNL Journey Orchestration]  版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html)中最新功能、改良功能和修復。

#### [!DNL Journey Orchestration]的更多資源

[說明中心](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html) - [最新文件更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

## ![圖示](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] 是與Adobe Experience Platform整合的服務。使用 [!UICONTROL Offer Decisioning] 可在適當的時間為所有接觸點的客戶提供最佳優惠方案和體驗。

### 最新Offer decisioning產品發行

進一步了解[Offer decisioning發行說明](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)中的最新功能、改善和修正。

#### [!UICONTROL Offer Decisioning] 的更多資源

[說明中心](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![圖示](/assets/aem.png) Experience Manager {#aem}

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)頁面，以掌握最新的版本資訊。

### 社群

* [Adobe開發人員上線](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 2021年10月4-5日，7:00太平洋夏令時

   Adobe開發人員現場培訓將Adobe開發人員與具有不同背景和單一用途的體驗建立人員結合在一起，打造出絕佳的端對端體驗。 這次為期兩天的會議提供重要的開發人員更新、技術會議和社群網路機會。

   Adobe Experience Cloud、Document Cloud和Creative Cloud的Adobe產品團隊將展示最新技術進步和開發人員工具，推動設計、內容建立工作流程、檔案服務和跨行業的客戶體驗管理。

   Adobe已規劃20個Experience Manager課程。 傳話！

   * [完成工作階段清單](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [免費註冊 — 登入RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe開發人員即時社群](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [XML檔案快速入門](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | 課程 | 了解如何使用Adobe Experience Manager的XML檔案建立、組織、撰寫和發佈內容。 |
| 2021 年 10 月 | [管理創意工作 [!DNL Workfront] 流程使用和Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | 課程 | 了解Adobe[!DNL Workfront]和Experience Manager。 |
| 2021 年 10 月 | [開始使用AEM Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | 課程 | 了解AEM Assets Essentials如何為貴組織簡化資產管理。 |
| 2021 年 10 月 | [[!UICONTROL 內容轉移工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | 影片 | 了解[!UICONTROL 內容轉移工具]如何協助您將內容從AEM 6.3+移轉至AEM作為Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL 批量導入服務]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | 影片 | 了解如何使用AEM as a Services [!UICONTROL Bulk Import Service]從非AEM來源匯入資產。 |
| 2021 年 10 月 | [通信（輸出服務）](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | 影片 | 了解AEM Forms as aCloud Service如何支援通訊使用案例。 |
| 2021 年 10 月 | [數位註冊](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | 影片 | 了解AEM Forms as aCloud Service如何支援數位註冊使用案例。 |
| 2021 年 10 月 | [使用 [!UICONTROL Cloud Acceleration ] Managertools](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | 影片 | 提供使用[!UICONTROL Cloud Acceleration Manager]工具的旁白逐步說明。 |
| 2021 年 10 月 | [導 [!UICONTROL 覽Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | 影片 | 探索[!UICONTROL Cloud Acceleration Manager]的導覽體驗，以Experience Manager為Cloud Service。 |
| 2021 年 10 月 | [資產工作流程移轉工具](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | 影片 | 了解[!UICONTROL 資產工作流程移轉]工具如何協助將您現有的AEM Assets工作流程移轉至AEM作為Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL 索引轉換器]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | 影片 | 了解[!UICONTROL 索引轉換工具]如何自動將現有AEM索引定義轉換為與AEM相容的Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL Dispatcher 轉換工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | 影片 | 了解[!UICONTROL Dispatcher轉換工具]如何自動更新現有的AEM Dispatcher設定，使其與AEMCloud Service相容。 |
| 2021 年 10 月 | [[!UICONTROL Code Repository Modernizer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | 影片 | 了解[!UICONTROL 核心存放庫Modernizer]如何自動更新現有的AEM Maven專案，使AEM以Cloud Service相容。 |
| 2021 年 10 月 | [[!UICONTROL 程式碼重構工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | 影片 | 了解AEM [!UICONTROL 程式碼重構工具]如何協助將現有AEM專案的轉換自動化，使其成為與AEM相容的Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL 內容轉移工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | 影片 | 了解[!UICONTROL 內容轉移工具]如何讓您有效地將內容從AEM 6.5移至AEM作為Cloud Service。 |
| 2021 年 10 月 | [Cloud Acceleration Manager的實 [!UICONTROL 作階段]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | 影片 | 使用[!UICONTROL Cloud Acceleration Manager]檢閱並了解主要實作階段或以Cloud Service形式移至AEM。 |
| 2021 年 10 月 | [Readiness and  [!UICONTROL Best Practice Analyzer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | 影片 | 了解[!UICONTROL Best Practice Analyzer]如何協助您準備從AEM內部部署或Adobe Managed Services移轉至Experience Manager作為Cloud Service。 |
| 2021 年 10 月 | [Cloud Acceleration Manager簡介](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | 影片 | 了解[!UICONTROL Cloud Acceleration Manager]如何協助您快速輕鬆地移至Experience Manager作為Cloud Service。 |
| 2021 年 10 月 | [AEM Forms as aCloud Service — 轉移至AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | 影片 | 了解AEM Forms as aCloud Service支援的使用案例和功能。 |
| 2021 年 10 月 | [疑難排解AEM as aCloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | 影片 | 了解如何疑難排解AEM SDK、AEM as aCloud Service，以及建置和部署程式。 |
| 2021 年 10 月 | [AEM  [!UICONTROL Assets Microservices]  — 移至AEM as aCloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | 影片 | 了解AEM Assets as aCloud Service的asset compute微服務如何讓您自動且有效率地為資產產生任何轉譯，取代傳統AEM Workflow的這個角色。 |
| 2021 年 10 月 | [搜索和索引](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | 影片 | 了解AEM作為Cloud Service搜尋索引、如何將AEM 6索引定義轉換為與AEM作為Cloud Service相容，以及如何將索引部署至AEM作為Cloud Service。 |
| 2021 年 10 月 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | 影片 | 了解AEM [!UICONTROL Dispatcher] for AEM as aCloud Service，著重於對AEM 6、[!UICONTROL Dispatcher]轉換工具的[!UICONTROL Dispatcher]進行重大變更，以及如何使用Dispatcher工具SDK。 |
| 2021 年 10 月 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | 影片 | 了解Cloud Manager for AEM as aCloud Service，以及其與Cloud Manager for AEM on Cloud Manager Manage Services(AMS)的差異。 |
| 2021 年 10 月 | [開始使用 AEM as a Cloud Service ](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | 影片 | 了解如何從合約階段開始，使用[!UICONTROL Cloud Manager]設定環境，以AEM as aCloud Service入門。 |
| 2021 年 10 月 | [存放庫現代化](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | 影片 | 了解儲存庫現代化、可變和不可變內容、包結構和儲存庫現代化工具。 |
| 2021 年 10 月 | [[!UICONTROL AEM 現代化工具]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | 影片 | 了解如何使用AEM [!UICONTROL 現代化工具]來將現有AEM專案和內容升級為與AEM相容的Cloud Service。 |
| 2021 年 10 月 | [AEM 現代化工具](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | 影片 | 了解如何將AEM視為Cloud Service實作，有所不同。 |
| 2021 年 10 月 | [Best Practice Analyzer和Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | 影片 | 了解Best Practice Analyzer(BPA)和Cloud Acceleration Manager(CAM)如何提供自訂指南，以便移轉至AEM as aCloud Service。 |
| 2021 年 10 月 | [維護版本歷史記錄](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | 影片 | 了解Adobe Workfront和Experience Manager[!UICONTROL Assets Essentials]如何協助您維護[!DNL Workfront]檔案和Assets Essentials資產的版本。 |
| 2021 年 10 月 | [傳送檔案和連結資產](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | 影片 | 了解如何將Workfront檔案傳送至Assets Essentials，以及將Assets Essentials資產連結至Workfront。 |
| 2021 年 10 月 | [設定整合](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | 影片 | 了解如何設定Adobe Workfront和Assets Essentials整合。 |
| 2021 年 10 月 | [什麼是數位簽名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | 影片 | 了解憑證式數位簽名，此簽名符合全球最嚴格的法律法規，並可提供簽署者身分的最高保證。 |
| 2021 年 10 月 | [Adobe Analytics中的區段產生器](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | 影片 | 在Adobe Analytics中透過分段來分解您的資料。 此影片會帶您逐步了解[!UICONTROL 區段產生器]，並提供基本概觀。 |
| 2021 年 10 月 | [對應中繼資料](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | 影片 | 了解如何在Workfront欄位和Assets Essentials屬性之間設定中繼資料對應，以及如何設定Assets Essentials以顯示對應的值。 |

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
* [Adobe Primetime 版本注意事項](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html)
* [Livefyre 版本注意事項](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html)

### 適用於 Experience Manager 的其他說明資源

* [[!DNL Experience Manager as a Cloud Service] 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=zh-Hant)
* [Experience Manager 6.5 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hant)
* [Experience Manager 6.4 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html)
* [Experience Manager 6.2 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant#previous-updates)
* [舊版 Experience Manager 文件](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] 使用手冊](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hant)
* [[!DNL Dynamic Media Classic] 說明首頁](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hant)
* [Experience Manager 文件：最近更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hant#aem-as-a-cloud-service)

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品發行版

進一步了解已發行的最新功能、改良與修正：

* [Campaign v8 版本注意事項](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html)
* [Campaign Classic v7 版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)
* [Campaign Standard 版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)

### 最新 [!UICONTROL Campaign] 課程與教學課程 {#tutorials-campaign}

適用於Adobe Campaign的最新教學課程和課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [使用Adobe Campaign V8為商業使用者建立進階行銷活動](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | 課程 | 了解如何使用Adobe Campaign V8設定及執行進階行銷活動。 了解必要條件、建立和設定進階行銷活動、傳送及管理訂閱。 |
| 2021 年 10 月 | [在工作流程中使用SOAP API — 簡介](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | 教學課程 | 了解如何使用Adobe Campaign Soap API，並根據透過API收到的資料，建立進階的傳送工作流程。 |
| 2021 年 10 月 | [建立事件](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | 教學課程 | 了解如何設定事件、指定串流端點和事件的裝載。 |
| 2021 年 10 月 | [設定資料來源](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | 教學課程 | 了解什麼是資料來源，並了解如何設定Experience Platform和外部資料來源。 |
| 2021 年 10 月 | [使用案例 — 突發報文](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | 教學課程 | 瞭解突發訊息的適用使用案例。 瞭解如何設定突發訊息的歷程，以及可套用的最佳實務。 |

{style=&quot;table-layout:auto&quot;}

### Campaign 說明資源

* Adobe Campaign v8：[說明中心](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html) 做法影片

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 版本注意事項。

* [ [!DNL Advertising Cloud DSP] 中的新功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新功能 {#adcloud-dsp}

上次更新：**2021年9月28日**

| 功能 | 說明 |
| ------- | ----------- |
| 行銷活動管理檢視 | 「[!UICONTROL 建立日期]」欄現在可在[!UICONTROL 促銷活動]、[!UICONTROL 套件]、[!UICONTROL 版位]和[!UICONTROL 廣告]檢視的自訂欄集中使用。 您也可以依據[!UICONTROL 建立日期]來篩選[!UICONTROL 版位]和[!UICONTROL 廣告]檢視。 |
| 程式擔保交易 | （9月8日發行版本）您現在可以編輯程式化保證(PG)交易的預設位置的[!UICONTROL 最高競價]。 但是，由於PG交易一律有固定的CPM，因此只有國際客戶才應編輯[!UICONTROL 最高競價]以將貨幣兌換費用納入考量。 |
|  | （9月8日發行）擁有「[!DNL FreeWheel Programmatic Guaranteed]」權限的使用者現在可以從[!UICONTROL 廣告]檢視或[!UICONTROL 版位]檢視，將廣告提交至[!DNL FreeWheel Programmatic Creative API]。 您仍可從[!UICONTROL Deals]檢視提交廣告。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

上次更新：**2021年9月28日**

| 功能 | 說明 |
| ------- | ----------- |
| Advertising Insights | 測試版模式提供其他深入分析。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![圖示](/assets/target.png) [!DNL Target] {#target}

上次更新日期：**2021 年 8 月 3 日**

如需最新版本資訊，請參閱 [[!DNL Target]  版本注意事項](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是適用於潛在客戶管理以及想要透過參與複雜購買旅程的每個階段來轉換客戶體驗的 B2B 行銷人員的完整應用程式。

### Marketo Engage 核心更新

如需最新發行版排程資訊和版本注意事項，請參閱「[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)」。

## ![圖示](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] 是統一的工作管理應用程式，用於共用構想、建立內容、管理複雜的流程並執行其最佳工作。

請參閱 [[!DNL Workfront]  發行版本](https://one.workfront.com/s/product-releases)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

針對 Adobe Document Cloud 發佈的新影片、教學課程或其他課程。

### Document Cloud 課程與教學課程 {#tutorials-doc-cloud}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 10 月 | [什麼是數位簽名？](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | 影片 | 了解如何透過Adobe Sign使用全球各地的數位ID。 |
| 2021 年 10 月 | [新發件者專用Adobe Sign快速入門](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | 影片 | 如果您是初次使用Adobe Sign，本教學課程是絕佳的起點。 本完整的教學課程著重於所有基本知識，協助您快速上手並執行Adobe Sign。 |
| 2021 年 10 月 | [將PDF注釋載入InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | 影片 | 在這個60秒的影片教學課程中，了解在Acrobat共用審核後，如何將PDF註解載入回InDesign。 此數位工作流程可協助您以創紀錄的時間完成修訂。 |
| 2021 年 10 月 | [從 [!DNL Intesi Group] 取得數位ID（合格）](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | 影片 | 了解如何從[!DNL Intesi]群組取得合格的數位簽署憑證。 註冊並驗證您的身份後，[!DNL Intesi]群組會向您發出數位ID，此數位ID用於套用Adobe Sign雲端簽名。 |
| 2021 年 10 月 | [使用進行簽署 [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | 影片 | 了解如何使用英特爾組數字ID驗證您的身份，並授權文檔上的遠程數字簽名（雲簽名）。 |
| 2021 年 10 月 | [從 [!DNL Intesi Group] 取得數位ID（進階）](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | 影片 | 了解如何從Intesi Group取得進階數位簽署憑證。 註冊並驗證您的身分後，Intesi Group會向您發出數位ID，此ID用於套用Adobe Sign雲端簽名。 |
| 2021 年 10 月 | [使用進行簽署 [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | 影片 | 了解如何使用您的[!DNL Digidentity]數位ID驗證您的身分，並授權檔案上的遠端數位簽名（雲端簽名）。 |
| 2021 年 10 月 | [從取得數位ID [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | 影片 | 了解如何從[!DNL Digidentity]取得數位簽署憑證。 註冊並驗證您的身份後，[!DNL Digidentity]會向您發出數位ID，此ID用於套用Adobe Sign雲端簽名。 |
| 2021 年 10 月 | [偵測兩個PDF之間的差異](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | 影片 | 切勿犯使用錯誤版本檔案的錯誤。 快速而準確地偵測兩個PDF檔案之間的差異，以改善檔案審核工作流程。 |
| 2021 年 10 月 | [使用Microsoft® Edge瀏覽時建立PDF內容](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | 影片 | 了解如何使用Microsoft® Edge的Adobe Acrobat擴充功能，即時將網頁封存為PDF。 此僅Windows工具對於研究項目和基於Web的資訊的離線查看非常有價值。 |
| 2021 年 10 月 | [在Outlook中將電子郵件和附件轉換為PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | 影片 | 了解如何在Outlook中，為專案封存電子郵件訊息和附件至PDF。 了解如何自動將附件轉換為PDF，以更專業且安全的方式提供資訊。 此工具僅適用於Windows。 |

{style=&quot;table-layout:auto&quot;}

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud 學習與支援](https://helpx.adobe.com/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) 適用於企業的 Creative Cloud {#creative-cloud}

如需了解最新教學課程，請參閱[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hant)。
