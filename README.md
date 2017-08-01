# IOS 司機 App 程式碼修改履歷

---
## 2017-07

**各發佈平台最新版本**

  1. _Hockeyapp 測試版_

    * Version 1.05.01 (201708011200)

    * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/11)

  2. _Hockeyapp 正式版_

    * Version 1.04.05 (201707131200)

    * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/3)

  3. _App Store 正式版_

    * Version 1.05 (201707181800)

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)

---
* **註解說明**

  * SCR1  : (Redmine#6558) 任務執行中(載客中)不應該顯示 任務取消電文

  * SCR2  : (Redmine#6560) 設定-更改密碼 功能先 Disable

  * SCR3  : (Redmine#6416) 小黃司機/多元司機，在上傳個人文件資料區，【執業登記】不該顯示為 【良民證】

  * SCR4  : (Redmine#6381) 預約列表頁 送機預約 未顯示 乘客人数行李數

  * SCR5  : (Redmine#6437) 個人資料放入車型 (舒適/豪華/商務)

  * SCR6  : (Redmine#6542) 預約列表頁 雙平台排序不一致

  * SCR7  : 取消 10秒 限制 (若司機調整設備時間 會接不到任務)

  * SCR8  : (Redmine#6817) 請將【手機末6碼】字串改為 【身分證號末9碼】

  * SCR9  : (Redmine#6820) 管家代駕申請第三頁 雖銀行帳號已存在 仍要回登入頁

  * SCR10 : (Redmine#6813) 已開通 個人資料不應出現重新上傳Button

  * SCR11 : (Redmine#6186) 本日營業資料 排序倒了-測試環境

  * SCR12 : (Redmine#6812) 7XXXX 主畫面少了空排點 , Layout 與安卓不同

  * SCR13 : (Redmine#6824 & 6828) 任務被誰接走 需要在轉完 後 確定沒 接到 Dismiss ui

  * SCR14 : (Redmine#6926) 只顯示即時詢問，或只顯示預約詢問 [類似 繁忙狀態切換]

  * SCR15 : (Redmine#7024) 任務付款完成頁 如果有小費 請 明顯顯示小費欄

  * SCR16 : (Redmine#7020) 登入後 先檢查是否有正在進行中的任務以顯示到達頁或載客頁

  * SCR17 : (Redmine#6174) 任務詢問頁 Google API預估時間 或路程差距 過大

  * SCR18 : (Redmine#7135) 反映 於到達頁 倒數時間 9X:XX 分鐘

  * SCR19 : (Redmine#7144) 接單紀錄數字有點龐大 現在點進去都要等

  * SCR20 : (Redmine#7059) DAP17070609166 結帳時閃退

  * SCR21 : (Redmine#7171) 因缺少任務開始時間 營業資料少了 8:00 TWD 230 元

  * SCR22 : (Redmine#7150) (載客中 ...按下手動結束前） 之間 允許顯示10秒預約詢問

  * SCR23 : (Redmine#7152) 按下手動結束 輸入車資前須將車機設為(繁忙)以免任務詢問干擾

  * SCR24 : (Redmine#7148) App 斷讯時或 背景回來 要有 retry 機制

  * SCR25 : (Redmine#7291) 主選單的導航功能 請改為按了沒反應

---
* **發版紀錄 (Hockeyapp) 測試版**

  1. *Version 1.04.4 (201707041330)*
      * SCR 1 : 修正 任務執行中(載客中)不應該顯示任務取消電文

      * SCR2 : 修正 設定-更改密碼 功能先 Disable

      * SCR3 : 修正 小黃司機/多元司機，在上傳個人文件資料區，【執業登記】不該顯示為 【良民證】

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b)

  2. *Version 1.04.4 (201707041630)*
      * SCR4 : 修正 預約列表頁 送機預約 未顯示 乘客人数行李數

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/5)

  3. *Version 1.04.4 (201707041730)*
      * SCR6 : 修正 預約列表頁 雙平台排序不一致

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/6)
  4. *Version 1.04.07 (201707051130)*

      **IOS App 測試環境**

      _修正 bug_

      * 任務執行中(載客中)不應該顯示 任務取消電文

      * 設定-更改密碼 功能先 Disable

      * 小黃司機/多元司機，在上傳個人文件資料區，【執業登記】未傳入後臺（I：執業登記)

      * 小黃司機/多元司機，在上傳個人文件資料區，【執業登記】不該顯示為 【良民證】

      * 預約列表頁 雙平台排序不一致

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b)

  5. *Version 1.04.08 (201707121500)*

      **IOS App 測試環境**

      _修正 bug_

      * 取消 10秒 限制 (若司機調整設備時間 會接不到任務)

      * 請將【手機末6碼】字串改為 【身分證號末9碼】

      * 管家代駕申請第三頁 雖銀行帳號已存在 仍要回登入頁

      * 已開通 個人資料不應出現重新上傳Button

      * 本日營業資料 排序倒了-測試環境

      * 7XXXX 主畫面少了空排點 , Layout 與安卓不同

      * 任務被誰接走 需要在轉完 後 確定沒 接到 Dismiss ui

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/8)

  6. *Version 1.04.09 (201707191200)*

      * SCR5 : 個人資料放入車型 (舒適/豪華/商務)

      * SCR14 : 只顯示即時詢問，或只顯示預約詢問 [類似 繁忙狀態切換]

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/9)

  7. *Version 1.05.01 (201707271200)*

      * SCR15 : 任務付款完成頁 如果有小費 請 明顯顯示小費欄

      * SCR18 : 反映 於到達頁 倒數時間 9X:XX 分鐘

      * SCR19 : 接單紀錄數字有點龐大 現在點進去都要等

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/10)

  5. *Version 1.05.01 (201708011200)*

      **IOS App 測試環境**

      _修正 bug_

      * 任務付款完成頁 如果有小費 請 明顯顯示小費欄

      * 反映 於到達頁 倒數時間 9X:XX 分鐘

      * 接單紀錄數字有點龐大 現在點進去都要等

      * DAP17070609166 結帳時閃退

      * (載客中 ...按下手動結束前） 之間 允許顯示10秒預約詢問

      * 按下手動結束 輸入車資前須將車機設為(繁忙)以免任務詢問干擾

      * App 斷讯時或 背景回來 要有 retry 機制

      * 主選單的導航功能 請改為按了沒反應

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/11)


---
* **發版紀錄 (Hockeyapp) 正式版**

  1. *Version 1.04.04 (201707131200)*

      **IOS App 正式環境**

      _修正 bug_
      * 任務執行中(載客中)不應該顯示 任務取消電文

      * 設定-更改密碼 功能先 Disable

      * 小黃司機/多元司機，在上傳個人文件資料區，【執業登記】不該顯示為 【良民證】

      * 預約列表頁 送機預約 未顯示 乘客人数行李數

      * 預約列表頁 雙平台排序不一致

      * 取消 10秒 限制 (若司機調整設備時間 會接不到任務)

      * 請將【手機末6碼】字串改為 【身分證號末9碼】

      * 管家代駕申請第三頁 雖銀行帳號已存在 仍要回登入頁

      * 已開通 個人資料不應出現重新上傳Button

      * 本日營業資料 排序倒了-測試環境

      * 7XXXX 主畫面少了空排點 , Layout 與安卓不同

      * 任務被誰接走 需要在轉完 後 確定沒 接到 Dismiss ui

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5)

  2. *Version 1.04.05 (201707131200)*

      * 更新憑證 新增測試設備5台

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/3)


---
* **發版紀錄 (App Store) 正式版**
  1. *Version 1.04 (201706091809)*

    * 營業資料顯示修正

  2. *Version 1.05 (201707181800)*  

    * 新增小黃司機申請酒後代駕入口

    * 任務詢問流程優化

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)
