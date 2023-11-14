# 決策樹分類器開發

## 專案概述

這個project旨在透過實作決策樹分類器，進行資料探勘實作。使用 Python 及相關套件，我選擇了兩個不同的資料集，其中包括自選資料集和UCI Datasets提供的Adult資料集。透過模型訓練，將評估分類器在訓練資料和測試資料上的正確率，並進行進一步的分析。

## Task

### 使用UCI Datasets的Bank Marketing資料集

- 下載並使用UCI Datasets提供的Bank Marketing資料集，同樣進行訓練及測試資料的劃分。
- 開發決策樹分類器，使用 Python 及相應套件實現。
- 評估訓練資料及測試資料上的分類正確率。

### 使用UCI Datasets的Adult資料集

- 下載並使用UCI Datasets提供的Adult資料集，同樣進行訓練及測試資料的劃分。
- 開發決策樹分類器，使用相同的Python套件進行實作。
- 評估訓練資料及測試資料上的分類正確率。

### 結果輸出與分析

- 將測試資料的分類結果輸出到一個Excel檔案中，包含正確的類別以及分類器預測的類別。
- 進行分析，檢視模型預測的效果和可能的改進方向。

### 決策樹參數優化

- 參考 "[Post pruning decision trees with cost complexity pruning](https://scikit-learn.org/stable/auto_examples/tree/plot_cost_complexity_pruning.html#sphx-glr-auto-examples-tree-plot-cost-complexity-pruning-py)" 章節，選擇三種適當的節點數及樹深度的參數。
- 劃出訓練完的決策樹，比較這三種參數設定之下，決策樹的分類預測正確率。

## 專案成果

- 以視覺化方式呈現決策樹模型。
- Excel檔案記錄測試資料的實際類別和分類器的預測類別。
- 分析模型在不同資料集上的表現，並提出可能的改進策略。
- 專案報告，包括專案背景、方法、結果和未來工作建議。
