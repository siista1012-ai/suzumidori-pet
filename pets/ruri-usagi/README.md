# ルリウサギ

`ルリウサギ` は、添付画像のような淡い青いウサギをもとにしたCodex petです。

## コンセプト

- 淡い青のふわふわしたウサギ
- 長い耳、ピンクの耳内側、白いお腹と白い足
- 青いリボンと小さな金色チャーム
- 金色の丸い目、ピンクのほっぺ、白いしっぽ
- 鳥ペットとは別の、丸く座ったウサギらしいシルエット

## ファイル

- `pet.json`: Codex petの設定
- `spritesheet.webp`: Codex pet用スプライトシート
- `figma/ruriusagi-atlas.png`: Figma向けの透過PNG版
- `figma/cells/*.png`: Figmaで扱いやすいセル単位の透過PNG
- `figma/motions/*.png`: Figmaで確認しやすい9枚モーション横並びPNG
- `motions/right-hop/*.png`: 右へジャンプしながら移動する9枚フル版
- `motions/left-hop/*.png`: 左へジャンプしながら移動する9枚フル版
- `motions/carrot-waiting/*.png`: 待機中ににんじんを食べる9枚フル版
- `qa/contact-sheet.png`: 全ポーズの確認用一覧
- `qa/transparency-check.png`: 黒・白・市松背景での透過確認
- `qa/motion-contact-sheet.png`: 9枚モーションの一覧
- `qa/motion-transparency-check.png`: モーション単位の透過確認
- `qa/previews/*.gif`: 各状態のアニメーション確認用GIF

## モーション反映

- 右ジャンプ: `running-right` に8枚版として反映
- 左ジャンプ: `running-left` に8枚版として反映
- にんじん待機: `idle` と `waiting` に6枚版として反映
- 9枚すべての元画像は `motions/` に残しています

## 検証

- スプライトシートサイズ: `1536x1872`
- セルサイズ: `192x208`
- 状態数: 9
- 透明ピクセルRGB残り: なし
- Figma向けPNG: あり
- モーションPNG: 27枚、透明ピクセルRGB残りなし
