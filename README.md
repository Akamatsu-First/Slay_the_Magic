# Slay the Magic

**超高難易度のMinecraft用Modpackです。**

既存の高難易度Modpackでは物足りないと感じている方に向けて作りました。

探索と戦闘を繰り返して少しずつ強くなる点は他のModpackと同じですが、その中で大きく後退することが頻繁にあります。

三歩進んで二歩下がりながら成長していくことで、**厳しい環境の中でも強くなっていく手応え**と、終盤には**序盤に苦戦した敵を圧倒できる爽快感**を味わえます。

Minecraft Java Edition 1.20.1（Forge 47.4.10）向けで、Prism Launcher で遊ぶことを前提にしています。

- Slay the Magic の ZIP ファイルのダウンロード：[Releases](https://github.com/Akamatsu-First/Slay_the_Magic/releases)
- Prism Launcher のダウンロードページ：https://prismlauncher.org/

## ゲーム開始までの流れ

[![Slay the Magic 導入方法の動画](https://img.youtube.com/vi/E3YQHpYZHVE/hqdefault.jpg)](https://www.youtube.com/watch?v=E3YQHpYZHVE)

画像をクリックすると YouTube で動画が開きます。

**以下の 1〜7 の手順を行ってください。 4〜6 の手順は必須ではありませんが、飛ばしてしまうと敵が少々強くなりすぎてしまいます。**

1. 上記の URL から、Slay the Magic の ZIP ファイルと Prism Launcher をダウンロードする。ZIP ファイルは解凍しなくてよい。
2. Prism Launcher を開いたら右クリック →「起動構成の作成」を選択。
3. 画面左側の「インポート」を選択 → 右側に現れる「参照」をクリック → Slay the Magic の ZIP ファイルを開く。Mod を手動でダウンロードするよう求める画面が出た場合は、その表示に従う。
4. Prism Launcher のホーム画面に Slay the Magic の起動構成が現れるので、それを右クリック →「フォルダ」を選択。
5. 「minecraft」→「stm_patcher」をダブルクリック。
6. **「apply_patches.bat」をダブルクリック。黒い画面に「All done」と出たら成功。** 何かキーを押すと画面が閉じる。
7. Prism Launcher のホーム画面に戻り、ゲームを起動する。初めて起動するときは、Minecraft を購入した Microsoft アカウントでのログインを求められる。

**macOS や Linux でも遊べますが、「apply_patches.bat」は Windows 専用です。** 事前に PowerShell 7 をインストールし、手順 6 の代わりに「apply_patches.ps1」を PowerShell 7 で実行してください。

## ゲーム開始後の注意点

**プレイヤーは戦闘や探索で手に入れた物を頻繁に失います。** 

そのストレスに耐えられる方、またはそれを楽しめる方に向けて作っています。あらかじめご了承ください。

ほぼ全てのバイオームの気温と水温を、設定（config）でかなり極端にしています。最初のリスポーン地点が高熱地帯、氷雪地帯、小さな島のいずれかだった場合、死んでは戻るを繰り返すだけの、先に進めないワールドになる可能性が高いです。

平原から始まるシード値が出るまでワールドを作り直すか、平原から始まる以下のシード値をご活用ください。

1. `-2768723339874476026`
2. `-4569950041963369763`
3. `2754201205115493890`
4. `-4370708269050466061`
5. `-545196103679302789`
6. `7295840979621375230`
7. `-6789429203791271423`
8. `-2049309514411892063`
9. `6415133135356373995`
10. `-7625166061991109336`

一部のアイテムは、日本語に訳すときにニュアンスを少し変えています。そのため、日本語でのプレイをおすすめします。

## ボスの討伐順

**このゲームには合計 20 体のボスがいます。おすすめの討伐順を以下に載せています。**

この順番どおりでなくてもクリアはできますが、各ボスの強さの目安になると思いますので、ぜひご活用ください。かっこ内は、そのボスがいる場所、または現れる場所です。下の行ほど強く、同じ行の中では右にいくほど強くなります。

- デイムフォルトゥナ（廃村）／スワンプ・ジョー（高度 100 以上の高山）／エルダー・ガーディアン（海底神殿）
- ベルリンガー（湿地帯）／ロザリン（青色の森）／オーバーガーディアン（砂漠）／ネザライトの怪物（黒い工場）
- ウィザー（ネザー要塞）／ヴォイド・ブロッサム（繁茂した平原）／ハービンジャー（地下研究所）
- ストーカー（ネザー全域）／リヴァイアサン（深海都市）／エンシェント・レムナント（呪いのピラミッド）／イグニス（炎の闘技場）／マレディクタス（凍りついた城）
- スキュラ（氷雪地帯）／ロード・パンプキン・ヘッド（臓腑の溜まり場）／ウォーデン（冷たい砂漠）／エンダードラゴン（エンド本島）
- ???（エンダードラゴンを倒した後、ブラッドムーンの夜に、巨大な切り株）

## 動画本編とは異なる要素

**動画で紹介した仕様の一部は、Modの作者の権利に配慮するため、または実際に遊んで不便に感じたため、変更しています。**

- ゲーム開始時から、敵の魔法の威力が3倍になり、敵がアイテムを持ち、敵の装備にエンチャントが付いています。
- Apotheosisにより追加された装備強化の要素は最初から使えます。ロード・パンプキン・ヘッドを倒す必要はありません。
- ウォーデンとストーカーの体力と攻撃力は反比例する仕組みではなく、それぞれ別々の値になっています。
- 最終ボスはエンダードラゴンを倒した後のブラッドムーンの夜に、巨大な切り株へ行くと現れます。雪が降っている必要はありません。
- ウィザーはネザー要塞のみに湧きます。
- セットボーナスはプレイヤーのみに付与されます。
- 動画に登場した構造物やクラフトレシピの一部を削除しています。
- タイダルクローの性能が動画とは異なります。
- 一部の装備の能力値が動画とは異なります。
- 一部のボスの能力値が動画とは異なります。
- 一部の魔法の挙動が動画とは異なります。
- 一部のアイテム名が動画とは異なります。
- 一部の実績名が動画とは異なります。

## Modに加えた変更

このModpackでは以下の5つのModの一部を変更しています。どこをどのように変えたかを、すべてここに公開します（LGPLで公開されているModについては、ライセンスでも公開が求められています）。

変更は、ZIPに入っているパッチツール（stm_patcher）が、プレイヤーのパソコンにある公式のファイルに対して行います。ZIPに入っているのは書き換える部分のデータだけで、Modそのものは含んでいません。ここに書いた箇所以外は公式のファイルから変えていません。

コードは、変更したクラスファイルをJavaのソースコードに戻して表示したものです（名前の一部は、読みやすいように元の名前に置き換えています）。

### Bloodmoon Update

- 対象のファイル：`bloodmoon-1.20.1-1.4.1-forge-1.20.1.jar`
- ライセンス：MIT
- 配布ページ：https://www.curseforge.com/minecraft/mc-mods/bloodmoon-update
- 変更点：下の表のとおり

| クラス | 変更前 | 変更後 | 内容 |
|---|---|---|---|
| `BloodmoonManagerProcedure` の `onWorldTick` | （なし） | 先頭に「オーバーワールド以外なら何もしない」処理を追加 | ブラッドムーンの進行をオーバーワールドだけで行う |
| `graphics/RedOverlayRenderProcedure` | 描く位置 `"hotbar"`、通常の描き方 | 描く位置 `"vignette"`、画面効果用の描き方 | 赤い画面の効果が体力などの表示の上に重ならないようにする |
| `mobs/ArmorDurabilityAmplifier` | `Math.random() < 0.005` | `Math.random() < 0.0` | 防具の耐久値を一度に大きく削る効果をなくす |
| `mobs/WeaponDurabilityAmplifier` | `Math.random() < 0.05` | `Math.random() < 0.0` | 武器の耐久値を一度に大きく削る効果をなくす |
| `mobs/MobSpawnRateProcedure` の `onPlayerTick` | 毎tick 追加のMOBを出す処理を呼ぶ | 中身を空にする | ブラッドムーン中の追加の湧きを止める（KubeJS で作り直している） |
| `mobs/SqueletonArrowsProcedure` の `onEntityTick` | 毎tick スケルトンの追加の矢の処理を呼ぶ | 中身を空にする | スケルトンの追加の矢を止める（KubeJS で作り直している） |
| `mobs/MobsArmorRateProcedure` の `execute` | 防具・武器を持たせるだけ | 持たせた直後に落とす確率を 0 にする処理を追加 | ブラッドムーンのMOBが持つ装備を倒しても落とさないようにする |

（クラスはすべて `net/foufakirby/bloodmoon/procedures/` の下にあります）

### Cataclysm: Spellbooks

- 対象のファイル：`cataclysm_spellbooks-1.2.7-1.20.1-all.jar`
- ライセンス：LGPL 2.1（GNU Lesser General Public License v2.1）
- 公式のソースコード：https://github.com/AceTheEldritchKing/Cataclysm_Spellbooks
- 変更点：下の表のとおり（どれも数値の変更だけです）

| クラス | 変更前 | 変更後 | 内容 |
|---|---|---|---|
| `spells/abyssal/AbyssalSlashSpell` | `radius = 4.1f` | `radius = 8.2f` | Abyssal Slash の攻撃範囲を 2 倍にする |
| `spells/blood/FinalRendSpell` | `radius = 3.25f` | `radius = 6.5f` | Final Rend の攻撃範囲を 2 倍にする |
| `spells/blood/FinalRendSpell` | 画面の揺れの強さ `0.08f` | `0.0f` | Final Rend の画面の揺れをなくす |
| `spells/ice/CryopiercerSpell` | 再詠唱の受付時間 `200` | `66` | Cryopiercer の再詠唱できる時間を 10 秒から約 3.3 秒にする |
| `spells/ice/CryopiercerSpell` | `setFreezeTicks(200)` | `setFreezeTicks(66)` | Cryopiercer で凍える時間を 10 秒から約 3.3 秒にする |
| `entity/spells/bullets/FrozenBulletProjectile` | `setDuration(300)` | `setDuration(40)` | 氷の塊に閉じ込める時間を 15 秒から 2 秒にする |

（クラスはすべて `net/acetheeldritchking/cataclysm_spellbooks/` の下にあります）

### YUNG's Better End Island

- 対象のファイル：`YungsBetterEndIsland-1.20-Forge-2.0.6.jar`
- ライセンス：LGPL 3.0（GNU Lesser General Public License v3.0）
- 公式のソースコード：https://github.com/yungnickyoung/YUNGs-Better-End-Island
- 変更点：`com/yungnickyoung/minecraft/betterendisland/mixin/EndDragonFightMixin` の `betterendisland_tickFight`
- 内容：本家のエンダードラゴンの体力バーを常に表示しないようにする

```java
// 変更前
this.dragonEvent.setVisible(!this.dragonKilled && this.betterendisland$hasDragonEverSpawned);
// 変更後
this.dragonEvent.setVisible(!this.dragonKilled && this.betterendisland$hasDragonEverSpawned ? false : false);
```

### The Twilight Forest

- 対象のファイル：`twilightforest-1.20.1-4.3.2508-universal.jar`
- ライセンス：LGPL 2.1（コード部分）
- 公式のソースコード：https://github.com/TeamTwilight/twilightforest
- 変更点：`twilightforest/entity/projectile/SeekerArrow` の 2 つのコンストラクタ
- 内容：Seeker Bow の矢の基本ダメージを 1.0 から 6.0 にする

```java
// 変更前
this.setBaseDamage(1.0);
// 変更後
this.setBaseDamage(6.0);
```

### The Trembling Earth

- 対象のファイル：`The_Trembling_Earth-M5.0_hotfix(1.20.1).jar`
- 作者：victo
- ライセンス：[Academic Free License 3.0](https://opensource.org/license/AFL-3.0)（CurseForge の配布ページの表記）
- 配布ページ：https://www.curseforge.com/minecraft/mc-mods/the-trembling-earth
- ライセンスの表示：The Trembling Earth is licensed under the Academic Free License version 3.0. このModpackでは、下に書いた箇所を変更しています。変更後の部分にも、同じライセンスの条件が適用されます。
- 変更点：下の表のとおり（地震・崩落の計算式、確率、ブロックの置き換え方は変えていません）

| クラス | 変更前 | 変更後 | 内容 |
|---|---|---|---|
| `BlockQuakingProcedure` の `onWorldTick` | （なし） | 先頭に「オーバーワールド以外なら何もしない」処理を追加 | 地震をオーバーワールドだけで起こす |
| `CollapseTriggerProcedure` の `onWorldTick` | （なし） | 先頭に「オーバーワールド以外なら何もしない」処理を追加 | 崩落をオーバーワールドだけで起こす |
| `BlockQuakingProcedure`・`CollapseProcedure`・`CollapseTriggerProcedure` | `world.getBlockState(pos)` | `StmChunkGuard.state(world, pos)` | 地形を調べる処理を置き換え（127 か所） |
| 同上 | `world.isEmptyBlock(pos)` | `StmChunkGuard.empty(world, pos)` | 同上（13 か所） |
| 同上 | `world.getHeight(type, x, z)` | `StmChunkGuard.height(world, type, x, z)` | 同上（5 か所） |
| `StmChunkGuard`（新しいクラス） | （なし） | このModpackで追加 | まだ読み込まれていない地形を調べようとしたときに、読み込みを待ってサーバーが止まるのを防ぐ |

（クラスはすべて `net/mcreator/thetremblingearth/procedures/` の下にあります）

```java
// onWorldTick の先頭に追加した処理（BlockQuakingProcedure・CollapseTriggerProcedure）
if (!event.level.dimension().equals(Level.OVERWORLD)) {
    return;
}
```

```java
// 置き換えの例（BlockQuakingProcedure）
// 変更前
if (world.getBlockState(BlockPos.containing(tx, ty, tz)).is(BlockTags.create(new ResourceLocation("minecraft:logs")))) {
// 変更後
if (StmChunkGuard.state(world, BlockPos.containing(tx, ty, tz)).is(BlockTags.create(new ResourceLocation("minecraft:logs")))) {
```

```java
// 追加したクラス StmChunkGuard（全文）
// 調べる場所の周り（前後左右 8 ブロック）が読み込み済みなら元と同じ値を返し、
// 読み込まれていなければ地形を読み込まずに「空気」「何もない」「高さ -100000」を返して、その場所の処理を飛ばす
package net.mcreator.thetremblingearth.procedures;

public final class StmChunkGuard {
    public static final int MARGIN = 8;
    public static final int SKIP_Y = -100000;

    private StmChunkGuard() {
    }

    private static boolean areaReady(ServerChunkCache cache, int x, int z) {
        return cache.getChunkNow(x - 8 >> 4, z - 8 >> 4) != null
            && cache.getChunkNow(x + 8 >> 4, z - 8 >> 4) != null
            && cache.getChunkNow(x - 8 >> 4, z + 8 >> 4) != null
            && cache.getChunkNow(x + 8 >> 4, z + 8 >> 4) != null;
    }

    public static boolean ready(LevelAccessor world, int x, int z) {
        if (world instanceof ServerLevel) {
            return areaReady(((ServerLevel) world).getChunkSource(), x, z);
        }
        return true;
    }

    public static int height(LevelAccessor world, Heightmap.Types type, int x, int z) {
        if (!ready(world, x, z)) {
            return -100000;
        }
        return world.getHeight(type, x, z);
    }

    public static BlockState state(LevelAccessor world, BlockPos pos) {
        if (!ready(world, pos.getX(), pos.getZ())) {
            return Blocks.AIR.defaultBlockState();
        }
        return world.getBlockState(pos);
    }

    public static boolean empty(LevelAccessor world, BlockPos pos) {
        if (!ready(world, pos.getX(), pos.getZ())) {
            return true;
        }
        return world.isEmptyBlock(pos);
    }
}
```

## クレジット・ライセンス

この Modpack で使っている Mod は、ほとんどを導入時に Prism Launcher が公式の配布元（CurseForge）から自動でダウンロードします。ZIP の中に Mod そのものは入っていません。

ただし次の 3 つの Mod は、作者が Modpack への同梱を認めているため改変せずに ZIP に同梱しています。それぞれのライセンスに従いここに記載します。

- **Katters Structures**（作者：Explorer's Eden）
  - https://modrinth.com/mod/katters-structures
- **DeCubed Dungeons**（旧名：Dungeons+）（作者：technodono）
  - ライセンス：[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja)
  - https://modrinth.com/mod/decubed-dungeons
- **Heart Crystals**（作者：n643064）
  - ライセンス：[GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html)
  - ソースコード：https://github.com/n643064/HeartCrystals
  - https://modrinth.com/mod/heart-crystals

また一部の Mod は、ZIP に入っているパッチツールが遊ぶ人のパソコン上で数値などを書き換えます。ZIP に入っているのは書き換える部分のデータだけで、Mod そのものは含んでいません。

## 注意事項・利用規約

- この Modpack の内、作者が作った部分（KubeJS のスクリプトや設定ファイルなど）は、再配布も改変したものの配布も大歓迎です。
- 同梱している他の作者の Mod にはそれぞれのライセンスが適用されます。ZIP をそのまま再配布する場合や、改変したものを配布する場合は、各 Mod のライセンスにも従ってください。
- この Modpack は無料で配布しています。販売や有料での配布はしないでください。同梱している Mod の中に、営利目的での利用を認めていないものがあるためです。
- この Modpack で遊んだ動画の投稿・配信は自由です。概要欄にこのページか元の動画へのリンクを載せていただけると嬉しいです。
- 同梱されている各 Mod の権利はそれぞれの作者に帰属します。
- この Modpack は Minecraft の公式製品ではありません。Mojang および Microsoft とは関係ありません。
- この Modpack の使用によって生じた不具合やデータの損失について作者は責任を負いません。ワールドのバックアップをこまめに取ってください。
