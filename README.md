[![Gitter](https://badges.gitter.im/fra-dev-ops-bu/community.svg)](https://gitter.im/fra-dev-ops-bu/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![GitHub contributors](https://img.shields.io/github/contributors/fra-dev-ops-bu/githubinar_github.svg)](https://GitHub.com/fra-dev-ops-bu/githubinar_github/graphs/contributors/)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Percentage of issues still open")


# :fish: 水研職員のためのGitHub学習の手引き

<!-- START doctoc -->
<!-- END doctoc -->

## はじめに

### コンセプト
:tada: さぁ、:octocat:GitHubを学びましょう！ :tada:

ただし、講師から習うのではありません :no_good:
学習の手引きを読み、不明点は[Issue](https://github.com/fra-dev-ops-bu/githubinar_github/issues/new)として運営に投げてみましょう。
[Pull Request](https://github.com/fra-dev-ops-bu/githubinar_github/compare)による変更の提案も大歓迎てす。
この学びかた自体がもはや共同開発です。

> 「ここまで読んだだけで既に知らない用語がある...」> :cry:

:man_dancing: <大丈夫。下の方で解説されているはずです。解説に不備があったら、[ここ](https://github.com/fra-dev-ops-bu/githubinar_github/issues/new)から教えてください。

### 学ばないこと

ここでは、GitHubの使い方に集中するため、まずブラウザ上でGitHubを操作することからはじめます。
途中から、Gitコマンドも登場しますが、
最低限で済むように工夫してあります<sup>[1](#gitcommand)</sup>




そもそも、GitHubとGitはどのような関係にあるのでしょうか。
これを理解するには、GitHubが車、Gitをエンジンに例えるとよいでしょう。
エンジンを意識せずとも、車を運転することはできます。
もちろん、Gitの強力なコマンドたちは、日常業務の大きな助けとなります。
興味のある方は [GitHubinar of Git](https://github.com/fra-dev-ops-bu/githubinar_git)にご参加ください。

<hr>

## GitHubを5秒で表現すると？

チームプレーに必要な全てが詰まったナレッジベースです。

## 絶対にハズせない三大機能

GitHubにはたくさんの機能がありますが、特に重要な機能は3つ&mdash;
「バージョン管理」「Issue」「Pull Request」です<sup>[2](#bigthree)</sup>。
Issueを立てるのは簡単です。
`g i`（Go to Issue）そして`c`（Create）とタイプするだけです。
Issueとは何かの説明をしていませんでした。
Issueとは、プロジェクトの課題をID管理するための機能です。
課題にはどのようなものがあるかというと:

- バグ報告
- ユーザーからの機能追加などの要望
- 開発者が認識している內部の改善案

ほかには...?
うーん、思いつかないので[Issue](https://github.com/fra-dev-ops-bu/githubinar_github/issues/8)にしておきます。

さて、Issueを使うと、なにかよいことがあるのでしょうか。
まず、Issue番号を使うことで、課題を指す時に誤解がありませんし、URLリンクが使えるようになります。

Issueの検索機能（`Ctrl` + `/`）を使うことで、このプロジェクトに過去にどのような問題があったのかを調べることができます。
また、「いつ」「誰が」「どんな方法で」解決したのかを検索できるようになります。
たとえばこのリポジトリでは、

では、Issueは少ない方かいいのでしょうか。


ごめんなさい、少し先走ってしまいました。
これらを知るためには、バージョン管理を学ぶ必要がありました。

## バージョン管理をしてみよう

## Pull Requestをしてみよう

## 仕事をスムーズにすすめるための補助機能
  - ブランチ
  - fork
  - merge
  - Issue駆動開発
  - History
  - Blame
## 自分のマシンで編集してみよう
  - Gitの環境構築
  - クリックでやっていたことをコマンドでやってみよう
  - コラム: GitHubとGitの関係は？ 
## 水研業務のコンテキストから見たGitHub
## 読者の感想
## Appendix
  - 参考サイト
  - さらなる学びのために

<a name="gitcommand">1</a>: git (reset|revert|rebase|stash|cherry-pick|bisect)は割愛します

<a name="bigthree">2</a>: 車の運転でいえば「アクセル」「ブレーキ」「ハンドル操作」といったところでしょうか。
