# Name（リポジトリ/プロジェクト/OSSなどの名前）

分かりやすくてカッコイイ名前をつける（今回は"hoge"という名前をつける）

"hoge"が何かを簡潔に紹介する

# DEMO

"hoge"の魅力が直感的に伝えわるデモ動画や図解を載せる

# Features

"hoge"のセールスポイントや差別化などを説明する

# Requirement

"hoge"を動かすのに必要なライブラリなどを列挙する

* huga 3.5.2
* hogehuga 1.0.2

# Installation

Requirementで列挙したライブラリなどのインストール方法を説明する

```bash
pip install -r requirements.txt
```

# Usage

DEMOの実行方法など、"rakuten"の基本的な使い方を説明する

```bash
git clone https://github.com/nobutan0113/rakuten.git
cd rakuten
python app.py
```

# Note

注意点などがあれば書く

# Author

作成情報を列挙する

* 作成者
* 所属
* E-mail

# License
ライセンスを明示する

"rakuten" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

社内向けなら社外秘であることを明示してる

"hoge" is Confidential.


# config 
- git cloneしたら、下記のファイルを修正する
    - setting/conf.json

- 修正内容
    - username : ユーザ名
    - pass : ログインパスワード

```
{
    "username": "",
    "pass": "",
    "login_url": "https://www.rakuten-card.co.jp/e-navi/",
    "dir_lists": [
        "./card_info",
        "./screenshots/card_rakuten"
    ]
}
```