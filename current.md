---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: f2d6f3489e183db682d62766d13be958cad5692b

---


# Adobe Experience Cloud 版本說明 - 2020 年 1 月

Adobe Experience Cloud 中的新功能及修正項目。

>[!NOTE]
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期：2020 年 1 月 16 日**

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面與核心服務](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services 與 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics) (**更新日期：2020年1月21日**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud)

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

**新功能**

* 您可以使用 Adobe ID，根據產品、地區和事件偏好設定來訂閱事件通知。完成訂閱偏好設定後，當使用者開啟、更新或關閉產品，只會收到相關產品事件和維護事件的通知。若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 訂閱電子郵件主動通知 | <ul><li>支援 Experience Cloud、Creative Cloud、Document Cloud、Adobe Experience Platform 和 Adobe 服務</li><li>支援地區和事件類型偏好設定</li></ul> |
| 管理通知偏好設定 | <ul><li>隨時編輯和儲存通知偏好設定</li><li>隨時取消訂閱通知</li></ul> |
| 實現個人化並加速傳送電子郵件 | <ul><li>事件開啟、更新或關閉時，立即傳送事件通知</li><li>僅接收與您設定之偏好設定相符的相關事件通知</li><li>根據您帳戶偏好設定中指定的語言接收本地化通知</li></ul> |
| 個人化產品通知 | <ul><li>符合通知偏好設定和產品權益的事件會顯示在「公告」面板中</li></ul> |

## Experience Cloud 介面與核心服務 {#ecloud}

Experience Cloud 介面中的新功能和修正，包括管理和核心服務 (客戶屬性、對象、觸發器、Cookie 等)。

### 統一產品網域

Adobe 正在更新網域和介面標題，以統一及提升您在所有 Experience Cloud 應用程式中的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會變更您目前的工作流程。

更新包括：

* 新解決方案 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * 瀏覽器支援：支援的瀏覽器包括 [!DNL Microsoft Edge]、[!DNL Google Chrome]、[!DNL Firefox]、[!DNL Safari] 和 [!DNL Opera] (最新版本)。**注意：**&#x200B;雖然 Experience Cloud 介面可支援這些瀏覽器，但個別解決方案可能不會支援所有瀏覽器 (例如 [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 不支援 [!DNL Safari])。
   * (僅限 [!DNL Safari]) 網域變更可能導致 [!DNL Safari] 發生 Cookie 問題。在 [!DNL Safari] 的「隱私權偏好設定」中取消勾選&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Experience Cloud 在這個新的網域中運作。
* 在組織或不同應用程式之間更輕鬆地切換。
* 改良產品說明：[!UICONTROL Experience League] 已整合至產品中，因此搜尋說明內容時，搜尋範圍會包含社群論壇和視訊內容。這項變更可讓您輕鬆存取更多內容，協助您充份運用 Experience Cloud。此外，按一下&#x200B;**[!UICONTROL 「說明]**>**[!UICONTROL &#x200B;意見回饋」]**即可回報問題，或與 Adobe 分享您的想法。
* 改良通知：[!UICONTROL 「通知」]下拉式選單現在提供兩個標籤，其中一個顯示您的產品通知，另一個顯示全球產品公告。

**注意：**[!UICONTROL 「摘要」]頁面將於 2020 年 1 月汰除。請參閱產品中的淘汰通知。

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

### Experience Cloud Cookie

Adobe 正在調整 `same-site`Cookie 設定，以因應 Chrome 預計於 Chrome 80 所做的變更 (即將於 2020 年 2 月發行)。

除非您使用 CNAME 進行第一方資料收集，但跨多個網域使用該 CNAME (友好第三方網域)，且未使用 Experience Cloud (訪客) ID 服務，否則您不需要變更。Chrome 80 版本釋出後，Chrome 會自動為 Analytics 的訪客 ID Cookie 提供 SameSite 值，以`Lax,`防止於其他網域使用。如果您想在不同網域間繼續使用 CNAME，請聯絡 Adobe 客戶服務，要求他們將您 CNAME 的 SameSite 值變更為 `None.`

