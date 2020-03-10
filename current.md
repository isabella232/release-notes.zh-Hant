---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b58151e366ba9aef341a8bd6742d6275d5cd8b30

---


# 提早存取- Adobe Experience Cloud發行說明- 2020年3月

Adobe Experience Cloud 的新功能及修正項目。

>[!IMPORTANT]
>此頁面含有搶鮮版內容，於預計發行前可能會有所變更。

>[!NOTE]
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期: 2020 年 3 月**

(特定產品發行日期可能有所不同)

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面與核心服務](#ecloud)
* [Experience Platform](#platform)
* [歷程協調](#journey)
* [Mobile Services 與 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [新檔案與教學課程](#selfhelp)

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

**新功能**

* 使用您的Adobe ID，您可以訂閱更精細的事件通知，包括產品選件和附加元件等級。 在Experience Cloud產品中尋找這項新功能，自訂程式會顯示您要訂閱的產品和服務的子產品。 此增強功能應可大幅降低您收到的通知數量，並讓通知與您使用的產品和功能更相關。  若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 依產品子方案的個人化自訂 | <ul><li>依產品方案或Experience Cloud產品附加元件自訂。</li><li>收到的事件通知與您的產品和產品方案偏好相關。</li></ul> |
| 根據使用者偏好提供個人化體驗 | <ul><li>電子郵件通知會使用根據瀏覽器設定的時區偏好設定。</li><li>使用所有選取的偏好設定，在訂閱／取消訂閱時傳送電子郵件確認。</li></ul> |
| 更好地傳遞事件訊息 | <ul><li>事件歷史記錄會根據時間順序事件更新排序。</li><li>已新增至「主要／次要」已關閉問題的事件解析度時間戳記。</li></ul> |

## Experience Cloud 介面與核心服務 {#ecloud}

Experience Cloud 介面的新功能和修正項目，包括管理和核心服務 (客戶屬性、對象、觸發器、Cookie 等)。

| 功能 | 發行日期 | 說明 |
| ----|----|---- |
| 管理工具 - 檢視使用者詳細資訊 | 2020 年 2 月 26 日 | 管理員可以在新的管理工具中，檢視所有 Experience Cloud 使用者及其詳細資訊，並可將清單加以排序及篩選。使用者詳細資訊包括使用者的產品存取情形、角色，以及上次存取的資訊。See [Experience Cloud Admin Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) help for details. |

### 統一產品網域

Adobe 正在更新網域和介面標題，以統一及提升您在所有 Experience Cloud 應用程式中的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會變更您目前的工作流程。

更新包括：

* 新解決方案 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * 瀏覽器支援：支援的瀏覽器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera] (最新版本)。**注意：**&#x200B;雖然 Experience Cloud 介面可支援這些瀏覽器，但個別解決方案可能不會支援所有瀏覽器(例如 [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 不支援 [!DNL Safari])。
   * (僅限 [!DNL Safari]) 網域變更可能導致 [!DNL Safari] 發生 Cookie 問題。在 [!DNL Safari] 的「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Experience Cloud 在這個新的網域中運作。
* 在組織或不同應用程式之間更輕鬆地切換。
* 改良產品說明：[!UICONTROL Experience League] 已整合至產品中，因此搜尋說明內容時，搜尋範圍會包含社群論壇和視訊內容。這項變更可讓您輕鬆存取更多內容，協助您充份運用 Experience Cloud。此外，按一下&#x200B;**[!UICONTROL 「說明]** > **[!UICONTROL 意見回饋」]**&#x200B;即可回報問題，或與 Adobe 分享您的想法。
* 改良通知：[!UICONTROL 「通知」]下拉式選單現在提供兩個標籤，其中一個顯示您的產品通知，另一個顯示全球產品公告。

**注意：** 「動 [!UICONTROL 態消息] 」頁面已於2020年1月過時。 請參閱產品中的淘汰通知。

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全性佈告和諮詢](https://helpx.adobe.com/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## 歷程協調 {#journey}

使用Adobe Experience Platform，透過智慧地即時預測每個客戶的需求，跨不同體驗通道大規模策劃客戶歷程。

第1季發行已發佈。 [閱讀更多資訊](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

### 其他資源

[檔案](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [發行說明](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [操作視訊](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## Mobile Services 與 Mobile SDK {#mobile}

**iOS v4.19.1**

* 一般——解決當追蹤呼叫的上下文資 [!UICONTROL 料中包含] Swiftenums時，可能發生當機的問題。
* [!DNL Target] - [!DNL Target] ID現在會在傳送至Adobe Analytics的內部 `a.target.sessionId` Analytics-for-Target點擊中，新增為內容資料參數。

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] Session ID現在會在傳送至Adobe Analytics的內部  Analytics-for-Target點擊中，新增為內容資料參數「a.target.sessionId」。

## [!DNL Analytics] {#analytics}

發行日期: **2020 年 3 月 12 日**

Adobe Analytics 的新功能和修正項目：

* [Adobe Analytics 的新功能、增強功能和修正項目](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 的新功能、增強功能和修正項目 {#aa-features}

* **分析工作區中的多[!UICONTROL 個報表套裝&#x200B;]**:您現在可以將多個報表套裝的資料匯入單一[!UICONTROL Analysis Workspace]專案，並排檢視。 此功能將在數週內推出給所有客戶。[更多詳情...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud受眾最佳化**:此功能可讓您在8小時內（而非之前48小時的處理時間）將區段發佈至Experience Cloud。 [更多詳情...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **分析工作區——訓練教學課程範本**:此新標準範本會逐步帶您瞭解在工作區中建立第一個分析的常用術語和步驟。 它可作為「新建項目」模式中的標準範本使用，並替換目前存在於清單中沒有其他專案的新使用者的範例專案。 

#### 修正

* 修正「報告與分 [!UICONTROL 析」中無法下載報] 告的 `.xls` 問題。 此問題影響使用美元和歐元以外貨幣的客戶。 (AN-206541、AN-204008)
* 新殼層的推出修正了與轉換Experience Cloud組織相關的數個客戶問題。(AN-200844、AN-186920)
* 修正劃分的搜尋篩選器中未包含「未指定」（無）時，對 _Unspecified___ 行項目（或某些其他報告行項目）執行劃分時，不會傳回劃分結果的問題。
* 修正使用分類維度時，進入或退出度量總計不符合劃分明細項目總計的問題。
* 修正Attribution IQ中的首次接觸和上次接觸模型無法正確計算某些非現成尺寸行項目評分的問題。
* 修正將一個日期維度劃分為另一個日期維度時，會傳回錯誤結果的問題。
* 修正當套用至分類維度報表中的「未指定」時，有時會錯誤計算進入或退出量度的問題。

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 轉換等級 **[!UICONTROL 設定的EOL]** | 2020 年 3 月 3 日 | 「管理工具 [](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) >報表套裝 **[!UICONTROL >]Report Suites** >一般帳戶設定」中的「無法運作的轉換層級」設定，將於2020年3月12日從UI中移除。 |
| 控制面板封 **[!UICONTROL 存的EOL]** | 2020 年 3 月 3 日 | 自2020 **[!UICONTROL 年3月]** 12日起，「報告與分析」中「管理控制面板 **** 」下方的「檢視封存」設定將不再提供使用。 |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 開始移動至新網域 - `https://experience.adobe.com/analytics.`<br>**注意：**凡是使用 Adobe ID 或 Enterprise ID 存取 Analytics 的所有使用者，均適用這項變更。<ul><li>這項網路異動可能會在 Safari 中載入 Analytics 時造成 Cookie 問題。在 「隱私權偏好設定」中取消選取&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Analytics 在這個新的 Adobe Experience Cloud 網域中運作。[!DNL Safari]You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>網域變更可能會導致 [!UICONTROL Activity Map] 在[部分特定情況下](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)停止運作。</li></ul> |
| 終止服務 - Analytics Legacy API | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy Oauth 驗證 (Oauth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy Oauth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)。2020年3月5日發行版本2.20.0。

## Audience Manager {#aam}

Audience Manager的新功能和更新：

### Fixes and improvements {#aam-fixes-and-improvements}

* 修正客戶因缺少RBAC權限 [!UICONTROL VIEW_ALL_DESTINATIONS而無法更新區段名稱的錯誤]。 更 [!UICONTROL 新區段時不需要VIEW_ALL_DESTINATIONS] 權限。 有關RBAC權限的詳細資訊，請參 [閱管理（RBAC控制）](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions)。 (AAM-52760)
* 修正 [Data Explorer](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) （資料總管）中，根據  Data Explorer訊號建立特徵時，有些客戶在運算式產生器的基本資訊區段和運算子中看不到內容的錯誤。 (AAM-53130)
* 已修正部分客戶無法載入 [!UICONTROL Audience Marketplace介面的錯誤] 。 (AAM-52070)
* 已修正區段API中 [!UICONTROL 的錯誤] ，因為有些區段沒有說明，當使用者嘗試存取這些區段，而使用者必須從該頁面導覽時，介面會凍結。 (AAM-53071)
* 整個介面提供多種協助工具改良功能。 (AAM-48952、AAM-48969、AAM-48979、AAM-48993、AAM-49048、AAM-49057、AAM-49058、AAMaam-49392)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 的新功能、修正及更新項目。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品更新

* **AEM 6.5.4.0** AEM 6.5,Service Pack 4.0（2020年3月5日發行的6.5.4.0）是重要的更新，其中包含新功能、重要客戶增強功能、改善的效能、穩定性和安全性，自2019年4月AEM 6.5全面上市以來已推出。
   * [Adobe Experience Manager 6.5、Service Pack 4的新增功能](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [發行說明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms發行交付結果](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4,Service Pack 8.0（6.4.8.0於2020年3月5日發行）是重要的更新，其中包含自2018年4月AEM 6.4全面上市以來發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8（2019年3月5日發行的6.3.3.8）是重要的更新，其中包含自2017年4月AEM 6.3全面上市以來發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4,Service Pack 6（6.4.6於2020年3月5日發行）變更了AEM Assets設定品牌入口網 [!UICONTROL 站的方式。] 此外，此版本還包含其他增強功能和錯誤修正。
   * [發行說明](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### 自助資源

* **AEM as a Cloud Service —— 角色型權限**

   Cloud Manager已預先設定具有適當權限的角色。 每個角色都具有與每個角色相關聯的特定權限、預先配置的任務或權限。 「基 [於角色的權限](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) 」幫助主題標識了可用函式和可運行這些函式的角色。

* **AEM as a Cloud Service - Dispatcher**

   已更 [新Dispatcher和CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) 和 [](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) Explicit Dispatcher快取失效區段，以釐清可用的選項及其運作方式。

* **使用品牌入口網站設定AEM資產**

   AEM Assets現在已透過Adobe I/O設定 [!UICONTROL 品牌入口網站] ,Adobe I/O會購買IMS Token以授權品牌入口網站租用戶。 之前，它是透過舊版OAuth閘道在Classic介 [!UICONTROL 面中設定。]
請參 [閱「使用品牌入口網站設定AEM資產」](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html)。

* **AEM as a Cloud Service - Dynamic Media中的智慧裁切**

   當您在動態媒體元件中使用「智慧裁切」時，AEM中會以雲端服務的形式提供新選項：

   **啟用外觀比例比對** -選取此選項，讓動態媒體挑選最符合原始影像外觀比例的智慧裁切轉譯。
請參 [閱使用智慧型裁切時](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop)。

### 社群

* **AEM Skill Builder網路研討會**

   * AEM Sites —— 從2020年3月17日起，瞭解內容製作的建立區塊以及AEM Sites的基本概念和運作。 [立即註冊](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register)。
   * AEM Assets —— 從2020年3月19日開始，磨練您的數位資產管理專業知識，並瞭解品牌入口網站、 [!UICONTROL Dynamic Media、][!UICONTROL Asset Link] 等基本知識。 [立即註冊](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register)。

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

## [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Campaign Classic

* [Campaign Classic 19.1.4更新](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### 其他資源

* Adobe Campaign Standard：[文件](https://helpx.adobe.com/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文件](https://helpx.adobe.com/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日期：2020 年 2 月 10 日 (適用於 2 月 8 日發行的版本)：

| 檢視 | 功能 |
|------|---------|
| [!UICONTROL 產品組合] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. 廣告群組中的所有廣告會套用相同出價。Japan Display Network促銷活動的資料會包含在投資組合的模擬中。 |
| [!UICONTROL 搜尋] >大量 [!UICONTROL 工作表] | 現在，您可以使用大量表單來建立、編輯及刪除 Google 回應式搜尋廣告 (RSA)。以前，您只能前往&#x200B;**[!UICONTROL 「搜尋]** > **[!UICONTROL 促銷活動」]**，透過標準促銷活動管理介面尋求支援 |
| [!UICONTROL 搜尋] >促銷 [!UICONTROL 活動、報表] | 現在起，所有基本報表和實體層級的促銷活動管理檢視均已提供 Google Ads 的「顯眼程度」度量 `Impr. (Abs. Top) %` 和 `Impr. (Top) %`，不過購物廣告產品群組、[!UICONTROL 「促銷活動每日曝光比重」]和[!UICONTROL 「關鍵字每日曝光比重」]報表，以及標籤和限制檢視除外。 |

## [!DNL Magento] {#magento}

如需 Magento 發行說明，請參閱：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] 是銷售機會管理的完整解決方案，也適合 B2B 行銷人員使用，而透過該解決方案，他們可參與複雜購買歷程的每個階段，從中轉變客戶體驗。

### Marketo Engage 核心更新

發行日期：2020 年 2 月 21 日

* **_Microsoft Dynamics_在 Microsoft Flow Action 中的變更負責人：**&#x200B;直接從 Marketo Engage 變更銷售機會或連絡負責人。
* **增強 API 呼叫功能：**
   * 使用者管理 API
   * 自訂物件結構描述 API
   * 登陸頁面重新導向規則 API
* **表單描述元快取：**&#x200B;改善登陸頁面與表單。

如需詳細資訊，請參閱[!DNL Marketo] [2020 年 2 月](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720)的發行說明。

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

## 新檔案與教學課程 {#selfhelp}

最新和最新的自助文章和影片。 <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| 解決方法 | 內容 | 說明 |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | 視訊——建 [立多個類別和產品頁面](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | 瞭解如何使用CIF核心元件，以建立最簡化的Adobe Experience Manager(AEM)CIF專案作為客戶專案的起點。 將主題和CSS樣式套用至元件，並檢查由原型產生的新AEM CIF專案。 此外，瞭解CIF核心元件使用的CSS和JavaScript如何組織。 |
| [!UICONTROL AEM 表格] | 文章——使 [用OKTA驗證AEM作者](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | 瞭解如何在OKTA入口網站上設定您的應用程式，以及註冊新應用程式時通常使用的設定。 |
| [!UICONTROL AEM Commerce] | 教學課程- [自訂CIF核心元件](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | 一般來說，請檢視CIF核心元件和AEM提供的數個不同擴充點。 CIF核心元件提供一套標準的商務元件，可用來加速整合Adobe Experience Manager(AEM)和Magento解決方案的專案。 |
| [!DNL Adobe Campaign] -觀眾目標 | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | 使用Adobe [!UICONTROL Experience Platform區段產生器在Campaign Standard中建立觀眾]。 您可以直接在Adobe Campaign Standard中透過「對象」模組存取 [!UICONTROL 此功] 能。 |
| [!DNL Adobe Campaign] -觀眾目標 | 視訊——在 [行銷工作流程中啟用Adobe Experience Platform觀眾](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | 瞭解如何使用「讀取 [!UICONTROL 對象」活動，在工作流程中啟] 動「資料服務查詢對象  」。 |
| [!DNL Adobe Campaign] | 教學課程- [使用Android的推播通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | 傳送個人化和分段的推播通知至iOS和Android行動裝置。 本教學課程將逐步引導您完成從Adobe Campaign傳送推播通知以及在Android應用程式中接收這些通知的相關步驟。 |
| [!DNL Adobe Campaign] | 影片- [建立推播通知](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | 在Adobe Campaign Standard中建立推播通知。 您可以傳送個人化和分段的推播通知至iOS和Android行動裝置。 |
| [!DNL Adobe Campaign] - AEP資料連接器 | 視訊- [檢查資料擷取工作的狀態](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | 瞭解如何檢查資料擷取工作的狀態，以及資料是否已從Adobe Campaign Standard擷取到Adobe Experience Platform。 |
| [!DNL Adobe Campaign] - AEP資料連接器 | 視訊——修 [改資料對應](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | 瞭解如何檢查狀態並修改資料對應。 |
| [!DNL Adobe Campaign] - AEP資料連接器 | 視訊——映 [射體驗事件](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | 瞭解如何在Adobe Experience Platform中對應「體驗事件」。 |
| [!DNL Adobe Campaign] - AEP資料連接器 | 視訊——對 [應自訂資源](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | 瞭解如何在Adobe Campaign Standard和Adobe Experience Platform之間對應不同的資料類型。 |
| [!DNL Adobe Campaign] - AEP資料連接器 | 視訊- [瞭解Adobe Experience Platform Data Connector](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | 瞭解如何將XTK資料（在Campaign中收錄的資料）對應至Adobe Experience Platform上的Experience Data Model(XDM)資料，以便在Adobe Experience Platform上提供您的資料。 |
| [!DNL Adobe Campaign] - AEP資料連接器 | 視訊——對 [應種子表資料](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | 瞭解如何使用Adobe Experience Platform來對應您的種子資料／測試設定檔。 |
| [!DNL Adobe Campaign]-觀眾目標 | 視訊- [變更平台對象之傳送的定位維度](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | 瞭解如何在Adobe Campaign Standard的主要設定檔表格外變更平台對象傳送的目標維度。 |
| [!DNL Adobe Campaign] | 視訊——雪花 [上的大型資料管理](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | 在Adobe Campaign Classic中運用Snowflake連接器。 |
| [!DNL Adobe Campaign] -觀眾目標 | 文章- [觀眾目標（測試版）-概觀](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | 瞭解如何在Adobe Campaign Standard中運用Adobe Experience Platform的集中整合個人檔案資料進行行銷宣傳。 |
| [!DNL Adobe Target] - Mobile SDK | 教學課程——使 [用Adobe Target個人化應用程式體驗](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | 在您自己的Android應用程式中實作Adobe Target。 驗證Mobile Services SDK設定並實作 [!DNL Target] 預取內容、封鎖請求等請求。 |
| Adobe Analytics | 視訊- [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | 觀看2019年Summit的高科技「超級會議」精選片段。 |
| Adobe Analytics | 影片——客 [戶歷程分析中計算量度簡介](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | 逐步瞭解在客戶歷程分析中 [!UICONTROL 建立計算量度][!UICONTROL 的基本概念]。 |
| Adobe Analytics | 視訊- [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | 觀看2019年峰會旅遊與接待服務會議的精選片段。 |
| Adobe Analytics | 視訊- [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | 請參閱2019年峰會零售會議的精選片段。 |
| Adobe Analytics | 影片——客 [戶使用案例：Accent Group投資客戶體驗推動銷售](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | 觀看Accent Group如何使用Adobe Experience Cloud建立順暢的數位體驗。 |
| Adobe Analytics | 影片——客 [戶使用案例：ServiceNow獲得與潛在客戶聯繫的正確見解](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | 瞭解如何透過 [!DNL ServiceNow] Adobe Advertising Cloud和Adobe Analytics從行銷通道獲取可操作的資料，並提高付費搜尋廣告的投資報酬率。 |
| Adobe Analytics | 視訊- [Adobe Analytics —— 它不僅僅是資料，還是客戶智慧](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | 瞭解資料導向式行銷，以及如何讓您的分析成熟度從資料、見解到行動。 |
| Adobe Analytics | 視訊- [Adobe Sensei和Adobe Analytics —— 延伸版](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | 檢視Adobe Analytics的主要功能， [!DNL Sensei,] 包括異常偵測、貢 [!UICONTROL 獻分析、智慧提醒、] 叢集、 [!UICONTROL IQ細分、傾向模型][!UICONTROL 。] |
| Adobe Analytics | 視訊- [Adobe Analysis Workspace如何改變您的業務](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | 瞭解如何使用分析工作區來執行臨機分析、彈性分析、世代分析和流 [!UICONTROL 失分析]。 您也可以與公司中的每個人共用分析工作環境，其拖放功能讓每個人都能輕鬆分析資料並快速獲得見解。 |
| Adobe Analytics | 影片——客 [戶使用案例：家得寶的客戶體驗管理創新](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | 瞭解如何 [!DNL Home Depot] 使用Adobe解決方案，透過個人化、自訂的購物體驗，建立品牌忠誠度和客戶滿意度。 |
| Adobe Analytics | 簡報——了 [解客戶歷程分析](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | 瞭解Adobe的Customer Journey Analytics [!UICONTROL (以Adobe的]Customer Journey Analytics為基礎的應用程式服務)如 [!DNL Adobe Experience Platform]何將 [!UICONTROL Analysis Workspace] 帶入Experience Platform。 此功能可讓您對任何資料集進行多頻道 [!DNL Adobe Experience Platform] 分析。 |
| Adobe Analytics | 視訊- [CJA中的跨通道歸因](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | 瞭解如何在客戶歷程分析中使用視覺化來顯示跨通道的歸 [!UICONTROL 因（評分）]。 |
| Adobe Analytics | 文章- [繼續Adobe Analytics學習歷程的客戶秘訣](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | 認識三位Adobe客戶，他們會為您提供如何從Adobe Analytics中獲得最大價值的秘訣與訣竅。 |
| Adobe Analytics | 視訊- [在CJA中建立跨通道視覺化](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | 瞭解客  戶歷程分析如何讓您建立視覺化，其中包含來自多個通道之多個資料集的資料，包括合併每位訪客的資料。 |
| Adobe Analytics | 視訊——將 [您的計算量度從Adobe Analytics移至客戶歷程分析](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | 在「客戶歷程分析」中尋找重新建 [!UICONTROLC立Analytics計算量度][!UICONTROL 的秘訣]。 |
