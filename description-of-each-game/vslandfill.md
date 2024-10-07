---
label: 【埋め立てバトル】の説明
order: 69000
---

# 埋め立て説明動画  
[!embed](https://youtu.be/KkGKXygxz00)
:::danger 注意
※埋め立てバトルのプレイ前に必ず見てください。
:::  

## バトルサーバーへの接続方法
[予約システム](https://docs.libertasmc.xyz/how-to-use-reserve-system/basic/)を使用して、サーバーに接続します。  
詳細なステップは以下の通りです。  
1. **上記ページの「予約方法」を参考に「埋め立てバトル」サーバーを予約する**
2. **上記ページの「予約したサーバーにサブユーザーを追加する」を参考に対戦相手をサーバーへ招待する**
3. **同じサーバーに入り、どちらかのユーザーがマイクラ内でコマンドを実行する**
```
/tp @s [相手のMinecraftID]
```
例： /tp @s az__ao

## ワールド説明

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
○○祭りが来た時にレバーを引くと、妨害が強制で止まります。
![妨害終了ボタン](/image/test２.gif)

6. **TNTボタン**  
ボタンを押すことで、TNTが5つ出ます。
![TNTボタン](/image/battle7.png)

7. **コマンド**  
ワールド操作や、難易度の設定ができます。
![コマンド](/image/battle8.png)

8. **テレポートコマンド**  
鉄の扉の奥にあるボタンを押すと、初期地にテレポートできます。
![テレポート](/image/battle9.png)


## コマンド一覧

### 基本的なコマンド一覧

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

- ダイヤブロックチーム全消し
```
/execute at @p run fill 10 51 7 24 37 -7 minecraft:air
```

- 金ブロックチーム全消し
```
/execute at @p run fill -24 51 7 -10 37 -7 minecraft:air
```

- サーバー再起動
```
/restart
```

### ギフトコマンド一覧  
- ハートミー:ミニ回復
```
/effect give @p minecraft:regeneration 5 5
```
- バラ:ゾンビ
```
/execute at @p[distance=1..] run summon minecraft:zombie ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,Attributes:[{Name:"generic.max_health",Base:10}],Health:10.0f}
```
- GG:スケルトン
```
/execute at @p[distance=1..] run summon minecraft:skeleton ~ ~ ~ 
```
- ソフトクリーム:目隠し
```
/execute at @p[distance=1..] run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- リスと松ぼっくり:目隠し
```
/execute at @p[distance=1..] run particle minecraft:explosion ~ ~1 ~ 0.5 0.5 0.5 0.1 100
```
- フィンガーハート:殺人うさぎ
```
/execute at @p[distance=1..] run execute at @p run summon minecraft:rabbit ~ ~ ~ {RabbitType:99}
```
- ニャオ:エンダーマン
```
/execute at @p[distance=1..] run summon minecraft:enderman ^ ^2 ^2 
```
- インスタントヌードル:防具付きゾンビ
```
/execute at @p[distance=1..] run summon zombie ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"iron_helmet",Count:1}]}
```
- 御守り:ハスク
```
/execute at @p[distance=1..] run summon minecraft:husk ~ ~ ~ 
```
- www:クリーパー
```
/execute at @p[distance=1..] run summon minecraft:creeper ~ ~ ~ 
```
- ゲームパッド:牛x5
```
/execute at @p[distance=1..] run summon minecraft:cow ~ ~ ~ 
```
- ローザ:ファイヤースケルトン
```
/execute at @p[distance=1..] run summon skeleton ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"bow",Count:1b,tag:{Enchantments:[{id:"flame",lvl:1}]}}],ArmorItems:[{},{},{},{}]}
```
- 友情ネックレス:クリーパー
```
/execute at @p[distance=1..] run summon minecraft:creeper ~ ~ ~ 
```
- ヴェノム:クリーパー
```
/execute at @p[distance=1..] run summon minecraft:creeper ~ ~ ~ 
```
- レイブダンス:エンダーマンx2
```
/execute at @p[distance=1..] run summon minecraft:enderman ^ ^2 ^2 
```
- かき氷:防具つきゾンビx2
```
/execute at @p[distance=1..] run summon zombie ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,HandItems:[{id:"iron_sword",Count:1}],ArmorItems:[{},{},{},{id:"iron_helmet",Count:1}]}
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
/execute at @p[distance=1..] run summon minecraft:pig ~ ~ ~ 
```
- ありがとう:回復
```
/effect give @p minecraft:regeneration 15 5
```
- ドーナッツ:ゴキブリx3
```
/execute at @p[distance=1..] run summon minecraft:silverfish ~ ~ ~ {CustomNameVisible:1,PersistenceRequired:1b,Attributes:[{Name:"generic.max_health",Base:5}],Health:5.0f}
```
- ホットチョコレート:クモの巣
```
/execute at @p[distance=1..] run fill ~ ~ ~ ~ ~ ~ minecraft:cobweb
```
- キャップ:空腹
```
/execute at @p[distance=1..] run effect give @p minecraft:hunger 30 255
```
- 折り鶴:TNT
```
/execute at @p[distance=1..] run execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```
- スター:大ジャンプ
```
/execute at @p[distance=1..] run effect give @p minecraft:levitation 1 100
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
/execute at @p[distance=1..] run summon minecraft:illusioner ~ ~ ~ 
```
- 柴犬:カミナリ
```
/execute at @p[distance=1..] run execute at @e[type=!minecraft:player,limit=30] run summon minecraft:lightning_bolt ~ ~ ~
```
- 鍵と鍵穴:金床の雨
```
/task anvil1 1 1 50
```
- サングラス:どっちもゾンビx100
```
/task zombie3 100 2
```
- ハート:黒曜石追加
```
/execute at @p[distance=1..] run summon minecraft:falling_block ~ ~10 ~ {BlockState:{Name:"minecraft:obsidian"},Time:1}
```
- 愛してる:どっちもTNT
```
/execute at @p[distance=1..] run execute at @p run summon tnt ~ ~5 ~ {fuse:100}
```
- 髪をなでる:シュルカー
```
/execute at @p[distance=1..] run summon minecraft:shulker ~ ~ ~ 
```
- 花冠:氷塊
```
/execute at @p[distance=1..] run fill ~-1 ~ ~-1 ~1 ~2 ~1 minecraft:ice
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
/execute at @p[distance=1..] run execute at @p run summon tnt ~ ~5 ~ {fuse:100}
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
/execute at @p[distance=1..] run fill ~ ~5 ~ ~ ~5 ~ minecraft:water
```
- マネーガン:アイテム没収
```
/execute at @p[distance=1..] run clear @p
```
- すばらしい！:爆撃TNT
```
/task tptnt1 1 1
```
- ライオンのたてがみ:監獄
```
/task kangoku1 1 1
```
- 白鳥:全員集合
```
/execute at @p[distance=1..] run execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~

```
- 列車:砂追加
```
/task battle1 1 1
```
- Travel with You:15分強制雨
```
/task weather1 1 1
```
- ラブリーミュージック:ラベジャーx2
```
/execute at @p[distance=1..] run summon minecraft:ravager ~ ~ ~ 
    - /execute at @p[distance=1..] run summon minecraft:ravager ~ ~ ~ 
```
- 銀河:マグマの塔
```
/execute at @p[distance=1..] run fill ~ ~5 ~ ~ ~5 ~ minecraft:lava
```
- キリン:ウォーデン
```
/execute at @p[distance=1..] run summon minecraft:warden ~ ~ ~
```
- 花火:チキンパーティー
```
/task chicken1 1000 2
```
- ドラムセット:チキンパーティー
```
/task chicken1 1000 2
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
/task water1 150 2
```
- 子猫のレオン:白馬の王子様
```
/task leon 1 1
```
- スポーツカー:炎ミサイル
```
/task blazephantom1 100 4
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
