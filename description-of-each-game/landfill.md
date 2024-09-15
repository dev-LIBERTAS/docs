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
- ハートミー：ミニ回復
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

- リスと松ぼっくり：目隠し
```
  /execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```

- フィンガーハート：激怒うさぎ
```
  /execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99}
```

- ニャオ：エンダーマン
```
  /summon minecraft:enderman
```

- インスタントヌードル：防具付きゾンビ
```
  /summon zombie ~ ~ ~ {HandItems:[{id:"minecraft:iron_sword",Count:1}]}
```

- 御守り：ハスク
```
  /summon minecraft:husk
```

- www：クリーパー
```
  /summon minecraft:creeper
```

- ローザ：ファイヤースケルトン
```
  /summon skeleton ~ ~ ~ {HandItems:[{id:"minecraft:bow",Count:1,tag:{Enchantments:[{id:flame,lvl:1}]}}]}
```

- 愛してる・初見です・ありがとう：回復
```
  /effect give @p minecraft:regeneration 15 5
```

- 香水：豚
```
  /summon minecraft:pig
```

- ドーナッツ：ゴキブリ
```
  /summon minecraft:silverfish
```

- ホットチョコレート：クモの巣
```
  /fill ~ ~ ~ ~ ~ ~ minecraft:cobweb
```

- 折り鶴：空腹
```
  /effect give @p minecraft:hunger 30 255
```

- キャップ：TNT
```
  /summon tnt ~ ~5 ~ {fuse:100}
```

- スター：大ジャンプ
```
  /effect give @p minecraft:levitation 1 100
```

- クラッカー：ゾンビx100
```
  /task zombie1 100 2
```

- ゲームコントローラー：肩車ゾンビx100
```
  /task zombie2 50 2
```

- ハートポーズ：魔法使い
```
  /summon minecraft:illusioner
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

- ハート：黒曜石追加
```
  /execute at @p run summon minecraft:falling_block ~ ~10 ~ {BlockState:{Name:"minecraft:obsidian"},Time:1}
```

- ニット帽：氷塊
```
  /fill ~-1 ~ ~-1 ~1 ~2 ~1 minecraft:ice
```

- びよ～ん：シュルカー
```
  /summon minecraft:shulker
```

- ゲームキーボード：ルーレット
```
  /roulette GamingKeyboard
```

- アヒル：クモの巣xゾンビ
```
  /task cobweb1 1 1
```

- 招きねこ：ねこパーティー
```
  /task cat1 100 2
```

- サンゴ：水の塔
```
  /fill 0 64 0 0 64 0 minecraft:water
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

- お疲れさま：監獄
```
  /task kangoku1 1 1
```

- 白鳥：全員集合
```
  /execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```

- 列車：砂追加
```
  /execute at @p run fill -8 200 8 8 200 -8 minecraft:light_blue_concrete_powder
```

- Travel with You：強制雨
```
  /task weather1 1 1
```

- 銀河：マグマの塔
```
  /execute at @p run fill 0 62 0 0 62 0 lava
```

- マジカルキャット：ラベジャー
```
  /summon minecraft:ravager
```

- フラワーミラー：ウォーデン
```
  /summon minecraft:warden
```

- 花火：〇〇祭り
```
  /execute at @p run fill 0 38 -25 0 38 -25 minecraft:redstone_torch
```

- アーケードゲーム：超お助け
```
  /task ArcadeGame1 1 1
```

- 不思議な花火：ブロック変換
```
  /execute at @p run fill 7 37 7 -7 51 -7 minecraft:light_blue_wool replace minecraft:diamond_block
```

- クジラのダイビング：動物園
```
  /task world2 1 1
```

- オートバイ：水族館
```
  /task water1 1 1
```

- 流星群：TNT流星群
```
  /task tnt4 1200 1
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
