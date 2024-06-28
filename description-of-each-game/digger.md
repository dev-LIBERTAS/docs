---
label: 【整地】の説明
order: 699999
---
スタートアップゲーム名：
```digger```

# 整地説明動画
[!embed](https://youtu.be/7gIpywjayBU)
:::danger 注意
※整地のゲームの前に必ず見てください。
:::  

# ワールド説明
### ワールド全体図
![ワールド全体図](/image/digger10.PNG)

1. **砂追加ボタン**  
ボタンを押すと、砂を追加することができます。
![砂追加ボタン](/image/2024-06-28_22.56.43.png)

2. **アイテムボタン**  
ボタンを押すと、基礎ツール類が手に入ります。
![アイテムボタン](/image/2024-06-28_20.16.02.png)

3.**晴れボタン**  
レバーを引くと天候が晴れになります。
![晴れボタン](/image/landfill-6.png)

4. **妨害終了ボタン**  
○○祭りが来た時にレッドストーントーチを破壊すると、鶏のスポーンが止まります。
![○○祭り](/image/digger1.gif)  
水族館が来た時にレバーを引くと、水が止まります。　　
![水族館](/image/digger1-1.gif)

5.**コマンド**  
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

- フィンガーハート：殺人うさぎ
```
/execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99, Attributes:[{Name:"generic.max_health", Base:10}], Health:10f}
```

- www：クリーパー
```
/summon minecraft:creeper
```

- ゲームパッド：牛5匹
```
/summon minecraft:cow
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

- ボクシンググローブ：TNT
```
/execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```

- マネーガン：アイテム全回収
```
/clear @p
```

- すばらしい！：ダイヤモンドシャベル
```
/task diamondshovel1 1 1
```

- ハグ：お助け
```
/effect give @a minecraft:haste 30 255 true
```

- スパゲッティのキス：採掘速度低下
```
/execute as @p at @s run summon minecraft:elder_guardian ~ ~ ~ {CustomName:"{user.profileName}",CustomNameVisible:1}
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

- フラワーミラー：ウォーデン
```
/summon minecraft:warden
```

- 花火：〇〇祭り
```
/execute at @p run fill 0 50 25 0 50 25 minecraft:redstone_torch
```

- ドラムセット：〇〇祭り
```
/execute at @p run fill 0 50 25 0 50 25 minecraft:redstone_torch
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

- 星から星へ：砂タワー！
```
/task concrete_powder1 1 1
```

- ローザの星雲：クリーパーカー
```
/task cart1 1 1
```

- ライオン：巨大ゾンビ軍
```
/task ghastgiant1 200 4
```

- TikTok Universe：ワールド崩壊
```
/task tnt2 1200 2
```
