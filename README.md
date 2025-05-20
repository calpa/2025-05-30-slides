# Vibe Coding 工作坊投影片

「生成、部屬、資料庫的 0-1 實戰工作坊」投影片專案，使用 Slidev 建置。

## 技術棧

- [Slidev](https://sli.dev/) - 網頁投影片工具
- [Astro](https://astro.build/) - 現代化網站開發框架
- [Supabase](https://supabase.com/) - 開源後端即服務
- [Drizzle ORM](https://orm.drizzle.team/) - 型別安全的 TypeScript ORM

## 開發環境

### 必要環境

- Node.js 18+
- pnpm 8+

### 安裝依賴

```bash
pnpm install
```

### 本地開發

```bash
pnpm dev
```

開啟瀏覽器訪問 [http://localhost:3030](http://localhost:3030)

### 建置靜態檔案

```bash
pnpm build
```

建置完成的檔案會輸出到 `dist` 目錄

## 部署

### 靜態網站部署

1. 建置靜態檔案
   ```bash
   pnpm build
   ```

2. 部署 `dist` 目錄到靜態網站託管服務（如 Vercel、Netlify、GitHub Pages 等）

### Zeabur 部署

1. 將專案推送到 GitHub 儲存庫
2. 登入 [Zeabur](https://zeabur.com/)
3. 點選「New Project」
4. 選擇「Deploy from Git」
5. 選擇你的 GitHub 儲存庫
6. 設定建置指令：`pnpm build`
7. 設定輸出目錄：`dist`
8. 點選「Deploy」

## 授權

MIT
