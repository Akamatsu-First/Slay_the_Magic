# Slay the Magic

Minecraft Java Edition 1.20.1（Forge 47.4.10）向けの Modpack です。Prism Launcher で遊ぶことを前提にしています。

- 配布ページ：https://akamatsu-first.github.io/Slay_the_Magic/
- Slay the Magic の ZIP ファイルのダウンロード：[Releases](https://github.com/Akamatsu-First/Slay_the_Magic/releases)
- Prism Launcher のダウンロードページ：https://prismlauncher.org/

## ゲーム開始までの流れ

**以下の 1〜7 の手順を必ず行ってください。手順を飛ばすと、ゲームの起動時やネザー突入時にクラッシュします。**

1. 上記の URL から、Slay the Magic の ZIP ファイルと Prism Launcher をダウンロードする。ZIP ファイルは解凍しなくてよい。
2. Prism Launcher を開いたら右クリック →「起動構成の作成」を選択。
3. 画面左側の「インポート」を選択 → 右側に現れる「参照」をクリック → Slay the Magic の ZIP ファイルを開く。Mod を手動でダウンロードするよう求める画面が出た場合は、その表示に従う。
4. Prism Launcher のホーム画面に Slay the Magic の起動構成が現れるので、それを右クリック →「フォルダ」を選択。
5. 「minecraft」→「stm_patcher」をダブルクリック。
6. **「apply_patches.bat」をダブルクリック。黒い画面に「All done」と出たら成功です。** 何かキーを押すと画面が閉じる。
7. Prism Launcher のホーム画面に戻り、ゲームを起動する。初めて起動するときは、Minecraft を購入した Microsoft アカウントでのログインを求められる。

**macOS や Linux でも遊べますが、「apply_patches.bat」は Windows 専用です。**　事前に PowerShell 7 をインストールし、手順 6 の代わりに「apply_patches.ps1」を PowerShell 7 で実行してください。

詳しい導入の手順、注意事項・利用規約、クレジット・ライセンスは、配布ページをご覧ください。

## ゲーム開始後の注意点

**このゲームは非常に難易度が高く設定されています。**

戦闘や探索で手に入れた物を定期的に失うことになります。そのストレスに耐えられる方、またはそれを楽しめる方に向けて作っています。あらかじめご了承ください。

また、ほぼすべてのバイオームの気温と水温を、設定（config）でかなり極端にしています。そのため、最初のリスポーン地点が高熱地帯、氷雪地帯、または小さな島だった場合、死んでは戻るを繰り返すだけの、先に進めないワールドになる可能性が高いです。平原から始まるシード値が出るまでワールドを作り直すか、平原から始まる以下のシード値をご活用ください。

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
**動画内で紹介された仕様内の一部に関しては、その仕様に関わるMOD作者様の権利を侵害する恐れがある、もしくは実際のプレイ中に不便に感じたため、変更を加えております。**

- ウォーデンとストーカーの体力と攻撃力は反比例せず、それぞれ別のステータスとして扱われます 。
- 最終ボスはエンダードラゴンを討伐後のブラッドムーン発生時に、巨大な切り株に行くと登場します。降雪時である必要はありません。
- 動画本編で登場していた構造物・クラフトレシピの一部がこのModpack内では削除されています。
- タイダルクローの挙動が動画本編と異なります。
- 一部のボスのステータスは動画本編と異なります。

## 再配布・改変について

**この Modpack のうち、作者が作った部分（KubeJS のスクリプトや設定ファイルなど）は、再配布も、改変したものの配布も大歓迎です。**

同梱している他の作者のModには、それぞれのライセンスが適用されます。このModpackに別のModを加えて新しいModpackとして配布する場合は、加えたModのライセンスにも従ってください。

## LGPLのModに加えた変更の公開

以下の3つのModはLGPLで公開されているため、ライセンスに従ってこのModpack内で加えた変更をすべてここに公開します。

これらの変更に関してZIPに入っているパッチツール（stm_patcher）が、プレイヤーのパソコンにある公式のファイルに対して行います。ここに書いた箇所以外は公式のファイルから変えていません。

下記のコードは、変更したクラスファイルをJavaのソースコードに戻して表示したものです（名前の一部は読みやすいように元の名前に置き換えています）。

### Cataclysm: Spellbooks

- 対象のファイル：`cataclysm_spellbooks-1.2.7-1.20.1-all.jar`
- ライセンス：LGPL 2.1（GNU Lesser General Public License v2.1）
- 公式のソースコード：https://github.com/AceTheEldritchKing/Cataclysm_Spellbooks
- 変更点：下の表のとおり

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

---

この Modpack は Minecraft の公式製品ではありません。Mojang および Microsoft とは関係ありません。
