# ex2: Fusion of Supervised + Unsupervised Learning

## 1. 模型設計概述
- Isolation Forest：檢測潛在異常點並標記為新特徵
- XGBoost：監督式分類器，學習原始特徵與異常標記

## 2. 模型理由
- 利用無監督模型先捕捉異常模式，再補強有監督模型的決策邊界
- 有助於發現一些未被標註但實際異常的樣本