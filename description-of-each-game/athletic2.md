---
label: 【アスレチック】の説明
order: 699997
---
スタートアップゲーム名：
```未定```
# アスレチック説明動画
[!embed](https://)
:::danger 注意
※アスレチックのプレイ前に必ず見てください。
:::  

# ワールド説明

# 1. スポーン地点コマンド【左】
![コマンド1](/image/athletic4.png)

**①:ゴールを表示します**

**②:ゴールを非表示にします**

**③:ゴール目標を+1します**

**④:ゴール目標を-1します**

**⑤:ゴールを+1します**

**⑥:ゴールを-1します**

**⑦:初期装備がもらえます**

**⑧:MOBを全部killします**

# 2. 水族館を止めるボタン
![コマンド2](/image/athletic3.png)

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
- ミニ回復
```
/effect give @p minecraft:regeneration 5 5
```
- ゾンビ
```
/summon minecraft:zombie ~ ~2 ~6 
```
- スケルトン
```
/summon minecraft:skeleton ~ ~2 ~6 {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:""minecraft:bow"",Count:1},{}]}
```
- 目隠し
```
/execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- 殺人うさぎ
```
/execute at @p run summon minecraft:rabbit ~ ~2 ~6 {RabbitType:99}
```
- エンダーマン
```
/summon minecraft:enderman ~ ~2 ~6 
```
- 防具付きゾンビ
```
/summon minecraft:zombie ~ ~2 ~6 {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:""minecraft:iron_sword"",Count:1}],ArmorItems:[{},{},{},{id:""minecraft:iron_helmet"",Count:1}]}
```
- ハスク
```
/summon minecraft:husk ~ ~2 ~6 
```
- クリーパー
```
/summon minecraft:creeper ~ ~2 ~6 
```
- 豚x10
```
/summon minecraft:pig ~ ~2 ~6 
```
- ノックバックスケルトン
```
/summon skeleton ~ ~2 ~6 {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:""bow"",Count:1b,tag:{Enchantments:[{id:""punch"",lvl:4}]}}],ArmorItems:[{},{},{},{id:""iron_helmet"",Count:1b}]}
```
- エンダーマンx2
```
/summon minecraft:enderman ~ ~2 ~6 
```
- 防具つきゾンビx2
```
/summon minecraft:zombie ~ ~2 ~6 {CustomName:'{""text"":""{user.profileName}""}',CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:""minecraft:iron_sword"",Count:1}],ArmorItems:[{},{},{},{id:""minecraft:iron_helmet"",Count:1}]}
```
- 回復
```
/effect give @p minecraft:regeneration 15 5
```
- 豚10匹
```
/summon minecraft:pig ~ ~2 ~6 
```
- ゴキブリx3
```
/summon minecraft:silverfish ~ ~2 ~6 
```
- クモの巣
```
/execute as @p run fill ~ ~ ~1 ~ ~ ~1 minecraft:cobweb
```
- 空腹
```
/effect give @p minecraft:hunger 30 255
```
- TNT
```
/execute at @p run summon tnt ~ ~2 ~6 {fuse:10}
```
- 50ブロック戻る
```
/tp @p ~ 0 ~-50
```
- 大ジャンプ
```
/effect give @p minecraft:levitation 1 25
```
- 肩車ゾンビx50
```
/rtask zombie2 50 100
```
- ゾンビx100
```
/rtask zombie1 100 100
```
- カミナリ
```
/execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
```
- 金床の雨
```
/rtask anvil1 1 1
```
- 黒曜石追加
```
/execute at @p run fill ~2 ~ ~5 ~-2 ~1 ~5 minecraft:obsidian
```
- 魔法使い
```
/summon minecraft:illusioner ~ ~2 ~6 
```
- 氷塊
```
/execute as @p run fill ~-1 ~ ~-1 ~1 ~2 ~1 minecraft:ice
```
- 雷+ねこパーティー
```
/execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
```
```
/rtask cat1 30 4
```
- ルーレット
```
/roulette GamingKeyboard
```
- 耐電クリーパー
```
/rtask creeper1 25 100
```
- TNTx3
```
/rtask tnt3 1 1
```
- クモの巣の雨
```
/rtask cobweb1 15 200
```
- 激おこ犬
```
/rtask wolf1 25 100
```
- ドラゴン
```
/rtask dragon2 1 1
```
- ルーレット
```
/roulette roulette2
```
- お助け
```
/tp @a 0 0 900
```
- アイテム没収
```
/clear @p
```
- 爆撃TNT
```
/rtask tnt4 3 10000
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
/rtask train1 1 1
```
- 15分雷雨
```
/rtask weather1 1 1
```
- ラベジャーx2
```
/summon minecraft:ravager ~ ~2 ~6 
```
- 蜘蛛の巣壁
```
/execute at @p run fill 11 -10 ~15 -11 10 ~17 minecraft:cobweb replace minecraft:air
```
- マグマの塔
```
/rtask lava1 1 1
```
- ウィザー
```
/timemob minecraft:wither 600 ~ ~2 ~15
```
- ウォーデン
```
/timemob minecraft:warden 900 ~ ~2 ~6
```
- チキンパーティー
```
/rtask chicken1 300 200
```
- 超お助け
```
/rtask ArcadeGame1 1 1
```
- 最強戦士
```
/rtask warden1 1 1
```
- 5分異常気象
```
/rtask weather2 1 1
```
- 動物園
```
/rtask zoo1 20 200
```
- 水族館
```
/rtask aquarium1 1 1
```
- 白馬の王子様
```
/rtask leon1 1 1
```
```
/rtask weather1 1 1
```
- 炎ミサイル
```
/rtask blazephantom1 50 200
```
- TNT大爆発
```
/rtask tnt6 1 1
```
- 領域展開
```
/rtask world2 1 1
```
- 巨大ゾンビ群
```
/rtask lion1 1 1
```
- 星から星へ x ライオン
```
/rtask tnt6 1 1
```
```
/rtask lion1 1 1
```
- ワールド崩壊
```
/rtask tiktokuniverse1 1 1
```
