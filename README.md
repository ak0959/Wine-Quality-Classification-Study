# Wine Quality Classification: A Comparative Study

## Project Overview
This project performs a multi-class classification to predict wine quality scores (3–9) for both Red and White wine datasets. The goal is to evaluate model performance across different wine chemistries and identify the challenges of predicting "fringe" quality classes.

## Key Insights & Results
* **Model Performance:** Random Forest significantly outperformed Logistic Regression, specifically reaching ~70% baseline accuracy on the White Wine dataset.
* **Data Characteristics:** White wine proved easier to predict than red wine, likely due to more distinct feature interactions in its chemical profile.
* **The "Fringe" Challenge:** Quality scores at the extremes (Classes 3, 4, 8, and 9) were the most difficult to classify. Due to severe class imbalance, models tended to predict the majority "middle ground" classes (5 and 6).
* **Recommendation:** To improve F1-scores, future iterations should convert the target into a 3-class system (Low/Medium/High) to resolve structural imbalances.

## Technologies Used
* **Language:** Python
* **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Models:** Logistic Regression, Random Forest Classifier

## Project Files
* `Assignment.ipynb`: Full data cleaning, EDA, and modeling pipeline.
* `winequality-red.csv` & `winequality-white.csv`: Raw datasets used for the study.
* `ML_Assignment_...pdf`: Original project requirements and rubric.

---
