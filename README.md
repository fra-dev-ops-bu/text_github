[![Gitter](https://badges.gitter.im/fra-dev-ops-bu/community.svg)](https://gitter.im/fra-dev-ops-bu/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![GitHub contributors](https://img.shields.io/github/contributors/fra-dev-ops-bu/githubinar_github.svg)](https://GitHub.com/fra-dev-ops-bu/githubinar_github/graphs/contributors/)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Percentage of issues still open")


# GitHubinar of GitHub

## コンセプト
:tada: さぁ、:octocat:GitHubを学びましょう！ :tada:

ただし、講師から習うのではありません :no_good:

学習の手引きを共同開発（執筆）しながら学んでみましょう。
他の人がわかりやすいように説明する過程で、自ずとあなた自身の理解度も深まるはずです。


> 「ただでさえ忙しいのに、共同執筆なんて絶対ムリ！」> :exploding_head: 

:man_dancing: <大丈夫。運営がタスク量を調整します


> 「GitHubについて何も知らないし、調べてみても全く理解できない...」> :cry:

:man_dancing: <大丈夫。基礎は運営が説明します

このセミナーが、:octocat:GitHubを使った共同開発（参考: [GitHubinar](https://scrapbox.io/fra-dev-ops-bu/GitHubinar)）
の形をとっているのにはワケがあります:

- 実際に成果物に貢献しながら学ぶので、自分ごととして取り組める:slightly_smiling_face:
- 自身の言葉で言い換えることによって理解が深まる:grin:
- 共同執筆を通して、基本的な開発フローを体験できる:star_struck:

セミナーが終わる頃には、あなたが持つ仕事のすすめ方についての概念は大きく変わっているはずです。
さぁ、さっそく執筆に加わってください！ :point_down:
|  | 募集締切 |
----|---- 
| [第1期](https://github.com/fra-dev-ops-bu/githubinar_github/issues/6) | 未定 |
| 第2期 | :construction: |

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## 執筆項目

- [『:fish:水研職員のためのGitHub学習の手引き:octocat:』](#%E3%80%8Efish%E6%B0%B4%E7%A0%94%E8%81%B7%E5%93%A1%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AEgithub%E5%AD%A6%E7%BF%92%E3%81%AE%E6%89%8B%E5%BC%95%E3%81%8Doctocat%E3%80%8F)
- [GitHubを5秒で表現すると？](#github%E3%82%925%E7%A7%92%E3%81%A7%E8%A1%A8%E7%8F%BE%E3%81%99%E3%82%8B%E3%81%A8)
- [絶対にハズせない三大機能](#%E7%B5%B6%E5%AF%BE%E3%81%AB%E3%83%8F%E3%82%BA%E3%81%9B%E3%81%AA%E3%81%84%E4%B8%89%E5%A4%A7%E6%A9%9F%E8%83%BD)
- [仕事をスムーズにすすめるための補助機能](#%E4%BB%95%E4%BA%8B%E3%82%92%E3%82%B9%E3%83%A0%E3%83%BC%E3%82%BA%E3%81%AB%E3%81%99%E3%81%99%E3%82%81%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AE%E8%A3%9C%E5%8A%A9%E6%A9%9F%E8%83%BD)
- [自分のマシンで編集してみよう](#%E8%87%AA%E5%88%86%E3%81%AE%E3%83%9E%E3%82%B7%E3%83%B3%E3%81%A7%E7%B7%A8%E9%9B%86%E3%81%97%E3%81%A6%E3%81%BF%E3%82%88%E3%81%86)
- [水研業務のコンテキストから見たGitHub](#%E6%B0%B4%E7%A0%94%E6%A5%AD%E5%8B%99%E3%81%AE%E3%82%B3%E3%83%B3%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E3%81%8B%E3%82%89%E8%A6%8B%E3%81%9Fgithub)
- [感想](#%E6%84%9F%E6%83%B3)
- [Appendix](#appendix)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 『:fish:水研職員のためのGitHub学習の手引き:octocat:』

# GitHubを5秒で表現すると？
# 絶対にハズせない三大機能
  - バージョン管理をしてみよう
  - Issueを立ててみよう
  - Pull Requestをしてみよう
# 仕事をスムーズにすすめるための補助機能
  - ブランチ
  - fork
  - merge
  - Issue駆動開発
  - History
  - Blame
# 自分のマシンで編集してみよう
  - Gitの環境構築
  - クリックでやっていたことをコマンドでやってみよう
  - コラム: GitHubとGitの関係は？ 
# 水研業務のコンテキストから見たGitHub
# 感想
# Appendix
  - 参考サイト
  - さらなる学びのために

**学ばないこと**
このGitHubinarでは、GitHubの習熟に集中します。
したがって、以下に挙げるGitのコマンドは学びません:
- git reset
- git revert
- git rebase
- git stash

ただし、これらのGitコマンドは日常業務の助けとなりますので、
興味のある方は [GitHubinar of Git](https://github.com/fra-dev-ops-bu/githubinar_git)にご参加ください。
