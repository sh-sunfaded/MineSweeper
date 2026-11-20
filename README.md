# MineSweeper

## 概要

- React 19 + TypeScript + Vite 製のマインスイーパー
- wrangler / @cloudflare/vite-plugin によるCloudflareデプロイに対応

## 必要環境

- Node.js

## セットアップ

```sh
npm ci
```

## 使い方

```sh
npm run dev      # 開発サーバー(vite)
npm run build    # 型検査(tsc -b)+ビルド
npm run lint     # oxlint
npm run preview  # ビルド後、wrangler dev でプレビュー
npm run deploy   # ビルド後、Cloudflare へデプロイ
```

## ライセンス

未設定。
