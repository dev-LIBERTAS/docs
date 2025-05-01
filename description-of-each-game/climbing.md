---
label: 【クライミング】の説明
order: 699998
---
スタートアップゲーム名：
```climbing```
# クライミング説明動画
[!embed](https://youtu.be/altSgy051t8)
:::danger 注意
※クライミングのプレイ前に必ず見てください。
:::  

# ワールド説明
### ワールド全体図
![ワールド全体図](/image/c1.png)

# 1. スポーン地点コマンド【左】
![コマンド1](/image/c100.png)

**①:初期装備が手に入ります**

**②:カートをすべて消去します**

**③:マグマを消去します**

**④:水を消去します**

**⑤:金床をすべて消去します**

# 2. スポーン地点コマンド【右】
![コマンド2](/image/c101.png)

**①:ゴールゲージのゲージを上げます**

**②:ゴールゲージのゲージの上限を増やします**

**③:ゴールゲージを非表示にします**

**④:ゴールゲージのゲージを下げます**

**⑤:ゴールゲージのゲージの上限を減らします**

**⑥:ゴールゲージを表示します**

# 3. テレポートボタン
最上層にはスポーン地点に戻れるテレポートボタンがあります。
![TPボタン](/image/c2.png)

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
※1回分のコマンドです。回数分繰り返して入力してください。

- ミニ回復
```
/effect give @p minecraft:regeneration 5 5
```
- ゾンビ
```
/summon minecraft:zombie ~ ~3 ~2 {CustomNameVisible:1,Attributes:[{Name:"generic.max_health",Base:10}],Health:10.0f}
```
- スケルトン
```
/summon minecraft:skeleton ~ ~3 ~2 {CustomNameVisible:1,HandItems:[{id:"minecraft:bow",Count:1},{}]}
```
- 目隠し
```
/execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- トロッコx1
```
/mobspawner:spawner shotcart CREEPER 10 2 2 all 0 15 15 0 -1 -1
```
- エンダーマン
```
/summon minecraft:enderman ~ ~3 ~2 {CustomNameVisible:1}
```
- 防具付きゾンビ
```
/summon minecraft:zombie ~ ~3 ~2 {CustomNameVisible:1,HandItems:[{id:"minecraft:iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"minecraft:iron_helmet",Count:1}]}
```
- クリーパー
```
/summon minecraft:creeper ~ ~3 ~2 {CustomNameVisible:1}
```
- 牛x5
```
/summon minecraft:cow ~ ~3 ~2 {CustomNameVisible:1}
```
- ノックバックスケルトン
```
/summon skeleton ~ ~3 ~2 {CustomNameVisible:1,HandItems:[{id:"bow",Count:1b,tag:{Enchantments:[{id:"punch",lvl:4}]}}],ArmorItems:[{},{},{},{id:"iron_helmet",Count:1b}]}
```
- エンダーマンx2
```
/summon minecraft:enderman ~ ~3 ~2 {CustomNameVisible:1}
```
- 防具つきゾンビx2
```
/summon minecraft:zombie ~ ~3 ~2 {CustomNameVisible:1,HandItems:[{id:"minecraft:iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"minecraft:iron_helmet",Count:1}]}
```
- 回復
```
/effect give @p minecraft:regeneration 15 5
```
- 豚10匹
```
/summon minecraft:pig ~ ~3 ~2 {CustomNameVisible:1}
```
- 豚5x牛5
```
/summon minecraft:pig ~ ~3 ~2 {CustomNameVisible:1}
```
- トロッコ列
```
/rtask cart2 1 1
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
/rtask tnt3 1 1
```
- 大ジャンプ
```
/effect give @p minecraft:levitation 1 25
```
- 肩車ゾンビx50
```
/rtask zombie2 15 200
```
- ゾンビx100
```
/rtask zombie1 30 200
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
/execute at @p run summon minecraft:falling_block ~ ~10 ~ {BlockState:{Name:"minecraft:obsidian"},Time:1}
```
- 耐電クリーパー
```
/rtask tnt3 1 1
```
- ルーレット
```
/roulette GamingKeyboard
```
- 耐電クリーパー
```
/rtask powercreeper1 40 100
```
- 大量トロッコ
```
/rtask cart3 5 50
```
- 激おこ犬
```
/rtask wolf1 25 150
```
- ネコパーティー
```
/rtask cat1 30 200
```
- テレポート
```
/tp @a 0 223 285
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

```
- ドラゴン群
```
/rtask dragon1 1 1
```
- ダイヤ装備
```
/rtask diamond1 1 1
```
- 強制晴れ
```
/weather clear
```
- 全員集合
```
/execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```
- 砂追加
```
/execute at @p run fill ~50 ~30 ~10 ~-50 ~45 ~10 minecraft:sand replace minecraft:air
```
- 15分強制雨
```
/rtask weather1 1 1
```
- ラベジャーx2
```
/summon minecraft:ravager ~ ~3 ~2 {CustomNameVisible:1}
```
- ウィザー
```
/timemob minecraft:wither 300 ~ ~3 ~2
```
- ウォーデン
```
/timemob minecraft:warden 900 ~ ~3 ~2
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
- 動物園
```
/rtask world2 1 1
```
- 水族館
```
/rtask water1 100 300
```
- 白馬の王子様
```
/rtask leon 1 1
```
- ジャイアントゾンビ群
```
/rtask sportscar1 1 1
```
- ワールド崩壊
```
/rtask dragon2 2 500
```
- 領域展開
```
/rtask world1 1 1
```
- ハッピーセット
```
/rtask lion1 1 1
```
- 滅亡
```
/rtask tiktokuniverse1 1 1
```
