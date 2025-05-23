# 39揚物送到你家-初音未來主題揚物鋪-前端(非官方)

## 網站特色
結合日/西式炸物販賣與Vocaloid資訊推播功能

## 功能
1. 會員相關：會員登入/註冊/修改基本資料/忘記密碼/google第三方登入/簡訊、電子郵件雙因素驗證
2. 購物相關：商品搜尋/瀏覽商品(每頁顯示25/50/100筆)/加入購物車/送出訂單/選取付款方式(貨到付款/信用卡/門市取付)/外帶或外送/優惠券折扣、集點回饋兌換、儲值金轉換點數/期間限定活動/抽獎(包含卡片收集)/購買vocaloid唱片與線上收聽(用miku點數購買)/小遊戲收集miku點數(簽到、vocaloid音遊)
4. 員工後臺：分店管理/營業額統計(圖表)/指派訂單/員工權限
5. 首頁/導覽頁：商品介紹/新品上市/vocaloid音樂收聽(隨機Vocaloid曲yt連結推播)/vocaloid周邊情報/進網站時隨機從yt、spotify、唱片行的api等串流平台抓一首vocaloid曲播放(在網頁右下角顯示現在播放的歌曲與作詞作曲者與歌手)/最新vocaloid曲情報
6. 使用者體驗相關：程式執行時有讀取畫面，SEO優化

## 技術
### 前端
1. SPA單頁式應用：Vite + Vue3 + Vue routing
2. AJAX
3. Jwt忘記密碼
4. ByCrypt密碼加密儲存
5. Cloudflare：網域託管(抗ddos) + 電子郵件路由 + Pages部署

### 後端
1. .net core 8 Web api
2. 串接綠界金流
3. Python爬蟲
4. azure部署：app service + sql database(sql server)雲端資料庫 + key vault隱藏gmail金鑰等機密資料
5. redis快取

## 後端的github頁面
https://github.com/tohousanae/am3buger-WebApi

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## 參考系統
麥當勞歡樂送、麥當勞app、麥當勞點點卡、SEGA Diva F系列

## 重要聲明
本專案內容為程式交流學習之用，不作為商業用途，，所有素材來源版權歸版權擁有者所有。

## Piapro角色創作規範
https://www.tw-pjsekai.com/news_detail.html?id=6998114598104701697

## 參考引用資料
1. https://pjsekai.fandom.com/zh-tw/wiki/%E5%88%9D%E9%9F%B3%E6%9C%AA%E4%BE%86
2. https://learn.microsoft.com/zh-tw/aspnet/identity/overview/features-api/two-factor-authentication-using-sms-and-email-with-aspnet-identity
3. 資料庫系統 PROJECT 2-歡樂送線上訂餐系統 https://www.mis.nsysu.edu.tw/db-book/DBProject2009Fall/db_98_03/report.ppt

## 模板來源
資展國際
