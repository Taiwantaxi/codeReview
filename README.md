# IOS 司機 App 程式碼修改履歷

---
## 2017-10

**各發佈平台最新版本**

  1. _Hockeyapp 測試版_

    * Version 1.08.13 (201711061800)

    * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b)

  2. _Hockeyapp 正式版_

    * Version 1.08.14 (201711061800)

    * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5)

  3. _App Store 正式版_

    * Version 1.09 (201711071200)

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)

---
* **註解說明**

  * Oct1 : (Redmine#8504) 頁面需手動關閉無法自消， 就算未承接也會顯示，會誤導為其他任務詢問被取消

  * Oct2 : (Redmine#7543) 手機App 的 log file 寫入機制, 以及將 log file 上傳 server 機制

  * Oct3 : (Redmine#XXXX) 測試 PFFFA 封包黏包問題

  * Oct4 : (Redmine#8688) 新增 Beep + 多元任務請承接音量增大 (4X to 6X)

  * Oct5 : (Redmine#8734) ios 11 到達頁導航地圖 不會 auto focus

  * Oct6 : (Redmine#8750) 按下到達 到出現 (未現) 應該倒數 5分鐘

  * Oct7 : (Redmine#8776) 跳到桌面 一分鐘後我在從空車那裡進去司機版 然後就秀斗了

  * Oct8 : (Redmine#8825) 任務補發成功 時 加上 Beep 提示

  * Oct9 : (Redmine#8749) 任務10秒詢問頁 司機希望 能不須捲動 就 完整看到 (上車) (下車) (備註)

  * Oct10: (Redmine#7935) 任務已經取消了，但車機卻還是可以 meter On 功能調整修改

  * Oct11: (Redmine#9056) 到達頁 如果按(Home) 回主選單 會重新倒數 未現 按鈕

  * Oct12: (Redmine#9159) 踢班後開始出現 空車 /排班 交替 異常

  * Oct13: (Redmine#9247) 司機沒按[承接]的[語音取消]提醒視窗 必須 2秒自消 或不顯示

  * Oct14: (Redmine#9246) 按了[開始]以後 出現注意[行車安全]提醒視窗 必須要10 秒自消

  * Oct15: (Redmine#9319) App版號檢查機制

  * Oct16: (Redmine#9221) 多元身分登入時 主選單 將 (空排點)(導航)隱藏

  * Oct17: (Redmine#9196) 連續按幾次拒接後 遇到乘客取消 就會發生 異常詢問音不見 App 整個異常

  * Oct18: (Redmine#9027) 80071 1.08.08 任務進行中忽然出現[付款失敗]訊息


---
* **發版紀錄 (Hockeyapp) 測試版**

  1. *Version 1.08.01 (201710031800)*

      **IOS App 測試環境**

      _修正 bug_

      * 手機App 的 log file 寫入機制, 以及將 log file 上傳 serve

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/26)  
  2. *Version 1.08.03 (201710191800)*

      **IOS App 測試環境**

      _修正 bug_

      * 手機App 的 log file 寫入機制, 以及將 log file 上傳 serve

      * 新增 Beep + 多元任務請承接音量增大 (4X to 6X)

      * 按下到達 到出現 (未現) 應該倒數 5分鐘

      * 跳到桌面 一分鐘後我在從空車那裡進去司機版 然後就秀斗了

      * 任務補發成功 時 加上 Beep 提示

      * ios 11 到達頁導航地圖 不會 auto focus

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/28)      

  3. *Version 1.08.05 (201710301800)*

      **IOS App 測試環境**

      _修正 bug_

      * 任務已經取消了，但車機卻還是可以 meter On 功能調整修改

      * 到達頁 如果按(Home) 回主選單 會重新倒數 未現 按鈕

      * 任務10秒詢問頁 司機希望 能不須捲動 就 完整看到 (上車) (下車) (備註)

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/29)

  4. *Version 1.08.05 (201710311200)*

      **IOS App 測試環境**

      _修正 bug_

      * 調整 UI 畫面

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/30)

  5. *Version 1.08.07 (201711031200)*

      **IOS App 測試環境**

      _修正 bug_

      * 司機沒按[承接]的[語音取消]提醒視窗 必須 2秒自消 或不顯示

      * 按了[開始]以後 出現注意[行車安全]提醒視窗 必須要10 秒自消

      * 多元身分登入時 主選單 將 (空排點)(導航)隱藏

      * 連續按幾次拒接後 遇到乘客取消 就會發生 異常詢問音不見 App 整個異常

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/31)

  6. *Version 1.08.09 (201711031800)*

      **IOS App 測試環境**

      _修正 bug_

      * 任務進行中忽然出現[付款失敗]訊息

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/32)

  7. *Version 1.08.11 (201711061200)*

      **IOS App 測試環境**

      _修正 bug_

      * 修正退背景後繁忙狀態未解除問題

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/33)

  8. *Version 1.08.13 (201711061800)*

      **IOS App 測試環境**

      _修正 bug_

      * 修正畫面未承接無法自消問題

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/34)

---
* **發版紀錄 (Hockeyapp) 正式版**

  1. *Version 1.08.02 (201710031800)*

      **IOS App 正式環境**

      _修正 bug_

      * 手機App 的 log file 寫入機制, 以及將 log file 上傳 serve

      * 新增 Beep + 多元任務請承接音量增大 (4X to 6X)

      * 按下到達 到出現 (未現) 應該倒數 5分鐘

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/12)

  2. *Version 1.08.04 (201710191800)*

      **IOS App 正式環境**

      _修正 bug_

      * 手機App 的 log file 寫入機制, 以及將 log file 上傳 serve

      * 新增 Beep + 多元任務請承接音量增大 (4X to 6X)

      * 按下到達 到出現 (未現) 應該倒數 5分鐘

      * 跳到桌面 一分鐘後我在從空車那裡進去司機版 然後就秀斗了

      * 任務補發成功 時 加上 Beep 提示

      * ios 11 到達頁導航地圖 不會 auto focus

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/13)

  3. *Version 1.08.06 (201710301800)*

      **IOS App 正式環境**

      _修正 bug_

      * 任務已經取消了，但車機卻還是可以 meter On 功能調整修改

      * 到達頁 如果按(Home) 回主選單 會重新倒數 未現 按鈕

      * 任務10秒詢問頁 司機希望 能不須捲動 就 完整看到 (上車) (下車) (備註)

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/14)

  4. *Version 1.08.06 (201710311200)*

      **IOS App 正式環境**

      _修正 bug_

      * 調整 UI 畫面

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/15)

  5. *Version 1.08.08 (201711031200)*

      **IOS App 正式環境**

      _修正 bug_

      * 司機沒按[承接]的[語音取消]提醒視窗 必須 2秒自消 或不顯示

      * 按了[開始]以後 出現注意[行車安全]提醒視窗 必須要10 秒自消

      * 多元身分登入時 主選單 將 (空排點)(導航)隱藏

      * 連續按幾次拒接後 遇到乘客取消 就會發生 異常詢問音不見 App 整個異常

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/16)

  6. *Version 1.08.10 (201711031800)*

      **IOS App 正式環境**

      _修正 bug_

      * 任務進行中忽然出現[付款失敗]訊息

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/17)

  7. *Version 1.08.12 (201711061200)*

      **IOS App 正式環境**

      _修正 bug_

      * 修正退背景後繁忙狀態未解除問題

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/18)

  8. *Version 1.08.14 (201711061800)*

      **IOS App 正式環境**

      _修正 bug_

      * 修正畫面未承接無法自消問題

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/19)


---
* **發版紀錄 (App Store) 正式版**

  1. *Version 1.08 (201709291800)*  

    * iOS 11 地圖定位問題修正

    * 到達頁防呆機制

    * 改善載客頁顯示資訊

    * 調整到達頁顯示資訊順序

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)

  2. *Version 1.09 (201711071200)*  

    * 任務詢問UI修改

    * 主選單調整

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)
