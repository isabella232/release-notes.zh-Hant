---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud 發行說明範本
doc-type: 發行說明
last-update: 2019 年 11 月 日
author: mfrei
translation-type: tm+mt
source-git-commit: 2c6076aa0af7b9a273e31b1f8919e006ff48e6b4

---


# 提早存取- Adobe Experience cloud發行說明- 2019年11月

> [!IMPORTANT]此頁面含有搶鮮版內容，於預計發行前可能會有所變更。

Adobe Experience Cloud 中的新功能及修正。

> [!NOTE]訂閱 [[!DNL Adobe 優先產品更新]](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。產品發行後才會發佈的新資訊皆會標示發佈日期。

**發行日期: 2019 年 30 月 10 日**

* [Experience Cloud 介面](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (前往解決方案說明的連結)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (前往解決方案說明的連結)
* [!DNL Advertising Cloud](#adcloud)

## Experience Cloud 介面 {#ecloud}

Experience Cloud 介面與產品管理的發行說明。

* 「動態消息」頁面已於2019年12月過時。 尋找產品中的淘汰通知。 (MCUI-10039)
* 從應用程 [式選取器更新](https://www.adobe.com/marketing/campaign.html) 「Adobe Campaign的更多資訊」連結。 (MCUI-10034)
* 已改善Experience cloud介面核心平台的穩定性和回應速度。 (MCUI-6822)
* 已修正Experience Cloud UI中的安全性弱點。 (MCUI-9942)
* 修正「客戶屬性」中封鎖某些客戶之結構驗證的重大問題。 (MCUI-10024、MCUI-6479)
* 改進「觀眾程式庫」，移除即時觀眾建立不支援的維度。 (MCUI-10046)

如需產品文件，請參閱 [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)。

## Experience Platform {#platform}

Experience Platform、Experience Platform Launch、身分服務和安全性佈告欄的發行說明。

* [Experience Platform Launch](#launch)
* [安全性佈告和諮詢](https://helpx.adobe.com/security.html) (所有 Adobe 產品)

### Experience Platform Launch {#launch}

如需發行說明和產品文件，請參閱 [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)。

## [!DNL Analytics] {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能、增強功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [AppMeasurement](#appm)

如需產品文件，請參閱 [Adobe Analytics 說明首頁](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。

### Adobe Analytics 中的新功能、增強功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- | 
| 客戶歷程分析 | Adobe將於2019年11月21日將「客 [戶歷程分析](https://www.adobe.com/analytics/customer-journey-analytics.html) 」作為Adobe Analytics的附加元件提供。<br><br/>客戶歷程分析可讓您從任何通道獲取所有客戶資料— 線上及線下皆可— 整合到Adobe Experience Platform中，然後像您現有的使用分析工作區分析資料一樣分析這些資料。 「客戶歷程分析」包含可讓您控制如何在分析工作區中透過任何常見客戶ID連接線上和離線資料的功能，最後讓您進行歸因、細分、流量、流失等。 Adobe Analytics中的整個客戶資料集。<br><br/>Analytics Select、Prime和Ultimate客戶有資格購買此附加產品。 如需詳細資訊，請連絡您的Adobe客戶團隊。 |
| 隱私權服務 API: CCPA | 加州消費者隱私權法案 (California Consumer Privacy Act, CCPA) 強化了美國加州居民的隱私權和消費者保護力道。此法案已訂於 2020 年 1 月 1 日生效。<br><br/>CCPA 為加州居民提供了新的資料隱私權，例如有權存取和刪除其個人資料、有權得知其個人資料是否遭到販售或揭露 (以及對象是誰)，以及有權拒絕廠商販售其個人資料。<br><br/>有鑑於 CCPA 即將生效，隱私權服務將會支援請求退出個人資料販售行列的功能。<br><br/>隱私權服務先前稱為 GDPR 服務，其不僅保留了先前的一切功能，現在更擴大為支援 CCPA。<br/><br/>[Analytics 中的 CCPA](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[隱私權服務概觀](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| 隱私權報告: Analytics Admin Console | 為 Analytics 啟用隱私權報告時，報表套裝中會新增一組保留變數。這些變數的設計目的，是要協助系統在點擊層級收集消費者同意資料。<br><br/>新維度:<br/><ul><li>同意管理選擇退出</li><li>同意管理選擇加入</li><li>[同意管理變數](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| 音訊和視訊分析: 隱私權支援 | Media Collection API 已新增兩個新變數:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>這兩者皆為可選變數，可用來擷取消費者在點擊時的同意狀態。<br/><br/>[媒體收集 API 文件](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>新的 Analytics 同意管理內容資料變數已新增至 Federated Analytics 表格。這些變數現在可用於標記選擇退出同盟的分享或販售點擊。<br/><br/>[下載 Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### 修正

* 修正嘗試刪除「未知使用者」擁有的日期範圍時發生錯誤的問題。(AN-185540)

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| EOL of **[!UICONTROL View Archive選項]** | 2019年10月30日 | 宣佈2020年1月，控制面板管理員(元件&gt;控制面板 **[!UICONTROL )中「檢視封存]******」選項的終止日期。 |
| 強制IP登 **[!UICONTROL 入限制選項]** | 2019年10月30日 | 宣佈2020年1月，IP登入白名單(**[!UICONTROL Enforce IP Login Restrictions]**)功能的終止日期，位於「 **[!UICONTROL Admin &gt; Company Settings &gt; Security]** 」（管理&gt;公司設定&gt;安全性）選單中。 |
| 已更新Cookie上的SameSite屬性處理 | 2019 年 10 月 15 日 | 2019年8月，Adobe宣佈將SameSite cookie設定新增至Analytics設定的所有Cookie。 在下列情況下套用邏輯更新：<ul><li>所有非基於Webkit的第三方Cookie都將SameSite屬性設為 `none`。</li><li>所有其他Cookie都沒有設定SameSite屬性。</li></ul> |
| 終止支援 TLS 1.1 | 2019 年 10 月 3 日 | 到了 2020 年 3 月 31 日時，Adobe Analytics 將會移除對於 TLS 1.1 的支援。此變更是我們為了保持最高安全標準並提升客戶資料安全性而不斷努力的其中一項成果。 |
| San Jose FTP Broker 結束倫敦和新加坡的業務 | 2020 年 7 月 | 對於倫敦和新加坡的客戶，我們不再支援於倫敦或新加坡與聖荷西資料中心 [ftp.omniture.com](ftp://ftp.omniture.com/) 之間的代理資料。<br/><ul><li>如果在倫敦，請使用 [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>如果在新加坡，請使用 [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| 更新為 Analysis Workspace 自由表格總計 | 2019 年 9 月 12 日 | 從 2019 年 10 月 開始，自由表格總計列會開始計入套用的[報表篩選器](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html)。就目前而言，總計僅計入分段。經過此變更後，將會更新依據的視覺效果 (例如連結的[!UICONTROL 摘要數字]視覺效果)，以及 CSV 和 PDF 資料。 |
| 關於 Analytics 使用者 `createDate` 欄位的近期變更 | 2019 年 8 月 30 日 | 在 2019 年 10 月或 11 月期間，系統會使用時區資訊，將 Analytics 使用者的 `createDate` 欄位從美國太平洋時間更新為格式正確的日期/時間值。(AN-183468) |
| 支援歷史時區位移 | 2019 年 8 月 8 日 | 現在起，Analytics 會自動處理時間戳記點擊的時區位移。8 月 8 日完成此變更後，系統載入歷史資料加以處理時，便不需要在傳送資料前調整時區位移。 |
| 分類規則產生器限制 | 新增日期: 2019 年 6 月 5 日 | 這些限制不是新的，而是已新增至[這裡](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)的文件。 |
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

請參閱 [AppMeasurement for Javascript 版本說明](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)。

## Audience Manager {#aam}

Audience Manager 中的新功能、增強功能和修正

| 功能 | 說明 |
|--- |----|
| [描述檔合併規則增強功能](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | 我們針對描述檔合併規則發佈了 [!UICONTROL 一系列增強功能]: <ul><li>現在最多可針對100種裝置，批次支援區段評估。</li><li>我們改善特徵和區段人口族群的報告正確性。</li><li>我們改善了使用跨裝置ID產生批次檔案的精確度。</li><li>我們更新了說明檔案，其中包含每個規則的更詳細使用案例。 請參 [閱描述檔合併規則](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)、外 [部裝置圖形使用案例](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)，以及描述 [檔連結裝置圖形使用案例](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)。</li></ul> |
| [大量管理工具](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | 我們發佈了新版的「大量管理」工作表，可在MacOS和Microsoft windows作業系統上運作，並支援Experience cloud登入。 |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | 我們新增支援 [!DNL HTTP Strict-Transport-Security]Web安全政策，以防止Cookie劫持和通訊協定降級攻擊。 |

**修正和改良**

* 我們修正了Audience Marketplace中，當客戶提交每月區段使用時，UI傳回錯誤409的錯誤。 (AAM-50825)
* 我們修正了「衍生訊號」中的錯誤，在短時間內，客戶無法建立新的衍生訊號。 (AAM-50968)
* 我們修正了「以人為本」的目標中，客戶無法變更目標名稱的錯誤。 (AAM-51025)
* 我們已修正部分使用者有重複帳戶以登入Audience Manager UI的錯誤。 由於與重複帳戶相關的權限，這些使用者無法存取UI的某些部分並執行作業。 (AAM-50818)
* 我們持續改進Audience Manager UI的協助功能。 (AAM-48932、AAM-49043、AAM-49054、AAM-49371、AAM-49375)

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5是一項功能發行，主要提供品牌入口網站使用者（外部代理商／團隊）上傳內容至品牌入口網站並發佈至AEM資產，而不需存取作者環境。 這項功能在品牌入口 [網站中稱為「資產採購」](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)，並透過為使用者提供雙向機制來貢獻資產並與其他全球分散的品牌入口網站使用者共用資產，改善客戶體驗。

   請參 [閱「AEM Assets品牌入口網站的新增功能](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html)」。

   See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **AEM Forms Automated Conversion Service**

   「自動化表單轉換」服務可透過將PDF表單自動轉換為可調式表單，協助加速資料擷取體驗的數位化和現代化。 這項服務由Adobe Sensei提供支援，可自動將PDF表單轉換為適用於裝置、回應速度快且以HTML5為基礎的最適化表單。 在運用PDF表單和XFA的現有投資的同時，本服務也會在轉換期間將適當的驗證、樣式和版面套用至最適化表單欄位。

   請參 [閱Adobe Experience Manager Forms Automated Conversion Service](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)。

* **Cloud Manager 2019.10.0**

   Cloud Manager 2019.10.0的一般發行說明現已推出。 附註中也列出部署步驟的更新，以及專案版本處理。

   請參 [閱Cloud Manager 2019.10.0發行說明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)。

### 自助式

* **Activity Map**

   由於Adobe Analytics API中的安全性變更，無法再使用AEM中包含的Activity Map版本。 請參 [閱設定與Adobe Analytics的連線](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics)。

   您現在應該像Adobe Analytics [提供的](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) Chrome、Firefox或Internet explorer使用Activity map瀏覽器外掛程式。

* **AEM Screens專案的最佳實務指南**

   全新的 _AEM Screens最佳實務指南_ ，提供全方位的見解和實用建議，讓您在數位招牌實作中，能夠想像、設計並引入有意的客戶體驗。 此外，它還會引導您如何運用最佳實務，在AEM Screens中部署數位標牌專案時，對您的業務產生積極影響。

   請參 [閱「AEM Screens專案的最佳實務指南」](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html)。

* **無頭體驗管理**

   現在已說明 [](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) 用於單頁應用程式伺服器端轉譯的遠端內容轉譯器功能。

* **SPA和伺服器端演算**

   您可擴充並自訂AEM導向SPA的遠端內容轉換服務，以供伺服器端轉換使用，以符合您的需求。

   請參 [閱SPA和伺服器端演算](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer)。

* **AEM Project Archetype**

   AEM專案原型會建立以最簡化、最佳實務為基礎的Adobe Experience Manager專案，做為您自己AEM專案的起點。 使用此原型時必須提供的屬性可讓您指定此項目所有部分的名稱，並控制某些可選特徵。

   請參 [閱AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html)。

* **AEM檔案更新**

   閱讀有關Adobe Experience Manager在過去三個月中的重要檔案變更和更新。

   請參閱 [AEM檔案：最近的檔案更新](https://helpx.adobe.com/experience-manager/documentation-updates.html)。

### 其他資源

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

### 檔案資源

* Adobe Campaign Standard: [文件](https://helpx.adobe.com/support/campaign/standard.html) - [版本說明](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [發行規劃](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [文件](https://helpx.adobe.com/support/campaign/classic.html) - [版本說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [做法影片](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

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
