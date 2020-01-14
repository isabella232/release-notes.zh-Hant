---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: d92cffebc2db7e6a6d7d7b531390b6e307b2943e

---


# 提早存取- Adobe Experience cloud發行說明- 2020年1月

Adobe Experience Cloud 中的新功能及修正項目。

>[!IMPORTANT]
>本頁包含發行前內容，並可能會在每個產品的計畫發行前變更。

>[!NOTE]
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期：2020年1月16日**

* [Adobe系統狀態](#status)
* [Experience cloud介面和核心服務](#ecloud)
* [Experience Platform](#platform)
* [行動服務與行動SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud)

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe System Status {#status}

[!UICONTROL Adobe System Status] 提供有關Adobe雲端產品與服務中斷、中斷及維護事件的詳細資訊、狀態更新及電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/)。

**新功能**

* 使用您的Adobe ID，您可以根據產品、地區和事件偏好設定來訂閱事件通知。 設定其訂閱偏好的使用者在開啟、更新或關閉時，只會收到相關產品事件和維護事件的通知。 請造訪status.adobe.com/subscriptions [開始](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今天推出新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 訂閱主動式電子郵件通知 | <ul><li>支援Experience Cloud、Creative Cloud、Document Cloud、Adobe Experience platform和Adobe服務</li><li>支援地區和事件類型偏好設定</li></ul> |
| 管理通知偏好設定 | <ul><li>隨時編輯和儲存通知偏好設定</li><li>隨時取消訂閱通知</li></ul> |
| 取得個人化且更快速的電子郵件傳送 | <ul><li>事件一開啟、更新或關閉，就會立即傳送事件通知</li><li>僅接收與您設定的偏好設定相符的相關事件通知</li><li>根據您帳戶偏好設定中設定的語言接收本地化通知</li></ul> |
| 取得個人化的產品內通知 | <ul><li>符合通知偏好設定和產品權益的事件會出現在「公告」面板中</li></ul> |

## Experience Cloud interface and core services {#ecloud}

Experience cloud介面中的新功能和修正，包括管理和核心服務（客戶屬性、觀眾、觸發器、Cookie等）。

### 統一的產品網域

Adobe正在更新網域和介面標題，以統一並改善您在所有Experience cloud應用程式中的體驗。 這些增強功能旨在以小型但重要的方式簡化您的體驗。 這些增強功能不會變更您目前的工作流程。

更新包括：

* 新的解決方案URL: `experience.adobe.com/<application name>`:
   * 所有產品最終都會採用此URL模式。 尋找新的URL以在整個月內生效。
   * 支援的瀏 [!DNL Microsoft Edge]覽器包 [!DNL Google Chrome]括、 [!DNL Firefox]、 [!DNL Safari]和 [!DNL Opera] （最新版本）。
   * (僅[!DNL Safari] 限)網域變更可能導致Cookie問題 [!DNL Safari]。 Unchecking _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* 更輕鬆地在組織之間切換或切換至不同的應用程式。
* 改良的產品說明：Experience League  已整合至產品中，因此說明搜尋也包含社群論壇和視訊內容的結果。 這項變更可簡化對更多內容的存取，並協助您充份運用Experience Cloud。 此外，按一 **[!UICONTROL 下「說明]**>**[!UICONTROL &#x200B;意見回應]** 」以報告問題或與Adobe分享您的想法。
* 改進通知：「通 [!UICONTROL 知] 」下拉式功能表現在有兩個標籤，一個用於您自己的產品通知，另一個用於全域產品公告。

**** 注意：摘 [!UICONTROL 要] (Feed)頁面已於2020年1月停用。 請參閱產品中的淘汰通知。

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

### Experience Cloud Cookie

Adobe正在調整 `same-site` Cookies的設定，以準備Chrome在Chrome 80中所做的變更（將於2020年2月發行）。

您不需要進行變更，除非您使用CNAME進行第一方資料收集，但在多個網域（友好的第三方網域）上使用該CNAME，且您不使用Experience Cloud（訪客）ID服務。 在Chrome 80版本中，Chrome會自動為Analytics訪客ID cookie提供SameSite值，以 `Lax,` 防止其用於其他網域。 如果您想要在網域間繼續使用CNAME，您必須聯絡Adobe客戶服務，並要求他們將您CNAME的SameSite值變更為 `None.`

請注意，Adobe建議您針對每個網域使用個別的CNAME，不論您是否使用Experience Cloud ID服務。

[更多內容…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全性佈告和諮詢](https://helpx.adobe.com/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## Mobile Services and Mobile SDKs {#mobile}

2020年1月16日：4.18.0版

* 贏取——新增新的API `Analytics.processGooglePlayInstallReferrerUrl(final String url)`，以支援「安 [!DNL Google Play] 裝反向連結API」。

如需安裝反向連結API的詳細資訊，請參閱「仍然 [使用InstallBroadcast?」 在2020年3月1日前切換至播放反向連結API](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正：

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- | 
| 分析工作區——自由表格產生器 | 啟用「表格產生器」後，您可以拖放許多維度、劃分、量度和區段，以建立可回答更複雜商業問題的表格。 資料不會立即更新。 而是在您按一下「建置」 **[!UICONTROL 後進行更新]**，在您知道要建立的表格後，為您節省時間。 此外，此功能還提供：<ul><li>**預覽**:您可以先預覽表格格式，再花時間來轉換真實資料。</li><li>**彈性的列與劃分設定**:您可以為每個維度列設定行和劃分層級。 以前，工作區強加的預設值在資料傳回後，才會變更。</li><li>**依職位劃分**:您可以設定維度行，以一律 _依位置劃分_ ，而 _非依特定項目_ （預設值）劃分。</li><li>**手動靜態列順序**:您可以手動對靜態行排序，以便表行按需顯示。 以前，靜態列只能依量度欄或依字母順序排序。</li></ul>當這項功能於1月稍後發行時，相關檔案將會發佈。 |
| 跨裝 [!UICONTROL 置分析] (CDA)的新已識別狀態維度 | 我們將新增名為「已識別狀 [!UICONTROL 態」的維度] ，加入CDA虛擬報表套裝。 維有兩個可能的值， _Identified_ 和 _Uniformined_。 _已識別_ ：表示人員已由裝置圖表識別。 _未識別_ ：表示裝置圖表未識別該人員。<br>這表示CDA使用者現在可以建立計算量度，例如「裝置圖表涵蓋範圍 」，該量度說明虛擬報表套裝中有多少人是透過裝置圖表得知的。 此度量有助於疑難排解CDA壓縮率。 如果沒有人被識別出來，縫合的程度就會很低。 |
| 資料倉庫API中的VRS支援 | 虛擬報表套裝現在可透過資料倉庫API使用。 以前只能透過「資料倉儲」UI使用。 使用資料倉庫API時，您現在可以查看和查詢虛擬報表套裝，但前提是套用至虛擬報表套裝的區段與資料倉庫相容。 |
| 隱私權服務 API：CCPA | 加州消費者隱私權法案 (California Consumer Privacy Act, CCPA) 強化了美國加州居民的隱私權和消費者保護力道。本法自2020年1月1日起生效。<br><br/>CCPA 為加州居民提供了新的資料隱私權，例如有權存取和刪除其個人資料、有權得知其個人資料是否遭到販售或揭露 (以及對象是誰)，以及有權拒絕廠商販售其個人資料。<br><br/>隱私權服務支援拒絕銷售個人資料的要求。<br><br/>隱私權服務原為GDPR服務，並保留所有先前的功能，現在已擴充以支援CCPA。<br/><br/>[Analytics 中的 CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[隱私權服務概觀](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### 修正

* 修正警報通知無法傳送至埃及電話號碼的問題。 (AN-197079)
* 已修正的多個問題 [!DNL DFA Data Connector]。 (AN-193281、AN-193075、AN-193484、AN-193737)
* [!UICONTROL 報告與分析]:修正「產品轉換漏斗」報表被截斷並顯示不清楚數字的問題。 (AN-186901)
* 修正使用者無法在「工作區」專案中，以新「分類」架構為基礎，切換報表套裝的問題。 (AN-199076)
* 修正「計算量度」中 [!UICONTROL 的] 「累  計」功能無法正常運作的問題。 (AN-184257)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | 從2020年1月16日起，Adobe Analytics將開始移至新網域- `https://experience.adobe.com/analytics.`<br>**注意&#x200B;**:這項變更適用於使用其Adobe ID或Enterprise ID存取Analytics的所有使用者。<ul><li>網域變更在Safari中載入Analytics時，可能會造成Cookie問題。 Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. 您可以不產生任何問題地使用其他瀏覽器，因為這只會影響Safari使用者。</li><li>網域變更可能導致 [!UICONTROL Activity Map] 在某些特定情況下停 [止為某些客戶運作](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)。</li></ul> |
| 生命週期結束- Analytics舊版API | 2020 年 1 月 9 日 | 在2020年11月，下列Analytics舊版API服務將到期並關閉。 使用這些服務建立的目前整合將停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>舊版OAuth驗證（OAuth和JWT）</li></ul>我們提供舊版 [API EOL常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) ，以協助您回答問題並提供如何繼續的指引。 採用這些服務的API整合可移轉至 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email)[或2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。 舊版OAuth帳戶可移轉至 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics整合帳戶，此帳戶可用來存取1.4 Analytics API和2.0 Analytics API。 |
| **[!UICONTROL 檢視封存]**選項的 EOL | 2019 年 10 月 30 日 | 宣佈儀表板管理員 (**[!UICONTROL 元件 > 儀表板]**) 中的**[!UICONTROL &#x200B;檢視封存]**選項將於 2020 年 1 月終止服務。 |
| **[!UICONTROL 強制 IP 登入限制]**選項的 EOL | 2019 年 10 月 30 日 | 宣佈&#x200B;**[!UICONTROL 管理 > 公司設定 > 安全性]**選單中的 IP 登入白名單 (**[!UICONTROL &#x200B;強制 IP 登入限制]**) 功能將於 2020 年 1 月終止服務。 |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 對於倫敦和新加坡的客戶，我們不再支援於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間的代理資料。<br/><ul><li>如果在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 關於 Analytics 使用者 `createDate` 欄位的近期變更 | 2019 年 8 月 30 日 | In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience manager中新增的修正和功能。

### Audience Manager 中的新功能、增強功能和修正 {#aam-features}

| 功能 | 說明 |
| -----------| ---------- |
| [加州消費者隱私權法案(CCPA)支援與隱私權檔案大修](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | 2020 [年1月1日生效的加州消費者隱私法(CCPA)](https://www.caprivacy.org/about)，為加州居民提供個人資訊的新權利，並對在加州經營業務的特定實體負責資料保護。 <br><br> Audience manager可協助您透過 [Adobe Experience Platform Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) （資料存取和刪除要求）等隱私權工具，遵守隱私權法規所規定的義務。 <br><br> 我們已更新目前 [的退出管理程式](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) ，加入退出任何宣告的ID（例如CRM ID）。 如果宣告的ID選擇退出，則宣告的ID和最後一個連結的裝置將選擇退出Audience manager資料收集。 選擇退出請求現在也會以批次和即時方式， [將取消分段請求傳送給支援此功能的](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) 「目標合作夥伴」。 <br><br> 此外，我們已重新設計了 [Data Security](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)、 [Data Privacy](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)和 [](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) Data Governance檔案，讓您更容易找到符合上述法規的必要資訊。 |

### 修正和改良 {#aam-fixes-and-improvements}

* 修正「建立目 [!UICONTROL 標] 」工作流程中，在選擇「整合平台」類別後，「基本資訊」 ****類別會消失，而無法完成工作流程的問題。 (AAM-52397、AAM-52414)
* 我們修正了Apple Safari和Mozilla Firefox [!UICONTROL 瀏覽器無法載入「建立／編輯] 」目標頁面的錯誤。 (AAM-51784)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品維護

* **AEM 6.5.3.0** AEM 6.5,Service Pack 3.0（2019年12月12日發行的6.5.3.0）是重要的更新，其中包含自2019年4月AEM 6.5全面上市以來發行的關鍵客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4,Service Pack 7.0（2019年12月12日發行的6.4.7.0）是重要的更新，其中包含自2018年4月AEM 6.4全面上市以來發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 7（2019年12月12日發行的6.3.3.7）是重要的更新，其中包含自2017年4月AEM 6.3全面上市以來發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1提供「使用Okta進行單一登入」的更新，並可在「偏好設定」中指定暫存檔案的位置。 此版本不再支援AEM 6.3.x的案頭應用程式2.x。
   * [發行說明](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1結束對AEM 6.3.x的支援**

   自2019年4月起，Adobe Asset Link已不再支援AEM 6.3.x。 自2020年1月13日起，Adobe Asset Link 1.1將取消對AEM 6.3.x的支援。
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### 產品發行

* **新功能：AEM As a Cloud Service**

   [Adobe Experience Manager](https://www.adobe.com/marketing/experience-manager.html) (AEM)現已提供雲端服務。

   * [簡介](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [發行資訊](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [文件](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **自動化表單轉換服務**

   Automated Forms Conversion Service是一種自動將PDF表單轉換為精美的行動HTML表單的服務，於2019年12月12日正式推出。

   * [簡介](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [配置服務](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [將PDF表單轉換為可調整的表單](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### 自助式

* **預覽3D資產**

   AEM 6.5支援3D資產的上傳、傳送和互動式預覽，做為製作程式的一部分。 您可從AEM的資產詳細資訊頁面取得互動式3D檢視器。 檢視器除了其他功能外，還包含一系列互動式相機控制項，可讓您環繞、縮放和平移3D資產。
請參閱 [預覽3D資產](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)。

* **核心元件**

   Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM 專案原型**

   [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) 的 [](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) ui.frontend模組是實用而有彈性的工具，可讓您更輕鬆地為AEM專案進行前端開發。

### 其他資源

* [AEM As a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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
| 加州消費者隱私法(CCPA) | CCPA是加州新推出的隱私法，協調並現代化2020年1月1日生效的資料保護要求。 CCPA適用於持有居住在加州之資料主體資料的Adobe Campaign客戶。 <br> 除了現有的隱私權功能（包括許可管理、資料保留設定和使用者角色）外，Adobe Campaign還可協助您做好CCPA的準備： <ul><li>__ 存取權&#x200B;_,_&#x200B;刪除權：我們運用了為GDPR新增的功能。 [更多詳情](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>您可以追蹤消費者是否已選擇退出個人資訊的銷售。 為此，您需要擴展「配置 [!UICONTROL 檔案] 」表，並添加 **[!UICONTROL 「退出CCPA」欄位]**。[更多詳情](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> 請參閱 [how-to影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| 工作流程即時監控 | 您現在可以使用預先定義的檢視來監視執行個體上所有工作流程的執行狀態。 <br> 如需詳細資訊，請參 [閱依據狀態篩選工作流程](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status)。 |
| 使用AMP製作互動式內容 | Adobe Campaign可讓您試用新的互動式 [AMP for Email](https://amp.dev/about/email/) （電子郵件格式），讓行銷人員在訊息中加入AMP元件，以利用豐富、動態和互動式內容來增強電子郵件體驗，並直接在訊息中採取行動。 <br> 此功能會以公開測試版發佈。 <br> 如需詳細資訊，請參閱詳細 [的檔案](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) ，以及 [教學影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)。 |
| 安全的 SMS 傳訊 (TLS) | 現已透過 Extended Generic SMPP Connector 支援安全的 SMS。如此可讓您加密連線至提供者。<br> **警告**:這項功能要求所有伺服器上都有最新的憑證。 無效、已撤銷或已過期的憑證會產生影響整體SMS傳送功能的錯誤。 <br>如需詳細資訊，請參閱[詳細文件](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)。 |

有關修正和改善項目，請參閱 [Adobe Campaign Classic 發行說明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)。

### Campaign Standard 19.4

| 功能 | 說明 |
| ------------- | ----------- |
| 加州消費者隱私法(CCPA) | CCPA是加州新推出的隱私法，協調並現代化2020年1月1日生效的資料保護要求。 CCPA適用於持有居住在加州之資料主體資料的Adobe Campaign客戶。 <br> 除了Adobe Campaign中已提供的隱私權功能（包括同意管理、資料保留設定和使用者角色）外，我們還將利用這個機會加入其他功能，以協助您做好CCPA的準備： <ul><li> 存取權與刪除權：我們運用了為GDPR新增的功能。 [更多詳情](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> 建立隱私權要求時，隱私權核心服務中已新增規則類型（GDPR或CCPA）。 此方法應用於所有存取和刪除請求。 不建議使用促銷活動API和介面來存取和刪除請求。 請參閱「已過 [時和已移除的功能」文章](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)。 </li><li> 「設 **定檔」資源已新增「CCPA選擇退出** 」欄位，讓Adobe Campaign使用者追蹤消費者是否選擇退出個人資訊銷售。 [更多詳情](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> 請參閱 [how-to影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)。 |
| Microsoft Dynamics 365整合(GA) | Adobe Campaign standard與Microsoft Dynamics 365的整合現已推出。 您將能夠將您的連絡人和自訂實體記錄從Dynamics 365傳輸至Campaign，並從Campaign將電子郵件事件資料傳回Dynamics 365，以便更好地協調銷售／行銷。 <br> 請參閱詳 [細檔案](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) ，以設定此整合併檢 [視操作視訊](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)。 |

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Adobe Campaign 控制面板

我們已新增功能，讓管理員使用者可從「控制面板」委派子網域並續約SSL憑證。

如需詳細資訊，請參閱以下頁面：

* 設定新子網域——閱 [讀更多](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* 續約子網域的SSL憑證——詳 [細資訊](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>這些功能將於1月底之前在測試版中提供，而且可能會經常更新和修改，恕不另行通知。

### 其他資源

* Adobe Campaign Standard：[文件](https://helpx.adobe.com/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文件](https://helpx.adobe.com/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign控制面板：文 [件](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) -發 [行說明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

2020年1月11日發行更新

| 檢視 | 功能 |
|------|---------|
| 轉換追蹤 | 所有Advertising Cloud cookie都已更新，以符合Google Chrome 80的新Cookie控制需求，該需求將於2月4日發行。 變更是使用現有Cookie從Adobe伺服器實作，對訪客量度沒有任何影響。 不需要任何廣告商更新。 |
| 前瞻分析>警報測試版、搜尋>促銷活動 | （僅限搜尋帳戶的測試版功能）新的警報測試版可讓您建立警報範本，以識別任何搜尋促銷活動、廣告群組、關鍵字或廣告何時符合特定條件— 例如效能量度— 然後產生警報。 警報適用於單一廣告商。 |
| 報表 | 產品清單廣告的資料現在已包含在「標籤分類」、「標籤值」、「競標規則」和「約束」報表中。 |
