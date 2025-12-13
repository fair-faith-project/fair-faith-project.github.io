# Fair Faith JP (FFJP)

<div align="center">
  <img src="docs/assets/logo.svg" width="120" alt="Fair Faith JP Logo">
  <h3>信仰に確かな安全と責任を。<br>現代社会のバグから身を守るための信仰安全基準プロトコル。</h3>
  
  <p>
    <a href="https://fair-faith.org">
      <img src="https://img.shields.io/badge/Official_Site-fair--faith.org-1a237e?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
    </a>
    <a href="https://github.com/fair-faith-project/fair-faith-project.github.io/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
    </a>
  </p>
</div>

---

## 📜 プロジェクト概要 (Overview)

**Fair Faith JP (FFJP)** は、信仰の自由を尊重しつつ、現代社会における「宗教組織の暴走（バグ）」から個人の尊厳と生活を守るための**安全基準プロトコル**を策定・発信するプロジェクトです。

本リポジトリは、公式ドキュメントサイト [fair-faith.org](https://fair-faith.org) のソースコードおよびコンテンツを管理しています。

### 主な提言
1.  **未成年保護** (Protection of Minors)
2.  **無限責任** (Unlimited Liability)
3.  **相互扶助** (Mutual Aid)

## 🔗 公式メディア (Official Media)

なりすまし防止のため、以下のIDのみを公式として運用しています。

| Platform | Account | Link |
| :--- | :--- | :--- |
| **Website** | fair-faith.org | [Official Site](https://fair-faith.org) |
| **Note** | @fairfaithjp | [note.com/fairfaithjp](https://note.com/fairfaithjp) |
| **X (Twitter)** | @fairfaithjp | [x.com/fairfaithjp](https://x.com/fairfaithjp) |
| **Instagram** | @fairfaithjp | [instagram.com/fairfaithjp](https://www.instagram.com/fairfaithjp/) |
| **Threads** | @fairfaithjp | [threads.com/@fairfaithjp](https://www.threads.com/@fairfaithjp) |
| **YouTube** | @FairFaithJP | [youtube.com/@FairFaithJP](https://www.youtube.com/@FairFaithJP) |
| **TikTok** | @fairfaithjp | [tiktok.com/@fairfaithjp](https://www.tiktok.com/@fairfaithjp) |

## 🛠 技術スタック (Tech Stack)

このプロジェクトは、静的サイトジェネレーター **MkDocs** と、マテリアルデザインテーマを用いて構築されています。

-   **Core:** [MkDocs](https://www.mkdocs.org/)
-   **Theme:** [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
-   **Hosting:** GitHub Pages
-   **Domain:** fair-faith.org
-   **Analytics:** Google Analytics 4 (GA4)

## 🚀 開発環境 (Development)

ローカル環境でプレビューを行う場合は、以下の手順で実行可能です。

```bash
# 1. リポジトリのクローン
git clone [https://github.com/fair-faith-project/fair-faith-project.github.io.git](https://github.com/fair-faith-project/fair-faith-project.github.io.git)
cd fair-faith-project.github.io

# 2. 依存関係のインストール
pip install mkdocs-material

# 3. ローカルサーバーの起動
mkdocs serve
