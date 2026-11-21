---
title: "ブログを始めました"
description: "GitHub PagesとJekyllで技術ブログを立ち上げました。記事の書き方のメモも兼ねています。"
tags: [ブログ, GitHubPages]
---

技術ブログを始めました。この記事は、記事の書き方のサンプルも兼ねています。

## 記事の追加方法

`_posts` フォルダに `YYYY-MM-DD-タイトル.md` という名前でファイルを作り、push するだけです。

```markdown
---
title: "記事タイトル"
description: "一覧に表示される概要（省略可）"
tags: [Go, 設計]
---

本文をMarkdownで書きます。
```

## コードのハイライト

コードブロックに言語名を付けると色が付きます。

```python
def fizzbuzz(n: int) -> str:
    if n % 15 == 0:
        return "FizzBuzz"
    if n % 3 == 0:
        return "Fizz"
    if n % 5 == 0:
        return "Buzz"
    return str(n)
```

```bash
git add _posts/
git commit -m "新しい記事を追加"
git push
```

## そのほかの書式

> 引用はこのように表示されます。

| 書式 | 書き方 |
| --- | --- |
| 太字 | `**太字**` |
| インラインコード | `` `code` `` |
| リンク | `[テキスト](URL)` |

- [x] タスクリストも使えます
- [ ] 次の記事を書く
