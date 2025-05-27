# ERA vs FIP Analysis

## 📌 概要
このプロジェクトでは、プロ野球投手の「ERA（防御率）」と「FIP（守備力や運を差し引いた防御率）」を比較・分析することで、運や守備に依存しない投手評価を試みた。セイバーメトリクスの考え方に基づき、ERAとFIPの乖離や、投手タイプの傾向分析を行っている。

## 📁 ファイル構成
- `ERA_FIP_analysis.ipynb`: メインの分析Notebook
- `bb_an.xlsx`: 投手成績の元データ
- `README.md`: このファイル

## 🚀 実行方法
Jupyter Notebook上で以下の手順で動作します。

1. 必要なパッケージをインストール（`pandas`, `matplotlib`, `seaborn`）
2. Notebookを開いてセルを順に実行

## 🔍 使用した主な指標
- ERA（Earned Run Average）
- FIP（Fielding Independent Pitching）
- 被本塁打 / 与四球 / 奪三振 など

## 📈 今後の展望
- 回帰分析や機械学習によるFIP予測
- 球場別や年度別の影響を加味した分析
