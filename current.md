---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: 發行說明
last-update: 2019 年 9 月
author: mfrei
translation-type: tm+mt
source-git-commit: 8e959510cb32eef2e619f562cd998b4e75c2c8d3

---


# Experience Cloud 發行說明 - 2019 年 9 月

Adobe Experience Cloud 中的新功能及修正。

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. 您會在發行前三至五個工作日收到通知。產品發行後才會發佈的新資訊皆會標示發佈日期。

## 發行日期: 2019 年 9 月 12 日

* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) （解決方案說明的連結）
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) （解決方案說明的連結）

## Experience Cloud 介面 {#ecloud}

Experience Cloud 介面與產品管理的發行說明。

* 已修正安全性弱點，並包含建議採用的 HTTP 標題。(MCUI-9942)
* 已修正在 Analytics 登入公司之間進行切換的問題。(MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform Launch](#launch)
* [Mobile Services 與 Mobile SDK](#mobile)
* [安全性公告和建議](https://helpx.adobe.com/security.html) （所有Adobe產品）

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services 與 Mobile SDK {#mobile}

發行日期: **9 月 26 日**

**iOS (4.18.8)**

* 已修正在每個 Analytics 呼叫上 SDK 資料已同步處理到配對的 WatchOS app 的錯誤。
* 已修正無法使用推送點進裝載作為應用程式內傳訊特徵的錯誤。
* 已更新為使用者通知架構 API，而非 UILoalNotification API (已經從 iOS10 起淘汰)。
* 已更新為 WKWebView，而非 UIWebView (已經從 iOS12 起淘汰)。

**Android 4.17.10**

* 新增對 BCP47 語言標籤的支援。

**Unity**

* 外掛程式己更新為 4.18.7 (適用於 iOS) 和 4.17.9 (適用於 Android)

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |  
| **Journey IQ: 跨裝置分析** | Adobe Analytics 於 2019 年 9 月推出了一項強大的新功能，稱為 Journey IQ: Cross-Device Analytics。(請注意，此功能僅供 Analytics Ultimate 客戶使用)。跨裝置分析 (CDA) 將 Adobe Analytics 從裝置導向轉換為人物導向的分析工具。使用 CDA，您可以回答下列問題: <ul><li>有多少人正在與我的品牌互動? 他們使用的裝置數量與類型為何? 他們互相重疊的程度?</li><li>人們會在行動裝置上開始工作，稍後再移至桌上型電腦完成工作的頻率為何? 登陸在一部裝置上的行銷活動點進次數，是否會導致在其他位置上的轉換?</li><li>如果將跨裝置歷程列入考量，我對行銷活動成效的理解會有何改變? 我的漏斗分析會有何改變?</li><li>使用者在裝置間移動最常採取的路徑為何? 他們在哪裡退出? 他們在哪裡獲得成功?</li><li>多部裝置使用者的行為與單一裝置使用者的行為有何不同?</li></ul><br/>若需詳細資訊，請造 [訪adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/)。 |
| **已更新的分類架構** | 自 9 月起，分類架構更新將會在數個月的期間內移轉給客戶。9 月發行版本包含少數早期採用者的移轉。<br/>此更新可大幅減少匯入/讀取上傳 (包括規則邏輯) 並可供報告的所需時間。 |

#### 修正

* 已修正無法從 Experience Cloud 主功能表存取 [!UICONTROL 「人員」]和[!UICONTROL 「優惠」]核心服務的問題。(AN-184294)
* 已修正 [!UICONTROL Analysis Workspace] 中的左側邊欄在有捲軸和無捲軸之間振盪，而導致飄動效果的問題。(AN-183904)
* 已修正錯誤報告的問題。您會開始看到更具體的錯誤訊息，而不只是紅色的錯誤指示器。更具體的說，應該有助您瞭解問題是因為負載嚴重、錯誤或建立過於複雜的報表要求所致。(AN-184135)更 [多……](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* 已修正無法成功下載 `.pdf/.xls/.rtf` 格式的流失報表問題。(AN-183165)
* 已修正透過 Experience Cloud 登入並切換至不同 Experience Cloud 解決方案或切換至另一個登入公司的問題。(AN-183376)
* 已修正排程專案的資產傳輸無法正常運作的問題。現在，群組是在 [!UICONTROL Admin Console] 中進行管理，因此在傳輸資產時，我們不會在使用者之間複製群組。(AN-183751)
* 已修正刪除其擁有者已刪除之排程報表的問題。從現在開始，當排程擁有者不再存在時，通知會傳送給 (執行刪除作業的) 管理員。(AN-181000)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
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
| 終止支援 TLS 1.0 | 2019 年 1 月 10 日更新 | 自 2019 年 2 月 11 日起，Adobe Analytics 報表不再支援 TLS (傳輸層安全性) 1.0 加密技術。我們做出此次變更，持續努力維持安全性的最高標準，並確保客戶資料安全無虞。If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/>[!DNL Analytics]自 2019 年 2 月 20 日起，Adobe 資料彙集機制不再支援 TLS 1.0。隨著此變更正式發佈，若終端使用者使用不支援 TLS 1.1 (含) 以上版本的舊款裝置或網頁瀏覽器，Adobe 將不再彙集其 Analytics 資料。我們預計這不會對客戶資料或報告造成重大影響。(若您的網站已不支援 TLS 1.0，則不受影響。)<br/>自 2019 年 4 月 11 日起，Adobe Analytics 報告 API 不再支援 TLS 1.0 加密技術。存取該 API 的客戶應確認他們不會受到影響。 <ul><li>使用 Java 7 搭配預設設定的 API 用戶端將需要[進行修改以支援 TLS 1.2](https://www.java.com/en/configure_crypto.html)。(請參閱&#x200B;_變更用戶端端點預設 TLS 通訊協定版本: 從 TLS 1.0 到 TLS 1.2_。) </li><li>使用 Java 8 的 API 用戶端已預設為 TLS 1.2，應該不會受到影響。</li><li> 使用其他架構的 API 用戶端需聯絡其供應商，以瞭解 TLS 1.2 支援的詳細資訊。</li></ul> |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動中 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的 [!DNL Live Stream] 端點可能會遭到停用。您可以聯絡客戶服務以查詢您的 [!DNL Live Stream] 端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 因為已不再支援 TLS 1.0，我們建議 [!DNL Report Builder] 使用者在 2019 年 2 月之前下載 5.6.21 版。在當天以後，舊版的 [!DNL Report Builder] 將無法繼續運作。 |

### [!DNL AppMeasurement] {#appm}

請參 [閱「Javascript適用的AppMeasurement」發行說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager 中的新功能、增強功能和修正

### 新功能和增強功能 {#aam-features}

| 功能 | 說明 |
| -----------| ---------- |  
| **[[!DNL基於人的目標]](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNL People-Based Destinations] 是一種付費的 Audience Manager 附加元件，可協助您使用雜湊識別碼 (例如電子郵件地址)，在各種以人員為基礎的環境 (例如 Facebook) 中啟用第一方對象區段。 |
| **[將Twitter量身訂做的觀眾設定為自助裝置型目標](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | 我們正在將 Twitter 目的地移轉至自助服務設定模型。本文說明為了在移轉後繼續使用現有 Twitter 整合所需採取的動作。 |
| **[Audience Marketplace帳單範例](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | 我們新增了一個案例 3 的範例，說明帳單如何適用於具有啟用和模型使用案例的區段。 |

**修正和改良**

* 我們已修正使用者無法編輯 Adobe Analytics 目的地以手動對應區段的錯誤。(AAM-49323)

* 我們已修正重複的 Audience Marketplace 摘要為源自單一資料來源 ID 的錯誤。資料來源和 [!DNL Marketplace] 摘要之間必須為 1:1 對應。(AAM-48504)
* 我們改良了特徵和區段建立工作流程。現在，您可以篩選資料來源來儲存特徵或區段，以排除任何非 Audience Manager 資料來源 (例如來自 Adobe Analytics 的報表套裝資料來源)。(AAM-35899)
* 我們修正了資料來源 API 中設定查詢參數 `ExcludeReportSuites=true` 並未從 Adobe Analytics 排除報表套裝資料來源的問題。(AAM-48545)
* 我們對 Audience Manager 使用者介面的協助工具進行了幾項相關的改良。(AAM-49024) 及 (AAM-49031)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

**Cloud Manager 2019.8.0**

Cloud Manager 版本 2019.8.0 修正了各種小錯誤、改善建置效能，並新增了對選擇性建立的內容套件的支援。

* [Cloud Manager 2019.8.0 發行說明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**Software Distribution**

[Software Distribution](https://downloads.experiencecloud.adobe.com/) 是專為簡化AEM套件的搜尋和下載而設計的全新使用者介面。 它目前處於測試狀態，僅供 Adobe Managed Services 客戶存取。

* [在所有客戶都能存取「軟體散發](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/package-manager.html#PackageShare) 」之前，「套件共用」仍可供存取。
* Package Share 和 Software Distribution 皆提供所有套件。

### 產品維護

**AEM 維護版本藍圖**

See the AEM maintenance release roadmap as published here.[](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html)

### 自助式

**資產連結 1.1 搶鮮版**

* [About Adobe Asset Link Prerelease](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [設定AEM for Adobe Asset Link的發行前版本](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

AEM 桌面應用程式 2.0 (Mac 版) 已於 2019 年 8 月 30 日發行。AEM 桌面應用程式 2.0 (Windows 版) 將於 9 月初推出。

Access documentation and downloads [here](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html).

**資產智慧標記**

Learn how to update a certificate after it has expired here.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate)

**AEM 6.5 Screens 使用手冊**

現已推出有關&#x200B;_網路部署指引_&#x200B;的新文件。請參閱 [ 使用者指南](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html)。

**自動化表單轉換服務**

現已推出 AEM Forms 自動化表單轉換服務的說明文件。See [Introduction to Automated Forms Conversion service](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html).

### 社群

**AEM 技能建立網路研討會**

* [Adobe Experience Manager Sites](https://forums.adobe.com/thread/2647742)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | _編寫網頁體驗_ | 2019 年 8 月 27 日 |
   | _搜尋和導覽內容_ | 2019 年 9 月 3 日 |
   | _輕鬆管理每個不斷演變的內容_ | 2019 年 9 月 10 日 |
   | _流暢的使用體驗_ | 2019 年 9 月 17 日 |
   | _建立並管理多語言、多國家/地區來設計全球網站結構_ | 2019 年 9 月 24 日 |

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | _檔案夾結構與搜尋_ | 2019 年 8 月 29 日 |
   | _中繼資料_ | 2019 年 9 月 5 日 |
   | _品牌門戶_ | 2019 年 9 月 12 日 |
   | _動態媒體_ | 2019 年 9 月 19 日 |
   | _資產連結_ | 2019 年 9 月 26 日 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | 表單 101_ | 2019 年 9 月 4 日 |
   | _將表單連接至資料庫、建置工作流程，並將表單與電子簽名整合_ | 2019 年 9 月 11 日 |
   | _建立行動互動式網頁和可直接列印的互動式通訊_ | 2019 年 9 月 25 日 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | _測試最佳實務 – 透過 Cloud Manager 建立執行、監控、稽核以及深入分析_ | 2019 年 9 月 18 日 |
   | _搭配 Cloud Manager 的發送器組態_ | 2019 年 10 月 16 日 |
   | _使用 Cloud Manager 和第三方工具建立工作流程_ | 2019 年 11 月 13 日 |

### 其他資源

* [AEM 6.5 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [舊版AEM檔案](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help Home](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### 產品服務終止

[!DNL Digital Publishing Suite Classic] (DPSC) 即將於 2019 年 8 月 31 日終止服務。For more information, see the [[!DNL Digital Publishing Suite Classic] End-of-Life FAQ](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

### 其他資源

* [AEM 6.5 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 學習與支援首頁](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [舊版 AEM 文件](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System 發行說明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) – build 9032
* [Campaign Classic 19.1.5 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) – build 9033

### Adobe Campaign [!UICONTROL 控制面板]

為管理員使用者新增功能，使其可將 IP 位址加入白名單，以連線 Campaign Classic 例項。此外，管理員使用者現在也能檢視例項清單，並具備版本升級資格。 For more information, refer to the [dedicated documentation](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html).

我們已新增新功能，讓管理員使用者在其網域的 SSL 憑證過期之前接收通知。如需詳細資訊，請參閱[詳細文件](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html)。

此外，管理員使用者現在可以刪除已新增的 SSH 金鑰，以存取 SFTP 伺服器。

請注意，[!UICONTROL 「控制面板」]可供託管於 AWS 的 Adobe Campaign Classic 和 Adobe Campaign Standard 客戶使用。不須升級即可存取[!UICONTROL 「控制面板」]。

### 其他資源

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
