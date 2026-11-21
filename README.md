# aestas_kar_studio

GitHub Pages + Jekyll の技術ブログです。

公開URL: https://aestaskar-studio.github.io/aestas_kar_studio/

## 1. 自分の情報に書き換える

- `_config.yml` の `title` / `description` / `author.name` を書き換える
- `about.md` を自分の紹介に書き換える

## 2. GitHub Pagesを有効にする（初回のみ）

リポジトリの **Settings → Pages** で、
Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして保存します。
1〜2分後に公開URLで表示されます。ビルド状況は **Actions** タブか `gh run list` で確認できます。

## 3. 記事を書く

`_posts/YYYY-MM-DD-英数字のスラッグ.md` を作成して push します。

```markdown
---
title: "記事タイトル"
description: "一覧に出る概要（省略可）"
tags: [Go, 設計]
---

本文
```

```powershell
git add .
git commit -m "記事を追加"
git push
```

## ローカルでプレビュー（任意）

Ruby（RubyInstaller for Windows）を入れたうえで:

```powershell
bundle install
bundle exec jekyll serve
```

`http://localhost:4000` で確認できます。
