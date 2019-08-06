---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: 發行說明
last-update: 2019 年 8 月
author: mfrei
translation-type: ht
source-git-commit: b3fa98427b027218e9600cb4c5e10dd2ba880f89

---


# 搶先使用 - Adobe Experience Cloud 發行說明

Adobe Experience Cloud 中的新功能及修正。

>[!IMPORTANT]
>
>此頁面含有搶鮮版內容，於預計發行前可能會有所變更。

>[!NOTE]
>
>訂閱 [Adobe 優先產品更新](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。您會在發行前三至五個工作日收到通知。產品發行後才會發佈的新資訊皆會標示發佈日期。

**發行日期: 2019 年 8 月**

* [Experience Platform 和管理](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html) (解決方案說明連結)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) (解決方案說明連結)

## [!UICONTROL Experience Platform] 和管理 {#platform}

[!UICONTROL Experience Platform] 的發行說明、Experience Cloud 介面、產品管理、Experience Platform Launch、身分服務和安全性佈告欄。

* [Experience Cloud 介面](#core-services)
* [Experience Platform Launch](#launch)
* [安全性佈告欄和建議](https://helpx.adobe.com/tw/security.html) (所有 Adobe 產品)

### Experience Cloud 介面 {#core-services}

* 修正 Experience Cloud 登入時的重大問題，這會導致部分使用者從工作階段登出。(MCUI-6908)
* 更新 Experience Cloud 登入機制，以改善效能並減少延遲。(MCUI-6854、MCUI-6869、MCUI-6883)
* 更新介面外觀。(MCUI-6861、MCUI-6911、MCUI-6862)
* 修正 Experience Cloud [!UICONTROL Triggers] 的問題，此問題會導致錯誤詮釋 _Like_ 子句 (位於 [!UICONTROL Trigger] 定義中)。(MCUI-6611)

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html)。

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |  
| 支援 SameSite Cookie 設定 | Analytics 會將 SameSite Cookie 設定新增至所有 Cookie 集。此變更可讓您符合需有 SameSite Cookie 欄位的 Chrome 變更。 |
| Workspace: 將下拉式篩選器的項目上限從 50 個提升至 200 個 | 我們將下拉式篩選器中可放置的項目上限從 50 個提升至 200 個。此增強功能適合多種使用案例，例如將所有國家 (195) 新增至篩選器，或新增所有美國州和省 (52)。 |

#### 修正

* 修正全螢幕模式中即時報告文字顯示的問題。(AN-183168)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 分類規則產生器限制 | 新增日期: 2019 年 6 月 5 日 | 這些不是新限制，且已新增至 [此文件](https://docs.adobe.com/content/help/zh-Hant/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)。 |
| 新區段運算子限制 | 新增日期: 2019 年 5 月 31 日 | 自 2019 年 7 月 18 日起，區段運算子&#x200B;_「包含任何」_、_「不包含任何」_、_「包含所有」_&#x200B;以及&#x200B;_「不包含所有」_，每個輸入欄位僅限 100 個字詞。此限制將套用至在此日期之後的所有新區段和修改區段。超出限制的現有區段仍會繼續獲得支援，但無法修改或儲存，直到輸入欄位的字詞減少為止。現正套用這些限制，同時藉此努力改善查詢效能。 |
| **[!UICONTROL 日期啟用]**&#x200B;和&#x200B;**[!UICONTROL 數值 2 分類]**&#x200B;的近期支援變更 | 2019 年 5 月 28 日更新 | 匯入數值 2 與日期啟用分類的功能已自基底程式碼移除。此變更預計於 2019 年 7 月維護版本中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| _報表總數_ 計算方式近期變更 | 更新日期: 2019 年 7 月 9 日 | Adobe Analytics 預計於 **2019 年 6 月 18 日**&#x200B;統一所有維度和量度的 _報表總數_ 計算方式。部分報表的總數會因此有所變動，通常會是「Prop」或「客戶屬性」報表。在此變更前，無論報表中是否出現 _未指定_ 一項，部分「報表總數」納入或排除 _未指定_ 項目的情況不一。<br/>自 2019 年 6 月 18 日起，即使「未指定」並未出現在報表項目中，報表總數都會一律顯示 _未指定_ 。此外，在這項變更後，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;邏輯的區段可能會看到某些維度的不同結果，具體而言就是&#x200B;_未指定_&#x200B;維度針對反向連結類型維度具有「已輸入/已加上書籤」條列項目特殊名稱，或針對裝置類型維度具有「其他」條列項目特殊名稱等。到時，此變更將會影響 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和報表 API。 |
| 更新 的 CSV 下載 [!DNL Analysis Workspace] | 2019 年 4 月 10 日 | 自 2019 年 4 月 11 日起，[!DNL Analysis Workspace] 中的&#x200B;**[!UICONTROL 「CSV 下載」]**(和&#x200B;**[!UICONTORL 「複製到剪貼簿」]**) 功能已有諸多變動，移除了匯出資料中的格式設定。  <ul><li>不再使用千分位分隔符號。將繼續使用小數分隔符號，其將遵循&#x200B;**[!UICONTROL 「元件 &gt; 報表設定 &gt; 千分位分隔符號」]**&#x200B;中定義的格式。注意: 匯出的 CSV 會繼續引用使用逗號作為小數分隔符號的數值。</li><li>不再顯示貨幣符號。</li><li>不再顯示百分比符號。百分比將以小數形式表示，例如: 75% 會表示成 0.75。</li><li>時間會以秒數表示。</li><li>同類群組表格僅會顯示原始值; 百分比符號將會移除。</li><li>如果數字無效，則顯示空白儲存格。</li></ul> |
| 即將變更 [!DNL Analysis Workspace] 偵錯工具命令 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日起**，開啟 [!DNL Analysis Workspace] 偵錯工具的控制台命令將變更為 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 自當天起將無法使用。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 終止 [!DNL Ad Hoc Analysis] 服務 | 2019 年 1 月 29 日 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 [!DNL Ad Hoc Analysis] 服務。我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，包括在此期間相容的 Java 版本，請造訪 [Discover Workspace](https://adobe.ly/discoverworkspace)。 |
| [!DNL Analytics] 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 [!DNL Analytics] 報表短連結。 |
| 終止支援 TLS 1.0 | 2019 年 1 月 10 日更新 | 自 2019 年 2 月 11 日起，Adobe Analytics 報表不再支援 TLS (傳輸層安全性) 1.0 加密技術。我們做出此次變更，持續努力維持安全性的最高標準，並確保客戶資料安全無虞。如果您在 2019 年 2 月 11 日之後無法連接至 Adobe Analytics 報表，請將瀏覽器升級為 [最新版本](https://docs.adobe.com/content/help/zh-Hant/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html)。<br/>[!DNL Analytics]自 2019 年 2 月 20 日起，Adobe 資料彙集機制不再支援 TLS 1.0。隨著此變更正式發佈，若終端使用者使用不支援 TLS 1.1 (含) 以上版本的舊款裝置或網頁瀏覽器，Adobe 將不再彙集其 Analytics 資料。我們預計這不會對客戶資料或報告造成重大影響。(若您的網站已不支援 TLS 1.0，則不受影響。)<br/>自 2019 年 4 月 11 日起，Adobe Analytics 報告 API 不再支援 TLS 1.0 加密技術。存取該 API 的客戶應確認他們不會受到影響。 <ul><li>使用 Java 7 搭配預設設定的 API 用戶端將需要[進行修改以支援 TLS 1.2](https://www.java.com/en/configure_crypto.html)。(請參閱&#x200B;_變更用戶端端點預設 TLS 通訊協定版本: 從 TLS 1.0 到 TLS 1.2_。) </li><li>使用 Java 8 的 API 用戶端已預設為 TLS 1.2，應該不會受到影響。</li><li> 使用其他架構的 API 用戶端需聯絡其供應商，以瞭解 TLS 1.2 支援的詳細資訊。</li></ul> |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動中 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的 [!DNL Live Stream] 端點可能會遭到停用。您可以聯絡客戶服務以查詢您的 [!DNL Live Stream] 端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 因為已不再支援 TLS 1.0，我們建議 [!DNL Report Builder] 使用者在 2019 年 2 月之前下載 5.6.21 版。在當天以後，舊版的 [!DNL Report Builder] 將無法繼續運作。 |

### AppMeasurement {#appm}

[!UICONTROL AppMeasurement] 2.16.0 於 2019 年 8 月 8 日發行。

| 功能 | 說明 |
| -----------| ---------- |
| 適用於退出連結的 `sendBeacon` 支援 | 為退出連結實作 `sendBeacon` 支援 (在 [!UICONTROL AppMeasurement] 中)。這會改善退出連結追蹤，並可能導致流量增加。 |
| ECID/fid 值 | 現在，第一次點擊時會快取 ECID/fid 值，即使 OptIn 設定有所變更。 |
| DIL 9.3 | Audience Manager 模組已更新至 DIL 9.3 |
| 捲動範圍追蹤 | 在 s.ActivityMap.trackScrollReach 顯示開關，開啓或關閉捲動範圍追蹤。 |
| 訪客 ID 服務 4.4.0 | 升級 AppMeasurement 以使用訪客 ID 服務 4.4.0。 |

#### 修正

* 修正在 isReadyToTrack 為 true 之前發生的 AppMeasurement 佇列錯誤。

如需以下平台的 AppMeasurement 的發行歷程記錄，請參閱 [AppMeasurement 發行歷程記錄](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html):

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone、XBOX、Silverlight 及 .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**修正和改良**

* 「管理」標籤現在僅向具有管理權限的使用者帳戶顯示 (AAM-48557)。
* 列出使用者 API 現在會傳回完整使用者詳細資訊 (AAM-48662)。
* 您現在可以調整特徵檔案夾清單的大小 (AAM-48800)。
* 最佳化多個 UI 協助工具 (AAM-48865、AAM-48933)。
* 最佳化載入「管理」和「資料來源」頁面 (AAM-48514)。

## [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Adobe Campaign Standard

[Campaign Standard 19.3 版](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html)

| 功能 | 說明 |
| -----------| ---------- |  
| 外部 API 活動 (公開測試版) | 為更深度個人化，外部 API 活動可讓您透過 REST API 呼叫，將資料從外部系統帶入工作流程。REST 端點可以是客戶管理系統、Adobe I/O Runtime 或 Adobe Experience Cloud REST 端點 (如 Data Platform、Target、Analytics、Campaign)。此功能目前仍在公開測試中。如需詳細資訊，請參閱[詳細文件](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html)和[說明影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html)。 |
| 工作流程區段的報告 | 此功能可讓行銷人員依區段代碼來劃分其傳遞效能。在建立工作流程，並使用分段活動將區段指派給傳遞人口時，這些區段現在可以進入同一傳遞。這可讓您根據單一傳遞內的多個區段，顯示開啟數/點按數統計資料。如需詳細資訊，請參閱[詳細文件](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html)和[說明影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html)。 |

### Adobe Campaign Classic

[Campaign Classic 19.1.3 更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – 版本編號 9031

### Adobe Campaign 控制面板

[新「控制面板」功能](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html)包含新增 Campaign Classic 所連線之 URL 的功能，以傳輸資料/檔案。

請注意，[!UICONTROL 「控制面板」]可供託管於 AWS 的 Adobe Campaign Classic 和 Adobe Campaign Standard 客戶使用。不須升級即可存取「控制面板」。

### 其他資源

* Adobe Campaign Standard: [文件](https://helpx.adobe.com/support/campaign/standard.html) - [發行說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [說明影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [文件](https://helpx.adobe.com/support/campaign/classic.html) - [發行說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [說明影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)