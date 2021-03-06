# Ch5 需求模型

## 5-1 使用者需求

* 表 5-1-1 功能需求表  

| 功能需求名稱       | 描述                                                                                     |
| ------------------ | ---------------------------------------------------------------------------------------- |
| 訪客註冊會員       | 使用者透過填寫名片資料註冊會員                                                           |
| 會員可進行登入     | 會員使用ID登入                                                  |
| 會員查看個人檔案   | 使用者可查看自己的資料，若有問題可修改                                                   |
| 會員修改個人資料   |會員可直接修改自己的資料，修改後能夠同步修改好友瀏覽到的資料                 |
| 會員搜尋使用者     | 會員透過藍牙功能搜尋附近未加入好友的會員           |
| 會員可加入好友     | 選擇尚未加入好友的會員新增好友，好友接受配對即成為好友                        |
| 會員可管理好友     | 會員可藉由分類，更迅速、清楚的瀏覽好友列表，並透過編輯好友簡歷、備註建構該名好友之資料、輪廓，以更了解該名好友 |
| 會員可查看與各好友之間的時間軸 | 當好友雙方見面時，會將兩人見面的時間和地點記錄至時間軸，且會員參與的活動會自動新增至時間軸    |
| 會員可管理活動內容 | 會員可建立、編輯活動內容                       |
| 會員可回饋系統問題 | 若會員於使用系統上有問題、想要回饋，使用者可傳送資訊給開發者         |
| 管理者追蹤問題    | 會員提供的問題，管理者可陸續追蹤問題狀態(是否解決此問題等……) |

* 表 5-1-2 非功能性需求表  

| 作業系統 | android 7 以上              |
| -------- | --------------------------- |
| 裝置需求 | 藍芽、Wi-Fi、3G/4G 行動網路 |
| 相容性   | 支援各種螢幕尺寸            |
| 易使用性 | 系統介面簡單清晰且容易理解  |
| 安全性 | 攸關個人隱私，密碼需要有一定的安全性限制，同時間不能有重複登入情形|

## 5-2 使用個案圖(Use case diagram)

![](https://i.imgur.com/8WinhuI.png)   
圖 5-2-1 使用案例圖

## 5-3 	使用個案描述：使用活動圖(Activity diagram)

![](https://i.imgur.com/NFVHGV0.png)  
圖 5-3-1 註冊活動圖

![](https://i.imgur.com/zepLRAq.png)  
圖 5-3-2 登入活動圖

![](https://i.imgur.com/qZESLja.png)  
圖 5-3-3 修改個人資料活動圖

![](https://i.imgur.com/qZESLja.png)
圖 5-3-4 加入好友活動圖

![](https://i.imgur.com/dAu9lNl.png)
圖 5-3-5 查看好友資料活動圖

![](https://i.imgur.com/LI6Itmi.png)
圖 5-3-6 編輯好友資料活動圖

![](https://i.imgur.com/WvjAqI4.png)
圖 5-3-7 活動建立者新增活動活動圖

![](https://i.imgur.com/TUlOGn6.png)
圖 5-3-8 活動參與者參與活動活動圖

![](https://i.imgur.com/oBi4I60.png)
圖5-3-9附近好友通知活動圖

![](https://i.imgur.com/6sR2tNZ.png)
圖5-3-10會員回報問題活動圖

![](https://i.imgur.com/G9QKL6C.png)
圖5-3-11管理者查看問題活動圖

## 5-4 	分析類別圖(Analysis class diagram)

![](https://i.imgur.com/WFtQl8E.png) 
圖 5-4-1 系統分析類別圖



