# IOS 司機 App 程式碼修改履歷

---
## 2018-01

**各發佈平台最新版本**

  1. _Hockeyapp 測試版_

    * Version 1.09.13 (201801311200)

    * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b)

  2. _Hockeyapp 正式版_

    * Version 1.09.14 (201801311200)

    * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5)

  3. _App Store 正式版_

    * Version 1.09.14 (201802011200)

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)

---
* **註解說明**

  * Jan0 : (Redmine#XXXX)
    > 多元付款方式「現金」->「其他」

  * Jan1 : (Redmine#10696)  
    > 未適配 ipad 版面 [預約任務詢問頁] 上車地址長一點下車看不到

  * Jan2 : (Redmine#10398)  
    > 實作 0x300F

  * Jan3 : (Redmine#10764)  
    > 多元司機開通代駕服務後 代駕任務詢問頁 語音卻為多元任務請承接

  * Jan4 : (Redmine#10832)
    > 載客頁加上 倍率 和小費金額

  * Jan5 : (Redmine#10396)
    > 整合勤威鎖路 SDK 1.0.0

  * Jan6 : (Redmine#10858)
    > 信用卡綁卡交易失敗，司機App無法再改用其他支付方式

  * JanA : (Redmine#XXXX)
    > 重複交易需任務結束

  * JanB : (Redmine#10401)
    > 確認 Socket 斷線時, 乘客取消叫車, 當重新連線後, 車機能否收到任務取消通知

  * JanC : (Redmine#XXXX)
    > 藍牙功能開發

  * JanD : (Redmine#XXXX)
    > 取消 3800 電文用 3000 電文替代

---
* **發版紀錄 (Hockeyapp) 測試版**

  1. *Version 1.09.09 (201801121800)*

      **IOS App 測試環境**

      _修正 bug_

      * 多元付款方式「現金」->「其他」

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/41)  

  2. *Version 1.09.11 (201801241800)*

      **IOS App 測試環境**

      _修正 bug_

      * 確認 Socket 斷線時, 乘客取消叫車, 當重新連線後, 車機能否收到任務取消通知

      * 重複交易需任務結束

      * 信用卡綁卡交易失敗，司機App無法再改用其他支付方式

      * 未適配 ipad 版面 [預約任務詢問頁] 上車地址長一點下車看不到

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/42)  

  3. *Version 1.09.13 (201801301200)*

      **IOS App 測試環境**

      _修正 bug_

      * 實作 0x300F，連線品質狀態回報 0 ~ 30 秒收到派遣中心回覆閃黃綠燈，30 ~ 60 秒閃橘燈，60 ~ 90 閃紅燈，90 以上派遣中心無回應紅燈恆亮

      * 多元司機開通代駕服務後 代駕任務詢問頁 語音卻為多元任務請承接

      * 載客頁加上 倍率 和小費金額

      * 整合勤威鎖路 SDK 1.0.0

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/43)


  4. *Version 1.09.13 (201801311200)*

      **IOS App 測試環境**

      _修正 bug_

      * 實作 0x300F，連線品質狀態回報 0 ~ 30 秒收到派遣中心回覆閃綠燈，30 ~ 60 秒閃橘燈，60 ~ 90 閃紅燈，90 以上派遣中心無回應紅燈恆亮

      * 多元司機開通代駕服務後 代駕任務詢問頁 語音卻為多元任務請承接

      * 載客頁加上 倍率 和小費金額

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/43)

---
* **發版紀錄 (Hockeyapp) 正式版**

  1. *Version 1.09.10 (201801121800)*

    **IOS App 正式環境**

    _修正 bug_

    * 多元付款方式「現金」->「其他」

    * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/26)

  2. *Version 1.09.12 (201801241800)*

      **IOS App 正式環境**

      _修正 bug_

      * 確認 Socket 斷線時, 乘客取消叫車, 當重新連線後, 車機能否收到任務取消通知

      * 重複交易需任務結束

      * 信用卡綁卡交易失敗，司機App無法再改用其他支付方式

      * 未適配 ipad 版面 [預約任務詢問頁] 上車地址長一點下車看不到

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/27)


  3. *Version 1.09.14 (201801301200)*

      **IOS App 正式環境**

      _修正 bug_

      * 實作 0x300F，連線品質狀態回報 0 ~ 30 秒收到派遣中心回覆閃黃綠燈，30 ~ 60 秒閃橘燈，60 ~ 90 閃紅燈，90 以上派遣中心無回應紅燈恆亮

      * 多元司機開通代駕服務後 代駕任務詢問頁 語音卻為多元任務請承接

      * 載客頁加上 倍率 和小費金額

      * 整合勤威鎖路 SDK 1.0.0

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/28)

  4. *Version 1.09.14 (201801311200)*

      **IOS App 正式環境**

      _修正 bug_

      * 實作 0x300F，連線品質狀態回報 0 ~ 30 秒收到派遣中心回覆閃綠燈，30 ~ 60 秒閃橘燈，60 ~ 90 閃紅燈，90 以上派遣中心無回應紅燈恆亮

      * 多元司機開通代駕服務後 代駕任務詢問頁 語音卻為多元任務請承接

      * 載客頁加上 倍率 和小費金額

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/28)

---
* **發版紀錄 (App Store) 正式版**

  1. *Version 1.09.14 (201802011200)*  

    * 新增連線品質狀態偵測

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)
