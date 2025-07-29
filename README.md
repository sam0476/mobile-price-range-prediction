# 📱 Mobile Price Range Prediction - Machine Learning Project

Bob is starting his own mobile company and wants to price phones smartly to compete with giants like Apple and Samsung. This project helps Bob classify phones into appropriate price ranges based on their features using machine learning.

## 🚀 Project Goal

To predict the **price range** of mobile phones using technical specifications such as:
- RAM
- Internal Memory
- Battery Power
- Camera specs
- 4G/3G support
- And more

## 📂 Dataset

The dataset used contains several thousand mobile phones with attributes and corresponding price range labels:
- 0 = Low Cost
- 1 = Medium Cost
- 2 = High Cost
- 3 = Very High Cost

## 🧪 ML Pipeline Overview

- Exploratory Data Analysis (EDA)
- Handling imbalanced data using **SMOTE**
- Feature scaling with **StandardScaler**
- One-hot encoding for categorical features
- Model training using:
  - 🎯 Random Forest
  - 🚀 XGBoost Classifier
  - 📈 Gradient Boosting Classifier
- Performance comparison using classification metrics

## 🏆 Best Model: XGBoostClassifier

| Model                | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Random Forest        | 89%      | 0.89      | 0.89   | 0.89     |
| Gradient Boosting    | 91%      | 0.91      | 0.92   | 0.91     |
| **XGBoostClassifier**| **91%**  | **0.91**  | **0.92**| **0.91** |

✅ XGBoost delivered the best balance of accuracy and class-wise performance.

## 📊 Results

- High classification accuracy
- Great F1-scores across all price segments
- Robust to class imbalance
- Easy integration into deployment pipelines

## 📌 Conclusion

With the help of XGBoost, mobile price range prediction can be **accurate and scalable**. This allows new companies like Bob’s to make **data-driven pricing decisions** and remain competitive in the market.

---

## 👨‍💻 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
