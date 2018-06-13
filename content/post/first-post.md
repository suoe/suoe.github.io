---
title: "ブログを始める"
date: 2018-06-12T19:00:26+09:00
draft: true
tags: [website]
---

Hello Hugo!!
===

[Hakyll](https://jaspervdj.be/hakyll/) を使ってブログを始めてみようという気分になった。

しかし stack さんの挙動が全然わからない上にあまり良さげなテーマがなかったので Hugo を使うことにした。

手順
=====

Arch Linux を使用
### 導入

```
sudo pacman -S hugo
```
でインストール

### テーマ
[Hugo Themes](https://themes.gohugo.io/) に色々あった。今回は
[Beautiful Hugo](https://themes.gohugo.io/beautifulhugo/) を選んだ。きれい。

### 設定
beautifulhugo/examplesite にあったものを少し変えて使っている。

### GitHub Pages
source ブランチで記事を書いて、
```
hugo
```
とすると blog_root/public 以下にビルドされるのでそれを master にプッシュしている。
