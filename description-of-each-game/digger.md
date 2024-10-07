---
label: 【整地】の説明
order: 699999
---
スタートアップゲーム名：
```digger```

# 整地説明動画
[!embed](https://youtu.be/7gIpywjayBU)
:::danger 注意
※整地のプレイ前に必ず見てください。
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

  - ハートミー ：ミニ回復
    ```
    /effect give @p minecraft:regeneration 5 5
    ```

  - バラ ：ゾンビ
    ```
    /summon minecraft:zombie ~ ~ ~
    ```

  - GG ：スケルトン
    ```
    /summon minecraft:skeleton ~ ~ ~
    ```
  
  - ソフトクリーム ：目隠し
    ```
    /execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
    ```
    
  - フィンガーハート ：殺人うさぎ
    ```
    /execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99}
    ```
    
  - www ：クリーパー
    ```
    /summon minecraft:creeper ~ ~ ~
    ```

  - ゲームパッド ：牛x5
    ```
    /summon minecraft:cow ~ ~ ~
    ```

  - ローザ ：ファイヤースケルトン
    ```
    /summon minecraft:skeleton ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:bow",Count:1b,tag:{Enchantments:[{id:"minecraft:flame",lvl:1}]}}],ArmorItems:[{},{},{},{}]}
    ```
    
  - 友情ネックレス ：クリーパー
    ```
    /summon minecraft:creeper ~ ~ ~
    ```

  - ヴェノム ：クリーパー
    ```
    /summon minecraft:creeper ~ ~ ~
    ```

  - レイブダンス ：エンダーマンx2
    ```
    /summon minecraft:enderman ^ ^2 ^2 {CustomNameVisible:1,PersistenceRequired:1b}
    ```

  - かき氷 ：防具つきゾンビx2
    ```
    /summon minecraft:zombie ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"minecraft:iron_helmet",Count:1}]}
    ```
    
  - 筋肉ムキムキ ：回復
    ```
    /effect give @p minecraft:regeneration 15 5
    ```

  - 愛してる ：回復
    ```
    /effect give @p minecraft:regeneration 15 5
    ```

  - 香水 ：豚10匹
    ```
    /summon minecraft:pig ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b}
    ```

  - ありがとう ：回復
    ```
    /effect give @p minecraft:regeneration 15 5
    ```

  - ドーナッツ ：ゴキブリx3
    ```
    /summon minecraft:silverfish ~ ~ ~
    ```

  - キャップ ：空腹
    ```
    /effect give @p minecraft:hunger 30 255
    ```
    
  - スター ：大ジャンプ
    ```
    /effect give @p minecraft:levitation 1 100
    ```

  - ゲームコントローラー ：肩車ゾンビx50
    ```
    /task zombie2 50 2
    ```

  - クラッカー ：ゾンビx100
    ```
    /task zombie1 100 2
    ```

  - ハンドハート ：魔法使い
    ```
    /summon minecraft:illusioner ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b}
    ```
    
  - ハンドハート ：魔法使い
    ```
    /summon minecraft:illusioner ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b}
    ```

  - 柴犬 ：カミナリ
    ```
    /execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
    ```

  - 鍵と鍵穴 ：金床の雨
    ```
    /task anvil1 1 1 25
    ```
    
  - ハート ：黒曜石追加
    ```
    /execute at @p run summon minecraft:falling_block ~ ~10 ~ {BlockState:{Name:"minecraft:obsidian"},Time:1}
    ```

  - 愛してる ：回復
    ```
    /effect give @p minecraft:regeneration 15 5
    ```
    
  - 髪をなでる ：シュルカー
    ```
    /summon minecraft:shulker ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b}
    ```

  - 花冠 ：氷塊
    ```
    /execute as @p run fill ~-1 ~ ~-1 ~1 ~2 ~1 minecraft:ice
    ```

  - ゲーマーキャット ：雷+ねこパーティー
    ```
    /execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
    ```
    ```
    /task cat1 100 2    
    ```
  - ゲーミングキーボード ：ルーレット
    ```
    /roulette GamingKeyboard
    ```

  - コーギー ：耐電クリーパー
    ```
    /task powercreeper1 25 2
    ```

  - ボクシンググローブ ：TNT
    ```
    /execute at @p run summon tnt ~ ~5 ~ {fuse:100}
    ```
    
  - フルーツの友達 ：激おこ犬
    ```
    /task wolf1 25 3
    ```
    
  - 招きねこ ：ネコパーティー
    ```
    /task cat1 100 2
    ```
    
  - マネーガン ：アイテム没収
    ```
    /clear @p
    ```

  - すばらしい！ ：ダイヤモンドシャベル
    ```
    /task diamondshovel1 1 1
    ```

  - ハグ ：お助け
    ```
    /effect give @a minecraft:haste 30 255 true
    ```
    
  - ライオンのたてがみ ：お助け
    ```
    /effect give @a minecraft:haste 30 255 true
    ```

  - 白鳥 ：全員集合
    ```
    /execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
    ```
    
  - 列車 ：砂追加
    ```
    /execute at @p run fill -8 200 8 8 200 -8 minecraft:light_blue_concrete_powder
    ```

  - Travel with You ：15分強制雨
    ```
    /task weather1 1 1
    ```
    
  - ラブリーミュージック ：ラベジャーx2
    ```
    /summon minecraft:ravager ~ ~ ~
    ```

  - フラワーミラー ：ウォーデン
    ```
    /summon minecraft:warden ~ ~ ~
    ```

  - キリン ：ウォーデン
    ```
    /summon minecraft:warden ~ ~ ~
    ```
    
  - 花火 ：チキンパーティー
    ```
    /task redstonetorch1 1 1
    ```

  - ドラムセット ：チキンパーティー
    ```
    /task redstonetorch1 1 1
    ```

  - アーケードゲーム ：超お助け
    ```
    /task ArcadeGame1 1 1
    ```

  - 配信者のセットアップ ：最強戦士
    ```
    /task warden1 1 1
    ```

  - クジラのダイビング ：動物園
    ```
    /task world2 1 1
    ```

  - オートバイ ：水族館
    ```
    /task water1 1 1
    ```
    
  - ゲーミングキーボード ：ルーレット
    ```
    /roulette GamingKeyboard
    ```

  - 子猫のレオン ：白馬の王子様
    ```
    /task leon 1 1
    ```

  - スポーツカー ：炎ミサイル
    ```
    /task blazephantom1 200 4
    ```

  - 星から星へ ：TNT大爆発
    ```
    /task concrete_powder1 1 1
    ```

  - ローザの星雲 ：砂タワー
    ```
    /task cart1 1 1
    ```

  - ライオン ：巨大ゾンビ群
    ```
    /task ghastgiant1 200 4
    ```

  - TikTok Universe ：ワールド崩壊
    ```
    /task tnt2 1200 2 
    ```
