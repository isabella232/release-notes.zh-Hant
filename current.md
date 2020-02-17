---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: d2b03da33ea1c49d683fc9486ae8b7d7bc59c87f

---


# 提早存取- Adobe Experience cloud發行說明- 2020年2月

Adobe Experience Cloud 中的新功能及修正。

>[!IMPORTANT]
>此頁面含有搶鮮版內容，於預計發行前可能會有所變更。

>[!NOTE]
>訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期: 2020 年 2 月 20 日**

（特定產品發行日期可能有所不同）

最新更新：2020年2月10日

* [Adobe 系統狀態](#status)
* [Experience Cloud 介面與核心服務](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services 與 Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Adobe 系統狀態 {#status}

[!UICONTROL Adobe 系統狀態]提供 Adobe 雲端產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/)。

**新功能**

* 使用您的Adobe ID，您可以根據您的產品、地區、事件和語言偏好設定來訂閱事件通知。 設定其訂閱偏好的使用者在開啟、更新或關閉相關產品事件和維護事件時，會立即收到通知。 若要開始設定，請前往 [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit)。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| -----------| ---------- |
| 更快速地瞭解產品活動 | <ul><li>在即將到來的服務維護前30天獲知。 此功能提供更多的前置時間來評估對業務運營的潛在影響，使您能夠在需要時實施緩解計畫。</li><li>進階通知可在網頁／行動裝置／平板電腦介面上使用，也可透過電子郵件通知取得。</li></ul> |
| 根據偏好的語言個人化您的體驗 | <ul><li>選擇電子郵件通知的偏好語言。 自訂功能現在提供十九種語言版本。</li></ul> |
| 改善訂閱和通知使用者體驗 | <ul><li>只要按一下，即可指定您要訂閱之所有產品的地區和事件偏好設定。</li><li>當潛在問 _題提升_ 為次要或主要問 _題時_ , _收到通知_ 。</li><li>當任何產品或事件狀態更新時，瀏覽器頁面會自動重新整理。</li></ul> |

## Experience Cloud 介面與核心服務 {#ecloud}

Experience Cloud 介面中的新功能和修正，包括管理和核心服務 (客戶屬性、對象、觸發器、Cookie 等)。

**修正**

* **** 客戶屬性：客戶屬性UI現在會顯示Target中同步的其他個人檔案狀態。 (MCUI-10231)
* **** 觸發器核心服務：由於使用不當，已移除建立放棄類型觸發器時的傾向分數「30天內回報的可能性」。 (MCUI-10056)

### 統一產品網域

Adobe 正在更新網域和介面標題，以統一及提升您在所有 Experience Cloud 應用程式中的體驗。這些增強功能的設計目的，是要透過改善重要的細節，簡化您的使用體驗。這些增強功能不會變更您目前的工作流程。

更新包括：

* 新解決方案 URL：`experience.adobe.com/<application name>`：
   * 所有產品最終都會採用此 URL 模式。尋找新的 URL，使效期能持續一整個月。
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **注意：**&#x200B;雖然 Experience Cloud 介面可支援這些瀏覽器，但個別解決方案可能不會支援所有瀏覽器 (例如 [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) 不支援 [!DNL Opera]，[Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) 不支援 [!DNL Safari])。
   * (僅限 [!DNL Safari]) 網域變更可能導致 [!DNL Safari] 發生 Cookie 問題。Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* 在組織或不同應用程式之間更輕鬆地切換。
* 改良產品說明：[!UICONTROL Experience League] 已整合至產品中，因此搜尋說明內容時，搜尋範圍會包含社群論壇和視訊內容。這項變更可讓您輕鬆存取更多內容，協助您充份運用 Experience Cloud。此外，按一下&#x200B;**[!UICONTROL 「說明]** > **[!UICONTROL 意見回饋」]**&#x200B;即可回報問題，或與 Adobe 分享您的想法。
* 改良通知：[!UICONTROL 「通知」]下拉式選單現在提供兩個標籤，其中一個顯示您的產品通知，另一個顯示全球產品公告。

**注意：**[!UICONTROL 「摘要」]頁面將於 2020 年 1 月汰除。請參閱產品中的淘汰通知。

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全性佈告和諮詢](https://helpx.adobe.com/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## Mobile Services 與 Mobile SDK {#mobile}

**2020 年 2 月 4 日：4.19.0 版**

此版本已進行下列更新：

**** 生命週期：已新增新的API, `pauseCollectingLifecycleData`以緩解某些舊iOS裝置回報的異常作業長度資料。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正：

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features) (2020 年 1 月 21 日更新)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **使用**&#x200B;跨裝置分析的組織適用的新工作區範本：此範本顯示CDA如何有效地將造訪連結在一起，並教育您瞭解CDA專屬的維度和量度。 需要使用CDA的報表套裝。 如需 [詳細資訊，請參閱設定跨裝置分析](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) 。
* **** CDA為使用專用圖表的組織聯繫延遲時間會縮短為一天：專用圖形功能已增強，可減少從每週批次處理到每日重新整理的圖形產生延遲，讓CDA客戶存取更新的識別圖形和連結。
* **** 實驗室（技術預覽）:此新的Analytics功能可讓您在生產中測試新功能原型，並為Adobe提供有價值的意見回饋。 [更多詳情...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **工作區中的新快速鍵：**<ul><li>收合／展開所有面板： `alt + m`</li><li>折疊／展開活動面板： `alt + ctrl + m`</li><li>搜尋左側欄： `ctrl + /`</li><li>移至下一個面板： `alt + Right Key`</li><li>移至上一個面板： `alt + Left Key`</li></ul>[更多詳情...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **其他工作區增強功能：**<ul><li>當面板或視覺化放入 [!UICONTROL Workspace]時，左側導軌會自動切換至元件，讓工作流程更順暢。</li><li>範本元件現在可以依據（例如標籤、標示為我的最愛、已核准）進行設定。</li><li>篩選的量度和區段清單會 `+` 提供按鈕，讓您在找不到所需項目時新增元件。</li></ul>
* 「工 **作區** 」除錯程式已新增至「說明」功能表，讓您能以更順暢的方式啟用它來除錯「工作區」請求。 [更多詳情...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** 以Chromium為基礎的Microsoft edge瀏覽器：此版本包含變更，可辨識以Chromium為基礎的Microsoft edge瀏覽器（79版及更新版本）以用於報告。

#### 修正

* 修正區段UI指出「行 [!UICONTROL 銷管道」維度與「資料倉儲」相容]，但實際上不相容的問題。 未來，「區段產 [!UICONTROL 生器] 」將不再將這些維度顯示為與 [!UICONTROL 資料倉庫相容] 。 (AN-202297)
* 已修正在Analytics中更新的已發佈區段名稱，在24小時內未在Audience manager中更新的問題。 (AN-199974)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | `https://experience.adobe.com/analytics.`<br>** 2020年1月16日，Adobe Analytics開始移轉至新網域- **注意：這項變更適用於使用其Adobe ID或Enterprise ID存取Analytics的所有使用者。<ul><li>這項網路異動可能會在 Safari 中載入 Analytics 時造成 Cookie 問題。Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. 只有 Safari 使用者會受到影響，建議使用其他瀏覽器，以免發生這類問題。</li><li>網域變更可能會導致 [!UICONTROL Activity Map] 在[部分特定情況下](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)停止運作。</li></ul> |
| 終止服務 - Analytics Legacy API | 2020 年 1 月 9 日 | 自 2020 年 11 月起，下列 Analytics Legacy API 服務將終止並關閉。透過這些服務建立的整合應用將會停止運作。 <ul><li>1.3 Analytics API</li><li>1.4 SOAP Analytics API</li><li>Legacy Oauth 驗證 (Oauth 和 JWT)</li></ul>我們提供 [Legacy API EOL 常見問答集](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)，以協助回答您的問題，並指引您展開後續操作。採用這些服務的 API 整合應用可移轉為 [1.4 Analytics REST API](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 或 [2.0 Analytics API](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)。Legacy Oauth 帳戶可移轉為 [Adobe IO](https://console.adobe.io/home?mv=email) Analytics 整合帳戶，藉以存取 1.4 Analytics API 和 2.0 Analytics API。 |
| **[!UICONTROL 檢視封存]**&#x200B;選項的 EOL | 2019 年 10 月 30 日 | 宣佈儀表板管理員 (**[!UICONTROL 元件 > 儀表板]**) 中的&#x200B;**[!UICONTROL 檢視封存]**&#x200B;選項將於 2020 年 1 月終止服務。 |
| **[!UICONTROL 強制 IP 登入限制]**&#x200B;選項的 EOL | 2019 年 10 月 30 日 | 宣佈&#x200B;**[!UICONTROL 管理 > 公司設定 > 安全性]**&#x200B;選單中的 IP 登入白名單 (**[!UICONTROL 強制 IP 登入限制]**) 功能將於 2020 年 1 月終止服務。 |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 對於倫敦和新加坡的客戶，我們不再支援於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間的代理資料。<br/><ul><li>如果在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| 關於 Analytics 使用者 `createDate` 欄位的近期變更 | 2019 年 8 月 30 日 | 2019 年 10 月或 11 月期間，Analytics 使用者的 `createDate` 欄位已從美國太平洋時間更新為格式正確的日期/時間值，並附上時區資訊。(AN-183468) |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html)。2020年2月13日發行版本2.18.0。

## Audience Manager {#aam}

Audience Manager 新增的修正項目和功能。

### Audience Manager 中的新功能、增強功能和修正 {#aam-features}

| 功能 | 說明 |
|----|----|
| [活動使用情況報告](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | 「活 [!UICONTROL 動使用狀況報表] 」可協助您檢視及追蹤Audience Manager例項的活動使用狀況，讓您清楚瞭解活動使用狀況與合約承諾的比較。 |

### 修正和改良 {#aam-fixes-and-improvements}

* 修正造成目標建立流程中斷「整合帳戶」選取UI的錯誤(AAM-52414)。
* 已修正導覽演算法模型建立流程時造成UI中斷的錯誤(AAM-37942)。
* 針對使用Adobe Experience platform整合的客戶，在新目的地或現有目的地儲存「資料匯出控制」時，造成「資料匯出」選項無法儲存的錯誤已經修正(AAM-52814)。
* 修正造成第三方特徵建議在名稱中包含垂直號字元(`|`)的特徵上運作不正確的錯誤(AAM-51635)。
* UI中的多種可存取性改進。

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

* **Cloud Manager 2020.2.0**

   Cloud Manager 2020.2.0可簡化Adobe Experience Manager雲端服務沙盒的自助服務管理。

   請參閱[版本說明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)。

### 自助式

* **AEM As a Cloud Service的教學課程**

   快速開始使用AEM [的Cloud Service教學課程](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html)。

* **AEM Forms互動式通訊批次API**

   AEM Forms互動式通訊的批次API可讓客戶自動或隨選產生多種互動式通訊。 客戶可同時產生列印和網頁輸出。
請參 [閱使用批次API產生多種互動式通訊](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html)。

* **JEE上AEM Forms的支援平台**

   新增對JEE客戶上AEM Forms的Oracle 19c支援。
請參 [閱「JEE上AEM Forms的支援平台」](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html)。

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

### Campaign Classic 19.2.3

若需修正和改善項目的相關資訊，請參閱 [Adobe Campaign Classic 發行說明](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html)。

### Campaign Standard 20.1

若需修正和改善項目的相關資訊，請參閱 [Adobe Campaign Standard 發行說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)。

### 其他資源

* Adobe Campaign Standard：[文件](https://helpx.adobe.com/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文件](https://helpx.adobe.com/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign 控制面板：[文件](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [發行說明](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

更新日期：2020 年 2 月 10 日 (適用於 2 月 8 日發行的版本)

| 檢視 | 功能 |
|------|---------|
| 產品組合 | 現在起，您能在產品組合中新增 Yahoo! Japan Display Network (YDN) 促銷活動，將促銷活動預算和廣告群組層級的出價最佳化。廣告群組中的所有廣告會套用相同出價。產品組合模擬作業會包含 YDN 促銷活動的資料。 |
| 搜尋 > 大量表單 | 現在，您可以使用大量表單來建立、編輯及刪除 Google 回應式搜尋廣告 (RSA)。Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| 搜尋 > 促銷活動、報表 | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

如需Magento版本注意事項，請參閱：

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
