# 🏠 California House Price Prediction using Machine Learning

## 📌 Overview

This project builds a **Machine Learning model** to predict housing prices in California based on various features such as median income, house age, average rooms, and location data.

The goal is to analyze housing data and create an accurate predictive model that can estimate property prices.

---

## 🚀 Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and evaluation
* Visualization of results
* Prediction on new data

---

## 📊 Dataset

The dataset used is the **California Housing Dataset**, which includes:

* Median Income
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Latitude & Longitude

📥 Source: Scikit-learn / Kaggle

---

## 🛠️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn

---

## ⚙️ Installation

Clone the repository:

```bash
https://github.com/naman0867/HOUSE_PREDICTION_MODEL.git
cd HOUSE_PREDICTION_MODEL
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the main script:

```bash
python main.py
```

Or open the notebook:

```bash
jupyter notebook California_Housing.ipynb
```

---

## 🔍 Workflow

1. Load dataset
2. Handle missing values
3. Perform EDA
4. Split dataset (Train/Test)
5. Train model (Linear Regression / Random Forest)
6. Evaluate using metrics (RMSE, R²)
7. Predict housing prices

---

## 📈 Model Performance

| Model             | RMSE  | R² Score |
| ----------------- | ----- | -------- |
| Linear Regression | ~0.73 | ~0.60    |
| Random Forest     | ~0.50 | ~0.80    |

*(Values may vary depending on tuning)*

---

## 📌 Example Prediction

```python
input_data = [[8.3252, 41, 880, 129, 322, 126, 37.88, -122.23]]
predicted_price = model.predict(input_data)
print(predicted_price)
```

---

## 📁 Project Structure

```
📦 California-Housing-ML
 ┣ 📜 main.py
 ┣ 📜 model.pkl
 ┣ 📜 requirements.txt
 ┣ 📜 README.md
 ┗ 📓 California_Housing.ipynb
```

---

## 🧠 Future Improvements

* Hyperparameter tuning
* Deep learning models
* Deployment using Flask / FastAPI
* Web UI integration

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Your Name**

* GitHub: https://github.com/naman0867

---

⭐ If you found this project helpful, please give it a star!
