---
title: Adobe Experience Cloud 發行說明
description: Adobe Experience Cloud 發行說明
doc-type: release notes
last-update: January 2021
author: mfrei
translation-type: tm+mt
source-git-commit: d5d885d83774f8160e77ec34ddc4cfa92b7f10f4
workflow-type: tm+mt
source-wordcount: '6414'
ht-degree: 90%

---


# Adobe Experience Cloud 版本說明 - 2021 年 1 月

![橫幅](/assets/experience-cloud-banner-3.png)

此頁面主要說明 [!DNL Adobe Experience Cloud] 的新功能、修正項目和重要注意事項。此外還有最新文件、訓練課程和教學課程影片，協助您充份運用 Experience Cloud。

>[!NOTE]
>
>訂閱每月[Adobe優先產品更新](https://www.adobe.com/subscription/priority-product-update.html)，以接收有關本頁更新的電子郵件通知。 本頁面會在整個月中維護，因此請定期回訪Adobe企業產品和Experience League檔案更新。

最新更新：**2020年1月11日**

* [Adobe系統狀態](#status) （未更新）
* [Experience Cloud 服務與管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey) (發行日期：**2021 年 1 月 14 日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo) (已更新： **(2021年1月11日**)
* [Document Cloud](#doc-cloud)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。內容已從`docs.adobe.com`移至此位置。 請相應地更新書籤。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/tw/)。

本月無更新。

如需最新發行資訊，請參閱 [Adobe 系統狀態 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hant/release-notes/experience-cloud/previous/2020/05212020.html#status)。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 服務與管理 {#ecloud}

[Experience Cloud服務和管](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html) 理檔案包括客戶屬性、觀眾程式庫( Peopleservice)、啟動、使用者和產品管理，以及Experience Cloud Cookie。

本月無更新。

如需最新發行資訊，請參閱 [Experience Cloud 服務的彙整發行說明](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/release-notes/release-notes.html)。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

包含Experience Platform和Experience Platform Launch的發行更新資訊。

| 功能 | 發行日期 | 說明 |
| ------- | ------| ------- |
| 增強Experience Platform的產品內支援互動功能 | 2021 年 1 月 15 日 | 您現在可以提出Experience Platform問題或報告問題，而不需離開您的Experience Platform介面。 導覽至「**[!UICONTROL 說明]** > **[!UICONTROL 支援]** > **[!UICONTROL 建立支援票證」，然後輸入查詢並直接將您的案例提交給客戶支援。]**&#x200B;您將會收到一封包含案例ID的電子郵件通知，客戶支援團隊將會透過票證與您聯絡，以滿足您的需求。 |

最新更新：**2020 年 12 月 9 日**

如需套用至以下項目的最新更新，請參閱[Experience Platform發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=en):

* [!UICONTROL 資料流]
* [!UICONTROL Data Science Workspace]
* [!UICONTROL 來源]

### Experience Platform Launch

如需 Platform Launch 的相關資訊，請參閱 [Experience Platform Launch 發行說明](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html)。

### Adobe Mobile

iOS 4.21.0版

一般- SDK現在使用[!DNL XCFrameworks]來散發，以支援採用新Apple M1架構的硬體，同時仍支援現有的Intel架構。

* 重要：升級至AdobeMobile [!DNL XCFrameworks]需要Xcode 12.0或更新版本。
* 重要：如果使用[!DNL Cocoapods]，則升級至AdobeMobile [!DNL XCFrameworks]需要[!DNL Cocoapods] 1.10.0或更新版本。

### Experience Platform 和服務教學課程與其他課程

針對 Experience Platform 和服務所發佈的新影片、教學課程或其他課程。

已更新：**2021年1月6日**

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 23 日 | [聯合結構概述](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/union-schemas-overview.html) | 影片 | 瞭解Adobe Experience Platform即時客戶個人檔案所使用的工會架構。 |
| 2020 年 12 月 22 日 | [建立多實體區段](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-multi-entity-segments.html) | 影片 | 瞭解如何在Adobe Experience Platform的「區段產生器」中建立多實體區段。 |
| 2020 年 12 月 21 日 | [建立優惠方案活動](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-offer-activities.html) | 影片 | 瞭解如何在[!UICONTROL 選件決策]中建立選件活動。 選件活動會將您的位置和系列結合為單一實體，以便能夠決定向客戶傳遞最相關的選件。 |
| 2020 年 12 月 21 日 | [建立集合](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-collections.html) | 影片 | 瞭解如何在[!UICONTROL 選件決策]中建立系列。 系列用於管理邏輯群組中的選件，並且是建立選件決策活動的必要項目。 |
| 2020 年 12 月 21 日 | [使用決策API提供優惠](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/deliver-offers-with-the-decisions-api.html) | 影片 | 瞭解如何透過決策API傳遞[!UICONTROL 選件決策]選件。 |
| 2020 年 12 月 15 日 | [建立個人化優惠方案](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-personalized-offers.html) | 影片 | 瞭解如何在[!UICONTROL 選件決策]中建立個人化選件。 |
| 2020 年 12 月 15 日 | [建立回退優惠方案](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-fallback-offers.html) | 影片 | 瞭解如何在[!UICONTROL 選件決策]中建立備援選件。 |
| 2020年12月14日（更新） | [瞭解即時客戶個人檔案](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/understanding-the-real-time-customer-profile.html) | 影片 | 本影片說明Adobe Experience Platform如何組裝和更新即時客戶個人檔案，以及您如何存取和使用這些個人檔案。 |
| 2020 年 12 月 10 日 | [建立標籤](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-tags.html) | 影片 | 瞭解如何在[!UICONTROL 選件決策]中建立標籤。 標籤是選件的選用建置區塊元件。 它們可用來組織選件，並將選件群組在動態系列中。 |
| 2020 年 12 月 9 日 | [在選件決策中建立規則](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-rules.html) | 影片 | 瞭解如何在[!UICONTROL 選件決策]中建立規則。 規則是使用平台的「即時客戶個人檔案」中的事件和屬性來建立，並形成選件的資格限制。 |
| 2020 年 12 月 9 日 | [建立位置](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-placements.html) | 影片 | 瞭解如何在選件決策中建立位置。 位置是內容類型與頻道的組合，例如網站上電子郵件或HTML程式碼中的影像。 |
| 2020年10月29日（更新） | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=zh-Hant) | 影片 | 了解各大品牌如何善用 Adobe 的全新 [!UICONTROL Offer Decisioning] 服務來定義及管理選件、運用即時客戶資料，並提供客戶期望的合適體驗。 |
| 2020年10月26日（更新） | [Offer Decisioning 簡介](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html) | 影片 | 這部影片主要概略介紹 [!UICONTROL Offer Decisioning]，這是以 Adobe Experience Platform 為基礎打造而成的應用程式服務。影片內容涵蓋 [!UICONTROL Offer Decisioning] 解決的企業難題、重要功能、基本架構和主要使用案例。 |
| 2020年10月26日（更新） | [使用Salesforce CRM來源連接器收錄資料](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | 影片 | Salesforce CRM來源連接器可讓您以順暢且可擴充的方式，輕鬆將Salesforce CRM中的資料批次內嵌至Adobe Experience Platform的即時客戶個人檔案和體驗資料湖。 |
| 2020年10月13日（更新） | [使用Salesforce CRM來源連接器收錄資料](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | 影片 | Salesforce CRM來源連接器可讓您以順暢且可擴充的方式，輕鬆將Salesforce CRM中的資料批次內嵌至Adobe Experience Platform的即時客戶個人檔案和體驗資料湖。 |
| 2020年10月23日（更新） | [將資料帶入即時客戶個人檔案](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html) | 影片 | 即時客戶個人檔案可推動跨通道個人化，在客戶歷程的每個階段都能大規模進行。 |
| 2020年10月13日（更新） | [設定 Attribution AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html) | 影片 | 了解如何建立 Attribution AI 例項，以明白行銷管道和行銷活動的影響。 |
| 2020年10月13日（更新） | [設定 Customer AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html) | 影片 | 了解如何建立 Customer AI 例項，以預測客戶行為。 |

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

運用Adobe Experience Platform透過智慧地即時預測每個個人的需求，跨不同的體驗通道大規模策劃客戶歷程。

### 新產品版本

* 11月發行- [閱讀更多](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#november-release)
* 十月發行- [閱讀更多](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#october-release)

### Journey Orchestration 的其他資源

[文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/zh-Hant/journey-orchestration-learn/tutorials/understanding-journey-orchestration.translate.html)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2021 年 1 月 14 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Adobe Analytics 修正項目](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)
* [Report Builder](#arb)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ------- |
| 分析工作區——元件選擇 | 2021 年 2 月 4 日 | 在[!UICONTROL Quick Insights]中找到的下拉／下拉區元件已新增至[!UICONTROL Workspace]中的所有下拉區。 此增強功能可讓您從相容元件的下拉式清單中挑選，或繼續將空間當做下拉區域使用。 |
| 分析工作區——影像URL | 2021 年 1 月 14 日 | 您可以參照公用影像URL，將影像新增至[!UICONTROL Workspace]專案。 |

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ----- |
| [!UICONTROL 「裝置」]和[!UICONTROL 「地理位置」]維度 | 2020 年 10 月 30 日 | 這些維度現在預設為Adobe Analytics [!UICONTROL Source Connector]中「全域查閱」支援專案的一部分。 ](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-usecases/global-lookups.html?lang=en#use-global-lookups-with-adobe-data-connector-datasets)[這項備受期待的新功能可促進 [Adobe Analytics 與 CJA 之間的對等關係](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-overview/cja-aa.html?lang=en#cja-overview)。 |
| 歷程IQ:[!UICONTROL 跨通道分析] | 2021 年 1 月 11 日 | 歷程IQ:[!UICONTROL 跨通道Analytics]可讓您將Experience Platform資料湖中的Adobe Analytics（或其他）事件資料集從一個ID命名空間重新鍵入到另一個ID命名空間。 這通常代表將事件資料集從 Cookie 型 ID 重新輸入為人員型 ID。這樣，重新鍵入的資料集可以與CJA連接中的其他基於人的資料相結合，從而在分析工作區中實現跨設備和跨通道分析。 [深入了解](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/cca/overview.html?lang=en#cja-connections) |
| 分析工作區——元件選擇 | 2021 年 2 月 4 日 | 在[!UICONTROL Quick Insights]中找到的下拉／下拉區元件已新增至[!UICONTROL Workspace]中的所有下拉區。 此增強功能可讓您從相容元件的下拉式清單中挑選，或繼續將空間當做下拉區域使用。 |
| 分析工作區——影像URL | 2021 年 1 月 14 日 | 您可以參照公用影像URL，將影像新增至工作區專案。 |

### Adobe Analytics 修正項目 {#aa-fixes}

* 修正「工作區」中下載的CSV報表的格式設定、下載和傳送問題。 (AN-224844
AN-240295)
* 修正即使Analytics報表套裝包含資料，行動屬性的資料仍未顯示在Livestream中的問題。 (AN-241169)
* 修正「即時」報表無法顯示任何資料的問題。 (AN-242477)
* 在「報告與分析」中，修正使用&#x200B;_contains_&#x200B;篩選器時，無法顯示任何資料的問題。 (AN-237354)
* 修正從Adobe Analytics刪除的區段繼續用於促銷活動資料連接器的問題。 (AN-236713)
* 修正計畫報表卡在報表佇列中的問題。 (AN-242599、AN-242554、AN-242900、AN-243329)
* 修正「報告與分析」中共用目標報表的問題。 (AN-234638)
* 修正長條圖無法在工作區中顯示資料的問題。 (AN-232127)
* 修正客戶無法登入Adobe Analytics的問題。 (AN-241882 AN-238802)
* 更新行動裝置報告，加入Samsung Galaxy Z Fold2 5G。 (AN-238246)
* 修正「工作區」中計畫報表錯誤的問題。 (AN-236707、AN-243449)
* 修正FTP無法擷取資料來源檔案的問題。 (AN-240347)
* 修正嘗試存取[!UICONTROL 廣告分析]時造成錯誤的問題。 (AN-241478)
* 修正無法從分類FTP擷取檔案的問題。 (AN-242490)
* 修正工作區中的UI轉換錯誤。 (AN-243123)
* 修正無法從SFTP伺服器接收檔案的「資料倉庫」問題。 (AN-244679)
* 修正在[!UICONTROL Admin] > [!UICONTROL Logs] > [!UICONTROL 使用與存取記錄]下，[!UICONTROL 下載報表]連結無法運作的問題。 (AN-238058)

#### 其他 Adobe Analytics 修正項目

AN-204659;AN-221726;AN-230949;AN-231984;AN-232835; AN-233989;AN-235593;AN-235989;AN-236823;AN-236840;AN-237168;AN-237262;AN-237265;AN-237633;AN-237740;AN-238523;AN-238870;AN-238941;AN-239414;AN-239649;AN-239652;AN-239676;AN-239703;AN-240184;AN-240219;AN-240412;AN-240530;AN-240609;AN-240625;AN-240664;AN-240682;AN-240715;AN-241052;AN-241077;AN-241112;AN-241149;AN-241578;AN-241714;AN-242157;AN-242485;AN-242535;AN-242573;AN-242608;AN-242728;AN-242818;AN-242820;AN-242963;AN-242978;AN-243013;AN-243054;AN-243105;AN-243172;AN-243181;AN-243255;AN-243326;AN-243418;AN-243449;AN-243463;AN-243507;AN-243518;AN-243519;AN-243598;AN-243805;AN-243814;AN-243910;AN-243929;AN-244009;AN-244012;AN-244105;AN-244121;AN-244137;AN-244188;AN-244225;AN-244305;AN-244357;AN-244363;AN-244419;AN-244607;AN-244695;AN-244713;AN-244828;AN-244843;AN-244876;AN-244877;AN-245388;AN-245470

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 需要[!UICONTROL 報告建立工具]更新 | 2021 年 1 月 8 日 | 到2021年4月30日，所有[!UICONTROL 報告建立工具]使用者都必須將[!UICONTROL 報告建立工具]增益集更新至5.6.47版或更新版本。 此版本包含登入程式的重要更新。 未更新至5.6.47版或更新版本的使用者將無法在2021年4月30日之後登入。 [!UICONTROL 報表] 建立工具5.6.47版及更新版本僅支援Experience Cloud登入，不支援舊版登入，例如SiteCatalyst單一登入或標準登入。如需詳細資訊，請參閱[報告建立工具登入](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA)。 |
| 三種Analytics API服務的生命週期結束 | 2021 年 1 月 6 日 | 在2021年4月30日，下列Analytics舊版API服務預計會到期，並將關閉。 使用這些服務建立的任何目前整合將於當天停止運作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy OAuth 驗證 (OAuth 和 JWT)</li></ul>我們提供[舊版API EOL常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助您回答問題並提供如何繼續的指引。 採用這些服務的API整合可移轉至[1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email)和／或[2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。 Legacy OAuth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| 為所有傳入的 HTTPS 要求加上 HSTS 標題 | 2020 年 9 月 29 日 | 自 2020 年 9 月 29 日起，我們開始為所有使用 HTTPS 的傳入要求加上 HSTS 標題。這會指示瀏覽器/用戶端日後一律透過 HTTPS 提出要求，以符合安全性最佳實務。目前我們還不會針對使用 HTTP 的傳入要求強制執行此規範。 |
| 變更至[!UICONTROL Experience Cloud ID服務] Cookie設定 | 2020 年 9 月 22 日 | 一項針對 Chrome 80 版本隱私權設定的更新影響 Adobe Analytics 追蹤部分檢視 Google AMP 頁面之使用者的能力。具體來說，這項更新會防止跨網域追蹤檢視 Google 託管 AMP 頁面的使用者。如此可能導致不重複訪客的數量增加。此修正可讓使用者透過變更 ECID Cookie 設定來解決此問題。<br>目前，Analytics 的 Experience Cloud ID (ECID) 服務 Cookie 設定為 `SameSite = Lax`，而此設定在 Chrome 80 版本之前皆允許進行跨網域追蹤。但如今情況有變。使用者可透過這項變更將 ECID Cookie 的 SameSite 設定更新為 `None`。<br>請注意，這雖然會允許在更多情況下共用 Analytics Cookie，不過 Analytics Cookie 本身並不包含敏感資料。此外，選擇這項設定時，Cookie 必須設定為 `Secure`，才能僅透過 HTTPS 連線傳送資料。若想進行此一變更，請由支援的使用者透過客戶服務建立票證。 |
| 從 `omniture.com` 移轉至 `adobe.com` 網域 | 2020 年 8 月 21 日 | 2020 年 8 月 13 日，Adobe Analytics 將前端架構從 `omniture.com|http://omniture.com/` 移轉至 `adobe.com|http://adobe.com/` 網域。此變更應可紓解 2020 年 5 月 28 日初次統一產品網域後發生的第三方 Cookie 問題。更新後，瀏覽器可能會提示使用者將 `.adobe.com|http://an.adobe.com/` 或 `experience.adobe.com|http://experience.adobe.com/` 等新網域加入信任清單。 |
| 更新 Ad Hoc Analysis Java 8 相容性 | 2020 年 8 月 21 日 | Ad Hoc Analysis 目前與 Java 8 1.8.0_261 以後的版本不相容。為確保您在[產品生命週期](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)結束前能順利存取此工具，建議您持續使用 1.8.0_261 之前的 Java 8 版本。 |
| Adobe Data Connectors 終止服務 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 的舊技術已無法使用或不再支援。[Adobe Exchange 合作夥伴計畫已推出一項新標準](https://partners.adobe.com/tw/exchangeprogram/experiencecloud)，任何希望能繼續使用服務及取得支援的整合項目，都應採用此標準。確切日期仍未決定，但預計未來 12 至 18 個月內 (2021 年中至 2021 年底) 將會正式終止服務。[深入了解...](https://docs.adobe.com/content/help/zh-Hant/analytics/import/dataconnectors/data-connectors-eol.html) |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意於 2021 年 3 月 1 日終止 Ad Hoc Analysis 服務。如需詳細資訊，請造訪[探索工作區](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### AppMeasurement {#appm}

如需 AppMeasurement 發行的最新消息，請參閱[適用於 JavaScript 的 AppMeasurement 發行說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。

### Report Builder {#arb}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ----- |
| 登入更新至Analytics [!UICONTROL 報告建立工具] | 2021 年 1 月 14 日 | [!UICONTROL 報告建立工具]登入程式改進功能可移除對舊有技術的依賴，並將登入程式與Adobe Experience Cloud一致。 Experience Cloud登入可讓您使用Adobe ID或Enterprise ID（單一登入）登入Adobe Experience Cloud。 到2021年4月30日，所有[!UICONTROL 報告建立工具]使用者都必須將[!UICONTROL 報告建立工具]增益集更新至5.6.47版或更新版本。 [!UICONTROL 報] 告建立工具5.6.47版及更新版本僅支援Experience Cloud登入，不支援舊版登入，例如SiteCatalyst單一登入或標準登入。如需詳細資訊，請參閱[報告建立工具登入](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA)。 |

### Analytics 說明資源

* [Adobe Analytics產品檔案與教學課程](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![圖示](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 的新功能、修正項目、說明文件和教學課程。

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixed an issue in the Predictive Audience feature where some users were unable to delete any of their models, even if no segments were mapped to the models. (AAM-55881)
* Fixed an issue where some users were unable to delete traits or segments which had been used as baseline for deleted predictive audience models. (AAM-56476)
* We continued making accessibility improvements across the interface. (AAM-53215) -->

### Audience Manager 課程與教學課程 {#tutorials-aam}

針對 Audience Manager 發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 15 日 | [使用基於角色的訪問控制設定權限](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/user-management/setting-permissions-with-role-based-access-control.html?lang=en#setup-and-admin) | 影片 | 瞭解如何管理群組層級的權限，控制哪些人可以檢視和使用資產，包括特徵、區段、目的地和模型。 設定權限群組並新增使用者至權限群組。 |

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

>[!NOTE]
>
>Adobe 建議時常瀏覽 [Experience Manager 版本更新和藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html)，以隨時掌握最新的發行資訊。

### 產品更新

* **AEM 6.5.7.0**
AEM 6.5,Service Pack 7（2020年11月26日發行的6.5.7.0）是重要的更新，其中包含自2019年4月AEM 6.5全面上市以來發佈的新功能、重要客戶增強功能、改善的效能、穩定性和安全性。
   * [發行說明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en#service-pack)
   * [AEM Forms 發行交付項目](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **AEM 6.4.8.3**
AEM 6.4、Service Pack 8、Cumulative Fix Pack 3（2020年11月26日發行的6.4.8.3）是重要的更新，其中包含自AEM 6.4、Service Pack 8(6.4.8.0)3月2日全面上市以來的數項內部和客戶修正020。
   * [發行說明](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
   * [AEM Forms 發行交付項目](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

### 產品發行

* **AEM as a Cloud Service**

   AEM as a Cloud Service 新增了哪些功能？

   * **Adobe Experience Manager Sites as a Cloud Service**
      * [內容片段HTTP API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html):新增使用HTTP API新增／更新和刪 [!UICONTROL 除「] 內容片段變數」的功能。
   * **Adobe Experience Manager Assets as a Cloud Service**

      * Experience Manager現在提供與Adobe InDesign Server的整合，以[!UICONTROL 雲端服務]的形式提供。 它提供使用Adobe InDesign Server指令碼處理Adobe InDesign檔案的自動功能，並讓使用者使用資產範本使用者介面來建立手冊或廣告。 Experience Manager僅支援Adobe Managed Services代管的InDesign Server，作為[!UICONTROL Cloud Service]。
      * 當資產用於遠端Experience Manager Sites部署時，Experience Manager已增強，可使用[!UICONTROL Connected Assets]功能來追蹤和顯示資產參考。 資產的[!UICONTROL 屬性]頁面中新的[!UICONTROL 參考]標籤現在會列出資產的本機和遠端參考。 參考可讓DAM使用者追蹤[!UICONTROL Sites]頁面和[!UICONTROL Assets]複合資產中的資產使用情形。
請參閱[設定及使用連線資產](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/use-assets-across-connected-assets-instances.html)。
      * [!UICONTROL 現在] 您可透過以網站為基礎的核  心元件存取動態媒體。作者可以在建立網頁時快速設定元件，使用[!UICONTROL 影像預設集]、[!UICONTROL 智慧型裁切]和[!UICONTROL 影像修飾元]。
請參閱[核心元件2.13.0版](https://github.com/adobe/aem-core-wcm-components/releases/tag/core.wcm.components.reactor-2.13.0)。
      * Experience Manager案頭應用程式可讓使用者從案頭應用程式介面的Windows檔案總管或Mac Finder中拖曳檔案，以上傳檔案和檔案夾。
請參閱「使用案頭應用程式新增資產」。[](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/using.html?lang=en#upload-and-add-new-assets-to-aem)
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * 發佈的CIF Venia參考網站- 2020.12.01，其中包含最新的CIF核心元件v1.6.0版。
請參閱[CIF韋尼亞參考站點](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2020.12.01)。
      * 已發佈CIF核心元件v1.6.0。
請參閱[CIF核心元件](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.6.0)。
   * **Cloud Manager**

      * [SSL憑證](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/manage-ssl-certificates/introduction.html)和[自訂網域名稱](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/custom-domain-names/introduction.html)的自助服務管理。
      * [IP允許清單的自助管理](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/ip-allow-lists/introduction.html)。
      * 「更新的環境詳細資訊」頁現在允許用戶管理其環境中的[!UICONTROL 自定義域名]和[!UICONTROL IP允許清單]。
   * **程式碼重構工具**

      * 新版AIO-CLI增效模組已發行。 此外掛程式的最新版本包含AEM Dispatcher Converter和Repository Modernizer的錯誤修正，也支援新的公用程式- Index Converter。
請參閱[統一體驗](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/refactoring-tools/unified-experience.html#benefits)以進一步瞭解此外掛程式。
      * Index Converter是一個公用程式，可用來將客戶的自訂OAK索引定義轉換為AEM，做為CLoud Service相容的OAK索引定義。
請參閱[索引轉換器](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/index-converter)。
      * 新增至[Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer)的新功能，可建立個別的套件`ui.config`以包含所有OSGi組態。





請參閱 [AEM as a Cloud Service 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)。

### 自助資源

**[!DNL Experience Manager as a Cloud Service]**

上述連結提供新功能檔案更新。 其他檔案更新包括：

* **最佳實務分析器**

   * [!UICONTROL Cloud Readiness ] Analyzeris現在 [!UICONTROL 是Best Practices Analyzer] (BPA)。BPA提供您目前AEM實作的最佳實務評估，並協助您評估從現有AEM例項移至AEM的準備程度，做為[!UICONTROL 雲端服務]。

* **基礎**

   * 工作流——支援根據[!UICONTROL 工作流標題]、[!UICONTROL 工作流模型]、[!UICONTROL 狀態]、[!UICONTROL 啟動器]、[!UICONTROL 裝載路徑]和[!UICONTROL 開始日期]。
請參閱[搜尋工作流程例項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/administering/workflows-administering.html#administering)。
   * 發佈層用戶資料同步——用戶資料（包括配置檔案屬性和組成員資格）可以保存在發佈層。
請參閱[註冊、登入和使用者設定檔檔案](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/personalization/user-and-group-sync-for-publish-tier.html#authoring)。

### [!DNL Experience Manager] 表單

6.5.7.0版包含下列功能的說明檔案已提供：

* 在安裝Service Pack後，您可體驗更快速的伺服器端驗證和PDF至最適化表單轉換。

* 您現在可以還原所有調整大小的變更，並在最適化表單的「版面」模式中，將預設版面套用至每個元件。 請參閱[使用版面模式來調整元件](https://experienceleague.adobe.com/docs/experience-manager-65/forms/adaptive-forms-basic-authoring/resize-using-layout-mode.html?lang=en)的大小。

* [!DNL Experience Manager Forms] 當與REST風格的Web服務整合作為資料源時，現在包括用於連接管理的HTTP客戶端配置。請參閱[設定資料來源](https://experienceleague.adobe.com/docs/experience-manager-65/forms/form-data-model/configure-data-sources.html?lang=en#configure-relational-database)。

### 社群

**2021年1月Experience League的最新Adobe Experience Manager內容** -請在 [這裡檢視功能影片、文章、教學課程和課程的完整清單](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/td-p/392549)。

### 最新 Experience Manager 課程與教學課程 

已更新：**2021年1月10日**

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 7 日 | [使用片段參照建立進階資料模型](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/fragment-references.html) | 文章 | 開始使用Adobe Experience Manager(AEM)和GraphQL。 瞭解如何使用[!UICONTROL 片段參考]功能建立進階資料模型，以及建立兩個不同[!UICONTROL 內容片段]之間的關係。 瞭解如何修改GraphQL查詢以包含參考模型中的欄位。 |
| 2020 年 12 月 7 日 | [從外部應用程式使用GraphQL查詢AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | 文章 | 開始使用Adobe Experience Manager(AEM)和GraphQL。 以範例WKND GraphQL React應用程式來探索AEM的GraphQL API。 瞭解此外部應用程式如何讓GraphQL呼叫AEM，以強化其體驗。 瞭解如何執行基本錯誤處理。 |
| 2020 年 12 月 7 日 | [探索GraphQL API](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | 文章 | 開始使用Adobe Experience Manager(AEM)和GraphQL。 使用內建的GrapiQL IDE，探索AEM的GraphQL API。 瞭解AEM如何根據內容片段模型自動產生GraphQL架構。 使用GraphQL語法來嘗試建構基本查詢。 |
| 2020 年 12 月 | [編寫內容片段](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/author-content-fragments.html) | 文章 | 開始使用Adobe Experience Manager(AEM)和GraphQL。 根據[!UICONTROL 內容片段模型]建立和編輯新的內容片段。 瞭解如何建立[!UICONTROL 內容片段]的變體。 |
| 2020 年 12 月 7 日 | [定義內容片段模型](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/content-fragment-models.html) | 文章 | 開始使用Adobe Experience Manager(AEM)和GraphQL。 瞭解如何在AEM中建立內容模型並使用內容片段模型建立架構。 檢閱現有模型並建立新模型。 瞭解可用來定義架構的不同資料類型。 |
| 2020 年 12 月 9 日 | [API相容性](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/developer-reference-material-apis.html) | 文章 | 建立簡單文章，清楚傳達哪些AEM API(npm、Java、HTTP)可用於各種[!UICONTROL Assets]作業。 |
| 2020 年 12 月 2 日 | [下載內容片段](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html) | 影片 | 內容片段的下載功能概觀。 |
| 2020 年 12 月 7 日 | [內容片段編輯功能](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html) | 影片 | [!UICONTROL 內容片段]編輯器的進階功能影片概觀。 瞭解如何與[!UICONTROL 內容片段]使用註解和版本比較。 |
| 2020 年 12 月 4 日 | [使用或不使用條形碼從政府發佈的文檔中提取OCR資料](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/ocr-data-extraction.html?lang=en#some-useful-integrations) | 文章 | 從政府核發的檔案（例如駕照或護照）擷取資料，以填入最適化表單。 |
| 2020 年 12 月 14 日 | [AEM Headless with GraphQL概觀](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/overview.html) | 影片 | 概觀在Adobe Experience Manager或AEM中實作的GraphQL API。 AEM中的GraphQL API主要設計為將[!UICONTROL 內容片段]資料傳送至下游應用程式，做為無頭部署的一部分。 |
| 2020 年 12 月 16 日 | [動態媒體核心元件](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/dynamic-media-core-components.html) | 影片 | Experience Manager Core Components的影像元件已內建Dynamic Media支援。 瞭解影像元件如何讓內容作者在AEM Sites頁面上使用動態媒體的功能，例如影像預設集、智慧裁切和影像修飾元。 |

### Experience Manager 發行資訊

所有 Experience Manager 的發行說明都會保留在以下頁面：

* [Experience Manager 版本更新和藍圖](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [AEM as a Cloud Service 發行資訊](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Automated Forms Conversion Service 發行說明](https://docs.adobe.com/content/help/zh-Hant/aem-forms-automated-conversion-service/using/release-notes.html)
* [AEM 6.5 Service Pack 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [AEM 6.4 Cumulative Fix Pack 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-64/release-notes/cfp-release-notes.html)
* [AEM Assets Dynamic Media 發行說明](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [AEM Brand Portal 發行說明](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [AEM 桌面應用程式發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-desktop-app/using/release-notes.translate.html)
* [AEM Dispatcher 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Livefyre 發行說明](https://docs.adobe.com/content/help/zh-Hant/livefyre/using/release-notes/c-rn.translate.html)

### AEM 其他說明資源

* [AEM as a Cloud Service 手冊](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
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

<!-- [Incident Response Bulletin](https://helpx.adobe.com/security/products/campaign/apsb21-04.html) (January 12) -->

* 20.3.3 版 - [深入了解](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* 20.3.1 版 - [深入了解](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* 20.2.4 版 - [深入了解](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-2.html#release-20-2-4-build-9187)
* 20.1.4 版 - [深入了解](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-1.html#release-20-1-4-build-9126)
* 19.2.4 版 - [深入了解](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-2.html#release-19-2-4-build-9082)
* 19.1.8 版 - [深入了解](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-8-build-9039)

#### Campaign Classic金級標準

* Gold Standard 11版本- [閱讀更多](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/gs-release/gold-standard.html?lang=en#gs-11)

### 說明資源

* Adobe Campaign Standard：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/campaign-standard-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/campaign-classic-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 作法影片

#### 最新 Campaign 課程與教學課程

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 解決方法 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 23 日 | [設定動態內容](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/configuring-dynamic-content.html#sending-messages) | Campaign Classic | （視訊）瞭解不同類型的動態內容，並瞭解如何建立並套用個人化區塊和條件陳述式至傳送。 |
| 2020 年 12 月 9 日 | [控制面板 - Google TXT 記錄管理](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/subdomains-and-certificates/google-txt-record-management.html#subdomains-and-certificates) | Campaign Standard | （視訊）瞭解如何將Google TXT網站驗證記錄新增至您用來透過[!UICONTROL 促銷活動控制面板]傳送電子郵件至GMAIL位址的所有子網域。 |

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 發行說明。

* [Advertising Cloud DSP 新功能](#adcloud-dsp)
* [Advertising Cloud Search 新功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新功能{#adcloud-dsp} 

上次更新日期：**2020年10月28日**

| 功能 | 說明 |
| -----------| ---------- |
| 新增說明 | (10 月 28 日發行) 舊版說明已更換為更新頁面，您可以透過 DSP 主功能表的「說明」連結加以存取，也可以隨時從 [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) 存取 |
| Campaigns | (10 月 28 日發行) 先前的 Campaigns 測試版檢視現已成為 Campaigns 預設檢視，能提供更快速的深入分析、簡潔的工作流程和自訂檢視。 |
| 私人詳細目錄 | (10 月 15 日發行) 所有使用者現在都能使用新交易 ID 表單來設定及編輯交易 ID 詳細資訊，此表單是舊版[!UICONTROL 「智慧型廣告服務」]表單的簡化版本。若要設定新交易 ID 詳細資訊，請前往&#x200B;**[!UICONTROL 「詳細目錄 > 交易」]**，按一下&#x200B;**[!UICONTROL 「建立」]**，然後按一下&#x200B;**[!UICONTROL 「交易 ID 測試版」]**。 |
| 刊登版位預測 | (10 月 15 日發行) 若刊登版位具有從刊登版位層級調整的設計，其設定的[!UICONTROL 「預測」]區段現已加入新的[!UICONTROL 「預估上限」]區段，能顯示目前的鎖定目標設定有多少容量可用。 |

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search} 

上次更新日期：**2020年10月17日**

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 搜尋促銷活動] | 在[!UICONTROL 「帳戶」]檢視中，[!UICONTROL 「存取」]欄現在會指出 [!DNL Advertising Cloud Search] 何時無法登入已啟用的搜尋引擎帳戶。若要查看錯誤的成因，請將游標放在警告圖示上。 |
| [!UICONTROL 自訂警報] | 舊版[!UICONTROL 「警報測試版」]現在稱為[!UICONTROL 「自訂警報」]。 |
| [!UICONTROL 自訂警報] | 在自訂警報中，已簡化用來識別指定日期範圍的量度比起上一個期間的量度何時增加或減少的工作流程，並移至[!UICONTROL 「篩選器」]索引標籤。 |

### Ad Cloud 教學課程和課程

更新日期：**2020 年 12 月 2 日**

| 已發佈 | 名稱 | 解決方法 | 說明 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 11 月 14 日 | [使用 Adobe Analytics 建立 Advertising Cloud 控制面板](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-dashboards-a4adc.html?lang=zh-Hant) | 影片 | 建立 Advertising Cloud 控制面板以即時監控行銷活動的技巧。 |
| 2020 年 11 月 14 日 | [建立 Advertising Cloud 網站項目報表](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-site-entry-a4adc.html?lang=zh-Hant#analytics) | 影片 | 建立 Advertising Cloud 網站項目報表，以監控一週中的某天、一天中的某一時刻、瀏覽器和地理環境影響。 |
| 2020 年 11 月 14 日 | [使用 Advertising Cloud 資料建立 Analytics 自訂量度](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-custom-metrics-a4adc.html?lang=zh-Hant#analytics) | 影片 | 在 Adobe Analytics 中使用 Advertising Cloud 資料時可建立的實用自訂度量。 |
| 2020 年 11 月 14 日 | [建立 Analytics 區段以利執行啟動和報表彙整作業](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-segments-a4adc.html?lang=zh-Hant#analytics) | 影片 | 使用 Advertising Cloud 維度建立區段，以簡化報表和分析作業。 |
| 2020 年 11 月 14 日 | [了解預測對象](https://experienceleague.corp.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html?lang=zh-Hant#build-and-manage-audiences) | 影片 | 此影片中，我們會說明何謂 Audience Manager 預測對象、詳細解說其運作方式，並提供使用案例。 |
| 2020 年 11 月 14 日 | [建立 Advertising Cloud 啟用與報表的 Analytics 設定檔](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-profiles-a4adc.html?lang=zh-Hant#analytics) | 影片 | 如何使用 Adobe Analytics 為 Advertising Cloud 再行銷工作，建立強大的網站重新鎖定群組。 |
| 2020 年 11 月 14 日 | [使用 Advertising Cloud 行銷管道製作報表](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-reporting-a4adc.html?lang=zh-Hant#analytics) | 影片 | Advertising Cloud 檢視和點閱項目資料如何與 Adobe Analytics 行銷管道搭配運用。 |
| 2020 年 11 月 14 日 | [使用 Adobe Analytics 在發起行銷活動前建立分析作業](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-pre-launch-a4adc.html?lang=zh-Hant) | 影片 | 如何使用 Adobe Analytics 為發起 Advertising Cloud 付費媒體行銷活動奠定基礎。 |

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![圖示](/assets/target.png)[!DNL Target] {#target}

如需最新版本的資訊，請參閱 [[!DNL Target]  發行說明](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html)。

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是銷售機會管理的完整解決方案，適合 B2B 行銷人員使用，而透過該解決方案，他們可參與複雜購買歷程的每個階段，從中推動客戶體驗轉型。

### Marketo Engage 核心更新

如需最新版本的資訊，請參閱 [!DNL Marketo] [發行說明](https://docs.marketo.com/display/public/DOCS/Jan+%2721)。

### 即將推出的功能

本季預計推出下列功能：

| 功能 | 說明 |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>全新的帳戶型細分</li><li>儲存儀表板專有的篩選器</li><li>將 Bizible 儀表板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 淘汰

* **資產 API「_method」參數：** 2020 年 9 月後，資產 API 端點將不再接受於 POST 主體中使用 `_method` 傳遞查詢參數，以略過 URI 長度限制。
* **停止支援 Internet Explorer：**&#x200B;自 2020 年 7 月 31 日推出的版本開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

如需彙整資料和過往的發行說明，請參閱 [Marketo 發行說明](https://docs.marketo.com/display/public/DOCS/Release+Notes)。

## ![圖示](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud 的發行資訊和說明資源。

### Acrobat教學課程

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 29 日 | [組織頁面](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/organize.html) | 文章 | 使用Acrobat Document Cloud中的[!UICONTROL 組織頁面]來新增、取代、擷取、旋轉、刪除和移動PDF中的頁面。 |
| 2020 年 12 月 29 日 | [建立可填寫的表單](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/create-fillable-forms.html) | 文章 | 將在InDesign、Microsoft Word或Excel或其他應用程式中建立的掃描紙本表單或檔案轉換為可填寫的PDF表單。 |
| 2020 年 12 月 29 日 | [掃描和OCR](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/scan-and-ocr.html) | 文章 | 將檔案的掃描或影像轉換為可搜尋、可編輯的PDF檔案，並調整產生檔案的品質。 |
| 2020 年 12 月 28 日 | [準備可存取的PDF檔案](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility.html) | 文章 | 建立可廣泛存取的PDF檔案。 |
| 2020 年 12 月 28 日 | [使用表單資料](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/formdata.html) | 文章 | 如果您有一組已完成的表單，而且需要編譯資料，則可使用Acrobat DC將回應合併為單一試算表。 |
| 2020 年 12 月 28 日 | [縮減檔案大小並最佳化](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/reduce.html) | 文章 | 減少大型檔案並最佳化PDF，而不會影響分享、張貼或封存的品質。 |
| 2020 年 12 月 21 日 | [讓PDF選票更方便存取](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/by-industry/gov/pdfs/making-pdf-ballots-accessible.html) | 網路研討會 | 瞭解協助技術（例如螢幕閱讀器）的使用者閱讀及完成投票所需之PDF協助工具的關鍵領域。 |
| 2020 年 12 月 21 日 | [校訂與淨化](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/redact.html) | 文章 | 使用校訂工具，從PDF中永久移除私人或敏感資訊，並淨化檔案。 |
| 2020 年 12 月 18 日 | [動作精靈](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/action.html) | 文章 | 建立動作，自動將一組指令套用至一或多個檔案。 |
| 2020 年 12 月 15 日 | [使用存留時間(TTL)設定設定特徵有效期](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/configuring-trait-expiration-with-the-time-to-live-ttl-setting.html?lang=en#build-and-manage-audiences) | 影片 | 瞭解如何使用[!UICONTROL 即時時間]，如果您未在指定的時段內重新符合資格，則此為特徵的會籍到期。 |
| 2020 年 12 月 4 日 | [使用Adobe PDF工具API來OCR PDF檔案](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/ocr.html) | 文章 | 瞭解如何使用[!UICONTROL 光學字元辨識]來解除鎖定掃描的PDF，以擷取文字並建立可搜尋的檔案。 |
| 2020 年 12 月 4 日 | [Adobe PDF Tools API和Java快速入門](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartedjava.html) | 文章 | 開發人員只需幾分鐘即可開始使用，以便執行範例檔案，以存取所有可用的web services。 本教學課程將引導您完成開始使用PDF工具Java SDK執行範例的所有步驟。 |
| 2020 年 12 月 4 日 | [Adobe PDF Tools API和。Net快速入門](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartednet.html) | 文章 | 開發人員只需幾分鐘即可開始使用，以便執行範例檔案，以存取所有可用的web services。 本教學課程將引導您完成開始使用PDF工具。Net SDK執行範例的所有步驟。 |
| 2020 年 12 月 4 日 | [運用PDF工具API將PDF轉存為Word、PowerPoint等](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/exportpdf.html) | 文章 | 將PDF檔案轉換為MS Word，以編輯內容、核准，並稍後傳送簽名，以建立自訂合約工作流程。 或者，將PDF內容匯出為MS Excel格式，以進行發票和財務計算或資料分析。 |
| 2020 年 12 月 4 日 | [使用PDF工具API和Node.js，在幾分鐘內從HTML或MS Office建立PDF](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/createpdffromhtml.html) | 文章 | 瞭解使用全新Adobe PDF工具API將檔案工作流程數位化。 此API可讓開發人員自由選擇多種功能強大的PDF處理服務，以滿足複雜商業工作流程的需求。 |

### 最新 Adobe Sign 課程與教學課程

針對 Adobe Document Cloud 發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 12 月 22 日 | [薪資保護](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/expand/recipes/gov/usecasegovpaycheck.html) | 示範 | 瞭解您如何使用Adobe Sign將「付款保護計畫」表單轉換為線上互動式表單。 |

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=en)
* [Adobe Sign 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=en)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)
