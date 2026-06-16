# Ames House Prices — SPSS 课程论文

基于 Kaggle [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) 竞赛数据，使用 SPSS 27 完成的课程论文。核心目标是全面练习 SPSS 各项分析命令，覆盖描述统计、推断统计与建模方法。

## 分析方法

| 类别 | 方法 | SPSS 模块 |
|------|------|-----------|
| 抽样 | 简单随机抽样 | Complex Samples |
| 回归 | 逐步线性回归（房价预测） | Regression → Linear |
| 分类 | 二元逻辑回归（是否有中央空调） | Regression → Binary Logistic |
| 分类 | 判别分析（房价等级预测） | Classify → Discriminant |
| 描述 | 频率分析、交叉表、描述统计 | Descriptive Statistics |

## 数据

源自 Kaggle Ames Housing 数据集，79 个特征变量，目标变量为 `SalePrice`。完整变量说明见 `data_description.txt`。

## 目录结构

```
ames-house-prices-spss/
├── README.md
├── SPSS/
│   └── data/
│       ├── data_description.txt      # Kaggle 变量字典
│       ├── train.csv / test.csv      # 原始数据
│       ├── data_backup/              # 数据备份
│       ├── main.sav                  # SPSS 主工作文件
│       ├── predict.sav               # 预测结果
│       ├── *.xml                     # SPSS 分析输出
│       ├── *.sav / *.csplan          # SPSS 抽样文件
│       └── 基于SPSS的房价影响因素分析及预测方法应用.pdf  # 完整报告
```

## 复现

SPSS 27 打开 `main.sav`，各分析输出可在 SPSS Viewer 中直接查看，完整过程见报告 PDF。
