---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: 發行說明
last-update: 2019 年 10 月 日
author: mfrei
translation-type: tm+mt
source-git-commit: 59bbe7ddd5cbbcb653d6c44223b644257dd94cb4

---


# Early Access - Experience Cloud Release Notes - October 2019

Adobe Experience Cloud 中的新功能及修正。

>[!IMPORTANT]
>
>此頁面含有搶鮮版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. 產品發行後才會發佈的新資訊皆會標示發佈日期。

## 發行日期: 2019 年 10 月 10 日

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) （解決方案說明的連結）

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform Launch](#launch)
* [安全性佈告欄和建議](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |  
| 隱私權服務API:CCPA | 加州消費者隱私法(CCPA)加強了美國加州居民的隱私權和消費者保護。 本法定於2020年1月1日生效。<br><br/>CCPA為加州居民提供新的資料隱私權，例如存取和刪除其個人資料的權利，以知道其個人資料是否被出售或被披露（以及向誰），以及拒絕銷售其個人資料。<br><br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out of the selling of personal data.<br><br/>隱私權服務先前稱為GDPR服務，並保留所有先前的功能，現在已擴充以支援CCPA。<br/>CCPA in Analytics: (content forthcoming) <br><br/>[Privacy Service Overview](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| 隱私權報告：Analytics管理控制台 | 啟用Analytics的隱私權報表會將一組保留變數新增至報表套裝。  這些變數設計為協助在點擊層級收集消費者同意資料。<br/>新維度：<br/><ul><li>同意管理選擇退出</li><li>Consent Management Opt-In</li><li>Consent Management Variables: <!-- `[Link to new Consent Variables page in Analytics]()` --></li></ul> |
| Audio and Video Analytics: Privacy Support | Two new variables have been added to the Media Collection API:<br/><ul><li> analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul>這些是可選變數，可用於擷取點擊時消費者同意的狀態。 [媒體收集API文](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/>件新的Analytics同意管理上下文資料變數已新增至同盟分析表單。 這些變數現在可用於標籤聯盟的退出分享或銷售點擊。 [Download Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| 分析工作區：更新至自由表格總計 | Freeform tables now include two totals, a Table total and a Grand total. ********&#x200B;套用報表篩選的「表格」 [總列帳戶](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 。 以前，只有區段會影響總計。 [更多](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>資訊此外，「 **[!UICONTROL 欄設定」中已新增「顯]** 示總計」和「顯示總計 **[!UICONTROL 」選項]******。<br/>對自由格式總計的這項變更會更新相依視覺化(例如連結的摘要數字視覺化 **** )，以及匯出的CSV和PDF資料。 |
| 分析工作區：移除「未指定／無」的選項 | The ability to easily remove ‘Unspecified (None)’ has been added as an option to report filters. |
| 分析工作區：取代紫色粒度元件 | 紫色詳細程度的時間元件（分鐘、小時、日、周、月、季、年）已過時。 紫色時間元件的行為一向與橘色尺寸元件完全相同，因此這項變更將簡化體驗。 **如果您先前使用** 其中一個紫色時間元件，則不需要採取任何動作。<br/>With this change, the purple Time section has also been renamed to Date Ranges.******** |

#### 修正

* 分析工作區：修正搜尋左側導軌中的維度項目時，搜尋結果不正確的問題。 (AN-185065)
* 已修正在Adobe Audience Manager(AAM)中無法刪除或取消發佈共用區段的問題。 修正是，如果AAM沒有回應，則不會刪除區段。 (AN-185882、AN-185883、AN-184607)
* 修正臨機分析中無法載入區段的逾時問題。 (AN-184654)
* Fixed an issue that occurred when the report suite you last used was subsequently hidden or you no longer had permissions to access this report suite. 在此情況下，您無法再透過Experience cloud登入。 (AN-181777)
* 修正區段中的逾時問題，此問題會讓您難以根據區段建立VRS。 (AN-179684)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. |
| San Jose FTP Broker Ending for London and Singapore | 2020 年 7 月 | 對於倫敦和新加坡的客戶，我們將不再支援在倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com之間進行資料中介](ftp://ftp.omniture.com/)。<br/><ul><li>For London use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>若是新加坡， [請使用ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新為 Analysis Workspace 自由表格總計 | 2019 年 9 月 12 日 | 在2019年10月，自由表格總計行將開始計入套用的報 [表篩選](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 。 就目前而言，總計僅計入分段。經過此變更後，將會更新依據的視覺效果 (例如連結的[!UICONTROL 摘要數字]視覺效果)，以及 CSV 和 PDF 資料。 |
| 關於 Analytics 使用者 `createDate` 欄位的近期變更 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月期間，系統會使用時區資訊，將 Analytics 使用者的 `createDate` 欄位從美國太平洋時間更新為格式正確的日期/時間值。(AN-183468) |
| 支援歷史時區位移 | 2019 年 8 月 8 日 | 現在起，Analytics 會自動處理時間戳記點擊的時區位移。8 月 8 日完成此變更後，系統載入歷史資料加以處理時，便不需要在傳送資料前調整時區位移。 |
| 分類規則產生器限制 | 新增日期: 2019 年 6 月 5 日 | 這些限制並非新鮮，但已新增至此處的文 [件](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)。 |
| 新區段運算子限制 | 新增日期: 2019 年 5 月 31 日 | 自 2019 年 7 月 18 日起，區段運算子&#x200B;_「包含任何」_、_「不包含任何」_、_「包含所有」_&#x200B;以及&#x200B;_「不包含所有」_，每個輸入欄位僅限 100 個字詞。此限制將套用至在此日期之後的所有新區段和修改區段。超出限制的現有區段仍會繼續獲得支援，但無法修改或儲存，直到輸入欄位的字詞減少為止。現正套用這些限制，同時藉此努力改善查詢效能。 |
| **[!UICONTROL 日期啟用]**&#x200B;和&#x200B;**[!UICONTROL 數值 2 分類]**&#x200B;的支援變更 | 2019 年 5 月 28 日更新 | 匯入數值 2 與日期啟用分類的功能已自基底程式碼移除。此變更於 2019 年 7 月維護版本中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| _報表總數_&#x200B;計算方式變更 | 更新日期: 2019 年 7 月 9 日 | Adobe Analytics 於 **2019 年 6 月 18 日**&#x200B;統一所有維度和量度的&#x200B;_報表總數_&#x200B;計算方式。部分報表的總數因此有所變動，通常會是「Prop」或「客戶屬性」報表。在此變更前，無論報表中是否出現 _未指定_ 一項，部分「報表總數」納入或排除 _未指定_ 項目的情況不一。<br/>自 2019 年 6 月 18 日起，即使「未指定」並未出現在報表項目中，報表總數都會一律顯示 _未指定_ 。此外，在這項變更後，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;邏輯的區段可能會看到某些維度的不同結果，具體而言就是&#x200B;_未指定_&#x200B;維度針對反向連結類型維度具有「已輸入/已加上書籤」條列項目特殊名稱，或針對裝置類型維度具有「其他」條列項目特殊名稱等。到時，此變更將會影響 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和報表 API。 |
| 更新 Analysis Workspace 的 CSV 下載 | 2019 年 4月 10 日 | 自 2019 年 4 月 11 日起，Analysis Workspace 中的&#x200B;**[!UICONTROL 「CSV 下載」]**(和&#x200B;**[!UICONTORL 「複製到剪貼簿」]**) 功能已有諸多變動，移除了匯出資料中的格式設定。  <ul><li>不再使用千分位分隔符號。將繼續使用小數分隔符號，其將遵循&#x200B;**[!UICONTROL 「元件 &gt; 報表設定 &gt; 千分位分隔符號」]**&#x200B;中定義的格式。注意: 匯出的 CSV 會繼續引用使用逗號作為小數分隔符號的數值。</li><li>不再顯示貨幣符號。</li><li>不再顯示百分比符號。百分比將以小數形式表示，例如: 75% 會表示成 0.75。</li><li>時間會以秒數表示。</li><li>同類群組表格僅會顯示原始值; 百分比符號將會移除。</li><li>如果數字無效，則顯示空白儲存格。</li></ul> |
| 即將變更 Analysis Workspace 偵錯工具命令 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日**，開啟 Analysis Workspace 偵錯工具的控制台命令將變更為 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 自當天起將無法使用。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 終止 [!DNL Ad Hoc Analysis] 服務 | 2019 年 1 月 29 日 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 [!DNL Ad Hoc Analysis] 服務。我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，包括在此期間相容的 Java 版本，請造訪 [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace)。 |
| [!DNL Analytics] 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 [!DNL Analytics] 報表短連結。 |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動中 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的 [!DNL Live Stream] 端點可能會遭到停用。您可以聯絡客戶服務以查詢您的 [!DNL Live Stream] 端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 因為已不再支援 TLS 1.0，我們建議 [!DNL Report Builder] 使用者在 2019 年 2 月之前下載 5.6.21 版。在當天以後，舊版的 [!DNL Report Builder] 將無法繼續運作。 |

### [!DNL AppMeasurement] {#appm}

請參 [閱「Javascript適用的AppMeasurement」發行說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager 中的新功能、增強功能和修正

**修正和改良**

* 所有在2019年7月1日之後建立的客戶帳戶都會自動獲得授權， [!DNL Tableau] 讓他們可以存取其報表。 如果您的帳戶是在2019年7月1日之前建立，而您仍無權存取報表，請連 [!DNL Tableau] 絡客戶服務。
* We've removed incorrectly generated activity trait memberships for visitor profiles that did not have an ID synchronization with the trait data source (AAM-45371).
* We've removed invalid global device IDs from global data sources. 請參 [閱全域資料來源](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) ，瞭解Audience manager應接受哪些有效裝置ID(AAM-41259)。
* 修正當您嘗試刪除受保護的區段時，造成「區段」頁面停止回應的錯誤(AAM-49881)。
* 編輯「Twitter量身訂做的觀眾」的目標時， [!UICONTROL Account] （帳戶）選擇器現在只會在目標未指派帳戶 [!DNL Twitter Ads] 時啟用(AAM-49975)。
* Fixed a bug preventing users from disabling Audience Marketplace data feeds when subscriptions are disabled (AAM-49640).
* 我們對 Audience Manager 使用者介面的協助工具進行了幾項相關的改良。

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品維護

* **AEM 6.3.3.6**

   AEM 6.3、Service Pack 3、Cumulative Fix Pack 6（2019年9月25日發行的6.3.3.6）是重要的更新，其中包含自2017年4月AEM 6.3全面上市以來發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4,Service Pack 6.0（6.4.6.0於2019年9月19日發行）是重要的更新，其中包含自2018年4月AEM 6.4全面推出以來發行的重要客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0** AEM 6.5,Service Pack 2.0（2019年9月19日發行的6.5.2.0）是重要的更新，其中包含自2019年4月AEM 6.5全面上市以來發行的關鍵客戶修正。
   * [發行說明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### 自助式

* **Scene7: Reprocess Assets workflow**

   您現在可以重新處理已有現有處理設定檔的資料夾中的資產，而您稍後會加以變更。
請參 [閱編輯資料夾的處理設定檔後，重新處理資產](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)。

* **Integration of Dynamic Media Viewers with Adobe Analytics and Adobe Launch**

   Adobe Launch的Dynamic Media Viewers擴充功能以及Dynamic Media Viewers 5.13的發行，可讓Dynamic Media、Adobe Analytics和Adobe Launch的客戶在其Adobe Launch設定中使用Dynamic Media Viewers專屬的事件和資料。
See Integrating Dynamic Media Viewers with Adobe Analytics and Adobe Launch.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html)

* **AEM案頭應用程式**

   AEM desktop app 2.0 is now available for creatives, marketers, and line-of-business users, to work with AEM Assets.
See the AEM desktop app Release notes.[](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **核心元件**
   * 瞭解核心元件的本地化功能，以及它們如何使用AEM範本。
      [See the example.](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html)
   * 核心元件2.6.0提供體驗片段元件。 此元件現在可在GitHub上 [取得](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) ，以 [及製作檔案和開發人員詳細資](https://github.com/adobe/aem-core-wcm-components)訊以及專案下載。

* **AEM Assets**
   * 視覺／相似性搜尋功能的新檔案。
請參閱 [尋找類似影像](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)。
   * Connected Assets功能現在除了使用影像檔案格式外，還使用遠端DAM部署上可用的檔案。
請參 [閱「使用連線的資產在AEM Sites中共用DAM資產」](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html)。
   * 資產搜尋和搜尋的最新內容。 AEM _(Adobe Assets in AEM_ )主題中的「搜尋」資產是您的一站式服務，以取得有關使用、設定、疑難排解、限制和秘訣的資訊。
請參閱「 [在AEM中搜尋資產」](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html)。

### 其他資源

* [AEM 6.5 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older Versions of AEM Documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic說明首頁](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update – build 9032](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032)
* [Campaign Classic 19.1.6更新](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) -組建9035

### 其他資源

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
