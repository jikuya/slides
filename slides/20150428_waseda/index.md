class: center middle
# 教育工学研究法15S
~ Git・Github・簡易DB 入門 ~

.right[軸屋 邦彦　　　]
---
# 授業の準備
- このスライドを開く
- 進捗シートを開く[（教育工学研究法01）](https://docs.google.com/a/dena.jp/spreadsheets/d/1T98FBpvoxOBaMvipnF1MBqnlWsYz8kgtDuN18UcbxNc/edit#gid=2102025050)・[(教育工学研究法03)](https://docs.google.com/a/dena.jp/spreadsheets/d/1K0i7CUWkISPQZgJ5lYSMsxRSu8rZjDnU40kQrKUkNaQ/edit#gid=1837835513)
- [Github](https://github.com)を開き自分のアカウントでログインする
- SouceTreeを立ち上げる
- ターミナルを立ち上げる（Macユーザのみ）
- Google Chromeをオプション付きで開く
 - Mac：ターミナルで以下のコマンドを実行する
  - `open -a Google\ Chrome --args -allow-file-access-from-files`
 - Windows：[この手順通りにやる](http://www.finefinefine.jp/web/jquery/kiji861/)
---
# 授業の流れ
- 自己紹介
- チーム作業について
- Git & Github 入門
- Git & Github 実践
- tmlib.js を使った ゲーム開発について
- Google Spread Sheet を使った簡易DBについて
---
# 自己紹介
- 軸屋 邦彦(30歳)
- 慶応義塾大学 経済学部
- 楽天 => DeNA
- Webアプリケーションエンジニア
 - PHP・Perl・Ruby
---
# 授業の流れ
- ~~授業の準備~~
- ~~自己紹介~~
- **チーム作業について**
- Git & Github 入門
- Git & Github 実践
- tmlib.js を使った ゲーム開発について
- Google Spread Sheet を使った簡易DBについて
---
# チーム作業について
## ゴール
- チームでの役割分担したとき、どのようにGit、Githubを使うかイメージができている

## 内容
- 実際にゲーム開発するときの役割分担について説明する
- 各役割の人がどのようにGitを使うかを説明する
---
# ゲーム開発するときの役割分担
- 「マネージャー」：PRJの運営・管理
- 「企画」：世界観・ストーリー・ゲームデザイン・仕様策定
- 「デザイナー」：グラフィックデザイン・キャラデザイン・UI設計・画像制作
- 「エンジニア」：プログラムを組んで、ゲーム自体を作る
---
# 今回、各役割の人がどこでGitを使うか
- 「企画」：問題作成・ワーディング・分析内容の調整
- 「デザイナー」：レイアウト調整・画像作成
- 「エンジニア」：ゲーム全般のプログラム作成
---
# 授業の流れ
- ~~授業の準備~~
- ~~自己紹介~~
- ~~チーム作業について~~
- **Git & Github 入門**
- Git & Github 実践
- tmlib.js を使った ゲーム開発について
- Google Spread Sheet を使った簡易DBについて
---
# Git & Github 入門
## ゴール
- Git・Githubの用語を理解し、各操作が何を行っているかイメージできる状態になる

## 内容
- Git・Githubについて
- SouceTreeについて
- Gitの基本
- Githubの機能
---
# Git・Githubについて
## Git
- [サルでもわかるGit入門](http://www.backlog.jp/git-guide/)
 - [Gitを使ったバージョン管理](http://www.backlog.jp/git-guide/intro/intro1_1.html)
 - [リポジトリの共有](http://www.backlog.jp/git-guide/intro/intro3_1.html)
 - [変更履歴の統合](http://www.backlog.jp/git-guide/intro/intro5_1.html)
 - [ブランチ](http://www.backlog.jp/git-guide/stepup/stepup1_1.html)

## Github
- [Githubとは](http://jp.techcrunch.com/2012/07/15/20120714what-exactly-is-github-anyway/)
- Githubの使い方
 - [Githubの登録](http://www.atmarkit.co.jp/ait/articles/1407/22/news019.html)
 - [SSHの公開鍵を作成しGithubに登録する手順（SouceTreeを使う場合は飛ばしてOK）](http://monsat.hatenablog.com/entry/generating-ssh-keys-for-github)
---
# SouceTreeについて
## SouceTree
- [Gitのインストール（SouceTreeのインストール）](http://www.backlog.jp/git-guide/intro/intro2_1.html)
- [SourceTree の使い方](http://celtislab.net/archives/20140527/git-sourcetree/)
- [SourceTreeをさらに使いこなすための便利機能](http://ics-web.jp/lab/archives/1365)
---
# Gitの基本
- [Git用語集](http://qiita.com/jikuya/private/5280940d8087c2b44309)

---
# Githubの機能
- [Github用語集](http://qiita.com/jikuya/private/0116145090ca41627b26)

---
# 授業の流れ
- ~~授業の準備~~
- ~~自己紹介~~
- ~~チーム作業について~~
- ~~Git & Github 入門~~
- **Git & Github 実践**
- tmlib.js を使った ゲーム開発について
- Google Spread Sheet を使った簡易DBについて
---
# Git & Github 実践
## ゴール
- 今後の開発に必要な作業をソースコード管理をSourceTreeを使って行える

## 内容
- 課題に解きながらSouceTreeを通したGit・Githubの操作を学ぶ

## 課題の流れ
1. 課題を解説
2. 課題の通りに操作
3. 進捗シートにGithubで作ったリポジトリのURLを記載[（教育工学研究法01）](https://docs.google.com/a/dena.jp/spreadsheets/d/1T98FBpvoxOBaMvipnF1MBqnlWsYz8kgtDuN18UcbxNc/edit#gid=2102025050)・[(教育工学研究法03)](https://docs.google.com/a/dena.jp/spreadsheets/d/1K0i7CUWkISPQZgJ5lYSMsxRSu8rZjDnU40kQrKUkNaQ/edit#gid=1837835513)
---
# 課題
- Q1. [SourceTreeとGithubの連携](http://qiita.com/jikuya/private/899c1a6dfd7412b5242a)
- Q2. [リポジトリ作成からプッシュまでの一連の操作](http://qiita.com/jikuya/private/c7fc3ded0bda367967dd)
- Q3. [ブランチ作成からプッシュまでの一連の操作](http://qiita.com/jikuya/private/1cb0b32b597972f59fb8)
- Q4. [プルリクエストとマージ](http://qiita.com/jikuya/private/04b3cf4c33fe33dff1aa)
---
# 授業の流れ
- ~~授業の準備~~
- ~~自己紹介~~
- ~~チーム作業について~~
- ~~Git & Github 入門~~
- ~~Git & Github 実践~~
- **tmlib.js を使った ゲーム開発について**
- Google Spread Sheet を使った簡易DBについて
---
# tmlib.js を使った ゲーム開発について
## ゴール
- ゲーム開発の環境を準備出来るようになる

## 内容
- 開発環境について
- ファイル構成について
- 実際に作業をしてみる
---
# 開発環境の説明
- Mac or Windows
- [Google Chrome](https://www.google.co.jp/chrome/browser/desktop/index.html)（オプション付き起動）
 - Mac：ターミナルでコマンド実行
  - `open -a Google\ Chrome --args -allow-file-access-from-files`
 - Windows：[この手順通りにやる](http://www.finefinefine.jp/web/jquery/kiji861/)
- [Github](https://github.com/)
- [SourceTree](http://www.sourcetreeapp.com/)
- テキストエディタ
 - Mac： [CotEditor](http://techacademy.jp/magazine/4720)
 - Windows： [Notepad++](http://techacademy.jp/magazine/4724)
 - [その他](http://qiita.com/jikuya/private/e4d074154f835ff7d7d9)
---
# ファイル構成について
- ○×クイズを例に[「サンプルリポジトリ」](https://github.com/phi-jp/tmlib.js-yesnoquiz)を見ながら解説

---
# 実際に作業をしてみる
-  Q1. [サンプルリポジトリをフォークしてプルリクエスト・マージまでを行う](http://qiita.com/jikuya/private/26eb30b7e1747c629097)

---
# 授業の流れ
- ~~授業の準備~~
- ~~自己紹介~~
- ~~チーム作業について~~
- ~~Git & Github 入門~~
- ~~Git & Github 実践~~
- ~~tmlib.js を使った ゲーム開発について~~
- **Google Spread Sheet を使った簡易DBについて**
---
# Google Spread Sheet を使った簡易DBについて
## ゴール
- 分析に必要な情報をGoogleDocs上に記録することができるようになる

## 内容
- GoogleDocs上に記録仕組みについて
- 記録用スプレッドシートを作る
- サンプルゲームのスコアを自分が作ったスプレッドシートに記録する
---
# GoogleDocs上に記録仕組みについて
## Google Apps Script とは
- Googleが提供するサーバーサイド・スクリプト環境
- Googleの提供しているサービスであればなんでも連携させて一つの仕事ができる
 - スプレッドシートをマクロのように動かす
 - スプレッドシートから予定をカレンダーに自動登録する
 - カレンダーの予定を毎朝自動でメールで通知する
 - スプレッドシートから差込メール*を送る
- [参考URL](http://libro.tuyano.com/index2?id=638001)
---
# 記録用スプレッドシートを作る
- Googleスプレッドシートを作る
- スプレッドシートにGoogle Apps Scriptを紐付ける
 - 「ツール」 > 「スクリプトエディタ」 をクリック
 - 適当な名前を付ける
 - コード.gsの中身を全部消して、スクリプトサンプルの内容をコピペする
 - 「実行」 > 「doPost」 をクリック（承認をする。その後エラーが起きてOK。）
 - 「公開」 > 「ウェブアプリケーションとして導入」 をクリック
 - 「アプリケーションにアクセスできるユーザー:」は「全員（匿名ユーザーを含む）」にし、後は適当に記載して更新ボタンを押す
 - [スプレッドシートサンプル](https://docs.google.com/spreadsheets/d/1ROrXaNtQJJ3jmXjCqm_DoBqL1n2WzQNNFo-qyYFKA7I/edit#gid=1751069508)
 - [スクリプトサンプル](https://script.google.com/macros/d/ME_0G-DCAkIk8CEn3YuQNZt2VmIwYkfDl/edit?uiv=2&mid=ACjPJvFtR14BRlzHXf877dVQUQHRFRVhUj3zvZKAQbP8HAcF3hqo2W4AN9SPfDg6lm-xLKL7MhBgD_EdT5DDixGZ0ZdNDHg50SlQcg582M-OP5SreCfHC7NFkUcoqwcuyPAvd-G96ito1_s)
---
# サンプルゲームのスコアを自分が作ったスプレッドシートに記録する
- サンプル用のカラム名をスプレッドシートに記載する
- 先ほど作ったサンプルのconstant.js内にある、スプレッドシートのURLを自分が作ったものに変更する
- 実際にゲームを動かして、自分のスプレッドシートにレコードが追加されるか確認する
---
class: center middle
# End
