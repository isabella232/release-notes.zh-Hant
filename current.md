---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: 發行說明
last-update: 2019年月
author: mfrei
translation-type: tm+mt
source-git-commit: fdcc0f53ea326b9c440e511ca5968749e68861cd

---


# 提早存取-2012年月- Experience Cloud發行說明

Adobe Experience Cloud 中的新功能及修正。

>[!IMPORTANT]
>
>本頁包含發行前內容，且可能在2019年月12日發行之前變更。

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
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (解決方案說明連結)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (解決方案說明連結)

## Experience Cloud 介面 {#ecloud}

Experience Cloud介面與產品管理的發行說明。

* 已修正包含建議HTTP標題的安全性弱點。(MCUI-9942)
* 已修正Analytics登入公司之間切換的問題。(MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、Identity Service和安全性公告的發行說明。

* [Experience Platform Launch](#launch)
* [Mobile Services 與 Mobile SDK](#mobile)
* [安全性公告和建議](https://helpx.adobe.com/security.html) (所有Adobe產品)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services 與 Mobile SDK {#mobile}

Release Date: **September 26th**

**iOS(4.18.8)**

* 已修正每個Analytics呼叫上，SDK資料與成對的WatchOS應用程式同步的錯誤。
* 已修正推送點進付費載入無法作為應用程式內傳訊特性的錯誤。
* 已更新至使用者通知架構API，而非UILoalNotification API，而非從iOS10轉送。
* 已更新為WKWebView，而非UIWebView，後者已停用iOS12。

**Android4.17.10**

* 新增支援BCP47語言標籤。

**Unity**

* 適用於iOS的增效模組更新為4.187，Android則為4.17.9

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |  
| **旅程IQ：跨裝置分析** | Adobe Analytics於19月推出了一項強大的新功能，稱為歷程IQ：跨裝置分析。(請注意，此功能僅適用於Analytics Ultimate客戶)。跨裝置分析(CDA)將Adobe Analytics從裝置導向至人員導向分析工具。使用CDA，您可以回答下列問題： <ul><li>有多少人與我的品牌互動？他們使用的裝置類型為何？如何重疊？</li><li>人們通常會在行動裝置上開始工作，然後稍後移至桌上型PC完成工作？在一台裝置上著陸的促銷活動點進是否會導致其他裝置轉換？</li><li>如果我考慮到跨裝置歷程，我對促銷活動有效性的理解如何？漏斗分析如何改變？</li><li>使用者在一個裝置間採取的最常見路徑是甚麼？他們在哪裡流失？他們是否成功？</li><li>有多個裝置的使用者行為如何與使用者使用單一裝置不同？</li></ul><br/>若要進一步瞭解，請造訪 [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/)。 |
| **更新的分類架構** | 自月起，分類架構的更新將會在數個月內移轉給客戶。月發行版本包含少數早期採用者的移轉。<br/>此更新可大幅減少上傳/吸收和提供報告時所需的時間(包括規則邏輯)。 |

#### 修正

* 修正 [!UICONTROL 「人員] 」的問題， [!UICONTROL 並無法] 從主要Experience Cloud功能表存取核心服務。(AN-184294)
* 已修正 [!UICONTROL 分析工作區中的左側導軌] 在具有捲軸和無捲軸之間搖晃，造成平滑效果的問題。(AN-183904)
* 修正錯誤報告的問題。您會開始看到更具體的錯誤訊息，而不只是紅色錯誤指標。更具體的說，它應該幫助您瞭解問題是因為負載嚴重、錯誤或建立過於複雜的報表請求所致。(AN-184135) [更多資訊…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* 修正無法成功下載 `.pdf/.xls/.rtf` 格式的流失報表問題。(AN-183165)
* 修正透過Experience Cloud登入並切換至不同Experience Cloud解決方案或切換至另一個登入公司的問題。(AN-183376)
* 修正計劃專案資產傳輸無法正常運作的問題。群組現在是在 [!UICONTROL 管理控制台] 中管理，因此在使用者傳輸資產時，我們不會在使用者之間複製。(AN-183751)
* 已修正刪除其擁有者已刪除之計劃報表的問題。從現在開始，當排程擁有者不再存在時，通知會前往管理員(執行刪除作業)。(AN-181000)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 更新至分析工作區自由表格總計 | 2019年月12日 | 在2019年10月，自由表格總列數將開始會計套用 [報表篩選器](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) 。截至目前為止，總計僅計入分段。有了這項變更，相依視覺效果將會更新(例如連結 [!UICONTROL 的摘要數字] 視覺化)以及匯出的CSV和PDF資料。 |
| Analytics使用者 `createDate` 適用的即將變更欄位 | 2019 年 30 月 8 日 | 在2019年10月或11月，Analytics使用者 `createDate` 的欄位將會從US太平洋時間更新為正確格式化的日期/時間值以及時區資訊。(AN-183468) |
| 支援歷史時區位移 | 2019 年 8 月 8 日 | 現在起，Analytics 會自動處理時間戳記點擊的時區位移。8 月 8 日完成此變更後，系統載入歷史資料加以處理時，便不需要在傳送資料前調整時區位移。 |
| 分類規則產生器限制 | 新增日期: 2019 年 6 月 5 日 | 這些限制不是新的，但已新增至 [此處](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)的文件。 |
| 新區段運算子限制 | 新增日期: 2019 年 5 月 31 日 | 自 2019 年 7 月 18 日起，區段運算子&#x200B;_「包含任何」_、_「不包含任何」_、_「包含所有」_&#x200B;以及&#x200B;_「不包含所有」_，每個輸入欄位僅限 100 個字詞。此限制將套用至在此日期之後的所有新區段和修改區段。超出限制的現有區段仍會繼續獲得支援，但無法修改或儲存，直到輸入欄位的字詞減少為止。現正套用這些限制，同時藉此努力改善查詢效能。 |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | 2019 年 5 月 28 日更新 | 匯入數值 2 與日期啟用分類的功能已自基底程式碼移除。此項變更在2018年月維護發行中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| _報告總計_ 計算 | 更新日期: 2019 年 7 月 9 日 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. 這會導致部分報表(通常是Prop或客戶屬性報表)的總計變更。在此變更前，無論報表中是否出現 _未指定_ 一項，部分「報表總數」納入或排除 _未指定_ 項目的情況不一。<br/>自 2019 年 6 月 18 日起，即使「未指定」並未出現在報表項目中，報表總數都會一律顯示 _未指定_ 。此外，在這項變更後，使用&#x200B;_存在_&#x200B;或&#x200B;_不存在_&#x200B;邏輯的區段可能會看到某些維度的不同結果，具體而言就是&#x200B;_未指定_&#x200B;維度針對反向連結類型維度具有「已輸入/已加上書籤」條列項目特殊名稱，或針對裝置類型維度具有「其他」條列項目特殊名稱等。到時，此變更將會影響 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和報表 API。 |
| 更新 Analysis Workspace 的 CSV 下載 | 2019 年 4 月 10 日 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>不再使用千分位分隔符號。將繼續使用小數分隔符號，其將遵循&#x200B;**[!UICONTROL 「元件 &gt; 報表設定 &gt; 千分位分隔符號」]**&#x200B;中定義的格式。注意: 匯出的 CSV 會繼續引用使用逗號作為小數分隔符號的數值。</li><li>不再顯示貨幣符號。</li><li>不再顯示百分比符號。百分比將以小數形式表示，例如: 75% 會表示成 0.75。</li><li>時間會以秒數表示。</li><li>同類群組表格僅會顯示原始值; 百分比符號將會移除。</li><li>如果數字無效，則顯示空白儲存格。</li></ul> |
| 即將變更 Analysis Workspace 偵錯工具命令 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日**，開啟 Analysis Workspace 偵錯工具的控制台命令將變更為 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 自當天起將無法使用。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 終止 [!DNL Ad Hoc Analysis] 服務 | 2019 年 1 月 29 日 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 [!DNL Ad Hoc Analysis] 服務。我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，請參閱此期間的哪個Java版本相容，請造訪 [[！DNL Discover工作區]](https://adobe.ly/discoverworkspace)。 |
| [!DNL Analytics] 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 [!DNL Analytics] 報表短連結。 |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動中 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的 [!DNL Live Stream] 端點可能會遭到停用。您可以聯絡客戶服務以查詢您的 [!DNL Live Stream] 端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 |
| 終止支援 TLS 1.0 | 2019 年 1 月 10 日更新 | 不再支援TLS1.0 |

### [!DNL AppMeasurement] {#appm}

請參閱 [「Javascript適用的AppMeasurement」發行說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager中的新功能、增強功能和修正。

### 新功能和增強功能 {#aam-features}

| 功能 | 說明 |
| -----------| ---------- |  
| **[[！DNL人員目標]](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNL People-Based Destinations] 是一種付費的Audience Manager附加元件，可協助您使用雜湊識別碼(例如電子郵件地址)在以人員為基礎的環境(例如Facebook)上啓用第一方觀眾區段。 |
| **[將Twitter自訂對象設定為自助服務裝置的目的地](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | 我們正在將Twitter目的地移轉至自助服務設定模型。本文說明您需要做甚麼，才能在移轉後繼續使用現有的Twitter整合。 |
| **[Audience Marketplace帳單範例](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | 我們新增了一個範例3，說明帳單如何適用於具有啓動和模型使用案例的區段。 |

**修正和改良**

* 我們已修正使用者無法編輯Adobe Analytics目的地以手動對應區段的錯誤。(AAM-49323)

* 我們修正了重復Audience Marketplace摘要源自單一資料來源ID的錯誤。資料來源和 [!DNL Marketplace] 饋送之間必須有1：1對應。(AAM-48504)

* 我們改善了特徵和區段建立工作流程。現在，您可以篩選資料來源來儲存特徵或區段，以排除任何非Audience Manager資料來源(例如Adobe Analytics的報表套裝資料來源)。(AAM-35899)

* 我們修正Data Sources API中設定查詢參數 `ExcludeReportSuites=true` 未從Adobe Analytics排除報表套裝資料來源的問題。(AAM-48545)

* 我們對Audience Manager使用者介面的協助功能進行了幾項改良。(AAM-49024)和(AAM-49031)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

**Cloud Manager 2019.8.0**

Cloud Manager版本2019.8.0修正了各種小錯誤、改善建置效能，並新增了選擇性建立的內容封裝支援。

* [Cloud Manager 2019.8.0 發行說明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### 產品維護

**AEM維護發行藍圖**

請參閱此處發佈 [的AEM維護發行藍圖](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html)。

### 自助式

**Asset Link1.1搶鮮版**

* [關於Adobe Asset Link搶鮮版](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [為預先發佈設定AEM for Adobe Asset Link](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

AEM桌面應用程式2.0for MAC已於2019年月30日發行。AEM桌面應用程式2.0for Windows將於月初推出。

在這裡存取文件和下載 [](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html)。

**資產智慧標記**

瞭解如何在 [此更新後更新憑證](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate)。

**AEM6.5畫面使用指南**

現在提供 _有關網路部署准則_ 的新文件。請參閱 [ 使用者指南](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html)。

**自動化表單轉換服務**

AEM Forms自動化表單轉換服務的說明文件現已推出。請參閱 [自動化表單轉換服務簡介](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html)。

### 社群

**AEM技能產生器網路研討會**

* [Adobe Experience Manager Sites](https://forums.adobe.com/thread/2647742)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | _編寫網頁體驗_ | 2019年月27日 |
   | _搜尋和導覽內容_ | 2019年月日 |
   | _輕鬆管理每個新興內容_ | 1919年月 |
   | _流暢的體驗_ | 19月17日 |
   | _建立並管理多語言、多國家/地區來設計全球網站結構_ | 2019年月24日 |

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | _資料夾結構與搜尋_ | 1929年月29日 |
   | _中繼資料_ | 2019年月05日 |
   | _Brand Portal_ | 2012年月12日 |
   | _Dynamic Media_ | 19月19日 |
   | _資產連結_ | 2019年月26日 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | Forms101_ | 2019年月04日 |
   | _將表單連接至資料庫、建立工作流程，並與電子簽名整合表單_ | 2011年月11日 |
   | _建立行動回應網路和可立即列印的互動式通訊_ | 2019年月25日 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | 網路研討會 | 日期 |
   | -----------| ---------- |  
   | _測試最佳實務-透過Cloud Manager建立執行、監控、稽核和見解_ | 2019年月18日 |
   | _搭配雲端管理員的Dispatcher組態_ | 2016年10月16日 |
   | _使用雲端管理員和第三方工具建立工作流程_ | 19月13日 |

### 其他資源

* [AEM 6.5 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 學習和支援首頁](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager 使用手冊](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [舊版AEM文件](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic說明首頁](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Dynamic Media 發行說明](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre 發行說明](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### 產品服務終止

[!DNL Digital Publishing Suite Classic] (DPSC)將於2019年月31日結束。For more information, see the [[!DNL Digital Publishing Suite Classic] End-of-Life FAQ](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

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

* [Campaign Classic19.1.4更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) -組建9032
* [Campaign Classic19.1.5更新](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) -組建9033

### Adobe Campaign [!UICONTROL Control Panel]

我們已新增新功能，讓管理員使用者在其網域的SSL憑證過期之前接收通知。如需詳細資訊，請參閱[詳細文件](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html)。

此外，管理員使用者現在可以刪除已新增的SSH金鑰，以存取SFTP伺服器。

請注意，[!UICONTROL 「控制面板」]可供託管於 AWS 的 Adobe Campaign Classic 和 Adobe Campaign Standard 客戶使用。No upgrades are required to access [!UICONTROL Control Panel].

### 其他資源

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
