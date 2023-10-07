# windows-lock-detector

Python で動く！Windows のロック状態を拾って Discord の特定ユーザーのニックネームを触る Bot  
ほぼほぼ自分用です 面白かったら改造してみてください

## 使いたいんだけど

以下に従って .env をいい感じにいじってください 中身はこんな感じ:

```.env
DISCORD_BOT_TOKEN=
TARGET_SERVER_ID=
TARGET_USER_ID=
```

あとは `pip install -r requirements.txt` して `python app.py` で動くと思います  
Linux とかでは動きません (Windows の API を触っているので)

## どうやって実装してんのこれ

書いたら書く
