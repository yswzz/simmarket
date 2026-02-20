# SimMarket

> 一個模擬市場平台，提供前端（Next.js）與後端（Express）完整應用架構。

---

## 專案結構

```
SimMarket/
├── frontend/          # Next.js 前端應用
├── backend/           # Express 後端 API
├── docs/              # 專案文件與說明
├── .env.example       # 環境變數範本
├── .gitignore
└── README.md
```

---

## 快速開始

### 1. 複製環境變數

```bash
cp .env.example .env
```

填入 `.env` 中所需的值。

### 2. 安裝前端依賴

```bash
cd frontend
npm install
npm run dev
```

### 3. 安裝後端依賴

```bash
cd backend
npm install
npm run dev
```

---

## 技術棧

| 層次     | 技術             |
|----------|------------------|
| 前端     | Next.js (React)  |
| 後端     | Express.js       |
| 資料庫   | PostgreSQL        |
| 認證     | JWT              |

---

## 文件

詳細文件請參考 [`/docs`](./docs/) 目錄。
