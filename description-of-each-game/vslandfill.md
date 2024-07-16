---
label: 【埋め立てバトル】の説明
order: 69000
---

# 埋め立て説明動画  
[!embed](https://youtu.be/KkGKXygxz00)
:::danger 注意
※埋め立てバトルのプレイ前に必ず見てください。
:::  

# ワールド説明

### ワールド全体図
![ワールド全体図](/image/battle1.PNG)

1. **スポーン地点**  
感圧版を踏むと埋め立て用のブロックが手に入ります。
![スポーン地点](/image/battle2.png)

2. **金リンゴボタン**  
ボタンを押すと、金リンゴが一つ手に入ります。
![金リンゴボタン](/image/b4.png)

3. **アイテムボタン**  
ボタンを押すと、基礎ツール類が手に入ります。
![アイテムボタン](/image/battle5.png)

4. **晴れボタン**  
レバーを引くと天候が晴れになります。
![晴れボタン](/image/battle6.png)

5.**妨害終了ボタン**
○○祭りが来た時にレッドストーントーチを破壊すると、鶏のスポーンが止まります。
![妨害終了ボタン](/image/

6. **TNTボタン**  
ボタンを押すことで、TNTが5つ出ます。
![TNTボタン](/image/battle7.png)

7. **コマンド**  
ワールド操作や、難易度の設定ができます。
![コマンド](/image/battle8.png)

8. **テレポートコマンド**  
鉄の扉の奥にあるボタンを押すと、初期地にテレポートできます。
![テレポート](/image/battle9.png)

# コマンド一覧

## 基本的なコマンド一覧

- TiktokLiveと接続
※TikTokIDは自身のTikTokIDに変更してください。
途中で切断された場合も同じコマンドを実行してください。
```
/libertascore connect [TiktokID]
```

- ワールドリセット
```
/libertascore reset
```

- 中央枠内ブロックのみ消去
```
/execute at @p run fill 7 37 -7 -7 51 7 minecraft:air
```

- サーバー再起動
```
/restart
```

## ギフトコマンド一覧  
- ハートミー：5秒回復
```
  /effect give @p minecraft:regeneration 5 5
```

- バラ：ゾンビ
```
  /execute at @p[distance=1..] run summon minecraft:zombie ~ ~ ~ {CustomName:'{"text":"{user.profileName}"}',CustomNameVisible:1,PersistenceRequired:1b}
```

- GG：スケルトン
```
  /execute at @p[distance=1..] run summon minecraft:skeleton ~ ~ ~ {CustomName:'{"text":"{user.profileName}"}',CustomNameVisible:1,PersistenceRequired:1b}
```

- フィンガーハート：激怒うさぎ
```
  /execute at @p[distance=1..] run execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99}
```

- www：クリーパー
```
  /execute at @p[distance=1..] run summon minecraft:creeper ~ ~ ~ {CustomName:'{"text":"{user.profileName}"}',CustomNameVisible:1,PersistenceRequired:1b}
```

- ゲームパッド：牛5匹
```
  /execute at @p[distance=1..] run summon minecraft:cow ~ ~ ~ {CustomName:'{"text":"{user.profileName}"}',CustomNameVisible:1,PersistenceRequired:1b}
```

- 愛してる：回復
```
  /effect give @p minecraft:regeneration 15 5
```

- 香水：豚10匹
```
  /execute at @p[distance=1..] run summon minecraft:pig ~ ~ ~ {CustomName:'{"text":"{user.profileName}"}',CustomNameVisible:1,PersistenceRequired:1b}
```

- ドーナッツ：ゴキブリ
```
  /execute at @p[distance=1..] run summon minecraft:silverfish ~ ~ ~ {CustomName:'{"text":"{user.profileName}"}',CustomNameVisible:1,PersistenceRequired:1b}
```

- スター：大ジャンプ
```
  /execute at @p[distance=1..] run effect give @p minecraft:levitation 1 100
```

- 折り鶴：TNT
```
  /execute at @p[distance=1..] run execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```

- クラッカー：ゾンビx100
```
  /task zombie1 100 2
```

- ゲームコントローラー：肩車ゾンビx50
```
  /task zombie2 50 2
```

- 鍵と鍵穴：金床の雨
```
  /task anvil1 1 1 50
```

- 柴犬：カミナリ
```
  /execute at @p[distance=1..] run execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
```

- フルーツの友達：激おこ犬
```
  /task wolf1 25 3
```

- コーギー：耐電クリーパー
```
  /task powercreeper1 25 2
```

- 招きねこ：ねこパーティー
```
  /task cat1 100 2
```

- マネーガン：アイテム全回収
```
  /execute at @p[distance=1..] run clear @p
```

- すばらしい！：爆撃TNT
```
  /task tptnt1 1 1
```

- 白鳥：全員集合
```
  /execute at @p[distance=1..] run execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```

- 列車：バトル
```
  /task battle1 1 1
```

- Travel with You：強制雨
```
  /task weather1 1 1
```

- フラワーミラー：ウォーデン
```
  /execute at @p[distance=1..] run summon minecraft:warden ~ ~ ~
```

- ドラムセット：チキン祭り
```
  /task chicken1 1000 2
```

- 花火：チキン祭り
```
  /task chicken1 1000 2
```

- クジラのダイビング：動物園
```
  /task world2 1 1
```

- オートバイ：水族館
```
  /task water1 150 2
```

- 子猫のレオン：白馬の王子様
```
  /task leon 1 1
```

- スポーツカー：炎ミサイル
```
  /task blazephantom1 200 4
```

- ローザの星雲：領域展開
```
  /task world1 1 1
```

- ライオン：巨大ゾンビ軍
```
  /task ghastgiant1 200 4
```

- TikTok Universe：ワールド崩壊
```
  /task tnt2 1200 2
```


