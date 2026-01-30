# 🏥 Predicting Fall Risk in Older Adults (ELSI-Brazil Dataset)

This project was developed as part of my transition from **Medicine** to **Digital Science**. It leverages machine learning to identify high-risk patients for falls using real-world data from the **ELSI-Brazil (English Longitudinal Study of Ageing)**, a nationally representative study of Brazilians aged 50 and older.

## 📝 Project Overview
Falls are a major public health challenge in geriatrics, leading to loss of independence and high healthcare costs. This project applies **Predictive Analytics** to clinical and socioeconomic variables to provide a data-driven tool for fall prevention and clinical decision support.

## 🚀 Key Clinical Insights (Odds Ratio)
The model identified that functional and clinical factors often outweigh chronological age as predictors:
* **Sleep Quality (OR: 1.72):** Poor or non-restorative sleep increased the risk of falling by 72%.
* **Arthritis (OR: 1.61):** A clinical diagnosis of arthritis is a significant predictor of mechanical falls.
* **Visual Acuity (OR: 1.33):** Difficulties in vision, even with corrective lenses, remain a critical risk factor.

<img width="989" height="590" alt="Unknown-4" src="https://github.com/user-attachments/assets/4a52f167-d636-4db6-884d-c7c52a63cab2" />


## 🛠️ Data Science & Technical Stack
- **Language:** Python
- **Core Libraries:** `Pandas` for data wrangling, `Scikit-Learn` for modeling, and `Seaborn/Matplotlib` for medical data visualization.
- **Handling Imbalanced Data:** Employed `class_weight='balanced'` within a Logistic Regression framework to address the rarity of fall events, successfully increasing the model's **Recall** from 0.01 to **0.58**.
- **Clinical Feature Engineering:** Transformed raw health surveys into a structured matrix for predictive modeling.

## 📊 Repository Structure
1. **`Predicting_Fall_Risk_ELSI_Brazil.ipynb`**: The complete data pipeline, including cleaning, exploratory analysis, and model evaluation.
2. **Clinical Simulator**: A Python function within the notebook that calculates a patient's fall probability in real-time based on their clinical profile.

---
**Academic Goal:** This portfolio serves as a technical demonstration of my skills for Master's applications in *Digital Science*, *Health Data Analytics*, or *Medical Informatics* in Italy.

