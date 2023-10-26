# このリポジトリについて

## 目的

Python言語のフレームワークDjangoについて理解を深める

## 主な参照元

[youtube動画【Django入門】](https://youtu.be/O037g3NOoXY?si=5c4CENL3XgbCYHuz)自作で簡単なブログを作ってDjangoの１歩を踏み出してみよう ~Djangoチュートリアル  

## 作業環境

- Windows11pro 22H2
- node v18.16.1 npm 8.16.0
- python 3.10.4
- virtualenv 20.24.6
- pip 23.3.1
- terminal: Git Bash

## 手順

### 1. 作業用フォルダを作成

作業場所は任意でOK、すでに作業用のフォルダがある場合はそこに移動する。（下記の作業は不要です）  

下記は「新たに作る場合」の事例です。  

[参考動画](https://youtu.be/O037g3NOoXY?si=8f7kSovNcukkREmK&t=380)

```bash
cd ~/Desktop
mkdir dev
cd dev
mkdir pythonproject
cd pythonproject
mkdir django
cd django
```

### 2. Python言語の仮想環境を作る

[参考動画](https://youtu.be/O037g3NOoXY?si=m-CTFg3WPWqkPSKu&t=420)  

#### 2-2 virtualenvコマンドの有無を確認し、なかったらインストールする

ターミナルで`virtualenv --version`と打ってみて `virtualenv 20.24.6`のようにバージョンが返ってくればOK。もし、NGだったら下記コマンドでインストールする。

```bash
pip install virtualenv
```

#### 2-3 python仮想環境をつくる

```bash
virtualenv my-first-blog-youtube
```

ここで、`my-first-blog-youtube`は仮想環境名で、任意の名前でOKです。
