---
title: Adobe Experience Cloud 發行說明
description: Experience Cloud發行說明
doc-type: 版本說明
last-update: 2019年月
author: mfrei
translation-type: tm+mt
source-git-commit: 3db1b9386db42a9b63a9a313ef80f05f377f1c65

---


# Adobe Experience Cloud 發行說明

Adobe Experience Cloud 中的新功能及修正。

>[!NOTE]
>訂閱 [Adobe 優先產品更新](https://www.adobe.com/subscription/priority-product-update.html)，即可透過電子郵件接收即將發行版本的相關通知。您會在發行前三至五個工作日收到通知。產品發行後才會發佈的新資訊皆會標示發佈日期。

**發行日期: 2019 年 6 月 13 日**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [！DNL [Campaign](#ac)]
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform 發行說明

* 請參閱 [[！Adobe. io上的DNL Experience Platform]發行說明](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) ，以取得最新更新 [!DNL Experience Platform]。

### [!DNL Experience Platform Launch]

* 請參閱 [[！DNL Experience Platform Launch]，](https://docs.adobelaunch.com/) 以取得最新資訊。

## Analytics {#analytics}

Adobe Analytics 中的新功能和修正:

* [Adobe Analytics 中的新功能和修正](#aa-features)
* [給 Analytics 管理員的重要通知](#aa-notices)

如需產品文件，請參閱 [Analytics 說明首頁](https://marketing.adobe.com/resources/help/en_US/reference/)。

### Adobe Analytics 中的新功能和修正 {#aa-features}

| 功能 | 說明 |
| -----------| ---------- |  
| **區段** | 區段中維度的新屬性模型：<ul><li>重復(預設)：包含維度的例項+持續值。</li><li>例項：包含維度的例項。</li><li>非重復例項：包含維度的唯一例項(不重復)。</li></ul> [更多內容](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **區段** | 新區段運算子： **[!UICONTROL 等於任何]** 和 **[!UICONTROL 不等於任何一]** 個。[更多內容...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **除錯程式** | 使用您的Adobe ID登入時，現在可以在Experience Cloud除錯程式中擷取處理後點擊。處理後點擊是伺服器呼叫經過 [!UICONTROL 處理規則] 和VISTA規則後，可讓您驗證 [!UICONTROL 處理規則] 和VISTA規則。**注意**：如果您使用A4T(ElementalDataID)，處理後資料可能需要幾分鐘的時間回來。 |
| **Analysis Workspace:** | 新增立即可用的篩選至左側導軌搜尋。除了您今天看到的項目(維度、量度、核准等)，新篩選條件包括計算量度、客戶屬性、eVar、Prop、視訊等。的新增功能。 |
| **Analysis Workspace** | 我們已對「流失視覺化」新增警告，將區段新增為接觸點-某些無效區段容器組合會導致無效的流失圖表，例如， <ul><li>以訪客為基礎的區段做為訪客內容流失視覺化中的接觸點</li><li>以訪客為基礎的區段做為瀏覽內容流失視覺化中的接觸點</li><li>在瀏覽內容流失視覺化中使用瀏覽型區段做為接觸點</li></ul> <br> [ 更多內容... ](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html) </br> |
| **Analytics文件改進** | Analytics文件已重新整理，現在包含可讓您改善內容的協同作業功能！您可以記錄文件的問題，並建議編輯。doc集已移至 [新網域](https://docs.adobe.com/content/help/en/analytics/landing/home.html)。重新導向應該生效。 |
| **新技術註解使用者指南** | [Tech Notes使用指南](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) 現已推出。目前，其目的在於協助使用者更熟悉第三方分析工具(例如Google Analytics)，以便更熟悉Adobe Analytics。技術註解使用者指南將於未來幾個月展開，納入其他內容。 |

**Analysis Workspace 修正**

* 修正 [!DNL Analysis Workspace] 視覺效果中本地化日文日期資訊的問題。(AN-180114)
* 修正在複製和貼上維度項目後發生的問題。後續的項目搜尋會產生錯誤。(AN-177394)
* 修正自由表格中區段面板中遺漏編輯選項的問題。(AN-171703)
* 修正 **[!UICONTROL 「設定為著陸頁面]** 」功能與大量收件者共用時無法運作的問題。(AN-163922)
* 修正了字串在即時報表中被垂直剪裁的問題。(AN-175980)

**其他 Analytics 修正**

* 已修正管理員使用者無法啓用 **[!UICONTROL 成功事件]** 的問題。(AN-176689)
* 修正使用 **[!UICONTROL 「退出率」]** 度量建立警報時發生的問題。(AN-177476)

### 給 Analytics 管理員的重要通知 {#aa-notices}

| 注意 | 新增日期或更新日期 | 說明 |
| -----------| ---------- | ---------- |
| 分類規則產生器限制 | 新增於2019年月日 | 這些限制不是新的，但已新增至 [此處](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html)的文件。 |
| 新的區段運算子限制 | 新增於2019年月31日 | 自2019年月18日起，區段運算子「包含任何」、「不包含任何」、「包含所有」和「不包含全部」，每個輸入欄位只會限制100字。此限制將套用至在此日期之後的所有新和修改區段。超出限制的現有區段仍可繼續受到支援，但無法修改或儲存，直到輸入欄位被減少為止。這些限制是為了持續改善查詢效能而套用的。 |
| **[!UICONTROL 日期啟用]** 和 **[!UICONTROL 數值 2 分類]** 的近期支援變更 | 2019 年 5 月 28 日更新 | 匯入數值 2 與日期啟用分類的功能已自基底程式碼移除。此變更預計於 2019 年 7 月維護版本中生效。若您的匯入檔案中含有數值或日期啟用欄，系統會自動忽略這些儲存格，至於該檔案中的其他所有資料都將正常匯入。<br/>您仍可透過標準分類工作流程匯出現有分類，並繼續在報表中使用。 |
| _報表總數_計算方式近期變更 | 2019 年 5 月 2 日更新 | Adobe Analytics 預計於 **2019 年 6 月 13 日** 統一所有維度和量度的_報表總數_計算方式。部分報表的總數會因此有所變動，通常會是「Prop」或「客戶屬性」報表。在此變更前，無論報表中是否出現_「未指定」_一項，部分「報表總數」納入或排除_「未指定」_項目的情況不一。<br/>自 2019 年 6 月 13 日起，即使「未指定」並未出現在報表項目中，報表總數都會一律顯示_「未指定」_。此外，在此變更後，使用_「存在」_或_「不存在」_邏輯的區段可能會看到部分維度的不同結果。到時，此變更將會影響 Analysis Workspace、Reports &amp; Analytics、Ad Hoc Analysis、Report Builder 和報表 API。 |
| 更新 的 CSV 下載[!DNL Analysis Workspace] | 2019 年 4 月 10 日 | 自 2019 年 4 月 11 日起，[!DNL Analysis Workspace] 中的 **[!UICONTROL 「CSV 下載」]**(和 **[!UICONTROL 「複製到剪貼簿」]**) 功能已有諸多變動，移除了匯出資料中的格式設定。  <ul><li>不再使用千分位分隔符號。將繼續使用小數分隔符號，其將遵循 **[!UICONTROL 「元件 &gt; 報表設定 &gt; 千分位分隔符號」]** 中定義的格式。注意: 匯出的 CSV 會繼續引用使用逗號作為小數分隔符號的數值。</li><li>不再顯示貨幣符號。</li><li>不再顯示百分比符號。百分比將以小數形式表示，例如: 75% 會表示成 0.75。</li><li>時間會以秒數表示。</li><li>同類群組表格僅會顯示原始值; 百分比符號將會移除。</li><li>如果數字無效，則顯示空白儲存格。</li></ul> |
| 即將變更 [!DNL Analysis Workspace] 偵錯工具命令 | 2019 年 4 月 4 日 | **2019 年 6 月 13 日起**，開啟 [!DNL Analysis Workspace] 偵錯工具的控制台命令將變更為 adobeTools.debug.includeOberonXml。adobe.tools.debug.includeOberonXml 自當天起將無法使用。 |
| 行動瀏覽器版本編號 | 2019 年 2 月 7 日 | 自 2019 年 1 月 8 日起，行動瀏覽器版本編號的小數點位數已從 2 變更為 1。從該日起，版本只會顯示頭兩個層級 (例如 _Firefox 64.0.2_ 現在只會顯示為 _Firefox 64.0_)。 |
| 終止 [!DNL Ad Hoc Analysis] 服務 | 2019 年 1 月 29 日 | Adobe 於 2018 年 8 月 6 日宣佈有意終止 [!DNL Ad Hoc Analysis] 服務。我們將會在確定後公佈服務終止日期。<br/>如需詳細資訊，包括在此期間相容的 Java 版本，請造訪 [Discover Workspace](https://adobe.ly/discoverworkspace)。 |
| Analytics 報表短連結 | 2019 年 1 月 14 日 | 自 2019 年 1 月 17 日星期四起，我們將逐步清理並刪除任何一年內未經造訪的 Analytics 報表短連結。 |
| 終止支援 TLS 1.0 | 2019 年 1 月 10 日更新 | 自 2019 年 2 月 11 日起，Adobe Analytics 報表不再支援 TLS (傳輸層安全性) 1.0 加密技術。我們做出此次變更，持續努力維持安全性的最高標準，並確保客戶資料安全無虞。如果您在2019年月11日後無法連線至Adobe Analytics報告，請將瀏覽器升級至 [最新版本](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html)。<br/>自 2019 年 2 月 20 日起，Adobe Analytics 資料彙集機制不再支援 TLS 1.0。隨著此變更正式發佈，若終端使用者使用不支援 TLS 1.1 (含) 以上版本的舊款裝置或網頁瀏覽器，Adobe 將不再彙集其 Analytics 資料。我們預計這不會對客戶資料或報告造成重大影響。(若您的網站已不支援 TLS 1.0，則不受影響。)<br/>自 2019 年 4 月 11 日起，Adobe Analytics 報告 API 不再支援 TLS 1.0 加密技術。存取該 API 的客戶應確認他們不會受到影響。 <ul><li>使用 Java 7 搭配預設設定的 API 用戶端將需要[進行修改以支援 TLS 1.2](https://www.java.com/en/configure_crypto.html)。(請參閱_變更用戶端端點預設 TLS 通訊協定版本: 從 TLS 1.0 到 TLS 1.2_。) </li><li>使用 Java 8 的 API 用戶端已預設為 TLS 1.2，應該不會受到影響。</li><li> 使用其他架構的 API 用戶端需聯絡其供應商，以瞭解 TLS 1.2 支援的詳細資訊。</li></ul> |
| 資料摘要: post_product_list 欄 - 大小變更 | 2019 年 1 月 9 日 | Adobe 自 2019 年 2 月 7 日起，已將 post_product_list 欄的大小從 64 KB 擴增至 16 MB。此項變更確保處理期間新增至 post_product_list 的銷售 eVar 值，不會截斷產品與收入值。如果您有內嵌 post_product_list 值的程序，請確定這些程序可以處理長度多達 16 MB 的值，否則會在達到 16 KB 時截斷值，以避免資料內嵌失敗。 |
| 影響非活動中 [!DNL Analytics Live Stream] 端點的管理變更 | 2018 年 12 月 20 日 | 自 2019 年 2 月 1 日起，90 天未與作用中消費者連線的 [!DNL Live Stream] 端點可能會遭到停用。您可以聯絡客戶服務以查詢您的 [!DNL Live Stream] 端點，並在必要時重新啟用。此外，請確定您的消費者程序按照該服務的設計意圖，維持穩定連線，並會在連線中斷時重新連線。 |
| 請更新 Adobe [!DNL Report Builder] 因為已不再支援 TLS 1.0 | 2018 年 9 月 7 日 | 因為已不再支援 TLS 1.0，我們建議 [!DNL Report Builder] 使用者在 2019 年 2 月之前下載 5.6.21 版。在當天以後，舊版的 [!DNL Report Builder] 將無法繼續運作。 |

## Audience Manager {#aam}

**修正、改良及淘汰內容**

* Audience Manager現在只會根據使用限制計算作用中演算法模型。
* 解決使用對應模型的特性無法顯示演算法模型覆蓋的問題。
* 解決造成特徵資料夾內容無法顯示，然後資料夾名稱包含括號和/或括號的問題。
* 解決當僅選取一個特徵類型時，造成特徵排序失敗的問題。
* 解決當您每次建立或更新新子檔案夾時，造成特徵檔案夾樹狀結構收合至 [!UICONTROL 「所有特徵] 」檢視的問題。
* 解決嘗試刪除合作夥伴時 [!DNL VIEW_DATASOURCES] ，需要權限的問題。
* 解決造成「區段」頁面中的「 [!UICONTROL 搜尋」][!UICONTROL 方塊] 搜尋所有資料夾而非選取的資料夾的問題。
* 解決建立新演算法模型時，無法透過標題控制項排序 [!UICONTROL 排除特性] 表格的問題。
* 解決造成Audience Manager在執行含空白間隔日期的報表時當機的問題。

## Experience Manager {#aem}

Adobe Experience Manager (AEM) 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

### 產品發行

**Cloud Manager 2019.5.0**

最新的Cloud Manager版本(2019.5.0)不包含重大功能變更，儘管它會提供一些錯誤修正。

* [Cloud Manager 2019.5.0 發行說明](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**適用於 AEM 的 XML 文件**

現已推出適用於XML文件解決方案的3.3版。請參閱下列發行說明：

***進階地圖功能***
* 使用從儲存庫檢視或使用水平列和元素目錄來新增主題參考。
* 在主題參照、區塊(例如導覽標題、格式、範圍等)上新增中繼資料。
* 按一下主題參照應該會開啓編輯器中的主題(如果未勾選並停用含結帳的編輯功能)。
* 新增主題標題和主題群組。
* 使用FrontMatter新增手冊(主題、前言、書籍清單、通知等)和背景(主題、附錄、詞彙表等)。
* 在「作者」模式中，會反白顯示損壞的連結、顯示階層連結，以及「完整標記檢視」。
* 設定地圖層級屬性的能力。
* 設定標題/BookTitle的能力。
* 對重新表格的支援，可新增rel標題、欄、將主題從地圖和存放庫拖放至rel表格、設定連結、範圍及其他連結參數，重新排序儲存格內的連結。
* 工具列介面工具集，以插入之前、插入後插入元素。
* 在主題上套用條件時反白顯示。
* 可一次編輯多個地圖(每個地圖在同一瀏覽器上開啓為標籤)。
* 在地圖面板和儲存庫檢視中，在滑鼠停留時-顯示完整主題標題和檔案名稱。

***完整標籤檢視***

* 在兩個元素之間插入新標記。
* 複製和貼上標籤。
* 允許拖放標記，且不允許在檔案內放置位置。
* 展開和收合標籤。

***DITA特定搜尋增強功能***

* 提供序列化工具來重新索引選取的內容
* 使用者可使用 `contains` 和 `exact match` 搜尋。他們也可以使用下列參數進行搜尋。：
   * 資產中繼資料。例如，客戶 `file name``title`定義的任何自訂中繼資料。
   * DITA屬性名稱及其值。例如, `platform=winOS`.
   * DITA元素名稱及其值。例如, `author = Joe Smith`.
   * DITA元素名稱及其套用屬性。例如，表格具有product= Space Base屬性名稱/值配對。
   * DITA主題和對應中繼資料。
   * DITA資訊類型。針對測驗[d、地圖、主題、概念等)。
   * 資產所在的根資料夾路徑。
   * 文件狀態。
   * 已勾選狀態。
   * 修改日期範圍。
   * CQ標籤。
* 您可以結合一或多個以上的搜尋參數來建立複雜查詢。

***評論功能變更***

* 審核者秘訣：
   * 在升級至3.3版本之前，匯入所有注釋並將變更併入持續審核中。
   * 請確定編輯器未開啓多個標籤。
   * 確定未啓用「完整標記」檢視。
   * 當審核正在進行時，請勿切換「作者」模式和「來源」模式。
* 可指定要檢閱的內容版本。
* 能夠根據基準、日期、標籤或目前作用中版本選擇所選主題的版本，或在建立評論時指定每個主題的版本。
* 能夠傳送相同主題/地圖供審核多次，作者可以存取編輯面板中的所有評論。
* 做為發起人，可為審核者推送稍後版本的內容。當新內容推送供審查時，審核者將會收到通知。
* 身為作者，使用者將能夠在編輯器的審閱面板中查看其所有版本內容的評論留言。作者可依版本號碼篩選注釋。
* 身為作者的使用者，將能夠檢視並將注釋匯入正在審核的編輯器中舊版內容中。

***其他***

* 從「儲存庫」檢視建立新資料夾、主題或地圖。
* 在資產UI中檢視-新增資料夾和主題的功能表選項-「在資產中檢視」。此選項會開啓「資產」UI，使用者可以在左側查看左側的內容樹狀結構，以及右側的所有檔案(位於右側的所有資產選單)。
* 「檢閱控制面板」現在可在DITA專案上做為「並排」，以便追蹤審核者層級和審核任務層級上的審核。
* 已新增將IDML轉換為DITA的功能。
* 提供API，以便對基準中所有指定版本套用指定標籤。
* 在XHTML/DOCX轉換至DITA轉換後啓用事件。您可以使用此事件，將特殊屬性新增至轉換的內容，或用於您需要實施的任何其他自訂邏輯。
* 基線效能標籤改良完成。使用者必須先在所有現有基準上執行指令碼。
* XHTML對DITA轉換進行了改良。
* 發佈最佳化的DITA-OT卸載。
* 修正「清單」檢視中「類型」欄的排序。
* 現在可處理Word與DITA轉換中的階層式樣式。

### 社群

**[Cloud Manager技能產生器網路研討會系列](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

有興趣瞭解DevOS如何簡化日常活動，以簡化雲端Adobe Experience Manager管理的日常活動？Cloud Manager為Adobe Experience Manager提供第一代雲端原生功能，讓雲端敏捷性得以實現，不論您的組織正在開始其DevOS轉型，或是尋找策略來加強現有的DevOS程序。

[在這個每月系列中](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)，您可以直接向Adobe產品團隊瞭解如何開始使用，並使用Cloud Manager功能簡化雲端的Adobe Experience Manager管理。

您將學習下列內容：
* 如何開始使用Cloud Manager並設定CI/CD管線
* 自動啓動和透明服務傳送的運作方式，並且可以簡化雲端的Adobe Experience Manager環境管理
* 如何使用Cloud Manager API並整合現有的DevOS程序

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

### [!DNL Campaign Classic] 19.1春季發行版本

| 功能 | 說明 |
| ------------- | ----------- |
| 控制面板 | 若要提高身為管理員使用者的工作效率，請監控儲存空間、安全的IP位址，並為每個執行個體安裝SSH金鑰來管理SFTP伺服器的設定。請注意，「控制台」僅適用於目前在AWS上代管的客戶。[透過Experience Cloud登入](https://experiencecloud.adobe.com/campaign/controlpanel/)。<br> 如需詳細資訊，請參閱 [詳細說明文件](https://helpx.adobe.com/campaign/kb/control-panel.html) 和 [教學影片](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html)。 |
| 稽核線索 | 身為管理員，請監控並管理Adobe Campaign Classic實例中所做的變更，以提高生產力。「稽核線索」將會記錄在「來源結構」、「工作流程」和「選項」上的動作。您可以快速查看元素是否已建立、修改或刪除。<br>如需詳細資訊，請參閱 [詳細說明文件](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) 和 [教學影片](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html)。 |
| GuardRAil、強穩與調整能力 | 已新增一系列改良 [!DNL Campaign Classic]功能。Adobe Campaign [Classic發行說明中列出了GuardRAil、強穩和可擴充性的改進](https://docs.campaign.adobe.com/doc/AC/en/RN.html)。 |
| 安全SMS Messaging(TLS) | 現在，透過延伸通用的SMPP Connector支援安全SMS。如此可讓使用者加密連線至提供者。<br>如需詳細資訊，請參閱[詳細文件](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)。 |
| 相容性矩陣更新 | 透過這個新版本，Adobe Campaign現在支援下列資料庫系統。請參閱 [相容性矩陣](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle18c</li><li>MySQL5.7(FDA)</li><li>SQL Server2017</li><li>Teradata16(FDA)</li><li>Post格雷QL11</li></ul> |

如需修正和改進，請參閱 [Adobe Campaign Classic] 發行說明](英文)。

### [!DNL Campaign Standard] 19.2春季發行版本

| 功能 | 說明 |
| ------------- | ----------- |
| 控制面板 | 為協助您以管理員使用者的身分提高工作效率，您可以輕鬆監控執行個體的容量並管理執行個體的設定(從SFTP伺服器管理開始)。<br> 如需詳細資訊，請參閱 [詳細說明文件](https://helpx.adobe.com/campaign/kb/control-panel.html) 和 [教學影片](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html)。 |
| 本機通知 | 本機通知訊息可讓您在行動應用程式中提供新資料時通知使用者，即使沒有網際網路或在前景上執行的行動應用程式亦然。本機通知會在特定時間和根據事件觸發行動應用程式。<br>如需詳細資訊，請參閱[詳細文件](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type)。 |
| 工作流程增強功能-新增裝載至外部訊號活動 | 從其他工作流程成功符合定義條件，或REST API呼叫與外部系統整合，以啓動工作流程。這也包含新的測試活動，您可以在此功能上執行測試。<br>如需詳細資訊，請參閱 [詳細說明文件](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) 和 [教學影片](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html)。 |
| 著陸頁面增強功能- Google ReCAPTCHA | 利用Google ReCAPTCHA防止垃圾郵件在您的登陸頁面上出現，而不需要客戶採取任何動作。<br>如需詳細資訊，請參閱[詳細文件](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha)。 |

如需產品文件，請參閱:

* Adobe Campaign Standard: [文件](https://helpx.adobe.com/support/campaign/standard.html) - [ 發行說明](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ 功能影片](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [文件](https://helpx.adobe.com/support/campaign/classic.html) - [發行說明](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [ 功能影片](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* 所有Adobe伺服器上已停用TLS1.0。對於Android4.x裝置，透過SSL連線至Adobe服務時，SDK現在會在建立交握時強制TLS1.1/TLS1.2。

## Advertising Cloud {#adcloud}

更新日期: 2019 年 5 月 6 日 (說明 6 月 8 日發行事項)

| 產品 | 功能 | 說明 |
| -----------| ---------- | ----------  |
| 搜尋促銷活動、標籤分類和限制 | 鍵盤快速鍵 | 您現在可以使用 <b>Shift+ Click</b> 選取多個連續列和 <b>Ctrl+ Click</b> ，以選取多個連續、非連續的列。 |
|  | 選取全部與選擇頁面上的全部 | 在資料表格中，當您選取要選取所有列的頂端核取方塊時，新預設值是選取頁面上所有的列(根據您要檢視25列、50列、100列、200列或連續捲動)。您仍然可以選擇所有可用的列。 |
| 預設檢視、自訂檢視和單機欄自訂設定 | 欄重新排序 | 新的向上和向下按鈕可讓您重新排序欄。您仍然可以拖放欄，像之前一樣重新排序欄。 |

## Target Standard/Premium 19.6.1 (2019 年 6 月 25 日) {#target}

如需最新發行資訊，請參閱 Adobe Target 發行說明。

[Target 版本說明 (發行前)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Target 發行說明 (最新)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

電子商務平台 Magento 提供線上商家彈性的購物車系統，且可控制線上商店的外觀、內容與功能。Magento 提供開放原始碼版本與功能更完整的商務版。

Magento Commerce 屬於 Adobe Commerce Cloud 的一部分，提供具備企業級效能、無限制擴充能力及開放原始碼彈性的電子商務解決方案，適用於 B2C 與 B2B 體驗.

您可以在 [「發行資訊](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) 」頁面上找到我們Open Source和Commerce版本的發行說明。

## Primetime {#primetime}

Adobe Primetime 是一種多螢幕電視平台，可協助媒體公司建立吸引人且個人化的觀看體驗，並從中獲利。

[Primetime 發行說明](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Primetime 說明首頁](http://help.adobe.com/en_US/primetime/)
