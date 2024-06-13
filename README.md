# 全名 : 轉珠遊戲專案 sideproject
<b>因為負責前端整合的人沒整合完，所以push一個自己更新後的專案上來<br>
Vue前端-放在ProjectB資料夾裡<br>
Laravel後台管理-放在back-laravel資料夾裡<br>
<br>
## 注意! docker伺服器啟動後需要一些時間連上Vue和Laravel，出現連線錯誤請再試一次

<br>

# 整個專案和分支網址
整個專案 : https://github.com/jiunfeng/ProjectB

分支 : https://github.com/hsd325/ProjectB
<br><br>

# 安裝步驟
## Vue、docker安裝和啟動
1.需安裝node.js、docker<br><br>
2.執行docker<br><br>
3.在ProjectB\vue-main執行【npm i】
![螢幕擷取畫面 (279)](https://github.com/hsd325/ProjectB-new/assets/100175482/07480a67-845d-4293-846f-e11d354bf73f)

4.在ProjectB執行【docker compose build】
![螢幕擷取畫面 (280)](https://github.com/hsd325/ProjectB-new/assets/100175482/69f10d8d-970c-4d26-92ac-69346e46d5cc)

5.在ProjectB執行【docker compose up -d】，啟動docker伺服器
![螢幕擷取畫面 (284)](https://github.com/hsd325/ProjectB-new/assets/100175482/49074b15-cc0b-42e9-86a7-3aad63ee89f5)


6.在ProjectB\vue-main執行【npm run dev】，啟動vue
![螢幕擷取畫面 (281)](https://github.com/hsd325/ProjectB-new/assets/100175482/27c33399-1d96-4b21-9ba6-9687dac72f6e)

## Laravel安裝和啟動
1.需安裝composer<br><br>
2.在back-laravel執行【composer i】和【npm i】
![螢幕擷取畫面 (282)](https://github.com/hsd325/ProjectB-new/assets/100175482/ec99b54f-3dad-4acd-bb44-8f8660395eee)

3.在back-laravel執行【cp .env.example .env】，製造出【.evn】
![螢幕擷取畫面 (286)](https://github.com/hsd325/ProjectB-new/assets/100175482/58903931-08d6-43fa-a07b-739fc96ad3a9)

4.在back-laravel執行【php artisan serve】，啟動Laravel
![螢幕擷取畫面 (283)](https://github.com/hsd325/ProjectB-new/assets/100175482/43d7d2cb-029d-4f84-9cd3-4451e9eda25a)

# 負責項目
## Vue前端負責項目
1.登入畫面和登入js使用(js為別的組員做的)
![螢幕擷取畫面 (275)](https://github.com/hsd325/ProjectB-new/assets/100175482/3de6eaff-2cea-4dc7-92be-ed5c74fcdfe1)

2.註冊畫面和註冊js使用(js為別的組員做的)，警告視窗使用sweetalert2完成
![螢幕擷取畫面 (274)](https://github.com/hsd325/ProjectB-new/assets/100175482/c3441a28-353b-4886-9ca2-4e119357ac95)

3.主畫面和資料庫抓取js使用(js為別的組員做的)，跳轉按鈕-戰鬥、BOX
![螢幕擷取畫面 (276)](https://github.com/hsd325/ProjectB-new/assets/100175482/869ff601-f830-4e7a-b763-4d3086825388)

4.可換主頁背景角色
![螢幕擷取畫面 (277)](https://github.com/hsd325/ProjectB-new/assets/100175482/69aa2284-317a-4dfe-82c8-1b20385f87b6)

5.可更換頭象
![螢幕擷取畫面 (278)](https://github.com/hsd325/ProjectB-new/assets/100175482/68486040-ae2e-4084-8d0f-aa66bb35a424)

## Laravel 後端管理系統，全部由我製作完成
1.可新增、刪除、更新
![螢幕擷取畫面 (267)](https://github.com/hsd325/ProjectB/assets/100175482/3c45be8c-70a8-4764-b277-a02dcab97ad7)

<br>

2.更改畫面
![螢幕擷取畫面 (268)](https://github.com/hsd325/ProjectB/assets/100175482/141013e1-448d-466c-b310-1d9aa94de621)

<br><br>
3.持有角色、隊伍勾選剩最後一個會鎖定，避免出BUG<br><br>
持有角色
![螢幕擷取畫面 (272)](https://github.com/hsd325/ProjectB/assets/100175482/cd116dae-de69-4607-b640-129ba0a01204)

隊伍
![螢幕擷取畫面 (273)](https://github.com/hsd325/ProjectB/assets/100175482/0f67e683-d30b-4447-bcaf-bbc3102e0a28)

# 專案技術
- GitHub 分支和上傳功能
- Vue 3
- Bootstrap v5.2.3
- jQuery v1.5.1
- sweetalert2.js
- Laravel 8
- Composer V2.7.6


