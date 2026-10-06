<!-- ELUCENIA technical documentation · gleason-isup · ja · no clinical/professional/rights approval -->

# Gleasonスコア・ISUPグレードグループ

[条件・出典・許諾](https://elucenia.org/ja/tools/gleason-isup)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 主パターン（最大範囲）

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### 副パターン

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## 方法の版

ISUP合意2014/発表2016：5群，3+4/4+3の区別

## 記載された計算式

Gleason ≤ 6 = 群 1 · 3 + 4 = 7 = 群 2 · 4 + 3 = 7 = 群 3 · 8 (4 + 4, 3 + 5, 5 + 3) = 群 4 · 9–10 = 群 5.

## 限界・対象集団

ISUPのグループへの換算は、前立腺がんの組織学的評価でGleasonパターンが適切に付与されていることを前提とし、3+4は4+3と同等ではありません。2014年の合意は、浸潤がんを伴わない導管内がんをGleasonで評価することを推奨していません。計算器はパターンを決めるものではなく、病理評価に代わるものでもありません。

## 参考文献

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

Gleason 3 + 3 = 6: グレードグループ 1

| 結果の詳細 | |
| --- | --- |
| 前立腺摘除術後の5年生化学的再発無再発生存 | 96% |


### 2

Gleason 3 + 4 = 7: グレードグループ 2

| 結果の詳細 | |
| --- | --- |
| 前立腺摘除術後の5年生化学的再発無再発生存 | 88% |


### 3

Gleason 4 + 3 = 7: グレードグループ 3

| 結果の詳細 | |
| --- | --- |
| 前立腺摘除術後の5年生化学的再発無再発生存 | 63% |


### 4

Gleason 3 + 5 = 8: グレードグループ 4

| 結果の詳細 | |
| --- | --- |
| 前立腺摘除術後の5年生化学的再発無再発生存 | 48% |


### 5

Gleason 5 + 4 = 9: グレードグループ 5

| 結果の詳細 | |
| --- | --- |
| 前立腺摘除術後の5年生化学的再発無再発生存 | 26% |

