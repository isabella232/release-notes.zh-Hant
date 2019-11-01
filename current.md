---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: 發行說明
last-update: 2019 年 11 月
author: mfrei
translation-type: ht
source-git-commit: 32fa8a1156cafb4a54bae4d57b125efbb781e64d

---


# Adobe Experience Cloud 版本說明 - 2019 年 11 月

Adobe Experience Cloud 中的新功能及修正項目。

> [!NOTE]訂閱[[!DNL Adobe 優先產品更新]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才發佈的新資訊皆會標示發佈日期。

**發行日期: 2019 年 10 月 31 日**

* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/zh-Hant/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Primetime](https://helpx.adobe.com/tw/primetime/user-guide.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud)

在找說明首頁嗎？ 請參閱 [Experience Cloud 學習與支援](https://helpx.adobe.com/tw/support/experience-cloud.html)。

## Experience Cloud 介面 {#ecloud}

Experience Cloud 介面與產品管理的發行說明。

* 「摘要」頁面將於 2019 年 12 月淘汰。請參閱產品中的淘汰通知。(MCUI-10039)
* 已更新應用程式選取器中 Adobe Campaign 的[深入了解](https://www.adobe.com/tw/marketing/campaign.html)連結。(MCUI-10034)
* 已改善 Experience Cloud 介面核心平台的穩定度和回應效能。(MCUI-6822)
* 已修正 Experience Cloud UI 的安全漏洞。(MCUI-9942)
* 已修正「客戶屬性」中阻擋部分客戶執行結構驗證的重大問題。(MCUI-10024、MCUI-6479)
* 已改善「對象庫」，移除即時對象建立程序不支援的維度。(MCUI-10046)

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform Launch](#launch)
* [安全性佈告和諮詢](https://helpx.adobe.com/tw/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/zh-Hant/launch/using/intro/release-notes/current.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/zh-Hant/analytics/landing/home.html)。

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- | 
| 客戶歷程分析 | Adobe 將於 2019 年 11 月 21 日起，將以 Adobe Analytics 附加元件的形式提供[「客戶歷程分析」](https://www.adobe.com/analytics/customer-journey-analytics.html)。<br><br/>「客戶歷程分析」可將您從任何管道取得的所有客戶資料 (線上及離線皆可) 整合到 Adobe Experience Platform 中，接著依您目前使用 Analysis Workspace 分析現有數位資料的方式加以分析。「客戶歷程分析」可讓您控制如何在 Analysis Workspace 中連線任何常見客戶 ID 的線上和離線資料，進而允許您針對 Adobe Analytics 中的整個客戶資料集執行歸因、區段、流量、流失等分析。<br><br/>Analytics Select、Prime 和 Ultimate 客戶均符合購買此附加產品的資格。如需詳細資訊，請連絡您的 Adobe 客戶團隊。 |
| 隱私權服務 API: CCPA | 加州消費者隱私權法案 (California Consumer Privacy Act, CCPA) 強化了美國加州居民的隱私權和消費者保護力道。此法案已訂於 2020 年 1 月 1 日生效。<br><br/>CCPA 為加州居民提供了新的資料隱私權，例如有權存取和刪除其個人資料、有權得知其個人資料是否遭到販售或揭露 (以及對象是誰)，以及有權拒絕廠商販售其個人資料。<br><br/>有鑑於 CCPA 即將生效，隱私權服務將會支援請求退出個人資料販售行列的功能。<br><br/>隱私權服務先前稱為 GDPR 服務，其不僅保留了先前的一切功能，現在更擴大為支援 CCPA。<br/><br/>[Analytics 中的 CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[隱私權服務概觀](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| 隱私權報告: Analytics Admin Console | 為 Analytics 啟用隱私權報告時，報表套裝中會新增一組保留變數。這些變數的設計目的，是要協助系統在點擊層級收集消費者同意資料。<br><br/>新維度:<br/><ul><li>同意管理選擇退出</li><li>同意管理選擇加入</li><li>[同意管理變數](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| 音訊和視訊分析: 隱私權支援 | Media Collection API 已新增兩個新變數:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>這兩者皆為可選變數，可用來擷取消費者在點擊時的同意狀態。<br/><br/>[媒體收集 API 文件](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>新的 Analytics 同意管理內容資料變數已新增至 Federated Analytics 表格。這些變數現在可用於標記選擇退出同盟的分享或販售點擊。<br/><br/>[下載 Federated Form](https://docs.adobe.com/content/help/zh-Hant/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### 修正

* 已修正嘗試刪除「未知使用者」所擁有的日期範圍時發生錯誤的問題。(AN-185540)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| **[!UICONTROL 檢視封存]**&#x200B;選項的 EOL | 2019 年 10 月 30 日 | 宣佈儀表板管理員 (**[!UICONTROL 元件 &gt; 儀表板]**) 中的&#x200B;**[!UICONTROL 檢視封存]**&#x200B;選項將於 2020 年 1 月終止服務。 |
| **[!UICONTROL 強制 IP 登入限制]**&#x200B;選項的 EOL | 2019 年 10 月 30 日 | 宣佈&#x200B;**[!UICONTROL 管理 &gt; 公司設定 &gt; 安全性]**&#x200B;選單中的 IP 登入白名單 (**[!UICONTROL 強制 IP 登入限制]**) 功能將於 2020 年 1 月終止服務。 |
| 已更新 SameSite 屬性對 Cookie 的處理方式 | 2019 年 10 月 15 日 | Adobe 於 2019 年 8 月宣佈，已將 SameSite Cookie 設定新增至由 Analytics 設定的所有 Cookie。在下列情況中套用邏輯更新:<ul><li>所有非採用 Webkit 的第三方 Cookie，其 SameSite 屬性均設為 `none`。</li><li>其他所有 Cookie 皆不設定 SameSite 屬性。</li></ul> |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 對於倫敦和新加坡的客戶，我們不再支援於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間的代理資料。<br/><ul><li>如果在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新為 Analysis Workspace 自由表格總計 | 2019 年 9 月 12 日 | 從 2019 年 10 月 開始，自由表格總計列會開始計入套用的[報表篩選器](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)。就目前而言，總計僅計入分段。經過此變更後，將會更新依據的視覺效果 (例如連結的[!UICONTROL 摘要數字]視覺效果)，以及 CSV 和 PDF 資料。 |
| 關於 Analytics 使用者 `createDate` 欄位的近期變更 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月期間，系統會使用時區資訊，將 Analytics 使用者的 `createDate` 欄位從美國太平洋時間更新為格式正確的日期/時間值。(AN-183468) |
| 支援歷史時區位移 | 2019 年 8 月 8 日 | 現在起，Analytics 會自動處理時間戳記點擊的時區位移。8 月 8 日完成此變更後，系統載入歷史資料加以處理時，便不需要在傳送資料前調整時區位移。 |
| 分類規則產生器限制 | 新增日期: 2019 年 6 月 5 日 | 這些限制不是新的，而是已新增至[這裡](https://docs.adobe.com/content/help/zh-Hant/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)的文件。 |
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

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/zh-Hant/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager 中的新功能、增強功能和修正

| 功能 | 說明 |
|--- |----|
| [設定檔合併規則增強功能](https://docs.adobe.com/help/zh-Hant/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | 我們針對[!UICONTROL 設定檔合併規則]發佈了一系列增強功能: <ul><li>現起支援批次區段評估，最多可評估 100 部裝置。</li><li>已改善特徵和區段人口的報表準確度。</li><li>已改善使用跨裝置 ID 產生批次檔案的準確度。</li><li>已更新說明文件，為各規則提供更詳細的使用案例。請參閱[設定檔合併規則一般使用案例](https://docs.adobe.com/help/zh-Hant/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)、[外部裝置圖形使用案例](https://docs.adobe.com/help/zh-Hant/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)，以及[設定檔連結裝置圖形使用案例](https://docs.adobe.com/help/zh-Hant/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)。</li></ul> |
| [大量管理工具](https://docs.adobe.com/content/help/zh-Hant/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | 我們已發佈新版的「大量管理」工作表，不僅能在 MacOS 和 Microsoft Windows 作業系統上使用，且支援 Experience Cloud 登入。 |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/zh-Hant/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | 新增 [!DNL HTTP Strict-Transport-Security] 的支援功能，此 Web 安全政策可抵禦 Cookie 劫持和通訊協定降級攻擊。 |

**修正和改良**

* 已修正 Audience Marketplace 中，客戶提交每月區段使用情況時 UI 傳回「錯誤 409」的問題。(AAM-50825)
* 已修正客戶暫時無法在「衍生訊號」中建立新衍生訊號的問題。(AAM-50968)
* 已修正客戶無法在「以人員為基礎的目的地」中變更目的地名稱的問題。(AAM-51025)
* 已修正部分使用者以重複帳戶登入 Audience Manager UI 的錯誤。重複帳戶的相關權限會導致這些使用者無法存取部分 UI 及執行作業。(AAM-50818)
* 我們持續改善 Audience Manager UI 的協助工具。(AAM-48932、AAM-49043、AAM-49054、AAM-49371、AAM-49375)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 是功能分支版本，主要作用是供 Brand Portal 使用者 (外部代理商/團隊) 上傳內容至 Brand Portal 及發佈至 AEM Assets，而不需存取作者環境。這項功能稱為[「Brand Portal 資產開源」](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)，為使用者提供雙向機制，方便貢獻資產並與分散於全球各地的其他 Brand Portal 使用者分享資產，達到改善客戶體驗的目的。

   請參閱 [AEM Assets Brand Portal 的新功能](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/introduction/whats-new.html)。

   請參閱[版本說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)。

* **AEM 自動化表單轉換功能**

   「自動化表單轉換」服務可將 PDF 表單自動轉換為調適性表單，有助於實現數位化和現代化，加速資料擷取體驗。這項服務由 Adobe Sensei 提供技術支援，可自動將 PDF 表單轉換為適合裝置的調適性表單，不僅是以 HTML5 為基礎，回應速度也快。運用現有 PDF 表單和 XFA 投資的同時，此服務也會在轉換期間將適當的驗證、樣式和版面配置套用至調適性表單欄位。

   請參閱 [Adobe Experience Manager 自動化表單轉換服務](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)。

* **Cloud Manager 2019.10.0**

   現已發佈 Cloud Manager 2019.10.0 的一般發行說明。說明中也列出部署步驟更新，以及 Maven 專案版本的處理方式。

   請參閱 [Cloud Manager 2019.10.0 發行說明](https://docs.adobe.com/content/help/zh-Hant/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)。

### 自助式

* **Activity Map**

   由於 Adobe Analytics API 經過安全性變更，現已無法再使用 AEM 中的 Activity Map 版本。請參閱[設定 Adobe Analytics 連線](https://helpx.adobe.com/tw/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics)。

   現在起請使用 Adobe Analytics 中適用於 Chrome、Firefox 或 Internet Explorer 的 [Activity Map 瀏覽器外掛程式](https://docs.adobe.com/content/help/zh-Hant/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html)。

* **AEM Screens 專案最佳作法指南**

   全新 _AEM Screens 最佳作法指南_&#x200B;提供全方位的深入分析和實用建議，協助您構想及設計意向式客戶體驗，並在數位招牌實作中具體實現。此外還可引導您運用最佳作法，在 AEM Screens 中部署數位招牌專案，同時對您的業務產生正面影響。

   請參閱 [AEM Screens 專案最佳作法指南](https://docs.adobe.com/content/help/zh-Hant/experience-manager-screens/using/about-guide.html)。

* **無頭式體驗管理**

   單頁應用程式在伺服器端轉譯作業中所使用的[遠端內容轉譯器](https://helpx.adobe.com/tw/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848)，其功能現已完整記錄成說明文件。

* **SPA 和伺服器端轉譯**

   您可根據自身需求，延伸及自訂 AEM 導向 SPA 在伺服器端轉譯遠端內容所使用的轉譯服務。

   請參閱 [SPA 和伺服器端轉譯](https://helpx.adobe.com/tw/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer)。

* **AEM 專案原型**

   AEM 專案原型會建立依最佳作法為基礎所簡化的 Adobe Experience Manager 專案，作為您專屬 AEM 專案的開端。使用此原型時須提供的屬性，可讓您指定此專案所有部分的名稱，以及控制特定的選用功能。

   請參閱 [AEM 專案原型](https://docs.adobe.com/content/help/zh-Hant/experience-manager-core-components/using/developing/archetype/overview.html)。

* **AEM 文件更新**

   請參閱 Adobe Experience Manager 過去三個月的重要文件變更和內容更新。

   請參閱 [AEM 說明文件: 近期文件更新](https://helpx.adobe.com/tw/experience-manager/documentation-updates.html)。

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

* Adobe Campaign Standard: [文件](https://helpx.adobe.com/tw/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/zh-Hant/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/tw/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [文件](https://helpx.adobe.com/tw/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/zh-Hant/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

2019 年 10 月 12 日版本的更新

| 檢視 | 功能 |
|------|---------|
| 搜尋促銷活動 | Advertising Cloud 現在可以同步，並且提供 Yahoo! Japan Display Network 上帳戶的廣告等級追蹤。如果您提供帳戶的登入詳細資料，則所有現有行銷活動、廣告群組及帳戶中的廣告，都可以在行銷活動管理檢視中以唯讀形式取得。點閱率、成本、轉換及其他效能資料，可以在行銷活動管理檢視和基本與進階報表中取得。 |
|  | (使用 Google Analytics 的廣告商) Advertising Cloud Search 可以同步特定 Google Analytics 帳戶、屬性及檢視組合的轉換量度，以便最佳化及報告。頁面檢視、工作階段、跳出率 (以跳出/工作階段來計算) 和工作階段持續時間會自動納入。您針對每個資料來源可以包含多達 16 個額外的量度。 |
|  | (使用 Advertising Cloud-Adobe Analytics 整合之廣告商的現有 Google Ads 帳戶) 適用於 s_kwcid 追蹤程式碼的新格式，可讓 Advertising Cloud 與 Adobe Analytics 報告和分析功能共用帳戶的相關資料。最新的格式包含行銷活動 ID 和廣告群組 ID 的參數，這些參數對於在 Analytics 中 Google Drafts 和 Experiments 行銷活動的行銷活動與廣告群組等級進行準確報告是必要的。如果您的現有 Google 帳戶包含 Google Drafts 和 Experiments 行銷活動，請為每個個別帳戶編輯「帳戶追蹤」設定，以移轉至新的 s_kwcid。如果您沒有 Google Drafts 和 Experiments 行銷活動，則移轉至新格式為選用。備註: 所有新的 Google 帳戶都會自動使用新格式。 |
| 搜尋 Advanced Campaign Management (ACM) | (Google Ads 行銷活動) 現在您可以為 Google 文字廣告和購物廣告範本設定促銷活動層級的最終 URL 尾碼。 |
|  | (Google Ads 行銷活動) 選用「Headline 3」和「Description 2」欄位可用於 Google 擴充文字廣告。 |
| 報表 | 下列 Bing Ads 印象會共用量度 (最新的 Bing Ads API 中已終止)，並且在 10 月 11 日之後不再收集: Search IS% Lost to Rank、Search IS% Lost to Bid (Bing)、Search IS% Lost to Page Relevance (Bing) 以及 Search IS% Lost to Keyword Relevance (Bing)。先前收集的量度仍然可用於報告。 |
| Adobe Analytics 整合功能 | (僅使用 Adobe Analytics 的廣告商) 在 Analysis Workspace 中，「Device (AMO ID)」維度 (從未收集資料) 再也無法使用。若要報告線上 Analytics 資料，請使用「Mobile Device Type」維度。若要依裝置類型報告搜尋引擎流量量度，(例如點閱率、成本和印象)，請繼續使用 Advertising Cloud Search 中的報告。 |
