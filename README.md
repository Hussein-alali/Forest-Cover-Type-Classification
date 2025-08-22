# 🌲 Forest Cover Type Classification

## 📌 Project Overview
This project predicts the type of forest cover based on cartographic variables such as elevation, slope, soil type, and wilderness area.  
It is a **multi-class classification** problem with several forest cover categories.  

We trained and evaluated two ensemble models: **Random Forest** and **XGBoost**.  

---

## 🚀 Key Highlights
- **Goal:** Classify forest cover type based on environmental features.  
- **Dataset:** Forest Cover Type Dataset (UCI / Kaggle).  
- **Models Used:**  
  - Random Forest Classifier.  
  - XGBoost Classifier.  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score.  
- **Cross-Validation:** Applied for robust evaluation.  

---

## 📊 Performance Results
| **Metric**   | **Random Forest** | **XGBoost** |
|--------------|-------------------|-------------|
| Accuracy     | 0.9551            | 0.9611      |
| Precision    | 0.9461            | 0.9348      |
| Recall       | 0.9085            | 0.9490      |
| F1 Score     | 0.9260            | 0.9417      |

✅ **XGBoost** achieved the best overall performance with higher accuracy and recall.  
✅ **Random Forest** maintained strong precision and balanced results.  

---

## 🛠 Tools & Libraries
- **Python**  
- **NumPy, Pandas**  
- **Scikit-learn** (RandomForestClassifier, metrics, cross_val_score)  
- **XGBoost** (XGBClassifier)  
- **Matplotlib, Seaborn** (EDA and visualization)  

---

## 📈 Workflow
1. **Data Preprocessing:**  
   - Checked for missing values.  
   - Standardized and encoded features where required.  
2. **EDA (Exploratory Data Analysis):**  
   - Visualized class distribution.  
   - Explored feature correlations and importance.  
3. **Model Training:**  
   - Trained **Random Forest** and **XGBoost**.  
4. **Model Evaluation:**  
   - Compared metrics: Accuracy, Precision, Recall, and F1 Score.  

---

## 🧩 How to Run
1. Clone the repository:

    git clone https://github.com/Hussein-alali/Forest-Cover-Type-Classification

2. Install dependencies:

    pip install -r requirements.txt

3. Run The Notebook:

    jupyter notebook Forest_Cover_Type_Classification.ipynb

---

## 📘 License
This project is licensed for educational and personal use.

---

## 🙋 Author
**Hussein Abdalrhman Alali Alhlal**  
Computer Engineer | Data & AI Enthusiast

---
