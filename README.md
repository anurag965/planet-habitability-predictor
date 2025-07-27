
# 🪐 Exoplanet Habitability Prediction

This project analyzes a comprehensive dataset of exoplanets to predict their habitability using machine learning. It combines **data preprocessing**, **feature engineering**, **class balancing**, **model training**, and **scientific metrics** like the **Earth Similarity Index (ESI)** and **habitability scores** for key comparisons across planets such as Earth, Mars, Venus, and Kepler-442b.

---

## 🔍 Project Overview

- **Dataset:** PHL Exoplanet Catalog (CSV)
- **Goal:** Classify exoplanets into habitability classes: Inhabitable, Conservatively Habitable, and Optimistically Habitable
- **Techniques Used:**
  - MICE (Iterative Imputer) for missing value imputation
  - SMOTEENN for handling class imbalance
  - Label Encoding for categorical conversion
  - Feature Selection using Random Forest, AdaBoost, and ExtraTrees
  - Model training using Decision Trees, K-Nearest Neighbors, and Gradient Boosting
  - Evaluation via confusion matrix, classification report, ROC & PR curves

---

## 🚀 Features

- 📊 Extensive data cleaning and preprocessing
- ⚖️ Class rebalancing using SMOTEENN
- 🔬 Feature selection with ensemble-based methods
- 🤖 GridSearchCV optimization for each model
- 📈 Visual analytics: correlation heatmaps, bar plots, PR & ROC curves
- 🧪 Habitability metrics (ESI, Flux Factor, Composite Scores)
- 🌐 Planet-wise prediction and comparison

---

## 🛠️ Tech Stack

- Python 3.10+
- Pandas, NumPy, Seaborn, Matplotlib, Plotly
- Scikit-learn
- imbalanced-learn (SMOTEENN)
- GridSearchCV for hyperparameter tuning

---

## 📈 Models Trained

| Model              | Accuracy | Highlights                         |
|-------------------|----------|------------------------------------|
| Decision Tree      | ✅       | Fast, interpretable                |
| K-Nearest Neighbors| ✅       | Instance-based, simple logic       |
| Gradient Boosting  | ✅✅     | Best accuracy & generalization     |

---

## 📊 Planet Comparison

Includes detailed side-by-side scoring for:
- 🌍 Earth
- 🌑 Mars
- 🌋 Venus
- 🪐 Kepler-442b

Using derived features such as:
- Earth Similarity Index (ESI)
- Flux Factor
- Composite Habitability Score

---

## 📌 Visual Outputs

- Heatmaps of missing data and correlations
- Confusion matrix & classification metrics
- Model comparison bar plots
- ROC & PR curves
- Planet-wise habitability bar chart
- 3D scatterplot using Plotly

---

---

## 🙋‍♂️ Author

**Anurag Pradhan**  
📧 [anuragpradhancb@gmail.com](mailto:anuragpradhancb@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/anurag-pradhan-0340bb288) • [GitHub](https://github.com/anurag965)

---

## 📄 License

This project is licensed under the MIT License.
