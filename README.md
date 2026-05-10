# 2026 全方位人生跳級課 ✦ 莫子

趨勢 × 能量 × 運勢 · 丙午赤馬年完整互動網站

---

## 🚀 上架步驟（10分鐘完成）

### 方法一：Vercel（最推薦）

**第一步：安裝依賴並測試**
```bash
npm install
npm run dev
```
打開瀏覽器 `http://localhost:5173` 確認畫面正常

**第二步：上傳到 GitHub**
1. 去 [github.com](https://github.com) 建立新 Repository（例如 `2026course`）
2. 在這個資料夾執行：
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/你的帳號/2026course.git
git push -u origin main
```

**第三步：部署到 Vercel**
1. 去 [vercel.com](https://vercel.com) 用 GitHub 帳號登入
2. 點「Add New Project」
3. 選擇你的 `2026course` repository
4. Framework 選 **Vite**，其他設定不用改
5. 點「Deploy」→ 等約 1 分鐘
6. 完成！得到網址 `https://2026course.vercel.app`

---

### 方法二：本機直接打包（不需要 GitHub）

```bash
npm install
npm run build
```
產生 `dist/` 資料夾，直接拖曳到 [Netlify Drop](https://app.netlify.com/drop) 即可上線

---

## 📁 檔案結構

```
2026course/
├── index.html          # 主 HTML 入口
├── vite.config.js      # Vite 設定
├── package.json        # 依賴套件
├── vercel.json         # Vercel 路由設定
├── public/
│   └── favicon.svg     # 網站圖示（馬字）
└── src/
    ├── main.jsx        # React 入口
    └── App.jsx         # 主程式（所有頁面都在這）
```

---

## 🌐 功能說明

- **首頁** — 赤馬年英雄區塊 + 四大入口
- **課程全文** — 五章完整講義，可展開閱讀
- **生肖運勢** — 12生肖點選，金錢桃花健康事業詳解
- **每日抽牌** — 8張宇宙能量牌，翻牌動畫
- **太歲全解** — 值冲刑破害完整攻略
- **提醒設定** — 三個每日能量功課開關
- **三語切換** — 繁中 / 簡中 / English

---

作者：莫子 · 2026丙午赤馬年
