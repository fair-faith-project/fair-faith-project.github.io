# Fair Faith JP

[![Publish Site](https://github.com/fair-faith-project/fair-faith-project.github.io/actions/workflows/publish.yml/badge.svg)](https://github.com/fair-faith-project/fair-faith-project.github.io/actions/workflows/publish.yml)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/fair-faith-project/fair-faith-project.github.io)](https://github.com/fair-faith-project/fair-faith-project.github.io/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<div align="center">
  <img src="docs/assets/logo.svg" width="120" alt="Fair Faith JP Logo">
  <h3>信仰に確かな安全と責任を。<br>現代社会のバグから身を守るための信仰安全基準プロトコル。</h3>
</div>

**信仰に確かな安全と責任を。**
現代社会における「信仰のバグ（脆弱性）」から人々を守るための、オープンソースの安全基準プロトコルとナレッジベースです。

🔗 **公式サイト:** [https://fair-faith.org/](https://fair-faith.org/)

## 📖 プロジェクト概要 (Overview)

Fair Faith Project は、信仰や宗教組織が持つ構造的なリスクを「技術的負債」や「バグ」として捉え直し、エンジニアリングのアプローチで解決を試みるプロジェクトです。

特定の宗教を批判・推奨するものではなく、あらゆる組織が健全に運営されるための **「ISO規格」や「RFC（通信規約）」のような共通プロトコル** を策定・公開しています。

### 主なコンテンツ
* **安全基準 (Standards):** 組織が遵守すべき透明性・ガバナンスのガイドライン (RFC like protocols)。
* **宗教用語翻訳辞典 (Dictionary):** 内部用語（ジャーゴン）を一般社会の言葉に翻訳・定義。

## 🤝 行動規範 (Code of Conduct)

本プロジェクトは、多様性を尊重し、誰もが心理的安全性を持って参加できるコミュニティを目指しています。
私たちは **Contributor Covenant v2.1** を公式に採用しています。

* [行動規範 (日本語版)](CODE_OF_CONDUCT_ja.md)
* [Code of Conduct (English)](CODE_OF_CONDUCT.md)

違反報告や懸念事項がある場合は、行動規範内に記載された連絡先までご報告ください。

## 🛠 技術スタック (Tech Stack)

このサイトは、以下のモダンな静的サイトジェネレーター技術によって構築・運用されています。

* **Framework:** [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
* **Hosting:** GitHub Pages
* **CI/CD:** GitHub Actions
* **Features:**
    * SPA (Single Page Application) ライクな高速遷移
    * 完全レスポンシブデザイン (Mobile Optimized)
    * 自動OGP画像生成 (Auto Social Cards with Noto Sans JP)
    * SEO最適化済み

## 💻 開発・貢献ガイド (Development)

Issueの報告やPull Requestはいつでも歓迎します。
ローカル環境でサイトをプレビューするには、以下の手順を実行してください。

### 前提条件 (Prerequisites)
* Python 3.x
* git

### セットアップ (Setup)

```bash
# リポジトリのクローン
git clone https://github.com/fair-faith-project/fair-faith-project.github.io.git
cd fair-faith-project.github.io

# 依存関係のインストール (画像生成ライブラリ含む)
pip install -r requirements.txt
