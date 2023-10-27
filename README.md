# Docker_practice

## Dockerって何？
PCの中に特殊な環境を作って、その上でソフトウェアを動かす。仮想的に作った環境のこと。
仮想環境を構築することでアプリケーションを簡単に開発、デプロイできるようにしている。

## Dockerがないと困ること
環境構築が大変。

### アプリケーションの開発は
OSがベースにある。<br>
↓<br>
ライブラリなどをインストールしてコードを書いていく。<br>
↓<br>
環境によってはライブラリをインストール時にエラーが発生する。<br>
↓<br>
別のライブラリが必要だったり。。。<br>


**人によって環境が違うので、それぞれで動きが違うため環境構築がとても大変。**

## Dockerがあれば
- アプリケーションを動作させるのに必要なものをひとまとめにして配布できる。
　
- OS・ライブラリ・アプリケーションをセットにして配布すれば、人による環境の違いの差分のエラーを吸収してくれる。

- コマンド一つで環境構築ができる

- ローカルで開発したものをテスト環境や本番環境でスムーズに動かせる。環境による差分をなくせる。→ リリースが早くできる。

## Docker-compose
### 設定手順
1. ライブラリインストール
    - requirements.txt 使いたいライブラリを指定する
2. アプリケーションのコードを書く
    - app.py アプリの処理を書く
3. Dockerfile作成
4. Docker-compose.yml作成

#### 不明点
ライブラリの必要性をどのように判断するのかが分からない。
