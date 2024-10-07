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
- ハートミー:ミニ回復
```
/effect give @p minecraft:regeneration 5 5
```
- バラ:ゾンビ
```
/summon minecraft:zombie ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,Attributes:[{Name:"generic.max_health",Base:10}],Health:10.0f}
```
- GG:スケルトン
```
/summon minecraft:skeleton ~ ~ ~ 
```
- ソフトクリーム:目隠し
```
/execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- リスと松ぼっくり:目隠し
```
/execute at @p run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- フィンガーハート:殺人うさぎ
```
/execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99}
```
- ニャオ:エンダーマン
```
/summon minecraft:enderman ^ ^2 ^2 
```
- インスタントヌードル:防具付きゾンビ
```
/summon minecraft:zombie ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"minecraft:iron_helmet",Count:1}]}
```
- 御守り:ハスク
```
/summon minecraft:husk ~ ~ ~ 
```
- www:クリーパー
```
/summon minecraft:creeper ~ ~ ~ 
```
- ゲームパッド:牛x5
```
/summon minecraft:cow ~ ~ ~ 
```
- ローザ:ファイヤースケルトン
```
/summon skeleton ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"bow",Count:1b,tag:{Enchantments:[{id:"flame",lvl:1}]}}],ArmorItems:[{},{},{},{id:"iron_helmet",Count:1b}]}
```
- 友情ネックレス:クリーパー
```
/summon minecraft:creeper ~ ~ ~ 
```
- ヴェノム:クリーパー
```
/summon minecraft:creeper ~ ~ ~ 
```
- レイブダンス:エンダーマンx2
```
/summon minecraft:enderman ^ ^2 ^2 
```
- かき氷:防具つきゾンビx2
```
/summon minecraft:zombie ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"minecraft:iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"minecraft:iron_helmet",Count:1}]}
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
/summon minecraft:pig ~ ~ ~ 
```
- ありがとう:回復
```
/effect give @p minecraft:regeneration 15 5
```
- ドーナッツ:ゴキブリx3
```
/summon minecraft:silverfish ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,Attributes:[{Name:"generic.max_health",Base:5}],Health:5.0f}
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
/execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```
- スター:大ジャンプ
```
/effect give @p minecraft:levitation 1 100
```
- ゲームコントローラー:肩車ゾンビx50
```
/task zombie2 50 2
```
- クラッカー:ゾンビx100
```
/task zombie1 100 2
```
- ハンドハート:魔法使い
```
/summon minecraft:illusioner ~ ~ ~ 
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
- ニット帽:氷塊
```
/execute as @p run fill ~-1 ~ ~-1 ~1 ~2 ~1 minecraft:ice
```
- びよ～ん:シュルカー
```
/summon minecraft:shulker ~ ~ ~ 
```
- 髪をなでる:シュルカー
```
/summon minecraft:shulker ~ ~ ~ 
```
- 花冠:氷塊
```
/execute as @p run fill ~-1 ~ ~-1 ~1 ~2 ~1 minecraft:ice
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
/task powercreeper1 25 2
```
- ボクシンググローブ:TNT
```
/execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```
- アヒル:クモの巣xスケルトン
```
/task cobweb1 1 1
```
- フルーツの友達:激おこ犬
```
/task wolf1 25 3
```
- いたずら好きな鶏:クモの巣xスケルトン
```
/task cobweb1 1 1
```
- 招きねこ:ネコパーティー
```
/task cat1 100 2
```
- サンゴ:水の塔
```
/execute at @p run fill 0 64 0 0 64 0 minecraft:water
```
- マネーガン:アイテム没収
```
/clear @p
```
- すばらしい！:爆撃TNT
```
/task tptnt1 1 1
```
- ハグ:お助け
```
/execute at @p run fill 7 37 7 -7 45 -7 minecraft:gold_block
```
- お疲れさま:監獄
```
/task kangoku1 1 1
```
- ライオンのたてがみ:お助け
```
/execute at @p run fill 7 37 7 -7 45 -7 minecraft:gold_block
```
- 白鳥:全員集合
```
/execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```
- 列車:砂追加
```
/execute at @p run fill -8 200 8 8 200 -8 minecraft:light_blue_concrete_powder
```
- Travel with You:15分強制雨
```
/task weather1 1 1
```
- ラブリーミュージック:ラベジャーx2
```
/summon minecraft:ravager ~ ~ ~ 
```
- 銀河:マグマの塔
```
/execute at @p run fill 0 62 0 0 62 0 lava
```
- マジカルキャット:ラベジャーx2
```
/summon minecraft:ravager ~ ~ ~ 
```
- フラワーミラー:ウォーデン
```
/summon minecraft:warden ~ ~ ~
```
- キリン:ウォーデン
```
/summon minecraft:warden ~ ~ ~
```
- 花火:チキンパーティー
```
/task redstonetorch1 1 1
```
- ドラムセット:チキンパーティー
```
/task redstonetorch1 1 1
```
- アーケードゲーム:超お助け
```
/task ArcadeGame1 1 1
```
- 配信者のセットアップ:最強戦士
```
/task warden1 1 1
```
- 不思議な花火:ブロック変換
```
/execute at @p run fill 7 37 7 -7 51 -7 minecraft:blue_wool replace minecraft:diamond_block
```
- クジラのダイビング:動物園
```
/task world2 1 1
```
- オートバイ:水族館
```
/task water1 1 1
```
- 流星群:TNT流星群
```
/task tnt4 1200 1
```
- 子猫のレオン:白馬の王子様
```
/task leon 1 1
```
- スポーツカー:炎ミサイル
```
/task blazephantom1 200 4
```
- 星から星へ:TNT大爆発
```
/execute at @p run fill 7 37 -7 -7 51 7 minecraft:tnt
```
- ローザの星雲:領域展開
```
/task world1 1 1
```
- ライオン:巨大ゾンビ群
```
/task ghastgiant1 200 4
```
- TikTok Universe:ワールド崩壊
```
/task tnt2 1200 2
```
