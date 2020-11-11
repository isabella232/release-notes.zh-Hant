---
title: Adobe Experience Cloud 發行說明
description: Adobe Experience Cloud 發行說明
doc-type: release notes
last-update: November 2020
author: mfrei
translation-type: ht
source-git-commit: 46d20e153aaa57df2387c2d084b6c20b914bc8e1
workflow-type: ht
source-wordcount: '8040'
ht-degree: 100%

---


# Adobe Experience Cloud 版本說明 - 2020 年 11 月

![橫幅](/assets/experience-cloud-banner-3.png)

此頁面主要說明 [!DNL Adobe Experience Cloud] 的新功能、修正項目和重要注意事項。此外還有最新文件、訓練課程和教學課程影片，協助您充份運用 Experience Cloud。

>[!IMPORTANT]
>
>本頁面可能包含特定產品的發行前內容，且在發行日期之前可能有所變更。請時常回訪以取得最新消息。

>[!NOTE]
>
>訂閱 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。

最近更新：**2020 年 11 月 10 日**

* [Adobe 系統狀態](#status)
* [Experience Cloud 服務與管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey) (更新日期：**2020 年 11 月 10 日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem) (更新日期：**2020 年 10 月 28 日**)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud) (更新日期：**2020 年 10 月 28 日**)
* [[!DNL Target]](#target) (更新日期：**2020 年 11 月 2 日**)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Primetime]](https://docs.adobe.com/content/help/zh-Hant/primetime/release-notes/home.html)
* [Document Cloud](#doc-cloud)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

>[!NOTE]
>
>Experience Cloud 文件正移至 Experience League。所有發行說明、文章、影片和教學課程，都會在 10 月從 `docs.adobe.com` 的目前位置移至 Experience League。如此能夠確保從單一位置提供所有學習、自助、培訓和社群內容。變更後，您無需執行任何操作，所有連結都將重新導向至 Experience League。開始切換後，我們會更新發行說明。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/tw/)。

未更新。

如需最新發行資訊，請參閱 [Adobe 系統狀態 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hant/release-notes/experience-cloud/previous/2020/05212020.html#status)。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 服務與管理 {#ecloud}

[Experience Cloud 服務與管理](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html)文件先前稱為 _Experience Cloud 核心服務_，其中包含客戶屬性、對象庫 ([!UICONTROL 人物]服務) 啟用、使用者和產品管理，以及 Experience Cloud Cookie。

未更新。

如需最新發行資訊，請參閱 [Experience Cloud 服務的彙整發行說明](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/release-notes/release-notes.html)。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

包含 Experience Platform 和 Experience Platform Launch 的版本更新資訊。

發行日期：**2020 年 10 月 14 日**

如需下列項目之更新的相關資訊，請參閱 [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)：

* 資料準備
* 即時客戶個人檔案
* 細分服務
* 來源

### Experience Platform Launch

如需 Platform Launch 的相關資訊，請參閱 [Experience Platform Launch 發行說明](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)。

### Experience Platform 和服務教學課程與其他課程

針對 Experience Platform 和服務所發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 26 日 | [Offer Decisioning 簡介](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html) | 影片 | 這部影片主要概略介紹 [!UICONTROL Offer Decisioning]，這是以 Adobe Experience Platform 為基礎打造而成的應用程式服務。影片內容涵蓋 [!UICONTROL Offer Decisioning] 解決的企業難題、重要功能、基本架構和主要使用案例。 |
| 2020 年 10 月 29 日 | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=zh-Hant) | 影片 | 了解各大品牌如何善用 Adobe 的全新 [!UICONTROL Offer Decisioning] 服務來定義及管理選件、運用即時客戶資料，並提供客戶期望的合適體驗。 |
| 2020 年 9 月 14 日 | [Attribution AI 的商業價值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/intelligent-services/business-value-of-attribution-ai.html) | 影片 | [!UICONTROL Attribution AI] 是 [!UICONTROL Intelligent Services] 的一部分，是一種多管道的演算法歸因服務，可計算客戶互動對指定結果的影響和累加影響。透過 [!UICONTROL Attribution AI]，行銷人員可經由了解每個客戶在客戶歷程各個階段的互動所產生的影響，來衡量行銷和廣告支出並予以最佳化。 |
| 2020 年 9 月 14 日 | [Customer AI 的商業價值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/intelligent-services/business-value-of-customer-ai.html) | 影片 | 此影片顯示客戶 [!UICONTROL Customer AI] 如何運用 AI 傾向豐富客戶個人檔案，以及執行客戶細分和目標定位工作。 |
| 2020 年 9 月 14 日 | [Platform 和 Magento 的商業價值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/experience-cloud/business-value-of-platform-and-magento.html) | 影片 | 此影片顯示 Adobe Experience Platform 可與 [!DNL Magento] 商務搭配使用，以建立客戶的單一檢視，並在數位店面和各管道間聰明地打造個人化體驗。 |

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

不論客戶處於哪個歷程階段，Adobe Experience Platform 均可聰明地即時預測每個人的需求，以便大規模協調不同體驗管道的客戶歷程。

### Journey Orchestration 的其他資源

[文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/zh-Hant/journey-orchestration-learn/tutorials/understanding-journey-orchestration.translate.html)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2020 年 10 月 29 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey) (更新日期：2020 年 11 月 10 日)
* [Media Analytics 新功能](#media-aa)
* [Adobe Analytics 修正項目](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ------- |
| Adobe Analytics 文件 | 2020 年 11 月 | Adobe Analytics 文件正移至 Experience League。所有文章、影片、發行說明和教學課程，都會在 10 月從 `docs.adobe.com` 的目前位置移至 `experienceleague.adobe.com`。如此能夠確保從單一位置提供所有學習、自助、培訓和社群內容。變更後，您無需執行任何操作，所有連結都將重新導向至 Experience League。開始切換後，我們會更新發行說明。 |
| [!UICONTROL 工作區] [!UICONTROL 線條]視覺效果：移動平均趨勢線選項 | 2020 年 10 月 8 日 | 在[!UICONTROL 「線條」]視覺效果趨勢線設定中新增了移動平均。移動平均也稱為滾動平均，會使用特定數量的資料點 (由[!UICONTROL 期間]選項決定)、求取其平均值，並將平均值作為線條中的點。[深入了解](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/visualizations/line.html) |
| [!UICONTROL 資料修復 API] | 2020 年 10 月 8 日 | [!UICONTROL 資料修復] API 是從 Analytics 報表套裝中刪除資料的工具。10 月版包含將指定日期範圍內的指定 eVar、Prop 和 [!UICONTROL Activity Map] 變數刪除的功能。未來將發行其他功能。使用[!UICONTROL 資料修復] API 會永久刪除現有的 Adobe Analytics 資料。建議在執行修復時應多加留意，盡可能避免意外刪除。存取[!UICONTROL 資料修復] API 需要簽署合約 - 請洽詢您的帳戶團隊以取得詳細資訊。[深入了解](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/data-repair.md) |
| [!UICONTROL 工作區]：效能說明頁面 | 2020 年 10 月 22 日 | [!UICONTROL Analysis Workspace] 效能說明頁面會顯示對專案效能造成影響的不同因素，以及最佳化秘訣的連結。[深入了解](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| Analytics [!UICONTROL 控制面板] UI 的增強功能 | 2020 年 10 月 23 日 | 現在，在[!UICONTROL 工作區]中建立行動計分卡時，計分卡的樣式會與應用程式相符。 |

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ----- |
| Customer Journey Analytics文件 | 2020 年 11 月 | Customer Journey Analytics 文件正移至 Experience League。所有文章、影片、發行說明和教學課程，都會在 10 月從 `docs.adobe.com` 的目前位置移至 `experienceleague.adobe.com`。如此能夠確保從單一位置提供所有學習、自助、培訓和社群內容。變更後，您無需執行任何操作，所有連結都將重新導向至 Experience League。開始切換後，我們會更新發行說明。 |
| [!UICONTROL 線條]視覺效果：移動平均趨勢線選項 | 2020 年 10 月 8 日 | 在「線條」視覺效果趨勢線設定中新增了移動平均。移動平均會計算指定前期的平均值，並將其作為趨勢線資料點，然後再計算下一個期間。[深入了解](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/visualizations/line.html) |
| 移除回填限制 | 2020 年 10 月 19 日 | 為改善 CJA 體驗，我們已移除回填 (匯入歷史資料) 限制。過去，您可以自行回填最多 25 億列的資料，若超過這個數字便需有工程技術介入。現在，您可以自行回填資料，沒有任何限制。[深入了解](https://docs.adobe.com/content/help/zh-Hant/analytics-platform/using/cja-connections/create-connection.html#enable-connection) |
| Analysis Workspace 效能說明頁面 | 2020 年 10 月 22 日 | Analysis Workspace 效能說明頁面會顯示對專案效能造成影響的不同因素，以及最佳化秘訣的連結。[深入了解](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| [!UICONTROL 「逗留時間」]量度和維度 | 2020 年 10 月 30 日 | [!UICONTROL 「逗留時間」]量度和維度可供您查看消費者在客戶歷程各階段所花費的時間，讓您能更全面掌握各管道的參與度和瓶頸所在。 |
| [!UICONTROL 「裝置」]和[!UICONTROL 「地理位置」]維度 | 2020 年 10 月 30 日 | 現在，[!UICONTROL 「裝置」]和[!UICONTROL 「地理位置」]維度預設可在 [Adobe Analytics 來源連接器](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html)的「全域查詢支援」專案中使用。這項備受期待的新功能可促進 [Adobe Analytics 與 CJA 之間的對等關係](https://docs.adobe.com/content/help/zh-Hant/analytics-platform/using/cja-overview/cja-aa.html)。 |
| 歷程 IQ：跨頻道分析 | 2020 年 11 月 22 日 | 歷程 IQ：跨頻道分析讓客戶得以將 Adobe Experience Platform 資料湖的 Adobe Analytics (或其他) 事件資料集，從一個 ID 命名空間重新輸入至另一個 ID 命名空間。這通常代表將事件資料集從 Cookie 型 ID 重新輸入為人員型 ID。如此一來，重新輸入的資料集可以與 CJA 連線中的其他人員型資料結合，從而在 Analysis Workspace 中進行跨裝置/跨管道分析。 |

### [!UICONTROL Media Analytics] 新功能{#media-aa}

| 功能 | [全面發佈](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ---------- |
| [!UICONTROL 工作區]的[!UICONTROL 「媒體同時檢閱者」]面板 | 2020 年 9 月 17 日 | [!UICONTROL 「媒體同時檢閱者」]面板可供您掌握何時最多人同時觀看媒體，以及趨勢反轉的時間。這項功能提供內容品質和檢視者互動的重要分析，有助於疑難排解或依數量/規模完成規劃。[深入了解...](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Adobe Analytics 修正項目 {#aa-fixes}

* 修正當量度具有配置模式時，涉及分類的劃分無法運作的問題。這適用於報表套裝移轉至最新分類架構的情況。(AN-230364)
* 修正將值貼入容器後區段 UI 中斷的問題。(AN-233998)
* 修正[!UICONTROL 「資料摘要」]工作記錄遺失某些每小時資料的問題。(AN-231776)
* 修正複製計算量度時發生的問題。這會導致「您沒有存取此量度的權限」錯誤訊息。(AN-238070)
* 修正無法對[!UICONTROL 「工作區」][!UICONTROL 「文字」]視覺效果設定正確對齊方式的問題。(AN-238188)

#### 其他 Adobe Analytics 修正項目

AN-224702、AN-232791、AN-233982、AN-234384、AN-235608、AN-236538、AN-236598、AN-236738、AN-237434、AN-237672、AN-237850、AN-237943、AN-238081、AN-238508、AN-238527、AN-238536、AN-238619

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 為所有傳入的 HTTPS 要求加上 HSTS 標題 | 2020 年 9 月 29 日 | 自 2020 年 9 月 29 日起，我們開始為所有使用 HTTPS 的傳入要求加上 HSTS 標題。這會指示瀏覽器/用戶端日後一律透過 HTTPS 提出要求，以符合安全性最佳實務。目前我們還不會針對使用 HTTP 的傳入要求強制執行此規範。 |
| 變更了 Experience Cloud ID 服務 Cookie 設定 | 2020 年 9 月 22 日 | 一項針對 Chrome 80 版本隱私權設定的更新影響 Adobe Analytics 追蹤部分檢視 Google AMP 頁面之使用者的能力。具體來說，這項更新會防止跨網域追蹤檢視 Google 託管 AMP 頁面的使用者。如此可能導致不重複訪客的數量增加。此修正可讓使用者透過變更 ECID Cookie 設定來解決此問題。<br>目前，Analytics 的 Experience Cloud ID (ECID) 服務 Cookie 設定為 `SameSite = Lax`，而此設定在 Chrome 80 版本之前皆允許進行跨網域追蹤。但如今情況有變。使用者可透過這項變更將 ECID Cookie 的 SameSite 設定更新為 `None`。<br>請注意，這雖然會允許在更多情況下共用 Analytics Cookie，不過 Analytics Cookie 本身並不包含敏感資料。此外，選擇這項設定時，Cookie 必須設定為 `Secure`，才能僅透過 HTTPS 連線傳送資料。若想進行此一變更，請由支援的使用者透過客戶服務建立票證。 |
| 從 `omniture.com` 移轉至 `adobe.com` 網域 | 2020 年 8 月 21 日 | 2020 年 8 月 13 日，Adobe Analytics 將前端架構從 `omniture.com|http://omniture.com/` 移轉至 `adobe.com|http://adobe.com/` 網域。此變更應可紓解 2020 年 5 月 28 日初次統一產品網域後發生的第三方 Cookie 問題。更新後，瀏覽器可能會提示使用者將 `.adobe.com|http://an.adobe.com/` 或 `experience.adobe.com|http://experience.adobe.com/` 等新網域加入信任清單。 |
| 更新 Ad Hoc Analysis Java 8 相容性 | 2020 年 8 月 21 日 | Ad Hoc Analysis 目前與 Java 8 1.8.0_261 以後的版本不相容。為確保您在[產品生命週期](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)結束前能順利存取此工具，建議您持續使用 1.8.0_261 之前的 Java 8 版本。 |
| Adobe Data Connectors 終止服務 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 的舊技術已無法使用或不再支援。[Adobe Exchange 合作夥伴計畫已推出一項新標準](https://partners.adobe.com/tw/exchangeprogram/experiencecloud)，任何希望能繼續使用服務及取得支援的整合項目，都應採用此標準。確切日期仍未決定，但預計未來 12 至 18 個月內 (2021 年中至 2021 年底) 將會正式終止服務。[深入了解...](https://docs.adobe.com/content/help/zh-Hant/analytics/import/dataconnectors/data-connectors-eol.html) |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意於 2021 年 3 月 1 日終止 Ad Hoc Analysis 服務。如需詳細資訊，請造訪[探索工作區](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### AppMeasurement {#appm}

如需 AppMeasurement 發行的最新消息，請參閱[適用於 JavaScript 的 AppMeasurement 發行說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。

### Analytics 課程與教學課程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 的最新課程、教學課程和文章。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 8 日 | [自由格式表格：分析的基礎](https://video.tv.adobe.com/v/41766?captions=chi_hant) | 影片 | 了解須知事項，以及您展開本課程後將學到的內容。 |
| 2020 年 10 月 5 日 | [在 Analysis Workspace 中使用參與率量度](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/using-participation-metrics-in-analysis-workspace.html) | 影片 | 在 [!UICONTROL Analysis Workspace] 中隨時使用這個簡單的秘訣取得任何參與率量度。 |
| 2020 年 10 月 5 日 | [在 Analysis Workspace 中自動建置自由格式表格](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/auto-build-freeform-tables-in-analysis-workspace.html) | 影片 | 將元件直接拖放至空白專案、面板或自由格式表格中，系統就會自動以建議的格式為您建立表格。 |
| 2020 年 10 月 5 日 | [在自由格式表格中使用量度](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/working-with-metrics-in-a-freeform-table.html) | 影片 | 了解您可以在 [!UICONTROL Analysis Workspace] 的[!UICONTROL 「自由格式表格」]中使用量度的各種方式。 |
| 2020 年 9 月 21 日 | [Journey AI - 預測性傳送時間最佳化](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/communication-channels/email/journey-ai/predictive-send-time-optimization.html) | 影片 | 了解在 Adobe Campaign 和 Journey AI 模型之間同步資料所需的工作流程。了解如何在個別設定檔層級檢視傳送時間分數，以及如何使用傳送時間公式執行電子郵件傳遞。 |

### Analytics 說明資源

* [Adobe Analytics 教學課程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 產品文件](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)

## ![圖示](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 的新功能、修正項目、說明文件和教學課程。

發行日期：**2020 年 10 月 8 日**&#x200B;當天結束

### Audience Manager 的新功能、增強功能和修正 {#aam-features}

| 功能 | 新增或更新日期 | 說明 |
|----|----|----|
| [預測對象](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) | 2020 年 10 月 21 日 | <ul><li>**預測對象模型複製**：您現在可以複製現有模型，並根據需求變更設定。如需詳細資訊，請參閱[複製和編輯預測對象模型](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences-start.html#clone-predictive-audiences)。</li><li>**預測對象批次分類**：除了即時以不同人物誌分類訪客外，「預測對象」現在還支援批次分類，讓您分類已開始使用的使用者並啟用至批次目的地。</li></ul> |
| [重疊報表](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/reporting/interactive-and-overlap-reports/dynamic-reports.html) | 2020 年 10 月 23 日 | 我們已更新用於計算「重疊報表」([特徵對特徵](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/reporting/interactive-and-overlap-reports/trait-trait-overlap-report.html)、[區段對特徵](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/reporting/interactive-and-overlap-reports/segment-trait-overlap-report.html)、[區段對區段](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/reporting/interactive-and-overlap-reports/segment-segment-overlap-report.html)) 的方法。「重疊報表」計算現在是以報表唯一值和 MinHash 簽名 (而非 [1/54 資料抽樣](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/reporting/report-sampling.html#data-sampling-ratio)) 為基礎。 |

### 修正和改良 {#aam-fixes-and-improvements}

* 修正「預測對象」功能中，即使沒有區段對應至模型，部分使用者仍無法刪除任何模型的問題。(AAM-55881)
* 部分使用者無法刪除當作已刪除預測對象模型基線的特徵或區段，此問題現已修正。(AAM-56476)
* 我們持續改善介面的協助工具。(AAM-53215)

### Audience Manager 課程與教學課程 {#tutorials-aam}

針對 Audience Manager 發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 28 日 | [了解特徵圖中的數據](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/understanding-numbers-in-the-trait-graph.html?lang=zh-Hant#build-and-manage-audiences) | 影片 | 在特徵資訊畫面中取得相關秘訣，以利了解報告中的各項特徵數據。 |
| 2020 年 10 月 23 日 | [以 Analytics 資料建立特徵的事前規劃](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/planning-trait-creation-from-analytics-data.html?lang=zh-Hant#build-and-manage-audiences) | 影片 | 了解幾項秘訣與技巧，以協助您在 Audience Manager 的特徵中順利使用 Adobe Analytics 資料。 |
| 2020 年 10 月 23 日 | [建立特徵時選擇資料來源](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/choosing-a-data-source-when-creating-traits.html?lang=zh-Hant#build-and-manage-audiences) | 影片 | 建立特徵時，「資料來源」欄位是必填的重要欄位之一。取得秘訣，為規則型特徵和已登錄特徵選擇正確資料來源。 |
| 2020 年 9 月 14 日 | [使用程式碼檢視建立及編輯特徵](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-code-view-to-create-and-edit-traits.html?lang=zh-Hant#build-and-manage-audiences) | 影片 | 了解如何使用程式碼檢視來建立新特徵或編輯現有的特徵。設定特徵運算式時，程式碼檢視是除了運算式產生器以外的替代選項。 |
| 2020 年 10 月 10 日 | [了解預測對象](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | 影片 | 此影片中，我們會說明何謂 Audience Manager 預測對象、詳細解說其運作方式，並提供使用案例。 |

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

AEM 本月未更新。以下是從上個月開始提供的內容 (新課程和教學課程除外)。

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

>[!NOTE]
>
>Adobe 建議時常瀏覽 [Experience Manager 版本更新和藍圖](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)，以隨時掌握最新的發行資訊。

### 產品發行

* **AEM as a Cloud Service**

   AEM as a Cloud Service 新增了哪些功能？

   * **Adobe Experience Manager Sites as a Cloud Service**
      * 單頁應用程式 (SPA) 編輯器 Javascript SDK 現已為[開放原始碼](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/implementing/headless/spa/reference-materials.html)。
   * **Adobe Experience Manager Assets as a Cloud Service**

      * 使用資產微服務產生的轉譯支援浮水印影像檔。此類檔案可設定為「處理設定檔」，並使用 PNG 檔案作為浮水印。請參閱[為您的資產加上浮水印](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/assets/manage/watermark-assets.html)。
      * Dynamic Media 中的增強功能：
         * 選擇性發佈 - 現在，行銷團隊可以存取同步到 Dynamic Media 的 [!UICONTROL Dynamic Media] 智慧型裁切影像和動態轉譯，以便建立促銷文宣，而完全無須將這些資產發佈至 Dynamic Media 以進行全域傳送。Experience Manager 和 [!UICONTROL Dynamic Media] 發佈是分離的，可個別執行以達成此目的。請參閱[選擇性發佈](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/assets/dynamicmedia/selective-publishing.html)。
         * 密碼重設 - 現在，管理員可以重設在佈建時收到的 [!UICONTROL Dynamic Media] Cloud Service 密碼。重設可在 Experience Manager 使用者介面中完成，而無須使用 [!UICONTROL Dynamic Media] 傳統桌面應用程式。請參閱[變更 Dynamic Media 的密碼](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#change-dm-password)。
      * 若要了解下列增強功能，請參閱[品牌入口網站的新功能。](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/introduction/whats-new.html)
         * 透過 Adobe Document Cloud 檢視 SDK 整合強化 PDF 預覽。
         * 按一下即可下載的功能。
         * 下載體驗有新的管理設定。
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * CIF 核心元件 v1.3.0 已發行。如需詳細資訊，請參閱 [CIF 核心元件](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.3.0) 。
      * 現已提供產品和類別範本的產品/類別預覽功能。此功能可讓 AEM 中的商業使用者/行銷人員檢視具有真實資料的產品/類別範本。
      * 產品和類別新增了屬性頁面，可讓商業使用者檢視與產品 SKU/類別 ID 相關聯的詳細資料。
      * 「產品控制台」新增了排序功能，可依名稱或價格屬性排序產品/類別。
      * [!UICONTROL 產品控制台]新增了產品搜尋功能。
   * **Cloud Manager**

      * [!UICONTROL 內容稽核]已重新標示為[!UICONTROL 體驗稽核]。
      * 建置程序已分成三個不同的 Maven 命令。
      * Git 存放庫複製失敗時，最多將重新嘗試三次。
   * **Cloud Readiness Analyzer**

      * Cloud Readiness Analyzer (CRA) 有一個啟動狀態控制台，會顯示一個明確的&#x200B;**[!UICONTROL 產生報表]**&#x200B;按鈕供使用者點選，以執行 CRA。
      * CRA UI 在執行時會顯示進度。它會顯示分析中的項目，以及在執行期間發現的結果。
      * CRA 報表會以表格形式顯示結果的摘要和數目，並依據結果類型和重要性層級加以整理。按一下某個結果的數目，就會自動捲動至該結果在報表中的位置。
   * **內容轉移工具**

      * 內容轉移工具 (CTT) 支援 Azure Blob Store 資料存放區。
      * CTT 使用者介面具有自動重新載入功能，每 30 秒會重新載入一次概觀頁面。
      * CTT 使用者介面新增了按鈕，可讓您輕鬆擷取存取權杖。
      * 為 *URL* 和&#x200B;*移轉集名稱*&#x200B;新增描述性名稱。
   * **程式碼重構工具**

      * AIO-CLI 外掛程式支援 Repository Modernizer，可讓使用者透過外掛程式執行工具。如需詳細資訊，請參閱 [Git 資源：aio-cli-plugin-aem-cloud-service-migration](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration)。
      * Repository Modernizer 公用程式可用來將現有的專案套件重新建構為與針對 AEM as a Cloud Service 定義的專案結構相容的套件。如需詳細資訊，請參閱 [Git 資源：Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer)。







請參閱 [AEM as a Cloud Service 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)。

### 自助資源

**[!DNL Experience Manager]Sites**

RTF 編輯器文件已更新，其中列出所有 [RTE 中連結的支援通訊協定](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/administering/operations/configure-rich-text-editor-plug-ins.html#linkstyles)。

**[!DNL Experience Manager]Assets**

* 已推出適用於所有使用者的 [AEM Assets 存取方式](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/assets/accessibility.html)全新說明內容。

* 資產選擇器 (資產選擇器) 新增了 **[Viewmode 參數](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/using/search-assets.html#assetpicker)**，用以在搜尋模式中開啟資產選擇器。若要在搜尋模式中開啟資產選擇器並搭配使用 `assettype` 和 `mimetype`，使用者必須在 URL `viewmode=search` 中的結尾處加上 `https://[aem-server]:[port]/aem/assetpicker.html` 參數。例如：`https://[aem-server]:[port]/aem/assetpicker.html?viewmode=search&assettype=images`。

* 在[刪除私人資料夾](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/managing/private-folder.html#delete-private-folder)時，會刪除與私人資料夾相關聯的使用者群組，而現有的備援、未使用和自動產生的使用者群組，則可以使用 JMX 中的清除方法從存放庫中清除。

* 桌面應用程式 2.0.3.2 版已修正 [Service Pack 6.5.5.0](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/release-notes/service-pack/previous-hotfixes-featurepacks.html#assets-6550) 的桌面應用程式登入問題。

* 如果使用者修改了 [Apache Jackrabbit Oak TokenConfiguration](https://helpx.adobe.com/tw/experience-manager/kb/How-to-set-token-session-expiration-AEM.html)，而將逾時設定設為少於資產上傳所花費的時間，則使用者可能會遇到工作階段逾時的狀況。因此，使用者必須變更 `chunkUploadMinFileSize` 和 `chunksize`，讓每個區塊要求都會重新整理工作階段。如需詳細資訊，請參閱[上傳資產](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/managing/managing-assets-touch-ui.html#uploading-assets)。

* 除了會開啟[!UICONTROL 「移動資產」]精靈的[!UICONTROL 移動 (M)] 作業以外，資產也可以[使用拖曳作業移入同層級資料夾](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/managing/managing-assets-touch-ui.html#moving-or-renaming-assets)中。

* 如需 Assets Insights，請使用 [Adobe Launch](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/advanced/asset-insights-launch-tutorial.html)。[DTM 整合](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/managing/touch-ui-using-dtm-for-asset-insights.html)在文件中列為淘汰的方法。

更新日期：**2020 年 10 月 28 日**

* **品牌入口網站增強功能**：下列新功能和更多內容均可從 [!DNL Brand Portal] 取得：

   * [改良版下載體驗](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/download/brand-portal-download-assets.html)可簡化及加速下載程序。管理員可設定額外的下載設定，以提供符合使用者和企業需求的體驗。
   * 現在您可以從任何頁面按一下，導覽至[!UICONTROL 「檔案」]、[「集合」](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/share/brand-portal-share-collection.html)和[!UICONTROL 「共用連結」]。
   * 使用者現在可以[選擇並下載特定轉譯](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/download/brand-portal-download-assets.html#download-assets-from-asset-details-page)。您可以在 Asset 詳細資訊頁面的[!UICONTROL 「轉譯」]面板中使用新的轉譯下載選項。
   * 使用者作業逾時 15 分鐘可確保所有同時使用者獲得更理想的體驗。

### [!DNL Experience Manager] 表單

下列 6.5.6.0 版所含功能的說明文件已上線。您現在可以：

* 在用戶端執行最適化表單預先填入資料動作。[在用戶端預先填入](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/forms/adaptive-forms-advanced-authoring/prepopulate-adaptive-form-fields.html)可大幅降低合併資料和演算最適化表單所需的時間。
* 在表單資料模型中[對 RESTful 和 SOAP Web 服務使用憑證式相互驗證](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/forms/form-data-model/configure-data-sources.html#mutual-authentication)。
* 納入[地區設定資訊作為 URL 選擇器](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/forms/manage-administer-aem-forms/supporting-new-language-localization.html)。使用 URL 選擇器有助於在 Dispatcher 上[快取轉譯的最適化表單](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/forms/install-aem-forms/configure-aem-forms/configure-adaptive-forms-cache.html)。
* [將多個檔案附加到最適化表單的「檔案附件」元件](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/forms/getting-started/introduction-forms-authoring.html)。

下列針對「自動化表單轉換」服務所發行功能的文件已上線。您現在可以：

* 將[已啟用 Adobe Sign 的 PDF 表單](https://git.corp.adobe.com/AdobeDocs/aem-forms-automated-conversion-service.en/blob/master/help/frequently-asked-questions.md)與此服務搭配使用。如果來源 PDF 表單有 Adobe Sign 文字標籤，服務會在轉換期間保留所有 Adobe Sign 相關資訊，並且將來源 PDF 中顯示的簽署者資訊與對應的最適化表單欄位建立關聯。

* 此服務現在支援[將彩色 PDF 表單轉換為最適化表單](https://docs.adobe.com/content/help/zh-Hant/aem-forms-automated-conversion-service/using/release-notes.html)。

### [!DNL Adobe Experience Manager] 版本更新和藍圖文件

針對 Adobe Experience Manager 發行藍圖、版本更新和附加元件資訊，發佈一站式文件解決方案。將多處 AEM 空間提供的許多相關文章整合到單一位置，以方便存取。包含下列重要文章：

* [AEM 發行藍圖](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/update-releases-roadmap.html)：列出即將發行的 AEM as a Cloud Service 版本，以及支援的內部部署和受管服務 AEM 版本。
* [AEM 版本更新](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/aem-releases-updates.html)：列出 AEM as a Cloud Service 最新發行版本，以及支援的內部部署和受管服務 AEM 版本，並將您導向這些發行版本的文件。
* [AEM Forms 版本](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html)：列出所有發行的 Forms 附加元件套件的軟體發佈套件連結。

此外，其中還有其他重要文章，例如 [AEM 更新發行工具定義](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/update-release-vehicle-definitions.html)和[最近的 AEM 文件更新](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html)。

### [!DNL Adobe Experience Manager] 桌面應用程式

* 在登出後重新登入桌面應用程式或首次登入的使用者，應以 `https://[aem-server-url]:[port]/` 格式提供其 [!DNL Experience Manager] 伺服器 URL，然後選取[!UICONTROL 「連線」]選項，以避免出現「應用程式發生未知錯誤」錯誤。如需詳細資訊，請參閱[使用 Adobe Experience Manager 桌面應用程式](https://docs.adobe.com/content/help/zh-Hant/experience-manager-desktop-app/using/using.html)。

### 社群

* **發表提交 Experience Manager 功能要求的新程序**

   您想看看 Experience Manager 藍圖中新增的功能嗎？Adobe 發表了 *FeatureBit* - 此專案旨在改善客戶和合作夥伴向 Experience Manager 產品團隊要求功能增強 (稱為 RFE) 的方式。您可以透過 [Experience League AEM 社群](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-the-new-process-to-submit-experience-manager-feature/td-p/380425)了解詳細資訊。

* **Experience League 的最新 AEM 內容**

   此為 Adobe 提供之數位體驗技術內容的官方來源。若需參閱完整清單，請前往[此處](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)。

### 最新 Experience Manager 課程與教學課程 

更新日期：**2020 年 10 月 21 日**

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 11 月 2 日 | [載入及觸發 Target 呼叫](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/load-and-fire-target.html) | 影片 | 了解如何使用 Launch 規則將參數載入、傳遞至頁面請求，以及從您的網站頁面觸發 Target 呼叫。系統會使用 Adobe Client Data Layer 來擷取頁面資訊並以參數形式傳遞，此資料層可讓您收集和儲存訪客的網頁體驗相關資料，並且讓此資料易於存取。 |
| 2020 年 10 月 28 日 | [影片智慧標籤](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/video-smart-tags.html) | 影片 | Experience Manager Assets 利用 Adobe Sensei 提供的技術，靈活地使用可描述影片中關鍵元素的關鍵字來標記影片資產，讓 AEM 使用者能使用關鍵字搜尋功能輕鬆找到影片。 |
| 2020 年 10 月 27 日 | [AEM Document Security Extension for Microsoft Office 簡介](https://docs.adobe.com/content/help/en/experience-manager-document-security/using/document-security-extension-microsoft-office.html) | 文章 | Adobe Experience Manager Document Security Extension for Microsoft Office 可確保只有您授權的人員才能使用內含您智慧財產權的 Word、Excel 和 PowerPoint 檔案。您可以使用 Document Security Extension for Microsoft Office，將預先定義的機密設定套用至您的檔案。 |
| 2020 年 10 月 7 日 | [在 Adobe Analytics 中檢視頁面量度](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/analytics/create-analytics-workspace.html) | 文章 | 了解如何將從 Adobe Experience Manager Site 擷取的資料對應至 Adobe Analytics 報表套裝中的量度和維度。 |
| 2020 年 10 月 8 日 | [個人化完整網頁體驗](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/personalization-web-page.html) | 影片 | 了解如何建立活動，使用 Adobe Target 將 AEM 上託管的網站頁面重新導向至新頁面。 |
| 2020 年 10 月 8 日 | [使用可視化體驗撰寫器進行個人化](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/personalization-using-vec.html) | 影片 | 了解如何使用可視化體驗撰寫器 (VEC) 建立 A/B 測試 Target 活動。 |
| 2020 年 9 月 14 日 | [使用體驗片段選件建立 Target 活動](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/create-target-activity.html) | 影片 | 了解如何使用 AEM 體驗片段選件建立和測試 Adobe Target 活動。 |
| 2020 年 10 月 8 日 | [將體驗片段匯出至 Adobe Target](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/export-experience-fragment-target.html) | 影片 | 了解如何將 AEM 體驗片段匯出為 Adobe Target 選件。 |
| 2020 年 10 月 5 日 | [使用表單資料模型變數在資料庫中插入列](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/variables-aem-workflow/form-data-model.html) | 影片 | 表單資料模型類型的變數通常用來在表單資料模型的基礎資料來源中插入列。此影片說明使用 AEM 工作流程在資料庫中插入列所需的步驟。 |
| 2020 年 9 月 28 日 | [使用簡訊的雙重因素驗證](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/some-useful-integrations/two-factor-authentication.html) | 文章 | 在最適化表單中使用簡訊執行 OTP 驗證。 |
| 2020 年 9 月 28 日 | [資產計算課程](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.asset.compute) | 課程 | 本課程探討如何延伸 AEM as a Cloud Service 資產計算微服務！您現在應該能夠設定、開發、測試、除錯和部署自訂「資產計算」背景工作，以供 AEM as a Cloud Service 作者服務使用。 |
| 2020 年 9 月 23 日 | [使用 Adobe Analytics 追蹤已點按的元件](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/analytics/track-clicked-component.html) | 文章 | 使用事件導向的 Adobe Client Data Layer，在 Adobe Experience Manager 中收集網站上頁面和使用者互動的相關資料。了解如何使用 Experience Platform Launch 中的規則來監聽這些事件，並且將資料傳送至 Adobe Analytics 報表套裝。 |
| 2020 年 9 月 25 日 | [整合資產計算背景工作與 AEM 處理設定檔](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/deploy/processing-profiles.html) | 影片 | AEM as a Cloud Service 可透過 AEM Assets 處理設定檔與部署至 Adobe I/O Runtime 的資產計算背景工作整合。處理設定檔設定於「作者」服務中，以使用自訂背景工作處理特定資產，以及將背景工作產生的檔案儲存為資產轉譯。 |
| 2020 年 9 月 25 日 | [部署至 Adobe I/O Runtime - 教學課程](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/deploy/runtime.html) | 影片 | 資產計算專案及其所包含的背景工作必須部署至 Adobe I/O Runtime，才可供 AEM as a Cloud Service 使用。 |
| 2020 年 9 月 25 日 | [對資產計算背景工作進行除錯](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/asset-compute/test-debug/debug.html) | 文章 | 資產計算背景工作可透過數種方式進行除錯，包括簡單的除錯記錄陳述式、附加的 VS Code (作為遠端除錯工具)，乃至於從起始自 AEM as a Cloud Service 的 Adobe I/O Runtime 中提取啟用的記錄。 |
| 2020 年 9 月 25 日 | [使用資產計算開發工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/development-tool.html) | 文章 | 資產計算開發工具是本機 Web 工具，可讓開發人員在 AEM SDK 外部的本機位置，對 Adobe I/O Runtime 中的資產計算資源設定並執行資產電腦背景工作。 |
| 2020 年 9 月 27 日 | [開發資產計算背景工作](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/worker.html) | 文章 | 資產計算背景工作是資產計算應用程式的核心，因為其自訂功能可用來執行或協調對資產執行的工作，以建立新的轉譯。 |
| 2020 年 9 月 25 日 | [設定 manifest.yml](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/manifest.html) | 文章 | 資產計算專案的 manifest.yml 說明此應用程式中所有要部署的背景工作。 |
| 2020 年 9 月 14 日 | [設定環境變數](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/environment-variables.html) | 影片 | 環境變數會保留在「.env」檔案中以供本機開發使用，並用來提供本機開發所需的 Adobe I/O 憑證和雲端儲存空間憑證。 |
| 2020 年 9 月 14 日 | [建立資產計算專案](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/project.html) | 文章 | 資產計算應用程式是使用 Adobe I/O CLI 產生的 Node.js 專案，須符合特定結構，以便部署至 Adobe I/O Runtime 並且與 AEM as a Cloud Service 整合。 |
| 2020 年 9 月 14 日 | [設定環境變數](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/environment-variables.html) | 文章 | 環境變數會保留在「.env」檔案中供本機開發使用，並用來提供本機開發所需的 Adobe I/O 憑證和雲端儲存空間憑證 |
| 2020 年 9 月 14 日 | [建立資產計算專案](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/project.html) | 影片 | 資產計算應用程式是使用 Adobe I/O CLI 產生的 Node.js 專案，須符合特定結構，以便部署至 Adobe I/O Runtime 並且與 AEM as a Cloud Service 整合。 |
| 2020 年 9 月 14 日 | [設定 Adobe I/O Project Firefly](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/firefly.html) | 教學課程 | 資產計算應用程式是特別定義的 Adobe Project Firefly 應用程式，因此必須在 Adobe Developer Console 中存取 Adobe Project Firefly，才能加以設定和部署。 |
| 2020 年 9 月 25 日 | [設定本機開發環境](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/development-environment.html) | 文章 | 開發資產計算背景工作 (屬於 Node.js JavaScript 應用程式) 需要與傳統 AEM 開發不同的特定開發工具，包括 Node.js 和各種 npm 模組，乃至於 Docker Desktop 和 Microsoft Visual Studio Code。 |
| 2020 年 9 月 25 日 | [設定帳戶和服務](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/accounts-and-services.html) | 文章 | 開發資產計算背景工作時需要存取帳戶和服務，包括 AEM as a Cloud Service、Adobe Project Firefly 以及 Microsoft 或 Amazon 提供的雲端儲存空間。 |
| 2020 年 9 月 30 日 | [探索 Adobe Client Data Layer](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | 文章 | 探索事件導向 Adobe Client Data Layer 的功能，及其與 AEM Sites 核心元件的整合。了解如何監聽事件、取得目前狀態及修改資料層。 |
| 2020 年 9 月 30 日 | [Adobe Client Data Layer 簡介](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | 影片 | 了解事件導向的 Adobe Client Data Layer 如何公開 AEM Sites 核心元件中的資料。使用 Adobe Client Data Layer 時，Experience Platform Launch 之類的標記管理解決方案可將網站資料傳輸至 Analytics 和 Target 等應用程式。 |
| 2020 年 10 月 8 日 | [將 Target 擴充功能新增至 Launch 屬性](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/add-target-launch-extension.html) | 影片 | 了解如何使用 Launch 規則將參數載入、傳遞至頁面請求，以及從您的網站頁面觸發 Target 呼叫。系統會使用 Adobe Client Data Layer 來擷取頁面資訊並以參數形式傳遞，此資料層可讓您收集和儲存訪客的網頁體驗相關資料，並且讓此資料易於存取。 |
| 2020 年 10 月 7 日 | [建立 Adobe Target 雲端服務帳戶](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/setup-aem-target-cloud-service.html) | 影片 | 了解如何使用 Cloud Service 和 Adobe IMS 驗證整合 Adobe Experience Manager as a Cloud Service 與 Adobe Target。 |
| 2020 年 10 月 2 日 | [AEM 和 Adobe Target 概觀](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/target/overview.html) | 影片 | AEM 和 Target 兩者都是強大的解決方案，且功能大致重疊。客戶有時不易了解搭配使用這兩種產品來提供個人化體驗的方式與時機。為了向每位一般使用者提供最佳化的體驗，組織內不同的團隊應密切合作，並定義各自的職責。 |
| 2020 年 10 月 2 日 | [整合 AEM Forms 與 Adobe Sign](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.2.forms) | 課程 | Adobe Sign 和 AEM Forms 可搭配運作，使複雜的交易自動化，並加入安全、合法的電子簽名，以提供順暢的數位體驗。 |
| 2020 年 10 月 6 日 | [針對列印管道建立互動式文件](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.5.forms) | 課程 | 「互動式通訊」可集中處理及管理安全、個人化與互動式通信的建立、集合與傳遞，例如商業信函、文件、對帳單、利益通知、行銷郵件、帳單和歡迎套件。本課程將重點介紹如何建立構成互動式通訊文件的各種元件。 |
| 2020 年 10 月 10 日 | [開發人員專用 AEM SPA Editor 快速入門](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.spaeditor) | 課程 | 了解如何使用 AEM SPA Editor 建立可在 AEM 中編寫的高效能單頁應用程式 (SPA)。從建立新的 SPA Editor 專案到建立自訂元件等，各項主要開發作業都在本課程涵蓋範圍內。另有提供等效的 Angular 和 React 架構課程；預計大多數開發人員會選擇使用單一架構。 |
| 2020 年 10 月 7 日 | [資產計算的擴充性](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/overview.html) | 文章 | 本教學課程將逐步說明如何建立 AEM as a Cloud Service 的自訂資產微服務背景工作。 |
| 2020 年 10 月 6 日 | [建立第一個最適化表單](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.4.forms) | 課程 | AEM Forms 可讓您建立吸引人、回應式、動態且最適化的表單。本課程從建立自訂最適化表單範本開始，並逐步帶您了解使用各種表單元件建立最適化表單的過程。 |
| 2020 年 10 月 21 日 | [本機 Dispatcher 工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | 文章 | AEM 的 Dispatcher 是 Apache HTTP Web 伺服器模組，可在 CDN 和 AEM Publish 層級之間提供安全性與效能層。了解如何將 Dispatcher 設定為本機開發環境的一部分。 |
| 2020 年 10 月 14 日 | [開發人員專用 AEM Sites 快速入門](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.2.guided) | 課程 | 本課程更新 Experience League 上的[現有課程](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2019.2.guided)。 |
| 2020 年 10 月 7 日 | [AEM 專案結構](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | 影片 | 本文概述讓 Adobe Experience Manager Maven 專案與 AEM as a Cloud Service 相容所需的變更，確保專案遵守可變和不可變內容的分割，建立相依性以實現不衝突、確定性的部署，並封裝成可部署結構。 |

### Experience Manager 發行資訊

所有 Experience Manager 的發行說明都會保留在以下頁面：

* [Experience Manager 版本更新和藍圖](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [AEM as a Cloud Service 發行資訊](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/home.html)
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

#### 控制面板

* 使用 CNAME 設定子網域 - [深入了解](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html#use-cnames)

* 資料庫監控增強功能 - [深入了解](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/performance-monitoring/database-monitoring.html)

### 最新 Campaign 課程與教學課程

過去一個月內發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 解決方法 | 說明 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 11 月 2 日 | [控制面板 - 產生 SSH 金鑰 - 功能影片](https://docs.adobe.com/content/help/zh-Hant/campaign-classic-learn/control-panel/sftp-management/generate-ssh-key.html) | Campaign Classic | 了解如何透過終端產生 SSH 金鑰，以及如何在控制面板中儲存公開版本的金鑰。 |
| 2020 年 11 月 2 日 | [控制面板 - 連線至 SFTP 伺服器 - 功能影片](https://docs.adobe.com/content/help/zh-Hant/campaign-classic-learn/control-panel/sftp-management/connect-to-sftp-server.html) | Campaign Classic | 了解如何透過用戶端 SFTP 應用程式，使用您儲存在控制面板的金鑰，連線至您的 SFTP 伺服器。 |
| 2020 年 10 月 20 日 | [控制面板 - 控制面板快速入門 - 文章](https://docs.adobe.com/content/help/zh-Hant/campaign-classic-learn/control-panel/getting-started-with-the-control-panel.html) | Campaign Classic | 本文說明如何存取控制面板，以及使用控制面板的先決條件。 |
| 2020 年 10 月 20 日 | [控制面板 - 控制面板快速入門 - 文章](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/control-panel/getting-started-with-the-control-panel.html) | Campaign Standard | 本文說明如何存取控制面板，以及使用控制面板的先決條件。 |
| 2020 年 10 月 19 日 | [控制面板 - 新增 IP 範圍至允許清單](https://docs.adobe.com/content/help/zh-Hant/campaign-classic-learn/control-panel/sftp-management/adding-ip-range-to-allow-list.html) | Campaign Classic | 了解如何在控制面板中新增 IP 位址範圍至允許清單。 |
| 2020 年 10 月 19 日 | [控制面板 - 新增 IP 範圍至允許清單](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/control-panel/sftp-management/adding-ip-range-to-allow-list.html) | Campaign Standard | 了解如何在控制面板中新增 IP 位址範圍至允許清單。 |
| 2020 年 10 月 16 日 | [控制面板 - 使用 CNAME 委派子網域 (測試版) - 功能影片](https://docs.adobe.com/content/help/zh-Hant/campaign-classic-learn/control-panel/subdomains-and-certificates/delegating-subdomains-using-cname.html) | Campaign Classic | 了解如何使用「控制面板」中的 CNAME 來設定和提交子網域。 |
| 2020 年 10 月 16 日 | [控制面板 - 使用 CNAME 委派子網域 (測試版) - 功能影片](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/control-panel/subdomains-and-certificates/delegating-subdomains-using-cname.html) | Campaign Standard | 了解如何使用「控制面板」中的 CNAME 來設定和提交子網域。 |

### 說明資源

* Adobe Campaign Standard：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/campaign-standard-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/campaign-classic-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html)- [Campaign Standard](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html) 作法影片

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Adobe Advertising Cloud 發行說明。

* [Advertising Cloud DSP 新功能](#adcloud-dsp)
* [Advertising Cloud Search 新功能](#adcloud-search)

### [!DNL Advertising Cloud DSP] 中的新功能{#adcloud-dsp} 

更新日期：2020 年 10 月 28 日

| 功能 | 說明 |
| -----------| ---------- |
| 新增說明 | (10 月 28 日發行) 舊版說明已更換為更新頁面，您可以透過 DSP 主功能表的「說明」連結加以存取，也可以隨時從 [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) 存取 |
| Campaigns | (10 月 28 日發行) 先前的 Campaigns 測試版檢視現已成為 Campaigns 預設檢視，能提供更快速的深入分析、簡潔的工作流程和自訂檢視。 |
| 私人詳細目錄 | (10 月 15 日發行) 所有使用者現在都能使用新交易 ID 表單來設定及編輯交易 ID 詳細資訊，此表單是舊版[!UICONTROL 「智慧型廣告服務」]表單的簡化版本。若要設定新交易 ID 詳細資訊，請前往&#x200B;**[!UICONTROL 「詳細目錄 > 交易」]**，按一下&#x200B;**[!UICONTROL 「建立」]**，然後按一下&#x200B;**[!UICONTROL 「交易 ID 測試版」]**。 |
| 刊登版位預測 | (10 月 15 日發行) 若刊登版位具有從刊登版位層級調整的設計，其設定的[!UICONTROL 「預測」]區段現已加入新的[!UICONTROL 「預估上限」]區段，能顯示目前的鎖定目標設定有多少容量可用。 |

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search} 

發行日期：**2020 年 10 月 17 日**

| 功能 | 說明 |
| -----------| ---------- |
| 搜尋促銷活動 | 在[!UICONTROL 「帳戶」]檢視中，[!UICONTROL 「存取」]欄現在會指出 [!DNL Advertising Cloud Search] 何時無法登入已啟用的搜尋引擎帳戶。若要查看錯誤的成因，請將游標放在警告圖示上。 |
| [!UICONTROL 自訂警報] | 舊版[!UICONTROL 「警報測試版」]現在稱為[!UICONTROL 「自訂警報」]。 |
|  | 在自訂警報中，已簡化用來識別指定日期範圍的量度比起上一個期間的量度何時增加或減少的工作流程，並移至[!UICONTROL 「篩選器」]索引標籤。 |

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![圖示](/assets/target.png)[!DNL Target] {#target}

如需最新版本的資訊，請參閱 [[!DNL Target]  發行說明](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html)。

### 最新 Adobe Target 課程與教學課程

更新日期：**2020 年 11 月 2 日**

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 10 月 11 日 | [混合個人化部署模型](https://docs.adobe.com/content/help/en/target-learn/tutorials/implementation/hybrid-deployment.html) | 影片 | Adobe Target 提供獨特的混合部署模型，整合用戶端和伺服器端實作，實現個人化體驗。藉由此混合模型，技術人員以外的使用者能透過 WYSIWYG Visual Experience Composer 製作實驗或個人化活動，供伺服器端執行、傳送及轉譯體驗，以提供高效能的傳遞作業。 |

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

## ![圖示](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud 的發行資訊和說明資源。

### 最新 Adobe Sign 課程與教學課程

針對 Adobe Document Cloud 發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 9 月 29 日 | [Adobe Sign 快速導覽](https://docs.adobe.com/content/help/en/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/quick-tour.html) | 影片 | 在此影片中，我們將從首頁畫面開始快速導覽 Adobe Sign。 |

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=en)
* [Adobe Sign 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=en)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)
