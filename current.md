---
title: Adobe Experience Cloud 發行說明
description: Adobe Experience Cloud 發行說明
doc-type: release notes
last-update: October 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b3ba9bfac88074b9dd5838acd086bade5a43b734
workflow-type: tm+mt
source-wordcount: '6617'
ht-degree: 44%

---


# 提早存取- Adobe Experience Cloud發行說明- 2020年10月

![橫幅](/assets/experience-cloud-banner-3.png)

此頁面主要說明 [!DNL Adobe Experience Cloud] 的新功能、修正項目和重要注意事項。此外還有最新文件、訓練課程和教學課程影片，協助您充份運用 Experience Cloud。

>[!IMPORTANT]
>
>此頁面含有搶先版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>訂閱 [Adobe Priority Product Update](https://www.adobe.com/tw/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。

**發行日期：2020 年 10 月 8 日**

產品的發行日期可能不盡相同。請時常回訪以取得更新內容。

最近更新: **2020 年 10 月 2 日**

* [Adobe 系統狀態](#status)
* [Experience Cloud服務與管理](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) 和 [Customer Journey Analytics](#cust-journey) （2020年10月2日更新）
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Primetime]](https://docs.adobe.com/content/help/zh-Hant/primetime/release-notes/home.html)
* [Document Cloud](#doc-cloud)

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，尋找產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

>[!NOTE]
>
>說明檔案正在移轉至Experience League。 在10月期間，所有發行說明、文章、影片和教學課程都將從目前位置移至Experience League `docs.adobe.com` ，並可隨附於Experience League。 此舉可確保從單一位置提供所有學習、自助、啟用和社群內容：體驗聯盟。 發生此變更時，您不需執行任何動作，因為所有連結都會重新導向至新位置。 當切換開始時，我們會更新版本注意事項。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/tw/)。

未於9月更新。

如需最新發行資訊，請參閱 [Adobe 系統狀態 - 2020 年 5 月 21 日](https://docs.adobe.com/content/help/zh-Hant/release-notes/experience-cloud/previous/2020/05212020.html#status)。

## ![Icon](/assets/ec_appicon_24.png) Experience Cloud服務與管理 {#ecloud}

Experience Cloud服務 _和管理檔案先前稱為_ Experience Cloud核心服務 [，其中包括客戶屬性、觀眾程式庫(](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html) People service)啟動、使用者和產品管理，以及Experience Cloud Cookie。

未於9月更新。

如需 [最新發行資訊，請參閱Experience Cloud服務的](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/release-notes/release-notes.html) 「累計發行說明」。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

的發行說明 [!DNL Experience Platform]。

發行日期：**2020 年 9 月 9 日**

如需 [下列更新的相關資訊](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) ，請參閱Experience Platform發行說明：

* 資料控管
* 目的地
* 可觀性見解
* 隱私權服務
* 即時客戶個人檔案
* 區段服務
* 來源

### Experience Platform 和服務教學課程與其他課程

針對 Experience Platform 和服務所發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 14 月 9 日 | [歸因人工智慧的商業價值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/intelligent-services/business-value-of-attribution-ai.html) | 影片 | [!UICONTROL Attribution AI]( [!UICONTROL Intelligent Services])是多通道、演算法歸因服務，可計算客戶互動對特定結果的影響和增量影響。 使用 [!UICONTROL Attribution AI]，行銷人員可以透過瞭解客戶歷程各個階段中每個客戶互動的影響，來衡量和最佳化行銷和廣告支出。 |
| 2020 年 14 月 9 日 | [客戶人工智慧的商業價值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/intelligent-services/business-value-of-customer-ai.html) | 影片 | 此視訊顯示客戶 [!UICONTROL AI] 如何運用AI傾向豐富客戶個人檔案，並協助客戶細分和鎖定目標。 |
| 2020 年 14 月 9 日 | [平台和Magento的商業價值](https://docs.adobe.com/content/help/en/platform-learn/tutorials/experience-cloud/business-value-of-platform-and-magento.html) | 影片 | 此影片顯示，Adobe Experience Platform可與 [!DNL Magento] Commerce搭配使用，以建立單一客戶檢視，並在數位店面和跨通道聰明地個人化體驗。 |

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

不論客戶處於哪個歷程階段，Adobe Experience Platform 均可聰明地即時預測每個人的需求，以便大規模協調不同體驗管道的客戶歷程。

### 新產品版本

9月版本——請參 [閱歷程協調發行說明](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#september-release)。

### Journey Orchestration 的其他資源

[文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/zh-Hant/journey-orchestration-learn/tutorials/understanding-journey-orchestration.translate.html)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期: **2020 年 10 月 8 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Media Analytics 新功能](#media-aa)
* [Adobe Analytics 修正項目](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ------- |
| [!UICONTROL 工作區]:下載單一維度的5萬個項目 | 2020 年 9 月 17 日 | 您將能以自由格式表格，針對單一維度下載 50,000 個項目，並套用區段和篩選條件。這可讓您存取 Analysis Workspace 以外超過 400 列的資料。[更多詳情...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/download-send.html#download-items) |
| 工作區：改良[!UICONTROL 線條]視覺化 | 2020 年 9 月 17 日 | <ul><li>You can show or hide the X-axis and Y-axis of any [!UICONTROL Line] visualization. 當[!UICONTROL 線條]視覺化效果較為精簡時，這項功能可說相當實用。</li><li>您可以在任何[!UICONTROL 線條]視覺化效果上覆蓋最小值和最大值標籤，以迅速突顯量度的高低值。</li><li>您可以在任何[!UICONTROL 線條]視覺化效果上覆蓋不同的迴歸趨勢線，以便輕鬆查看資料趨勢。選項包括[!UICONTROL 線性]、[!UICONTROL 對數]、[!UICONTROL 指數]、[!UICONTROL 冪]和[!UICONTROL 二次方程式]。</li></ul> [更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/visualizations/line.html) |
| [!UICONTROL 工作區]:「效能幫助」頁 | 2020年10月22日 | 「分析工作區」效能說明頁面顯示影響專案效能的不同因素以及最佳化秘訣的連結。 [更多詳情](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| [!UICONTROL 工作區][!UICONTROL 線圖] 視覺化：移動平均趨勢線選項 | 2020年10月8日 | 「行」視覺化趨勢線設定已新增移動平均值。 移動平均值也稱為滾動平均值，它使用特定數量的資料點(由「期間」選擇確定  )、將其平均化，並將平均值用作行中的點。 [更多詳情](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/visualizations/line.html) |
| [!UICONTROL 資料修復 API] | 2020年10月8日 | 「資 [!UICONTROL 料修復] API」是從Analytics報表套裝刪除資料的工具。 10月發行包含刪除指定日期範圍之指定eVar、prop和Activity Map變數的能力。 未來將推出其他功能。 使用資料修復API會永久刪除現有的Adobe Analytics資料。 我們建議謹慎地執行修復，以最大限度地減少意外刪除。 存取資料修復API需要簽署合約——請洽詢您的帳戶團隊以取得詳細資訊。 [更多詳情](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/data-repair.md) |
| Analytics控制面板UI的增強功能 | 2020年10月23日 | 在工作區中建立行動記分卡時，記分卡的樣式現在與應用程式相符。 |

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ----- |
| [!UICONTROL 工作區]:下載單一維度的5萬個項目 | 2020 年 9 月 17 日 | 您將能以自由格式表格，針對單一維度下載 50,000 個項目，並套用區段和篩選條件。這可讓您存取 Analysis Workspace 以外超過 400 列的資料。[更多詳情...] |
| 工作區：改良[!UICONTROL 線條]視覺化 | 2020 年 9 月 17 日 | <ul><li>You can show or hide the X-axis and Y-axis of any [!UICONTROL Line] visualization. 當[!UICONTROL 線條]視覺化效果較為精簡時，這項功能可說相當實用。</li><li>您可以在任何[!UICONTROL 線條]視覺化效果上覆蓋最小值和最大值標籤，以迅速突顯量度的高低值。</li><li>您可以在任何[!UICONTROL 線條]視覺化效果上覆蓋不同的迴歸趨勢線，以便輕鬆查看資料趨勢。選項包括[!UICONTROL 線性]、[!UICONTROL 對數]、[!UICONTROL 指數]、[!UICONTROL 冪]和[!UICONTROL 二次方程式]。</li></ul> [更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics-platform/using/cja-workspace/visualizations/line.html) |
| 「分析工作區：效能幫助」頁 | 2020年10月22日 | 「分析工作區」效能說明頁面顯示影響專案效能的不同因素以及最佳化秘訣的連結。 [更多詳情](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/workspace-faq/optimizing-performance.html) |
| [!UICONTROL 線條視覺化] :移動平均趨勢線選項 | 2020年10月8日 | 「行」視覺化趨勢線設定已新增移動平均值。 移動平均值會計算指定前期的平均值，並將該平均值用作趨勢線資料點，然後移至下一期間。 [更多詳情](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/visualizations/line.html) |
| 移除回填限制 | 2020年10月19日 | 以前，建立連接時最多可以回填25億行。 我們移除回填限制，允許您回填最多13個月的資料，不論其大小。 |

### [!UICONTROL Media Analytics] 新功能{#media-aa}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| ----------- | ---------- | ---------- |
| [!UICONTROL 工作區]的[!UICONTROL 「媒體同時檢閱者」]面板 | 2020 年 9 月 17 日 | [!UICONTROL 「媒體同時檢閱者」]面板可供您掌握何時最多人同時觀看媒體，以及趨勢反轉的時間。這項功能提供內容品質和檢視者互動的重要分析，有助於疑難排解或依數量/規模完成規劃。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Adobe Analytics 修正項目 {#aa-fixes}

* 修正Experience Platform Launch中DFA Connector外掛程式程式碼傳回錯誤的問題。 (AN-214531)
* 修正當存取工作區專 [!UICONTROL 案時] ，造成錯誤的小報告中斷 [!UICONTROL 的問題] 。 (AN-230776)
* 修正在工作區中開啟警報連結並嘗試 [!UICONTROL 編輯專案] 時發生的問題。 (AN-230853)
* 修正某些元件頁面的使用者名稱中出現亂碼的GB18030字 [!UICONTROL 元] 。 (AN-233863)
* 修正Data Warehouse [!UICONTROL API的各種問題] 。 (AN-234424、AN-234557)
* 修正透過Experience Cloud登入 [!UICONTROL 時，Workspace] 未載入的問題。 (AN-235658)
* 修正分類檔案 [!UICONTROL 佇列] 的問題。 (AN-236043)
* [!UICONTROL 客戶歷程分析]:修正無法開啟資料檢視的問題。 (AN-236108)
* 修正Adobe提供的區段無法在計算量度產 [!UICONTROL 生器中使用] (AN-236835)的問題
* 修正非管理員VRS組織體驗的問題，以確保非管理員使用者僅能檢視下列內容：組織的元件、已建立的元件，以及已共用的元件。 (AN-236615、AN-236704)

#### 其他 Adobe Analytics 修正項目

-205046、AN-206847、AN-209003、AN-211746、AN-214104、AN-215367、AN-215484、AN-226209、AN-227413、AN-227485、AN-229347、AN-、AN-230574、AN-230708、AN-231689、AN-231949、AN-232102、AN-232752、AN-232995、AN-234123、AN-234175、AN-234658、AN-234694、AN-234835、AN-235506、AN-235509、AN-235612、AN-235921

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 為所有傳入的 HTTPS 要求加上 HSTS 標題 | 2020 年 9 月 29 日 | 自 2020 年 9 月 29 日起，我們開始為所有使用 HTTPS 的傳入要求加上 HSTS 標題。這會指示瀏覽器/用戶端日後一律透過 HTTPS 提出要求，以符合安全性最佳實務。目前我們還不會針對使用 HTTP 的傳入要求強制執行此規範。 |
| 變更Experience Cloud ID服務Cookie設定 | 2020 年 9 月 22 日 | 一項針對 Chrome 80 版本隱私權設定的更新影響 Adobe Analytics 追蹤部分檢視 Google AMP 頁面之使用者的能力。具體來說，這項更新會防止跨網域追蹤檢視 Google 託管 AMP 頁面的使用者。如此可能導致不重複訪客的數量增加。此修正可讓使用者透過變更 ECID Cookie 設定來解決此問題。<br>目前，Analytics會設定Experience Cloud ID服務(ECID)Cookie，設定在Chrome 80版之前 `SameSite = Lax` 允許跨網域追蹤。 但如今情況有變。使用者可透過這項變更將 ECID Cookie 的 SameSite 設定更新為 `None`。<br>請注意，這可讓Analytics Cookie在更多情況下共用，但Analytics Cookie不包含敏感資訊。 In addition, when choosing this setting, cookies must be set to `Secure` so that data can be passed only via HTTPS connections. 若想進行此一變更，請由支援的使用者透過客戶服務建立票證。 |
| 從 `omniture.com` 移轉至 `adobe.com` 網域 | 2020 年 8 月 21 日 | 2020 年 8 月 13 日，Adobe Analytics 將前端架構從 `omniture.com|http://omniture.com/` 移轉至 `adobe.com|http://adobe.com/` 網域。此變更應可紓解 2020 年 5 月 28 日初次統一產品網域後發生的第三方 Cookie 問題。更新後，瀏覽器可能會提示使用者將 `.adobe.com|http://an.adobe.com/` 或 `experience.adobe.com|http://experience.adobe.com/` 等新網域加入信任清單。 |
| 更新 Ad Hoc Analysis Java 8 相容性 | 2020 年 8 月 21 日 | Ad Hoc Analysis 目前與 Java 8 1.8.0_261 以後的版本不相容。為確保您在[產品生命週期](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)結束前能順利存取此工具，建議您持續使用 1.8.0_261 之前的 Java 8 版本。 |
| Adobe Data Connectors 終止服務 | 2020 年 7 月 13 日 | Adobe [!UICONTROL Data Connectors] 的舊技術已無法使用或不再支援。[Adobe Exchange 合作夥伴計畫已推出一項新標準](https://partners.adobe.com/tw/exchangeprogram/experiencecloud)，任何希望能繼續使用服務及取得支援的整合項目，都應採用此標準。確切日期仍未決定，但預計未來 12 至 18 個月內 (2021 年中至 2021 年底) 將會正式終止服務。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/import/dataconnectors/data-connectors-eol.html) |
| 報告套裝對應至 IMS 組織 | 2020 年 7 月 | 報告套裝對應工具將於 2020 年 11 月終止提供。此功能可提升 Advertising Analytics 和 Experience Cloud 在 Adobe Analytics 中發佈區段的整合程度。報告套裝必須與 IMS 組織對應，才能啟用各項服務。較新的報告套裝會在建立時自動完成對應。然而，先前的報告套裝必須以手動方式與 IMS 組織對應。請參閱 Experience Cloud 介面 (核心服務) 使用指南中的[「將報表套裝對應至組織」](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/about-core-services/report-suite-mapping.html)，確認所有報表套裝均有歸屬的 IMS 組織。 |
| 全新 Adobe Analytics 預設登陸頁面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日起，Adobe Analytics 的預設登陸頁面將從[!UICONTROL 報告]變更為[!UICONTROL 工作區]。未設定自訂登陸頁面的使用者，將一律適用此變更。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 若為倫敦和新加坡的客戶，我們將不再於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間支援資料代理。<br/><ul><li>如果您是在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果您是在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意終止 Ad Hoc Analysis 服務。我們將會在確定後公佈服務終止日期。如需詳細資訊，請造訪[探索工作區](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### AppMeasurement {#appm}

如需 AppMeasurement 發行的最新消息，請參閱[適用於 JavaScript 的 AppMeasurement 發行說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。

### Analytics 課程與教學課程 {#tutorials-analytics}

[!DNL Analytics] 和 [!UICONTROL Customer Journey Analytics] 的最新課程、教學課程和文章。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 14 月 9 日 | [在分析工作區中自動建立自由表格](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/auto-build-freeform-tables-in-analysis-workspace.html) | 影片 | 將元件直接拖放至空白的專案、面板或 [!UICONTROL Freeform] table中，系統會自動以建議的格式為您建立表格。 |
| 2020 年 14 月 9 日 | [在自由表格中使用量度](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/working-with-metrics-in-a-freeform-table.html) | 影片 | 瞭解在分析工作區中，在自由表格中 [!UICONTROL 使用量度] 的各 [!UICONTROL 種方式]。 |
| 2020 年 14 月 9 日 | [下載50,000個CSV項目](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/download-50000-items-as-csv.html) | 影片 | 「以 [!UICONTROL CSV格式下載項目] 」選項可讓您在套用區段和篩選條件的情況下，為自由表格中的維度下載最多50,000個項目。 雖然UI在編頁前將繼續顯示最多400個項目，但此選項可讓您在分析工作區以外存取更多 [!UICONTROL 資料列]。 |
| 2020 年 14 月 9 日 | [分析工作區中的線條視覺化](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/visualizations/line-visualization-in-analysis-workspace.html) | 影片 | 「行」視覺化會描述趨勢時段內的量度。 視覺化設定可讓您自訂每行視覺化的外觀，並包含「顯示X/Y軸」、「顯示最小／最大標籤」和「顯示趨勢線」的設定。 |
| 2020 年 14 月 9 日 | [自由表格中的列和列設定](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/row-and-column-settings-in-freeform-tables.html) | 影片 | 瞭解分析工作區中 [!UICONTROL 自由表格] (Freeform Tables)的設定，以及這些設定對進入這些表格的資料有何影響。 |
| 2020 年 14 月 9 日 | [在自由表格中處理維度](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/working-with-dimensions-in-a-freeform-table.html) | 影片 | 瞭解在自由表格中處理維 [!UICONTROL 度] ，包括新增維度、排序、篩選、依其他維度劃分維度等。 |
| 2020 年 14 月 9 日 | [使用左側導軌在分析工作區中建立自由表格](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/building-freeform-tables/using-the-left-rail-to-build-freeform-tables-in-analysis-workspace.html) | 影片 | 瞭解如何在分析工作區中使用左側導軌來尋找、建立項目，以及將項目新增至自由表 [!UICONTROL 格] 。 |

### Analytics 說明資源

* [Adobe Analytics 教學課程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 產品文件](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)

## ![圖示](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 的新功能、修正項目、說明文件和教學課程。

發行日期: **2020 年 10 月 8 日**

### Adobe Audience Manager 新功能和修正項目

* 修正Audience Manager REST API的問題，此問題在篩選請求中的特徵時，特徵端點不會傳回跨裝置量度。 (AAM-55878)
* 修正「以人為本的目的地」中，Facebook整合存取權杖過期提醒電子郵件未傳送給正確收件者的問題。 (AAM-56215)
* 修正Google目標的問題，當客戶將區段對應至其Google目 `RateExceededError: Rate_Exceeded` 標時，會收到錯誤。 (AAM-55998)
* 修正資料提供者未指派組織ID [的問題](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/organizations.html#concept_384D169B0B724B799D573B8ECB5C39BF) ，此問題會導致資料來源清單頁面在連續載入狀態中遭到封鎖。 (AAM-56410)
* 整個介面的協助工具有多處改良。(AAM-49077、AAM-49399、AAM-55991、AAM-55992)

### Audience Manager檔案更新 {#docs-aam}

[Audience Manager現在提供協助工具檔案](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/accessibility-in-aam.html) 。

### Audience Manager 課程與教學課程 {#tutorials-aam}

針對 Audience Manager 發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 14 月 9 日 | [建立特徵分類法](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-a-trait-taxonomy.html) | 影片 | 瞭解在Audience Manager中建立包含您特徵的檔案夾結構的秘訣。 |
| 2020 年 14 月 9 日 | [建立已登入的特徵](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-onboarded-traits.html) | 影片 | 瞭解在Audience Manager中建立已登入特徵的秘訣。 |

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

* **AEM 雲端服務**

   AEM 雲端服務新增了哪些功能？

   * **Adobe Experience Manager Sites 雲端服務**
      * 單頁應用程式(SPA)編輯器Javascript SDK現在是開 [放原始碼。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/headless/spa/reference-materials.html)
   * **Adobe Experience Manager Assets 雲端服務**

      * 使用Asset microservices產生的轉譯支援浮水印影像檔案。 它可以設定為「處理設定檔」，並使用PNG檔案做為浮水印。 請參閱 [浮水印您的資產。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/manage/watermark-assets.html)
      * 動態媒體中的增強功能：
         * 選擇性發佈——行銷團隊現在可以存取與動態媒體同步的 [!UICONTROL Dynamic Media] 智慧型裁切影像和動態轉譯，讓他們建立促銷文宣，完全不需要將這些資產發佈至動態媒體以進行全域傳送。 Experience Manager和 [!UICONTROL Dynamic Media] Publishing是分離的，可分開執行，以達成此目的。 請參閱 [選擇性發佈。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/selective-publishing.html)
         * 密碼重設——管理員現在可重設 [!UICONTROL 布建時收到的Dynamic Media] Cloud服務密碼。 重設可在Experience Manager使用者介面中完成，而不需使用 [!UICONTROL Dynamic Media] Classic案頭應用程式。 請參 [閱將密碼變更為動態媒體。](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#change-dm-password)
      * 若要瞭解下列增強功能，請參 [閱品牌入口網站的新增功能。](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/introduction/whats-new.html)
         * 使用Adobe Document Cloud檢視SDK整合增強PDF預覽。
         * 按一下即可下載功能。
         * 下載體驗的新管理設定。
   * **Adobe Experience Manager Commerce即雲端服務**

      * 已發佈CIF核心元件v1.3.0。如需詳 [細資訊，請參閱CIF核心元件](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.3.0) 。
      * 現在提供產品／類別範本的預覽功能。 這可讓AEM中的商業使用者／行銷人員檢視具有真實資料的產品／類別範本。
      * 屬性頁面已新增至產品和類別，可讓商業使用者檢視與產品SKU/類別ID相關的詳細資訊。
      * 新增至「產品主控台」的排序功能，允許依名稱或價格屬性來排序產品／類別。
      * 產品搜尋功能已新增至 [!UICONTROL 產品主控台]。
   * **Cloud Manager**

      * [!UICONTROL 「內容審核] 」已重新標示為「 [!UICONTROL 體驗審核」]。
      * 建立程式已分為三個不同的Maven命令。
      * 如果Git Repository無法克隆，則最多將重新嘗試三次。
   * **Cloud Readiness Analyzer**

      * Cloud Readiness Analyzer(CRA)有一個啟動狀態控制台，它顯示一個明確的「生成報告 **** 」按鈕，供用戶按一下以執行CRA。
      * CRA UI會在執行中顯示進度。 它顯示正在分析的項目和在執行過程中發現的查找結果。
      * CRA報告以按查找類型和重要性級別組織的表格形式顯示了調查結果的摘要和數目。 按一下該尋找的數目會自動捲動至該尋找在報表中的位置。
   * **內容轉移工具**

      * 內容傳輸工具(CTT)支援Azure Blob儲存資料儲存。
      * CTT使用者介面具有自動重新載入功能，每30秒重新載入一次概述頁面。
      * 新增至CTT使用者介面的按鈕，以輕鬆擷取存取Token。
      * 新增「 *URL* 」和「移 *轉集名稱」的說明性驗證訊息*。
   * **程式碼重構工具**

      * AIO-CLI插件支援Repository Modernizer，並允許用戶使用插件執行工具。 See the [Git Resource: aio-cli-plugin-aem-cloud-service-migration](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration) for more details.
      * Repository Modernizer公用程式可用來將現有的專案套件重新架構為與為AEM定義為雲端服務的專案結構相容的套件。 請參閱 [Git資源：Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer) （資料庫現代化器），以瞭解詳細資訊。







請參閱 [AEM 雲端服務發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)。

### 自助資源

**[!DNL Experience Manager]網站**

Rich Text Editor文檔已更新，以列出RTE [中連結的所有支援的協定](https://docs.adobe.com/content/help/en/experience-manager-65/administering/operations/configure-rich-text-editor-plug-ins.html#linkstyles)。

**[!DNL Experience Manager]Assets**

* 有關AEM Assets如何 [可供所有使用者存取的](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/accessibility.html) ，有新說明內容可供使用。

* **[檢視模式參數](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/search-assets.html#assetpicker)** 會新增至資產選擇器（資產選擇器），以在搜尋模式中開啟資產選擇器。 若要在搜尋模式中開啟資產選擇器並搭配使用 `assettype` 和 `mimetype`，使用者需要在URL `viewmode=search` 中加上參數尾碼 `https://[aem-server]:[port]/aem/assetpicker.html`。 例如：`https://[aem-server]:[port]/aem/assetpicker.html?viewmode=search&assettype=images`。

* 在刪除專用資料夾時，會刪除專用資料夾的相關用戶組 [](https://docs.adobe.com/content/help/en/experience-manager-65/assets/managing/private-folder.html#delete-private-folder)，並且可以使用JMX中的clean方法從儲存庫中清理現有冗餘、未使用和自動生成的用戶組。

* 案頭應用程式2.0.3.2版 [已修正Service Pack 6.5.5.0](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/previous-hotfixes-featurepacks.html#assets-6550) ，案頭應用程式登入問題。

* 如果使用者修改了 [Apache Jackrabbit Oak TokenConfiguration](https://helpx.adobe.com/experience-manager/kb/How-to-set-token-session-expiration-AEM.html) ，將逾時設定設定為少於上傳資產所花的時間，則使用者會遇到作業逾時的情況。因此，使用者需要變更 `chunkUploadMinFileSize``chunksize`and，如此每個區塊請求就會重新整理作業。 如需詳細資訊，請參 [閱上傳資產](https://docs.adobe.com/content/help/en/experience-manager-65/assets/managing/managing-assets-touch-ui.html#uploading-assets)。

* 資產也可以 [使用拖曳作業移入同級資料夾](https://docs.adobe.com/content/help/en/experience-manager-65/assets/managing/managing-assets-touch-ui.html#moving-or-renaming-assets) ，除了 [!UICONTROL Move(m)] operation opens  Move Assets wizard外。

* 若為資產見解，請使 [用Adobe Launch](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/advanced/asset-insights-launch-tutorial.html)。 [DTM整合](https://docs.adobe.com/content/help/en/experience-manager-65/assets/managing/touch-ui-using-dtm-for-asset-insights.html) ，在檔案中稱為已過時的方法。

**[!DNL Adobe Experience Manager]案頭應用程式**

* 登出或首次登入案頭應用程式的使用者應提供其伺服器 [!DNL Experience Manager] URL的格式，然後選取 `https://[aem-server-url]:[port]/`[!UICONTROL Connect] （連線）選項，以避免出現「應用程式遇到未知錯誤」錯誤。 如需詳細資訊，請參 [閱「使用Adobe Experience Manager案頭應用程式」](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/using.html)。

### 社群

* **宣佈提交Experience Manager功能要求的新程式**

   您想看看Experience Manager規劃藍圖中新增的新功能嗎？ Adobe很高興推出 *FeatureBit* —— 這個專案旨在改善客戶和合作夥伴向Experience Manager產品團隊要求功能增強（稱為RFE）的方式。 透過 [Experience League AEM社群瞭解更多資訊。](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-the-new-process-to-submit-experience-manager-feature/td-p/380425)

* **Experience League 的最新 AEM 內容**

   此為 Adobe 提供之數位體驗技術內容的官方來源。若需參閱完整清單，請前往[此處](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)。

### 最新 Experience Manager 課程與教學課程 

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2020 年 30 月 9 日 | [類型變數表單資料模型](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/variables-aem-workflow/form-data-model.html) | 影片 | 表單資料模型類型的變數通常用於在表單資料模型的底層資料源中插入行。 此影片說明使用AEM工作流程在資料庫中插入列所需的步驟。 |
| 2020 年 25 月 9 日 | [驗證使用者是否使用其行動電話號碼](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/some-useful-integrations/two-factor-authentication.html) | 文章 | 瞭解如何在自適應表單中使用SMS來執行OTP驗證。 |
| 2020 年 28 月 9 日 | [AEM Asset Compute Microservices簡介](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.asset.compute) | 課程 | 本課程探討如何將AEM延伸為雲端服務資產計算微服務。 您現在應該能夠設定、開發、測試、除錯和部署自訂的「資產計算」工作者，以便AEM做為「雲端服務作者」服務使用。 |
| 2020 年 23 月 9 日 | [使用Adobe Analytics追蹤點按的元件](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/analytics/track-clicked-component.html) | 文章 | 搭配AEM核心元件使用事件導向的Adobe客戶資料層，以追蹤Adobe Experience Manager網站上特定元件的點按次數。 瞭解如何使用Experience Platform Launch中的規則來監聽點按事件、依元件篩選資料，以及將資料傳送至具有追蹤連結信標的Adobe Analytics。 |
| 2020 年 25 月 9 日 | [與AEM處理設定檔整合](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/deploy/processing-profiles.html) | 影片 | AEM as a Cloud Service透過AEM Assets Processing Profiles與部署至Adobe I/O Runtime的資產計算工作者整合。 「處理設定檔」是在「作者」服務中設定，以使用自訂工作者處理特定資產，並將工作者產生的檔案儲存為資產轉譯。 |
| 2020 年 25 月 9 日 | [部署至Adobe I/O Runtime](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/deploy/runtime.html) | 文章 | 資產計算專案及其所包含的工作者必須部署至Adobe I/O Runtime,AEM才能將其當做雲端服務使用。 |
| 2020 年 25 月 9 日 | [對資產計算工作器進行調試](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/asset-compute/test-debug/debug.html#asset-compute) | 文章 | 資產計算工作者可透過數種方式進行除錯，從簡單的除錯記錄陳述式到附加的VS程式碼（做為遠端除錯程式），再到提取從AEM以雲端服務方式啟動的Adobe I/O Runtime中啟動的記錄檔。 |
| 2020 年 25 月 9 日 | [測試資產計算工作者](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/test-debug/test.html) | 文章 | 「資產計算」項目定義了一種模式，以便輕鬆建立和執行資產計算工作者的測試。 |
| 2020 年 25 月 9 日 | [使用資產計算開發工具](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/development-tool.html) | 文章 | Asset Compute Dev Tool是本機網路工具，可讓開發人員在AEM SDK外部，針對Adobe I/O Runtime中的Asset Compute資源，在本機設定並執行Asset Computer工作者。 |
| 2020 年 21 月 9 日 | [開發資產計算員工](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/worker.html) | 文章 | 資產計算工作者是資產計算應用程式的核心，因為它提供了對資產執行或協調的定製功能，以建立新的轉譯。 |
| 2020 年 21 月 9 日 | [設定manifest.yml](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/manifest.html) | 文章 | Asset Compute專案的manifest.yml說明此應用程式中要部署的所有工作者。 |
| 2020 年 25 月 9 日 | [自定義分配任務通知](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/handling-af-form-submissions/customize-assign-task-notification.html) | 文章 | 在AEM工作流程中，在任務通知電子郵件中使用表單資料。 |
| 2020 年 21 月 9 日 | [配置環境變數](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/environment-variables.html) | 文章 | 環境變數會保留在「.env」檔案中，以供本機開發使用，並用來提供本機開發所需的Adobe I/O憑證和雲端儲存憑證。 |
| 2020 年 21 月 9 日 | [建立資產計算項目](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/develop/project.html) | 影片 | 資產計算應用程式是使用Adobe I/O CLI產生的Node.js專案，符合特定結構，可讓這些專案部署至Adobe I/O Runtime，並與AEM整合為雲端服務。 |
| 2020 年 21 月 9 日 | [設定Adobe I/O專案Firefly](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/firefly.html) | 影片 | 資產計算應用程式是特別定義的Adobe Project Firefly應用程式，因此需要在Adobe Developer Console中存取Adobe Project Firefly，才能設定和部署它們。 |
| 2020 年 21 月 9 日 | [設定本機開發環境](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/development-environment.html) | 文章 | 開發資產計算工具（即Node.js JavaScript應用程式）需要與傳統AEM開發不同的特定開發工具，從Node.js和各種npm模組到Docker Desktop和Microsoft Visual Studio程式碼。 |
| 2020 年 21 月 9 日 | [設定帳戶和服務](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/set-up/accounts-and-services.html) | 文章 | 開發資產計算工作者需要存取帳戶和服務，包括AEM作為雲端服務、Adobe Project Firefly以及Microsoft或Amazon提供的雲端儲存空間。 |
| 2020 年 14 月 9 日 | [搭配AEM核心元件使用Adobe用戶端資料層](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | 影片和文章 | Adobe用戶端資料層採用標準方法來收集和儲存網頁上訪客體驗的資料，然後方便存取此資料。 Adobe用戶端資料層不受平台限制，但已完全整合至核心元件，可與AEM搭配使用。 |
| 2020 年 28 月 9 日 | [搭配AEM核心元件使用Adobe用戶端資料層](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/adobe-client-data-layer/data-layer-overview.html) | 影片 | 瞭解事件導向的Adobe用戶端資料層如何公開AEM Sites核心元件的資料。 使用Adobe用戶端資料層，Experience Platform Launch等標籤管理解決方案可將網站資料傳輸至Analytics和Target等應用程式。 |
| 2020 年 21 月 9 日 | [資產計算微服務擴充性](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/overview.html) | 影片 | 教學課程，逐步介紹如何建立適用於AEM的自訂資產微型服務工作者，做為雲端服務。 |
| 2020 年 21 月 9 日 | [資產計算微服務擴充性](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/asset-compute/overview.html) | 影片 | AEM作為Cloud Service的Asset Compute microservices支援自訂工作者的開發與部署，這些工作者用來讀取和控制儲存在AEM中的資產的二進位資料，最常用的是，用來建立自訂資產轉譯。 |
| 2020 年 23 月 9 日 | [使用Adobe Analytics收集頁面資料](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/analytics/collect-data-analytics.html) | 文章 | 瞭解如何搭配使用Adobe用戶端資料層的內建功能與AEM核心元件，以收集Adobe Experience Manager Sites中某頁面的相關資料。 |
| 2020 年 8 月 9 日 | [樣式AEM CIF核心元件](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/customize/style-cif-component.html) | 文章 | CIF Venia Project是使用CIF核心元件的參考代碼庫。 在本教學課程中，您將檢視Venia參考專案，並瞭解AEM CIF核心元件所使用的CSS和JavaScript的組織方式。 您也可以使用CSS建立新樣式，以更新「產品摘要」元件的預設樣式。 |
| 2020 年 9 月 11 日 | [AEM —— 使用Commerce Integration Framework進行Magento整合](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | 影片 | 此影片會逐步帶您瞭解AEM與Magento for AEM On-Premise與AEM Managed Services之間的整合設定。 |

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

* [AEM As a Cloud Service指南](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
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

* 20.2.3 版 - [深入了解](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html#release-20-3-2-build-9182)
* 19.1.7 版 - [深入了解](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-7-build-9036)

#### Campaign Standard

* 20.4 版 - [深入了解](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-20-4---october-2020)

### 最新 Campaign 課程與教學課程

過去一個月內發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 解決方法 | 說明 |
| ----------- | ----------- | ---------- | ---------- |
| 2020 年 22 月 9 日 | [歷程AI —— 預測性傳送時間最佳化——視訊](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/communication-channels/email/journey-ai/predictive-send-time-optimization.html) | Campaign Standard | 瞭解在 Adobe Campaign 和 Journey AI 模型之間同步資料所需的工作流程。瞭解如何在個別設定檔層級檢視傳送時間分數，以及如何使用傳送時間公式執行電子郵件傳遞。 |
| 2020 年 22 月 9 日 | [歷程AI —— 預測性參與計分——視訊](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/communication-channels/email/journey-ai/predictive-engagement-scoring.html) | Campaign Standard | 瞭解如何在個別設定檔層級檢視參與分數、使用分數來定位參與的使用者並抑制疲勞的使用者，以及如何建立樣態規則來管理客戶疲勞。 |
| 2020 年 22 月 9 日 | [新增控制群組至傳送——視訊](https://docs.adobe.com/content/help/zh-Hant/campaign-standard-learn/tutorials/communication-channels/email/control-groups.html) | Campaign Standard | 瞭解如何為傳送定義控制組，以及如何在傳送後擷取指派給控制組的設定檔。 |
| 2020年9月11日 | [委派子網域](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/subdomain-delegation.html) | Campaign Classic | Adobe Campaign 控制面板可以讓您將子網域完全委派給 Adobe Campaign。 |
| 2020年9月3日 | [新增IP位址以允許清單](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/ip-allow-listing.html) | Campaign Classic | 「控制面板」可以讓您允許列出 IP 位址範圍，以便將新的連線設定到您的執行個體。依預設，Adobe Campaign Classic 執行個體無法從各種 IP 位址進行存取。 |
| 2020年9月3日 | [控制面板——新增URL權限](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/control-panel-acc/adding-url-permissions.html) | Campaign Classic | 「控制面板」可以讓您允許列出 IP 位址範圍，以便將新的連線設定到您的執行個體。依預設，Adobe Campaign Classic 執行個體無法從各種 IP 位址進行存取。 |

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
| 延長互動式影片前置內容的時間，加入 VAST 詳細目錄支援 | 現在，每個互動式影片前置內容版位和廣告均可支援 VPAID 和 VAST 詳細目錄。**注意：**&#x200B;如果您的主要 KPI 是檢視功能，請繼續建立個別的 VPAID 和 VAST 版位和廣告，因為可視度曝光率不適用於 VAST 廣告。 |

### [!UICONTROL Advertising Cloud Search] 新功能 {#adcloud-search}

**8 月 8 日**&#x200B;發行

| 功能 | 說明 |
| ----------- | ---------- |
| [!UICONTROL 產品組合] | 產品組合設定不再提供產品組合層級的位置限制。先前建立的所有位置限制均已移除。 |
| [!UICONTROL 限制] | 不再支援以位置為基礎的限制和限制條件：<br/> <ul><li>不再提供[!UICONTROL 「最小位置」]和[!UICONTROL 「最大位置」]等限制，並且已從先前建立的所有[!UICONTROL 「競價與位置」]限制和[!UICONTROL 「曝光共用」]限制中移除。</li><li>如果現有[!UICONTROL 「競價與位置」]限制內含位置限制，但無競價限制，均已一併暫停。上述限制仍可在 UI 和報表中使用。</li><li>[!UICONTROL 「競價與位置」]限制已重新命名為[!UICONTROL 「競價」]限制。</li><li>任意類型的限制中，所有以位置為基礎的條件 (使用[!UICONTROL 「平均位置」]、[!UICONTROL 「加權平均位置」]或[!UICONTROL 「最後已知位置」]量度) 均已移除。</li></ul> <br/> **注意：**&#x200B;如果從搜尋引擎能取得位置資料，系統仍會繼續將其填入。Microsoft Ads 將於 2020 年 9 月終止「位置」功能。 |
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

## ![圖示](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Adobe Document Cloud的發行資訊和說明資源。

### 全新Adobe Sign課程與教學課程

針對Adobe Document Cloud發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 9月30/20日 | [Adobe Sign快速導覽](https://docs.adobe.com/content/help/en/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/quick-tour.html) | 影片 | 快速導覽Adobe Sign介面，以開始使用。 |

如需Document Cloud說明，請參閱：

* [Adobe Acrobat 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=en)
* [Adobe Sign 學習中心](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=en)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)
