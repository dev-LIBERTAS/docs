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
- ハートミー:ミニ回復
```
/effect give @p minecraft:regeneration 5 5
```
- バラ:ゾンビ
```
/summon minecraft:zombie ~ ~3 ~2 {CustomNameVisible:1,PersistenceRequired:1b,Attributes:[{Name:"generic.max_health",Base:10}],Health:10.0f}
```
- GG:スケルトン
```
/summon minecraft:skeleton ~ ~3 ~2 {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:bow",Count:1},{}]}
```
- ソフトクリーム:目隠し
```
/execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- フィンガーハート:トロッコx1
```
/mobspawner:spawner shotcart CREEPER 10 2 2 all 0 15 15 0 -1 -1
```
- ニャオ:エンダーマン
```
/summon minecraft:enderman ~ ~3 ~2 
```
- インスタントヌードル:防具付きゾンビ
```
/summon minecraft:zombie ~ ~3 ~2 {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:iron_sword",Count:1}],HandDropChances:[0.0f]}
```
- 御守り:ハスク
```
/summon minecraft:husk ~ ~3 ~2 
```
- www:クリーパー
```
/summon minecraft:creeper ~ ~3 ~2 
```
- ゲームパッド:牛x5
```
/summon minecraft:cow ~ ~3 ~2 
```
- ローザ:ファイヤースケルトン
```
/summon minecraft:skeleton ~ ~3 ~2 {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:bow",Count:1b,tag:{Enchantments:[{id:"minecraft:flame",lvl:1}]}}],ArmorItems:[{},{},{},{}]}
```
- 友情ネックレス:クリーパー
```
/summon minecraft:creeper ~ ~3 ~2 
```
- ヴェノム:クリーパー
```
/summon minecraft:creeper ~ ~3 ~2 
```
- レイブダンス:エンダーマンx2
```
/summon minecraft:enderman ~ ~3 ~2 
```
- かき氷:防具つきゾンビx2
```
/summon minecraft:zombie ~ ~3 ~2 {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"minecraft:iron_helmet",Count:1}]}
```
- 筋肉ムキムキ:回復
```
/effect give @p minecraft:regeneration 15 5
```
- 愛してる:回復
```
/effect give @p minecraft:regeneration 15 5
```
- 香水:豚10匹
```
/summon minecraft:pig ~ ~3 ~2 
```
- ありがとう:回復
```
/effect give @p minecraft:regeneration 15 5
```
- ドーナッツ:トロッコ列
```
/task cart2 2 20
```
- ホットチョコレート:クモの巣
```
/execute as @p run fill ~ ~ ~ ~ ~ ~ minecraft:cobweb
```
- キャップ:空腹
```
/effect give @p minecraft:hunger 30 255
```
- 折り鶴:TNT
```
/task tnt3 1 1
```
- スター:大ジャンプ
```
/effect give @p minecraft:levitation 1 25
```
- ゲームコントローラー:肩車ゾンビx50
```
/task zombie2 15 4
```
- クラッカー:ゾンビx100
```
/task zombie1 30 4
```
- ハンドハート:魔法使い
```
/summon minecraft:illusioner ~ ~3 ~2 
```
- 柴犬:カミナリ
```
/execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
```
- 鍵と鍵穴:金床の雨
```
/task anvil1 1 1 50
```
- ハート:黒曜石追加
```
/execute at @p run summon minecraft:falling_block ~ ~10 ~ {BlockState:{Name:"minecraft:obsidian"},Time:1}
```
- びよ～ん:シュルカー
```
/summon minecraft:shulker ~ ~3 ~2 
```
- 髪をなでる:シュルカー
```
/summon minecraft:shulker ~ ~3 ~2 
```
- ゲーマーキャット:雷+ねこパーティー
```
/execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
```
- ゲーミングキーボード:ルーレット
```
/roulette GamingKeyboard
```
- コーギー:耐電クリーパー
```
/task powercreeper1 40 2
```
- ボクシンググローブ:TNT
```
/task tnt3 1 1
```
- アヒル:大量トロッコ
```
/task cart3 5 26
```
- フルーツの友達:激おこ犬
```
/task wolf1 25 3
```
- 招きねこ:ネコパーティー
```
/task cat1 30 4
```
- マネーガン:アイテム没収
```
/clear @p
```
- すばらしい！:爆撃TNT
```
/task tnt4 3 200
```
- ハグ:テレポート
```
/tp @a 0 223 285
```
- スパゲッティのキス:ドラゴン群
```
/task dragon1 1 1
```
- タイムゴーグル:ダイヤ装備
```
/task diamond1 1 1
```
- ライオンのたてがみ:テレポート
```
/tp @a 0 223 285
```
- 白鳥:全員集合
```
/execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```
- 列車:砂追加
```
/execute at @p run fill ~50 ~30 ~10 ~-50 ~45 ~10 minecraft:sand replace minecraft:air
```
- Travel with You:15分強制雨
```
/task weather1 1 1
```
- ラブリーミュージック:ラベジャーx2
```
/summon minecraft:ravager ~ ~3 ~2 
```
- フラワーミラー:ウォーデン
```
/summon minecraft:warden ~ ~3 ~2
```
- キリン:ウォーデン
```
/summon minecraft:warden ~ ~3 ~2
```
- 花火:チキンパーティー
```
/task chicken1 300 4
```
- ドラムセット:チキンパーティー
```
/task chicken1 300 4
```
- アーケードゲーム:超お助け
```
/task ArcadeGame1 1 1
```
- 配信者のセットアップ:最強戦士
```
/task warden1 1 1
```
- クジラのダイビング:動物園
```
/task world2 1 1
```
- オートバイ:水族館
```
/task water1 100 6
```
- 子猫のレオン:白馬の王子様
```
/task leon 1 1
```
- スポーツカー:ジャイアントゾンビ群
```
/task sportscar1 1 1
```
- 星から星へ:ワールド崩壊
```
/task dragon2 2 10
```
- ローザの星雲:領域展開
```
/task world1 1 1
```
- ライオン:ハッピーセット
```
/task lion1 1 1
```
- TikTok Universe:滅亡
```
/task tiktokuniverse1 1 1
```
