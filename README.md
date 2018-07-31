# IOS 司機 App 程式碼修改履歷

---
## 2018-05

**各發佈平台最新版本**

  1. _Hockeyapp 測試版_

    * Version 1.09.25 (201805021800)

    * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b)

  2. _Hockeyapp 正式版_

    * Version 1.09.25 (201805021800)

    * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5)

  3. _App Store 正式版_

    * Version 1.09.24 (201805031200)

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)

---
* **註解說明**

  * Mar1 : (Redmine#12547)
    > 任務詢問音效, 小黃任務(JobExInfo.PlusJobType=0)播放金幣音效

  * May2 : (Redmine#12472)
    > 車機本機log保留時間放大到14天，以利追查異常問題。

  * May3 : (Redmine#11793)
    > 串接推播服務, 實作「任務詢問」與「任務取消」

  * May4 : (Redmine#XXXX)
    > 顯示車機訊息

  * May5 : (Redmine#XXXX)
    > Google Map 路徑規劃

  * May6 : (Redmine#XXXX)
    > UU Pon系統、Happy go串接作業

  * MayA : (Redmine#XXXX)
    > 修正正在打電話確認畫面，造成任務取消異常

  * MayB : (Redmine#XXXX)
    > 追蹤電文代碼不能轉成文字造成的異常，增加 Log 確認資料

  * MayC : (Redmine#XXXX)
    > 登入，啟用司機預設工作模式 - 空車 or 只接預約

---

  * ## 小黃- 功能需求 - 排班點修改

  * MayD0 : 測試用點擊定位

  * MayD1 : 點擊車資輸入(路招)，再點擊即時任務，會有異常任務出現

  * MayD2 : 小黃- 功能需求 - 排班點修改 - 1.任務踢班邏輯修改 2.排班點相關電文 3103、3106、310B、3105 修改

  * MayD3 : XXX

  * ## 小黃- 功能新增

  * Jun1 : 小黃-功能新增-投標任務頁面

  * Jun2 : 接單感應紐範圍縮減，防止司機誤觸

  * Jun3 : 業務單位需求文字修改，只接預約 -> 裝忙

  * Jun4 : bug fix : 預約任務詢問頁，圖示擋住日期

  * Jun5 : bug fix : 等待乘客頁，預約任務取消失敗

  * Jun6 : bug fix : 臨近排班點週期 queueCheck -> RNP_CHECK_TIME

---

  * ## 小黃- 功能需求 - MID 非現金結帳

  * July1 : 建置核心元件 MIDStreamData 與 MID 設備溝通

  * July2 : 相關結帳業務邏輯

  * July3 : 發送訊息頁 - 新增 Log 回傳 Server 功能

---

* **發版紀錄 (Hockeyapp) 測試版**

  1. *Version 1.09.23 (201805021800)*

      **IOS App 測試環境**

      _修正 bug_

      * 任務詢問音效, 小黃任務(JobExInfo.PlusJobType=0)播放金幣音效

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/52)

  2. *Version 1.09.25 (201805171200)*

      **IOS App 測試環境**

      _修正 bug_

      * 車機本機log保留時間放大到14天，以利追查異常問題。

      * 顯示車機訊息

      * Google Map 路徑規劃

      * 修正正在打電話確認畫面，造成任務取消異常

      * 追蹤電文代碼不能轉成文字造成的異常，增加 Log 確認資料

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/53)

  3. *Version 1.09.25 (201805281200)*

      **IOS App 測試環境**

      _修正 bug_

      * 車機本機log保留時間放大到14天，以利追查異常問題。

      * 顯示車機訊息

      * Google Map 路徑規劃

      * 修正正在打電話確認畫面，造成任務取消異常

      * 追蹤電文代碼不能轉成文字造成的異常，增加 Log 確認資料

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/54)

  4. *Version 1.09.25 (201806251200)*

      **IOS App 測試環境**

        _功能 新增_
       * 小黃- 功能需求 - 排班點修改
       * 小黃- 功能需求 - 路招功能
       * 小黃- 功能新增 - 投標任務頁面
       * 新增 HappyGo UUPON 結帳方式
       * 接單感應紐範圍縮減，防止司機誤觸
       * 業務單位需求文字修改，只接預約 -> 裝忙
       * 車機本機log保留時間放大到14天，以利追查異常問題
       * 顯示車機訊息
       * Google Map 路徑規劃
       * 登入啟用司機預設工作模式

       _修正 bug_
       * 修正正在打電話確認畫面，造成任務取消異常
       * 追蹤電文代碼不能轉成文字造成的異常，增加 Log 確認資料
       * 修正任務承接失敗任務倒數消失
       * 登入後 Hardware Status 修改
       * 任務下放時間修改 T + ETA - ct
       * 修正預約任務詢問頁，圖示擋住日期
       * 修正等待乘客頁，預約任務取消失敗

      [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/55)

---
* **發版紀錄 (Hockeyapp) 正式版**

  1. *Version 1.09.24 (201805021800)*

      **IOS App 正式環境**

      _修正 bug_

      * 任務詢問音效, 小黃任務(JobExInfo.PlusJobType=0)播放金幣音效

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/35)

  2. *Version 1.09.25 (201805021800)*

      **IOS App 正式環境**

      _修正 bug_

      * 車機本機log保留時間放大到14天，以利追查異常問題。

      * 顯示車機訊息

      * Google Map 路徑規劃

      * 修正正在打電話確認畫面，造成任務取消異常

      * 追蹤電文代碼不能轉成文字造成的異常，增加 Log 確認資料

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/36)

  3. *Version 1.09.25 (201806251200)*

      **IOS App 正式環境**

        _功能 新增_
       * 小黃- 功能需求 - 排班點修改
       * 小黃- 功能需求 - 路招功能
       * 小黃- 功能新增 - 投標任務頁面
       * 新增 HappyGo UUPON 結帳方式
       * 接單感應紐範圍縮減，防止司機誤觸
       * 業務單位需求文字修改，只接預約 -> 裝忙
       * 車機本機log保留時間放大到14天，以利追查異常問題
       * 顯示車機訊息
       * Google Map 路徑規劃
       * 登入啟用司機預設工作模式

       _修正 bug_
       * 修正正在打電話確認畫面，造成任務取消異常
       * 追蹤電文代碼不能轉成文字造成的異常，增加 Log 確認資料
       * 修正任務承接失敗任務倒數消失
       * 登入後 Hardware Status 修改
       * 任務下放時間修改 T + ETA - ct
       * 修正預約任務詢問頁，圖示擋住日期
       * 修正等待乘客頁，預約任務取消失敗

      [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/55)

---
* **發版紀錄 (App Store) 正式版**

  1. *Version 1.09.24 (201805031200)*  

    * 調整任務音檔

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)   
