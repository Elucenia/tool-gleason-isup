<!-- ELUCENIA technical documentation · gleason-isup · zh · no clinical/professional/rights approval -->

# Gleason 评分与 ISUP 分级组

[条件、来源与许可](https://elucenia.org/zh/tools/gleason-isup)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 主要模式（范围最大）

`p`

- `3` — 3
- `4` — 4
- `5` — 5

### 次要模式

`s`

- `3` — 3
- `4` — 4
- `5` — 5

## 方法版本

ISUP共识2014/发表2016：5组，区分3+4/4+3

## 已记录的公式

Gleason ≤ 6 = 组 1 · 3 + 4 = 7 = 组 2 · 4 + 3 = 7 = 组 3 · 8 (4 + 4, 3 + 5, 5 + 3) = 组 4 · 9–10 = 组 5.

## 限制与适用人群

换算为ISUP分组的前提是已在前列腺癌组织学检查中正确判定Gleason模式；3+4不等同于4+3。2014年共识不建议对无浸润性癌的导管内癌进行Gleason分级。计算器不能判定模式，也不能代替病理评估。

## 参考文献

- [Epstein JI et al. The 2014 International Society of Urological Pathology (ISUP) consensus conference on Gleason grading of prostatic carcinoma. Am J Surg Pathol, 2016.](https://doi.org/10.1097/PAS.0000000000000530)

- [Epstein JI et al. A contemporary prostate cancer grading system: a validated alternative to the Gleason score. Eur Urol, 2016.](https://doi.org/10.1016/j.eururo.2015.06.046)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

Gleason 3 + 3 = 6：分级组 1

| 结果详情 | |
| --- | --- |
| 前列腺切除术后 5 年生化复发无病生存率 | 96% |


### 2

Gleason 3 + 4 = 7：分级组 2

| 结果详情 | |
| --- | --- |
| 前列腺切除术后 5 年生化复发无病生存率 | 88% |


### 3

Gleason 4 + 3 = 7：分级组 3

| 结果详情 | |
| --- | --- |
| 前列腺切除术后 5 年生化复发无病生存率 | 63% |


### 4

Gleason 3 + 5 = 8：分级组 4

| 结果详情 | |
| --- | --- |
| 前列腺切除术后 5 年生化复发无病生存率 | 48% |


### 5

Gleason 5 + 4 = 9：分级组 5

| 结果详情 | |
| --- | --- |
| 前列腺切除术后 5 年生化复发无病生存率 | 26% |

