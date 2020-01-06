---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: ht
source-git-commit: 8a895d104abd20910aa37ec2ec3b6eeaccd8c461

---


# 內部審閱 - Adobe Experience Cloud 發行說明 - 2020 年 1 月

Adobe Experience Cloud 中的新功能及修正項目。

> [!NOTE]訂閱 [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期：2020 年 1 月**

* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud) (11 月 8 日更新)

在找說明首頁嗎？請參閱 [Adobe Experience Cloud 檔案](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)。

## Status.adobe.com

您可以使用您的 Adobe ID，根據產品、地區和事件偏好設定，訂閱狀態事件通知。

| 功能 | 說明 |
| -----------| ---------- |
| 訂閱即時電子郵件通知 | <ul><li>支援 Experience Cloud、Creative Cloud、Document Cloud、AEP 和 Adobe 服務</li><li>支援地區和事件類型偏好設定</li><li>網頁、行動裝置和平板電腦介面 UX 支援</li></ul> |
| 通知偏好設定管理 | <ul><li>隨時編輯和儲存通知偏好設定</li><li>隨時取消訂閱通知</li><li>項目</li></ul> |
| 個人化且更快速傳送電子郵件 | <ul><li>開啟、更新或關閉 CSO 和 CMR 時，立即傳送事件通知</li><li>僅接收與您設定的偏好設定相符的相關事件通知</li><li>根據您帳戶偏好設定中設定的語言接收本地化通知</li></ul> |
| 個人化產品內通知 | 符合通知偏好設定和產品權益的事件會顯示在「公告」面板中。 |

## Experience Cloud 介面 {#ecloud}

Experience Cloud 介面與產品管理的發行說明。

* 項目
* 項目

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform 發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [安全性佈告和諮詢](https://helpx.adobe.com/tw/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正：

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices) (**2019 年 12 月 18 日更新**)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)。

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- | 
|  |  |

#### 修正

