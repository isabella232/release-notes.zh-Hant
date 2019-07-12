---
title: Adobe Experience Cloud 發行說明
description: 1919年月Experience Cloud發行說明
doc-type: 發行說明
last-update: 2019 年 7 月
author: mfrei
translation-type: tm+mt
source-git-commit: 78ffd561e625a5b75d2e6f3aa8c66629eda06c90

---


# 搶先使用 - Adobe Experience Cloud 發行說明

Adobe Experience Cloud 中的新功能及修正。

>[!IMPORTANT]
>
>此頁面含有搶鮮版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>訂閱 [Adobe 優先產品更新](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。您會在發行前三至五個工作日收到通知。產品發行後才會發佈的新資訊皆會標示發佈日期。

**發行日期: 2019 年 7 月 18 日**

* [核心服務與管理](#experiencecloud)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [促銷活動](#ac)
* [Target](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

Experience Cloud 介面 (包含[!UICONTROL 平台]核心服務與產品管理) 發行說明。

* [Experience Cloud ID 服務](#ecid)
* [Mobile Services 與 Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [安全性公告和建議](#security)

### Experience Cloud ID 服務 {#ecid}

**修正和更新**

* `cookieDomain` 組態更新：未設定 `cookieDomain` 時 `initConfig` ，程式庫會自動指派頂層Cookie網域。(CORE - 29223)

* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE - 31287)

* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE - 29719)

* 修正jQuery3.2.1中的弱點問題。(CORE - 31183)

* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE - 30623)


See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services 與 Mobile SDK {#mobile}

iOS和Android已更新如下：

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target：已修正記憶體洩漏。
* The double encoding of the visitor ID URL, which contains characters such as _%25_, was being flagged in security reviews. 此問題已修正。

**Android**

* 目標：所有請求現在都會在URL查詢參數中納入用戶端和sessionId。
* 修正當訊息使用空點進URL觸發時，Android應用程式會當機的問題。
* The double encoding of the visitor ID URL, which contains characters such as _%25_, was being flagged in security reviews. 此問題已修正。

如需產品文件，請參閱 [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html)。

如需 Mobile SDK 的詳細資訊，請參閱[適用於 Experience 解決方案的 Android SDK 4.x](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) 和[適用於 Experience Cloud
 解決方案的 iOS SDK 4.x](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html)。

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## Analytics {#analytics}

* [Adobe Analytics 中的新功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)

### New features in Analytics {#aa-features}

如需產品文件，請參閱 [Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

| 元件 | 說明 |
| -----------| ---------- |  
| Adobe Analytics Labs | _Labs_ 是新的原型入口網站，讓您提早檢視新興技術，讓您影響未來的解決方案優先順序和開發。 |
| Analysis Workspace-世代分析增強功能 | 新增了「新世代分析」設定： <ul><li>僅顯示%</li><li>四捨五入至最接近的整數</li><li>沿著頂端顯示平均%列</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. 以前回顧期間最多為個月。如此可更輕鬆地比較去年的頁面或促銷活動，最多18個月前。 |
| Analytics 資料摘要 | Users can now see the history for all feeds that are enabled with the _Make Feed Visible to Customer_ flag. |

#### [!DNL Analysis Workspace] 修正

* 修正劃分維度時，會向下顯示多位元組字元的問題。(AN-180112)
* 修正視覺效果錯誤的問題-當發生視覺化錯誤時，我們現在會顯示紅色錯誤列。(AN-175542)
* 修正本地化環境中維度名稱顯示為英文的問題。(AN-178695)

#### [!DNL Reports & Analytics] 修正

* 修正即時深入報告中的折線圖空白的問題。(AN-181690)

### 給 Analytics 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 分類規則產生器限制 | 新增日期: 2019 年 6 月 5 日 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| 新區段運算子限制 | 新增日期: 2019 年 5 月 31 日 | 自 2019 年 7 月 18 日起，區段運算子「包含任何」、「不包含任何」、「包含所有」以及「不包含所有」，每個輸入欄位僅限 100 個字詞。此限制將套用至在此日期之後的所有新區段和修改區段。超出限制的現有區段仍會繼續獲得支援，但無法修改或儲存，直到輸入欄位的字詞減少為止。現正套用這些限制，同時藉此努力改善查詢效能。 |
| **[!UICONTROL 日期啟用]** 和 **[!UICONTROL 數值 2 分類]** 的近期支援變更 | 2019 年 5 月 28 日更新 | 匯入數值 2 與日期啟用分類的功能已自基底程式碼移除。此變更預計於 2019 年 7 月維護版本中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| _報表總數_ 計算方式近期變更 | 更新日期: 2019 年 7 月 9 日 | Adobe Analytics 預計於 **2019 年 6 月 18 日** 統一所有維度和量度的 _報表總數_ 計算方式。部分報表的總數會因此有所變動，通常會是「Prop」或「客戶屬性」報表。在此變更前，無論報表中是否出現 _未指定_ 一項，部分「報表總數」納入或排除 _未指定_ 項目的情況不一。<br/>自 2019 年 6 月 18 日起，即使「未指定」並未出現在報表項目中，報表總數都會一律顯示 _未指定_ 。Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the &quot;Typed/Bookmarked&quot; line item for Referrer Type dimension or the &quot;Other&quot; line item for the Device Type dimension. 到時，此變更將會影響 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和報表 API。 |
| 更新 的 CSV 下載 [!DNL Analysis Workspace] | 2019 年 4 月 10 日 | 自 2019 年 4 月 11 日起，[!DNL Analysis Workspace] 中的 **[!UICONTROL 「CSV 下載」]**(和 **[!UICONTORL 「複製到剪貼簿」]**) 功能已有諸多變動，移除了匯出資料中的格式設定。  <ul><li>不再使用千分位分隔符號。將繼續使用小數分隔符號，其將遵循 **[!UICONTROL 「元件 &gt; 報表設定 &gt; 千分位分隔符號」]** 中定義的格式。注意: 匯出的 CSV 會繼續引用使用逗號作為小數分隔符號的數值。</li><li>不再顯示貨幣符號。</li><li>不再顯示百分比符號。百分比將以小數形式表示，例如: 75% 會表示成 0.75。</li><li>時間會以秒數表示。</li><li>同類群組表格僅會顯示原始值; 百分比符號將會移除。</li><li>如果數字無效，則顯示空白儲存格。</li></ul> |
| 即將變更 [!DNL Analysis Workspace] 偵錯工具命令 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日起**，開啟 [!DNL Analysis Workspace] 偵錯工具的控制台命令將變更為 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 自當天起將無法使用。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 終止 [!DNL Ad Hoc Analysis] 服務 | 2019 年 1 月 29 日 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 [!DNL Ad Hoc Analysis] 服務。我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，包括在此期間相容的 Java 版本，請造訪 [Discover Workspace](https://adobe.ly/discoverworkspace)。 |
| Analytics 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 Analytics 報表短連結。 |
| 終止支援 TLS 1.0 | 2019 年 1 月 10 日更新 | 自 2019 年 2 月 11 日起，Adobe Analytics 報表不再支援 TLS (傳輸層安全性) 1.0 加密技術。我們做出此次變更，持續努力維持安全性的最高標準，並確保客戶資料安全無虞。If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>自 2019 年 2 月 20 日起，Adobe Analytics 資料彙集機制不再支援 TLS 1.0。隨著此變更正式發佈，若終端使用者使用不支援 TLS 1.1 (含) 以上版本的舊款裝置或網頁瀏覽器，Adobe 將不再彙集其 Analytics 資料。我們預計這不會對客戶資料或報告造成重大影響。(若您的網站已不支援 TLS 1.0，則不受影響。)<br/>自 2019 年 4 月 11 日起，Adobe Analytics 報告 API 不再支援 TLS 1.0 加密技術。存取該 API 的客戶應確認他們不會受到影響。 <ul><li>使用 Java 7 搭配預設設定的 API 用戶端將需要[進行修改以支援 TLS 1.2](https://www.java.com/en/configure_crypto.html)。(請參閱 _變更用戶端端點預設 TLS 通訊協定版本: 從 TLS 1.0 到 TLS 1.2_。) </li><li>使用 Java 8 的 API 用戶端已預設為 TLS 1.2，應該不會受到影響。</li><li> 使用其他架構的 API 用戶端需聯絡其供應商，以瞭解 TLS 1.2 支援的詳細資訊。</li></ul> |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動中 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的 [!DNL Live Stream] 端點可能會遭到停用。您可以聯絡客戶服務以查詢您的 [!DNL Live Stream] 端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 因為已不再支援 TLS 1.0，我們建議 [!DNL Report Builder] 使用者在 2019 年 2 月之前下載 5.6.21 版。在當天以後，舊版的 [!DNL Report Builder] 將無法繼續運作。 |

### AppMeasurement {#appm}

發行日期：2019年月15日

**JavaScript 2.15.0**

* 已將DIL7.2新增至AppMeasurememt。(AN-175142)
* 修正Experience Cloud ID Service OptIn設為true時發生的問題，而MID不是在s. t()呼叫上產生，而不會重新載入頁面。(CORE - 30890)


請參閱 [AppMeasurement 版本歷史記錄](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)，此為下列平台上 AppMeasurement 之版本歷史記錄的內容:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone、XBOX、Silverlight 及 .NET
* BlackBerry
* Java
* PHP
* Symbian

### Data Workbench {#aa-dwb}

* Updated the help definition for [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) metric syntax documentation. (AN-180527)

如需最新資訊，請參閱 [Data Workbench 發行說明](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/)。

## Audience Manager {#aam}

**修正和增強功能**

* [!UICONTROL 在區段概述] 頁面上，區段儲存資料夾的寬度現在有彈性。這可讓您區分較長名稱的區段。(AAM-48400)

* Fixed an issue in [!UICONTROL Algorithmic Models], where moving the **Adjust Reach &amp; Accuracy** slider did not affect the model&#39;s reach or accuracy. (AAM-47996)

* 修正Analytics目的地中，下載與資料匯出控制項衝突及/或第三方資料共用原則衝突的區段. csv檔案的問題。(AAM-48100)

* 修正客戶登入Audience Manager使用者介面時，看到隨機「存取遭拒」錯誤的問題。(AAM-47632)


## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

下列產品的新功能資訊：

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Cloud Manager 2019.6.0 發行說明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### XML文件3.4

XML Document3.4解決方案現已推出。

***發行說明***

* 已針對AEM6.5新增支援。
* 編輯器變更：
   * 地圖層級預覽。
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * 表格-提供選取欄中多個儲存格並加以合併或合併的選項。
   * 表格-提供在網頁編輯器的「作者」模式中設定表格欄屬性的方式。
   * 表格-提供調整標準表格中欄比例和大小的方式。
   * 表格-在「作者」檢視中選取列和欄。
   * 表格-在表格儲存格對齊中啓用網頁編輯器中的樣式和屬性(對齊、驗證)。
   * 「完整標記檢視」的錯誤修正，包括複製和貼上和拖放內容的藍本。
   * 在「編輯器」標籤中顯示主題標題。
   * 已解決網頁編輯器中的效能問題。
* 翻譯時將基準傳輸至翻譯的內容。
* 翻譯工作流程期間的傳輸條件預設集。
* 已新增從基準套用標籤至地圖所有從屬單位的功能。
* 提供一個按鈕，將所有的從屬關係下載為郵遞區號。
* XHTML轉換為DITA轉換改良功能：
   * 產生的DIAMAP名稱現在等同於已上載zip檔案的名稱。
   * 新增對其他HTML元素和屬性的支援。
   * 支援並行html-zip檔案擷取。
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* 提供稽核記錄，以查看誰回復至哪個版本及其原因。
* AEM網站重新啓用：
   * 停用子地圖的重制。
   * 啓用後制工作流程可用於重新建立使用案例。
   * 針對區塊主題停用重新產生選項，並針對套用區塊屬性的上層主題提供選項。
* DITA搜尋現在適用於AEM資產搜尋的AND邏輯。
* 結果無法帶出儲存在翻譯輸出資料夾中的暫存檔案。
* 基線標籤：
   * 開啓基準時的效能改進。
   * 依日期選擇主題以處理用戶端時間戳記。
* 用於刪除標籤的API。

#### 產品維護

**AEM 6.2 SP1-CFP20**

AEM6.2Service Pack- Cumulative Fix Pack20(6.2.1.20)(6.2.1.20)是一項重要更新，其中包含自2016年12月AEM6.2SP全面上市以來發行的重要客戶修正。

* [發行說明](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM6.3.3.5(於2019年月日發行)是重要的更新，其中包含自2017年月AEM6.3全面上市以來的重要客戶修正。

* [發行說明](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM6.4.5.0是一項重要更新，其中包含自2018年月全面發行AEM6.4以來的重要客戶修正。

* [發行說明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM6.5.1.0是一項重要更新，其中包含自2019年月全面發行AEM6.5以來的重要客戶修正。

* [發行說明](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [AEM Forms CFP 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### 自助式

**AEM快取失效更新**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

### 其他資源

* [AEM 6.5 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [舊版 AEM 文件](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System 發行說明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## 促銷活動 {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

如需發行說明，請參閱：

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

如需產品文件，請參閱:

* Adobe Campaign Standard: [文件](https://helpx.adobe.com/support/campaign/standard.html) - [ 發行說明](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 功能影片](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [文件](https://helpx.adobe.com/support/campaign/classic.html) - [發行說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 功能影片](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Target {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

如需Magento Commerce和Magen Open Source版本注意事項的詳細資訊，請參閱：

* [Magento Open Source2.3.2發行說明](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magento Commerce2.3.2發行說明](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)