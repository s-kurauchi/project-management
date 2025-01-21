# Project Management Application

シンプルで使いやすいプロジェクト管理アプリケーションです。

## 機能

- 📋 プロジェクト一覧の表示・管理
- ✅ タスクの作成・編集・削除
- 👥 チームメンバーの管理
- 📊 プロジェクトの進捗管理
- 🔒 TypeScript 採用による型安全性
- 🎨 モダンな UI デザイン

## 技術スタック

- React + TypeScript
- React Router
- Material UI (MUI)
- Vite

## 開発環境のセットアップ

### 必要要件

- Node.js 18.0.0 以上
- npm 9.0.0 以上

### インストール

```bash
npm install
```

### 開発サーバーの起動

```bash
npm run dev
```

アプリケーションは `http://localhost:5173` で利用できます。

## ビルドと本番環境

本番用ビルドの作成:

```bash
npm run build
```

## Docker 環境

Docker を使用して環境を構築する場合:

```bash
# イメージのビルド
docker build -t project-management .

# コンテナの起動
docker run -p 3000:3000 project-management
```

---

Made with ❤️ by Your Team
