---
title: 最新版本注意事項
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關 [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 最新的說明與教學課程
doc-type: release notes
last-update: February 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: e9a119ac8351d6431039b1e0387db1d4875a91bb
workflow-type: tm+mt
source-wordcount: '4933'
ht-degree: 49%

---

# Adobe Experience Cloud 版本注意事項 - 2022 年 2 月

![橫幅](assets/experience-cloud-banner-3.png)

作為體驗創造者，您的成功之路始於 [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home)。 查找大量的How-To文檔庫、自我指導教程、How-To視頻以及適用於所有級別和角色的課程、一個線上對等社區，並在需要時提供專家支援。

準備開始了嗎？ [參加5分鐘的測驗並贏得勝利](https://exploreadobe.com/experience-league-quiz/)!

>[!NOTE]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。 請經常回來查看，持續了解 Experience League 最新消息。

**2022 年 2 月**

上次更新日期：**2022 年 2 月 11 日**

* [[!DNL Experience League] 活動](#events)
* [Adobe [!UICONTROL 系統狀態]](#status)
* [[!DNL Experience Cloud Central Interface Components] 與管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target) (更新日期：**2022 年 2 月 3 日**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [數字型驗藍圖 — 教程](#blueprints)

需要協助嗎？ 請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，了解產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/experience-league.png) [!DNL Experience League]活動 {#events}

若想了解 Adobe 產品專家的答案，Experience League Events 會是個好選擇。三種類型的事件包括：

| 事件類型 | 說明 |
| -----------|---------- |
| [Experience League LIVE](#exl-live) | 由Experience League團隊製作，在YouTube主持的直播節目。 您可以藉此機會與 Adobe 產品專家交流。了解可以透過 Adobe Experience Cloud 應用程式應用可落實的秘訣、技巧和策略。<br> 向下滾動以瞭解有關即將發生的事件的更多資訊，並觀看上承載的過去事件 [Experience League實況](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hant)。 |
| [社群問答咖啡會](#coffee) | 與特邀來賓共處一小時，並在Experience League社區中提交您的問題！ 從Adobe的產品專家那裡獲得問題答案Grab咖啡，並與Experience League社區的產品經理聊天。<br>向下滾動以瞭解我們要覆蓋的內容。 不要忘記在為時已晚之前註冊！ |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | 可在Experience League上使用按需視頻事件。 |

{style=&quot;table-layout:auto&quot;}

### Experience League LIVE{#exl-live}

| 活動日期 | 時間 | 活動名稱 | 格式 | 說明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 2 月 3 日 | 隨選 | [介紹 AEM 內所有最新參考示範](https://www.youtube.com/watch?v=FEREXV826NQ) | 即時視訊活動 | 了解 AEM as a Cloud Service 佈建最快方式、示範並探索相關功能。 |

{style=&quot;table-layout:auto&quot;&quot;

### 社群問答咖啡會{#coffee}

| 活動名稱 | 日期 | 應用程式 | 格式 | 說明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| Adobe Target 社群問答咖啡會 | 2022年2月23日太平洋標準時間早8點 | Adobe Target、Experience Platform、RTCDP | 論壇問答 | [立即註冊](http://atcommunityqacoffeebreak.splashthat.com/?utm_source=in-product&amp;utm_medium=gainsight&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220223)! 請加入Adobe Target社區，從上午8:00到上午9:00 ，瞭解高級產品經理Vishal Chordia的專家答案。 他將回答您所有的Adobe Experience Platform(AEP)、基於受眾的個性化、Real-time Customer Data Platform(RTCDP)與目標的整合，以及與Adobe Target一般相關的問題 |

{style=&quot;table-layout:auto&quot;&quot;

### Adobe Developer&#39;s Live{#dev-live}

| 事件 | 日期與時間 | 類型 | 說明 |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | 隨選 | 影片 | [!DNL Developers Live] 會展示最新的技術進展和開發人員工具，藉以促進各產業的設計、內容創作工作流程、文件服務和客戶體驗管理。檢視專題演講、了解 Analytics API、客戶資料層、Adobe I/O 開放原始碼專案等等。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

發行日期：**2021 年 11 月 16 日**

**新功能**

* Adobe狀態現在在產品級別報告事件。 「狀態雲」和「產品」頁基於事件的產品級報告具有新的外觀和增強的篩選器。 這使您能夠更輕鬆地瞭解您的產品受到的影響 [狀態.adobe.com](https://status.adobe.com/) 和您的電子郵件通知。 如果您未訂閱，請使用此連結設定您的個性化訂閱首選項 [https://status.adobe.com/proactive-notifications/manage](https://status.adobe.com/proactive-notifications/manage)

* 現在，狀態首頁已個性化，並根據您的權利和產品訂閱篩選了事件。 請在 **狀態.adobe.com** > **[!UICONTROL 我的事件]** 頁籤。

**今日推出的新功能和增強功能**

| 功能 | 說明 |
| ------- | -------|
| 事件的產品級報告 | <ul><li>每個產品上都有一個標題 [!UICONTROL 狀態] 包括產品的最新更新、歷史記錄和影響屬性</li><li>現在，電子郵件遵循的是產品級影響報告而不是事件級報告的相同格式</li></ul> |
| 個性化視圖 [!UICONTROL 狀態] 首頁 | <ul><li>引入新觀點， **[!UICONTROL 我的事件]** 的 [!UICONTROL 概述] 的子菜單。 此視圖根據您的權利和訂閱篩選事件</li><li>權利可以是組織或個人的權利。 訂閱可用於產品或事件</li></ul> |
| 增強的用戶體驗 | <ul><li>雲頁概括了所有產品的可用性，並能夠按產品、區域、日期和事件類型進行篩選</li><li>產品頁面包含所有功能的可用性摘要以及事件和歷史記錄的詳細視圖</li><li>增強的篩選器按功能、資料中心/環境（如果適用）、區域、日期、事件類型和事件/維護狀態提供</li></ul> |
| 增強的訂閱，包括產品產品更新 | <ul><li>Adobe Analytics產品更新為客戶友好視圖(現有 [!DNL Analytics] 訂閱遷移到新產品)</li><li>針對 [!DNL Customer Journey Analytics]</li></ul> |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 與管理 {#ecloud}

| 功能 | 說明 |
| ------- |-------|
| **[!UICONTROL 朗瑟]** （快捷方式）添加到 [Experience Cloud](https://experience.adobe.com/home) 著陸 | 您可以在新的Journey Optimizer和Experience Platform活動下訪問最近的快捷方式 **[!UICONTROL 朗瑟]** 的子菜單。 此更新還包括登錄頁上的常規佈局和響應改進。 |
| **[!UICONTROL 沙箱]** 移到標題欄 | 現在，所有Experience Platform介面應用程式的標題中都整合了「Sandboxes」指示器。 請參閱 [沙箱](https://experienceleague.adobe.com/docs/experience-platform/sandbox/ui/user-guide.html?lang=zh-Hant) 的子菜單。 |

{style=&quot;table-layout:auto&quot;&quot;

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理**&#x200B;的說明資源

* [發行說明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) 用於Experience Cloud中央UI元件
* [用戶和產品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant) Experience Cloud（管理）
* 位置服務 [發行說明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)
* 產品文檔 [人員 — 客戶屬性和受眾庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

最新版本資訊和新文檔，用於Experience Platform和 [!UICONTROL 移動SDK]:

發行日期：**2022 年 1 月 26 日**

* [Experience Platform 發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)

### 最新 Experience Platform 教學課程與其他課程 {#tutorials-platform}

針對 Experience Platform 所發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [使用 Web SDK 實作 Adobe Experience Cloud](https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html) | 多頁教程 | 瞭解如何使用Adobe Experience PlatformWeb SDK實施Experience Cloud應用程式。 本教程介紹如何使用名為 _盧馬_。 的 [盧馬](https://luma.enablementadobe.com/content/luma/us/en.html) 站點具有豐富的資料層和功能，使您能夠構建一個真實的實施。 立即開始！ |
| 2022 年 2 月 | [通過即時CDP和Adobe Target實現下一次的個性化](https://experienceleague.adobe.com/docs/platform-learn/tutorials/experience-cloud/next-hit-personalization.html) | 影片 | 瞭解如何在下一次點擊時個性化 [!UICONTROL Real-time Customer Data Platform] 和Adobe Target。 即時CDP中的Adobe Target目標允許您使用Adobe Target的Experience Platform段實現同頁和下一頁個性化，並提供治理和隱私支援。 |

{style=&quot;table-layout:auto&quot;&quot;

### Adobe Mobile SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2022 年 2 月 16 日**

* Adobe Analytics [發行說明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en) (**新位置**)
* Adobe Analytics [產品文檔和教程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

### [!DNL Customer Journey Analytics] {#cja}

發行日期：**2022 年 2 月 16 日**

* Customer Journey Analytics [發行說明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en)  (**新位置**)
* Customer Journey Analytics [產品文檔和教程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### AppMeasurement {#appm}

版本： **2.22.4**

* [JavaScript 適用的 AppMeasurement 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 最新 Analytics 教學課程與其他課程 {#tutorials-analytics}

針對 Adobe Analytics 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [使用處理規則操控傳入的資料](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=en) | 影片 | 獲取Adobe Analytics處理規則的概述，並瞭解它們的用途。 瞭解一些提示、示例，甚至警告。 |
| 2022 年 2 月 | [設定清單變數](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=en) | 影片 | 當您必須一次將多個值放入eVar（轉換變數）時，您將做什麼？ 列出解救的變數！ 了解如何以及為何要在 Adobe Analytics 中設定和使用清單變數。  |
| 2022 年 2 月 | [配置通信分類](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-traffic-classifications.html?lang=en) | 影片 | 瞭解如何為通信量變數配置分類(通常稱為 _道_&#x200B;的 _pagename_&#x200B;等等。 |
| 2022 年 2 月 | [配置轉換分類](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-conversion-classifications.html?lang=en) | 影片 | 瞭解如何為轉換變數配置分類，也稱為 _埃瓦爾_。 此配置也適用於產品和清單變數。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修正與改良。

* 已解決在透過 Swagger 介面執行時導致所有 API 呼叫傳回 `Undocumented` 錯誤的問題。(AAM-59190)
* 已解決在某些情況下導致指派錯誤的用戶角色給合作夥伴的問題。(AAM-59451)
* 已解決導致 API 要求區分大小寫驗證標題的問題。(AAM-58528)

有關自助資源，請參見 [Audience Manager文檔和教程](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) Experience League

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以掌握最新的版本資訊。

### Experience Manager 產品發行

* **Experience Manager as a Cloud Service**

   觀看 [2022年1月發佈概述視頻](https://video.tv.adobe.com/v/340120) 2022.1.0（2022年1月）版中添加的功能摘要。

   * [](https://video.tv.adobe.com/v/339278)2021 年 12 月版本總覽新功能影片。
   * [](https://video.tv.adobe.com/v/338253)2021 年 10 月版本總覽 新功能影片。
   * [](https://video.tv.adobe.com/v/337381)2021 年 9 月版本總覽 新功能影片。

   * **Experience Manager Assets as a Cloud Service**

      _Experience Manager Assets新功能_

      * Dynamic Media — 您現在可以使用Experience Manager-Dynamic Media介面配置 [常規設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html) 和 [發佈設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html) 而不必去Dynamic Media Classic案頭應用程式。
      * Dynamic Media 現在支援 MXF 影片的攝取、預覽、播放和發佈。 尚不支援 MXF 影片的附註和可訂購影片。
      * 在設定遠端 DAM 和 Sites 部署之間的連接後，遠端 DAM 上的資產可在 Sites 部署中使用。 您現在可以在遠端 DAM 資產或檔案夾上執行[更新、刪除、更名和移動操作](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=en)。這些更新在 Sites 部署中可自動使用，但有一些延遲。

      _Experience Manager Assets 發行前頻道中的新功能_

      * Dynamic Media現在提供了靈活性， [配置一個公司別名帳戶](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=en) 在用戶介面中，以更新出廠設定的Dynamic MediaURL和Viewer Embed代碼。 此操作對SEO產生積極影響，以反映對您的業務環境所做的更新，如品牌重塑。
      * 現在，您可以使用Experience Manager Assets用戶介面：

         * 配置儲存庫中重複資產的檢測。
         * 配置向影像添加數字水印。
      * 管理員現在可以為大下載配置電子郵件服務。 它允許用戶 [啟用大量下載的電子郵件通知](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=en#enable-email-notifications-for-large-downloads) 從Experience Manager Assets介面。 用戶在完成下載過程後接收包含存檔的zip資料夾的下載連結的電子郵件通知。
      * 的 [管理發布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en) 利用改進的用戶介面增強特徵。 用戶可以將內容發佈到選定目標或從選定目標取消發佈內容， [添加內容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#add-content) 到發佈清單。 他們也 [包括資料夾設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#include-folder-settings) 發佈所選資料夾的內容並應用篩選器， [計畫發佈](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#publish-assets-later) 到更晚的日期或時間。

      _錯誤修復_

      * 將沒有原始格式副本的未處理資產發送到Asset compute以進行處理，同時將資產從本地Experience Manager遷移到Cloud Services。
   * **Experience Manager Forms as a Cloud Service**

      _Forms_

      * **Experience Manager Formsas a Cloud Service — 通信** — [通信API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=en) 幫助您將模板和XML資料組合起來，以生成各種格式的打印文檔。 該服務允許您以同步和批處理模式生成文檔。 API可幫助您建立應用程式，以便您執行以下操作：

         * 使用 XML 資料填寫範本檔案來產生文件。
         * 以各種格式生成表單，包括非互動式PDF打印流。
         * 從 XFA 表單 PDF 產生列印 PDF。
         * 通過將多組資料與源模板合併，批量生成PDF、PostScript、PCL和ZPL文檔。
      * **記錄文檔的自定義字型和使用Communications API建立的PDF文檔**  — 現在，您可以在使用Communications API生成的PDF文檔中使用品牌批准的字型，以符合您的組織要求。

      _Forms預發行頻道的新功能_

      * [匯編程式API](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/)  — 匯編器API，用於組合、重新排列、增大和獲取有關PDF文檔的資訊。
   * **Cloud Manager**

      _發行日期_

      Cloud Manager在Experience Manageras a Cloud Service2022.01.0中的發佈日期為2022年1月20日。
下一版計畫於2022年2月10日發行。

      _新功能_

      * 雲管理器 [當檢測到使用了相同的git提交時，避免重建代碼庫](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=en#build-artifact-reuse) 在多個全棧流水線執行中。
      * 現在訪問Experience Manager環境日誌需要 **[!UICONTROL 部署管理器]** 產品配置檔案。 沒有此配置檔案的用戶在用戶介面中看到禁用按鈕。
      * 用戶介面不允許為未將站點作為解決方案啟用的程式配置前端管道。
      * 在生成Git密碼時，顯示到期日期。








### 社群

* **Experience ManagerGEM網路研討會： _使用無Experience Manager頭和App Builder更快地構建站點_**

   **日期**:2022年3月23日星期三
   **時間**:上午8點(PST)、5:00(CET)或9:00(IST)
   **揚聲器**:Duy Nguyen,Adobe軟體開發工程師
   [註冊參加網路研討會，網址為https://adobe.ly/3oCkEsh](https://adobe.ly/3oCkEsh)
   [關於網路研討會的常見問題](https://adobe.ly/3LkSWdm)

* 播放2022年1月Experience ManagerGEM。網路研討會： [_Experience Manageras a Cloud Service2021年回顧和2022年展望_](https://adobe.ly/3rqbSOz)

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| ------| ------| ----- | -----| ----|
| 2022 年 2 月 | [建立服務憑據](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/service-credentials.html) | 影片 | 瞭解如何建立服務憑據以確保與as a Cloud Service的整合進行安全AEM身份驗證。 | AEM FormsCS |
| 2022 年 2 月 | [建立JSON Web令牌(JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) | 文章 | 瞭解JSON Web Tokens（一種開放的行業標準RFC 7519方法，用於在雙方之間安全地表示聲明）。 `JWT.io` 此示例中使用庫來生成JWT。 | AEM FormsCS |
| 2022 年 2 月 | [Exchange JWT for Access Token（訪問令牌的Exchange JWT）](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-access-token.html) | 文章 | 在 [建立JSON Web令牌(JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) 步驟與Adobe IMS API交換為訪問令牌，然後可用於訪問AEMas a Cloud Service。 瞭解如何請求訪問令牌向IMSPOST服務發送包含JWT 、 clientid 、 clientsecret的認證請求。 | AEM FormsCS |
| 2022 年 2 月 | [在生成的pdf中嵌入字型](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/intellij-set-up.html?lang=en#add-the-fonts-module) | 文章 | 瞭解如何安裝 [!DNL IntelliJ] 社區版。 | AEM FormsCS |
| 2022 年 2 月 | [撥打POST](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/merge-data-with-template.html) | 影片 | 瞭解如何使用必要的參數對端點進行HTTPPOST調用。 模板和資料檔案作為資源檔案提供。 | FormsCS |
| 2022 年 2 月 | [從舊原型遷AEM移](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/updating-project-archetype.html?lang=en) | 影片 | Desc. | FormsCS |
| 2022 年 2 月 | [AEM FormsCS中工作流資料外部儲存](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/create-aem-workflow/externalize-workflow.html?lang=en) | 影片 | 瞭解如何在Azure儲存中儲存您的工作流資料。 AEM FormsCS具有將工作流資料（如變數、附件等）儲存在外部儲存帳戶中的新功能。 | AEM FormsCS |
| 2022 年 2 月 | [將Adobe Analytics與Experience Cloud設定自動化整合](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/integrations/adobe-analytics-exc-setup-automation.html) | 影片 | 瞭解Experience Cloud設定自動化如何提供一種簡單而自動化的方法，將Experience Manager Sites與Experience Platform Launch和Adobe Analytics整合併測試。 | AEM Sites |
| 2022 年 2 月 | [產品Recommendations](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/product-recommendations.html) | 影片 | 瞭解如何在Adobe Experience Manager()店面動態插入這些產AEM品建議。 Adobe Commerce推薦引擎由Adobe Sensei提供。 | AEMAdobe Commerce |

{style=&quot;table-layout:auto&quot;&quot;

### Experience Manager 版本資訊

所有 Experience Manager 的發行說明都會保留在以下頁面：

* [Experience Manager as a Cloud Service 發行說明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Experience Manager Cloud Manager 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hant)
* [Automated Forms Conversion Service 版本注意事項](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hant)
* [Experience Manager 6.5 Service Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Experience Manager 6.4 Cumulative Fix Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hant)
* [Experience Manager Assets Dynamic Media 版本注意事項](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hant)
* [Experience Manager Brand Portal 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hant)
* [Experience Manager 桌面應用程式版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hant)
* [Experience Manager Dispatcher 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hant)
* [Adobe Primetime 版本注意事項](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hant)
* [Livefyre 版本注意事項](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hant)

### 適用於 Experience Manager 的其他說明資源

* [Experience Manager as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Cloud Manager 使用手冊](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hant)
* [Experience Manager 6.5 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hant)
* [Experience Manager 6.4 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hant)
* [Experience Manager 6.3 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant)
* [Experience Manager 6.2 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant#previous-updates)
* [舊版 Experience Manager 文件](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 說明首頁](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hant)
* [Experience Manager 文件：最近更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hant#aem-as-a-cloud-service)

## ![表徵圖](/assets/ec_appicon_24.png) XMLAdobe Experience Manager文檔 {#xml-doc}

Adobe Experience Manager 的 XML 文件是部署至 AEM 的應用程式。 這是一個功能強大、企業級元件內容管理解決方案 (CCMS)；此方案可支援 Adobe Experience Manager 的本機 DITA 支援、使 AEM 能夠處理以 DITA 為主的內容建立和傳遞。

了解更多關於 [AEM 的 XML 文件](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html)。

### 適用於 Adobe Experience Manager 的 XML 文件最新教學課程 {#tutorials-xml-doc}

針對 Adobe Experience Manager 的 XML 文件所發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [XML 文件發佈](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=en)。 | 影片 | 了解關於 Adobe Experience Manager 的 XML 文件，這是一個功能強大、企業級元件內容管理解決方案 (CCMS)。此方案可提供 Adobe Experience Manager 本機的 DITA 支援，使 AEM 能夠處理以 DITA 為主的內容建立和傳遞。 |
| 2022 年 1 月 | [使用 AEM 的 XML 文件進行的 Output 生成](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=en) | 影片和文章 | 了解 Map 儀表板、報告、使用基線和條件發佈等。 |

{style=&quot;table-layout:auto&quot;&quot;

### 其他資源

* [XMLAdobe Experience Manager文檔](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=en) -Experience League教程
* [Adobe Experience Manager學習和支援的XML文檔](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html)  — 產品文檔

## ![圖示](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教學課程 {#tutorials-commerce}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [升級Adobe Commerce/Magento Open Source](https://experienceleague.adobe.com/docs/commerce-operations/upgrade-guide/overview.html) | 使用手冊 | 獲取完成升級過程所需的所有幫助。 |
| 2022 年 2 月 | [Adobe Commerce2.4升級研討會](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade-workshop.html?lang=en) | 影片 | 瞭解準備下次升級到2.4.4或更高版本時要遵循的步驟和最佳做法。 |
| 2022 年 2 月 | [在 PhpStorm 上使用升級相容性工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/uct-phpstorm.html?lang=en) | 影片 | 瞭解如何使用 `PhpStorm` 插件 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新時間： **2022年2月1日**

* 有關預發行資訊，請參見 [Adobe Target預發佈](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)
* 有關當前資訊，請參見 [Adobe Target發佈說明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品發行版

進一步了解已發行的最新功能、改良與修正：

* (新增!) [Campaign Standard22.1版](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant)
* [Campaign v8.2.10](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=zh-Hant)
* [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)

### 新 [!DNL Campaign] 教學課程和其他課程 {#tutorials-campaign}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 | 版本 |
| ------| ----- | -----| ------ | --- |
| 2022 年 2 月 | [使用Adobe Campaign工作流進行資料管理的基礎知識](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/data-management-fundamentals.html?lang=en) | 影片 | 瞭解以維和工作表為目標是什麼，以及Adobe Campaign如何跨不同資料源管理資料。 | Campaign v8 |
| 2022 年 2 月 | [更改資料源](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/change-data-source.html?lang=en) | 影片 | 瞭解如何使用「更改資料源活動」更改工作流工作表的資料源，以靈活管理不同資料源（如FDA、FFDA和本地資料庫）的資料。 | 市場活動v8 |

{style=&quot;table-layout:auto&quot;&quot;

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [發行說明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=zh-Hant) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 做法影片

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

有了 Journey Optimizer，您就可以從單一應用程式為幾百萬名客戶管理排程的全通道行銷活動及一對一時刻，還有智慧型決策和見解讓整個旅程最佳化。

### 最新 Journey Optimizer 產品發行版

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hant)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

運用 Experience Platform 聰明地即時預測每個人的需求，在不同體驗管道大規模地協調客戶歷程。

### 最新 [!DNL Journey Orchestration] 產品發行版

進一步了解 [[!DNL Journey Orchestration]  版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

#### [!DNL Journey Orchestration] 的更多資源

* [Journey Orchestration 文件](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是適用於潛在客戶管理以及想要透過參與複雜購買旅程的每個階段來轉換客戶體驗的 B2B 行銷人員的完整應用程式。

### Marketo Engage 核心更新

如需最新發行排程資訊和版本注意事項，請參閱「[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)」。

## ![圖示](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是統一的工作管理應用程式，用於共用構想、建立內容、管理複雜的流程並執行其最佳工作。

請參閱 [[!DNL Workfront]  發行版本](https://one.workfront.com/s/product-releases)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 版本注意事項。

* [ [!DNL Advertising Cloud] 的新功能](#adcloud-all)
* [ [!DNL Advertising Cloud DSP] 中的新功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新功能](#adcloud-search)
* [新  [!DNL Advertising Cloud] 教學課程](#tutorials-ad-cloud)

### [!DNL Advertising Cloud] 的新功能 {#adcloud-all}

最新更新：**2021 年 10 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| Analytics for Advertising Cloud | 如果您的組織想從舊式Adobe Analytics `visitorAPI.js` 圖書館到Adobe Experience Platform圖書館(`alloy.js`)，必須進行更改才能啟用ID拼接。 請參閱「[在 Adobe Experience Platform 中使用  [!DNL Last Event Service] JavaScript 資料庫 [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=zh-Hant)」。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Advertising Cloud DSP] 中的新功能 {#adcloud-dsp}

最新更新：**2021 年 10 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| 自訂報告 | 您現在可以為自訂報告建立和管理 [!DNL Amazon S3] 和不同類型的 FTP 傳送位置，稱為 *[!DNL report destinations]*。設定報告目標後，您可以將每個新的自訂報告設為傳送到單一目標類型的一個或多個位置，或傳送到電子郵件收件者。更新您的 [!DNL Amazon S3]，則 FTP 認證將不會中斷報告傳遞。<br><br>您現有的報告仍會傳送到指定的電子郵件收件者。若要設定傳遞到不同的報告目標，請使用新目標建立報告。 |
| [!UICONTROL 套件]，[!UICONTROL 位置]，和 [!UICONTROL 廣告]檢視 | 當您查看某一天的資料時，趨勢圖表將包括每小時資料。將游標放在任意點上可查看該小時的資料。 |
| [!UICONTROL 位置] | 位置[!UICONTROL 檢查]現在包含[!UICONTROL 詳細目錄]標籤，顯示位置的所有交易及其相關指標。使用這些資訊進行快速調整或疑難排解問題，而無需產生自訂報告。 |
| [!UICONTROL 廣告] | (有權在其廣告中包含 Clearcastclock 數字的用戶) 如果您使用附加到其他廣告的時鐘數字，DSP 將不再顯示錯誤。**請注意：**&#x200B;最佳實務是為每個廣告影片使用唯一的時鐘數字。否則，發佈者不會核准所有廣告。 |
| [!UICONTROL 交易識別碼] | [!UICONTROL 交易識別碼]設定和用戶界面中的其他地方反映了 [!DNL Magnite]SSP<br> 的新品牌：<ul><li>SSP「[!DNL Tremor]」([!DNL Telaria]) 現為「[!DNL Magnite CTV]」。</li><li>在接下來的幾週內，「[!DNL Rubicon]」將變更為「[!DNL Magnite DV+]」，其中 [!DNL DV+] 代表顯示、影片和其他格式，例如音訊。</li></ul> |
| [!DNL Freewheel] 程式化預留交易 | 現在您可以從[!UICONTROL 廣告]檢視中找到 [!DNL Freewheel] 程式化預留交易的廣告狀態。以前您只能從[!UICONTROL 交易]檢視中查看狀態。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

上次更新時間： **2022年2月4日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 布爾克謝特]。 [!UICONTROL 通知中心] | （1月22日發佈）現在由Advertising Cloud Search處理的所有針對牛咭操作完成或失敗時發送的有關牛蒡子的電子郵件通知 [!UICONTROL 通知中心]。<br><br>[!UICONTROL 布爾克謝特] 是具有自己的通知首選項的新通知類型，在 [!UICONTROL 通知中心]。 預設情況下會啟用電子郵件通知和Web通知，但您可以選擇更改通知設定。<br><br>電子郵件通知的格式和內容使用 [!UICONTROL 通知中心] 模板，並包括關聯的工作表檔案或錯誤檔案的直接下載連結。 |

{style=&quot;table-layout:auto&quot;&quot;

### 新 Advertising Cloud 教學課程 {#tutorials-ad-cloud}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [Advertising Cloud 教學課程](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=en) | 影片 | 有五個關於 Advertising Cloud DSP 的新影片教學課程。 |

## ![圖示](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

針對 Adobe Document Cloud 發佈的新影片、教學課程或其他課程。

### 新 Document Cloud 課程與教學課程 {#tutorials-doc-cloud}

針對 Adobe Document Cloud 發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [使用表單域](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/workforms.html?lang=en) | 影片 | 瞭解如何添加各種類型的表單域、設定表單域屬性以及添加安全性以建立高質量的專業表單。 |
| 2022 年 2 月 | [Optimize PDFSEO（搜索引擎優化）](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizeseo.html) | 影片 | 瞭解如何優化PDF，以改進Web上的可發現性和搜索引擎排名。 |

{style=&quot;table-layout:auto&quot;&quot;

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Acrobat標籤](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) 適用於企業的 Adobe Creative Cloud {#creative-cloud}

如需了解最新教學課程，請參閱「[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hant)」。

## 數字型驗藍圖 — 教程 {#blueprints}

[數字型驗藍圖](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) 是可重複實施的，使您能夠解決戰略並快速解決既定的業務問題。 每個藍圖都提供一系列工件，它們解釋了高價值的業務問題、體系結構、實施步驟、技術考慮事項以及指向相關文檔的連結。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [客戶歷程](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en) | 影片 | Customer Journeys解決了品牌通過電子郵件、SMS和移動警報等渠道主動接觸客戶並與其進行溝通的能力。 |
| 2022 年 2 月 | [市場活動v7藍圖](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=en) | 影片 | Adobe Campaignv7是為電子郵件和直郵等傳統營銷渠道構建的宣傳工具。 它提供強大的ETL和資料管理功能，幫助制定和組織完美的活動。 |

{style=&quot;table-layout:auto&quot;&quot;
