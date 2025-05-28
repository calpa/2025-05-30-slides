---
theme: dracula
title: Vibe Coding 工作坊 | 生成、部屬、資料庫的 0-1 實戰工作坊
transition: fade
mdc: true
---

<LoadingScene
  title="Vibe Coding 工作坊"
  subtitle="生成、部屬、資料庫的 0-1 實戰工作坊"
  quote="Calpa Liu"
/>

---
layout: center
class: bg-[#172966] text-white font-mono
---

<div class="text-3xl font-bold text-center leading-snug">
 Vibe Coding 實作工作坊|0-1生成並部屬自己的第一個產品
</div>
<div class="text-xs opacity-50">2025-05-30</div>

<div class="text-xs italic opacity-50">Calpa Liu</div>

---
layout: center
class: bg-[#172966] text-white font-mono
---

<div class="text-xl opacity-70 mb-2">你是不是也曾經想過...</div>

<div class="text-2xl sm:text-3xl font-bold leading-snug text-red-400">
  「我有一個點子，<br />但完全不會寫程式該怎麼辦？」
</div>

<div class="text-2xl sm:text-3xl text-green-300 mt-6" v-click>
  今天，我會帶你用 Cursor + Supabase + Zeabur，<br />
  帶你如何不寫一句程式碼也能做出能打開、能操作的產品原型！
</div>

---
layout: two-cols
class: flex flex-col h-full justify-center items-center gap-4
---

## 👋 大家好，我是 Calpa

- 2017 年開始寫程式，一路從全端工程師走到 Web3 領域
- 2025 年開始每天分享技術文章，現在累積已超過 270 篇
- 我用 ChatGPT + Bolt.new 實作過 10+ 個 AI 工具 App
- 喜歡用簡單的方法解釋複雜的技術，也辦過 6 場 AI 實作分享會！

::right::

<img src="https://assets.calpa.me/public/pfp.avif" class="rounded-full w-36 h-36 border-4 border-white shadow-lg" alt="Calpa Liu">

<div class="text-xl font-bold mt-2">Calpa Liu</div>
<div class="text-sm opacity-70">全端工程師 / AI 工具愛好者 / 技術寫作者</div>

---
layout: center
---

## 到底我用 AI 做了什麼？

---
layout: two-cols
class: flex flex-col h-full justify-center items-center
---

## OrbitGO

2025-04-04 ~ 2025-04-06

- 🥈 榮獲 ETHGlobal Taipei 2025 黑客松 1inch 賽道第二名
- 整合 1inch Portfolio API，實作多鏈資產查詢與視覺化介面

<div class="text-blue-400">https://orbitgo.calpa.me/</div>

::right::

![1inch 賽道銀獎](https://assets.calpa.me/ethglobal-taipei-2025-1inch-best-portfolio-tracker.avif)

---
layout: two-cols
layoutClass: gap-4 bg-[#172966]
class: flex flex-col h-full justify-center gap-4 text-white
---

## 技術博客

2017 ~

- 持續分享前端、後端與 Web3 技術文章與實作心得，涵蓋 Astro、React.js、TypeScript 等主題
- 2025 年 3 月中開始每日一篇鐵人賽
- 2017 起累積 276 篇文章

<div class="text-blue-400">https://calpa.me/</div>

::right::

![Calpa 2025 Blog](https://assets.calpa.me/calpa-2025-blog.avif)

---
layout: two-cols
class: flex flex-col h-full justify-center items-center
---

## 紫微斗數排盤系統

2025-05-22 ~

https://calpa.me/tools/ziwei/

::right::

<img src="https://assets.calpa.me/紫微斗數排盤系統.avif" class="w-full my-4 object-contain mx-auto" />


---
layout: center
class: bg-[#172966] text-white
---

# 網站是如何運作的？

---
layout: center
---

## 前端

```mermaid
flowchart LR
    User["<span style='color:white'>🧑‍💻<br>使用者介面<br><span style='font-size:12px'>(內容展示與互動)</span></span>"]
    HTML["<span style='color:white'>📝<br>HTML<br><span style='font-size:12px'>(結構)</span></span>"]
    CSS["<span style='color:white'>🎨<br>CSS<br><span style='font-size:12px'>(樣式)</span></span>"]
    JS["<span style='color:white'>⚡<br>JavaScript<br><span style='font-size:12px'>(互動)</span></span>"]
    User --> HTML
    User --> CSS
    User --> JS

  style User fill:#2563eb,stroke:#60a5fa,stroke-width:2px,color:#fff
  style HTML fill:#fbbf24,stroke:#b45309,stroke-width:2px,color:#fff
  style CSS fill:#059669,stroke:#22d3ee,stroke-width:2px,color:#fff
  style JS fill:#fde68a,stroke:#f59e42,stroke-width:2px,color:#222
```

---
layout: center
---

## 伺服器端

```mermaid
flowchart LR
  USER --> API

  API["API<br>邏輯處理"]
  DB["資料庫<br>資料儲存"]
  Auth["認證<br>使用者管理"]
  API --> DB
  API --> Auth
```

---
class: flex flex-col h-full justify-center items-center gap-4
---

<SDLC />

---
layout: center
class: bg-[#172966] text-white
---

# 現代網頁開發新選擇

---
layout: two-cols
class: flex flex-col h-full justify-center gap-4
---

## Astro

- 現代化的網站開發框架
- 採用「島嶼式」架構，提升效能
- 頁面載入速度極快，體驗流暢
- 支援多種主流前端技術（如 React、Vue 等）

::right::

![Astro](https://cpecbghjua.cloudimg.io/_r2_/homepage/astro_2023_10.png)

---
layout: center
---

## Supabase

- 開放原始碼的雲端資料庫平台
- 提供即時同步功能
- 內建用戶認證與授權
- 提供簡潔易用的 API，方便前後端整合

---
layout: center
---

## Drizzle ORM

- 型別安全的 TypeScript ORM，讓你用程式碼定義資料表結構
- 支援多種資料庫（Postgres、MySQL、SQLite 等）
- 編譯時自動產生 SQL，避免手寫錯誤
- 整合 Migration、Schema、型別推斷，開發更安心

---

## Zeabur

- 現代化的應用程式部署平台
- 支援多種程式語言和框架
- 一鍵部署 GitHub 專案
- 提供免費方案，適合個人專案
- 內建 CI/CD 流程，自動化部署
- 支援自訂網域和 SSL 憑證

---

## 實作示範：建立部落格

1. 建立 Astro 專案
2. 設計資料庫結構
3. 整合 Supabase
4. 實作 CRUD 功能
5. 部署上線

<div class="text-blue-400">讓我們開始吧！</div>

---
layout: center
class: bg-[#172966] text-white
---

# 1. 建立 Astro 專案

```bash
# 建立新專案
npm create astro@latest my-astro-blog

# 進入專案目錄
cd my-astro-blog

# 安裝依賴
npm install

# 啟動開發伺服器
npm run dev
```

---
layout: center
class: bg-[#172966] text-white
---

# 2. 設定 Supabase

1. 前往 [Supabase](https://supabase.com/) 註冊帳號
2. 建立新專案
3. 取得 API 金鑰和專案 URL
4. 安裝 Supabase 客戶端

```bash
npm install @supabase/supabase-js
```

---

## 3. 設計資料庫

```ts
// 使用 Drizzle ORM 定義 posts 資料表
import { pgTable, serial, text, timestamp } from 'drizzle-orm/pg-core'

export const posts = pgTable('posts', {
  id: serial('id').primaryKey(),
  title: text('title').notNull(),
  content: text('content'),
  createdAt: timestamp('created_at', { withTimezone: true }).defaultNow(),
  updatedAt: timestamp('updated_at', { withTimezone: true }).defaultNow(),
})
```

---

## 4. 環境變數設定

在 `.env` 檔案中：

```txt
PUBLIC_SUPABASE_URL=你的專案URL
PUBLIC_SUPABASE_ANON_KEY=你的公開金鑰
```

---
layout: center
class: bg-[#172966] text-white
---

# 5. 實作 CRUD 功能

1. 初始化 Supabase 客戶端
2. 實作文章列表
3. 新增/編輯/刪除文章
4. 即時更新

---
layout: center
class: bg-[#172966] text-white
---

# 6. 部署上線

1. 推送到 GitHub 儲存庫
2. 登入 Zeabur
3. 匯入專案
4. 設定環境變數
5. 部署！

---
layout: center
class: bg-[#172966] text-white
---

# 學習資源

- [Astro 官方文件](https://docs.astro.com/)
- [Supabase 官方文件](https://supabase.com/docs)
- [GitHub 範例專案](https://github.com/yourusername/astro-supabase-blog)
- [我的技術部落格](https://calpa.me/)

---
layout: center
class: bg-[#172966] text-white
---

# Q & A

有任何問題嗎？

---
layout: two-cols
layoutClass: gap-4
class: flex flex-col h-full justify-center gap-4
---

## 接下來的計畫

- 1/6 台北《AI 煉金術》實體分享會

::right::

![Train on Railway at Daytime](https://assets.calpa.me/b-k-HAl6CKxM3xU-unsplash.avif)

---

## 📍 6/1（台北）

《AI 煉金術》實體分享會

- 從靈感到 Side Project，用 AI 工具煉出你的創作流程
- 工具包含 ChatGPT、Firecrawl、Notion
- 分享我從 prompt → 文章 → 產品的完整流程

📅 時間：6/1（週日）15:00 – 18:00

📍 地點：小樹屋｜龍眼 501
- 捷運西門站 3 分鐘
- 台北市萬華區成都路67號5樓之1-501房

🆓 免費參加

📌 報名表單：
👉 https://go.calpa.me/2025-06-01

::right::

<img src="https://assets.thehapp.com/jZOMrUk.jpg" class="w-full my-4 object-contain mx-auto" />
---

## 謝謝大家

<img src="https://assets.calpa.me/感謝您讓我占用的寶貴時間.avif" class="w-2/3 my-4 object-contain mx-auto" />


- 🎯 今天，我們完成了從需求分析到報名系統的一條龍自動化流程
- 📩 有問題歡迎私訊，我會在 Discord 回應大家的提問！
