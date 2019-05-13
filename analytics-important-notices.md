---
title: 給 Analytics 管理員的重要通知
description: Experience Cloud 發行說明範本
doc-type: 版本說明
last-update: 3 月 2019 日
author: mfrei
translation-type: ht
source-git-commit: 147b01562e6c8d579a2bec0e4fa2841d1791a671

---


# 給 Analytics 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 日期啟用和數值分類的近期支援變更 | 2019 年 2 月 28 日 | 匯入數值 2 與日期啟用分類的功能已自基底程式碼移除。此變更預計於 2019 年 6 月維護版本中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| 大幅更新有關 getPercentPageViewed 外掛程式的說明文件。 | 2019 年 2 月 12 日 | [https://experiencecloud.adobe.com/resources/help/zh_TW/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/zh_TW/sc/implement/getPercentPageViewed.html) |
| 管理員 &gt; 一般帳戶設定 | 2019 年 2 月 7 日 | * 2019 年 1 月後，在倫敦資料中心新建的所有報表套裝，都會預設啟用_「以 0 取代 IP 位址的最後八位數字」_設定，且僅限從 Admin Console 所列範本複製而來的報表套裝設定。若報表套裝的設定是複製自其他報表套裝，則會繼承所選報表套裝的所有設定。<br/> * 如果客戶已在 EMEA 中設定報表套裝，預設不再啟用_「IP 模糊化」_設定。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 終止 Ad Hoc Analysis 服務 | 2019 年 1 月 29 日更新 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 Ad Hoc Analysis 服務，我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，包括在此期間相容的 Java 版本，請造訪 [Discover Workspace](https://adobe.ly/discoverworkspace)。 |
| Analytics 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 Analytics 報表短連結。 |
| 終止支援 TLS 1.0 | 2019 年 1 月 10 日更新 | 自 2019 年 2 月 11 日起，Adobe Analytics 報告將不再支援 TLS (傳輸層安全性) 1.0 加密技術。我們做出此次變更，持續努力維持安全性的最高標準，並確保客戶資料安全無虞。如果您在 2019 年 2 月 11 日之後無法連接至 Adobe Analytics 報表，請將瀏覽器升級為[最新版本](https://marketing.adobe.com/resources/help/zh_TW/sc/user/requirements.html)。<br/>自 2019 年 2 月 20 日起，Adobe Analytics 資料收集將不再支援 TLS 1.0。隨著此變更正式發佈，若終端使用者使用不支援 TLS 1.1 以上版本的較舊裝置或網頁瀏覽器，Adobe 將不再收集其 Analytics 資料。我們預計這不會對客戶資料或報告造成重大影響。(若您的網站已不支援 TLS 1.0，則不受影響。)<br/>自 2019 年 4 月 11 日起，Adobe Analytics 報告 API 將不再支援 TLS 1.0 加密技術。存取該 API 的客戶應確認他們不會受到影響。<br/>* 使用 Java 7 搭配預設設定的 API 用戶端將需要[進行修改以支援 TLS 1.2](https://www.java.com/en/configure_crypto.html)。(請參閱_變更用戶端端點預設 TLS 通訊協定版本: 從 TLS 1.0 到 TLS 1.2_。)<br/>* 使用 Java 8 的 API 用戶端已預設為 TLS 1.2，應該不會受到影響。<br/>* 使用其他架構的 API 用戶端須聯絡其供應商，以瞭解 TLS 1.2 支援的詳細資訊。 |
| 請更新 Adobe Report Builder 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 由於我們不再支援 TLS 1.0，建議 Adobe Report Builder (ARB) 使用者在 2019 年 2 月 7 日前下載 ARB 5.6.21 版。**該日之後，舊版 ARB 將無法繼續運作。** |
| 更新 Analysis Workspace 的 CSV 下載 | 2019 年 1 月 9 日 | 自 2019 年 2 月 7 日起，Analysis Workspace 的 CSV 下載 (和「複製至剪貼簿」) 將不再使用千分位分隔符號。注意: Analysis Workspace UI 將繼續顯示千分位分隔符號。此外，也將繼續使用小數分隔符號，並遵循**[!UICONTROL 「元件]** &gt; **[!UICONTROL 報表設定]** &gt; **[!UICONTROL 千分位分隔符號」]**中定義的格式。 |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 計畫於 2019 年 2 月 7 日起，將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更旨在確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非作用中 Analytics 即時資料流端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的即時資料流端點可能會遭到停用。您可以聯絡 客戶服務以查詢您的即時資料流端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 達拉斯 FTP 伺服器移轉 (ftp2.omniture.com) | 2018 年 10 月 19 日 | 2018 年 10 月 23 日當天，若透過 SFTP 通訊協定連線至 ftp2.omniture.com，您可能需要重新接受 SJ1 網站的主機識別碼。此問題僅會發生於 10 月 23 日當天。請參閱[升級 Adobe FTP 伺服器](https://marketing.adobe.com/resources/help/zh_TW/whitepapers/ftp/ftp_upgrade.html)。 |
| 行動裝置維度的更新 | 2018 年 10 月 16 日 | Adobe 會在 9 月 26 日，將其裝置查找功能更新至裝置 Atlas 的 2.1 API。如此一來，某些瀏覽器的行動裝置維度中，就會顯示更詳細的裝置資訊 (例如 Apple iPhone 7、Apple iPhone 8 Plus 等)。這種新層級的裝置詳細資訊應在明確指示下使用，因為目前並非所有裝置和瀏覽器類型都能提供這類資訊。 |
| 終止支援 Internet Explorer 11 | 2018 年 9 月 12 日 | 2018 年 11 月 13 日起，Adobe Analytics 將停止支援 Internet Explorer 11。請及早改用 Microsoft Edge 或其他支援的瀏覽器。 |
| 終止 Ad Hoc Analysis 服務 | 2018 年 9 月 8 日 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 Ad Hoc Analysis 服務，我們將會在確定後公佈服務終止日期。如需詳細資訊，請造訪 [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/)。從現在開始，我們不會為了支援 Java 9+ 而修改 [!UICONTROL Ad Hoc Analysis]。如果您升級至 Java 9+，[!UICONTROL Ad Hoc Analysis] 將會停止運作。僅支援 Java 8。 |
| 請更新 Adobe [!UICONTROL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 因為已不再支援 TLS 1.0，我們建議 [!UICONTROL Report Builder] (ARB) 使用者在 2019 年 2 月之前下載 ARB 5.6.21 版。在當天以後，舊版的 ARB 將無法繼續運作。 |
| 全新的 Analytics 使用者移轉幫助 | 2018 年 5 月 10 日 | 我們已藉由關於將 Enterprise 與 Federated ID 移轉至 Admin Console 的詳細資訊，來更新 Analytics 使用者的 ID 移轉說明。請參閱[將 Analytics 使用者帳戶移轉至 Enterprise 與 Federated ID](https://marketing.adobe.com/resources/help/en_US/experience-cloud/admin-console/analytics-migration/migrate-enterprise.html)。 |
| 近期即將移除「帳戶活動報表」 | 2018 年 5 月 10 日 | 在 Adobe Analytics 的夏季版本中，「伺服器呼叫使用情況」功能將會取代「帳戶活動報表」。「帳戶活動報表」將在 2018 年 8 月 9 日永久移除。在 2018 年 8 月 9 日之後，若要檢視關於報表套裝流量的摘要資料，請使用「伺服器呼叫使用情況」功能。 |
| 在計算量度中的線性配置模型變更 | 生效日期: 2018 年 7 月 19 日 | Adobe Analytics 將在 7 月 19 日修改計算量度中配置模型的評估方式。到時，使用非預設配置模型的計算量度會移轉到改良後的新屬性模型。[!UICONTROL 「行銷管道上次接觸」]和[!UICONTROL 「行銷管道首次接觸」]配置模型將分別移轉到新的[!UICONTROL 「上次接觸」]和[!UICONTROL 「首次接觸」]屬性模型。(不會廢止[!UICONTROL 行銷管道]，只會廢止計算量度中的兩個配置模型)。此外，我們也會修正線性配置的計算方式。如果您使用含有線性配置模型的計算量度，報表可能會稍微變更，以反映修正後的新屬性模型。[!UICONTROL Analysis Workspace]、[!UICONTROL Reports &amp; Analytics]、[!UICONTROL Reporting API]、[!UICONTROL Report Builder] 和 [!UICONTROL Ad Hoc Analysis] 會反映此次計算量度變更。如需有關此次變更的詳細資訊，請參閱[計算量度](https://marketing.adobe.com/resources/help/zh_TW/analytics/calcmetrics/m_metric_type_alloc.html)文件。 |
| [!UICONTROL ][!UICONTROL 「異常偵測」和「貢獻分析」這兩項功能已從 ]Reports &amp; Analytics 中移除[!UICONTROL ] | 2018 年 4 月 10 日 | 「異常偵測」和「貢獻分析」這兩項功能已從 Reports &amp; Analytics 功能集中移除，現在只能透過 Analysis Workspace 使用。Adobe Analytics Select 與 Foundation 客戶在 Workspace 中只能存取「每日精細度」的「異常偵測」功能。 |
| Adobe 不再核發適用於 Safari 的第三方 s_vi Cookie | 2018 年 4 月 5 日 | 自 2018 年 3 月 20 日起，Adobe 已停止核發適用於 Safari 瀏覽器的第三方 s_vi Cookie。此變更不會影響使用第一方資料收集 Cookie 的客戶。此變更也可避免部分客戶因 Safari ITP 而遇到的造訪次數及訪客數量膨脹的問題。 |
| 請先更新 Report Builder 再將使用者 ID 移轉至 Admin Console | 2018 年 3 月 17 日 | **重要:** 請將您安裝的 Report Builder 更新至最新版本。自 2018 年 4 月起，必須安裝此項更新才能將 Analytics 使用者 ID 移轉至 Admin Console。請參閱 [Analytics 使用者移轉至 Admin Console] 以瞭解更多資訊。 |
| 影響報告的後端變更 | 2018 年 4 月 11 日 | 對 (後端) 查找機制的變更將以數種方式影響報告。請注意，這些變更已在 2018 年 2 月底左右生效:不再允許重新命名頁面。日後，您必須使用分類才能重新命名頁面。自 2018 年 5 月 10 日的發行版本起，系統才會繼續按照目前的設定處理重新命名的頁面。Adobe 正在要求所有客戶在當天之前移轉至分類。在 5 月的發行版本之後，將不再遵循現有的重新命名，而且會回溯變更，恕不另行通知。<br> <br>URL 取代方法已改變。過去，Adobe Analytics 通常會每月儲存與每個頁面名稱相關聯的第一個 URL。日後，我們將儲存每個頁面名稱最新的 URL。(更新日期: 2018 年 4 月 11 日) 不再提供 Reports &amp; Analytics 中用於統計與目前資料的類別報告。自 2018 年 5 月 10 日的 Adobe Analytics 維護發行起停用網站服務 API 中的類別統計報表。不再支援大約 2007 年 1 月 (部份情況為 2006 年) 以前的頁面/Prop 資料。這只會影響頁面、Prop 和頁面事件 (例如自訂連結、退出連結、下載連結)。注意: 此變更不會影響 Analysis Workspace 或 Data Warehouse 中的報告。如果您擁有這些日期以前的資料，將會遇到以下情況: 時間橫跨 2007 年 1 月前後的資料將無法正確合併。搜尋功能無法用於大約 2007 年 1 月以前的資料。 |
| 日期啟用和數值分類的近期支援變更 | 2018 年 5 月 7 日 | 在 2018 年 5 月 10 日的維護發行中，我們將開始限制日期啟用和數值分類的功能。這些分類類型將從「管理員」和「分類匯入工具」介面中移除。從該日期起，將無法新增新的日期啟用和數值分類。但仍可透過標準分類工作流程來管理 (上傳和刪除) 現有分類，並可繼續在報告中使用。 |
| 行銷管道成本和預算的近期支援變更 | 2018 年 2 月 28 日 | 在 4 月的維護發行中，我們將從「管理員 &gt; 行銷管道」選單中移除「行銷管道成本」和「預算」。無法新增新的成本和預算資料。現有成本和預算資料會繼續在報告中可用，但無法更新。 |
| 代碼管理器 - 舊版 H 代碼 | 2018 年 2 月 8 日 | 已不再支援從代碼管理器下載舊版 JavaScript (H 代碼)。 |
| 資料保留: 檢查並設定 Adobe Analytics 的資料保留政策 | 2018 年 2 月 1 日 | **背景:** 2018 年 5 月 25 日起生效的歐盟資料保護規範 (GDPR) 中，規範作為您資料處理者角色的 Adobe 必須採取適當的措施，以協助客戶取得權限、刪除以及其他個人請求。套用適當、安全與即時的刪除政策，是遵守這項法規中非常重要的一個環節。因此，Adobe 想在 2018 年 5 月 25 日 GDPR 生效前，與您合作執行資料保留政策。<br> <br>**預期情況:** 除非您目前已制定 Adobe Analytics 資料保留政策，或做出其他的變更，否則 Adobe 將開始依據 Adobe Analytics 客戶合約中的規定套用資料保留。Adobe 可在 25 個月後刪除資料，大部份的 Adobe Analytics 合約中都已說明此事。一旦您的組織制定了資料保留政策，該政策就會每個月加以執行。資料保留時間若超過 25 個月，需額外收費。資料保留時間也可以透過聯絡客戶服務部門，設定為較短的保留時間。您很快就會收到您組織的額外詳細資料電子郵件。<br> <br>資料保留影響所有存取 Adobe Analytics 歷史資料的方式，其中包含但不限於 Reports &amp; Analytics、Analysis Workspace、Report Builder、Web Services Reporting Api、Data Warehouse 以及資料摘要。**後續步驟:** 識別您組織內負責決定資料保留的利害關係人。您的組織最好瞭解 Adobe Analytics 資料應該保留的適當期限。如果您有任何與 Adobe Analytics 資料保留相關的問題，請聯絡您的 Adobe Customer Success Manager。 |
| 使用者帳戶連結 | 2017 年 10 月 26 日 | Analytics 使用者無需再手動連結 Experience Cloud 與 Analytics 之間的帳戶。使用者可以聯絡 Admin Console 的管理員以要求 Analytics 存取權。Analytics 使用者 ID 移轉可以讓管理員將使用者帳戶從 Analytics「使用者管理」輕鬆移轉到 Adobe「Admin Console」。您的使用者在移轉後，將能存取 Experience Cloud 中提供的已購解決方案和核心服務。[深入了解 Analytics 使用者 ID 移轉](https://marketing.adobe.com/resources/help/zh_TW/experience-cloud/admin-console/analytics-migration/)。 |