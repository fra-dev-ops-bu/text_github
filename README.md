[![Gitter](https://badges.gitter.im/fra-dev-ops-bu/community.svg)](https://gitter.im/fra-dev-ops-bu/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![GitHub contributors](https://img.shields.io/github/contributors/fra-dev-ops-bu/githubinar_github.svg)](https://GitHub.com/fra-dev-ops-bu/githubinar_github/graphs/contributors/)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Percentage of issues still open")


# :fish: 水研職員のためのGitHub学習の手引き

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [はじめに](#%E3%81%AF%E3%81%98%E3%82%81%E3%81%AB)
  - [コンセプト](#%E3%82%B3%E3%83%B3%E3%82%BB%E3%83%97%E3%83%88)
  - [学ばないこと](#%E5%AD%A6%E3%81%B0%E3%81%AA%E3%81%84%E3%81%93%E3%81%A8)
- [GitHubを5秒で表現すると？](#github%E3%82%925%E7%A7%92%E3%81%A7%E8%A1%A8%E7%8F%BE%E3%81%99%E3%82%8B%E3%81%A8)
- [絶対にハズせない三大機能](#%E7%B5%B6%E5%AF%BE%E3%81%AB%E3%83%8F%E3%82%BA%E3%81%9B%E3%81%AA%E3%81%84%E4%B8%89%E5%A4%A7%E6%A9%9F%E8%83%BD)
- [仕事をスムーズにすすめるための補助機能](#%E4%BB%95%E4%BA%8B%E3%82%92%E3%82%B9%E3%83%A0%E3%83%BC%E3%82%BA%E3%81%AB%E3%81%99%E3%81%99%E3%82%81%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AE%E8%A3%9C%E5%8A%A9%E6%A9%9F%E8%83%BD)
- [自分のマシンで編集してみよう](#%E8%87%AA%E5%88%86%E3%81%AE%E3%83%9E%E3%82%B7%E3%83%B3%E3%81%A7%E7%B7%A8%E9%9B%86%E3%81%97%E3%81%A6%E3%81%BF%E3%82%88%E3%81%86)
- [水研業務のコンテキストから見たGitHub](#%E6%B0%B4%E7%A0%94%E6%A5%AD%E5%8B%99%E3%81%AE%E3%82%B3%E3%83%B3%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E3%81%8B%E3%82%89%E8%A6%8B%E3%81%9Fgithub)
- [読者の感想](#%E8%AA%AD%E8%80%85%E3%81%AE%E6%84%9F%E6%83%B3)
- [Appendix](#appendix)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

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
いちばん重要な機能はバージョン管理ですが、ここでは簡単な順に学んでいきましょう。

### Issueを立ててみよう
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