請注意，不論您是否使用 Experience Cloud ID 服務，Adobe 建議在各網域分別使用不同 CNAME。

[更多內容…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全性佈告和諮詢](https://helpx.adobe.com/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## Mobile Services 與 Mobile SDK {#mobile}

2020 年 1 月 16 日：4.18.0 版

* 取得 - 新增 API `Analytics.processGooglePlayInstallReferrerUrl(final String url)` 以支援[!DNL Google Play]安裝 Referrer API。

如需安裝 Referrer API 的詳細資訊，請參閱[您還在使用 InstallBroadcast 嗎？在 2020 年 3 月 1 日前切換至 Play Referrer API](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正：

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)   （更新日期：2020年1月21日）
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |
| 分析工作區——使用者介面改進 | 分析工作區將於2020年1月16日開始進行使用者介面改良，將持續數個月。 這些變更的目標是讓使用者更容易存取應用程式，並在Adobe Experience cloud中提供更一致的體驗。 |
| Analysis Workspace – 自由表格產生器 | 啟用「表格產生器」後，許多維度、劃分、量度和區段都可直接拖放使用，方便建立可回答更複雜商業問題的表格。資料不會立即更新，而是在您確定要建立的表格並點擊&#x200B;**[!UICONTROL 「建立」]**後，資料才會更新，為您節省寶貴時間。此外，這項功能也提供以下輔助功能：<ul><li>**預覽**：演算實際資料前，您可以先預覽表格格式。</li><li>**彈性的表格列與劃分設定**：您可以針對每個維度列設定列與劃分層級。以前，Workspace 的預設內容只有在資料回傳後才能變更。</li><li>**依位置劃分**：您可以設定維度列，一律&#x200B;_依位置劃分_&#x200B;而非&#x200B;_依特定項目_&#x200B;劃分 (預設)。</li><li>**手動靜態列排序**：您可以手動排序靜態列，讓表格列能依您的需求顯示。以前，靜態列只能依量度欄或字母順序排序。</li></ul>[更多詳情...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/freeform-table.html). |
| 跨裝置分析 (CDA) 新增[!UICONTROL 識別狀態]維度 | 我們為 CDA 虛擬報表套裝新增[!UICONTROL 識別狀態]維度。此維度有兩個可能的值，分別是&#x200B;_已識別_&#x200B;和&#x200B;_未識別_。_已識別_：表示人員已由裝置圖表識別。_未識別_：表示裝置圖表未識別該人員。換句話說，<br>CDA 使用者現在可以建立經過計算的量度，例如[!UICONTROL 裝置圖表涵蓋範圍]，該量度可顯示虛擬報表套裝中有多少人已由裝置圖表識別。此度量有助於疑難排解 CDA 壓縮率的相關問題。如果識別的人數不多，結合度就會偏低。 |
| 資料倉儲 API 中的 VRS 支援 | 現在，使用者可透過資料倉儲 API 使用虛擬報表套裝。相較之下，以前使用者只能透過資料倉儲 UI 使用此功能。現在使用資料倉儲 API 時，您可以查看及查詢虛擬報表套裝，但套用至虛擬報表套裝的區段必須與資料倉儲相容。 |
| 隱私權服務 API：CCPA | 加州消費者隱私權法案 (California Consumer Privacy Act, CCPA) 強化了美國加州居民的隱私權和消費者保護力道。本法案自 2020 年 1 月 1 日起生效。<br><br/>CCPA 為加州居民提供了新的資料隱私權，例如有權存取和刪除其個人資料、有權得知其個人資料是否遭到販售或揭露 (以及對象是誰)，以及有權拒絕廠商販售其個人資料。<br><br/>隱私權服務可支援使用者提出拒絕銷售個人資料的要求。<br><br/>隱私權服務原本稱為 GDPR 服務，不僅保留之前的所有功能，現在更擴大範圍支援 CCPA。<br/><br/>[Analytics 中的 CCPA ](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[隱私權服務概觀](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### 修正

* 修正警示通知無法傳送至埃及電話號碼的問題。(AN-197079)
* 已修正多個 [!DNL DFA Data Connector] 問題。(AN-193281、AN-193075、AN-193484、AN-193737)
* [!UICONTROL 報告與分析]：修正產品轉換漏斗報表遭切斷以及數字模糊的問題。(AN-186901)
* 修正使用者無法在 Workspace 專案中切換採取新分類架構之報表套裝的問題。(AN-199076)
* 修正[!UICONTROL 計算量度]中[!UICONTROL 累計]功能無法正常運作的問題。(AN-184257)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | 自 2020 年 1 月 16 日起，Adobe Analytics 將開始移動至新網域 - `https://experience.adobe.com/analytics.`<br>**注意&#x200B;**：這項變更適用於使用 Adobe ID 或 Enterprise ID 存取 Analytics 的所有使用者。<ul><li>這項網路異動可能會在 Safari 中載入 Analytics 時造成 Cookie 問題。在 Safari「隱私權偏好設定」中取消勾選&#x200B;_「防止跨網站追蹤」_，即可在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Analytics 在這個新的 Adobe Experience Cloud 網域中運作。只有 Safari 使用者會受到影響，建議使用其他瀏覽器，以免發生這類問題。</li><li>網域變更可能會導致 [!UICONTROL Activity Map] 在[部分特定情況下](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)停止運作。</li></ul> |
| 終止服務 - Analytics Legacy API | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy Oauth 驗證 (Oauth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy Oauth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| **[!UICONTROL 檢視封存]**選項的 EOL | 2019 年 10 月 30 日 | 宣佈儀表板管理員 (**[!UICONTROL 元件 > 儀表板]**) 中的**[!UICONTROL &#x200B;檢視封存]**選項將於 2020 年 1 月終止服務。 |
| **[!UICONTROL 強制 IP 登入限制]**選項的 EOL | 2019 年 10 月 30 日 | 宣佈&#x200B;**[!UICONTROL 管理 > 公司設定 > 安全性]**選單中的 IP 登入白名單 (**[!UICONTROL &#x200B;強制 IP 登入限制]**) 功能將於 2020 年 1 月終止服務。 |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 對於倫敦和新加坡的客戶，我們不再支援於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間的代理資料。<br/><ul><li>如果在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 關於 Analytics 使用者 `createDate` 欄位的近期變更 | 2019 年 8 月 30 日 | 2019 年 10 月或 11 月期間，Analytics 使用者的 `createDate` 欄位已從美國太平洋時間更新為格式正確的日期/時間值，並附上時區資訊。(AN-183468) |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager 新增的修正項目和功能。

### Audience Manager 中的新功能、增強功能和修正 {#aam-features}

| 功能 | 說明 |
| -----------| ---------- |
| [加州消費者隱私權法案 (CCPA) 支援與隱私權文件大幅修改](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | [加州消費者隱私權法案 (CCPA)](https://www.caprivacy.org/about) 自 2020 年 1 月 1 日起生效，賦予加州居民管理個人資料的新權利，並對在加州營業的特定實體加諸資料保護責任。<br><br>Audience Manager 可協助您利用 [Adobe Experience Platform 隱私權服務](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) (處理存取和刪除資料的要求) 等隱私權工具，落實隱私權法規所規定的義務。<br><br>我們已更新目前的[退出管理](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests)程序，加入所有選擇退出的已宣告 ID (例如 CRM ID)。如果宣告的 ID 選擇退出，則宣告的 ID 和其最後連結的裝置將退出 Audience Manager 的資料收集活動。退出請求功能也會以批次和即時傳送等方式，將取消分段請求傳送給支援此功能的[目標合作夥伴](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation)。<br><br>此外，我們已重新設計[資料安全性](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)、[資料隱私權](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)和[資料管理](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html)文件，協助您更輕鬆找到所需資訊，以遵行上述法規。 |

### 修正和改良 {#aam-fixes-and-improvements}

* 修正在[!UICONTROL 「建立目標」]工作流程中，選擇&#x200B;**[!UICONTROL 「整合平台」]**[!UICONTROL 類別]即導致[!UICONTROL 「基本資訊」]區段消失而無法完成工作流程的問題。(AAM-52397、AAM-52414)
* 我們已修正 Apple Safari 和 Mozilla Firefox 瀏覽器無法載入[!UICONTROL 「建立/編輯」]目標頁面的錯誤。(AAM-51784)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品維護

* **AEM 6.5.3.0**
AEM 6.5 Service Pack 3.0 (6.5.3.0，於 2019 年 12 月 12 日發行) 是一項重要更新，其中包括自 2019 年 4 月 AEM 6.5 全面推出以來所發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4 Service Pack 7.0 (6.4.7.0，於 2019 年 12 月 12 日發行) 是一項重要更新，其中包括自 2018 年 4 月 AEM 6.4 全面推出以來所發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3 Service Pack 3 Cumulative Fix Pack 7 (6.3.3.7，於 2019 年 12 月 12 日發行) 是一項重要更新，其中包括自 2017 年 4 月 AEM 6.3 全面推出以來所發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1 提供以 Okta 執行單一登入的更新，並可在「偏好設定」中指定暫存檔案的位置。此版本不再支援 AEM 6.3.x 的桌面應用程式 2.x。
   * [發行說明](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1 終止對 AEM 6.3.x 的支援**

   自 2019 年 4 月起，Adobe Asset Link 已不再支援 AEM 6.3.x。自 2020 年 1 月 13 日起，Adobe Asset Link 1.1 將取消對 AEM 6.3.x 的支援。
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### 產品發行

* **新功能：AEM 雲端服務**

   [Adobe Experience Manager](https://www.adobe.com/marketing/experience-manager.html) (AEM) 現已提供雲端服務。

   * [簡介](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [發行資訊](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [文件](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **自動化表單轉換服務**

   自動化表單轉換服務是一種將 PDF 表單自動轉換為精美行動 HTML 表單的服務，於 2019 年 12 月 12 日正式推出。

   * [簡介](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [設定服務](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [將 PDF 表單轉換為可調整的表單](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### 自助式

* **預覽 3D 資產**

   AEM 6.5 支援 3D 資產的製作程序功能，包括上傳、傳送和互動式預覽。您可從 AEM 的資產詳細資訊頁面使用互動式 3D 檢視器。檢視器的功能包含一系列互動式相機控制機制，可供您環繞、縮放及平移 3D 資產。請參閱[預覽 3D 資產](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)。

* **核心元件**

   現在，使用者取得核心元件 2.8.0 和許多修正項目時可一併取得[撰寫文件](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html)，並可[在 GitHub 上取得開發人員詳細資料和下載專案](https://github.com/adobe/aem-core-wcm-components)。

* **AEM 專案原型**

   [AEM 專案原型](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html)的 [ui.frontend 模組](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html)是實用而有彈性的工具，可讓您更輕鬆地為 AEM 專案進行前端開發。

### 其他資源

* [AEM 雲端服務](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [舊版的 AEM 文件](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Campaign Classic 19.2

| 功能 | 說明 |
| ------------- | ----------- |
| 加州消費者隱私權法案 (CCPA) | CCPA 是加州新推出的隱私權法案，調和了 2020 年 1 月 1 日起生效的資料保護要求，並落實現代化標準。CCPA 適用於位在加州，並為個人資料主體保管資料的 Adobe Campaign 客戶。<br>除了現有的隱私權功能 (包括許可管理、資料保留設定和使用者角色) 之外，Adobe Campaign 還可協助您為 CCPA 做好準備： <ul><li>_存取權_&#x200B;與&#x200B;_刪除權_：我們妥善運用針對 GDPR 新增的功能。[更多詳情](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>您可以追蹤消費者是否已選擇退出，不允許銷售其個人資料。為此，您需要擴充[!UICONTROL 「設定檔」]表格，並添加&#x200B;**[!UICONTROL 「退出 CCPA」欄位]**。[更多詳情](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> 請參閱[示範影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| 工作流程即時監控 | 您現在可以使用預先定義的檢視，即時監控所有工作流程的執行狀態。<br>如需詳細資訊，請參閱[依狀態篩選工作流程](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status)。 |
| 以 AMP 製作互動式內容 | Adobe Campaign 可讓您試用全新互動式 [AMP for Email](https://amp.dev/about/email/) 格式，讓行銷人員能在訊息中加入 AMP 元件，以利用豐富、動態的互動式內容提升電子郵件體驗，並直接在訊息中轉化為實際行動。<br>此功能已發佈公開測試版。<br>如需詳細資訊，請參閱[詳細文件](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html)和[教學影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)。 |
| 安全的 SMS 傳訊 (TLS) | 現已透過 Extended Generic SMPP Connector 支援安全的 SMS。如此可讓您加密連線至提供者。<br> **警告**：若要使用這項功能，所有伺服器都需具備最新憑證。憑證無效、撤銷或過期都會造成錯誤，影響整體 SMS 傳送功能。<br>如需詳細資訊，請參閱[詳細文件](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)。 |

若需修正和改善項目的相關資訊，請參閱 [Adobe Campaign Classic 發行說明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)。

### Campaign Standard 19.4

| 功能 | 說明 |
| ------------- | ----------- |
| 加州消費者隱私權法案 (CCPA) | CCPA 是加州新推出的隱私權法案，調和了 2020 年 1 月 1 日起生效的資料保護要求，並落實現代化標準。CCPA 適用於位在加州，並為個人資料主體保管資料的 Adobe Campaign 客戶。<br>除了 Adobe Campaign 所提供的隱私權功能 (包括許可管理、資料保留設定和使用者角色) 之外，我們也趁此次機會加入其他功能，以協助您為 CCPA 做好準備： <ul><li> 存取權與刪除權：我們妥善運用針對 GDPR 新增的功能。[更多詳情](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> 建立隱私權要求時，隱私權核心服務已新增規則類型 (GDPR 或 CCPA)。此方法適用於所有存取和刪除請求。不建議使用 Campaign API 和介面來存取及刪除請求。請參閱[過時及移除的功能](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)一文。 </li><li> 「設定檔」資源已新增&#x200B;**「退出 CCPA」**&#x200B;欄位，能方便 Adobe Campaign 使用者追蹤消費者是否選擇退出，不允許銷售其個人資訊。[更多詳情](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> 請參閱[示範影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| Microsoft Dynamics 365 整合(GA) | 現已推出 Adobe Campaign standard 與 Microsoft Dynamics 365 整合應用。您可以把連絡人和自訂實體記錄從 Dynamics 365 傳輸至 Campaign，並從 Campaign 將電子郵件事件資料傳回 Dynamics 365，以便統合銷售/行銷工作。<br>請參閱[詳細文件](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html)，以完成設定整合並觀看[示範影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)。 |

若需修正和改善項目的相關資訊，請參閱 [Adobe Campaign Standard 發行說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)。

### Adobe Campaign 控制面板

我們已新增相關功能，協助管理員使用者從「控制面板」委派子網域並續約 SSL 憑證。

如需詳細資訊，請參閱以下頁面：

* 設定新的子網域 - [詳細資訊](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* 子網域的 SSL 憑證續約 - [詳細資訊](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>這些功能將於 1 月底前，以測試版的形式推出，不過可能將會經過多次更新和修改，屆時恕不另行通知。

### 其他資源

* Adobe Campaign Standard：[文件](https://helpx.adobe.com/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文件](https://helpx.adobe.com/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020 年 1 月 11 日版本更新

| 檢視 | 功能 |
|------|---------|
| 轉換追蹤 | 為符合即將於 2 月 4 日發行之 Google Chrome 80 的新 Cookie 控制需求，所有 Advertising Cloud Cookie 均已完成更新。此次變更是由 Adobe 伺服器使用現有的 Cookie 來執行，因此對訪客的量度沒有任何影響。不需使用任何廣告商更新。 |
| 深入分析 > 警示測試版、搜尋 > 促銷活動 | (僅供搜尋帳戶使用的測試版功能) 新的通知測試版可讓您建立通知範本，以識別任何搜尋促銷活動、廣告群組、關鍵字或一段時間內符合特定條件的廣告 (例如成效量度)，接著發出警示。警示功能適用於單一廣告商。 |
| 報表 | 產品清單型廣告的資料現已納入「標籤分類」、「標籤值」、「競標規則」和「規範」報表之中。 |
