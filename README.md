# 🪨 Rock vs Mine Classification

This machine learning project classifies sonar signals to determine whether the object is a **rock** or a **mine**. The dataset is sourced from the UCI Machine Learning Repository and processed using a Logistic Regression model.

---

## 📂 Repository Contents

- `RockvsMine.ipynb` – Main notebook with data loading, preprocessing, training, and evaluation.
- `sonar data.csv` – The dataset used for training and testing the model.
- `README.md` – Project documentation.

---

## 📊 Dataset Overview

- **File:** `sonar data.csv`
- **Instances:** 208
- **Features:** 60 numeric features representing sonar signal energy levels
- **Target:** `R` (Rock) or `M` (Mine)

---

## 🚀 Features of the Notebook

- Data loading and inspection
- Data preprocessing using pandas and NumPy
- Model training using Logistic Regression from Scikit-learn
- Performance evaluation on both training and testing sets
- Manual prediction input supported for new data

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `sklearn`

---

## ▶️ How to Run the Project

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/rock-vs-mine-classifier.git
    cd rock-vs-mine-classifier
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:

    ```bash
    jupyter notebook RockvsMine.ipynb
    ```

---

## 📈 Model Performance

- **Training Accuracy:** ~98%
- **Testing Accuracy:** ~90%
- Classification with minimal preprocessing using Logistic Regression

---

## 🧠 Future Enhancements

- Experiment with other models: SVM, Random Forest, Gradient Boosting
- Add data visualization and correlation heatmaps
- Build a simple web app for live predictions

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for more information.
