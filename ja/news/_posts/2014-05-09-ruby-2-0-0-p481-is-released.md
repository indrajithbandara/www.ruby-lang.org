---
layout: news_post
title: "Ruby 2.0.0-p481 リリース"
author: "usa"
translator:
date: 2014-05-09 03:00:00 +0000
lang: ja
---

Ruby 2.0.0-p481 がリリースされました。

今回のリリースには、多数のバグ修正が含まれています。例としては、

* Readline-6.3 サポート
* 古い OpenSSL での問題の修正 (p451 でのリグレッション)
* 同梱されている libyaml の更新 (詳細は[YAML の URI エスケープ処理におけるヒープオーバーフローについて (CVE-2014-2525)](https://www.ruby-lang.org/ja/news/2014/03/29/heap-overflow-in-yaml-uri-escape-parsing-cve-2014-2525/)を参照)

などがあります。

詳しくは、対応する[チケット](https://bugs.ruby-lang.org/projects/ruby-200/issues?set_filter=1&amp;status_id=5)および [ChangeLog](http://svn.ruby-lang.org/repos/ruby/tags/v2_0_0_481/ChangeLog) を確認して下さい。

## ダウンロード

* [https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p481.tar.bz2](https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p481.tar.bz2)

      SIZE:   10727244 bytes
      MD5:    ea406a8d415a1a5d8365596d4288f3da
      SHA256: 0762dad7e96d8091bdf33b3e3176c2066fbf3dc09dfe85fbf40e74e83c63d8e2

* [https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p481.tar.gz](https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p481.tar.gz)

      SIZE:   13586757 bytes
      MD5:    3913e0ad6cc572b7358e4c6a8c4b2551
      SHA256: 00dd3d72435eb77f2bd94537c1738e5219ca42b6d68df3d4f20c183f4bd12d0f

* [https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p481.zip](https://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p481.zip)

      SIZE:   15101944 bytes
      MD5:    1cdf06d1a58f3103e9ed7e072d680b19
      SHA256: 7457cdfac36cefcb0721b0520371939926fa755759631c90dd91e64e986eb23d

## リリースコメント

無事に今回のリリースを迎えられたのは、Ruby を応援してくださる皆さんのおかげです。
ありがとうございました。
