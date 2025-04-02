# 蟹堡王餐廳線上點餐

## 功能
1. 會員相關：會員登入/註冊/修改基本資料/忘記密碼等
2. 購物相關：瀏覽商品/加入購物車/送出訂單/選取付款方式(實際營運需串接第三方金流)/外帶或外送(選取外送時自動計算當前訂單是否達分店外送門檻，若選擇第三方外送平台外送則會顯示運費)/優惠券等/表演節目(章魚歌舞秀)
3. 員工後臺：分店管理/營業額統計等

## 基本技術
1. Vue.js框架
2. Vite

## 進階技術
1. 忘記密碼用jwt產生token
2. ByCrypt亂數加密+加鹽註冊密碼與token，提高安全性
3. CloudFlare自訂網域+CloudFlare Pages部署網頁前端

## 後端部分

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
## 未來規劃
