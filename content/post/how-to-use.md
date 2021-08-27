---
title: "How to Use"
description: Introduction the usage of hugo
date: 2021-08-24T18:38:29+09:00
tags: ["memo"]
draft: false
katex: math
---

本稿では，以下の環境で静的サイトジェネレータ[Hugo](https://gohugo.io/)の使い方について簡単に述べる．

### Environment

- Ubuntu 20.04 LTS

### Install Hugo

- [Install Hugo](https://gohugo.io/getting-started/installing/)

### Usage

1. `hugo new site <the name of site>`
1. `git init`
1. `git submodule add https://github.com/MeiK2333/github-style.git themes/github-style`
1. `cp -r ./themes/github-style/layouts/* ./layouts/`
1. `cp -r themes/github-style/static/* static/`
1. `hugo new post/first-article.md`
1. edit `config.toml`
1. `hugo server`
1. `hugo`
1. `git add, commit, and push to the remote repository`

### KaTeX

- activate KaTeX (Ref: https://blog.atusy.net/2019/05/09/katex-in-hugo/)

### Refferences

- [Hugoテーマのカスタマイズ箇所メモ](https://suihan74.github.io/posts/2019/12_26_00_theme_customize/)