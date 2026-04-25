# Shigekazu Yuasa Portfolio

静的HTML/CSS/JSで作成した公開用ポートフォリオです。

## Files

- `index.html`: ページ本体
- `styles.css`: デザイン
- `script.js`: スクロール演出
- `favicon.svg`: タブ・ブックマーク用アイコン
- `site.webmanifest`: PWA/テーマカラー設定
- `assets/portrait-retouched.png`: 加工済みプロフィール写真
- `assets/Shigekazu-Yuasa-CV.docx`: 職務経歴書
- `.nojekyll`: GitHub Pages 用補助ファイル

## Before Publish

`index.html` 内の以下を差し替えてください。

- `mailto:your-email@example.com`
- 必要なら氏名の英字表記
- 必要ならSNSやLinkedInのURL

## Deploy

### GitHub Pages

1. このフォルダをGitHubリポジトリに push
2. GitHub の `Settings > Pages` を開く
3. `Deploy from a branch` を選ぶ
4. Branch に `main`、Folder に `/ (root)` を指定

### Vercel

1. Vercel にリポジトリを import
2. Framework Preset は `Other`
3. Build Command は空欄
4. Output Directory は空欄のままで公開可能

## Notes

- Open Graph 用画像は現在 `assets/portrait-retouched.png` を利用しています
- 独自ドメインで公開する場合は、`og:image` を絶対URLに変更すると共有表示が安定します
