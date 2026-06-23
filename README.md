# 体験塾 議事録サイト

はるさー体験塾の運営ミーティング議事録を公開するための静的HTMLサイトです。

## 公開ファイル

- `index.html`: 議事録一覧ページ
- `gijiroku/YYYY-MM-DD.html`: 各回の議事録ページ

## 更新手順

1. 新しい議事録HTMLを `gijiroku/YYYY-MM-DD.html` に追加する。
2. `index.html` に議事録カードを追加する。
3. 最新回だけに `NEW` タグを付ける。
4. GitHubへpushする。
5. GitHub Pagesの公開URLで表示を確認する。

## GitHub Pages

GitHub Pagesでは、リポジトリ直下の `index.html` をトップページとして公開します。
