---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 5246ec08b9a04fcbdfff401dc214256185faaf2d

---


# Adobe Experience Cloud 發行說明 - 2020 年 3 月

![橫幅](/assets/experience-cloud-banner-3.png)

[!DNL Adobe Experience Cloud] 中的新功能及修正。

>[!IMPORTANT]
>此頁面含有搶先版內容，於預計發行前可能會有所變更。

>[!NOTE]
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期：2020 年 3 月**

上次更新：2020 年 3 月 11 日

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面與核心服務](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) - 發行日期：**2020 年 3 月 12 日**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (前往解決方案說明的連結)
* [新文件與教學課程](#selfhelp)

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

(特定產品的發行日期可能有所不同。)

## ![圖示](/assets/adobe.png) Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

**新功能**

* 使用 Adobe ID 即可訂閱事件通知，並擁有更精細的控制能力，包括可針對產品和附加元件層級選擇所需通知。在 Experience Cloud 產品中尋找這項新功能，其自助訂閱流程會顯示您要訂閱之產品和服務的細項。此增強功能應可大幅減少您收到的通知數量，並讓通知內容與您使用的產品和功能更為相關。若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 依子方案提供個人化自助訂閱 | <ul><li>依產品項目或 Experience Cloud 產品附加元件提供自助訂閱。</li><li>收到的事件通知會與您的產品和產品偏好相關。</li></ul> |
| 根據使用者偏好提供個人化體驗 | <ul><li>電子郵件通知會根據瀏覽器設定提供您偏好的時區設定。</li><li>依所有選取的偏好設定，在訂閱/取消訂閱時透過電子郵件傳送確認函。</li></ul> |
| 事件訊息的傳送作業更完善 | <ul><li>事件歷史記錄會根據事件更新的時間順序排序。</li><li>主要/次要的結案問題新增事件的解決時間戳記。</li></ul> |

## ![圖示](/assets/experience-cloud.png) Experience Cloud 介面與核心服務 {#ecloud}

Experience Cloud 介面的新功能和修正項目，包括管理和核心服務 (客戶屬性、對象、觸發器、Cookie 等)。

| 功能 | 發行日期 | 說明 |
| ----|----|---- |
| 管理工具 - 檢視使用者詳細資訊 | 2020 年 2 月 26 日 | 管理員可以在新的管理工具中，檢視所有 Experience Cloud 使用者及其詳細資訊，並可將清單加以排序及篩選。使用者詳細資訊包括使用者的產品存取情形、角色，以及上次存取的資訊。如需詳細資訊，請參閱 [Experience Cloud 管理工具](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html)說明。 |

### 統一產品網域

Adobe 正在更新網域和介面標題，以統一及提升您在所有 Experience Cloud 應用程式中的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會變更您目前的工作流程。

更新包括：

* 新解決方案 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * 瀏覽器支援：支援的瀏覽器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera] (最新版本)。**注意：**&#x200B;雖然 Experience Cloud 介面可支援這些瀏覽器，但個別解決方案可能不會支援所有瀏覽器(例如 [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 不支援 [!DNL Safari])。
   * (僅限 [!DNL Safari]) 網域變更可能導致 [!DNL Safari] 發生 Cookie 問題。在 [!DNL Safari] 的「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Experience Cloud 在這個新的網域中運作。
* 在組織或不同應用程式之間更輕鬆地切換。
* 改良產品說明：[!UICONTROL Experience League] 已整合至產品中，因此搜尋說明內容時，搜尋範圍會包含社群論壇和影片內容。這項變更可讓您輕鬆存取更多內容，協助您充份運用 Experience Cloud。此外，按一下&#x200B;**[!UICONTROL 「說明]** > **[!UICONTROL 意見回饋」]**&#x200B;即可回報問題，或與 Adobe 分享您的想法。
* 改良通知：[!UICONTROL 「通知」]下拉式選單現在提供兩個標籤，其中一個是您的產品通知，另一個是全球產品公告。

**注意：**[!UICONTROL 「摘要」]頁面已於 2020 年 1 月汰除。請參閱產品中的淘汰通知。

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) 說明。

## ![圖示](/assets/platform.png) Experience Platform {#platform}

[!UICONTROL Experience Platform]、[!UICONTROL Experience Platform Launch]、[!UICONTROL 身分服務]、Journey Orchestration、Mobile Services 和安全性佈告欄的發行說明。

* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [歷程協調](#journey)
* [Mobile Services 與 Mobile SDK](#mobile)
* [安全性佈告和諮詢](https://helpx.adobe.com/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

### 歷程協調 {#journey}

不論客戶處於哪個歷程階段，Adobe Experience Platform 能聰明地即時預測每個人的需求，以便能大規模協調不同體驗管道的客戶歷程。

第 1 季版本已發佈。[深入了解](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

#### Journey Orchestration 的其他資源

[文件](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services 與 Mobile SDK {#mobile}

**iOS v4.19.1**

* 一般 – 解決追蹤呼叫的內容資料中列舉 [!UICONTROL Swifte] 時可能導致當機的問題。
* [!DNL Target] – [!DNL Target] 工作階段 ID 現在會在傳送至 Adobe Analytics 的內部 [!UICONTROL Analytics-for-Target] 點擊中，以內容資料參數 `a.target.sessionId` 的形式新增。

**Android v4.18.1**

* [!DNL Target] – [!DNL Target] 工作階段 ID 現在會在傳送至 Adobe Analytics 的內部 [!UICONTROL Analytics-for-Target] 點擊中，以內容資料參數「a.target.sessionId」的形式新增。

## ![圖示](/assets/analytics.png) [!DNL Analytics] {#analytics}

發行日期：**2020 年 3 月 12 日**

Adobe Analytics 的新功能和修正項目：

* [Adobe Analytics 的新功能、增強功能和修正項目](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 的新功能、增強功能和修正項目 {#aa-features}

* **在[!UICONTROL Analysis Workspace ]**中使用多個報表套裝：您現在可以將多個報表套裝的資料匯入同一個[!UICONTROL Analysis Workspace]專案，在並排的面板中清楚檢視。[更多詳情...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**：此功能可讓您在 8 小時內將區段發佈到 Experience Cloud (不像之前需要 48 小時的處理時間)。[更多詳情...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - 訓練教學課程範本**：這個全新的標準範本會逐步引導您了解常用術語，以及在「工作區」中首次建立分析的步驟。若新使用者的清單中沒有其他專案，這會顯示為[!UICONTROL 「新增專案」]模組中的標準範本，取代目前現有的範例專案。

#### 修正

* 修正 [!UICONTROL Reports &amp; Analytics] 中導致 `.xls` 報表無法下載的問題。此問題會影響使用美元和歐元以外貨幣的客戶。(AN-206541、AN-204008)
* 新殼層修正了與切換 Experience Cloud 組織相關的好幾個客戶問題。(AN-200844、AN-186920)
* 修正對&#x200B;_「未指定」_&#x200B;明細項目 (或其他報表明細項目) 執行劃分，而劃分的搜尋篩選條件中未包含&#x200B;_「未指定 (無)」_&#x200B;時，劃分不會傳回任何結果的問題。
* 修正使用分類維度時，登入與退出量度總計與劃分明細項目總計不符的問題。
* 修正歸因 IQ 中，首次接觸和上次接觸模型無法正確計算部分現成維度中某些明細項目評分的問題。
* 修正依另一個日期維度劃分某日期維度時，系統傳回錯誤結果的問題。
* 修正在分類維度報表中，將登入或退出量度套用至「未指定」時，有時系統會計算錯誤的問題。

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| **[!UICONTROL 「轉換級別」]**&#x200B;設定確定汰除 | 2020 年 3 月 3 日 | **[!UICONTROL 「管理工具]>[!UICONTROL 報表套裝]>[!UICONTROL 一般帳戶設定」]**&#x200B;中沒有作用的[「轉換級別」](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html)設定，預計於 2020 年 3 月 12 日從 UI 中移除。 |
| **[!UICONTROL 控制面板封存]**&#x200B;確定汰除 | 2020 年 3 月 3 日 | 自 2020 年 3 月 12 日起，[!UICONTROL Reports &amp; Analytics] 中&#x200B;**[!UICONTROL 「管理控制面板」]**&#x200B;底下的&#x200B;**[!UICONTROL 「檢視封存」]**&#x200B;設定將不再提供使用。 |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 開始移動至新網域 - `https://experience.adobe.com/analytics.`<br>**注意：**凡是使用 Adobe ID 或 Enterprise ID 存取 Analytics 的所有使用者，均適用這項變更。<ul><li>這項網路異動可能會在 Safari 中載入 Analytics 時造成 Cookie 問題。在 「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Analytics 在這個新的 Adobe Experience Cloud 網域中運作。[!DNL Safari]只有 [!DNL Safari] 使用者會受此問題影響，使用其他瀏覽器不會發生問題。</li><li>網域變更可能會導致 [!UICONTROL Activity Map] 在[部分特定情況下](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)停止運作。</li></ul> |
| 終止服務 - Analytics Legacy API | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy Oauth 驗證 (Oauth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy Oauth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 若為倫敦和新加坡的客戶，我們將不再於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間支援資料代理。<br/><ul><li>如果您是在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果您是在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 臨機分析的EOL | 2018年8月6日 | Adobe宣佈打算終止臨機分析。 我們將會在確定後公佈服務終止日期。如需了解更多資訊，請造訪[探索 Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。 |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)。2.20.0 版已於 2020 年 3 月 5 日發行。

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 的新功能和更新：

| 功能 | 說明 |
| -----------| ---------- |
| [大量管理工具工作表](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | 新版工作表修正了部分客戶在 Windows 64 位元作業系統中建立演算模型時遇到的問題，目前已可供使用。若要下載最新版本，請前往[這裡](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/assets/BAAAM_V2_20200311.xlsm)。 |

### 修正和改良 {#aam-fixes-and-improvements}

* 修正客戶因缺少 RBAC 權限 [!UICONTROL VIEW_ALL_DESTINATIONS] 而無法更新區段名稱的錯誤。更新區段不需要 [!UICONTROL VIEW_ALL_DESTINATIONS] 權限。若需 RBAC 權限的詳細資訊，請參閱[管理 (RBAC 控制)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions)。(AAM-52760)
* 修正[「資料總管」](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html)中，根據[!UICONTROL 「資料總管」]訊號建立特徵時，部分客戶無法看見基本資訊區段內容及運算式產生器運算子的錯誤。(AAM-53130)
* 修正部分客戶無法載入 [!UICONTROL Audience Marketplace] 介面的錯誤。(AAM-52070)
* 修正[!UICONTROL 區段 API] 中，由於部分區段沒有說明，導致使用者嘗試存取這些區段時介面凍結，迫使使用者必須離開該頁面的錯誤。(AAM-53071)
* 整個介面的協助工具有多處改良。(AAM-48952、AAM-48969、AAM-48979、AAM-48993、AAM-49048、AAM-49057、AAM-49058、AAM-49392)

## ![圖示](/assets/aem.png) Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品更新

* **AEM 6.5.4.0**
AEM 6.5 Service Pack 4.0 (6.5.4.0，已於 2020 年 3 月 5 日發行) 是項重要更新，其中包括自 2019 年 4 月 AEM 6.5 全面發行以來所推出的新功能、重要客戶增強功能，以及效能、穩定性和安全性等方面的改善項目。
   * [Adobe Experience Manager 6.5 Service Pack 4 的新增功能](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [發行說明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms 發行交付項目](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4 Service Pack 8.0 (6.4.8.0，已於 2020 年 3 月 5 日發行) 是項重要更新，其中包括自 2018 年 4 月 AEM 6.4 全面發行以來所推出的重要客戶修正項目。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3 Service Pack 3 Cumulative Fix Pack 8 (6.3.3.8，已於 2019 年 3 月 5 日發行) 是項重要更新，其中包括自 2017 年 4 月 AEM 6.3 全面發行以來所推出的重要客戶修正項目。
   * [發行說明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4 Service Pack 6 (6.4.6，已於 2020 年 3 月 5 日發行) 變更了使用 [!UICONTROL Brand Portal 設定 AEM Assets 的方式。] 此外，此版本還包含其他增強功能和錯誤修正項目。
   * [發行說明](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### 自助資源

* **AEM 雲端服務 – 角色型權限**

   Cloud Manager 已預先設定各種角色並賦予適當權限。每個角色都具備與各角色相關聯的特定權限、預先設定的工作或權限。[角色型權限](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html)說明主題統整了各種可用功能和可執行這些功能的角色。

* **AEM 雲端服務 – Dispatcher**

   更新 [Dispatcher 和 CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) 以及 [Explicit Dispatcher 快取失效](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation)等章節，以清楚說明可用的選項及其使用方式。

* **使用 Brand Portal 設定 AEM Assets**

   現在您可透過 Adobe I/O 並使用 [!UICONTROL Brand Portal] 來設定 AEM Assets，其中 Adobe I/O 會擷取 IMS 代號，以便授權 Brand Portal 租用戶 。之前，使用者是透過[!UICONTROL 舊版 Oauth 閘道，在傳統介面中完成設定。]
請參閱[使用 Brand Portal 設定 AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html)。

* **AEM 雲端服務 - Dynamic Media 的智慧型裁切功能**

   當您使用 Dynamic Media 元件中的智慧型裁切功能時，AEM 雲端服務會提供新選項：

   **啟用外觀比例比對** - 選取此選項，讓 Dynamic Media 挑選最符合原始影像外觀比例的智慧型裁切輸出。
請參閱[使用智慧型裁切](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop)。

### 社群

* **AEM 技能建立網路研討會**

   * AEM Sites – 自 2020 年 3 月 17 日起，了解內容製作的基礎說明，以及 AEM Sites 的基本概念和操作。[立即註冊](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register)。
   * AEM Assets – 自 2020 年 3 月 19 日起，磨練您的數位資產管理專業技能，並了解 Brand Portal、[!UICONTROL Dynamic Media]、[!UICONTROL Asset Link] 等基本知識。[立即註冊](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register)。

### 其他資源

* [AEM 雲端服務](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [舊版 AEM 文件](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![圖示](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Campaign Classic

* [Campaign Classic 19.1.4 更新](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### 其他資源

* Adobe Campaign Standard：[文件](https://helpx.adobe.com/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文件](https://helpx.adobe.com/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![圖示](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

更新日期：2020 年 2 月 10 日 (適用於 2 月 8 日發行的版本)：

| 檢視 | 功能 |
|------|---------|
| [!UICONTROL 產品組合] | 您現在可新增 [!DNL Yahoo!] Yahoo! Japan Display Network (YDN) 促銷活動，將促銷活動預算和廣告群組層級的出價最佳化。廣告群組中的所有廣告會套用相同出價。產品組合模擬作業會包含 Japan Display Network 促銷活動的資料。 |
| [!UICONTROL 搜尋] > [!UICONTROL 大量表單] | 現在，您可以使用大量表單來建立、編輯及刪除 Google 回應式搜尋廣告 (RSA)。以前，您只能前往&#x200B;**[!UICONTROL 「搜尋]** > **[!UICONTROL 促銷活動」]**，透過標準促銷活動管理介面尋求支援 |
| [!UICONTROL 搜尋] > [!UICONTROL 促銷活動、報表] | 現在起，所有基本報表和實體層級的促銷活動管理檢視均已提供 Google Ads 的「顯眼程度」度量 `Impr. (Abs. Top) %` 和 `Impr. (Top) %`，不過購物廣告產品群組、[!UICONTROL 「促銷活動每日曝光比重」]和[!UICONTROL 「關鍵字每日曝光比重」]報表，以及標籤和限制檢視除外。 |

## ![圖示](/assets/magento.png) [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![圖示](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是銷售機會管理的完整解決方案，也適合 B2B 行銷人員使用，而透過該解決方案，他們可參與複雜購買歷程的每個階段，從中轉變客戶體驗。

### Marketo Engage 核心更新

發行日期：2020 年 2 月 21 日

* **_Microsoft Dynamics_在 Microsoft Flow Action 中的變更負責人：**&#x200B;直接從 Marketo Engage 變更銷售機會或連絡負責人。
* **增強 API 呼叫功能：**
   * 使用者管理 API
   * 自訂物件結構描述 API
   * 登陸頁面重新導向規則 API
* **表單描述元快取：**&#x200B;改善登陸頁面與表單。

如需詳細資訊，請參閱 [!DNL Marketo] [2020 年 2 月](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)的發行說明。

### 即將推出的功能

本季預計推出下列功能：

| 功能 | 說明 |
|------|---------|
| [!DNL Bizible] | <ul><li>全新的帳戶型分段</li><li>儲存控制面板專有的篩選器</li><li>將 Bizible 控制面板匯出為 PDF</li></ul> |
| Sales Connect | Compose Window 和 Command Center 更新/增強功能 |

### 公告

**Marketo Engage Success Center：**&#x200B;預計於 2020 年 2 月推出。Success Center 是產品內的說明中心，可讓您搜尋產品檔案和社群、啟動操作指南、存取採用內容等等。注意：此功能將會以測試版的形式在澳洲與紐西蘭推出，並預計於本季末在北美地區推出。

### 淘汰

* **資產 API「_method」參數：** 2020 年 9 月後，資產 API 端點將不再接受於 POST 主體中使用「_method」傳遞查詢參數，以略過 URI 長度限制。
* **Internet Explorer 支援淘汰：**&#x200B;從 2020 年 7 月 31 日推出的七月版開始，Marketo Engage 使用者介面將不再支援 Internet Explorer。

如需彙整資料和過往的發行說明，請參閱 [Marketo 發行說明](https://docs.marketo.com/x/CgA6Ag)。

## ![圖示](/assets/experience-cloud.png)新文件與教學課程 {#selfhelp}

近期的全新自助文章和影片。<!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| 解決方法 | 內容 | 說明 |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | 影片 - [建立多個類別和產品頁面](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | 了解如何使用 CIF 核心元件，建立最簡化的 Adobe Experience Manager (AEM) CIF 專案，作為客戶專案的起點。將主題和 CSS 樣式套用至元件，並檢查由原型產生的新 AEM CIF 專案。此外，也能了解 CIF 核心元件使用的 CSS 和 JavaScript 如何組織。 |
| [!UICONTROL AEM 表格] | 文章 - [使用 OKTA 驗證 AEM 作者](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | 了解如何在 OKTA 入口網站上設定您的應用程式，以及註冊新應用程式時通常會使用的相關設定。 |
| [!UICONTROL AEM Commerce] | 教學課程 - [自訂 CIF 核心元件](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | 檢視 CIF 核心元件及 AEM 一般所提供的數個不同擴充點。CIF 核心元件提供一套標準的 Commerce 元件，可加速推動整合了 Adobe Experience Manager (AEM) 和 Magento 解決方案的專案。 |
| [!DNL Adobe Campaign] - 對象目的地 | 影片 - [建立對象...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | 使用 Adobe [!UICONTROL Experience Platform 區段產生器]，在 Campaign Standard 中建立對象。您可以直接在 Adobe Campaign Standard 中，透過[!UICONTROL 「對象」]模組存取此功能。 |
| [!DNL Adobe Campaign] - 對象目的地 | 影片 - [在行銷工作流程中啟用 Adobe Experience Platform 對象](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | 了解如何使用[!UICONTROL 「讀取對象」]活動，在工作流程中啟動[!UICONTROL 「資料服務查詢對象」]。 |
| [!DNL Adobe Campaign] | 教學課程 - [使用 Android 的推播通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | 向 iOS 和 Android 行動裝置傳送個人化和分段的推播通知。本教學課程會逐步引導您完成相關步驟，順利從 Adobe Campaign 傳送推播通知，以及在 Android 應用程式中接收這些通知。 |
| [!DNL Adobe Campaign] | 影片 - [建立推播通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | 在 Adobe Campaign Standard 中建立推播通知。您可以向 iOS 和 Android 行動裝置傳送個人化和分段的推播通知。 |
| [!DNL Adobe Campaign] - AEP 資料連接器 | 影片 - [檢查資料擷取工作的狀態](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | 了解如何檢查資料擷取工作的狀態，以及資料是否已從 Adobe Campaign Standard 擷取到 Adobe Experience Platform。 |
| [!DNL Adobe Campaign] - AEP 資料連接器 | 影片 - [修改資料對應工作](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | 了解如何檢查狀態並修改資料對應工作。 |
| [!DNL Adobe Campaign] - AEP 資料連接器 | 影片 - [對應體驗事件](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | 了解如何在 Adobe Experience Platform 中對應體驗事件。 |
| [!DNL Adobe Campaign] - AEP 資料連接器 | 影片 - [對應自訂資源](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | 了解如何對應 Adobe Campaign Standard 和 Adobe Experience Platform 之間不同的資料類型。 |
| [!DNL Adobe Campaign] - AEP 資料連接器 | 影片 - [了解 Adobe Experience Platform 資料連接器](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | 了解如何將 XTK 資料 (在 Campaign中擷取的資料) 對應至 Adobe Experience Platform 上的 Experience Data Model (XDM) 資料，以便您的資料可在 Adobe Experience Platform 上使用。 |
| [!DNL Adobe Campaign] - AEP 資料連接器 | 影片 - [對應種子表資料](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | 了解如何使用 Adobe Experience Platform 對應您的種子資料/測試設定檔。 |
| [!DNL Adobe Campaign]- 對象目的地 | 影片 - [變更平台對象傳送作業的定位維度](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | 了解如何在 Adobe Campaign Standard 主要設定檔表格之外的位置，變更平台對象傳送作業的定位維度。 |
| [!DNL Adobe Campaign] | 影片 - [管理 Snowflake 的大型資料](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | 在 Adobe Campaign Classic 中運用 Snowflake 連接器。 |
| [!DNL Adobe Campaign] - 對象目的地 | 文章 - [對象目的地 (測試版)- 概觀](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | 了解如何在 Adobe Campaign Standard 中，運用 Adobe Experience Platform 提供的集中整合式設定檔資料推展行銷活動。 |
| [!DNL Adobe Target] - Mobile SDK | 教學課程 - [使用 Adobe Target 提供個人化應用程式體驗](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | 在您自己的 Android 應用程式中實作 Adobe Target。驗證 Mobile Services SDK 設定並實作預先擷取內容、封鎖請求等 [!DNL Target] 請求。 |
| Adobe Analytics | 影片 - [Adobe Summit 2019 超級座談](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | 觀看 2019 年 Summit 高科技業「超級座談」的精選片段。 |
| Adobe Analytics | 影片 - [Customer Journey Analytics 計算量度簡介](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | 逐步說明在 [!UICONTROL Customer Journey Analytics] 中[!UICONTROL 建立計算量度]的基本知識。 |
| Adobe Analytics | 影片 - [Adobe Summit 2019 超級座談](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | 觀看 2019 年 Summit 旅宿業座談的精選片段。 |
| Adobe Analytics | 影片 - [Adobe Summit 2019 超級座談](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | 觀看 2019 年 Summit 零售業座談的精選片段。 |
| Adobe Analytics | 影片 - [客戶使用案例：Accent Group 集團斥資提升客戶體驗以促進業績](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | 觀看 Accent Group 集團如何使用 Adobe Experience Cloud 打造順暢的數位體驗。 |
| Adobe Analytics | 影片 - [客戶使用案例：ServiceNow 取得與潛在客戶建立連結的正確見解](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | 了解 [!DNL ServiceNow] 如何透過 Adobe Advertising Cloud 和 Adobe Analytics 從行銷管道取得寶貴資料並據以行動，提高付費搜尋廣告的 ROI。 |
| Adobe Analytics | 影片 - [Adobe Analytics - 不僅僅是資料，還是客戶情報](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | 了解資料導向行銷的概念，掌握如何運用成熟的分析能力，從收集資料、建構見解，最後轉化為實際行動。 |
| Adobe Analytics | 影片 - [Adobe Sensei 和 Adobe Analytics - 加長版](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | 一覽採用 [!DNL Sensei,] 技術之 Adobe Analytics 的主要功能，包括[!UICONTROL 異常偵測]、[!UICONTROL 貢獻分析]、[!UICONTROL 智慧型警報]、[!UICONTROL 叢集]、[!UICONTROL 區段 IQ] 和[!UICONTROL 傾向模型]。 |
| Adobe Analytics | 影片 - [Adobe Analysis Workspace 如何改變業務現況](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | 了解如何使用 Analysis Workspace 執行 Ad Hoc Analysis、彈性分析、同類群組分析和[!UICONTROL 流失分析]。您也可以與所有同仁共用分析工作環境，而透過拖放功能，每個人都能輕鬆分析資料並快速獲得寶貴見解。 |
| Adobe Analytics | 影片 - [客戶使用案例：The Home Depot 使用客戶體驗管理推動創新](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | 了解 [!DNL Home Depot] 如何使用 Adobe 解決方案，透過個人化的自訂購物體驗，提升品牌忠誠度和客戶滿意度。 |
| Adobe Analytics | 簡報 - [了解 Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | 了解 Adobe 的 [!UICONTROL Customer Journey Analytics] (以 [!DNL Adobe Experience Platform] 為基礎的應用程式服務) 如何將 [!UICONTROL Analysis Workspace] 導入 Experience Platform。藉由此功能，您可以對任何 [!DNL Adobe Experience Platform] 資料集執行多管道分析。 |
| Adobe Analytics | 影片 - [CJA 的跨管道歸因](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | 了解如何在 [!UICONTROL Customer Journey Analytics] 中使用視覺化功能顯示跨管道歸因 (評分)。 |
| Adobe Analytics | 文章- [繼續 Adobe Analytics 學習歷程的客戶秘訣](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | 三位 Adobe 客戶現身說法，為您提供從 Adobe Analytics 獲致最大價值的秘訣。 |
| Adobe Analytics | 影片 - [在 CJA 中建立跨管道視覺化效果](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | 了解 [!UICONTROL Customer Journey Analytics] 可如何協助您將資料視覺化，其中包含多種管道所提供多個資料集的資料，而且還包括依訪客整併的資料類型。 |
| Adobe Analytics | 影片 - [將計算量度從 Adobe Analytics 移至 Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | 說明在 [!UICONTROL Customer Journey Analytics] 中重新建立 Analytics [!UICONTROLC計算量度]的秘訣。 |
