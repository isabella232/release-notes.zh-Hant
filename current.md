---
title: 最新版本注意事項
description: 了解 Experience Cloud 產品和服務的最新版本注意事項、新功能和新文件。查看 Experience Cloud、適用於企業的 Creative Cloud 和 Document Cloud 的最新說明和教學課程。
doc-type: release notes
last-update: June 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: b0ad7a5c45760fba6a1a4e7e0f6dbbedbef93355
workflow-type: tm+mt
source-wordcount: '4913'
ht-degree: 41%

---

# Adobe Experience Cloud 發行說明 - 2021 年 6 月

![橫幅](assets/experience-cloud-banner-3.png)

Experience Cloud應用程式和服務每月更新。 此頁面是您尋找[!DNL Experience Cloud]和[!DNL Experience Platform]最新版本更新、檔案和教學課程的集中位置。 您也可以尋找適用於 [!DNL Creative Cloud for Enterprise] 和 [!DNL Document Cloud] 的新文件。

>[!NOTE]
>
>訂閱每月 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)，以接收此頁面更新的電子郵件通知。此頁面會在整個月進行維護，請定期回來查看是否有 Adobe 企業產品和 Experience League 文件的更新。

最近更新：**2021 年 6 月 14 日**

* [Experience Cloud中心介面元件](#ecloud)
* [Adobe 系統狀態](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) 和 [Customer Journey Analytics](#cust-journey)
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hant/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![](/assets/ec_appicon_24.png) 圖示Experience Cloud中央UI元件 {#ecloud}

Experience Cloud中央介面元件包括可從統一產品標題存取的更新，例如自助服務、搜尋和使用者帳戶偏好設定。 您可以在此處找到人員、位置（位置）和產品管理的更新。

| 功能 | Date | 說明 |
| ------- | ------- | ------- |
| AdobeFederated ID的單一登入支援 | 2021 年 6 月 17 日 | 如果您使用Federated ID，則無需輸入電子郵件地址或密碼即可登入Experience Cloud。 若要使用此功能，請將&#x200B;**#/sso:@domain**&#x200B;新增至Experience CloudURL。 <br><br>例如，假設您擁有網域 **adobecustomer.** com且想登入Adobe Analytics。URL會是：**https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**。 |
| Experience League搜尋 | 2021 年 6 月 1 日 | Experience League檔案搜尋功能已改善。 導覽至[Experience League](https://experienceleague.adobe.com/docs/?lang=en)並使用&#x200B;**[!UICONTROL Search]**&#x200B;欄位來尋找教學課程、檔案、課程等。 |

{style=&quot;table-layout:auto&quot;}

**更多說明資源**

* [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-tw)和用戶管理的管理幫助
* [Places - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)的說明和發行說明
* [People — 客戶屬性和受眾程式庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)相關說明。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

如需最新版本的資訊，Adobe 系統狀態的最新更新位在 [Adobe 系統狀態 - 2020 年 5 月 21 日](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hant)。

## ![圖示](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

包含發行更新資訊以及Experience Platform和Experience Platform Launch的新檔案。

* **2021年5月26日：** [Experience Platform發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)
* **2021年5月17日：** [Experience Platform資料收集發行說明](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=zh-Hant) (原稱Experience Platform Launch)

### Experience Platform 教學課程與其他課程 {#tutorials-platform}

針對 Experience Platform 和服務所發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [準備資料](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | 影片 | 了解如何清除、準備和結合多個資料集的資料，以使用「建立表格AS」(CTAS)和Spark SQL函式建立資料集，以便製作報表和控制面板。 |
| 2021 年 6 月 | [在沙箱之間複製結構](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | 影片 | 了解如何使用[!UICONTROL 匯出/匯入結構API]，將結構從Adobe Experience Platform的一個沙箱複製到另一個沙箱。 在開發沙箱中建置並測試您的結構，然後複製到生產環境。 |
| 2021 年 6 月 | [更新結構](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | 影片 | 了解更新Adobe Experience Platform中現有結構時應注意的基本事項。 |
| 2021 年 6 月 | [架構建置區塊](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | 影片 | 了解Experience Data Model(XDM)結構描述的重要建置區塊元素，包括欄位、資料類型、結構欄位群組、類別和行為。 |
| 2021 年 6 月 | [建立類](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | 影片 | 了解如何在Adobe Experience Platform中建立類別，以便用於Experience Data Model(XDM)結構。 |
| 2021 年 6 月 | [配置結構之間的關係](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | 影片 | 了解如何在Adobe Experience Platform中設定兩個結構之間的關係。 關係可讓您使用一個資料集作為另一個資料集的查閱表格。 |
| 2021 年 6 月 | [建立資料類型](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | 影片 | 了解如何在Adobe Experience Platform中建立您自己的資料類型，以便用於Experience Data Model(XDM)結構。 |
| 2021 年 6 月 | [將您的資料模型轉換為體驗資料模型](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | 影片 | 了解資料架構師如何運用現有的交易式資料模型，並將其轉換為體驗資料模型。 此影片說明使用實體關係圖的建模方法之差異。 |
| 2021 年 6 月 | [規劃您的資料模型](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | 影片 | 在Adobe Experience Platform中開始建立綱要之前，請先了解該做什麼。 記錄您的業務使用案例、了解您的Platform授權、了解產品護欄，以及在最終確定您的資料模型之前識別要擷取的資料。 |
| 2021 年 6 月 | [塔布洛](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | 影片 | 了解如何從支援`PostgreSQL`協定的各種案頭客戶端應用程式連接到[!UICONTROL 查詢服務]，以及如何使用`PostgreSQL`工具和驅動程式連接和寫入查詢。 |
| 2021 年 6 月 | [Adobe定義的函式](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | 影片 | 了解如何使用Adobe Experience Platform [!UICONTROL 查詢服務]中的Adobe定義函式，對體驗事件資料執行常見的業務相關工作。 |
| 2021 年 6 月 | [資料探索](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | 影片 | 了解如何使用SQL函式驗證所擷取的資料、預覽資料，以及探索資料的統計和分析屬性。 |
| 2021 年 6 月 | [查詢服務概述](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | 影片 | 了解Adobe Experience Platform中的Query Service，以及它如何協助您了解客戶行為並產生具影響力的深入分析。 |
| 2021 年 6 月 | [查詢服務UI概述](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | 影片 | 了解如何在Adobe Experience Platform Query Service中撰寫和執行查詢、檢視先前執行的查詢，以及存取由您IMS組織內其他使用者儲存的查詢。 |
| 2021 年 6 月 | [查詢 API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | 影片 | 了解如何使用Adobe Experience Platform [!UICONTROL 查詢服務API]來撰寫和執行查詢、建立排程查詢及建立查詢範本。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

運用Experience Platform聰明地即時預測每個人的需求，以大規模協調不同體驗管道的客戶歷程。

* 2021年6月更新 — [Journey Orchestration發行說明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hant)

**Journey Orchestration 的其他資源**

[文件](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [做法影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=en)

## ![圖示](/assets/experience_platform_appicon_24.png) Offer Decisioning{#offer-decisioning}

[!UICONTROL Offer Decisioning] 是一項與 Adobe Experience Platform 整合的應用程式服務。使用 [!UICONTROL Offer Decisioning] 可在適當的時間為所有接觸點的客戶提供最佳優惠方案和體驗。

* 更新日期： 2021年4月 — [Offer decisioning發行說明](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=zh-Hant#new)

**適用於 Offer Decisioning 的更多資源**

[文件](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [做法影片](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=zh-Hant)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2021 年 6 月 17 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Adobe Analytics 中的修正項目](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | [全面發佈](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=zh-Hant) - 目標日期 | 說明 |
| ----------- | ---------- | ------- |
| 不適用 | 不適用 |

{style=&quot;table-layout:auto&quot;}

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | [全面發佈](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - 目標日期 | 說明 |
| ----------- | ---------- | ----- |
| 不適用 | 不適用 |

{style=&quot;table-layout:auto&quot;}

### Adobe Analytics 中的修正項目 {#aa-fixes}

* 修正「收入即時」報表中顯示錯誤貨幣的問題。 (AN-254649)
* 更新報告](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html)中[eVar區分大小寫的說明檔案。 (AN-246438)
* 更新說明檔案，以便更妥善說明[資料摘要實作](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html)和[這裡](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl)。 (AN-219485)
* 修正Data Warehouse報告中未傳送部分資料的問題(AN-259951;AN-259712;AN-260107;AN-259953)

#### Adobe Analytics或CJA中的其他修正

AN-246344;AN-250035;AN-250354;AN-252482;AN-254661;AN-254965;AN-255424;AN-256515;AN-257232;AN-257572;AN-257893;AN-258393;AN-259203;AN-259513;AN-259614;AN-259665;AN-259931;AN-260074;AN-260085;AN-260147;AN-260190;AN-260198;AN-260290;AN-260306(CJA);AN-260508;AN-260625;AN-260793;AN-260861;AN-260938;AN-260945;AN-261149;AN-261317

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 瀏覽器使用者代理反映的macOS作業系統版本不正確 | 2021 年 5 月 19 日 | 所有主要瀏覽器目前都會以使用macOS 10的方式，錯誤報告macOS X 11及以上版本的使用者，如瀏覽器的使用者代理字串所記錄。 此問題會影響Adobe Analytics報表，因為報表會使用使用者代理來判斷裝置資訊，例如作業系統。 這種不正確顯然是為了防止某些網站出現相容性問題。 請參閱此[Bugzilla票證](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454)以獲得參考。 目前不清楚此問題會在何時修正或是否修正。<br>有些瀏覽器最初正確記錄了macOS 11，因此可能會有一些流量符合此值。但是，由於報告不準確，對作業系統macOS 11進行篩選並不實用。<br>此問題相當重要，因為自macOS 11上的Safari開始，Apple已更新ITP Cookie過期限制，以套用至CNAME實作(請參閱 [WebKit部落格文章](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/))。<br>在此更新前，這些限制僅套用至透過JavaScript設定的用戶端Cookie。這種不準確性使得很難評估使用OS 11的流量，並因此受到ITP變更的影響。 您可以在此處](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html#cookies)進一步了解Cookie和Adobe Analytics [。 |
| 三個 Analytics API 服務終止運作 | 2021 年 5 月 19 日 | 下列Analytics Legacy API服務於2021年8月18日終止服務並關閉。 所有目前使用這些服務建立的整合功能當天都停止運作。<ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy OAuth 驗證 (OAuth 和 JWT)</li></ul>Adobe提供[舊版API EOL常見問題集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)以協助回答您的問題，並提供如何進行的指引。 採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy OAuth 帳戶可移轉為 [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| 2021 ISO地區更新 | 2021 年 5 月 13 日 | Adobe將於2021年5月21日執行2021 ISO地區更新。 預期在此版本後會出現微幅更新。 |
| 全面處理資料來源的 EOL | 2021 年 4 月 12 日 | Adobe 計劃在 2021 年 7 月 31 日淘汰完整處理資料來源。自 2021 年 3 月 25 日起，將無法再建立此類型的新匯入。請利用[大量資料插入 API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md)匯入此類資料。 |
| [!UICONTROL Report Builder] 登入更新 | 2021 年 4 月 9 日 | 在 2021 年 1 月 14 日，[!UICONTROL Report Builder] 登入更新淘汰對舊版技術的相依性，並使登入程序符合 Experience Cloud。Experience Cloud 使用您的 Enterprise ID (電子郵件和密碼)。為確保對 [!UICONTROL Report Builder] 的存取不中斷，請於 2021 年 7 月 22 日前將 [!UICONTROL Report Builder] 增益集更新至 5.6.47 版或更新版本。Report Builder 5.6.47 版或更新版本只支援 Experience Cloud 登入，不支援單一登入。 |
| 資料摘要和 Data Warehouse IP 位址變更 | 2021 年 4 月 6 日 | 自 6 月 17 日起，資料摘要和 Data Warehouse 傳遞系統將在 Adobe 的資料中心內重新配置，因此您可能會看到外部 IP 位址變更。 Adobe 建議您最好確認，您的報表和資料摘要之來源資料中心的所有 IP CIDR 區塊，都存在於您所控制的目標系統的防火牆內。[以下是要放入防火牆允許清單的IP位址範圍完整清單](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=zh-Hant#data-collection-and-ftp-ip-address-blocks)。 |
| 即將推出之 Analytics 選單變更的通知 | 2021 年 3 月 24 日 | Adobe 已經在 2021 年 4 月 22 日更新了「**[!UICONTROL 元件]**」、「**[!UICONTROL 工具]**」和「**[!UICONTROL 管理]**」下拉選單，以提高效能。所有這些頁面仍可在&#x200B;**[!UICONTROL 所有元件]**、**[!UICONTROL 所有工具]**&#x200B;和&#x200B;**[!UICONTROL 所有管理員]**&#x200B;連結下使用 — 它們將從下拉式功能表中移除。 以下是將從下拉選單中移除並放置在其相對應連結頁面上的選單項目：<br><br> [!UICONTROL 元件]<ul><li>[!UICONTROL 書籤]</li><li>[!UICONTROL 儀表板]</li><li>[!UICONTROL 目標]</li><li>[!UICONTROL 日曆事件]</li><li>[!UICONTROL 排程報告]</li><li>[!UICONTROL 報表設定]</li></ul>[!UICONTROL 工具]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search &amp; Promote]</li></ul>[!UICONTROL 管理員]<ul><li>[!UICONTROL 用戶管理]</li><li>[!UICONTROL 分類匯入工具]</li><li>[!UICONTROL 分類規則產生器]</li><li>[!UICONTROL 資料來源]</li><li>[!UICONTROL 資料連接器]</li><li>[!UICONTROL 公司設定]</li><li>[!UICONTROL 記錄]</li><li>[!UICONTROL 動態標籤管理]</li><li>[!UICONTROL 代碼管理器]</li><li>[!UICONTROL 依 IP 排除]</li><li>[!UICONTROL 流量管理]</li></ul> |
| Same-as-SiteCatalyst VISTA Processing ON | 2021 年 3 月 17 日 | 在 2021 年 6 月 17 日，所有報表套裝都將更新：將 [!UICONTROL Same-as-SiteCatalyst VISTA Processing] 設定為 ON。此變更會透過處理資料以符合處理規則來影響 Data Warehouse 報告。如有疑問或需要釐清一些事情，請聯繫客戶服務。 |
| Reports &amp; Analytics 登陸頁面選項 | 2021 年 2 月 19 日 | 2021 年 3 月 25 日，將新 Reports &amp; Analytics 儀表板或其他內容設定為 Adobe Analytics 登陸頁面的選項將被刪除。如果您先前將 Reports &amp; Analytics 頁面設為自訂登陸頁面，則該頁面將繼續有效，直到您在「[!UICONTROL 用戶偏好設定]」中修改登陸頁面為止。 |
| Adobe Data Connectors 終止服務 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 的舊技術已無法使用或不再支援。[Adobe Exchange 合作夥伴計劃](https://partners.adobe.com/exchangeprogram/experiencecloud)中有提供新的標準。您可以針對任何整合使用該項標準，以繼續獲得產品供應和支援。生命週期結束的官方日期為 2021 年 8 月 1 日。[了解更多...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=zh-Hant) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

如需 AppMeasurement 發行的最新消息，請參閱[適用於 JavaScript 的 AppMeasurement 發行說明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)。

### 最新 Analytics 課程與教學課程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 的最新課程、教學課程和文章。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [管理員專用 Customer Journey Analytics 快速入門](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | 課程 | 了解如何設定、設定和管理Customer Journey Analytics。 了解一些基本概念，為您奠定基礎，然後進入更多設定步驟。 接著，我們會針對從Adobe Analytics移轉計算量度和區段至Customer Journey Analytics提供一些建議，來限制課程內容。 |
| 2021 年 6 月 | [設定內部網站搜尋報告](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | 影片 | 在Analysis Workspace中建立並設定自由表格，以分析網站上的內部搜尋功能。 |
| 2021 年 6 月 | [將 Web SDK 變數對應至 Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | 影片 | 了解如何使用處理規則將分析變數從Web SDK對應至Adobe Analytics。 |
| 2021 年 6 月 | [使用 Web SDK 實作內部搜尋變數](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | 影片 | 了解如何使用Web SDK為內部搜尋詞追蹤使用案例實作Adobe Analytics變數。 查看從頁面到Experience Edge，再到Adobe Analytics的資料流程。 |
| 2021 年 6 月 | [使用 AppMeasurement 實作內部搜尋變數](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | 影片 | 此影片會說明如何使用「Experience Platform資料收集/啟動」，為Adobe Analytics實作內部網站搜尋變數的步驟，包括搜尋詞、結果數量等。 |
| 2021 年 6 月 | [定義您的內部網站搜尋業務要求](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | 影片 | 在決定追蹤網站上的內部搜尋時，首先必須決定要追蹤的搜尋方面，以及分析結果後可採取哪些動作。 本影片會逐步說明業務需求的檔案。 |

{style=&quot;table-layout:auto&quot;}

### Analytics 說明資源

* [Adobe Analytics 產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修正與改良。

### 修正和改良 {#aam-fixes-and-improvements}

* 已發行[活動使用量報表](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en)的增強功能，現在可讓您檢閱超過一年的資料。 (AAM-58268)
* Adobe可為Audience Manager客戶提供Audience ManagerAmazon S3貯體的使用者存取金鑰。 基於安全考量，閒置100天後，金鑰現在會自動停用。 如需詳細資訊，請參閱[資料收集與產品整合常見問題集](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en)中頁面底部的問題。

## ![圖示](/assets/aem.png) Experience Manager {#aem}

 Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

>[!NOTE]
>
>Adobe建議瀏覽[Experience Manager版本更新和路線圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以保持最新的發行資訊。

### Experience Manager產品更新

* **Experience Manager 6.5.9.0**

   Experience Manager6.5 Service Pack 9.0（6.5.9.0，已於2021年5月27日發行）是項重要更新，其中包括自2019年4月AEM 6.5全面發行以來所推出的新功能、客戶要求的重要增強功能，以及效能、穩定性和安全性的改善項目。

   * [版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=zh-Hant)
   * [AEM Forms 發行交付項目](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### Experience Manager產品發行

* **Experience Manager as a Cloud Service**

   Experience Manager as a Cloud Service 中的新功能：

   * **Adobe Experience Manager as a Cloud Service 基礎**

      * [發行前管道](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en):在即將上線的功能投入生產前，先預覽一個月！
      * [取代API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en):最新淘汰的API清單。
      * [Experience Manager作為Cloud ServiceSDK建置分析器Maven外掛程式](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en):將您的Maven專案更新至最新版本，其中包括已棄用的Java™ API檢查和其他改善。
   * **Experience Manager Sites as a Cloud Service**

      您現在可以在新的[預覽層級](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en)上驗證內容，以模擬最終的體驗外觀，如同您在發佈層級上一樣。 此新功能由「Experience Manager網站管理的出版物」精靈啟用，可讓您在[!UICONTROL Publish]或[!UICONTROL Preview]之間選擇發佈目的地。 接著，您就可以透過專用URL存取[!UICONTROL 預覽]上的體驗。 在[!UICONTROL 預覽]上進行驗證後，您可以照常從[!UICONTROL 作者]發佈內容至[!UICONTROL 發佈]。 在Experience Manager中啟用[!UICONTROL 預覽]服務，因為Cloud Service環境將在未來幾週逐步推出。

   * **Experience Manager Assets as a Cloud Service**

      發行前管道的新功能：

      * 中繼資料結構可直接套用至資料夾屬性。
      * [!UICONTROL 資產大量擷取]工具可讓您在大量擷取期間新增中繼資料。
      * 使用者體驗增強功能會顯示資料夾中存在的資產數量。 若資料夾中有超過1000個資產，「Experience Manager資產」會顯示1000個以上。

      [!UICONTROL Dynamic Media]中的新功能：

      * 智慧型影像設備像素比(DPR)和網路頻寬優化使您能夠在具有高解析度顯示器且網路頻寬受限的設備上高效地提供最佳質量影像。 請參閱[智慧影像常見問題集](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en)。



### **Experience Manager社群**

* [為所有Experience Manager部落格一站式服務](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [提交新Experience Manager構想的准則](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [Adobe峰會2021年與丹·利維交談](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865):每年，每位Adobe員工（從工程師、資料科學家到UX設計師和產品經理）都有機會分享創新想法，以改進品牌與客戶互動的方式。和我們一起參加「Adobe斯尼克斯」(Sneaks)，我們在這裡分享前七大項目，在人工智慧和低代碼應用等領域利用最新技術。

### Experience Manager 發行資訊

所有 Experience Manager 的版本注意事項都會保留在以下頁面：

* [Experience Manager as a Cloud Service 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Experience Manager Cloud Manager 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hant)
* [Automated Forms Conversion Service 版本注意事項](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Experience Manager 6.5 Service Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hant)
* [Experience Manager Assets Dynamic Media 版本注意事項](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hant)
* [Experience Manager Brand Portal 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hant)
* [Experience Manager 桌面應用程式版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Experience Manager Dispatcher 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hant)
* [Livefyre 版本注意事項](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hant)

### 最新 Experience Manager 課程與教學課程  {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [實作介面的方法](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | 文章 | 了解如何使用Document CloudREST API實作介面方法以建立PDF。 |
| 2021 年 6 月 | [建立服務介面](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | 文章 | 在要公開的介面中定義方法。 |
| 2021 年 6 月 | [建立自訂OSGi設定](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | 文章 | 了解自訂OSGi設定，以便擷取Adobe I/O專案詳細資訊。 |
| 2021 年 6 月 | [建立內容分析器](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | 文章 | 了解如何建立JSON部件，其中包含建立PDF REST呼叫之輸入參數的相關資訊。 |
| 2021 年 6 月 | [建立自訂流程步驟](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | 文章 | 檢視自訂處理步驟的完整程式碼，該程式碼會以轉換的PDF來轉換和取代原生檔案。 此自定義步驟將搜索資料夾名稱下的所有附件，該資料夾名稱作為工作流中的進程參數提供。 此自訂處理步驟使用自訂`DocumentCloudSDKService`的方法來建立PDF。 |
| 2021 年 6 月 | [GraphQL持續查詢](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | 影片 | 了解如何在Experience Manager中啟用、建立、更新及執行持續查詢。 |
| 2021 年 6 月 | [在AEM Forms中建立您的第一個servlet](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | 文章 | 建置您的第一個Sling servlet，以便將資料與表單範本合併。 |
| 2021 年 6 月 | [使用Experience Manager表單建立您的第一個OSGi服務](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | 文章 | 使用AEM Forms建立您的第一個OSGi服務，借此將資料與範本合併，以產生PDF。 |

{style=&quot;table-layout:auto&quot;}

### 適用於 Experience Manager 的其他說明資源

* [Experience Manager as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Experience Manager 6.5 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hant)
* [Experience Manager 6.4 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hant)
* [Experience Manager 6.3 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-3.html)
* [Experience Manager 6.2 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant#previous-updates)
* [舊版 Experience Manager 文件](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Cloud Manager 使用手冊](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hant)
* [Dynamic Media Classic 說明首頁](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hant)
* [Experience Manager 文件：最近更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hant#aem-as-a-cloud-service)

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新產品發行版

進一步了解已發行的最新功能、改良與修正：

* **新的Adobe Campaign v8** 提供重要的基礎架構、安全性、傳遞能力及監控增強功能。Adobe Campaign v8可大幅改善其規模和速度，並能管理更多客戶設定檔，以及更高的每小時傳送率和交易。 進一步了解[Campaign v8檔案](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html)。

* **Adobe Campaign Classic v7 21.1.3版：** 了解更多 [Campaign Classicv7發行說明](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)。

* **Adobe Campaign Standard 21.2版：** 進一步了解 [Campaign Standard發行說明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant)。

### 最新[!UICONTROL Campaign]課程與教學課程{#tutorials-campaign}

| 已發佈 | 名稱 | 解決方法 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [將Campaign Standard與Analytics整合，以最佳化您的電子郵件行銷](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2021.1.integration) | Campaign Standard | （課程）了解如何將Campaign Standard與Adobe Analytics整合，以及使用即時資料最佳化您的電子郵件行銷策略。 本課程會示範如何在Adobe Analytics中建立Campaign Standard報表。 接著，了解如何使用Experience Cloud觸發器和Platform launch，根據客戶活動設定行銷和交易式訊息。 |
| 2021 年 6 月 | [Adobe Campaign V8 教學課程](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign V8 | 本使用手冊包含了 Adobe Campaign V8 許多功能的相關影片和教學課程。 |
| 2021 年 6 月 | [建立及設計電子郵件遞送](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | 促銷活動V8 | （影片）了解建立電子郵件傳送的程式，並了解如何設計及個人化電子郵件內容。 |
| 2021 年 6 月 | [針對遞送功能設計電子郵件](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | 促銷活動V8 | （影片）了解如何將傳遞能力最佳實務套用至您的電子郵件傳遞。 |
| 2021 年 6 月 | [使用類型規則管理疲勞](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | 促銷活動V8 | （影片）了解如何套用類型規則來實作疲勞管理。 |
| 2021 年 6 月 | [使用篩選器設定疲勞管理](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | （影片）了解如何使用篩選器在Adobe Campaign中實作疲勞管理。 |

{style=&quot;table-layout:auto&quot;}

### Campaign 說明資源

* Adobe Campaign Standard：[說明中心](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [發行說明](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [作法影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新內容](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[說明中心](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [作法影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant)- [最新文件更新內容](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=en) 作法影片

## ![](/assets/advertising-cloud.png) 圖示廣告 {#adcloud}

[!DNL Adobe Advertising]的發行說明。

* [Advertising DSP 新功能](#adcloud-dsp)
* [Advertising Search 新功能](#adcloud-search)

### [!DNL Advertising DSP] 中的新功能{#adcloud-dsp}

上次更新：**2021年6月10日（6月16日發行）**

| 功能 | 說明 |
| -----------| ---------- |
| 行銷活動管理 | （6月16日發行版本）標準顯示版位具有版位層級的步調和預算，可提供預測功能。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Search] 中的新功能{#adcloud-search}

上次更新：**2021年5月19日（5月18日發行）**

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 通知中心測試版] | 所有使用者皆可使用[!UICONTROL 通知中心Beta]。 使用它可訂閱帳戶驗證錯誤、觸發的自訂警報，以及您產生[!UICONTROL Advertising Insights]的完成的電子郵件和網路通知。<br>您可以透過以下任一項檢視通知：<ul><li>[!UICONTROL 通知]面板，可從任何頁面右上角的通知連結開啟。</li><li>[!UICONTROL 通知中心]位於[!UICONTROL 前瞻分析與報表>通知中心測試版]。</li></ul><br><b>注意：</b> 由於改善了通知的儲存方式，所有現有通知皆已清除。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

請參閱 Magento Commerce 和 Open Source [版本注意事項](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)，以取得最新版本資訊。

## ![圖示](/assets/target.png)[!DNL Target] {#target}

如需最新版本資訊，請參閱 [[!DNL Target]  版本注意事項](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是適用於潛在客戶管理以及想要透過參與複雜購買旅程的每個階段來轉換客戶體驗的 B2B 行銷人員的完整應用程式。

### Marketo Engage 核心更新

如需最新發行計畫資訊和發行說明，請參閱[!DNL Marketo Engage] [發行計畫](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) 。

## ![圖示](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe[!DNL Workfront]是一個統一的工作管理應用程式，用於共用思想、建立內容、管理複雜的流程並執行其最佳工作。

請參閱[[!DNL Workfront] 發行版本](https://one.workfront.com/s/product-releases)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

針對 Adobe Document Cloud 發佈的新影片、教學課程或其他課程。

### Document Cloud課程與教學課程{#tutorials-doc-cloud}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2021 年 6 月 | [Adobe Acrobat for Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | 影片 | 直接在Google Drive應用程式中存取省時的PDF工具和電子簽名工作流程。 |

{style=&quot;table-layout:auto&quot;}

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

| 已發佈 | 名稱 | 類型 | 說明 |
| ----------| --------- | --------- | --------- |
| 2021 年 6 月 | [在iPad（和iPhone）上，用Fresco試試手](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | 影片 | 在這個15分鐘的實作研討會上，與Adobe Fresco一起探索全新的數位繪圖世界。 快速學習如何使用圖層和剪裁蒙版，以將油漆和紋理與基本形狀一致。 |
| 2021 年 6 月 | [圖式字母湯的解碼](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | 影片 | PG、PNG、SVG、GIF和EPS檔案均常用於設計，有些用於網頁，有些用於演示文稿、出版物和創意項目。 但……他們什麼意思，你該選哪個？ 在這15分鐘的實作研討會中了解詳情。 |

{style=&quot;table-layout:auto&quot;}

如需最新教學課程，請參閱[企業TutorialsCreative Cloud](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en)。
