# 投資ポートフォリオ管理サイト
このリポジトリはfffukkenのエンジニアとしてのポートフォリオリポジトリです。

Djangoで作成した、個人の投資ポートフォリオ管理Webサイトです。

このサイトを使ってユーザは自身の投資銘柄を検索・登録でき、自身の投資ポートフォリオの総合得点を評価することもできます。

# 概要
このWebサイト立ち上げには9名ほどのメンバーで取り組みました。
1名のチームリーダー、3名のプログラマー兼レビュワー、3名のプログラマー、2名のデザイナーの構成です。
私はプログラマー兼レビュワー兼インフラ担当を担っていました。

現在はWeb公開されていない環境ですが、以前はGithub Actionsを使ってCICDを構成し、インターネット上で閲覧できました。


# ダウンロードして使う方法
リポジトリをクローンします
```
$ git clone https://github.com/fffukken/Portfolio_fund.git
```
リポジトリへ移動します
```
$ cd Portfolio_fund
```
必要なパッケージをインストールします
```
$ pip install -r requirements.txt
```
データベースのセットアップを行います
```
$ python manage.py makemigrations
$ python manage.py migrate
```
開発用サーバを立ち上げます
```
$ python manage.py runserver
```
ローカルホストへアクセスすることでWebサイトを確認できます


# 使用した技術
- Django
- Javascript
- AWS(EC2, Route53)
- Github, Github Actions

# 主張したい点
- Github Actionsを使ってCICD環境を構築した
- ポートフォリオの検索のクエリ、ソート、Web上での描画を担当した。
