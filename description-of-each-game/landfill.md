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
- ミニ回復
```
/effect give @p minecraft:regeneration 5 5
```
- ゾンビ
```
/summon minecraft:zombie ~ ~ ~ 
```
- スケルトン
```
/summon minecraft:skeleton ~ ~ ~ 
```
- 目隠し
```
/execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- 殺人うさぎ
```
/execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99}
```
- エンダーマン
```
/summon minecraft:enderman ^ ^2 ^2 
```
- 防具付きゾンビ
```
/summon minecraft:zombie ~ ~ ~ {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:""minecraft:iron_sword"",Count:1}],ArmorItems:[{},{},{},{id:""minecraft:iron_helmet"",Count:1}]}
```
- ハスク
```
/summon minecraft:husk ~ ~ ~ 
```
- クリーパー
```
/summon minecraft:creeper ~ ~ ~ 
```
- 豚x10
```
/summon minecraft:pig ~ ~ ~ 
```
- ファイヤースケルトン
```
/summon skeleton ~ ~ ~ {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:""bow"",Count:1b,tag:{Enchantments:[{id:""flame"",lvl:1}]}}],ArmorItems:[{},{},{},{id:""iron_helmet"",Count:1b}]}
```
- エンダーマンx2
```
/summon minecraft:enderman ^ ^2 ^2 
```
- 防具つきゾンビx2
```
/summon minecraft:zombie ~ ~ ~ {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:""minecraft:iron_sword"",Count:1}],ArmorItems:[{},{},{},{id:""minecraft:iron_helmet"",Count:1}]}
```
- 回復
```
/effect give @p minecraft:regeneration 15 5
```
- 豚10匹
```
/summon minecraft:pig ~ ~ ~ 
```
- ゴキブリx3
```
/summon minecraft:silverfish ~ ~ ~ {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,Attributes:[{Name:""generic.max_health"",Base:5}],Health:5.0f}
```
- クモの巣
```
/execute as @p run fill ~ ~ ~ ~ ~ ~ minecraft:cobweb
```
- 空腹
```
/effect give @p minecraft:hunger 30 255
```
- TNT
```
/execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```
- 大ジャンプ
```
/effect give @p minecraft:levitation 1 100
```
- 肩車ゾンビx50
```
/rtask zombie2 50 100
```
- ゾンビx100
```
/rtask zombie1 100 100
```
- 魔法使い
```
/summon minecraft:illusioner ~ ~ ~ 
```
- カミナリ
```
/execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
```
- 金床の雨
```
/rtask anvil1 1 1 2500
```
- 黒曜石追加
```
/execute at @p run summon minecraft:falling_block ~ ~10 ~ {BlockState:{Name:""minecraft:obsidian""},Time:1}
```
- 氷塊
```
/execute as @p run fill ~-1 ~ ~-1 ~1 ~2 ~1 minecraft:ice
```
- シュルカー
```
/summon minecraft:shulker ~ ~ ~ 
```
- 雷+ねこパーティー
```
/execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
    - /rtask cat1 100 100
```
- ルーレット
```
/roulette GamingKeyboard
```
- 耐電クリーパー
```
/rtask powercreeper1 25 100
```
- クモの巣xスケルトン
```
/rtask cobweb1 1 1
```
- 激おこ犬
```
/rtask wolf1 25 200
```
- ルーレット
```
/roulette roulette2
```
- ネコパーティー
```
/rtask cat1 100 100
```
- お助け
```
/execute at @p run fill 7 37 7 -7 45 -7 minecraft:gold_block
```
- 水の塔
```
/execute at @p run fill 0 64 0 0 64 0 minecraft:water
```
- アイテム没収
```
/clear @p
```
- 爆撃TNT
```
/rtask tptnt1 1 1
```
- 監獄
```
/rtask kangoku1 1 1
```
- 全員集合
```
/execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```
- 砂追加
```
/execute at @p run fill -8 200 8 8 200 -8 minecraft:light_blue_concrete_powder
```
- 15分強制雨
```
/rtask weather1 1 1
```
- ラベジャーx2
```
/summon minecraft:ravager ~ ~ ~ 
```
- マグマの塔
```
/execute at @p run fill 0 62 0 0 62 0 lava
```
- ウォーデン
```
/timemob minecraft:warden 900
```
- チキンパーティー
```
/rtask redstonetorch1 1 1
```
- 超お助け
```
/rtask ArcadeGame1 1 1
```
- 最強戦士
```
/rtask warden1 1 1
```
- ブロック変換
```
/execute at @p run fill 7 37 7 -7 51 -7 minecraft:blue_wool replace minecraft:diamond_block
```
- 動物園
```
/rtask world2 1 1
```
- 水族館
```
/rtask water1 1 1
```
- TNT流星群
```
/rtask tnt4 600 1
```
- 白馬の王子様
```
/rtask leon 1 1
```
```
/rtask weather1 1 1
```
- 炎ミサイル
```
/rtask blazephantom1 200 200
```
- TNT大爆発
```
/execute at @p run fill 7 37 -7 -7 51 7 minecraft:tnt
```
- 領域展開
```
/rtask world1 1 1
```
- 巨大ゾンビ群
```
/rtask ghastgiant1 200 200
```
- 星から星へ+ライオン
```
/execute at @p run fill 7 37 -7 -7 51 7 minecraft:tnt
```
```
/rtask ghastgiant1 200 200
```
- ワールド崩壊
```
/rtask tnt2 600 100
```
