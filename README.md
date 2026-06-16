# Ames House Prices — SPSS 课程论文

基于 Kaggle [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) 竞赛数据，以 SPSS 27 为工具完成的《多元统计分析与 SPSS 应用》课程论文。核心目标是尽可能全面地练习和掌握 SPSS 各项分析命令，系统覆盖从数据预处理到多元统计建模的完整流程。

## 分析方法

### 数据预处理
- 变量重命名、缺失值处理（众数填充 / 频率分布填充 / 多重插补）、分类变量转换

### 描述统计
- 频数分析
- 交叉列联表分析 + 卡方检验
- 探索性分析（分布分析、箱线图、茎叶图）
- 多重响应集分析
- 复杂抽样

### 参数检验
- 单样本 T 检验
- 独立样本 T 检验
- 配对样本 T 检验

### 方差分析
- 单因素方差分析（齐性与非齐性，Welch / Games-Howell）
- 多因素方差分析
- 协方差分析

### 相关分析
- 双变量相关分析
- 偏相关分析
- 距离相关分析

### 回归分析
- 线性回归
- 逐步回归
- 非线性回归
- 二元逻辑回归
- 泊松回归
- Cox 生存分析

### 非参数检验
- Mann-Whitney U 检验
- Wilcoxon 符号秩检验

### 聚类与分类
- K-means 聚类
- 层次聚类
- 判别分析

### 降维
- 因子分析

## 数据

Kaggle Ames Housing 数据集，79 个特征变量，目标变量为 `SalePrice`。完整变量说明见 `data_description.txt`。

## 目录结构

```
ames-house-prices-spss/
├── README.md
├── data_description.txt              # 变量字典
├── train.csv / test.csv              # 原始数据
├── data_backup/                      # 数据备份
├── main.sav                          # SPSS 主工作文件
├── predict.sav                       # 预测结果
├── *.xml                             # SPSS 分析输出
├── *.sav / *.csplan                  # SPSS 抽样文件
└── 基于SPSS的房价影响因素分析及预测方法应用.pdf  # 完整报告（128 页）
```

## 复现

SPSS 27 打开 `main.sav`，各分析输出可在 SPSS Viewer 中直接查看，完整过程见报告 PDF。
