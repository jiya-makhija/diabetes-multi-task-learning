# Multi-Task Healthcare Predictive Framework

### [Click here to see workbook](https://jiya-makhija.github.io/diabetes-multi-task-learning/)

## Project Overview
This project implements a **Multi-Task Learning (MTL)** neural network to optimize patient care outcomes for diabetic individuals. By leveraging a **Hard-Parameter Sharing** architecture, the model captures underlying physiological patterns from a 100k+ patient dataset to solve three distinct clinical challenges simultaneously.

## Key Features
* **Predictive Tasks:**
    * **Readmission Risk:** Binary classification of <30-day hospital return.
    * **Length of Stay (LOS):** Regression analysis to predict hospitalization duration.
    * **Medication Recommendation:** Multi-label classification providing confidence scores for treatments (e.g., Insulin, Glipizide, Metformin).
* **Architectural Optimization:** Engineered a shared-parameter backbone with task-specific heads, using **joint loss weighting** to balance Mean Squared Error (MSE) and Cross-Entropy objectives.
* **Clinical Decision Support:** Integrated case studies providing probability-based risk profiles to aid physician decision-making.

## Tech Stack
* **Deep Learning:** Python, TensorFlow/Keras (or PyTorch)
* **Data Engineering:** Scikit-learn, Pandas, NumPy
* **Visualization:** Plotly, Seaborn, Matplotlib

## Repository Structure
* `index.html`: The complete technical report, including data preprocessing, model training logs, and visualizations.

## Case Study Highlight (Patient 8331)
* **Risk Level:** Predicted HIGH (48.9% probability)
* **Stay Length:** Predicted 6.0 days (Actual: 5.0)
* **Top Recommendation:** Glipizide (Confidence: 5.86)
