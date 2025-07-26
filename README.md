# Beyond EDA: Intelligent Data Cleaning & Preprocessing with LLM-Powered Imputation

This project focuses on **data cleaning**, **exploratory data analysis (EDA)**, and **preprocessing** steps for a customer churn dataset, preparing it for downstream machine learning tasks. The dataset contains customer demographic and account information with the goal of understanding churn patterns.

## 📁 Project Structure

EDA/data/<br>
├── processed/<br>
├── raw/<br>
<br>
📄 .env <br>
📄 .gitignore <br>
📒 0_handle_missing_values.ipynb <br>
📒 1_handling_outliers.ipynb <br>
📒 2_feature_binning.ipynb <br>
📒 3_feature_encoding.ipynb <br>
📒 4_feature_scaling.ipynb <br>
📄 README.md <br>
📄 requirements.txt <br>

## 🧾 Steps Covered

- ✅ Standard setup and dataset loading  
- ✅ Handling **missing values**
- ✅ Visualizing numerical data with **boxplots**
- ✅ Exploring categorical data with **pie charts**
- ✅ Outlier detection using:
  - **Empirical Rule (Three Sigma Rule)**
  - **IQR Method**
- ✅ Logging and flagging of outliers (not removed until business confirmation)
- ✅ Saving the cleaned dataset after handling missing values
- ✅ **Feature Binning** (e.g., converting Credit Score to categories like Poor, Good, Excellent)
- ✅ **Feature Encoding** for nominal variables using One-Hot Encoding
- ✅ **Feature Scaling** with standardization techniques to normalize numerical features

## 🧠 Beyond EDA with LLMs

Large Language Models (LLMs) like ChatGPT were used to:
- Accelerate explanation of data exploration steps  
- Generate clean, readable summaries of code and logic  
- Provide instant support during debugging and documentation  
- Suggest next steps for feature engineering and modeling

This approach blends traditional EDA with modern AI-assisted workflows to increase both **speed** and **clarity**.

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- ChatGPT / LLMs for code assistance and documentation

## 📌 Notes

- Outliers were **only identified**, not removed, as further validation is needed from business stakeholders.
- Cleaned datasets are saved in the `data/processed/` folder for easy access and reuse.

## 📂 Next Steps

- Feature Selection  
- Model Building (Classification)

---

Feel free to clone or fork this project and adapt it for your own EDA workflows.
