# フレアスキル現状まとめ（SINGLE）

プレイヤー: **462**（しろにく）
**TOTAL FLARE SKILL: 85,626**　対象90曲すべてフレアIX以上（EX 33曲 / IX 57曲）

## スキル値とフレアランク

| スキル | 譜面Lv | フレア |
|---:|---|---|
| 977 | Lv.17 | IX |
| 960 | Lv.15 | EX |
| 954 | Lv.16 | IX |
| 924 | Lv.15 | IX |

## カテゴリ別

| カテゴリ | 合計 | 平均 | 最低（枠の底） | EX | IX | 内訳 |
|---|---:|---:|---:|---:|---:|---|
| CLASSIC | 28,350 | 945.0 | 924 | 5 | 25 | 15 IX ×5 / 16 IX ×15 / 15 IX ×10 |
| WHITE   | 28,397 | 946.6 | 924 | 4 | 26 | 17 IX ×1 / 15 EX ×4 / 16 IX ×16 / 15 IX ×9 |
| GOLD    | 28,879 | 962.6 | 954 | 24 | 6 | 17 IX ×5 / 15 EX ×24 / 16 IX ×1 |

（「15 EX」= Lv.15 フレアEX）

## 伸びしろ

- **CLASSIC / WHITE の底は Lv.15 フレアIX（924）で、計19曲**
  - 同じ曲をEXにすると +36（→960）
  - Lv.16 フレアIX（954）と入れ替えると +30、Lv.17 IX（977）なら +53
- **GOLD の底は Lv.16 IX の Steps for Victory (U1 Heavy Metal Edition)（954）だけ**。残りはLv.15 EX（960）とLv.17 IX（977）
  - Lv.17 フレアIX を1曲増やすごとに +17（960 → 977）
  - Lv.16 は IX では 954 なので、GOLD 枠の底（960）を超えられない。GOLD で Lv.16 を入れるなら EX が必要
- **Lv.16 未対象の譜面**（難易度表で TOP30 に入っていないもの）: CLASSIC 26 / WHITE 36 / GOLD 143
  - CLASSIC の易しめ: I'm so Happy (CSP) 16.25、隅田川夏恋歌 (CSP) 16.40、Sakura Sunrise (CSP) 16.45
  - WHITE の易しめ: 海神 (ESP) 16.25、AWAKE (CSP) 16.25、Grip & Break down !! (CSP) 16.30
  - CLASSIC / WHITE ではこれらを IX で取るだけで、1曲 +30（924 の枠を置き換え）

データ: [`data/flare_skill.json`](data/flare_skill.json)（各曲に `flare` を追加） /
[`data/flare_ranks.json`](data/flare_ranks.json)（ページの初期フレアランク） /
[`data/lv16.json`](data/lv16.json)（3icecream Lv16 難易度表）
