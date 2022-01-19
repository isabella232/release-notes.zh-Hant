---
title: 最新版本注意事項
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關 [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 最新的說明與教學課程
doc-type: release notes
last-update: January 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 5f66a23cec9c0a92528f3ccb96b4a7889fd38b46
workflow-type: tm+mt
source-wordcount: '6585'
ht-degree: 39%

---

# Adobe Experience Cloud 版本說明 - 2022 年 1 月

![橫幅](assets/experience-cloud-banner-3.png)

瞭解有關 [Adobe Experience Cloud產品](https://business.adobe.com/products/adobe-experience-cloud-products.html)。 獲取有關Experience League的最新自助文檔、教程和課程。

>[!NOTE]
>
>要接收有關此頁面更新的每月電子郵件通知，請訂閱 [Adobe優先順序產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。 經常回去看，瞭解Experience League上發生的情況。

**2022 年 1 月**

最新更新：**2022 年 1 月 14 日**

* [[!DNL Experience League] 活動](#events)
* [[!DNL Experience Cloud Central Interface Components] 與管理](#ecloud)
* [Adobe [!UICONTROL 系統狀態]](#status)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)

需要協助嗎？訪問 [Adobe Experience League](https://experienceleague.adobe.com/#home) 有關產品和技術文檔、Adobe教學課程、視頻教程、快速答案、社區見解和講師指導培訓。

## ![圖示](/assets/experience-league.png) [!DNL Experience League]活動 {#events}

若想了解 Adobe 產品專家的答案，Experience League Events 會是個好選擇。以下是可用的活動：

* [Experience League Live](#exl-live)：YouTube 上的直播和隨選視訊活動
* [社區問答咖啡休息](#coffee):與Experience League社區產品經理的交流
* [Adobe Developer&#39;s Live](#dev-live)：Experience League 提供的隨選視訊活動

時間表和活動如下：

### Experience League LIVE{#exl-live}

[Experience League LIVE 是 Experience League 團隊製作的直播串流節目。](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hant)這是與Adobe產品專家聯繫的機會。瞭解您可以應用於Adobe Experience Cloud應用程式的可操作的提示、技巧和策略。

| 活動日期 | 時間 | 活動名稱 | 格式 | 說明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 1 月 25 日 | 上午9點(PST) | [跨資料源分析您的業務](https://www.youtube.com/watch?v=L2EWCOHeyXI) | 即時視訊活動 | 使用Customer Journey Analytics將所有資料放到一個位置。 |
| 2022 年 2 月 3 日 | 下午 12 點 (EST) | [介紹中的所有新參考演示AEM](https://www.youtube.com/watch?v=FEREXV826NQ) | 即時視訊活動 | 瞭解調配、演示和探索as a Cloud Service功能的最快方AEM法。 |

{style=&quot;table-layout:auto&quot;}

過去的劇集可在 [Experience League實況](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en)。

### 社群問答咖啡會{#coffee}

與特邀來賓共處一小時，並在Experience League社區中提交您的問題。 從Adobe的產品專家那裡獲得問題解答！

| 活動名稱 | Date | 應用程式 | 格式 | 說明 |
| -----------| ---------- | ---------- | ---------- |---------- |
| Customer Journey Analytics 分析學的未來 | 2022年1月18日太平洋標準時間早8點 | Adobe Analytics,Customer Journey Analytics,Experience Platform | 論壇問答 | 在Adobe Analytics的Group Product Manager的Trevor Paulsen分析社區發佈您的問題。<br>[詳細資訊和註冊](https://analyticscommunityqacoffeebrea.splashthat.com/?utm_source=community-thread&amp;utm_campaign=coffee_talk_AA&amp;utm_content=220118) |
| Adobe Target與Journey Optimizer、Adobe Target介面和一般目標專題的整合 | 2022年1月19日太平洋標準時間早9點 | Adobe Target,Journey Optimizer | 論壇問答 | 和喬恩·特赫羅呆一個小時，在Adobe Target社區提問。<br>[詳細資訊和註冊](https://communitycoffeebreakadobetarge.splashthat.com/?utm_source=email&amp;utm_campaign=coffee_talk_AT&amp;utm_content=210119) |

{style=&quot;table-layout:auto&quot;&quot;

### Adobe Developer&#39;s Live{#dev-live}

| 事件 | 日期與時間 | 類型 | 說明 |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=zh-Hant) | 按需 | 影片 | [!DNL Developers Live] 會展示最新的技術進展和開發人員工具，藉以促進各產業的設計、內容創作工作流程、文件服務和客戶體驗管理。檢視專題演講、了解 Analytics API、客戶資料層、Adobe I/O 開放原始碼專案等等。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] 與管理 {#ecloud}

未在過去一個月中更新。

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理**&#x200B;的說明資源

* [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant)和使用者管理的管理說明
* [地點 - 定位服務](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)的協助和版本注意事項
* [人員 - 客戶屬性和對象庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hant)說明

## ![圖示](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

閱讀 [最新發行說明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=zh-Hant) 為 [!DNL Adobe System Status]。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

發佈更新資訊和新文檔，用於Experience Platform和 [!UICONTROL 移動SDK]:

* 下一計畫版本： **2022年1月26日**
* 最新版本： **2021年11月17日**

請參閱 [Experience Platform發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant) 保持最新。

### 新的Experience Platform教程和課程 {#tutorials-platform}

為Experience Platform發佈的新視頻、教程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [設定 Customer AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html?lang=zh-Hant) | 影片 | 了解如何建立 Customer AI 例項，以預測客戶行為。 |
| 2022 年 1 月 | [設定 Attribution AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html?lang=zh-Hant) | 影片 | 了解如何建立 Attribution AI 例項，以明白行銷管道和行銷活動的影響。 |

{style=&quot;table-layout:auto&quot;&quot;

### Adobe Mobile SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2022 年 1 月 19 日**

* [Adobe Analytics 新功能](#aa-features)
* [Customer Journey Analytics 新功能](#cust-journey)
* [Adobe Analytics 中的修正](#aa-fixes)
* [給 Analytics 管理員的重要通知](#aa-notices)
* [Analytics 課程與教學課程](#tutorials-analytics)
* [AppMeasurement](#appm)

### Adobe Analytics 新功能 {#aa-features}

| 功能 | 說明 | 目標日期 |
| ----------- | ---------- | ------- |
| 不適用 |  | 請參閱 [一般可用性](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=zh-Hant) |

{style=&quot;table-layout:auto&quot;&quot;

### Customer Journey Analytics 新功能 {#cust-journey}

| 功能 | 說明 | 目標日期 |
| ----------- | ---------- | ----- |
| [!UICONTROL 持久性] 綁定維和綁定度量的選項 | 建立或編輯資料視圖時，可以將維的持久性綁定到其他維或度量。 這個概念被稱為 _促銷_ 在報告和分析中，現在在CJA中受支援。 [進一步了解](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#binding-dimension) | 2022 年 1 月 19 日 |
| [!UICONTROL 第一個已知] 和 [!UICONTROL 上次已知] 分配模型 | 這兩個新分配模型為指定持久性範圍（會話、人員或具有回溯的自定義時間段）內的維獲取第一個或最後一個觀察值。 然後，他們將分配模型應用於指定範圍內的所有事件。 [進一步了解](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#allocation-settings) | 2022 年 1 月 19 日 |
| [!UICONTROL 人員ID] 和 [!UICONTROL PersonID命名空間] 作為維 | 公開 `personID` 或 `customerID`，或用於合併連接中的資料集的任何ID)作為資料視圖中的維。 此增強功能使您更容易包括 `personID` 從連接中拉入，作為資料視圖中的維。 [進一步了解](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-reference.html?lang=en#optional-standard-components) | 2022 年 1 月 19 日 |

{style=&quot;table-layout:auto&quot;&quot;

請參閱 [一般可用性](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=zh-Hant) 的雙曲餘切值。

### 在Adobe Analytics和Customer Journey Analytics {#aa-fixes}

* 已修復維項中缺少受眾ID的Analysis Workspace問題。 (AN-262038；AN-279315)
* 已修復阻止用戶載入已保存的問題 [!DNL Target] 在Workspace中建立項目。 (AN-277461;AN-275825;AN-266397)
* 修復了未啟用功能在UI中可見的問題。 (AN-262006)
* 使用Workspace中的日期欄位修復更改日期時發生的問題。 這導致 [!UICONTROL 結束時間] 從晚上11點59分改為12點00分。 (AN-277269；AN-277481)
* 已修復在已載入段中添加新段時導致段UI中斷的問題。 (AN-260827)
* 已修正用戶無法存取共用 Workspace 專案的問題。 (AN-267529)
* 添加一條錯誤消息，顯示滾動日期範圍的開始日期晚於結束日期的時間。 (AN-270488)
* 已修復各種資料饋送問題。 (AN-275876;AN-270512;AN-277284;AN-277290;AN-274893;AN-274606;AN-269651)
* 修復了圖表中日期範圍忽略表中日期篩選器的問題。 (AN-263999)
* 已解決由於夏令時而提前發送計畫報告的問題。 (AN-276410；AN-276305)
* 已修復項目下載到的問題 `.csv` 檔案在Workspace中失敗。 (AN-275834)

#### Adobe Analytics和CJA中的其他修復

AN-253294;AN-254976;AN-255377;AN-255561;AN-258550;AN-259336;AN-263935;AN-265094;AN-269441;AN-269486;AN-269855;AN-271166;AN-271588;AN-272088;AN-272249;AN-272859;AN-272873;AN-272885;AN-273229;AN-273913;AN-274237;AN-274472;AN-274491;AN-274619;AN-274766;AN-275248;AN-275259;AN-275271;AN-275315;AN-275388;AN-275418;AN-275597;AN-275643;AN-275650;AN-275651;AN-275675;AN-275682;AN-275704;AN-275711;AN-275796;AN-275834;AN-275923;AN-275941;AN-276044;AN-276125;AN-276157;AN-276397;AN-276597;AN-276789;AN-276834;AN-276861;AN-276870;AN-276963;AN-276975;AN-277000;AN-277044;AN-277093;AN-277200;AN-277215;AN-277271;AN-277281;AN-277362;AN-277419;AN-277492;AN-277498;AN-277533;AN-277619;AN-277675;AN-277681;AN-277767;AN-277805;AN-277810;AN-277818;AN-277875;AN-277933;AN-277988;AN-278105;AN-278115;AN-278122;AN-278192;AN-278407;AN-278437;AN-278559;AN-278604;AN-278610;AN-278709;AN-278835;AN-278849;AN-278881;AN-279067;AN-279103;AN-279111;AN-279219;AN-279237;AN-279312

### 給 [!DNL Analytics] 管理員的重要通知 {#aa-notices}

| 注意 | 新增或更新日期 | 說明 |
| ----------- | ---------- | ---------- |
| 舊式分析OAuth/JWT整合的允許清單EOL擴展過期 | 2022 年 1 月 14 日 | 開 **2022年5月25日**，也請參見Wiki頁。 [分析1.3 API、1.4 SOAP API和Legacy Analytics OAuth/JWT EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md) allowlist擴展將過期。 它旨在為使用傳統產品的客戶提供 [!DNL Adobe Analytics] OAuth/JWT憑據將其客戶端整合遷移到 [Adobe IMS憑據](https://developer.adobe.com/console)。 此到期影響（但不限於） [!DNL Adobe Analytics Livestream] 和 [!DNL Adobe Campaign] 尚未完成其所需IMS遷移的客戶。 當前使用舊式服務的客戶 [!DNL Analytics] 通過允許清單擴展的OAuth/JWT憑據以及在2022年5月25日之前未完成到IMS憑據的遷移的憑據將無法訪問Adobe服務。 LiveStream客戶可以參考以下 [說明](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/live-stream-api/getting_started.md) 將其客戶端應用程式遷移到IMS憑據。 [!DNL Campaign] 客戶可以聯繫其Adobe客戶團隊，瞭解升級到 [!DNL Campaign]。 |
| Reports &amp; Analytics 生命週期結束 | 2022 年 1 月 4 日 | 自 **2023 年 12 月 31 日**&#x200B;起生效，Adobe 計畫停止支援 Reports &amp; Analytics 及其隨附的報告和功能。支援Reports &amp; Analytics的報告、可視化和底層技術不再滿足Adobe的技術標準。 大多數報告和分析功能都可在 [Analysis Workspace](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/home.html)。 自 Analysis Workspace 在 2015 年發佈以來，Reports &amp; Analytics 功能已移至 Analysis Workspace 並已達到工作流程同位臨界值。[本通知](https://spark.adobe.com/page/6WnF8JK6IRDhf/)說明生命週期結束程序。 |
| 安全檔案傳輸協定(SFTP)服務升級 | 2022 年 1 月 13 日 | 開 **2022年5月2日**。 [!DNL Adobe Analytics] 將升級其安全檔案傳輸協定(SFTP)服務，以提高檔案傳輸的安全性。 通過此更改，將不再支援某些SFTP客戶端配置。 我們還將添加一些連接選項， **2022年3月1日**。 這只會影響使用SFTP發送到Adobe Analytics或從其檢索到的資料。 FTP協定將不受影響。 為避免服務中斷，請確保您的SFTP客戶端（代碼、工具、服務）將符合詳細更改 [這裡](https://experienceleague.adobe.com/docs/analytics/export/ftp-and-sftp/secure-file-transfer-protocol/sftp-upgrade.html)。 |
| _全球+中國_ RDC類型 | 2021 年 11 月 22 日 | _全球+中國_ 是一種新的區域資料收集(RDC)類型，它使用 [!UICONTROL 中國效能優化附加包]。 在過去，您必須決定資料應該路由至中國收集端點或其中一個全球收集端點。現在您可以選擇這個 RDC *類型*，讓 Adobe 根據用戶的地理位置來決定最佳收集端點。 |
| 資料來源中完整處理的生命週期結束 | 2021 年 10 月 18 日 | 在 **2022 年 1 月 31 日**，Adobe 將終止完整處理的服務。此服務可讓用戶將離線點擊資料擷取至 Analytics。此功能透過 [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) 提供。[了解更多](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html?lang=zh-Hant?lang=zh-Hant) |

{style=&quot;table-layout:auto&quot;&quot;

### AppMeasurement {#appm}

如需 AppMeasurement 版本 (版本 2.22.4) 最新的更新，請參閱 [AppMeasurement for JavaScript 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)。

### 新建分析教程和課程 {#tutorials-analytics}

為Adobe Analytics發佈的新視頻、教程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [適用於商務使用者的分析基礎已淘汰](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/retire-fundamentals-for-business-users-course.html) | 影片 | 瞭解原始課程為什麼已退學，以及Adobe建議的新替代課程。 |
| 2022 年 1 月 | [媒體播放時間面板](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/media-analytics/measuring-media-analytics/media-playback-time-spent-panel.html?lang=en) | 影片 | 瞭解媒體播放花費時間面板如何使媒體用戶能夠根據在一天中按選定粒度查看的時間量來瞭解他們的收視率。 |
| 2022 年 1 月 | [Adobe Analytics客戶細分策略與最佳實踐](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/customer-segmentation-strategies.html?lang=en) | 影片 | 與分析內部人員一起參加週四的分析會議，重點討論客戶細分基礎知識、戰略和最佳實踐。 |
| 2022 年 1 月 | [設定付費搜尋偵測](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-paid-search-detection.html#) | 影片 | 瞭解如何瀏覽Adobe AnalyticsAdmin Console付費搜索檢測部分的配置，包括一些建議。 |
| 2022 年 1 月 | [配置清單變數](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=en) | 影片 | 瞭解如何配置和使用清單變數的Adobe Analytics。 清單變數使您能夠將多個值放入eVar。 |
| 2022 年 1 月 | [配置流量變數(props)](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-traffic-variables-props.html?lang=en) | 影片 | 瞭解流量變數的配置，也稱為 _道_，在分析Admin Console中。 |
| 2022 年 1 月 | [使用處理規則處理傳入資料](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=en) | 影片 | 瞭解在Adobe Analytics處理規則以及您可以使用它們的內容。 獲取有關使用「處理規則」的一些提示、示例，甚至警告。 |
| 2022 年 1 月 | [在 Analysis Workspace 中將區段用作維度](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/using-segments-as-dimensions-in-analysis-workspace.html?lang=zh-Hant) | 已更新視頻 | 瞭解如何通過將段用作Analysis Workspace的維來比較和可視化它們。 |
| 2022 年 1 月 | [分部管理與分享在Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-management-and-sharing.html?lang=en) | 已更新視頻 | 在此更新的視頻中，瞭解共用和管理段的一些提示。 |
| 2022 年 1 月 | [在 Analysis Workspace 中使用區段來限制資料](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/using-segments-to-limit-data-in-analysis-workspace.html?lang=en) | 已更新視頻 | 瞭解如何將Analysis Workspace項目的用戶限制在使用該工具時的特定段（或段）。 |
| 2022 年 1 月 | [Analysis Workspace 中的區段比較](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-comparison-in-analysis-workspace.html?lang=en) | 已更新視頻 | 瞭解Segment IQ(Adobe AnalyticsAnalysis Workspace州的一部分)如何通過檢查所有維度和指標的任何兩個分析段來自動發現它們在統計上最顯著的差異，從而簡化分析。 |

{style=&quot;table-layout:auto&quot;&quot;

### Analytics 說明資源

* [Adobe Analytics 產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修正與改良。

* 已解決在透過 Swagger 介面執行時導致所有 API 呼叫傳回 `Undocumented` 錯誤的問題。(AAM-59190)
* 已解決在某些情況下導致指派錯誤的用戶角色給合作夥伴的問題。(AAM-59451)
* 已解決導致 API 要求區分大小寫驗證標題的問題。(AAM-58528)

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以掌握最新的版本資訊。

### Experience Manager 產品發行

* **Experience Manager as a Cloud Service**

   觀看 [2021年12月發佈概述視頻](https://video.tv.adobe.com/v/339278) 2021.11.0（2021年11月）版中添加的功能摘要。

   * [](https://video.tv.adobe.com/v/338253)2021 年 10 月版本總覽 新功能影片。
   * [](https://video.tv.adobe.com/v/337381)2021 年 9 月版本總覽 新功能影片。

   * **Experience Manager Assets as a Cloud Service**

      _新功能_

      * Dynamic Media [!UICONTROL 影像智慧裁剪] 和 [!UICONTROL 斯沃琪] 現在由Sensei最新服務提供支援，該服務生產改良的作物和色板。 此外，已啟動增強以針對相同縱橫比但跨不同解析度產生不同的作物內容。 此外，如果「影像配置檔案」中的寬度和高度沒有變化，則在重新處理時將保留任何手動編輯。

      _Experience Manager Assets預發行渠道的新功能_

      * Dynamic Media — 您現在可以使用Experience ManagerDynamic Media介面配置 [!UICONTROL 常規設定] 和 [!UICONTROL 發佈設定] 而不必去Dynamic Media Classic案頭應用程式。
      * Dynamic Media現在支援MXF視頻的攝取、預覽、播放和發佈。 尚不支援MXF視頻的注釋和可購物視頻。
      * 在配置遠程DAM和站點部署之間的連接後，遠程DAM上的資產可在站點部署中使用。 您現在可以執行 [更新、刪除、更名和移動操作](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=en) 遠程DAM資產或資料夾。 這些更新在站點部署中自動可用，但有一些延遲。
   * **Experience Manager Forms as a Cloud Service**

      _新功能_

      * **外部化Experience Manager工作流資料以進行安全處理**:您可以儲存進程中Experience Manager工作流資料(Experience Manager [!UICONTROL 工作流變數] 資料)，該資料包含客戶管理的儲存庫中的SPD（敏感個人資料）元素，以進行安全處理。 資料元素和工作流變數不儲存在Experience Manager儲存庫中，在處理工作流時會根據需要從客戶管理的儲存庫中獲取。

      _Experience Manager Forms預發行渠道的新功能_

      * **AEM Formsas a Cloud Service — 通信**: [通信API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=en) 幫助您將模板和XML資料組合起來，以生成各種格式的打印文檔。 使用該服務，您可以以同步和批處理模式生成文檔。 API允許您建立應用程式以執行以下操作：
         * 使用 XML 資料填寫範本檔案 (PDF 和 XDP) 來產生文件。
         * 產生多種格式的輸出表單，包括非互動式 PDF 列印資料流。
      * **記錄文檔的自定義字型和使用Communications API建立的PDF文檔**:現在，您可以在使用Communications API生成的PDF文檔中使用品牌批准的字型，以符合您的組織要求。
      * **Forms門戶**:您可以使用 [Forms門戶](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/configure-forms-portal.html?lang=en) 列出已發佈的自適應表單。 它可幫助站點訪問者發現所有可用表格。 此外，參觀者可使用 [!UICONTROL Forms門戶] 以保存和訪問自適應表單的草稿，並查看已提交自適應表單的PDF版本。
   * **Cloud Manager**

      _新功能_

      * 用戶現在可以使用新的前端管道以加速的方式專門部署前端代碼。 請參閱 [Cloud Manager前端管道](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#front-end) 來瞭解更多資訊。

         >[!IMPORTANT]
         >
         >您必須處於Experience Manager版本 `2021.10.5933.20211012T154732Z` 或更高版本使用新 [!UICONTROL 前端管線]。

      * 通過以更有效的方式執行代碼分析而減少代碼質量流水線持續時間，而不需要構建整個Experience Manager影像。 此更改在發佈後的未來幾週內逐步展開。
      * Git提交ID現在顯示在管道運行詳細資訊中，使跟蹤生成的代碼更容易。
      * [!UICONTROL 程式建立] 現在可以通過公開的API獲得。
      * [!UICONTROL 環境建立] 現在可通過公開的API獲得。
      * 的 `x-request-id` 響應標頭現在可在上的API Ploagn中看到 [www.adobe.io](https://www.adobe.io/)。 此標題在提交客戶關心問題以進行故障排除時非常有用。
      * 新 [!UICONTROL 活動] 頁面可用，其中可以查看管道和代碼運行等活動及其關聯的詳細資訊。 隨著時間的推移，此頁中列出的活動在範圍內擴展，並提供詳細資訊。
      * 新 [!UICONTROL 管線] 現在可以使用「狀態跨距」(status popover)來輕鬆查看詳細資訊摘要。 您可以查看 [!UICONTROL 管線] 與相關詳細資訊一起運行。
      * 的 [!UICONTROL 編輯管線] API現在支援更改部署階段中使用的環境。
      * 在 [!DNL OakPal] 掃描過程現在可用於大型包。
      * 質量問題CSV檔案現在包含每個質量問題的時間戳。





### 社群

* **Experience ManagerGEM網路研討會 — Experience Manageras a Cloud Service** | 2021年回顧和2022年展望

   **日期**:2022年1月25日星期二
   **時間**:上午8點太平洋標準時間下午5點CET或9:30IST
   **持續時間**:60分鐘
   **成本**:自由！

   * [按一下這裡報名](https://adobe.ly/3tAh3OC)
   * [提問](https://adobe.ly/3zJrS0f)

* [宣佈2021年社區成員](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/announcing-community-members-of-the-year-2021/td-p/436782)

   我們要向所有參與的人致以衷心的感謝 [Experience Manager社區](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community) 2021年，他們幫助了其他人解決自己的問題。

   每年，Experience Cloud社區都向那些在服務上超越和超越其他領域的成員授予&quot;社區年度成員&quot;獎，為其他成員提供令人難以置信的支援。 我們在此宣佈，我們承認以公開方式作出的努力 [@Asutosh_Jena_](https://experienceleaguecommunities.adobe.com/t5/user/viewprofilepage/user-id/7532759)  和 [@Vijayalakshmi_S](https://experienceleaguecommunities.adobe.com/t5/user/viewprofilepage/user-id/11077056) 成為2021年共同體成員。

* [Experience League2022年1月內容](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/experience-league-content-for-month-of-january-2022/td-p/437137)

   [在Experience League中發佈的所有Experience Manager內容的清單](https://adobe.ly/3tuGuRH)

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | ----- |
| 2022 年 1 月 | [使用Adobe開發人員應用程式生成器擴展Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/configuring-and-extending/app-builder/extending-aem-with-app-builder.html?lang=en) | 視頻（多個） | 新的Adobe開發人員應用程式構建器為開發人員提供了一個擴展框架，以便輕鬆擴展AEMas a Cloud Service功能。 | AEM as a Cloud Service |
| 2022 年 1 月 | [AEM無頭快速設定AEMas a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/quick-setup/cloud-service.html) | 影片 | 看看無頭AEM快速設定。 它使用WKND站點示例項目中的內容AEM，讓您能夠與Headless進行操作，並提供一個示例React App(aSPA)，該示例React App消耗了AEMHeadless GraphQL API中的內容。 | AEMas a Cloud Service |
| 2022 年 1 月 | [高級網路](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/advanced-networking.html?lang=en) | 視頻（多個） | 瞭解AEMas a Cloud Service如何提供三種選項來管理與外部服務的連接：靈活的埠出口、專用出口IP地址和虛擬專用網路。 as a Cloud Service中的Cloud Manager程式和環AEM境一次只能使用一種類型的高級網路配置。 | AEMas a Cloud Service |
| 2022 年 1 月 | [利用關聯內容豐富產AEM品資料](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/enrich-product-associated-content.html?lang=en) | 影片 | 瞭解營銷人員如何利用Adobe Experience Manager的相關內容豐富產品資料。 內容，比如資產， [!UICONTROL 體驗片段], [!UICONTROL 內容片段] 可AEM以與商業產品關聯。 | AEMas a Cloud Service |
| 2022 年 1 月 | [電子郵件服務](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/examples/email-service.html?lang=en) | 影片 | 通過配置從AEMas a Cloud Service發送電子郵AEM件 `DefaultMailService` 使用高級網路出口端。 | AEMas a Cloud Service |
| 2022 年 1 月 | [Workfront增強連接器基礎](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=en) | 影片 | 瞭解Adobe Workfront和Experience Manager Assets增強連接器的基本知識。 另請瞭解 [項目資料夾](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/project-folders.html?lang=en)。 | AEM Assets和Workfront |
| 2022 年 1 月 | [AEM Sites入門 — 快速站點建立](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html?lang=en) | 視頻（多個） | 瞭解如何使用低代碼方法在Adobe Experience Manager通過快速站點建立和預定義的站點模板建立您的第一個站點。 | AEM Sites |
| 2022 年 1 月 | [非標準埠上的HTTP/HTTPS連接，用於靈活的埠輸出](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/examples/http-on-non-standard-ports-flexible-port-egress.html?lang=en) | 視頻（多個） | 瞭解非標準埠（而非80/443）上的HTTP/HTTPS連接如何必須代理出AEMas a Cloud Service。 | AEMas a Cloud Service |
| 2022 年 1 月 | [添加表徵圖以指示活動和已完成的頁籤](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/ui-tips-and-tricks/active-complete.html?lang=en) | 影片 | 瞭解如何顯示表徵圖以指示在具有帶左頁籤導航的自適應窗體時頁籤的狀態。 | AEM Forms |
| 2022 年 1 月 | [Adobe資產連結設定](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/adobe-asset-link/setup.html?lang=en) | 影片 | 通過讓創意和營銷團隊更容易在內容建立過程中就資產進行協作，為您的組織帶來快速的影響。 | AEM Assets |
| 2022 年 1 月 | [Commerce AEMas a Cloud Service入門](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/getting-started.html?lang=en) | 影片 | 瞭解營銷人員如何利用Adobe Experience Manager的相關內容豐富產品資料。 中的內容(如資產、體驗片段和內容片AEM段)可以與商業產品關聯。 | AEMas a Cloud Service |
| 2022 年 1 月 | [AEM Sites入門 — 快速站點建立](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html) | 影片 | 瞭解如何使用低代碼方法在Adobe Experience Manager通過快速站點建立和預定義的站點模板建立您的第一個站點。 | AEM Sites |
| 2022 年 1 月 | [利用關聯內容豐富產AEM品資料](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/enrich-product-associated-content.html) | 影片 | 瞭解營銷人員如何利用Adobe Experience Manager的相關內容豐富產品資料。 中的內容(如資產、體驗片段和內容片AEM段)可以與商業產品關聯。 | AEMas a Cloud Service |

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

## 適用於 Adobe Experience Manager 的 XML 文件 {#xml-doc}

Adobe Experience Manager的XML文檔是部署到的應AEM用程式。 它是一個功能強大、企業級元件內容管理解決方案(CCMS)，它支援Adobe Experience Manager的本機DITA支援，AEM能夠處理基於DITA的內容建立和交付。 瞭解有關 [XML文檔AEM](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html)。

### XML文檔的新教程(Adobe Experience Manager) {#tutorials-xml-doc}

為Adobe Experience Manager的XML文檔發佈的新視頻、教程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [XML文檔版本](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=en) | 影片 | 瞭解Adobe Experience Manager的XML文檔，這是一個功能強大、企業級元件內容管理解決方案(CCMS)。 它支援Adobe Experience Manager的本機DITA支援，AEM能夠處理基於DITA的內容建立和交付。 |
| 2022 年 1 月 | [使用XML文檔生成輸AEM出](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=en) | 視頻和文章 | 瞭解「映射儀表板」、報告、使用基線和條件發佈等。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 教學課程 {#tutorials-commerce}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [Business Intelligence](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/getting-started/business-intelligence/1-overview.html) | 視頻（多個） | 從概述開始，瞭解Business Intelligence的全部資訊，這是一個針對所有Adobe Commerce和Magento Open Source商都進行了優化的完整解決方案。 |
| 2022 年 1 月 | [用戶、角色和權限](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/users-roles-permissions.html) | 影片 | 瞭解如何為每個用戶建立單獨的用戶帳戶並根據其業務需求分配受限訪問權限。 |
| 2022 年 1 月 | [雙因素身份驗證](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/two-factor-authentication.html) | 影片 | 瞭解二元身份驗證(2FA)如何防止未經授權訪問您的資料。 Adobe Commerce和Magento Open Source支援來自多個提供商的雙因素認證方法。 |
| 2022 年 1 月 | [添加網站、商店和商店視圖](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/add-websites-stores-views.html) | 影片 | 瞭解每個Adobe Commerce和Magento Open Source安裝如何支援網站、商店和商店視圖的層次結構。 根據業務需要構建和擴展此層次結構。 |
| 2022 年 1 月 | [更改儲存URL](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/change-store-url.html) | 影片 | 瞭解如何更改商店的基本URL。 (視頻內容反映2.1.0版。) |
| 2022 年 1 月 | [設定商店站點映射](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/site-map-setup.html) | 影片 | 瞭解如何輕鬆將站點地圖添加到您的Commerce商店。 |
| 2022 年 1 月 | [促銷價格規則](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/promotions-price-rules.html) | 影片 | 瞭解如何設定產品關係並使用價格規則根據各種條件觸發折扣。 |
| 2022 年 1 月 | [建立頁面](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/frontend-development/create-new-page.html) | 影片 | 瞭解如何使用一個參數建立返回JSON的頁。 |
| 2022 年 1 月 | [添加JavaScript模組](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/frontend-development/add-javascript-module.html) | 影片 | 瞭解如何開發提供問候語「Hello World」的簡單JS模組。 |
| 2022 年 1 月 | [頁面生成器概述](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/page-builder-overview.html) | 影片 | 瞭解頁面生成器如何使用自定義佈局輕鬆建立內容豐富的頁面，從而增強您的視覺敘事能力，並推動客戶參與和忠誠度。 |
| 2022 年 1 月 | [向資料庫添加表](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/add-new-db-table.html?lang=en) | 影片 | 瞭解Commerce中的特殊機制，該機制使您能夠建立資料庫表、修改現有的表，並將資料添加到它們中，如安裝資料，安裝模組時必須添加這些資料。 |
| 2022 年 1 月 | [建立模組](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/create-module.html) | 影片 | 模組是Commerce的一個結構元素，整個系統都建立在模組之上。 通常，建立自定義項的第一步是構建模組。 |
| 2022 年 1 月 | [建立產品屬性](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/add-product-attribute.html) | 影片 | 瞭解如何添加產品屬性，這是Commerce中最常用的操作之一。 屬性是解決與產品相關的許多實際任務的有力方法。 |
| 2022 年 1 月 | [依賴關係注入示例](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/backend-development/dependency-injection.html) | 影片 | 瞭解相關性注入，該設計模式允許對象A向提供這些相關性的外部對象B聲明其相關性。 A聲明的依賴項通常是類介面，而B提供的依賴項是這些介面的具體實現。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

最近更新日期：**2022 年 1 月 10 日**

請參閱 [目標發行說明](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant) 的子菜單。

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品發行版

進一步了解已發行的最新功能、改良與修正：

* [市場活動v7.2版](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)

### 新建 [!DNL Campaign] 教程和課程 {#tutorials-campaign}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 | 版本 |
| ------| ----- | -----| ------ | --- |
| 2022 年 1 月 | [部署隨選電子郵件傳遞範本](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/deploy-ad-hoc-email-delivery-template.html?lang=en) | 影片 | 瞭解如何部署即席電子郵件傳遞模板，並說明電子郵件傳遞和傳遞工作流之間的區別。 | Campaign v8 |
| 2022 年 1 月 | [設定傳遞範本屬性](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/set-delivery-template-properties.html?lang=en) | 影片 | 瞭解如何設定傳遞範本屬性，並詳細說明每個屬性。 | 市場活動v8 |
| 2022 年 1 月 | [設定行銷活動的核准 ](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.html?lang=en) | 影片 | 瞭解如何在行銷活動層級設定核准和審核者。 | 市場活動v8 |
| 2022 年 1 月 | [在工作流程中建立核准流程](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.html?lang=en) | 影片 | 瞭解如何在工作流程中建立核准流程，以在啟動傳遞前，允許審核和核准目標定位選擇邏輯。 | 市場活動v8 |
| 2022 年 1 月 | [設定用於傳遞的核准 ](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.html?lang=en) | 影片 | 瞭解如何在傳遞層級設定核准和審核者。 | 市場活動v8 |
| 2022 年 1 月 | [帶FFDA的API分級機制](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/api-staging-mechanism.html?lang=en) | 影片 | 瞭解API轉移機制與完整FDA的工作原理。 瞭解使用轉移的原因、在Adobe Campaign轉移的主要原則以及如何激活自定義表的轉移機制。 | 市場活動v8 |

{style=&quot;table-layout:auto&quot;&quot;

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [發行說明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=zh-Hant) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant) - [做法影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 做法影片

## ![表徵圖](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

有了 Journey Optimizer，您就可以從單一應用程式為幾百萬名客戶管理排程的全通道行銷活動及一對一時刻，還有智慧型決策和見解讓整個旅程最佳化。

### 最新 Journey Optimizer 產品發行版

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hant)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hant)

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
* [新建 [!DNL Advertising Cloud] 教程](#tutorials-ad-cloud)

### [!DNL Advertising Cloud] 的新功能 {#adcloud-all}

最新更新：**2021 年 10 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| Analytics for Advertising Cloud | 如果您的組織想從舊式Adobe Analytics `visitorAPI.js` 圖書館到Adobe Experience Platform圖書館(`alloy.js`)，必須進行一些更改才能啟用ID拼接。 請參閱 [使用 [!DNL Last Event Service] 帶有Adobe Experience Platform的JavaScript庫 [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=zh-Hant)。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Advertising Cloud DSP] 中的新功能 {#adcloud-dsp}

最新更新：**2021 年 10 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| 自訂報告 | 您現在可以為自訂報告建立和管理 [!DNL Amazon S3] 和不同類型的 FTP 傳送位置，稱為 *[!DNL report destinations]*。設定報告目標後，您可以將每個新的自訂報告設為傳送到單一目標類型的一個或多個位置，或傳送到電子郵件收件者。更新您的 [!DNL Amazon S3]，則 FTP 認證將不會中斷報告傳遞。<br><br>您現有的報告仍會傳送到指定的電子郵件收件者。要配置到其他報告目標的傳遞，請使用新目標建立報告。 |
| [!UICONTROL 套件]，[!UICONTROL 位置]，和 [!UICONTROL 廣告]檢視 | 當您查看某一天的資料時，趨勢圖表將包括每小時資料。將游標放在任意點上可查看該小時的資料。 |
| [!UICONTROL 位置] | 位置[!UICONTROL 檢查]現在包含[!UICONTROL 詳細目錄]標籤，顯示位置的所有交易及其相關指標。使用這些資訊進行快速調整或疑難排解問題，而無需產生自訂報告。 |
| [!UICONTROL 廣告] | (有權在其廣告中包含 Clearcastclock 數字的用戶) 如果您使用附加到其他廣告的時鐘數字，DSP 將不再顯示錯誤。**請注意：**&#x200B;最佳實務是為每個廣告影片使用唯一的時鐘數字。否則，發佈者不會批准所有廣告。 |
| [!UICONTROL 交易識別碼] | [!UICONTROL 交易識別碼]設定和用戶界面中的其他地方反映了 [!DNL Magnite]SSP<br> 的新品牌：<ul><li>SSP [!DNL Tremor] ([!DNL Telaria]) [!DNL Magnite CTV]。</li><li>在接下來的幾週裡， [!DNL Rubicon] 將更改 [!DNL Magnite DV+]，也請參見Wiki頁。 [!DNL DV+] 表示顯示、視頻和其他格式，如音頻。</li></ul> |
| [!DNL Freewheel] 以寫程式方式擔保的交易 | 您現在可以找到 [!DNL Freewheel] 以寫程式方式擔保的交易 [!UICONTROL 廣告] 的子菜單。 以前您只能從[!UICONTROL 交易]檢視中查看狀態。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

最新更新：**2021 年 10 月 7 日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 報告]、[!UICONTROL 通知中心] | (10 月 9 日發行) 報告的所有電子郵件通知目前都由[!UICONTROL 通知中心]處理。這些通知是 Advertising Cloud Search 在自訂或排程報告完成或失敗時傳送。報告預設為啟用電子郵件通知與 Web 通知預設，但您可以選擇變更通知設定。進行此變更：<ul><li>電子郵件收件者限為已註冊的用戶、已驗證身分的 Advertising Cloud Search 用戶，以及存取廣告商帳戶的用戶。此功能可確保不會將機密資訊傳送給未經授權的用戶。</li><li>電子郵件的格式與內容使用[!UICONTROL 通知中心]範本，其中包括報告的詳細資訊與所有報告格式的直接下載連結。</li><li>報告通知是[!UICONTROL 通知中心]中新的通知類型，有自己的通知偏好設定。</li></ul>如果您有任何從電子郵件通知提取報告的自動化作業，您可能需要更新篩選邏輯，以確保程序不中斷。 |
| 廣告分析 | Beta 版模式提供其他深入分析。 |

{style=&quot;table-layout:auto&quot;&quot;

### 新Advertising Cloud教程 {#tutorials-ad-cloud}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [Advertising Cloud 教學課程](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=en) | 影片 | 有五個關於Advertising Cloud DSP的新視頻教程。 |

## ![表徵圖](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

針對 Adobe Document Cloud 發佈的新影片、教學課程或其他課程。

### 新Document Cloud課程和教程 {#tutorials-doc-cloud}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 1 月 | [增強PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/enhance.html?lang=en) | 影片 | 在本操作教程中，瞭解如何通過添加圖形增強和自動編號來轉換PDF。 |
| 2022 年 1 月 | [更明智地與Acrobat DC和Microsoft® 365合作](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.microsoft365) | 課程 | 在內部發現功能強大的PDF工具 [!DNL Microsoft® 365] 和 [!DNL Acrobat DC] 替換過時的中斷文檔工作流。 瞭解如何自動執行手動文檔流程以避免延遲和錯誤、提高安全性和生產效率，以及提供卓越的客戶和員工體驗 — 所有這些都在您已使用的Microsoft®和Acrobat工具中。 |

{style=&quot;table-layout:auto&quot;&quot;

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![表徵圖](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

如需了解最新教學課程，請參閱「[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hant)」。
