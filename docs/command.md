---
title: コマンド
nav_order: 4
layout: post
---

# Minecraft コマンド

## 1. 基本コマンド

* `/help [command]`  
  コマンドのヘルプを表示

* `/give <player> <item> [count] [nbt]`  
  プレイヤーにアイテムを与える

* `/tp <target> <destination>`  
  プレイヤーやエンティティをテレポート

* `/teleport <target> <destination>`  
  `/tp` の別名

* `/gamemode <mode> [player]`  
  ゲームモードを変更（サバイバル、クリエイティブ、アドベンチャー、スペクテイター）

* `/effect <give|clear> <player> <effect> [seconds] [amplifier] [hideParticles]`  
  ステータス効果を付与・解除

* `/summon <entity> [pos] [nbt]`  
  エンティティを召喚

* `/kill [target]`  
  エンティティやプレイヤーを倒す

* `/weather <clear|rain|thunder> [duration]`  
  天気を変更

* `/time <set|add|query> [value]`  
  時間を操作

* `/difficulty <peaceful|easy|normal|hard>`  
  難易度を設定

* `/scoreboard`  
  スコアボードを管理

* `/say <message>`  
  チャットメッセージを送信

## 2. 実行・条件付きコマンド

* `/execute [as <entity>] [at <entity>] [store <...] <...] [if|unless <condition>] run <command>`  
  条件やコンテキスト付きでコマンドを実行

## 3. 位置・座標関連

* `/locate <structure|biome> [name]`  
  最寄りの構造物やバイオームを探す

* `/setworldspawn [pos]`  
  ワールドのスポーン地点を設定

* `/spawnpoint [player] [pos]`  
  プレイヤーのスポーン地点を設定

## 4. ブロック・環境操作

* `/setblock <pos> <block> [destroy|keep|replace] [nbt]`  
  ブロックを設置

* `/fill <from> <to> <block> [destroy|keep|replace|...] [nbt]`  
  範囲内をブロックで埋める

* `/clone <begin> <end> <destination> [maskMode] [cloneMode] [tileName]`  
  範囲内のブロックをコピー

## 5. プレイヤー管理

* `/ban <target> [reason]`  
  プレイヤーをBAN

* `/pardon <target>`  
  BANを解除

* `/op <player>`  
  オペレーター権限を付与

* `/deop <player>`  
  オペレーター権限を剥奪

* `/kick <player> [reason]`  
  プレイヤーをサーバーから追放

## 6. ゲームルール

* `/gamerule <ruleName> [value]`  
  ゲームルールを設定または確認

## 7. エンティティデータ

* `/data get|merge|remove <target> [path]`  
  エンティティやブロックのNBTデータを操作

## 8. その他

* `/title <player> <title|subtitle|actionbar|clear|reset> [text|times]`  
  タイトルを表示

* `/playsound <sound> <source> <targets> [pos] [volume] [pitch] [minimumVolume]`  
  音を再生

* `/particle <name> [pos] [delta] [speed] [count] [force|normal] [player]`  
  パーティクルを生成

* `/advancement <grant|revoke> <player> <advancement>`  
  実績（アドバンスメント）を管理

* `/function <name>`  
  コマンド関数を実行

* `/loot`  
  戦利品テーブルを操作
