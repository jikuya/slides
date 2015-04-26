class: center middle
# 教育工学研究法
~ Git・Github・簡易DB 入門 ~

.right[軸屋 邦彦　　　]
---
# 授業の流れ
- 授業の準備
- 自己紹介
- チーム作業について
- Git & Github 入門
- tmlib.js を使った ゲーム開発について
- Google Spread Sheet を使った簡易DBについて
---
# 授業の準備
- このスライドを開く
- [Github](https://github.com)にログインする
- SouceTreeを立ち上げておく
- ターミナルを立ち上げておく（Macユーザのみ）
- Googleスプレッドシートを開いておく
- Google Chromeをオプション付きで開く
 - Mac：ターミナルでコマンド実行 `open -a Google\ Chrome --args`
 - Windows：[この手順通りにやる](http://www.finefinefine.jp/web/jquery/kiji861/)
---
# 自己紹介
- 軸屋 邦彦(30歳)
- 慶応義塾大学経済学部出身
- 楽天 => DeNA
- Webアプリケーションエンジニア
- PHP・Perl・Ruby
---
# チーム作業について
## ゴール
- チームでの役割分担をイメージできている
- どのようにGit、Githubを使うかイメージができている

## 内容
- 実際にゲーム開発するときの役割分担について説明する
- 各役割の人がどのようにGitを使うかを説明する
---
# ゲーム開発するときの役割分担
- ざっくりいうと「マネージャー」「企画」「デザイナー」「エンジニア」がいる
- 「マネージャー」：PRJの運営・管理
- 「企画」：世界観・ストーリー・ゲームデザイン・仕様策定
- 「デザイナー」：グラフィックデザイン・キャラデザイン・UI設計・画像制作
- 「エンジニア」：プログラムを組んで、ゲーム自体を作る
---
# 今回、各役割の人がどこでGitを使うか
- 「企画」：問題作成・ワーディング
- 「デザイナー」：レイアウト調整・画像作成
- 「エンジニア」：プログラム作成
---
# Git & Github 入門
## ゴール
- 今後の開発に必要な作業をソースコード管理をSourceTreeを使って行える

## 内容
- Git・Githubについて
- SouceTreeについて
- SourceTreeを使ってGithubのリポジトリを更新する
- ブランチを作ってマージする
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
 - [SSHの公開鍵を作成しGithubに登録する手順（SouceTreeを使い場合は飛ばしてOK）](http://monsat.hatenablog.com/entry/generating-ssh-keys-for-github)
---
# SouceTreeについて
## SouceTree
- [Gitのインストール（SouceTreeのインストール）](http://www.backlog.jp/git-guide/intro/intro2_1.html)
- [SourceTree の使い方](http://celtislab.net/archives/20140527/git-sourcetree/)
- [SourceTreeをさらに使いこなすための便利機能](http://ics-web.jp/lab/archives/1365)
---
# Gitの用語
- リポジトリ：ファイルやディレクトリの状態を記録する場所
- リモートリポジトリ：専用のサーバに配置して複数人で共有するためのリポジトリ
- ローカルリポジトリ：ユーザ一人ひとりが利用するために、自分の手元のマシン上に配置するリポジトリ
- コミット：ファイルやディレクトリの追加・変更を、リポジトリに記録
- ワークツリー：Gitの管理下に置かれた、みなさんが実際に作業をしているディレクトリ
- インデックス：リポジトリにコミットする準備をするための場所
- プッシュ：ローカルリポジトリの変更履歴をリモートリポジトリに共有する
- クローン：リモートリポジトリの内容をまるまるダウンロードしてきて、別のマシンにローカルリポジトリとして作成する
- プル：リモートリポジトリの変更内容をローカルリポジトリに取り込む
---
# Githubの用語
- プルリクエスト：開発者のローカルのリポジトリでPushした変更や機能追加を、
ほかの開発者のリポジトリやブランチに取り込んでもらうためのリクエストを出す機能
- フォーク：他の開発者のリポジトリを github 上で クローン する
---
# SourceTreeを使ってGithubのリポジトリを更新する
- SourceTreeとGithubを連携させる
- Githubで新規リポジトリを作る
- SouceTreeでローカルにクローンする
- ファイルをコピーして差分を作る
- 差分をステージに上げる
- commitする
- Githubにpushする
---
# ブランチを作ってマージする
- ブランチを作る
- ファイルをコピー作成して差分を作る
- 差分をステージに上げる
- commitする
- GithubにPushする
- Github上でプルリクエストを出す
- Github上でプルリクエストをマージする
- SourceTreeを使ってmasterブランチを更新する
---
# tmlib.js を使った ゲーム開発について
## ゴール
- ゲーム開発の環境を準備出来るようになる

## 内容
- 開発環境について
- ファイル構成について
- 実際に作業をしてみ
---
# 開発環境の説明
- Mac or Windows
- [Google Chrome](https://www.google.co.jp/chrome/browser/desktop/index.html)（オプション付き起動）
 - Mac：ターミナルでコマンド実行 `open -a Google\ Chrome --args`
 - Windows：[この手順通りにやる](http://www.finefinefine.jp/web/jquery/kiji861/)
- [Github](https://github.com/)
- [SourceTree](http://www.sourcetreeapp.com/)
- テキストエディタ
 - Mac： [CotEditor](http://techacademy.jp/magazine/4720)
 - Windows： [Notepad++](http://techacademy.jp/magazine/4724)
 - [その他](http://qiita.com/jikuya/private/e4d074154f835ff7d7d9)
---
# ファイル構成について
- ○×クイズを例に「runstant」と「サンプルリポジトリ」を比較しながら説明する
 - [runstant](http://goo.gl/lZJMLz)
 - [サンプルリポジトリ](https://github.com/phi-jp/tmlib.js-yesnoquiz)


- ２つの違い
 - 最初に読み込まれるファイルはindex.html
 - その中から必要なjavascriptファイルを読み込んで実行している
 - 設定ファイルなどの定数は、別ファイルにしている
 - 画像や音は、ファイルを直接指定している
---
# 実際に作業をしてみる
- Google Chromeをオプション付きで開く
 - Mac：ターミナルでコマンド実行 `open -a Google\ Chrome --args`
 - Windows：[この手順通りにやる](http://www.finefinefine.jp/web/jquery/kiji861/)
- [サンプルリポジトリ](https://github.com/phi-jp/tmlib.js-yesnoquiz)をフォークする
- ローカル環境にクローンする
- masterブランチで、constant.js内にある問題文を変更してを加えて commit => push する
- 新しいブランチを作った上で、constant.js内にある問題文を変更して commit => push する
- 作ったブランチをmasterブランチに プルリク => マージ する
---
# Google Spread Sheet を使った簡易DBについて
## ゴール
- 分析に必要な情報をGoogleDocs上に記録することができるようになる

## 内容
- GoogleDocs上に記録仕組みについて
- 記録用のGoogleスプレッドシートを作る
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
# 記録用のGoogleスプレッドシートを作る
- Googleスプレッドシートを作る
- スプレッドシートにGoogle Apps Scriptを紐付ける
 - 手順
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
