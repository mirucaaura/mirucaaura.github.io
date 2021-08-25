---
title: "How to Use"
description: Introduction the usage of hugo
date: 2021-08-24T18:38:29+09:00
draft: false
katex: math
---

`hugo` はインストール済みであると仮定して話を進める．

1. `hugo new site <the name of site>`
1. `git init`
1. `git submodule add https://github.com/MeiK2333/github-style.git themes/github-style`
1. `cp -r ./themes/github-style/layouts/* ./layouts/`
1. `cp -r themes/github-style/static/* static/`
1. `hugo new post/first-article.md`
1. edit `config.toml`
1. `hugo`

オプション

- activate KaTeX (Ref: https://blog.atusy.net/2019/05/09/katex-in-hugo/)