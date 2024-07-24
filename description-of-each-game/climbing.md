---
label: 【クライミング】の説明
order: 699998
---
スタートアップゲーム名：
```climbing```

# ワールド説明
### ワールド全体図
![ワールド全体図](/image/c1.png)

1. **スポーン地点コマンド【左】**
![コマンド1](/image/c100.png)

**1:初期装備が手に入ります**

**2:カートをすべて消去します**

**3:マグマを消去します**

**4:水を消去します**

**5:金床をすべて消去します**

   
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
  /summon minecraft:zombie ~ ~3 ~2
```

- GG：スケルトン
```
  /summon minecraft:skeleton ~ ~3 ~2
```

- フィンガーハート：トロッコ
```
  /mobspawner:spawner shotcart CREEPER 10 2 2 all 0 15 15 0 -1 -1
```

- www：クリーパー
```
  /summon minecraft:creeper ~ ~3 ~2
```

- Gamepad：牛5匹
```
  /summon minecraft:cow ~ ~3 ~2
```

- 愛してる：回復
```
  /effect give @p minecraft:regeneration 15 5
```

- 香水：豚10匹
```
  /summon minecraft:pig ~ ~3 ~2
```

- ドーナッツ：カート2列
```
  /task cart2 2 20
```

- 折り鶴：TNT
```
  /task tnt3 1 1
```

- クラッカー：ゾンビx100
```
  /task zombie1 30 4
```

- ゲームコントローラー：肩車ゾンビx100
```
  /task zombie2 15 4
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
  /task powercreeper1 40 2
```

- アヒル：トロッコ群
```
  /task cart3 5 26
```

- 招きねこ：ねこパーティー
```
  /task cat1 30 4
```

- マネーガン：アイテム全回収
```
  /clear @p
```

- すばらしい！：爆撃TNTx3
```
  /task tnt4 3 200
```

- ハグ：テレポート
```
  /tp @a 0 223 285
```

- スパゲッティのキス：ドラゴン群
```
  /tp @a 0 223 285
```

- タームゴーグル：ダイヤモンド装備
```
  /task diamond1 1 1
```

- 白鳥：全員集合
```
  /execute at @p run tp @e[type=!minecraft:minecart] ~ ~ ~
```

- 列車：お邪魔ブロック
```
  /execute at @p run fill ~50 ~30 ~10 ~-50 ~45 ~10 minecraft:sand replace minecraft:air
```

- Travel with You：5分強制雨
```
  /task weather1 1 1
```

- フラワーミラー：ウォーデン
```
  /summon minecraft:warden ~ ~3 ~2
```

- 花火：チキン祭り
```
  /task chicken1 300 4
```

- ドラムセット：チキン祭り
```
  /task chicken1 300 4
```

- クジラのダイビング：動物園
```
  /task world2 1 1
```

- オートバイ：水族館
```
  /task water1 100 6
```

- 子猫のレオン：白馬の王子様
```
  /task leon 1 1
```

- スポーツカー：ジャイアントゾンビ群
```
  /task sportscar1 1 1
```

- 星から星へ：ワールド崩壊
```
  /task dragon2 2 10
```

- ローザの星雲：領域展開
```
  /task world1 1 1
```

- ライオン：ハッピーセット
```
  /task lion1 1 1
```

- TikTok Universe：滅亡
```
  /task tiktokuniverse1 1 1
```
