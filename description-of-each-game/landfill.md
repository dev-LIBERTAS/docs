---
label: 【埋め立て】の説明
order: 700000
---
スタートアップゲーム名：
```landfill```


# 埋め立て説明動画  
[!embed](https://youtu.be/5NufXU4s7Vo)
:::danger 注意
※埋め立てのプレイ前に必ず見てください。
:::  

# ワールド説明
### ワールド全体図
![ワールド全体図](/image/landfill-2.png)

1. **スポーン地点**  
手前の感圧版を踏むと埋め立て用のダイヤブロックが手に入ります。  
![スポーン地点](/image/landfill-3.png)

2. **金リンゴボタン**  
ボタンを押すと、金リンゴが一つ手に入ります。
![金リンゴボタン](/image/landfill-4.png)

3. **アイテムボタン**  
ボタンを押すと、基礎ツール類が手に入ります。
![アイテムボタン](/image/landfill-5.png)

4. **晴れボタン**  
レバーを引くと天候が晴れになります。
![晴れボタン](/image/landfill-6.png)

5. **妨害終了ボタン**  
○○祭りが来た時にレッドストーントーチを破壊すると、鶏のスポーンが止まります。
![○○祭り](/image/landfill-7.gif)  
水族館が来た時にレバーを引くと、水が止まります。　　
![水族館](/image/landfill-8.gif)

6. **コマンド**  
ワールドの操作や、難易度の設定ができます。
![コマンド](/image/landfill-9.png)


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
  /summon minecraft:zombie
```

- GG：スケルトン
```
  /summon minecraft:skeleton
```

- フィンガーハート：激怒うさぎ
```
  /execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99, Attributes:[{Name:"generic.max_health", Base:10}], Health:10f}
```

- www：クリーパー
```
  /summon minecraft:creeper
```

- 愛してる：回復
```
  /effect give @p minecraft:regeneration 15 5
```

- 香水：豚10匹
```
  /summon minecraft:pig
```

- ドーナッツ：ゴキブリ
```
  /summon minecraft:silverfish
```

- 折り鶴：TNT
```
  /execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```

- クラッカー：ゾンビx100
```
  /task zombie1 100 2
```

- ゲームコントローラー：肩車ゾンビx100
```
  /task zombie2 50 2
```

- 鍵と鍵穴：金床の雨
```
  /task anvil1 1 1 50
```

- 柴犬：カミナリ
```
  /execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
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
  /clear @p
```

- すばらしい！：爆撃TNT
```
  /task tptnt1 1 1
```

- ハグ：お助け
```
  /execute at @p run fill 7 37 7 -7 45 -7 minecraft:gold_block
```

- 白鳥：全員集合
```
  /execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```

- 列車：お邪魔ブロック
```
  /execute at @p run fill -8 200 8 8 200 -8 minecraft:light_blue_concrete_powder
```

- Travel with You：強制雨
```
  /task weather1 1 1
```

- フラワーミラー：ウォーデン
```
  /summon minecraft:warden
```

- 花火：〇〇祭り
```
  /execute at @p run fill 0 38 -25 0 38 -25 minecraft:redstone_torch
```

- クジラのダイビング：動物園
```
  /task world2 1 1
```

- オートバイ：水族館
```
  /task water1 1 1
```

- 子猫のレオン：白馬の王子様
```
  /task leon 1 1
```

- スポーツカー：炎ミサイル
```
  /task blazephantom1 200 4
```

- 星から星へ：TNT大爆発
```
  /execute at @p run fill 7 37 -7 -7 51 7 minecraft:tnt
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
