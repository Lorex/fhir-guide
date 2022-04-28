---
tags: tutorials, FHIR, 中文, 教學
---
# FHIR 教育訓練相關資源

[![HL7 FHIR v4.0.1](https://img.shields.io/badge/HL7%20FHIR-v4.0.1-blue)](http://hl7.org/fhir/)
[![License: WTFPL](https://img.shields.io/badge/License-WTFPL-brightgreen.svg)](http://www.wtfpl.net/about/)
[![GitHub issues](https://img.shields.io/github/issues/Lorex/fhir-guide)](https://github.com/Lorex/fhir-guide/issues)
[![hackmd-github-sync-badge](https://hackmd.io/r08gAIefT-yvwJj38llfbA/badge)](https://hackmd.io/r08gAIefT-yvwJj38llfbA)

![](https://i.imgur.com/1JPWsWE.png)

## 目錄
[TOC]

## 說明
### 註冊商標聲明
因應國際健康資訊交換第七層協定協會（HL7® International）之規定，本文件提及的「FHIR®」、「FHIR 標準」、「帶有火焰標示的 HL7 FHIR Logo」是 HL7 的註冊商標，並經由 HL7 許可授權使用。

### 文件授權條款
本文件為 FHIR 教育訓練的相關資源收錄，並以 **[你他媽的想幹嘛就幹嘛公共授權條款 (WTFPL)](http://www.wtfpl.net/about/)** 發布。惟本文件所連結或參考之各項文獻／圖片／影音素材，其著作權、智慧財產權與授權方式仍依該引用資料本身之規定為準。

本文件使用 HackMD 製作，並依開放原始碼精神將完整內容上傳至 GitHub，歡迎讀者自由提交 Commit 豐富本文內容。

[點我檢視 GitHub Repository](https://github.com/Lorex/fhir-guide)

### 如何閱讀本文件
FHIR 的官方網站涵蓋了大量且完整的資料，考量到許多不熟悉 FHIR 的新手若直接看官方網站的話可能會望之卻步。為了讓還在新手村的學員們能快速對這個標準上手，因此製作了這份文件。您可以在這份文件中，用（筆者認為）比較有系統性的方式對 FHIR 進行學習。這份文件收錄了筆者從以前到現在發布的各項教材／演講資料以及相關資源／參考連結，由幾個部分組成：

+ **參考資料**
  + **簡報**
    收錄筆者從 2017 年至今所有的演講簡報，目前最新的簡報是「FHIR 從入門到放棄」系列，對應到最新的 R4 版本，新手可以直接讀這份簡報搭配下面文件／範例程式／情境演練題目進行練習。
  + **介紹／教學文章**
    收錄網路上對 FHIR 的介紹及教學文章，及筆者發布的各式教學文件。
  + **標準文件**
    收錄與 FHIR 有關的各種標準文件、實作指引（Implementation Guide）及 Profile，由於此部分是描述標準規範文件，因此讀起來可能會比較無聊，請您忍一下XD
+ **操作與應用**
  + **測試伺服器列表**
    這裡收錄常見的 FHIR 測試伺服器列表，您可以使用這些伺服器作為練習用途。但由於這些 FHIR 伺服器的資料是公開且會不定時清除，您==不應==把它應用在開發／正式環境中。
  + **Toolchain／工具鏈**
    這裡列出在學習 FHIR 過程中可能會使用到的工具，您可以視需求進行安裝，或是使用您慣用的工具。
  + **範例程式**
    這裡列出與 FHIR 開發相關的教育訓練相關的範例程式，您可以參考這些程式進行開發。
+ **情境演練（題目與參考解答）**
  收錄筆者設計的幾個情境演練題目，並在部分題目收錄解答，您可以利用這些題目來進行練習。
+ **開源專案**
  這裡列出目前正進行中的 FHIR 開放原始碼專案，您可以利用這些專案進行 FHIR 練習，如果您已經對 FHIR 有一定程度的了解，也歡迎提交 Commit，為 FHIR 的生態做出一份貢獻💖
+ **封存資料**
  存放已經失效、版本過舊或是需要被封存的資料，以避免造成讀者在學習 FHIR 的過程中被不同時期的新舊資料造成混淆。
  
:::warning
**注意**

FHIR 是一個仍在不斷發展中的標準，不同時期的的資料可能會因為 FHIR 的標準發展、文件更新而可能有不適用的狀況，筆者會盡量更新這份文件，以維持其準確性。然而仍有可能有疏漏的地方，所有對於 FHIR 標準的規範與解釋，請以 FHIR 官方網站為準。

若您發現本文件有任何有誤的地方，請 Email 至 **Lorex\<ceo@sita.tech>**，或是直接在 [GitHub](https://github.com/Lorex/fhir-guide) 中提交 Issue，我會立即修正有誤的資料。
:::

# 參考資料
## 簡報
### 「FHIR 從入門到放棄」系列（R4 版本／真．新手村）
+ 【FHIR 從入門到放棄】簡報 Session 1: FHIR 簡介
  https://www.slideshare.net/secret/9gTLCKnZWV7oqH
+ 【FHIR 從入門到放棄】簡報 Session 2: 文件導讀 
  https://www.slideshare.net/secret/r6onSiAvjqHkNo
  
### R4 版本參考資料
+ 【給有開發經驗看的】北護大／FHIR 開發簡介與應用
    https://www.slideshare.net/lorexyang/fhir-201782104
    
    
## 介紹／教學文章
  + iThome 專欄：FHIR三大優勢可快速複製應用，完勝前一代醫療資料交換標準
    https://www.ithome.com.tw/news/141637
  + [FHIR 從入門到放棄] Day 01－簡介
    https://ithelp.ithome.com.tw/articles/10260117
  + [FHIR 從入門到放棄] Day 02－FHIR 基本概念 
    https://ithelp.ithome.com.tw/articles/10266854
  + [FHIR 從入門到放棄] Day 03－FHIR 伺服器安裝
    https://ithelp.ithome.com.tw/articles/10281172
  + JSON 是什麼？
    https://ithelp.ithome.com.tw/articles/10159700

    
    
## 標準文件
+ FHIR 官方網站
  https://www.hl7.org/fhir/
+ FHIR Administration Module
  https://www.hl7.org/fhir/administration-module.html
+ FHIR Bundle
  https://www.hl7.org/fhir/bundle.html
+ FHIR Guide to Resource（常用的 Resource 對照表）
  https://www.hl7.org/fhir/resourceguide.html
+ JSON 規範（RFC7159文件）
  https://tools.ietf.org/html/rfc7159
+ XML 規範（RFC4825文件）
  https://tools.ietf.org/html/rfc4825
+ REST API 文件
  https://www.restapitutorial.com
+ 衛福部數位新冠病毒健康證明實作指引（TWDCC IG）
  https://dccfhirig.mohw.gov.tw/ig/ch/index.html
  
  
  
# 操作與應用
## 測試伺服器列表
+ ==臺灣公開測試伺服器（維護中）
  https://hapi.fhir.tw==
:::info
**小小工商**
本伺服器是筆者架設的臺灣公開測試伺服器，機房地點就在 ~~我大發財市~~ 高雄市，理論上連線速度應該會比較快。然而維護伺服器有成本，如果這份文件對您有幫助的話，歡迎用以下連結贊助支持 ❤https://p.ecpay.com.tw/8E309AC❤

筆者會在下次更新伺服器時，在贊助清單上放上您的芳名 m(\_ \_)m
:::
+ FHIR 官方公開伺服器
  http://hapi.fhir.org
+ Firely Server（Simplifier.net 提供）
  https://server.fire.ly/
+ 其他伺服器列表
  http://wiki.hl7.org/index.php?title=Publicly_Available_FHIR_Servers_for_testing
  
  
## Toolchain／工具鏈
+ 程式碼編輯器 **Visual Studio Code**
  https://code.visualstudio.com/
+ API 測試工具 **Postman**
  https://www.postman.com/downloads/
+ 線上免費繪圖工具 **Draw.io**
  https://app.diagrams.net/
+ Profile 編輯工具 **Forge**
  https://simplifier.net/downloads/forge


## 範例程式
+ 以 node.js 操作 FHIR Server
  https://hackmd.io/rte-MW7_SuOX1Yg5sMGXtA#%E5%AF%A6%E4%BD%9C%E5%88%9D%E8%A8%BA%E5%9F%BA%E6%9C%AC%E8%B3%87%E6%96%99%E8%A1%A8%E5%96%AE%E7%99%BB%E9%8C%84
+ 初診資料登錄表單
  https://hackmd.io/rte-MW7_SuOX1Yg5sMGXtA#%E4%BB%A5-nodejs-%E6%93%8D%E4%BD%9C-FHIR-Server
+ 病患及檢驗資料登錄表單
  https://gitlab.sita.tech/medic/fhir-training-example
  

# 情境演練
:::danger
**!!!注意!!!**
本情境演練中提到的各項案例，其未標注或明示「真實案例」者，為筆者基於出題需求自行產生之資料，其中的所有欄位皆屬虛構，如您發現有部分資料雷同，請立即透過 Email：**Lorex\<ceo@sita.tech>** 告知，或是直接在 [GitHub](https://github.com/Lorex/fhir-guide) 中提交 Issue，我將會立即修正雷同的資料。

所有標注「真實案例」的資料，其資料來源為筆者自身的病歷資料，基於教學用途，於抹除個人資料後自願提供作為出題使用。

上述提到的所有資料，無論是否為真實案例，均僅限作為學術研究與教學用途，嚴禁為任何商業或營利之應用。資料之著作權及智慧財產權仍屬筆者本身，如有違反本規定之使用情事，筆者有權視情況取消讀者對該筆資料的授權利用。
:::


## 演練 1：建立單筆 Patient Resource
本題目是為了評估您是否掌握將基本資料轉換為 Resource 的知識。

以下是某位病患的資料：
:::info
* 病人英文姓名為「Connor Graham」，中譯姓名為「葛康納」
* 這是他的照片：https://i.imgur.com/VeTQheO.png
* 護照號碼：65848725
* 聯絡電話：(宅) 07-2159685 (公) 07-7938888 (手機) 0912-354879
* 聯絡地址：高雄市橋頭區經武路 58 號 24 樓之 11
* 戶籍地址同聯絡地址
* 緊急聯絡人姓名：James Yates
* 緊急聯絡人電話：(手機) 0988-878545
* 緊急聯絡人關係：父
* 病人慣用溝通之語言為英文（en-US）
:::
請運用您學到的 FHIR 知識，使用以上資料設計 FHIR Resource。並將結果儲存為 XML 或 JSON 格式擇一。
### 參考解答
:::spoiler 點我顯示參考解答
```json=
{
  "resourceType": "Patient",
  "identifier": [
    {
      "use": "official",
      "type": {
        "coding": [
          {
            "system": "http://terminology.hl7.org/CodeSystem/v2-0203",
            "code": "PPN",
            "display": "Passport Number"
          }
        ]
      },
      "value": "65848725"
    }
  ],
  "name": [
    {
      "use": "official",
      "text": "Connor Graham",
      "family": "Graham",
      "given": [
        "Connor"
      ]
    },
    {
      "use": "official",
      "text": "葛康納"
    }
  ],
  "telecom": [
    {
      "system": "phone",
      "value": "07-2159685",
      "use": "home"
    },
    {
      "system": "phone",
      "value": "07-7938888",
      "use": "work"
    },
    {
      "system": "phone",
      "value": "0912-354879",
      "use": "mobile"
    }
  ],
  "gender": "male",
  "address": [
    {
      "use": "home",
      "type": "both",
      "text": "高雄市橋頭區經武路58號24樓之11",
      "line": [
        "經武路58號24樓之11"
      ],
      "city": "高雄市",
      "district": "橋頭區",
      "postalCode": "825006",
      "country": "TW"
    }
  ],
  "contact": [
    {
      "relationship": [
        {
          "coding": [
            {
              "system": "http://terminology.hl7.org/CodeSystem/v2-0131",
              "code": "C",
              "display": "Emergency Contact"
            }
          ],
          "text": "父"
        }
      ],
      "name": {
        "use": "official",
        "text": "James Yates"
      },
      "telecom": [
        {
          "system": "phone",
          "value": "0988-878545",
          "use": "mobile"
        }
      ]
    }
  ],
  "photo": [
    {
      "url": "https://i.imgur.com/VeTQheO.png"
    }
  ],
  "communication": [
    {
      "language": {
        "coding": [
          {
            "system": "urn:ietf:bcp:47",
            "code": "en-US"
          }
        ],
        "text": "English (US)"
      }
    }
  ]
}
```
:::








## 演練 2：上傳單筆 Patient Resource
本題目是為了評估您是否掌握以 REST API 與 FHIR Server 互動的知識。

請運用您學到的 REST API 相關知識，將您在演練 1 中完成的 FHIR 資料上傳至 FHIR Server 中。

## 演練 3：實際案例分析／判別 Resource
本題目是為了評估您是否能就實際案例進行分析，並根據原始資料判別所屬的 Resource。

以下是某位病人的出院病歷摘要單：
:::spoiler 點我展開出院病歷摘要單
![](https://i.imgur.com/rXnxysR.png)
![](https://i.imgur.com/ELnAReJ.png)
![](https://i.imgur.com/cjp7SzR.png)
:::

請運用您學到的 FHIR 知識，判斷以上資料各部描述屬於哪個 FHIR Resource，並予以標註。


## 演練 4：實際案例分析／分析各 Resource 之間的關聯
本題目是為了評估您是否能在分析實際案例並判別各部所屬的 Resource 後，進一步釐清各 Resource 之間的關聯，並繪製關聯圖以便與團隊協作。

以下是某個病人的就診資料：
:::info
患者楊O凡，男，84年08月13日生，手機 0975123456。主訴為長期無法集中注意力與情緒障礙問題，於 110/01/05 至河堤診所（醫事機構代碼 3507300711）就診，診斷醫師姓名為孫讚福。

診斷結果如下，下列診斷代碼均使用 ICD-10 作為代碼參考：
* 主診斷：F3164／雙極疾患，目前為伴有神病特徵之混合發作，重度
* 次診斷 1：K30／功能性消化不良
* 次診斷 2：M791／肌痛
* 次診斷 3：F909／注意力缺失過動疾患，未明示型

本次診斷開立以下藥物，藥品代碼均為健保代碼
* AB47553100／"瑞安"癲必停持續性藥效膜衣錠500毫克／每日 1 次、每次 1 粒、共 7 日
* AB54977100／必博寧持續性藥效錠 150 毫克／每日 1 次、每次 1 粒、共 7 日
* AC260801G0／"強生"牟靜錠3毫克（布馬平）(鋁箔/膠箔)／每日 1 次、每次 1 粒、共 7 日
* AC49423100／"鼎泰"舒寧必朗膠囊 10 毫克／每日 1 次、每次 1 粒、共 7 日
* AC59275100／瑰樂平膜衣錠25毫克／每日 1 次、每次 1 粒、共 7 日
* BC27080100／利他能錠10毫克／每日 2 次、每次 1 粒、共 7 日
:::

請運用您在課程學到的 FHIR 知識，判斷以上資料各部屬於哪個 FHIR Resource，並以 draw.io 等工具畫出關聯圖。

### 參考解答
:::spoiler 點我顯示參考解答
![](https://i.imgur.com/sMNhkR8.png)
:::


## 演練 5：實際案例分析／Bundle 批次資料上傳
本題目是為了評估您是否掌握 Bundle Resource 的使用方法，並將完整的病歷資料標準化為 FHIR Resource 後進行資料上傳的能力。

在演練 4 中，我們將原始的病歷資料進行分類，找出各部資料所屬的 FHIR Resource，並以 draw.io 等工具繪製成關聯圖。

請運用您在課程學到的 REST API 相關知識，並參考您在演練 4 中完成的關聯圖，將原始資料以 FHIR 標準化後，產生 FHIR Bundle Resource，並以 Bundle (type: transaction) 的形式上傳至 FHIR Server 中。

#### Hint
:::info
:mega: **可以將多個Resource寫在同一個檔案**
請參考[這篇FHIR Bundle](https://www.hl7.org/fhir/bundle-transaction.json.html)

> **幾個點要注意：** [name=Lorex L. Yang] [time=Sun, Jan 28, 2022 5:25 PM] [color=#aa69aa]
1. 直接 POST 到 FHIR Base URL，而不是 /bundle
2. 記得帶 "type": "transaction"
3. 之後每一個 resource 塞到 entry 內
（他會是個 JSON Object Array），resource 本體放在 entry.resource 裡面, 格式照著範例打
4. 每個 entry 裡面記得帶上
    ```json=
    "request": { "method": "PUT", "url": "<resourceType>/<id>" }
    ```
    並指定 Resource ID，可自訂，不要跟別的 record 衝到就好
:::

#### Alternatives
若您還不會使用 Bundle 進行資料上傳，也可以個別上傳每個 Resource，惟須注意每個 Resource 的關聯性並調整上傳的順序。


## 演練 6：撰寫 Profile
本題目是為了評估您是否掌握 Profile 的相關知識，並是否具備撰寫 Profile 的能力。

FHIR 實作指引（Implementation Guide）與 Profile 是 FHIR 維持一致性這項特性的實踐方式，而 Forge 是一個由 Simplifier.net 發布的 Profile 編輯器。現在請您試著使用該項工具，以任意 Resource 製作出一個自己的 Profile，並滿足以下條件：
+ **必須（SHALL）** 至少包含 3 個欄位的修改。
+ **必須（SHALL）** 在製作的 Profile (StructureDefinition) 中，指定有效的 url 欄位，並在 description 欄位中撰寫您對於本 Profile 的描述。
+ 情境不拘，但 **建議（SHOULD）** 挑選一個現實世界的應用情境，並盡可能將 Profile 的內容規範完整一點。

您可以使用 Forge 工具（必須先註冊 Simplifier.net 帳號）或自行撰寫 StructureDefinition 來製作 Profile，並將完成的 Profile (StructureDefinition) 上傳至 FHIR Server。

完成 Profile 的上傳後，請撰寫出符合您的 Profile 要求的 FHIR Resource 資料，該筆資料的 meta.profile 欄位必須填入您的 Profile URL，完成後請上傳至 FHIR Server 中。


## 演練 7：程式設計／病患初診資料登錄表單
本題目是為了評估您是否具備開發基礎的 FHIR 應用程式的能力。

資料來源：[衛生福利部胸腔醫院－初診病患基本資料卡](https://www.ccd.mohw.gov.tw/public/forms/e831aad3547e45eae064a58922202bd5.pdf)

請根據以下表單實作病人資料登錄網頁，必須要能提供以下資料登記（塗掉的欄位不用寫），並能將使用者填寫的資料上傳到 FHIR Server 後，取得 Patient ID 並顯示於頁面中。

![](https://i.imgur.com/Yvith4A.png)



# 開源專案
## FHIR 通用轉換工具：Project F.U.C.K.
FHIR Universal Conversion Kit (Project F.U.C.K) 是一個通用的 FHIR 資料標準化工具，支援以設定檔及 Low Code 的方式，將任意資料標準化為 FHIR 格式，並具備自動上傳至 FHIR 伺服器的功能。

| Author | License | Source Code 
| -------- | -------- | ------- |
| Lorex     | CC BY-NC-SA 3.0 | [GitHub Repository](https://github.com/Lorex/FHIR-Universal-Conversion-Kit)


## Burni FHIR Server
Burni 使用 Node.JS 、Express 框架以及 MongoDB 實作 FHIR R4 Server，經由簡單的設定即可產生指定 FHIR Resource的 Mongoose Schema、API程式碼並可自行更改，滿足需求。目前Burni支援Windows以及Linux，讓開發人員可以快速架設 FHIR Server。 

Burni FHIR Server有別於關聯式資料庫，採用NoSQL架構，目前已100%通過 AEGIS Touchstone Basic-R4-Server驗證測試，包含 2,216測試情境。

| Author | License | Source Code 
| -------- | -------- | ------- |
| CYLAB     | Apache 2.0 | [GitHub Repository](https://github.com/Chinlinlee/Burni)

## Raccoon
Raccoon 是使用 no-SQL 資料庫實作的醫學影像儲存系統(DICOMweb PACS)，目前主要由北護影像資訊學實驗室維護。 Raccoon 使用 MongoDB 管理 DICOM 影像並提供 DICOMweb 以及 FHIR ImagingStudy RESTful API 功能進行儲存、查詢、調閱。 另外 Raccoon 使用了 Burni FHIR Server為底延伸出 FHIR 與 DICOM 結合的功能。

| Author | License | Source Code 
| -------- | -------- | ------- |
| CYLAB     | MIT | [GitHub Repository](https://github.com/cylab-tw/raccoon)

# 封存資料
#### ~~~都更前的~~舊新手村
+ 【~~都更前的~~舊新手村】陽明大學／FHIR 快速跳坑指南
  https://www.slideshare.net/lorexyang/fhir-201786643
+ 【新版伺服器架設】FHIR 伺服器建置指南
  https://hackmd.io/e7sWPVUzQjSTJ6IYDcwAFQ
#### DSTU3 版本適用
+ 【舊版新手村】慈濟大學／FHIR 快速掃描
  https://www.slideshare.net/lorexyang/fhir-153713142
+ 【不懂 REST 看這篇】台中榮總／FHIR REST API 導論與使用
  https://www.slideshare.net/lorexyang/fhir-rest-api-123996154
+ 【想架 Server 看這邊】台中榮總／FHIR Server 安裝與使用
  https://www.slideshare.net/lorexyang/fhir-server



# 版本紀錄
#### 2022/04/28
- 重新整理這份文件（我覺得太亂了QQ）
- 加入新的參考資料
- 重新編輯情境演練內容，使其符合學習順序
- 加入新的情境演練內容
- 加入開源專案章節

#### 2020-2021
- 陸續加入了一些參考文件
- 陸續加入了範例程式及情境演練

#### 2019/11/21
- 整理文件格式

#### 2019/07/06
- 加入一些標準參考文件
- 加入 FHIR Server 安裝與使用

#### 2018/11/22
- 創建了這份文件，並收錄了基本的參考資料