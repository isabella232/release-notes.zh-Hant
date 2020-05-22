---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 4bdb8dde04f55703e52aca1295aad03374f3eb25
workflow-type: tm+mt
source-wordcount: '4998'
ht-degree: 95%

---


# Adobe Experience Cloud發行說明- 2020年5月

![橫幅](/assets/experience-cloud-banner-3.png)

此頁面主要說明 [!DNL Adobe Experience Cloud] 的新功能、修正項目和重要注意事項。解決方案的發行日期可能不盡相同。請時常返回查看最新更新。

>[!NOTE]
>
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。

**發行日期：2020 年 5 月**

最新更新：**2020 年 5 月 21 日**

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**更新日期：2020年5月21日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html) (Target 說明頁面連結)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) (Primetime 說明頁面連結)

需要協助嗎？請造訪 [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home)，尋找 Adobe 策畫的課程、技術文件、快速解答、社群見解，以及由講師授課的培訓課程。

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

**統一產品網域**

Adobe 持續更新網域和介面標題，以統一及提升您使用所有 Experience Cloud 應用程式的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會改變目前的工作流程。

更新包括：

* 新應用程式 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * 瀏覽器支援：支援的瀏覽器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera] (最新版本)。**注意：**&#x200B;雖然 Experience Cloud 介面可支援這些瀏覽器，但個別解決方案可能不會支援所有瀏覽器。(例如 [Analytics](https://docs.adobe.com/content/help/zh-Hant/analytics/admin/sys-reqs.translate.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/zh-Hant/target/using/implement-target/before-implement/supported-browsers.translate.html) 不支援 [!DNL Safari])。
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
| 客戶歷程分析 | `experience.adobe.com/platform/analytics` |
| Adobe Campaign 控制面板 | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| 管理工具 (測試版) | `experience.adobe.com/admin` |

>[!NOTE]
>
>[!UICONTROL Marketing Cloud Assets] 選取器中的舊版篩選器&#x200B;**[!UICONTROL 「展示板和系列」]**&#x200B;即將終止服務。

## ![圖示](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

[!DNL Experience Platform,] 的發行說明，內容包括 [!DNL Experience Platform Launch,] [!UICONTROL 歷程協調]、[!UICONTROL Offers]、[!UICONTROL People]、[!UICONTROL Places]、[!UICONTROL Mobile Services]、安全性公告。

### 介面增強功能

更新日期：**2020 年 5 月 15 日**

[!DNL Adobe Experience Platform] 即將推出網域和標題列更新，除了提升您的使用體驗，也與其他 Experience Cloud 應用程式統一。更新包括：

* 在不同組織或應用程式之間更輕鬆地切換。
* 提升使用者說明品質，包括「說明」功能表中的精選文章和內容相關文件。
* 允許使用者提供 Experience Platform 和檔案支援票證的相關意見。

如需詳細資訊，請參閱 [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)。

### 客戶屬性 - 新文件

更新日期：**2020 年 5 月 15 日**

* [CCPA (加州消費者隱私保護法) 的客戶屬性支援](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/customer-attributes/ccpa.html)
* [GDPR (一般資料保護規範) 的客戶屬性支援](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/customer-attributes/gdpr.html)

### 歷程協調 {#journey}

不論客戶處於哪個歷程階段，Adobe Experience Platform 能聰明地即時預測每個人的需求，以便能大規模協調不同體驗管道的客戶歷程。