* 修正
* 修正

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 新的 Adobe Analytics 網域 | 2019 年 12 月 18 日 | 2020 年 1 月 16 日，Adobe Analytics 將移至新的網域：https://experience.adobe.com/analytics 。這項變動可能會在 Safari 中載入 Analytics 時造成 Cookie 問題。在 Safari「隱私權偏好設定」中取消勾選「防止跨網站追蹤」，會在各網域 (以及所有跨網站體驗) 啟用 Cookie，並允許 Analytics 在這個新的 Adobe Experience Cloud 網域中運作。使用者可以順利使用其他瀏覽器，因為這只會影響 Safari 使用者。 |
| **[!UICONTROL 檢視封存]**選項的 EOL | 2019 年 10 月 30 日 | 宣佈儀表板管理員 (**[!UICONTROL 元件 > 儀表板]**) 中的**[!UICONTROL &#x200B;檢視封存]**選項將於 2020 年 1 月終止服務。 |
| **[!UICONTROL 強制 IP 登入限制]**選項的 EOL | 2019 年 10 月 30 日 | 宣佈&#x200B;**[!UICONTROL 管理 > 公司設定 > 安全性]**選單中的 IP 登入白名單 (**[!UICONTROL &#x200B;強制 IP 登入限制]**) 功能將於 2020 年 1 月終止服務。 |
| 已更新 SameSite 屬性對 Cookie 的處理方式 | 2019 年 10 月 15 日 | Adobe 於 2019 年 8 月宣佈，已將 SameSite Cookie 設定新增至由 Analytics 設定的所有 Cookie。在下列情況中套用邏輯更新：<ul><li>所有非採用 Webkit 的第三方 Cookie，其 SameSite 屬性均設為 `none`。</li><li>其他所有 Cookie 皆不設定 SameSite 屬性。</li></ul> |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 對於倫敦和新加坡的客戶，我們不再支援於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間的代理資料。<br/><ul><li>如果在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新為 Analysis Workspace 自由表格總計 | 2019 年 9 月 12 日 | 從 2019 年 10 月 開始，自由表格總計列會開始計入套用的[報表篩選器](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)。就目前而言，總計僅計入分段。經過此變更後，將會更新依據的視覺效果 (例如連結的[!UICONTROL 摘要數字]視覺效果)，以及 CSV 和 PDF 資料。 |
| 關於 Analytics 使用者 `createDate` 欄位的近期變更 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月期間，系統會使用時區資訊，將 Analytics 使用者的 `createDate` 欄位從美國太平洋時間更新為格式正確的日期/時間值。(AN-183468) |
| 支援歷史時區位移 | 2019 年 8 月 8 日 | 現在起，Analytics 會自動處理時間戳記點擊的時區位移。8 月 8 日完成此變更後，系統載入歷史資料加以處理時，便不需要在傳送資料前調整時區位移。 |
| 分類規則產生器限制 | 新增日期：2019 年 6 月 5 日 | 這些限制不是新的，而是已新增至[這裡](https://docs.adobe.com/content/help/zh-Hant/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)的文件。 |
| 新區段運算子限制 | 新增日期：2019 年 5 月 31 日 | 自 2019 年 7 月 18 日起，區段運算子&#x200B;_「包含任何」_、_「不包含任何」_、_「包含所有」_&#x200B;以及&#x200B;_「不包含所有」_，每個輸入欄位僅限 100 個字詞。此限制將套用至在此日期之後的所有新區段和修改區段。超出限制的現有區段仍會繼續獲得支援，但無法修改或儲存，直到輸入欄位的字詞減少為止。現正套用這些限制，同時藉此努力改善查詢效能。 |
| **[!UICONTROL 日期啟用]**和**[!UICONTROL &#x200B;數值 2 分類]**的支援變更 | 2019 年 5 月 28 日更新 | 匯入數值 2 與日期啟用分類的功能已自基底程式碼移除。此變更於 2019 年 7 月維護版本中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| _報表總數_&#x200B;計算方式變更 | 更新日期：2019 年 7 月 9 日 | Adobe Analytics 於 **2019 年 6 月 18 日**&#x200B;統一所有維度和量度的&#x200B;_報表總數_&#x200B;計算方式。部分報表的總數因此有所變動，通常會是「Prop」或「客戶屬性」報表。在此變更前，無論報表中是否出現 _未指定_ 一項，部分「報表總數」納入或排除 _未指定_ 項目的情況不一。<br/>自 2019 年 6 月 18 日起，即使「未指定」並未出現在報表項目中，報表總數都會一律顯示 _未指定_ 。此外，在這項變更後，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;邏輯的區段可能會看到某些維度的不同結果，具體而言就是&#x200B;_未指定_&#x200B;維度針對反向連結類型維度具有「已輸入/已加上書籤」條列項目特殊名稱，或針對裝置類型維度具有「其他」條列項目特殊名稱等。到時，此變更將會影響 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和報表 API。<br>**注意&#x200B;**：此&#x200B;_報表總計_計算方式現在稱為&#x200B;_總量_。請參閱上方的「Analysis Workspace：更新為自由表格總計」。 |
| 更新 Analysis Workspace 的 CSV 下載 | 2019 年 4 月 10 日 | 自 2019 年 4 月 11 日起，Analysis Workspace 中的&#x200B;**[!UICONTROL 「CSV 下載」]**(和**[!UICONTORL 「複製到剪貼簿」]**) 功能已有諸多變動，移除了匯出資料中的格式設定。  <ul><li>不再使用千分位分隔符號。將繼續使用小數分隔符號，其將遵循&#x200B;**[!UICONTROL 「元件 > 報表設定 > 千分位分隔符號」]**中定義的格式。注意：匯出的 CSV 會繼續引用使用逗號作為小數分隔符號的數值。</li><li>不再顯示貨幣符號。</li><li>不再顯示百分比符號。百分比將以小數形式表示，例如：75% 會表示成 0.75。</li><li>時間會以秒數表示。</li><li>同類群組表格僅會顯示原始值; 百分比符號將會移除。</li><li>如果數字無效，則顯示空白儲存格。</li></ul> |
| 即將變更 Analysis Workspace 偵錯工具命令 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日**，開啟 Analysis Workspace 偵錯工具的控制台命令將變更為 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 自當天起將無法使用。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 終止 [!DNL Ad Hoc Analysis] 服務 | 2019 年 1 月 29 日 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 [!DNL Ad Hoc Analysis] 服務。我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，包括在此期間相容的 Java 版本，請造訪 [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace)。 |
| [!DNL Analytics] 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 [!DNL Analytics] 報表短連結。 |
| 資料摘要：post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動中 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的 [!DNL Live Stream] 端點可能會遭到停用。您可以聯絡客戶服務以查詢您的 [!DNL Live Stream] 端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 因為已不再支援 TLS 1.0，我們建議 [!DNL Report Builder] 使用者在 2019 年 2 月之前下載 5.6.21 版。在當天以後，舊版的 [!DNL Report Builder] 將無法繼續運作。 |

### [!DNL AppMeasurement] {#appm}

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

### Audience Manager 中的新功能、增強功能和修正 {#aam-new-features}

| 功能 | 說明 |
|--- |----|
|  |  |

### 增強功能 {#aam-enhancements}

如需詳細資訊，請聯絡您的 Audience Manager 顧問或客戶服務。

### 修正和改良 {#aam-fixes-and-improvements}

* 修正
* 修正

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

### 自助式

* **AEM 文件更新**

   請參閱 Adobe Experience Manager 過去三個月的重要文件變更和內容更新。

   請參閱 [AEM 說明文件：近期文件更新](https://helpx.adobe.com/tw/experience-manager/documentation-updates.html)。

### 其他資源

* [AEM 6.5 學習和支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-5.html)
* [AEM 6.4 學習和支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-4.html)
* [AEM 6.3 學習和支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-3.html)
* [AEM 6.2 學習和支援首頁](https://helpx.adobe.com/tw/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/tw/experience-manager/cloud-manager/user-guide.html)
* [舊版的 AEM 文件](https://helpx.adobe.com/tw/experience-manager/aem-previous-versions.html)
* [動態媒體傳統說明首頁](https://docs.adobe.com/content/help/zh-Hant/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/zh_TW/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 說明文件資源

* Adobe Campaign Standard：[文件](https://helpx.adobe.com/tw/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/tw/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic：[文件](https://helpx.adobe.com/tw/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/zh-Hant/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

| 檢視 | 功能 |
|------|---------|
|  |  |
