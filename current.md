---
title: Adobe Experience Cloud 發行說明
description: Adobe Experience Cloud 發行說明
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b909c99b4389be6ad67536e49224d33b3fb10af8
workflow-type: tm+mt
source-wordcount: '6688'
ht-degree: 43%

---


# Adobe Experience Cloud發行說明- 2020年6月

![橫幅](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. 此外，還著重說明全新檔案、訓練課程和視訊教學課程，以協助您充份運用Experience Cloud。

>[!NOTE]
>
>訂閱 [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。

**發行日期: 2020 年 6 月 18 日**

產品發行日期可能會有所不同。 請經常返回以取得更新。

最近更新：**2020 年 6 月 18 日**

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [歷程協調](#journey-orch)
* [Analytics](#analytics) (和 [客戶歷程分析](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [促銷活動](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) (Primetime 說明頁面連結)

需要協助嗎？請造 [訪Adobe Experience League](https://experienceleague.adobe.com/#home) ，以尋找產品與技術檔案、Adobe教學課程、視訊教學課程、快速解答、社群見解以及講師指導訓練。

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

已發佈： **2020年5月21日**

**新功能**

* 使用 Adobe ID 即可訂閱事件通知，並擁有更精細的控制能力，包括可針對產品和附加元件層級選擇所需通知。為協助您縮短設定訂閱的時間，自助訂閱程序現在會根據您的產品權限，為您建議一系列產品和服務項目。這樣應可減少您收到的電子郵件數量，您的收件匣將會收到與您更切身相關的通知。若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 更理想的訂閱和使用者通知體驗 | <ul><li>系統現在會根據您所選取的產品清單，篩選 [!DNL Marketo Engage] 區域位置。</li><li>[!DNL Marketo Engage] 電子郵件通知與使用者的地區、位置和環境偏好設定相關。</li></ul> |
| 事件訂閱確認 | <ul><li>現在訂閱進行中的單一事件更新時，會收到電子郵件確認。</li></ul> |
| 全域導覽可用性增強功能 | <ul><li>頂層導覽功能表提供與 `Adobe.com` 一致的使用者體驗。</li></ul> |

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud 介面 {#ecloud}

Experience Cloud介面的一般更新。

**統一產品網域**

Adobe 持續更新網域和介面標題，以統一及提升您使用所有 Experience Cloud 應用程式的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會改變目前的工作流程。

更新包括：

* 新應用程式 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * 瀏覽器支援：支援的瀏覽器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera] (最新版本)。**注意：** 雖然Experience Cloud介面支援這些瀏覽器，但個別應用程式可能不支援每個瀏覽器。 (例如 [Analytics](https://docs.adobe.com/content/help/zh-Hant/analytics/admin/sys-reqs.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hant/target/using/implement-target/before-implement/supported-browsers.html) 不支援 [!DNL Safari])。
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

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

發行日期: **2020 年 6 月 10 日**

[!DNL Adobe Experience Platform] 包含下列新功能：

* **資料科學工作區：** 現 [!DNL JupyterLab Launcher] 在包含Real-time Machine Learning(Alpha) [!DNL Python] 專用的筆記型啟動器。
* **區段：** 已新增日期函式的週年日欄位，讓使用者可評估不含年份的日期。
* **來源：** 和的新源連接 [!DNL Apache HDFS] 器 [!DNL Couchbase]。

如需這些功能的詳細資訊，請參閱 [Experience Platform發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)。

### 其他 Experience Platform 發行資訊

* [Experience Platform發行說明](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)
* [安全性佈告和諮詢](https://helpx.adobe.com/tw/security.html) (所有 Adobe 產品)

### 全新的Experience Platform課程與教學課程 {#tutorials-plat}

| 內容 | 內容類型 | 說明 |
| -----------| ---------- | ---------- |
| [Adobe Experience Platform簡介](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | 課程 | 瞭解Adobe Experience Platform如何透過將您的資料轉換為強穩的即時客戶個人檔案和AI導向見解，幫助您透過各個通道獲得啟動，進而提供正確的體驗。 本入門級課程概述Experience Platform的功能、使用案例、與Adobe Experience Cloud的關係、基本架構、介面和專案角色。 |
| [Web SDK和Edge Network簡介](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | 教學影片 | Adobe Experience Platform SDK和Edge Network的概觀。 Experience Platform Web SDK是用戶端JavaScript程式庫，可讓客戶使用一個JavaScript程式庫、一個信標類型、一個資料串流、一個伺服器端目的地，將資料傳送至所有Adobe應用程式和第三方目標。 |
| [Web SDK和Edge Network的示範程式](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | 教學影片 | 觀看Adobe Experience Platform Web SDK和Edge Network的實際運作，只要透過一次Adobe來電，即可將資料傳送至Experience Platform、Analytics、Audience Manager和Target。 |
| [即時客戶資料平台示範](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | 教學影片 | 瞭解如何使用即時CDP從多個源收集資料。 您可以將資料合併為單一即時客戶個人檔案，並啟用該資料以建立個人化客戶體驗。 |

## ![圖示](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

不論客戶處於哪個歷程階段，Adobe Experience Platform 能聰明地即時預測每個人的需求，以便能大規模協調不同體驗管道的客戶歷程。

### 最新版本

如需最新版本更新，請參閱 [Journey Orchestration版本注意事項](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html)

### 全新的歷程協調課程與教學課程 {#jo-tutorials}

| 內容 | 內容類型 | 說明 |
| -----------| ---------- | ---------- |
| [管理員的歷程協調快速入門](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | 課程 | 瞭解如何設定和使用Journey Orchestration。 本課程涵蓋重要概念，以及協調歷程所需的設定步驟。 瞭解如何建立、發佈，以及如何報告及分析您精心策劃的歷程。 |
| [面向商業使用者的Journey Orchestration快速入門](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | 課程 | 瞭解如何設定和使用Journey Orchestration。 本課程涵蓋主要概念。 您將學習如何建立、發佈、報告及分析您精心策劃的歷程。 |

### Journey Orchestration 的其他資源

[文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期: **2020 年 6 月 18 日**

* [Adobe Analytics 的新功能](#aa-features)
* [Customer Journey Analytics 的新功能](#cust-journey)
* [Media Analytics](#media-aa) 的新功能
* [Adobe Analytics中的修正](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [全新Adobe Analytics課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 的新功能 {#aa-features}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| -----------| ---------- |-------|
| 歸因 IQ：演算法歸因 | 2020 年 6 月 18 日 | Analysis Workspace 的[!UICONTROL 演算法歸因]模型會使用統計技術，以動態方式決定所選量度的最佳評分配置。適用於Adobe Analytics Ultimate客戶。 [更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| 歸因 IQ：自訂回顧期間 | 2020 年 6 月 18 日 | 您現在可以在[!UICONTROL 歸因 IQ] 設定任何歸因模型，以納入報表統計時段前最多 90 天的接觸點。這通常會計算之前月份的互動，以提高報表統計期間前期所發生之事件的歸因準確度。適用於Adobe Analytics Foundation、Select、Prime、Premium、Premium Attribution、Premium Complete和Ultimate客戶。 [更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| 共用工作區專案的專案角色 | 2020 年 6 月 18 日 | 共用工作區專案時，您現在可以根據您希望收件者擁有的專案體驗，將收件者置於下列三個專案角色之一：編輯、複製和檢視。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 僅限檢視的工作區專案 | 2020 年 6 月 18 日 | 工作區專案能僅以「可供檢視」狀態與使用者共用。「檢視」收件者開啟共用專案時，能獲得限制較嚴格的專案體驗，除了沒有左側邊欄，互動也會受限。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| 可共同編輯工作區專案 | 2020 年 6 月 18 日 | 新增至「可編輯」角色的收件者可在他們已獲共用的專案中執行儲存作業。無論管理員或非管理人員均可適用。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| 更新工作區中的空白面板 | 2020 年 6 月 18 日 | 工作區中的空白面板現在增設多種面板和視覺效果，提供您更順暢的操作方式，以便您挑選最適合的分析工作流程。 |
| 中國 RDC 允許使用的第一方網域 | 2020 年 6 月 18 日 | 讓擁有 `.cn` 網域的客戶可請求第一方網域，以便在中國大陸境內使用(購買「中國效能最佳化」SKU 時可拿到相關文件)。 |
| 工作區中的「快速深入分析」面板 | 2020 年 6 月 25 日 | 「快速深入分析」為 Analysis Workspace 的非分析師和新使用者提供指引，了解如何快速輕鬆回答業務問題。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| 工作區中的「Analytics for Target」面板 | 2020 年 6 月 25 日 | 「Analytics for Target」(A4T)面板可讓您在分析工作區中，以提升度和自信的方式分析Adobe Target活動和體驗。 [更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL 關於工作區] 」頁 | 18,2020 年 6 月 | 「關 [!UICONTROL 於工作區] 」頁面提供您分析工作區環境、Adobe Analytics管理員的相關資訊（如果您需要支援），以及提供產品內部意見回應的方式。 它可在「工作區 **[!UICONTROL >說明]** >關於工作 **[!UICONTROL 區」下找到]******。 |

### Customer Journey Analytics 的新功能 {#cust-journey}

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| -----------| ---------- |-----|
| 支援物件陣列 | 2020 年 6 月 18 日 | CJA客戶現在可以報告其Adobe Experience Platform資料集結構中，物件陣列中顯示的維度和量度。 [更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-usecases/object-arrays.html) |
| Attribution IQ: [!UICONTROL Algorithmic Attribution] | 2020 年 6 月 18 日 | Analysis Workspace 的[!UICONTROL 演算法歸因]模型會使用統計技術，以動態方式決定所選量度的最佳評分配置。適用於Adobe Analytics Ultimate客戶。 [更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| 歸因 IQ：自訂回顧期間 | 2020 年 6 月 18 日 | You can now configure any attribution model in [!UICONTROL Attribution IQ] to include touch-points from up to 90 days before the reporting time period. 這通常會計算之前月份的互動，以提高報表統計期間前期所發生之事件的歸因準確度。[更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/models.html) |
| Support for [!UICONTROL Anomaly Detection] | 2020 年 6 月 18 日 | [!UICONTROL 「異常偵測」提供一種統計方法，以判斷指定的量度和先前的資料比較有何變更。][更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Project roles for shared [!UICONTROL Workspace] projects | 2020 年 6 月 18 日 | When sharing a [!UICONTROL Workspace] project, you can now place recipients in one of three project roles, depending on the project experience you want them to have: Edit, Duplicate and View. [更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| View-only [!UICONTROL Workspace] projects | 2020 年 6 月 18 日 | [!UICONTROL 工作區] 專案可共用給使用者，如 _[!UICONTROL 「僅限檢視]_」。 當「檢視」收件者開啟共用專案時，他們會收到限制較嚴格的專案體驗，而且沒有左側導軌和有限的互動。[更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html) |
| Ability to co-edit [!UICONTROL Workspace] projects | 2020 年 6 月 18 日 | Recipients added to the _[!UICONTROL Can Edit]_role can save over a project that has been shared to them.[更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| [!UICONTROL Workspace] 中的「快速深入分析」面板 | 2020 年 6 月 25 日 | 「快速深入分析」為 [!UICONTROL Analysis Workspace] 的非分析師和新使用者提供指引，瞭解如何快速輕鬆回答業務問題。[更多詳情...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/panels/quickinsight.html) |
| [!UICONTROL 關於工作區] 」頁 | 18,2020 年 6 月 | 「關 [!UICONTROL 於工作區] 」頁面提供您分析工作區環境、Adobe Analytics管理員的相關資訊（如果您需要支援），以及提供產品內部意見回應的方式。 它可在「工作區 **[!UICONTROL >說明]** >關於工作 **[!UICONTROL 區」下找到]******。 |

### [!UICONTROL Media Analytics] 的新功能{#media-aa}

更新日期： **2020年6月18日**

| 功能 | [一般可用性](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/an-releases.html) - 目標日期 | 說明 |
| -----------| ---------- | ---------- |
| [支援的裝置和平台](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 2020 年 6 月 18 日 | 含AEP SDK的Media Launch Extension現在支援下列OTT裝置：<ul><li>Apple TV  (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [支援的裝置和平台](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 2020 年 6 月 18 日 | 含AEP SDK的Media Launch Extension現在支援下列OTT裝置：<ul><li>Apple TV  (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [播放器狀態追蹤](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/player-state-tracking/player-state-overview.html) | 2020 年 5 月 29 日 | [!UICONTROL Media Analytics] 客戶可在播放時使用全螢幕、隱藏字幕、靜音、畫中畫和焦點的標準解決方案變數集來擷取檢視者互動。 您也可以彈性建立自訂播放器狀態。「播放器狀態追蹤」變數現在可用於 [!UICONTROL Analysis Workspace] 中的報告。此功能需有下列任一個項目： <ul><li>Media [!DNL JavaScript] SDK 3.0 或更新版本</li><li>與 [!DNL Adobe Experience Platform] (AEP) SDK 搭配使用：</li><li>[!UICONTROL Media Analytics 擴充功能] (適用於網頁)：[!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 或更新版本</li><li>[!UICONTROL Media Analytics 擴充功能] (適用於行動裝置)：[!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 或更新版本</li><li>[!UICONTROL 媒體收集]</li></ul> |

### Adobe Analytics中的修正 {#aa-fixes}

* 修正特定報表套裝中，具多位元組搜尋條件的區段找不到任何相符項目的問題。現在，這類區段已能找到正確的相符字串。(AN-220043)
* Fixed an issue with the [!UICONTROL Item Filter] in [!UICONTROL Reports &amp; Analytics] not working. (AN-206132)
* Fixed slow response time in [!UICONTROL Scheduled Projects] interface. (AN-214837)
* 修正 Analytics 報表 API 2.0 所造成日期範圍錯誤的問題。(AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. 同一秒內的後續點擊沒有維度值 (例如 Pagename) 時，就會發生此現象。(AN-211074)
* Fixed an issue with users unable to access [!UICONTROL Workspace] projects shared with them. (AN-217561)
* Fixed issue with keys not being classified by [!UICONTROL Classification Rule Builder]. (AN-221538)
* Fixed an issue with the [!UICONTROL Server Call Usage] not reporting any usage data. (AN-210452)
* 已修正已發佈的Adobe Analytics區段在Audience Manager中遺失資料的問題。 (AN-220208、AN-220659)
* Fixed an issue with reports showing data but [!UICONTROL Data Feeds] logs saying &quot;No Data Warehouse data&quot;. (AN-220784、AN-220858)
* Fixed issues that prevented the launch of [!UICONTROL Ad Hoc Analysis] from the `experiencecloud.com` domain. (AN-219680、AN-221629)
* 修正使用「Ctrl (或 Command) + C」快速鍵時發生的問題。(AN-221101、AN-221537)
* Fixed an issue with the [!UICONTROL Activity Map] enablement page. (AN-222029、AN-221242)
* Fixed an issue with not being able to add a touch-point in the middle of a [!UICONTROL Fallout] visualization. (AN-221648)

#### 其他 Adobe Analytics 修正項目

AN-218269；AN-218455；AN-218492；AN-219888；AN-220447；AN-220546；AN-220788；AN-220866；AN-221165；AN-221545；AN-221712；AN-221832；AN-221853；AN-222000；AN-222505；AN-222559

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 移轉至統一的產品網域 | 生效日期：2020 年 5 月 28 日 | 從 2020 年 1 月開始，Adobe Analytics 就開始移轉至統一的產品網域，相關作業已於 2020 年 5 月 28 日完成。雖然 Adobe Analytics 已著手從架構中移除所有 `omniture.com` 網域參考，但請務必將 `omniture.com` 放入協力廠商 Cookie 允許清單。當完成完整架構移轉時，我們將透過發行說明通知您，不再需要此allowlist步驟。 請參閱這份建議 IP 位址和網域的[完整清單](https://helpx.adobe.com/tw/analytics/kb/adobe-ip-addresses.html)，這些位址和網域均應列入允許清單。<br>如果貴組織封鎖第三方 Cookie，請連絡客戶服務人員，以重新取得 Adobe Analytics 的存取權限。 |
| 全新 Adobe Analytics 預設登陸頁面 | 生效日期：2020 年 6 月 18 日 | 2020 年 6 月 18 日起，Adobe Analytics 的預設登陸頁面將從[!UICONTROL 報告]變更為[!UICONTROL 工作區]。未設定自訂登陸頁面的使用者，將一律適用此變更。 |
| 協力廠商技術許可清單 | 2020 年 3 月 12 日 (生效日期) | Adobe Analytics 已開始運用協力廠商技術進行功能推出管理和產品內支援。下列 URL 應新增至任何必要的網路防火牆允許清單，確保完整的功能存取權限：<ul><li>Gainsight：https://esp.aptrinsic.com</li><li>LaunchDarkly：https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 2020 年 5 月 21 日 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. 應將下列URL添加到任何必要的網路防火牆允許清單：<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| 變更 [!UICONTROL Workspace] 計算[!UICONTROL 輸入/結束]次數的方式 | 2020 年 4 月 7 日 | 自 2020 年 3 月起，[!UICONTROL Analysis Workspace] 已變更&#x200B;_「無」_&#x200B;值與[!UICONTROL 輸入/結束]動作的互動方式。由於您現在可以在 [!UICONTROL Analysis Workspace] 中開啟或關閉&#x200B;_「無」_，因此我們會在使用者輸入或結束後套用&#x200B;_「無」_，但 (eVars) 以往都是在輸入或結束之前就先套用。例如，假設造訪事件的第一次點擊未輸入 eVars 的值，但第二次點擊則有輸入。在 [!UICONTROL Reports &amp; Analytics] 中，第一次點擊的輸入會顯示為&#x200B;_「未指定」_，但在 [!UICONTROL Analysis Workspace] 中則會顯示第二次點擊的值。 |
| **[!UICONTROL 控制面板封存]**&#x200B;確定汰除 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，[!UICONTROL Reports &amp; Analytics] 中&#x200B;**[!UICONTROL 「管理控制面板」]**&#x200B;底下的&#x200B;**[!UICONTROL 「檢視封存」]**&#x200B;設定將不再提供使用。 |
| 終止服務 - Analytics Legacy API | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy Oauth 驗證 (Oauth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy Oauth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 若為倫敦和新加坡的客戶，我們將不再於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間支援資料代理。<br/><ul><li>如果您是在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果您是在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意終止 Ad Hoc Analysis 服務。我們將會在確定後公佈服務終止日期。如需詳細資訊，請造訪[探索工作區](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

#### 全新Analytics課程與教學課程 {#tutorials-analytics}

Analytics和客戶歷程分析中的新課程、教學影片和文章。

| 內容 | 內容類型 | 說明 |
| -----------| ---------- | ---------- |
| [使用者客戶歷程分析快速入門](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | 課程 | 在本課程中，您將學習如何使用客戶歷程分析(CJA)來分析來自許多不同資料來源的資料。 您將瞭解Adobe Analytics和客戶歷程分析之間的差異，以及CJA中如何處理資料。 參加本課程後，您應能夠建立和自訂跨通道視覺化，以進一步瞭解客戶。 |
| [管理員客戶歷程分析快速入門](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | 課程 | 瞭解如何設定和使用歷程 [!UICONTROL 協調]。 本課程涵蓋重要概念及協調歷程所需的設定步驟。 您將學習如何建立、發佈以及如何報告及分析您精心策劃的歷程。 |
| [針對資料工程師的客戶歷程分析快速入門](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | 課程 | 在本課程中，您將瞭解傳入客戶歷程分析的資料，以及它對分析師報表的影響。 本課程以您對Adobe Experience Platform的一般知識為基礎。 |
| [管理員客戶歷程分析快速入門](https://video.tv.adobe.com/v/34349?captions=chi_hant) | 教學影片 | 管理員客戶歷程分析簡介影片。 |
| [引導分析實作](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | 課程 | 在本課程中，您將學習如何開始實作Adobe Analytics、瞭解Analytics概念、建立計畫，以及使用Experience Platform Launch實作Adobe Analytics。 |
| [領導者的Adobe Analytics基礎](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | 課程 | 在本課程中，請瞭解Analytics基礎知識，以及分析工作區如何改變您的業務。 瞭解如何透過Adobe Sensei發掘見解、聽取客戶實證，並觀看2019年峰會業界專家的精彩介紹。 |
| [分析工作區快速入門](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | 課程 | 瞭解如何開始使用分析工作區。 建立您的第一個專案、瞭解如何定義日期範圍、套用區段，以及在專案上共用和協作。 |
| [Adobe Analytics儀表板Scorecard Builder](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | 教學影片 | 在此影片中，瞭解如何在 [!UICONTROL Analysis] Workspace中建立和共用記分卡  ，以便在Adobe Analytics儀表板（行動應用程式）上檢視。 |
| [Adobe Analytics儀表板應用程式內體驗](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | 教學影片 | 在此影片中，瞭解如何使用Adobe Analytics儀表板（行動應用程式）存取及檢視由您建立或與您共用 [!UICONTROL 的記分卡] 。 |

#### Analytics 說明資源

* [Adobe Analytics 教學課程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 產品文件](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)

## ![圖示](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Audience Manager 的新功能、修正項目、說明文件和教學課程。

Updated **June 10, 2020**

### 使用者介面更新

Audience Manager 即將推出網域和標題列更新，除了提升您的使用體驗，也與其他 Experience Cloud 應用程式統一。

* 在不同組織或應用程式之間更輕鬆地切換。
* 提升使用者說明品質，包括「說明」功能表中的精選文章和內容相關影片。
* 能夠提供有關Experience Platform和檔案支援票證的意見回饋。
* 更容易上手的新 URL 模式。將書籤更新至新 URL：`experience.adobe.com/audience-manager`。

這些更新僅適用於使用 Adobe ID 登入的使用者。若要切換成以 Adobe ID 登入，請參閱[管理 Experience Cloud 使用者和產品](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/manage-users-and-products/admin-getting-started.html)。

### Adobe Audience Manager 的新功能和修正項目

| 功能 | 說明 |
| -----------| ---------- |  
| [IAB TCF v2.0的Audience Manager外掛程式 ](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | 繼續Adobe對「依設計隱私權」的專注，我們將IAB TCF的Audience Manager外掛程式升級為IAB透明與同意框架(TCF)2.0版，從2020年6月10日起。 已實作IAB TCF Audience Manager外掛程式的客戶必須在2020年8月15日前升級至2.0版，才能繼續使用此功能。 在2020年8月15日之後，1.1版將不再支援。 |

**修正項目**

* 更新 [!UICONTROL Audience Marketplace條款與條件] ，以反映特定地區的法律要求。 (AAM-54518)
* 修正從書籤存取 [!UICONTROL Traits] 頁面會導致404錯誤的問題。 (AAM-54768)
* 修正擷取演算模型時，目標更新API逾時的 [!UICONTROL 問題]。 (AAM-54342)
* 使用者現在可以看到智慧型人物的模型分類 [!UICONTROL 正確度指標]。 (AAM-54847)
* 修正新增特徵運算式後按Enter會移除運算式而非儲存的問題。 (AAM-54210)
* 修正沒有VIEW_MODELS權限的使用者，對 [!UICONTROL Traits] API的GET方法的呼叫會失敗的問題。 (AAM-53104)
* 修正使用者無法刪除包含資料夾特 [!UICONTROL 徵的演算法模型][!UICONTROL 的問題]。 (AAM-50192)
* 長特徵運算式現在包住多行。 (AAM-54972)
* 已修正具有唯讀權限的使用者在演算法模型頁面中 [!UICONTROL 看到「建立新] 」按鈕的問題。 (AAM-54889)
* 修正CSV下載完成 [!UICONTROL 後] ,「一般」和「趨  勢」報表載入指示符仍會旋轉的問題。 (AAM-54571)
* 修正使用者無法在區段產生器中新增大量特徵至區段 [!UICONTROL 的問題]。 (AAM-55033)
* 整個介面的協助工具有多處改良。(AAM-47269、AAM-48966、AAM-48976、AAM-49369、AAM-49023、AAM-49042)。

### 新的Audience Manager課程和教學課程 {#tutorials-aam}

| 內容 | 內容類型 | 說明 |
| -----------| ---------- | ---------- |  
| [Audience Manager簡介](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | 課程 | 本課程教您Audience Manager的基本知識，以及您可使用它解決的問題。 瞭解常見使用案例和主要Audience Manager術語和概念。 |
| [Audience Manager中的Identity簡介](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | 教學影片 | 瞭解Adobe Audience Manager如何管理身分識別，包括內部個人檔案與個人檔案合併，以及與合作夥伴的ID同步。 |
| [瞭解和設定以人為本的LinkedIn目的地](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | 課程 | 此影片會逐步帶您瞭解建立LinkedIn的以人為本的目的地的概念和步驟。 它以其他有關以人為本的目的地的影片和檔案為基礎。 |
| [建立規則型特徵](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | 教學影片 | 瞭解如何使用Audience Manager介面中的 [!UICONTROL Trait Builder] ，以建立以規則為基礎的特徵，讓您將即時活動擷取到Audience Manager個人檔案中。 |
| [啟用IAB TCF 2.0的Audience Manager外掛程式](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | 教學影片 | 瞭解如何啟用IAB TCF的Audience Manager外掛程式。 如果您使用Adobe Experience Platform Launch，啟用此外掛程式就很簡單。 |
| [IAB TCF 2.0的Audience Manager外掛程式示範](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | 教學影片 | 在此影片中，瞭解Experience Cloud ID服務和解決方案的Cookie和信標如何受到IAB使用者選擇選擇的影響。 |

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品更新

* **AEM 6.5.5.0**

   AEM 6.5,Service Pack 5（6.5.5.0於2020年6月04日發行）是重要的更新，其中包含新功能、客戶要求的重要增強功能，以及自2019年4月AEM 6.5全面推出以來發佈的效能、穩定性、安全性改進。

   * [發行說明](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [AEM Forms 發行交付項目](https://helpx.adobe.com/tw/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack（6.4.8.1於2020年6月4日發行）是重要的更新，包含自2020年3月AEM 6.4、Service Pack 8(6.4.8.0)全面推出以來的數項內部和客戶修正。

   * [發行說明](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms 發行交付項目](https://helpx.adobe.com/tw/aem-forms/kb/aem-forms-releases.html)

### 自助資源

* **AEM 雲端服務**

   AEM的Cloud Service有哪些新功能？

   重點包括：

   * AEM Sites商務整合架構。
   * 增強的智慧型標籤和UI引導式培訓體驗的新功能。
   * Adobe Xd的Adobe Asset Link支援。
   * AEM Assets Dynamic Media 3D支援。
   * 全新的自助服務改良功能可降低對Adobe執行沙盒作業的依賴性。
      * Cloud Manager中增強的自助沙盒支援可讓有權使用的使用者刪除沙盒內的所有環境並接收點數。
      * 自動休眠沙盒環境會在閒置一段時間後自動「休眠」沙盒。 客戶可以主動觸發「去休眠」。
   * 支援雲端加速的轉換工具

   為了減少從現場服務過渡到雲服務的時間和成本，本月推出了兩種過渡工具。 這些工具旨在自動化過渡過程中的某些關鍵任務，從而減少整體工作量。 .

   1. [使用內容傳輸工具](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) （SD提供）可簡化內容傳輸活動，並讓其可擴充。 此工具提供使用者友好的UI，可讓轉換至AEM做為雲端服務的現有客戶和合作夥伴（在預備/AMS）自助服務。
   1. [AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) （開放原始碼）工具，可自動將AMS Dispatcher組態轉換為Cloud Service Dispatcher組態。

   [AEM a Cloud Service 2020.6.0的發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   轉換工具：

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **核心元件**

   核心元件2.9.0與 [Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) （用戶端資料層）和全新的進度列元件整合，現在提供製作檔案和開發人員詳細資訊，以及GitHub上提供的專案下載 [](https://docs.adobe.com/content/help/zh-Hant/experience-manager-core-components/using/introduction.html)[](https://github.com/adobe/aem-core-wcm-components)。

* **移轉至AEM做為雲端服務**

   [以雲端服務的形式移轉至AEM](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/home.html) ，說明現有AEM客戶移轉至雲端服務的建議轉換歷程。 本說明檔案的目標是提供客戶資訊、指引和最佳實務，協助他們為此轉變做好準備，並讓這一歷程有條理且可預測。

   其中一個雲端轉換工具——內容傳輸工具已發行。 [內容傳輸工具](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) (Content Transfer Tool)由Adobe開發，可用來將現有內容從來源AEM例項（內部部署或AMS）移至目標AEM Cloud服務例項。

   已發行其中一個程式碼重構工具- AEM Dispatcher Converter。 [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) 是將現有的AEM Dispatcher組態轉換為AEM做為Cloud Service Dispatcher組態的工具，現已推出。

* **無障礙環境支援與WCAG 2.1准則**

   與WCAG 2.1准則相關的更新：

   * [Adobe Experience Manager 雲端服務與網路無障礙指引 ](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [WCAG 2.1 快速指南](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [建立可存取的內容 (符合 WCAG 2.1)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM 電子報**

   Experience League 的 AEM 電子報可協助您快速熟悉 AEM，並立即開始實現其價值。以下是最新的電子報：

   * [第 31 期](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html)：Experience Manager 現在能以雲端服務形式使用。
   * [訂閱](https://adobeeventsonline.com/AEM/2017/NL/Optin/) Experience Insider 電子報。
   * 前往 Adobe Experience Manager 6.5「學習與支援」頁面的[「AEM 資源」](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)區段，即可檢視電子報封存檔。

### **社群**

* **AEM社群討論**

   現在，您可以集中檢視所有AEM公告，以及內部和外部部落客的有趣參考。 請參閱AEM社群的「討 [論」區段。](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### 全新Experience Manager課程與教學課程

| 內容 | 內容類型 | 說明 |
| -----------| ---------- | ---------- |
| [適用於商業使用者的Adobe Asset Link快速入門](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | 課程 | 在本課程中，瞭解如何使用Adobe Asset Link的功能和功能，透過Adobe Experience Manager Assets中儲存的內容，推動您的創意設計。 本課程涵蓋各種課程，從如何啟動adobe資產連結、基本資產作業、搜尋和瀏覽選項，以及如何有效率地與其他使用者協作。 |
| [適用於商業使用者的AEM資產快速入門](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | 課程 | 瞭解如何針對商業使用者開始使用AEM Assets。 探索AEM Assets的基本概念、協作功能、搜尋、組織資產，以及下載資產及其轉譯。 |
| [AEM Sites快速入門，適用於商業使用者](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | 課程 | 瞭解如何使用AEM Sites的核心功能和功能來管理您組織的網頁。 本課程涵蓋從AEM Sites簡介、製作的基本概念、進階製作功能以及頁面管理功能等所有內容。 |
| [AEM 專案結構](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | 文章 | 說明Adobe Experience Manager Maven專案所需的變更，以便與AEM Cloud Service相容。 |
| [Sling Models](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | 教學影片 | 瞭解如何使用Sling Models網頁主控台，將AEM除錯為Cloud Service SDK的本機快速入門。 |
| [AEM Web Console元件](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | 教學影片 | 瞭解如何使用「元件」網頁主控台，將AEM除錯為Cloud Service SDK的本機快速入門。 |
| [使用記錄檔除錯AEM SDK的本機快速入門](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | 教學影片 | 瞭解如何使用Bundles網頁主控台，將AEM除錯為Cloud Service SDK的本機快速入門。 |
| [遠端除錯AEM作為Cloud Service SDK的本機快速入門](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | 教學影片 | 從IDE瞭解遠端Java除錯，讓您逐步執行AEM中的即時程式碼執行，以瞭解確切的執行流程。 |
| [智慧型標籤設定](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | 教學影片 | 使用Adobe I/O將Adobe Experience Manager(AEM)與智慧型內容服務整合的逐步指示。 |
| [批次產生檔案](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | 文章 | 瞭解如何使用批次API從範本產生多種互動式通訊。 |
| [在AEM Forms中建立列印渠道檔案](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | 文章 | 瞭解建立適用於列印頻道的互動式通訊所需的步驟。 |
| [存取Adobe Asset Link](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | 教學影片 | 瞭解如何存取儲存在Adobe Experience Manager Assets(AEM Assets)中的內容，而不需離開您最熟悉的Creative Cloud案頭應用程式。 |
| [資產連結面板概觀](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | 教學影片 | Adobe Asset Link讓創意使用者能夠使用InDesign、Photoshop和Illustrator的應用程式內面板，瀏覽、搜尋、取出和存回儲存在AEM Assets中的資產。 瞭解Adobe Asset Link面板的UI及其功能。 |
| [資產搜尋](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | 教學影片 | 創意使用者可以使用關鍵字搜尋儲存在AEM Assets中的資產，或在特定位置下執行搜尋。 |
| [檔案版本修訂與注釋](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | 教學影片 | 使用Adobe Asset Link面板，您可以從面板存取AEM Assets中資產的檔案詳細資訊，例如縮圖、基本中繼資料和版本。 |
| [登入登出](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | 教學影片 | Adobe Asset可讓您直接從您正在使用的創意應用程式中取出AEM Assets，並立即開始進行編輯。 |
| [適用於僅限AEM資產的轉譯](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | 教學影片 | 探索如何針對AEM資產建立和使用「僅限於位置(FPO)」轉譯。 |
| [置入文案](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | 教學影片 | 瞭解如何使用「置入複製」作業，從AEM Assets使用資產。 |
| [下載和上傳](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | 教學影片 | 瞭解如何使用「資產連結」面板，從AEM Assets下載資產檔案並上傳至AEM Assets。 |
| [檔案和系列](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | 教學影片 | 瞭解如何從「資產連結」面板快速輕鬆地存取AEM Assets檔案和系列。 |
| [下載](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | 教學影片 | 瞭解如何將資產及其轉譯下載至本機電腦，以便使用和共用。 |

### 其他資源

* [AEM 雲端服務](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)
* [AEM 6.4 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-4.html)
* [AEM 6.3 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-3.html)
* [AEM 6.2 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/tw/experience-manager/cloud-manager/user-guide.html)
* [舊版 AEM 文件](https://helpx.adobe.com/tw/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre 發行說明](https://docs.adobe.com/content/help/zh-Hant/livefyre/using/release-notes/c-rn.translate.html)

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 新產品版本

[Adobe Campaign Classic 20.2版本包括](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html) :

* _支援Emoticon_ - _Azure Synapse FDA Connector_ —— 新的隱 _私法規_
* 促銷活動控制面板： [主動式描述檔監控](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### 新的Campaign課程和教學課程

| 內容 | 內容類型 | 說明 |
| -----------| ---------- | ---------- |  
| [適用於商業使用者的Adobe Campaign Standard快速入門](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | 課程 | 瞭解如何導覽介面、處理傳送，以及建立和管理收件者資料。 |
| [安裝和設定Adobe Campaign用戶端](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | 影片 | 瞭解如何下載和安裝Adobe Campaign Client主控台、建立和管理您與多個環境的連線，以及驗證Adobe Campaign主控台的存取權 |

### 說明資源

* Adobe Campaign Standard：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/campaign-standard-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[說明中心](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html) - Campaign Standard / [Campaign Classic的使用說](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)[明影片](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Advertising Cloud DSP 新功能](#adcloud-dsp)
* [Advertising Cloud Search 新功能](#adcloud-search)

### Advertising Cloud DSP 新功能 {#adcloud-dsp}

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 促銷活動] 首頁 | （6月3日發行版本）提供新的促銷活動層級進度量度，其依據是提供的促銷活動預算和剩餘時間。 |
| 位置預測 | （6月3日發行）對於具有位置層級最佳化的CTV和視訊位置，位置設定現在包含對多個廣告長度（15秒和30秒）的預測。 還包括對VAST和VPAID庫存的預測。 |
| CPA/ROAS最佳化 | （5月20日發行）促銷活動經理不再需要在套件中限制新位置，以防止預算超額分配。 位置現在會根據其CPM或CPA/ROAS績效接收動態預算分配。 |

### [!UICONTROL Advertising Cloud Search] 新功能 {#adcloud-search}

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 行銷活動] | Microsoft Advertising（之前稱為Bing Ads）會取代2020年9月30日之後的平均職位度量。 為了準備，從7月11日開始，將忽略基於位置的約束，也將忽略任何類型約束中基於位置的條件。 |
| [!UICONTROL 廣告見解] | （6月13日發行）已移除下列見解：<br/><br/><ul><li>Audience Target效能（較新版本）</li><li>歷史效能（較新版本）</li><li>符合類型（較新版本）</li><li>設定稽核（較新版本）</li><li>投資組合貼文前（舊版）</li></ul><br/>其餘的見解是舊版， _Legacy_ label已從名稱中移除。 此外，「即時／編輯」模式已移除。 |

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
| [!DNL Bizible] | <ul><li>全新的帳戶型分段</li><li>儲存控制面板專有的篩選器</li><li>將 Bizible 控制面板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 公告

**Marketo Engage Success Center：**&#x200B;預計於 2020 年 2 月推出。Success Center 是產品內的說明中心，可讓您搜尋產品檔案和社群、啟動操作指南、存取採用內容等等。注意：此功能將會以測試版的形式在澳洲與紐西蘭推出，並預計於本季末在北美地區推出。

### 淘汰

* **資產 API「_method」參數：** 2020 年 9 月後，資產 API 端點將不再接受於 POST 主體中使用 `_method` 傳遞查詢參數，以略過 URI 長度限制。
* **Internet Explorer 支援淘汰：**&#x200B;從 2020 年 7 月 31 日推出的七月版開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

如需彙整資料和過往的發行說明，請參閱 [Marketo 發行說明](https://docs.marketo.com/x/CgA6Ag)。
