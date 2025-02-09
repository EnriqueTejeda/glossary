---
title: 継続的デリバリー(CD)
status: Completed
category: コンセプト
tags: ["方法論", "アプリケーション", ""]
---

継続的デリバリー(しばしばCDと略される)は、
コードの変更が自動的に受け入れ環境にデプロイされる
(または継続的デプロイメントの場合、本番環境にデプロイされる)一連の実践を指します。
CDは、ソフトウェアがデプロイメント前に適切にテストされていることを保証する手順を重要視し、
必要と判断された場合に変更をロールバックする方法を提供します。
継続的インテグレーション(CI)は継続的デリバリーに向けた最初のステップです
(つまり、テストやデプロイがされる前に、変更がうまく統合されなければなりません。)

## 解決すべき問題は何ですか

大規模な環境では、[信頼性](/ja/reliability/)の高いアップデートのデプロイが問題となります。
理想的には、エンドユーザーにより良い価値を提供するために、頻繁にデプロイを行いたいところです。
しかし、それを手動で行うと変更ごとに高いトランザクションコストが発生します。
歴史的に、これらのコストを避けるために、組織は頻繁にリリースを行わず、
一度に多くの変更をデプロイしてきましたが、これにより何かが間違ってしまうリスクが高まります。

## どのように役に立つのでしょうか

CD戦略は、完全に自動化された本番環境へのパスを作成し、
[カナリア](/ja/canary-deployment/)や[ブルーグリーン](/ja/blue-green-deployment/)リリースなどの様々なデプロイメント戦略を使用してソフトウェアをテストしデプロイします。
これにより、開発者は頻繁にコードをデプロイすることができ、新しいリビジョンがテストされていることを安心して受け入れることができます。

## 関連する用語はありますか

* [継続的インテグレーション](/ja/continuous-integration/)
* [継続的デプロイメント](/ja/continuous-deployment/)
