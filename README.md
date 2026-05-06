# kazunari-kamata.github.io

GitHub Pages で公開する技術ポートフォリオサイトです。

## 公開URL

https://kazunari-kamata.github.io/

## 目的

公開リポジトリで作成した技術成果物を整理し、インフラ運用、EOL対応、基盤更改、検証、運用改善に関する取り組みを掲載します。

## 掲載内容

- プロフィール概要
- 技術領域
- 公開プロジェクト一覧
- `infra-lifecycle-portal` の紹介
- GitHub リポジトリへのリンク

## 代表プロジェクト

### Infra Lifecycle Portal

インフラ資産の EOL リスク、移行優先度、検証観点、ロールバック手順を整理するための軽量なライフサイクル管理ツールです。

Repository:

https://github.com/kazunari-kamata/infra-lifecycle-portal

主な特徴:

- YAML 形式のインベントリ読み込み
- OS / ミドルウェア / ランタイムの EOL リスク検出
- HIGH / MEDIUM / LOW / INFO によるリスク分類
- Markdown 形式のレポート生成
- FastAPI による診断 API
- React + TypeScript による簡易ダッシュボード
- GitHub Actions による自動テスト

## ローカル確認

静的 HTML のため、ブラウザで `index.html` を開いて確認できます。

Python を使ってローカルサーバーを起動する場合:

    python -m http.server 8000

ブラウザで以下を開きます。

    http://localhost:8000

## ディレクトリ構成

    .
    ├── README.md
    ├── index.html
    ├── script.js
    ├── style.css
    └── assets/
        └── screenshots/
            └── .gitkeep

## 運用方針

- 公開リポジトリのみ掲載対象とします。
- private repository は掲載対象外とします。
- 架空の導入実績や誇張表現は記載しません。
- ローカル環境固有のパスは記載しません。
