# AutoAI-Model-using-IBM-Watson
(https://colab.research.google.com/drive/1csbbEmddd5TA3cVyiMxKim64QSsnN_xr#)
# 🤖 AutoAI Salary Prediction using IBM Watson Studio

A data science project that uses **IBM Watson Studio's AutoAI** to automatically build, evaluate, and export machine learning models for **predicting salaries** based on features like experience, education, and job role.

---

## 📌 Objective

The objective of this project is to develop a predictive model that estimates an individual's salary using various features from a structured dataset. IBM Watson’s **AutoAI** tool is leveraged to automate:

- Data cleaning and preprocessing
- Feature engineering
- Model selection
- Hyperparameter optimization
- Pipeline generation

---

## 🗃️ Files in this Repository

| File / Folder                  | Description                                              |
|-------------------------------|----------------------------------------------------------|
| `AutoAI.ipynb`                | Exported notebook from IBM Watson AutoAI (Google Colab ready) |
| `salary_train.csv`            | Training dataset with features and salary labels         |
| `salary_test.csv`             | Testing dataset used for predictions                     |
| `salary_pred_online_test_result.json` | JSON file with prediction output from model         |
| `README.md`                   | This documentation file                                  |
| `Feature summary.png`         | AutoAI-generated summary of important features           |
| `Model Evaluation.png`        | Performance metrics and evaluation chart                 |
| `Model Information.png`       | Info about the best model and pipeline                   |
| `Prediction Result.png`       | Screenshot of salary predictions                         |
| `Relation Map.png`            | Graph showing relationships between input features       |
| `Maric Chart.png`             | Likely a visual comparison of predicted vs actual values |

---

## 📊 Dataset Description

- **Training File**: `salary_train.csv`
- **Test File**: `salary_test.csv`
- **Target Column**: `salary`

### Feature Columns May Include:
- `experience`
- `education_level`
- `job_title`
- `industry`
- `location`
- ... *(exact columns based on dataset content)*

---

## ⚙️ AutoAI Workflow (IBM Watson Studio)

1. Upload the training dataset to **Watson Studio**.
2. Launch an **AutoAI experiment** and configure:
   - Target column: `salary`
   - Metric: R² Score or RMSE
3. AutoAI performs:
   - Feature transformations
   - Model selection (e.g. XGBoost, LGBM, etc.)
   - Hyperparameter tuning
   - Pipeline ranking
4. Export the best pipeline as a **notebook** (`AutoAI.ipynb`).
5. Run predictions on `salary_test.csv`.

---

## 📈 Model Performance

| Metric     | Value (Example) |
|------------|-----------------|
| R² Score   | `0.88`          |
| RMSE       | `~4500`         |
| Best Model | `XGBoost`       |

> Detailed charts are available in:
> - `Model Evaluation.png`
> - `Model Information.png`
> - `Prediction Result.png`

---

## 🧠 Visuals

| Feature Summary | Model Evaluation | Prediction Output |
|-----------------|------------------|-------------------|
| ![Feature Summary](Feature%20summary.png) | ![Model Evaluation](Model%20Evaluation.png) | ![Prediction Result](Prediction%20Result.png) |

---

## 🛠️ Technologies Used

- IBM Watson Studio – AutoAI
- IBM Cloud Object Storage
- Python
- Pandas, NumPy
- Jupyter / Google Colab
- Scikit-learn (in exported pipeline)

---

## 📝 How to Run This Project

1. Clone or download this repo.
2. Open `AutoAI.ipynb` in Google Colab or Jupyter Notebook.
3. Upload `salary_test.csv` when prompted.
4. Run all cells to see prediction results.
5. Check the `.json` file for structured output.

---

## 🙋‍♀️ Author

**Bhoomi Jaiswal**  
🎓 B.Tech CSE | Data Science Enthusiast  
🔗 [GitHub Profile](https://github.com/BhoomiJaiswal0)
