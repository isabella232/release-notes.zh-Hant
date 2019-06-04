---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: 版本說明
last-update: 2019 年 5 月
author: mfrei
translation-type: tm+mt
source-git-commit: 8517ef177c10b4a0e5228ccbcb9168d0e35577e0

---


# Adobe Experience Cloud 發行說明

Adobe Experience Cloud 中的新功能及修正。

>[!NOTE]
>>訂閱 [Adobe 優先產品更新](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。您會在發行前三至五個工作日收到通知。產品發行後才會發佈的新資訊皆會標示發佈日期。


**發行日期：2019年月**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [促銷活動](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform發行說明

2019年月15日版

* 如需Experience Platform的最新更新，請參閱 [Adobe. io](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) 上的Experience Platform發行說明。

### Experience Platform Launch

* 如需最新資訊，請參閱 [Experience Platform Launch](https://docs.adobelaunch.com/) 。

### Experience Cloud ID 服務

發行日期: **2019 年 5 月 13 日**

* 訪客 API 4.3.0 支援
* ITP 2.1 支援。
* 修正 secureCookie 設定問題。

## Analytics {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)

如需產品文件，請參閱 [Analytics 說明首頁](https://marketing.adobe.com/resources/help/en_US/reference/)。

### Adobe Analytics 中的新功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |  
| [!DNL AppMeasurement Version 2.14.0] <ul><li>已修正當有多個點擊擱置時，追蹤參數狀態的問題。(AN-176931、AN-176629、DTM-12758)</li><li>已更新AppMeasurement以納入Visitor. js4.3.0(AN-180049)</li></ul> |
| [!DNL Analysis Workspace]: 全新_「包含重複例項」_的「流量」視覺效果設定 | _「包含重複例項」_流量設定可讓您選擇納入或排除重複例項，例如「頁面重新載入」。此外，現在所有「流量」視覺效果皆僅根據例項。 |
| [!DNL Ad Hoc Analysis]: 與 Java 11 的相容性 | Ad Hoc Analysis 現在與 Java 11 相容。瞭解如何在Java11上執行 [臨機分析](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html)。 |
| **資料收集：** 新s_ ecid Cookie | 新增全新第一方伺服器 Cookie s_ecid，資料彙集會將訪客的 ECID 儲存在此處。 |

**Analysis Workspace 修正**

* 修正影響頁面逗留 **[!UICONTROL 時間的問題]**。[!DNL Analysis Workspace]計算「逗留時間」貯體時， 報告不再使用「頁面名稱」，以計算精細且貯體的點擊。**[!UICONTROL ]****[!UICONTROL ]**(AN-140479)
* 修正線上視覺化效能問題，做為改善 [!DNL Analysis Workspace] 效能的一部分。(AN-174878)
* 修正下載的 .csv 檔案缺少 UTF-8 編碼的問題。(AN-178393)
* 已修正專案效能緩慢 [!DNL Analysis Workspace] 的問題。(AN-177710)
* 修正 y 軸粒度方面小範圍的折線圖視覺效果顯示問題。(AN-176467)

**其他 Analytics 修正**

* [!DNL Audience Analytics]：修正對象名稱變更後發生的問題 [!DNL Audience Manager (AAM)] -更新的名稱未反映在對象分析中。(AN-176237)
* 修正使用者無法儲存[！DNL Analytics區段 [!DNL Audience Manager]中的區段。此問題是因為現有 AAM 檔案夾混合使用大寫和小寫名稱所導致。我們現在將所有檔案夾視為不區分大小寫，以便順利進行同步。(AN-177934)
* 已修正使用者登入到 [!DNL Analytics] ，然後工作階段 [!DNL Experience Cloud] 逾時的問題。繼續工作階段時，系統將使用者重新導向至錯誤的 URL。(AN-176812)
* 修正 [!DNL Data Warehouse] 請求中時區偏移的問題。(AN-177585)

### 給 Analytics 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 針對 **[!UICONTROL 啓用日期]** 和 **[!UICONTROL 數值分類的近期支援變更]** | 2019 年 5 月 28 日更新 | 匯入數值和啓用日期分類的能力將從程式碼基底中移除。此項變更將於2018年月維護發行中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| _報表總數_計算方式近期變更 | 2019 年 5 月 2 日更新 | Adobe Analytics 預計於 **2019 年 6 月 13 日** 統一所有維度和量度的_報表總數_計算方式。部分報表的總數會因此有所變動，通常會是「Prop」或「客戶屬性」報表。在此變更前，無論報表中是否出現_「未指定」_一項，部分「報表總數」納入或排除_「未指定」_項目的情況不一。<br/>自 2019 年 6 月 13 日起，即使「未指定」並未出現在報表項目中，報表總數都會一律顯示_「未指定」_。此外，在此變更後，使用_「存在」_或_「不存在」_邏輯的區段可能會看到部分維度的不同結果。到時，此變更將會影響 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和報表 API。 |
| 從CSV下載更新至 [!DNL Analysis Workspace] | 2019 年 4 月 10 日 | 從2019年月11日開始，對 **[!UICONTROL CSV下載]** (和「複製至剪貼簿 **[!UICONTORL ]**」)進行了幾項變更， [!DNL Analysis Workspace] 從匯出的資料中移除格式。  <ul><li>不再包含千個分隔符號。將繼續使用小數分隔符號，其將遵循 **[!UICONTROL 「元件 &gt; 報表設定 &gt; 千分位分隔符號」]** 中定義的格式。注意: 匯出的 CSV 會繼續引用使用逗號作為小數分隔符號的數值。</li><li>不再顯示貨幣符號。</li><li>不再顯示百分比符號。百分比將以小數形式表示，例如: 75% 會表示成 0.75。</li><li>時間會以秒數表示。</li><li>同類群組表格僅會顯示原始值; 百分比符號將會移除。</li><li>如果數字無效，則顯示空白儲存格。</li></ul> |
| 除錯程式命令 [!DNL Analysis Workspace] 即將變更 | 2019 年 4 月 4 日 | 開啓 [!DNL Analysis Workspace] 除錯程式的控制台命令會在2019年 **月13日變更為AdobeTools. debug. includeoberXML**。adobe.tools.debug.includeOberonXml 自當天起將無法使用。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 生命週期結束 [!DNL Ad Hoc Analysis] | 2019 年 1 月 29 日 | Adobe於2018年月日宣佈即將終止 [!DNL Ad Hoc Analysis]生命週期。我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，包括在此期間相容的 Java 版本，請造訪 [Discover Workspace](https://adobe.ly/discoverworkspace)。 |
| Analytics 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 Analytics 報表短連結。 |
| 終止支援 TLS 1.0 | 2019 年 1 月 10 日更新 | 自 2019 年 2 月 11 日起，Adobe Analytics 報表不再支援 TLS (傳輸層安全性) 1.0 加密技術。我們做出此次變更，持續努力維持安全性的最高標準，並確保客戶資料安全無虞。如果您在2019年月11日後無法連線至Adobe Analytics報告，請將瀏覽器升級至 [最新版本](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)。<br/>自 2019 年 2 月 20 日起，Adobe Analytics 資料彙集機制不再支援 TLS 1.0。隨著此變更正式發佈，若終端使用者使用不支援 TLS 1.1 (含) 以上版本的舊款裝置或網頁瀏覽器，Adobe 將不再彙集其 Analytics 資料。我們預計這不會對客戶資料或報告造成重大影響。(若您的網站已不支援 TLS 1.0，則不受影響。)<br/>自 2019 年 4 月 11 日起，Adobe Analytics 報告 API 不再支援 TLS 1.0 加密技術。存取該 API 的客戶應確認他們不會受到影響。 <ul><li>使用 Java 7 搭配預設設定的 API 用戶端將需要[進行修改以支援 TLS 1.2](https://www.java.com/en/configure_crypto.html)。(請參閱_變更用戶端端點預設 TLS 通訊協定版本: 從 TLS 1.0 到 TLS 1.2_。) </li><li>使用Java的API用戶端不應受到影響，因為預設設定為TLS1.2。</li><li> 使用其他架構的 API 用戶端需聯絡其供應商，以瞭解 TLS 1.2 支援的詳細資訊。</li></ul> |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更可確保在處理期間新增至post_ product_ list的銷售eVar值不會截斷產品和收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 從2019年月日起，90天無作用中消費者連線 [!DNL Live Stream] 的端點可能會停用。您可以聯絡客戶服務查詢您 [!DNL Live Stream] 的端點，並視需要重新啓用這些端點。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 由於TLS1.0支援終止，我們建議 [!DNL Report Builder] 使用者在2019年月之前下載版本v5.6.21。在該日期之後，舊版 [!DNL Report Builder] 將不再運作。 |

## Audience Manager {#aam}

| 功能 | 說明 |
| -----------| ---------- |  
| [IP 位址模糊化](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | 由於全球隱私權規範，貴公司可能會想要模糊化許多國家/地區中的 IP 位址。Audience Manager 可讓您根據全球或個別國家/地區模糊化訪客 IP 位址。 |
| [自訂合作夥伴整合 - Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | 此頁面列出 Audience Manager 與資料合作夥伴之間的自訂整合。Audience Manager 會透過傳入資料檔案，從適用於 Audience Marketplace 的 Oracle Data Cloud 擷取 Cookie 和行動 ID 資料。本頁面所述的自訂整合規格僅指包含行動 ID (IDFA 和 Android 裝置 ID) 的傳入資料檔案。 |

**修正、改良及淘汰內容**

* 我們在「目的地」的「一般報表」中新增了兩個新的欄。您現在會看到對應至目的地之區段的「開始日期」和「結束日期」。(AAM-44781)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

**AEM 6.5**

AEM 6.5 於 2019 年 4 月 8 日起推出，此為 AEM 6.4 程式碼庫的升級版。AEM 6.5 的最新更新可讓您立即存取絕佳的改善項目，更迅速地推動業務成長。

* [Adobe Experience Manager 6.5 新增功能](https://www.adobe.com/marketing/experience-manager/new.html)
* [Adobe Experience Manager 6.5 發行說明](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

最新 Cloud Manager 版本 (已於 2019 年 4 月 18 日發行 2019.4.0) 新增了當地語系化 (包括法文、德文和日文) 的使用者介面。此外，也已改善部署步驟。

* [Cloud Manager 2019.4.0 發行說明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 產品維護

**AEM 6.4.4.0**

AEM 6.4 Service Pack 4 (已於 2019 年 4 月 4 日發行 6.4.4.0) 是很重要的更新，其中包括自 2018 年 4 月 AEM 6.4 全面推出以來的重要客戶修正。

[AEM 6.4 Service Pack 發行說明](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[AEM Forms 發行版本](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM S3 Connector**

由於在 2019 年 6 月 24 日終止支援 Signature 版本 2 後 S3 存取失敗，您可能無法使用具有舊版 S3 Datastore 連接器的 AEM 例項。身為 AEM 客戶，Adobe 建議您確認正在使用的 S3 Datastore 連接器版本。視需要更新至最新版本。

請參閱[停止支援 Amazon S3 的 AWS Signature 版本 2 的影響](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)

### 自助式

**更新 AEM Sites 程式碼基底**

瞭解如何運用最新的AEM技術，現代化您的AEM Sites程式碼基底。 [現代化現有Adobe Experience Manager Sites程式碼基底](https://expleague.azureedge.net/labs/L761/index.html)

**AEM RTF 編輯器 – 深入探索**

瞭解有關豐富設定的最佳作法，以及如何在 AEM 中使用 RTF 編輯器。

請參閱[AEM RTF 編輯器 (RTE) 深入探索](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)

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

* Campaign Classic18.10.4-組建8983
* Campaign Classic18.10.5-組建8984

有關修正和改善項目，請參閱 [Adobe Campaign Classic 發行說明](http://docs.campaign.adobe.com/doc/AC/en/RN.html)。

如需產品文件，請參閱:

* Adobe Campaign Standard: [文件](https://helpx.adobe.com/support/campaign/standard.html) - [ 發行說明](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 功能影片](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [文件](https://helpx.adobe.com/support/campaign/classic.html) - [發行說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 功能影片](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| 功能 | 說明 |
| -----------| ---------- |  
| 搜尋工具 | (具有 Google Ads 帳戶的廣告商) Advertising Cloud 可選擇是否要針對所有使用 Advertising Cloud 轉換追蹤服務的 Google Ads 促銷活動，將其追蹤的轉換資料上傳至 Google Ads。每日上傳包含使用廣告商層級屬性模型所定義的轉換值。所有上傳的轉換都會加上「Adobe_ACS_」前置詞 (例如「訂閱」轉換會顯示為「Adobe_ACS_Subscriptions」)。 <br/> **注意:** 上傳內容不包含從摘要檔案上傳至 Advertising Cloud 的轉換資料。 |
| 搜尋促銷活動 | **「搜尋** &gt; **促銷活動** &gt; **促銷活動」** 中的功能表現為階層式，並具有「帳戶」下方的「促銷活動」；促銷活動下的廣告群組；和關鍵字(只有子功能表)、廣告、產品群組(僅限即時檢視)、位置(含子功能表)以及「廣告群組」下方的「自動目標」。<br/>在即時檢視中，觀眾和擴充功能與帳戶位於相同層級，並具有自己的子功能表。 |

## Target Standard/Premium 19.5.1 {#target}

此版本包含下列功能、變更和增強功能:

(括號內的問題編號供 Adobe 內部使用。)

### 功能更新

| 功能/增強功能 | 說明 |
| --- | --- |
| 單頁應用程式視覺化體驗撰寫器 (SPA VEC) | SPA VEC 已改良下列項目，讓您的工作更快更有效率: <ul><li>現在可於 VEC 取消載入網站，封鎖編輯活動。這項增強功能相當實用，舉例來說，如果您想稍微編輯活動、檢視活動設定或新增自訂程式碼，通常不會想等網站完全載入。(TGT-33872)</li><li>您可以在 VEC 中的頁面載入前，或甚至頁面完全無法載入時 (例如自訂程式碼無法繼續正常運作) 執行許多動作。無法在網站載入前編輯的動作，都會在 Target UI 中停用。(TGT-33851 和 TGT-34149)</li></ul> |
| 自動個人化 (AP) 和自動鎖定目標活動 | 建立 AP 或自動鎖定目標活動時，您可以選取要用來作為控制的體驗。此功能可讓您根據活動中設定的流量配置百分比，將整個控制流量傳送至特定體驗。接著，您可以根據控制體驗評估個人化傳送的效能。(TGT-26572) |
| 建議 | 建立「最近查看的項目」邏輯時，您可以使用「先前建議購買的項目」切換按鈕。(TGT-34030) |

### 增強功能、修正和變更

* 在 VEC 中取消載入頁面後，工具列圖示會正常顯示。如果在完全載入頁面前無法執行特定動作，系統會停用相關工具列圖示。(TGT-33811)
* 您現在可以更輕鬆地列出及瀏覽「資產」選擇器中的活動內容檔案夾，而不需要瀏覽平面化的檔案夾階層。(TGT-33725)

如需下列產品的最新發行資訊，請參閱 [Adobe Target 發行說明](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)。

* Target Standard和Target Premium
* Recommendations Classic


## Magento {#magento}

電子商務平台 Magento 提供線上商家彈性的購物車系統，且可控制線上商店的外觀、內容與功能。Magento 提供開放原始碼版本與功能更完整的商務版。

Magento Commerce 屬於 Adobe Commerce Cloud 的一部分，提供具備企業級效能、無限制擴充能力及開放原始碼彈性的電子商務解決方案，適用於 B2C 與 B2B 體驗。。

您可以在 [「發行資訊](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) 」頁面上找到我們Open Source和Commerce版本的發行說明。

## Primetime {#primetime}

Adobe Primetime 是一種多螢幕電視平台，可協助媒體公司建立吸引人且個人化的觀看體驗，並從中獲利。

[Primetime 發行說明](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime 說明首頁](http://help.adobe.com/en_US/primetime/)