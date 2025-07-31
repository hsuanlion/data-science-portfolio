
# 🏦 信用卡詐欺交易分類分析 (Decision Tree vs SVM) | Credit Card Fraud Classification

本專案透過 **Decision Tree** 與 **SVM** 模型，分析信用卡詐欺資料集 (Credit Card Fraud Dataset)，並針對不平衡樣本問題進行模型比較與可視化分析。  
This project compares **Decision Tree** and **SVM** on the credit card fraud dataset, focusing on imbalanced data handling and model evaluation.

---

## 📌 專案目標 | Project Goals
- 探索資料分布，觀察詐欺樣本比例與特徵關係 | Analyze class imbalance and feature distribution  
- 建立兩種分類模型：**Decision Tree** 與 **SVM** | Build Decision Tree & SVM classifiers  
- 以 **Recall、F1-score、AUC** 為主要指標，評估模型效能 | Evaluate models using Recall, F1-score, AUC  
- 提出未來優化方向（不平衡資料處理、集成學習）| Suggest improvements (SMOTE, Ensemble methods)

---

## 📊 專案結果摘要 | Key Findings

### 1. 不平衡樣本比例 | Class Imbalance
詐欺交易僅佔極小比例，Accuracy 指標不可靠。  
Fraud transactions are extremely rare; Accuracy alone is misleading.

![Fraud vs Non-Fraud](reports/fraud_ratio.png)

---

### 2. 模型 ROC 曲線比較 | ROC Curve Comparison
SVM 在 Recall 與 AUC 表現明顯優於 Decision Tree。  
SVM outperforms Decision Tree in Recall and AUC.

![ROC Curve](reports/roc_curve.png)

---

## 🔍 未來優化方向 | Future Improvements

- 使用 **SMOTE / 權重調整** 處理不平衡樣本 | Handle class imbalance with SMOTE / class weights  
- 嘗試 **集成學習模型 (XGBoost, LightGBM)** 提升效能 | Try ensemble models to improve performance  
- 深入特徵重要度分析 | Perform feature importance analysis

---

**作者 | Author**：Pei Hsuan Lee  
📬 歡迎交流機器學習與資料分析經驗！ | Feel free to connect!
