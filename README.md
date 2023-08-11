# Discord Study Bot

勉強をサポートするためのDiscordBotです。

## 前提条件:

1. Pythonがインストールされていること
2. `discord.py` ライブラリがインストールされていること

## 環境変数の設定:

このボットを動作させる前に、以下の環境変数を設定する必要があります:

\```
DISCORD_TOKEN          # Discord Botのトークン
DISCORD_STUDY_ROLE_ID  # 勉強ロールのID
DISCORD_BREAK_ROLE_ID  # 休憩ロールのID
DISCORD_PAUSE_ROLE_ID  # 一時停止ロールのID
DISCORD_CHANNEL_ID     # チャンネルのID
\```

## 実行方法:

1. 必要なライブラリをインストールします:

\```
pip install discord.py
\```

2. ボットを実行します:

\```
python STUDY.py
\```
