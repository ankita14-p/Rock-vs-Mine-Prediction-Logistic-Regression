# Rock vs Mine Prediction using Logistic Regression

This project is a binary classification model built using **Logistic Regression** to predict whether a sonar signal has bounced off a **rock** or a **mine**. The project is implemented in **Python** using **Google Colab**, and includes label encoding and model evaluation steps.

---

## 📌 Dataset

- **Name**: Sonar Dataset
- **Instances**: 208 samples
- **Features**: 60 numeric features representing sonar energy
- **Target Labels**:
  - `R` = Rock
  - `M` = Mine

---

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- scikit-learn (Logistic Regression, LabelEncoder, train_test_split, accuracy_score)

---

## 🔁 Project Workflow

1. **Data Loading** using pandas  
2. **Exploratory Data Analysis (EDA)**  
3. **Label Encoding** of categorical target labels  
4. **Train-Test Split** using `train_test_split`  
5. **Model Building** using Logistic Regression  
6. **Model Evaluation** with accuracy on training and testing sets

---

## 📊 Model Performance

| Dataset        | Accuracy |
|----------------|----------|
| Training Set   | 84%      |
| Testing Set    | 82%      |

---

## 📂 How to Use This Project

1. Clone or download this repository.
2. Open the `.ipynb` notebook file in **Google Colab** or **Jupyter Notebook**.
3. Ensure the **`sonar.all-data.csv`** file is available in your environment.
4. Run all cells sequentially to load the data, train the model, and view results.

> Note: The dataset is not included in this repository. Please download it manually.

---

## 📚 Learning Source

This project was inspired by a YouTube tutorial. While the core concept was learned from the tutorial, I made my own modifications during implementation — such as applying label encoding to preprocess the target variable.


---

## 🚀 Future Enhancements

- Add confusion matrix, precision, recall, and F1-score
- Use cross-validation for more robust results
- Try other classification algorithms like SVM, Random Forest, or XGBoost

---

⭐️ If you found this helpful, consider giving this repo a star!


