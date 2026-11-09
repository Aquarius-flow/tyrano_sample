# 星あかりの配達便

架空の港町「凪の町」で、配達見習いが灯台へ星灯りを届ける短編分岐ノベルです。クリックで文章を進め、選択肢で進路を決めます。結末は3種類です。

- 公開先: https://aquarius-flow.github.io/tyrano_sample/
- シナリオ: `docs/data/scenario/first.ks`
- 元の練習用シナリオ: `docs/data/scenario/melos-original.ks`（ローカルで編集していたタイトルも保持）
- 背景: `docs/data/bgimage/starlight.svg`（新規制作）

## 分岐

| 経路 | 結末 |
| --- | --- |
| 安全な坂道 → 職人を手伝う | END 1「遠くまで届く光」 |
| 安全な坂道 → 自分の星灯りを先に届ける | END 2「約束の灯り」 |
| 海沿い → 待避所で待つ | END 3「夜明けの再出発」 |
| 海沿い → 引き返す | 坂道に合流し、職人への対応でEND 1または2 |

## 利用条件

新規シナリオ `first.ks` と新規背景 `starlight.svg` はCC0 1.0で提供します。
https://creativecommons.org/publicdomain/zero/1.0/

本作の登場人物、町、出来事はすべて架空です。実在人物や有名人を題材にしていません。

ティラノスクリプト本体と既存同梱素材の利用条件は変更しません。既存の練習用シナリオは元のREADMEでCC0とされています。既存写真は新作では使用せず、練習用ゲームのために保存しています。元のREADMEのクレジットは次のとおりです。

- `run.jpg`: Maksim Romashkin / Pexels
- `sleep.jpg`: Andrea Piacquadio / Pexels
- ティラノスクリプト: https://tyrano.jp/

## 環境

授業配布のエンジンはそのまま保持しました。`kag.js` の `version` は500、`TYRANO_ENGINE_VERSION` は400、`Config.tjs` は5.00という表記を含みます。新作は課題資料で参照されている[公式v4タグリファレンス](https://tyrano.jp/tag/v4)の基本タグを使用します。v4専用ランタイムへの置換はしていません。

ローカルではVS Codeでこのフォルダを開き、Live Serverで `docs/index.html` を表示できます。
