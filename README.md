# IOS 司機 App 程式碼修改履歷

---
## 2017-08-01 ~ 2017-09-30

**各發佈平台最新版本**

  1. _Hockeyapp 測試版_
  
    * Version 1.07.11 (201709291200)

    * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/25)

  2. _Hockeyapp 正式版_

    * Version 1.07.08 (201709291200)

    * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/11)

  3. _App Store 正式版_

    * Version 1.08 (201709291800)

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)

---
* **註解說明**

  * AUG1 : (Redmine#7205) 所有地圖中的黑車應該小黃登入要變黃車

  * AUG2 : (Redmine#7211) 選擇以現金支付 會立即閃退

  * AUG3 : (Redmine#7217) 選擇以非現金支付 雙平台錯誤訊息UI不一致

  * AUG4 : (Redmine#7347) 預約任務執行後 , 點選到達 , 關掉重開 , 預約任務仍停在未執行狀態

  * AUG5 : (Redmine#7470) 正在響(任務詢問時)調整 大小聲、或靜音ON_OFF ，都是下次才會生效

  * AUG6 : (Redmine#7465) 還沒登錄完成任務就叫個不停,當在登入頁

  * AUG7 : (Redmine#7569) 營業= meter on but 接單 = meter off 時間排序

  * AUG8 : (Redmine#7619) 結帳時 網路瞬斷 又瞬回 Loading 頁面未 Dismiss

  * AUG9 : (Redmine#7620) 任務詢問頁/到達頁 改由App端自行詢問Google 預估分鐘公里數(而不透過派遣)

  * AUG10 : (Redmine#XXXX) 新增任務詢問 多元詢問聲音

  * AUG11 : (Redmine#7683) 任務承接後 因無預期封包遺失 而造成任務停留在[派車成功]

  * AUG12 : (Redmine#XXXX) 新增提醒視窗，當金額超過1000元

  * AUG13 : (Redmine#7544) 在系統下拉通知欄列表上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面; Android點選後, 要能直接改變車機狀態

  * AUG14 : (Redmine#7788) 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

  * AUG15 : (Redmine#7794) 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

  * AUG16 : (Redmine#7736) 80123 反映常常在到達頁手抖 按了到達 就進入載客頁

  * AUG17 : (Redmine#7804) 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

  * AUG18 : (Redmine#7814) 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

  * AUG19 : (Redmine#7853) 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

  * AUG20 : (Redmine#7879) 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

  * AUG21 : (Redmine#7943) 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

  * AUG22 : (Redmine#7935) 任務已經取消了，但車機卻還是可以 meter On 功能調整修改

  * AUG23 : (Redmine#8101) 串接 6302 多付款別交易

  * AUG24 : (Redmine#XXXX) 小黃修改個人資料顯示字串為車發處

  * AUG25 : (Redmine#XXXX) 串接 A005 、 A006 的 Log file

  * AUG26 : (Redmine#8298) 到達頁 加上 「開始確定 詢問」以防誤觸進入載客頁

  * AUG27 : (Redmine#XXXX) 串接 PA007 、 PA008 多付款別明細

  * AUG28 : (Redmine#8506) 修正 6300 & 6302 同時收到電文問題 & 支援 IOS 11 定位功能

  * AUGX : Log 建立 CocoaLumberjack

  * AUGY : 藍芽收資料

  * AUGZ : 修正任務詢問頁距離

  * AUGW : 修正 6300 & 6302 同時收到電文問題 & 支援 IOS 11 定位功能

---
* **發版紀錄 (Hockeyapp) 測試版**

  1. *Version 1.05.01 (201708011200)*

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

  2. *Version 1.05.01 (201708031200)*

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

      * 預約任務執行後 , 點選到達 , 關掉重開 , 預約任務仍停在未執行狀態

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/12)

  3. *Version 1.05.01 (201708071200)*

      * 新增測試設備一台

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/13)

  4. *Version 1.05.03 (201708101200)*

      **IOS App 測試環境**

      _修正 bug_

      * Fix Bug 副班可能無法承接到任務

      * 任務付款完成頁 如果有小費 請 明顯顯示小費欄

      * 反映 於到達頁 倒數時間 9X:XX 分鐘

      * 接單紀錄數字有點龐大 現在點進去都要等

      * DAP17070609166 結帳時閃退

      * (載客中 ...按下手動結束前） 之間 允許顯示10秒預約詢問

      * 按下手動結束 輸入車資前須將車機設為(繁忙)以免任務詢問干擾

      * App 斷讯時或 背景回來 要有 retry 機制

      * 主選單的導航功能 請改為按了沒反應

      * 預約任務執行後 , 點選到達 , 關掉重開 , 預約任務仍停在未執行狀態

      * 結帳時 網路瞬斷 又瞬回 Loading 頁面未 Dismiss

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/15)

  5. *Version 1.05.05 (201708101800)*

      **IOS App 測試環境**

      _修正 bug_

      * Fix Bug 新增斷線狀態顯示

      * Fix Bug 副班可能無法承接到任務

      * 任務付款完成頁 如果有小費 請 明顯顯示小費欄

      * 反映 於到達頁 倒數時間 9X:XX 分鐘

      * 接單紀錄數字有點龐大 現在點進去都要等

      * DAP17070609166 結帳時閃退

      * (載客中 ...按下手動結束前） 之間 允許顯示10秒預約詢問

      * 按下手動結束 輸入車資前須將車機設為(繁忙)以免任務詢問干擾

      * App 斷讯時或 背景回來 要有 retry 機制

      * 主選單的導航功能 請改為按了沒反應

      * 預約任務執行後 , 點選到達 , 關掉重開 , 預約任務仍停在未執行狀態

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/16)

  6. *Version 1.06.01 (201708171600)*

      **IOS App 測試環境**

      _修正 bug_

      * 所有地圖中的黑車應該小黃登入要變黃車

      * 選擇以非現金支付 雙平台錯誤訊息UI不一致

      * 正在響(任務詢問時)調整 大小聲、或靜音ON_OFF ，都是下次才會生效

      * 還沒登錄完成任務就叫個不停,當在登入頁

      * 營業= meter on but 接單 = meter off 時間排序

      * 新增任務詢問 多元詢問聲音

      * 結帳時 網路瞬斷 又瞬回 Loading 頁面未 Dismiss

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/17)

  7. *Version 1.06.03 (201708211200)*

      **IOS App 測試環境**

      _修正 bug_

      * 所有地圖中的黑車應該小黃登入要變黃車

      * 選擇以非現金支付 雙平台錯誤訊息UI不一致

      * 正在響(任務詢問時)調整 大小聲、或靜音ON_OFF ，都是下次才會生效

      * 還沒登錄完成任務就叫個不停,當在登入頁

      * 營業= meter on but 接單 = meter off 時間排序

      * 新增任務詢問 多元詢問聲音

      * 結帳時 網路瞬斷 又瞬回 Loading 頁面未 Dismiss

      * 任務承接後 因無預期封包遺失 而造成任務停留在[派車成功]

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/18)

  8. *Version 1.07.01 (201709061200)*

      **IOS App 測試環境**

      _修正 bug_

      * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

      * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

      * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

      * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

      * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

      * 反映常常在到達頁手抖 按了到達 就進入載客頁

      * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

      * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

      * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/19)

  9. *Version 1.07.03 (201709061800)*

      **IOS App 測試環境**

      _修正 bug_

      * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

      * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

      * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

      * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

      * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

      * 反映常常在到達頁手抖 按了到達 就進入載客頁

      * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

      * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

      * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

      * 修正小黃修改個人資料顯示字串為車發處

      *  接單紀錄頁不顯示乘客電話

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/20)

  10. *Version 1.07.05 (201709071200)*

      **IOS App 測試環境**

      _修正 bug_

      * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

      * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

      * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

      * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

      * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

      * 反映常常在到達頁手抖 按了到達 就進入載客頁

      * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

      * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

      * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

      * 修正小黃修改個人資料顯示字串為車發處

      * 接單紀錄頁不顯示乘客電話

      * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/21)


  11. *Version 1.07.07 (201709131200)*

      **IOS App 測試環境**

      _修正 bug_

      * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

      * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

      * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

      * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

      * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

      * 反映常常在到達頁手抖 按了到達 就進入載客頁

      * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

      * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

      * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

      * 修正小黃修改個人資料顯示字串為車發處

      * 接單紀錄頁不顯示乘客電話

      * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

      * 隱藏任務詢問頁乘客電話

      * 調整結帳完成 UI 畫面

      * 串接 6302 多付款別交易

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/22)

  12. *Version 1.07.09 (201709181800)*

      **IOS App 測試環境**

      _修正 bug_

      * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

      * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

      * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

      * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

      * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

      * 反映常常在到達頁手抖 按了到達 就進入載客頁

      * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

      * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

      * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

      * 修正小黃修改個人資料顯示字串為車發處

      * 接單紀錄頁不顯示乘客電話

      * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

      * 隱藏任務詢問頁乘客電話

      * 調整結帳完成 UI 畫面

      * 串接 6302 多付款別交易

      * 到達頁 加上 「開始確定 詢問」以防誤觸進入載客頁

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/23)

  13. *Version 1.07.09 (201709201800)*

      **IOS App 測試環境**

      _修正 bug_

      * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

      * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

      * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

      * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

      * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

      * 反映常常在到達頁手抖 按了到達 就進入載客頁

      * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

      * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

      * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

      * 修正小黃修改個人資料顯示字串為車發處

      * 接單紀錄頁不顯示乘客電話

      * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

      * 隱藏任務詢問頁乘客電話

      * 調整結帳完成 UI 畫面

      * 串接 6302 多付款別交易

      * 到達頁 加上 「開始確定 詢問」以防誤觸進入載客頁

      * 串接 PA007 、 PA008 多付款別明細

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/24)

  14. *Version 1.07.11 (201709291200)*

      **IOS App 測試環境**

      _修正 bug_

      * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

      * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

      * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

      * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

      * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

      * 反映常常在到達頁手抖 按了到達 就進入載客頁

      * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

      * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

      * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

      * 修正小黃修改個人資料顯示字串為車發處

      * 接單紀錄頁不顯示乘客電話

      * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

      * 隱藏任務詢問頁乘客電話

      * 調整結帳完成 UI 畫面

      * 串接 6302 多付款別交易

      * 到達頁 加上 「開始確定 詢問」以防誤觸進入載客頁

      * 串接 PA007 、 PA008 多付款別明細

      * 調整營業資料 UI 呈現 (車資 $ XXX)

      * 更了 ios 11、司機App 架上版 接客任務進行中，車子GPS 不會移動

      * 加入強制定位機制

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/25)      

---
* **發版紀錄 (Hockeyapp) 正式版**

  1. *Version 1.04.05 (201707131200)*

      * 更新憑證 新增測試設備5台

      * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/3)

  2. *Version 1.05.02 (201708031200)*

      **IOS App 正式環境**

      _修正 bug_

      * 任務付款完成頁 如果有小費 請 明顯顯示小費欄

      * 反映 於到達頁 倒數時間 9X:XX 分鐘

      * 接單紀錄數字有點龐大 現在點進去都要等

      * DAP17070609166 結帳時閃退

      * (載客中 ...按下手動結束前） 之間 允許顯示10秒預約詢問

      * 按下手動結束 輸入車資前須將車機設為(繁忙)以免任務詢問干擾

      * App 斷讯時或 背景回來 要有 retry 機制

      * 主選單的導航功能 請改為按了沒反應

      * 預約任務執行後 , 點選到達 , 關掉重開 , 預約任務仍停在未執行狀態

      * [Download URL](https://rink.hockeyapp.net/apps/282a2bda505648618083db9a25ad986b/app_versions/4)

    3. *Version 1.05.04 (201708101200)*

        **IOS App 正式環境**

        _修正 bug_

        * Fix 副班可能無法承接問題

        * 任務付款完成頁 如果有小費 請 明顯顯示小費欄

        * 反映 於到達頁 倒數時間 9X:XX 分鐘

        * 接單紀錄數字有點龐大 現在點進去都要等

        * DAP17070609166 結帳時閃退

        * (載客中 ...按下手動結束前） 之間 允許顯示10秒預約詢問

        * 按下手動結束 輸入車資前須將車機設為(繁忙)以免任務詢問干擾

        * App 斷讯時或 背景回來 要有 retry 機制

        * 主選單的導航功能 請改為按了沒反應

        * 預約任務執行後 , 點選到達 , 關掉重開 , 預約任務仍停在未執行狀態

        * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/5)

    4. *Version 1.05.06 (201708101800)*

        **IOS App 正式環境**

        _修正 bug_

        * Fix Bug 新增斷線狀態顯示

        * Fix 副班可能無法承接問題

        * 任務付款完成頁 如果有小費 請 明顯顯示小費欄

        * 反映 於到達頁 倒數時間 9X:XX 分鐘

        * 接單紀錄數字有點龐大 現在點進去都要等

        * DAP17070609166 結帳時閃退

        * (載客中 ...按下手動結束前） 之間 允許顯示10秒預約詢問

        * 按下手動結束 輸入車資前須將車機設為(繁忙)以免任務詢問干擾

        * App 斷讯時或 背景回來 要有 retry 機制

        * 主選單的導航功能 請改為按了沒反應

        * 預約任務執行後 , 點選到達 , 關掉重開 , 預約任務仍停在未執行狀態

        * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/6)

    5. *Version 1.06.02 (201708211800)*

        **IOS App 正式環境**

        _修正 bug_

        * 所有地圖中的黑車應該小黃登入要變黃車

        * 選擇以非現金支付 雙平台錯誤訊息UI不一致

        * 正在響(任務詢問時)調整 大小聲、或靜音ON_OFF ，都是下次才會生效

        * 還沒登錄完成任務就叫個不停,當在登入頁

        * 營業= meter on but 接單 = meter off 時間排序

        * 新增任務詢問 多元詢問聲音

        * 結帳時 網路瞬斷 又瞬回 Loading 頁面未 Dismiss

        * 任務承接後 因無預期封包遺失 而造成任務停留在[派車成功]

        * 新增提醒視窗，當金額超過1000元

        * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/7)

    6. *Version 1.07.02 (201709121800)*

        **IOS App 正式環境**

        _修正 bug_

        * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

        * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

        * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

        * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

        * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

        * 反映常常在到達頁手抖 按了到達 就進入載客頁

        * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

        * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

        * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

        * 修正小黃修改個人資料顯示字串為車發處

        * 接單紀錄頁不顯示乘客電話

        * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

        * 串接 6302 多付款別交易

        * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/8)

    7. *Version 1.07.04 (201709131200)*

        **IOS App 正式環境**

        _修正 bug_

        * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

        * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

        * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

        * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

        * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

        * 反映常常在到達頁手抖 按了到達 就進入載客頁

        * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

        * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

        * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

        * 修正小黃修改個人資料顯示字串為車發處

        * 接單紀錄頁不顯示乘客電話

        * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

        * 串接 6302 多付款別交易

        * 隱藏任務詢問頁乘客電話

        * 調整結帳完成 UI 畫面

        * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/9)

    8. *Version 1.07.06 (201709181800)*

        **IOS App 正式環境**

        _修正 bug_

        * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

        * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

        * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

        * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

        * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

        * 反映常常在到達頁手抖 按了到達 就進入載客頁

        * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

        * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

        * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

        * 修正小黃修改個人資料顯示字串為車發處

        * 接單紀錄頁不顯示乘客電話

        * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

        * 串接 6302 多付款別交易

        * 隱藏任務詢問頁乘客電話

        * 調整結帳完成 UI 畫面

        * 到達頁 加上 「開始確定 詢問」以防誤觸進入載客頁

        * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/10)

    9. *Version 1.07.08 (201709291200)*

        **IOS App 正式環境**

        _修正 bug_

        * 到達頁/預約列表，乘客資訊名字與評比中間，要塞入乘客電話

        * 任務被別人接走 頁面需手動關閉 無法自消 會檔住後來的任務詢問

        * 派遣提示聲音修改需求 JobExInfo增加JobPilotId欄位，以識別任務類型

        * 車資提醒視窗，[請確認您輸入的金額是否正確]。應該提示原輸入金額

        * 到達頁 有時需司機手動捲頁面 才看到乘客 姓氏 開車不方便 可否換一下顯示順序

        * 反映常常在到達頁手抖 按了到達 就進入載客頁

        * 載客頁加上 乘客姓氏 手動結束 明顯放大一些Home 往上移

        * 系統下拉通知欄上, 顯示車機狀態; iOS 點選後, 要帶入司機App的畫面

        * 使用OAW 發起預約任務 則開始任務頁 下車地址為 空白

        * 修正小黃修改個人資料顯示字串為車發處

        * 接單紀錄頁不顯示乘客電話

        * 預約列表頁，乘客資訊名字與評比中間，要塞入乘客電話

        * 串接 6302 多付款別交易

        * 隱藏任務詢問頁乘客電話

        * 調整結帳完成 UI 畫面

        * 到達頁 加上 「開始確定 詢問」以防誤觸進入載客頁

        * 更了 ios 11、司機App 架上版 接客任務進行中，車子GPS 不會移動

        * 加入強制定位機制

        * [Download URL](https://rink.hockeyapp.net/apps/942be095eea84eed89dcb0c7aeff7cd5/app_versions/11)

---
* **發版紀錄 (App Store) 正式版**

  1. *Version 1.08 (201709291800)*  

    * iOS 11 地圖定位問題修正

    * 到達頁防呆機制

    * 改善載客頁顯示資訊

    * 調整到達頁顯示資訊順序

    * [Download URL](https://itunes.apple.com/tw/app/55688%E5%8F%B8%E6%A9%9F%E7%89%88/id1190486682?l=zh&mt=8)