* [文件](https://docs.adobe.com/content/help/zh-Hant/journeys/using/journey-orchestration-home.html)
* [發行說明](https://docs.adobe.com/content/help/zh-Hant/journeys/using/release-notes/release-notes.html)
* [作法影片](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### 其他 Experience Platform 發行資訊

* [Experience Platform Launch 發行說明](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)
* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [安全性佈告和諮詢](https://helpx.adobe.com/tw/security.html) (所有 Adobe 產品)

## ![圖示](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Customer Journey Analytics 的新功能](#cust-journey)
* [Adobe Analytics 的新功能](#aa-features)
* [Analytics管理員的重要注意事項](#aa-notices) (**於2020年5月21日更新**)
* [Adobe Analytics修正](#aa-fixes) (**2020年5月21日更新**)
* [AppMeasurement](#appm)
* [全新 Analytics 教學課程](#tutorials-analytics)

### Customer Journey Analytics 的新功能{#cust-journey}

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]：全域可用性 | 使 EMEA 和 APAC 的客戶得以使用 [!UICONTROL Customer Journey Analytics]。 |
| [!UICONTROL Customer Journey Analytics]：支援 [!UICONTROL Adobe Experience Platform 沙箱] | 允許選取特定的 [!UICONTROL Adobe Experience Platform 沙箱]，以便建立 CJA 連線。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics-platform/using/cja-connections/create-connection.html) |

### Adobe Analytics 的新功能 {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| 功能 | 說明 |
| -----------| ---------- |
| Analytics 對 [!UICONTROL Adobe Experience Platform 邊緣網路]提供支援 | 可讓您使用單一標記將資料傳送至多個 Adobe 解決方案，例如 Adobe Analytics、Adobe Target、Adobe Audience Manager、Adobe Experience Platform Data Lake、Unified Profile 和 Experience Cloud ID 服務。[更多詳情...](https://docs.adobe.com/content/help/en/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Adobe Analytics 儀表板] | [!UICONTROL Adobe Analytics 儀表板]是一款行動應用程式，可讓使用者隨時隨地存取 Adobe Analytics 的深入分析。此應用程式適合需要隨處存取關鍵量度的高階管理者。這能讓您存取精心設計的互動式計分卡，且在 iOS 和 Android 作業系統上都能使用。[更多詳情...](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace][!UICONTROL ：從空白狀態自動建立自由表格] | 過去，您必須先新增[!UICONTROL 自由表格]，無法直接將元件放入空白專案或空白面板中。現在，您可以直接將元件放入空白的專案或面板中，由系統自動以建議的格式為您建立[!UICONTROL 自由表格]。此外，新版也已改善混合元件類型 (例如維度和量度) 一併放入空白自由表格時的處理方式。 |
| [!UICONTROL 「功能存取層級」]頁面新增 [!UICONTROL Adobe Analytics Package] | 您現在可以在&#x200B;**[!UICONTROL 「管理員]** > **[!UICONTROL 公司設定]** > **[!UICONTROL 功能存取層級」]**&#x200B;中，檢視您公司有權使用的 [!UICONTROL Adobe Analytics Package] (SKU)。 |
| 改善協助工具 | Adobe Analytics 團隊改善 Analysis Workspace 的幾項協助工具，包括改善鍵盤瀏覽、顏色對比和螢幕助讀程式支援。 |

#### Adobe Analytics修正(#aa-fix)

* Adobe將「逗 [!UICONTROL 留時間] 」量度變更為從未在計算中包含「未指定」。 這表示，無論使用者介面是否指出包含「未指定」，我們都會在「逗留時間」計算中設定特殊例外，一律排除「未 [!UICONTROL 指定」] 。 因此，即使您設定包含「逗留時間  」量度的報表來包含「未指定」，它仍會傳回「未指定」行項目的0逗留時間。 請注意，這可能會變更「報告與分析」以及「報告API v1.4」中的歷史報告。 (AN-197958)
* 已修正此問題：例項／瀏覽／訪客未計入「逗留時間」度量的分 [!UICONTROL 母] 。  當在同一秒內追蹤沒有維度值(例如 [!UICONTROL Pagename])的點擊時，就會發生這種情況。 (AN-211074)
* 修正 Audience Manager 中導致 [!DNL Analytics] 區段資料遺失的問題。(AN-206221)
* 修正[!UICONTROL 「資料來源」]處理時顯示錯誤日期的問題。(AN-213604)
* 修正分類檔案無法正確上傳至 FTP 的問題。(AN-214102)
* 修正 API 方法 `Segments.Get` 未傳回完整回應的問題。(AN-206210)
* 修正表格明細項目在 [!DNL Workspace] PDF 下載內容中轉換為特殊字元的問題。(AN-196153)
* 修正 Adobe Analytics API 1.4 呼叫 `visattrcustomeridcustomerattributes` 無法正常運作的問題。(AN-186873)
* 修正資料顯示於報表中，但未顯示於[!UICONTROL 「資料摘要」]的問題。(AN-211923)
* 修正[!UICONTROL 「產品設定檔」]權限無法複製的問題 。(AN-211113)
* 修正使用者無法以 Federated ID 登入 [!UICONTROL Report Builder] 的問題。(AN-207750)
* 修正 [!UICONTROL AdWords] 資料無法顯示於 [!UICONTROL Advertising Analytics] 的問題。(AN-213249)
* 修正趨勢檢視未顯示分類資料的問題。(AN-212761)
* 修正[!UICONTROL 「區段管理器」]中發佈區段計數有誤的問題。(AN-213374)
* 修正[!UICONTROL 「計算量度編輯器」]中&#x200B;**[!UICONTROL 「將向上趨勢顯示為...」]**&#x200B;選項的問題 - 套用篩選器時無法運作。(AN-214223)
* 修正[!UICONTROL 分類]匯入和匯出的多個問題。(AN-213488、AN-215309、AN-216345、AN-215307、AN-216671)
* 修正[!UICONTROL 分類規則產生器]的多項問題。(AN-213826、AN-213550、AN-213095)
* 修正[!UICONTROL 資料來源]在處理方面的問題。(AN-218083、AN-213604、AN-214102、AN-215485、AN-215339、AN-212911、AN-217551、AN-217947、AN-219018、AN-214691、AN-218401)
* 修正 FTP 連線問題。(AN-115525)
* 修正多項 [!DNL Analytics] [!UICONTROL 資料摘要]問題。(AN-176769、AN-160480、AN-211923、AN-204286、AN-212977、AN-214528、AN-215080、AN-217784、AN-219093、AN-218817、AN-217798、AN-218267、AN-218382)
* 修正 [!UICONTROL Data Warehouse] 要求的問題。(AN-181836)
* 修正在 PDF 下載的 [!UICONTROL Workspace] 專案中，值會轉換為特殊字元的問題。(AN-196153)
* 修正無法在 [!UICONTROL Admin Console] 中複製[!UICONTROL 「產品設定檔」]權限的問題。(AN-211113)
* 修正計算量度中時間格式會因負值而損壞的問題。(AN-210900)
* 修正使用者無法對靜態列量度變更[!UICONTROL 歸因模型]的問題。(AN-207872)
* 修正[!UICONTROL 排程報表]產生器停滯於已排入佇列狀態的問題。(AN-215317)
* 修正 [!UICONTROL ExactTarget Data Connector]。(AN-210794)
* 修正[!UICONTROL 大量擷取 API] 的延遲問題。(AN-210165)
* 修正使用者無法使用 Federated ID 登入 [!UICONTROL Report Builder] 的問題。(AN-207750)
* 修正 [!UICONTROL Advertising Analytics] 中導致 [!DNL Google AdWords] 資料無法顯示的問題。(AN-213249)
* 修正記錄中無法顯示[!UICONTROL 「已檢視 Workspace 專案」]事件的問題。(AN-214134)
* 修正在變更 [!UICONTROL Workspace] 的日期範圍及選取&#x200B;**[!UICONTROL 「套用至所有面板」]**&#x200B;時所發生的問題。某些面板中的日期並未變更。(AN-214944)
* 修正無法建立或編輯警報的問題。(AN-215920)
* 修正 [!UICONTROL Workspace] 中所有動態日期範圍因一週的第一天偶爾會從星期一切換為星期日，而導致顯示錯誤日期的問題。(AN-218835)

#### 其他 Adobe Analytics 修正項目

AN-101871、AN-115525、AN-123869、AN-152580、AN-160480、AN-178128、AN-186907、AN-199299、AN-201342、AN-201397、AN-204286、AN-204518、AN-206045、AN-206948、AN-208607、AN-209486、AN-210743、AN-211550、AN-211539、AN-211826、AN-211943、AN-212130、AN-212151、AN-212653、AN-212673、AN-212709、AN-212833、AN-212961、AN-212977、AN-213095、AN-213422、AN-213450、AN-213490、AN-213752、AN-213827、AN-214094、AN-214153、AN-214214、AN-214234、AN-214253、AN-214255、AN-214343、AN-214355、AN-214401、AN-214427、AN-214528、AN-214642、AN-214691、AN-214772、AN-214793、AN-214924、AN-215017、AN-215080、AN-215212、AN-215312、AN-215377、AN-215402、AN-215545、AN-215905、AN-215963、AN-216447、AN-216676、AN-216880、AN-216999、AN-217245、AN-218450、AN-218899、AN-219487、AN-219677

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 改善Analysis Workspace可用性的備援 | 2020年5月21日 | 為確保分析工作區的可用性，我們新增次要CDN（內容傳送網路）以改善備援。 應將下列URL添加到任何必要的網路防火牆白名單中：<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| 變更 [!UICONTROL Workspace] 計算[!UICONTROL 輸入/結束]次數的方式 | 2020 年 4 月 7 日 | 自 2020 年 3 月起，[!UICONTROL Analysis Workspace] 已變更&#x200B;_「無」_&#x200B;值與[!UICONTROL 輸入/結束]動作的互動方式。由於您現在可以在 [!UICONTROL Analysis Workspace] 中開啟或關閉&#x200B;_「無」_，因此我們會在使用者輸入或結束後套用&#x200B;_「無」_，但 (eVars) 以往都是在輸入或結束之前就先套用。例如，假設造訪事件的第一次點擊未輸入 eVars 的值，但第二次點擊則有輸入。在 [!UICONTROL Reports &amp; Analytics] 中，第一次點擊的輸入會顯示為&#x200B;_「未指定」_，但在 [!UICONTROL Analysis Workspace] 中則會顯示第二次點擊的值。 |
| **[!UICONTROL 「轉換級別」]**&#x200B;設定確定汰除 | 2020 年 3 月 3 日 | **[!UICONTROL 「管理工具]** > **[!UICONTROL 報表套裝]** > **[!UICONTROL 一般帳戶設定」]**&#x200B;中的[「轉換級別」](https://docs.adobe.com/content/help/zh-Hant/analytics/admin/admin-tools/general-acct-settings-admin.html)設定早已停止作用，預計於 2020 年 3 月 12 日從介面中移除。 |
| **[!UICONTROL 控制面板封存]**&#x200B;確定汰除 | 2020 年 3 月 27 日 | 自 2020 年 10 月起，[!UICONTROL Reports &amp; Analytics] 中&#x200B;**[!UICONTROL 「管理控制面板」]**&#x200B;底下的&#x200B;**[!UICONTROL 「檢視封存」]**&#x200B;設定將不再提供使用。 |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 開始移動至新網域 - `https://experience.adobe.com/analytics.`<br>**注意：**凡是使用 Adobe ID 或 Enterprise ID 存取 Analytics 的所有使用者，均適用這項變更。<ul><li>這項網路異動可能會在 Safari 中載入 Analytics 時造成 Cookie 問題。在 「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Analytics 在這個新的 Adobe Experience Cloud 網域中運作。[!DNL Safari]只有 [!DNL Safari] 使用者會受此問題影響，使用其他瀏覽器不會發生問題。</li><li>網域變更可能會導致 [!UICONTROL Activity Map] 在[部分特定情況下](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/activity-map/activity-map.html)停止運作。</li></ul> |
| 終止服務 - Analytics Legacy API | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy Oauth 驗證 (Oauth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy Oauth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 若為倫敦和新加坡的客戶，我們將不再於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間支援資料代理。<br/><ul><li>如果您是在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果您是在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 終止 Ad Hoc Analysis 服務 | 2018 年 8 月 6 日 | Adobe 已宣佈有意終止 Ad Hoc Analysis 服務。我們將會在確定後公佈服務終止日期。如需詳細資訊，請造訪[探索 Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-updates.html)。2.20.0 版已於 2020 年 3 月 5 日發行。

### 全新 Analytics 教學課程{#tutorials-analytics}

| 內容 | 說明 |
| -----------| ---------- |
| [Analysis Workspace 培訓教學課程範本](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | [!UICONTROL Analysis Workspace] 培訓教學課程會逐步引導您了解在 [!UICONTROL Workspace] 中建立第一個專案的常用術語和步驟。 |
| [新增前一個月和前一年的趨勢比較](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | 了解如何套用自訂日期範圍，以針對 [!UICONTROL Analysis Workspace] 中的任何量度建立每月和每年的趨勢比較。 |
| [Analysis Workspace 深色模式擴充功能](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | 啟用 Dark Reader Chrome 擴充功能，將 Analysis Workspace 變暗。 |
| [定義自訂調色盤的色彩滴管擴充功能](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | 了解如何使用 ColorPick EyeDropper Chrome 擴充功能，輕鬆找出您在 [!UICONTROL Workspace] 專案中自訂調色盤所需的十六進位值。 |

#### Analytics 說明資源

* [Adobe Analytics 教學課程](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics 產品文件](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 的新功能、修正項目、說明文件和教學課程。

### 使用者介面更新

Audience Manager 即將推出網域和標題列更新，除了提升您的使用體驗，也與其他 Experience Cloud 應用程式統一。

* 在不同組織或應用程式之間更輕鬆地切換。
* 提升使用者說明品質，包括「說明」功能表中的精選文章和內容相關影片。
* 允許使用者提供 Experience Platform 和檔案支援票證的相關意見。
* 更容易上手的新 URL 模式。將書籤更新至新 URL：`experience.adobe.com/audience-manager`。

這些更新僅適用於使用 Adobe ID 登入的使用者。若要切換成以 Adobe ID 登入，請參閱[管理 Experience Cloud 使用者和產品](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/manage-users-and-products/admin-getting-started.html)。

### Adobe Audience Manager 的新功能和修正項目

| 功能 | 說明 |
| -----------| ---------- |  
| [大量管理工具 (BAAAM)](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | 我們上傳了新的大量管理工具工作表，其功能包括：<br><br><ul><li>讓您列出特徵階層中的子資料夾 (AAM-51528)</li><li>在系統提示您輸入與 CRM ID (跨裝置 ID) 相關聯的特徵時擷取量度 (AAM-52135)</li><li>修正韓文字元的語言編碼問題 (AAM-AAM-54006)</li></ul> |

**修正項目**

* 修正趨勢報表在資料夾中含有大量特徵時會發生逾時的問題。(AAM-54457)
* 修正客戶在特徵建立/編輯工作流程中無法看見[!UICONTROL 運算式產生器]的問題。(AAM-54255)
* 修正 UI 中錯誤訊息只會短暫顯示，客戶來不及閱讀即消失的問題。例如，當客戶嘗試刪除對應至目的地的區段時，就會發生此問題。(AAM-54031)
* 修正客戶不再使用 [!UICONTROL Audience Marketplace] 後仍會收到每月發票電子郵件的問題。(AAM-54602)
* 修正客戶從 UI 中其他位置點選特定特徵時，畫面顯示毀損連結而非特徵的問題。(AAM-54768)
* 修正在編輯特徵運算式模式中按 ENTER 鍵時，頁面會重新整理，而且特徵運算式會遺失的問題。(AAM-54210)
* 整個介面的協助工具有多處改良。(AAM-47781、AAM-49075、AAM-49360、AAM-49361、AAM-49376、AAM-50432、AAM-52550、AAM-54660).

### 全新 Audience Manager 教學課程 {#tutorials-aam}

| 內容 | 說明 |
| -----------| ---------- |  
| [了解 Audience Manager 的基本術語和概念](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | 這段影片會說明開始使用 Audience Manager 時所需了解的一些基本術語和概念，包括訊號、特徵、區段等。 |
| [了解 Audience Manager 的資料流程](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | 此影片會說明流入、流經和流出應用程式的資料流程，以協助您了解 Adobe Audience Manager。 |
| [Audience Manager - DMP 概觀](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | 說明跨管道個人化的主要挑戰，並解說 Adobe Audience Manager 如何提供客戶歷程。此外，還會說明哪些資料類型可在 Audience Manager 上架，並介紹與 Audience Manager 整合的廣告技術生態系合作夥伴。 |
| [Audience Manager 使用案例](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | 此影片中，我們會介紹 4 種常見的 Audience Manager 使用案例，並說明相關的最佳作法。 |
| [了解 Audience Manager 的跨裝置量度](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | 此影片中，我們會探討裝置設定檔與跨裝置設定檔之間的差異，並說明 UI 中的數字與不同設定檔類型如何對應。 |
| [了解 Audience Manager 的預測對象](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | 此影片中，我們會說明何謂 Audience Manager 預測對象、詳細解說其運作方式，並提供使用案例。 |
| [在 Audience Manager 中設定預測對象及製作報表](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | 此影片中，我們會在 Audience Manager 介面中逐步設定預測對象。我們也會呈現顯示模型結果的報表。 |

## ![圖示](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品更新

* **AEM 雲端服務**

   * 資產處理的改進與修正項目。透過資產重新處理對話方塊，使用者可進一步控制、選取特定的處理設定檔，以及選擇是否應觸發後續處理工作流程。
   * Dynamic Media 資產擷取效能提升。

### 自助資源

* **自動表單轉換服務 - AFC-2020.03.1 版**

   當您安裝最新的連接器時，會有新的選項可以使用：

   **[!UICONTROL 自動偵測邏輯區段]**：您可以使用[!UICONTROL 「自動偵測邏輯區段」]選項來放置頁面層級面板 (以頁碼為基礎的面板)，並僅建立邏輯面板。這個選項還可將不屬於任何具有前置邏輯區段之區段的欄位，與橫跨兩個相鄰頁面之邏輯區段的欄位合併成一個邏輯區段。例如，如果邏輯區段中有些欄位位於第一頁底部，有些位於第二頁頂端，這些欄位都能合併成一個邏輯區段。

* **Dynamic Media 不支援的影像格式**

   [!UICONTROL Dynamic Media] 不支援點陣影像檔案格式子類型的相關資訊。

   請參閱 [Dynamic Media 不支援的點陣影像格式](https://docs.adobe.com/content/help/zh-Hant/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media)。

* **內容片段**

   提供 [AEM Assets HTTP API 支援內容片段](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)，以及[自訂和延伸內容片段](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)與[內容片段的演算設定元件](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html)等相關資訊。

* **AEM Experience League 社群**

   與 [AEM Experience League 社群](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)交流：向其他使用者與 AEM 專家提問、瀏覽對話，並能分享您的秘訣與專業知識！

* **AEM 電子報**

   [!UICONTROL Experience League] 的 AEM 電子報可協助您快速熟悉 AEM，並立即開始實現其價值。以下是最新的電子報：

   * [第 30 期](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)：Experience Manager 現在能以雲端服務形式使用。
   * [訂閱](https://adobeeventsonline.com/AEM/2017/NL/Optin/) Experience Insider 電子報。
   * 前往 Adobe Experience Manager 6.5「學習與支援」頁面的[「AEM 資源」](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)區段，即可檢視電子報封存檔。

### 全新 Experience Manager 教學課程

| 內容 | 說明 |
| -----------| ---------- |  
| [設定本機 AEM 執行階段](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) 可透過 [!UICONTROL AEM 雲端服務] SDK 的 [!UICONTROL Quickstart Jar] 在本機上執行。如此一來，開發人員就能在將自訂程式碼、設定和內容送交來源控制項前，先行部署和測試，之後再部署至 [!UICONTROL AEM 雲端服務]環境。 |
| [開始使用 AEM Assets](https://video.tv.adobe.com/v/33624?captions=chi_hant) | 說明商業使用者如何開始使用 AEM Assets 的簡介影片。 |
| [中繼資料的資料夾結構](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | 藉由中繼資料的資料夾結構，使用者可管理及檢閱與資產資料夾本身相關聯的中繼資料，而非直接管理及檢閱資產。 |
| [標記](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | 標記是在資產的資料夾階層內管理資產時不可或缺的工具。要讓使用者在 AEM 中探索及組織資產，建立標記分類法是很重要的工作。 |
| [中繼資料設定檔](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | 中繼資料設定檔可讓預設中繼資料自動套用至資產資料夾內的資產。這有助於減輕 AEM 使用者管理中繼資料的負擔，並提高中繼資料的一致性。 |
| [中繼資料結構](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | 中繼資料結構會定義在 AEM 中公開資產中繼資料的介面。這段影片會說明套用資產時搭配使用的方法。 |

### 其他資源

* [AEM 雲端服務發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM 雲端服務文件](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)
* [AEM 6.4 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-4.html)
* [AEM 6.3 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-3.html)
* [AEM 6.2 學習與支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/tw/experience-manager/cloud-manager/user-guide.html)
* [AEM Cloud Manager 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [舊版 AEM 文件](https://helpx.adobe.com/tw/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/zh_TW/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![圖示](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Campaign Standard

* [Adobe Campaign Standard 20.3 版本](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Campaign 控制面板

| 功能 | 說明 |
| -----------| ---------- |  
| GPG 金鑰管理 | 在行銷例項上安裝及/或產生 GPG 金鑰，以便將 Campaign 傳送的資料加密，並為傳入的資料解密。 |
| CNAME 子網域的憑證管理 | 現在，控制面板可讓您續訂已透過 CNAME 方法委派之子網域的 SSL 憑證。 |

### 全新 Campaign 教學課程

* 全新 Campaign Standard 教學課程

| 內容 | 說明 |
| -----------| ---------- |  
| [控制面板 - Google TXT 記錄管理](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | 了解如何使用 Campaign 控制面板，將 Google TXT 網站驗證記錄新增至您將電子郵件傳送至 GMAIL 地址所需的所有子網域。 |
| [使用外部 API 活動設定及執行工作流程](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | 了解如何使用「外部 API」活動呼叫外部 REST API 端點。 |
| [開始使用 Android 的推播通知 - 教學課程](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | 本教學課程說明使用 Campaign Standard 和 Android 應用程式設定推播通知所需執行的步驟。 |

* 全新 Campaign Classic 教學課程

| 內容 | 說明 |
| -----------| ---------- |  
| [Snowflake 巨量資料管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | 了解如何在 Adobe Campaign Classic 中使用 Snowflake 連接器。 |
| [控制面板 - Google TXT 記錄管理](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | 了解如何使用 Campaign 控制面板，將 Google TXT 網站驗證記錄新增至您將電子郵件傳送至 GMAIL 地址所需的所有子網域。 |

### Campaign 說明資源

* Adobe Campaign Standard：[說明中心](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/campaign-standard-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [作法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic：[說明中心](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/release-notes/latest-release.html) - [作法影片](https://docs.adobe.com/content/help/zh-Hant/campaign-learn/campaign-classic-tutorials/overview.html)- [最新文件更新內容](https://docs.adobe.com/content/help/zh-Hant/campaign-classic/using/documentation-updates.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/release-notes.html)

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Advertising Cloud DSP 新功能](#adcloud-dsp)
* [Advertising Cloud Search 新功能](#adcloud-search)

### Advertising Cloud DSP 新功能 {#adcloud-dsp}

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL Campaign Classic] 和 [!UICONTROL Campaign 測試版] | 針對詐騙和品牌安全性推出 IAS 測量設定 (您可以選擇為個別促銷活動設定)，現在包含測量 VAST 和 VPAID 庫存的相關選項。 |
| [!UICONTROL Campaign 測試版] | 資料視覺效果和頁面載入時間均有所改善。 |
|  | 現在，您可以在所有頁面下載以最新篩選器和檢視為基礎的 Excel 報表。 |
|  | (在 5 月 22 日的版本中) 新量度包括「所有時間」量度、「最新間隔交付」、「日期特定 OTS」。 |
| [!UICONTROL 黑名單] | 預測系統現在會自動使用廣告商或帳戶層級的黑名單。使用者不再需要自行將黑名單貼到位置設定。 |
| [!UICONTROL 庫存交易] | (內部測試版) 簡化的全新表單可讓您快速設定、編輯「交易 ID 收件匣」中未提供的供應端平台 (SSP) 交易，並對其進行疑難排解。 |
|  | 現在，當您在「交易 ID 收件匣」中接受程式化保證交易的套件時，系統會提醒您為每個交易 ID 建立預設位置。 |

### [!UICONTROL Advertising Cloud Search] 新功能 {#adcloud-search}

| 功能 | 說明 |
| -----------| ---------- |
| [!UICONTROL 行銷活動] | (Google Ads 帳戶；測試版服務) 從 5 月底開始，Advertising Cloud Search 可將您 Google Gmail 顯示促銷活動和 Google Smart Shopping 促銷活動的資料與 Google Conversions 同步，以利追蹤和製作報表。此服務也可讓您在「促銷活動」和「廣告群組」檢視中，編輯現有促銷活動的促銷活動設定和廣告群組設定。此為選用服務。服務正式推出後，使用者將需支付額外費用。<br>如需此服務的詳細資訊 (包括測試版計劃和未來服務範圍)，請洽詢您的 Adobe 客戶經理。 |

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![圖示](/assets/marketo.png) [!DNL Marketo] {#marketo}

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
