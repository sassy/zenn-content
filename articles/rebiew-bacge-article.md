---
title: "Review BadgeというChrome拡張機能を作りました"
emoji: "🌟"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["Chrome", "DevTools", "extension"]
published: true
---

Review BadgeというGoogle Chromeの拡張機能を作りました。

# 作ったもの

https://chrome.google.com/webstore/detail/review-badge/kiepclhakcefkflamflnjbfogmfamoal?hl=ja

GitHub上でレビューコメントの先頭にどんなコメントかをバッジで挿入できます。
`!r` でどんなバッジか選択し、挿入可能です。

![スナップショット](https://storage.googleapis.com/zenn-user-upload/6a812155dce9-20220222.png)

# なぜ作ったのか

コードレビューをするときの、そのコメントがどのような意図なのかを最初にバッジで示したかったからです。

下記の記事のように必ず直して欲しいときは "must", 自分が思うけど直さなくてもいいときは "imo" とかをつけたかったからです。
そこでバッジのように ![badge](https://img.shields.io/badge/review-must-red.svg) としたほうがかっこいいし、
先頭につける項目はなんだっけ？ というのを思い出しやすくしたかったからです。
特にimo(in my opinion: 自分だったらこうする) とか nits(めちゃくちゃ細かい指摘)とか忘れがちだったからです。

# 機能追加や提案があればIssueやPRをください！

以下のリポジトリに改善点とかあればissueをあげてください。
PRも大歓迎です。大したコードではないです。
Starつけてくれると喜びます。

https://github.com/sassy/review-badge-crx

