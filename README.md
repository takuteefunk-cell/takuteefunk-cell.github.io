# Taku's Music Life

阿部拓也 公式サイト。プレーンなHTML/CSS/JSで構成された静的サイト（ビルド不要）。

## 構成
- `index.html` — HOME
- `biography.html` — プロフィール
- `schedule.html` — 直近の出演スケジュール
- `schedule-archive.html` — 2019〜2024年の出演実績アーカイブ
- `works.html` — ディスコグラフィー
- `gallery.html` — 写真ギャラリー
- `movies.html` — 動画
- `music.html` — 活動中のプロジェクト紹介
- `contact.html` — お問い合わせ（Googleフォーム埋め込み）
- `styles.css` / `script.js` — 共通スタイル・スクリプト
- `images/` — 画像素材

## ローカルプレビュー
```
python3 -m http.server 8420
```
その後 `http://localhost:8420` を開く。

## 公開（GitHub Pages）
1. GitHubにリポジトリを作成
2. このフォルダの内容をpush
3. リポジトリの Settings → Pages で公開ブランチを設定
