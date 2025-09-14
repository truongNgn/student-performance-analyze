# Student Performance Analysis

This project explores and analyzes the **Student Performance Dataset** using machine learning models and visualization techniques.  
The notebook demonstrates data preprocessing, feature engineering, training different models, and evaluating their performance.

---

## 📘 Project Overview
- Perform **exploratory data analysis (EDA)** to understand the dataset.  
- Build classification and regression models to predict student outcomes.  
- Compare evaluation metrics such as **accuracy, MSE, and R² score**.  
- Visualize results with clear charts for better interpretation.

---

## 🧰 Technologies Used
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy` – data manipulation  
  - `matplotlib` – visualization  
  - `scikit-learn` – ML models (Decision Tree, Linear Regression, SVR, etc.)  

---

## 📂 Repository Structure
```
├── student-performance.ipynb   # Main notebook with code and results
├── README.md                   # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/student-performance.git
cd student-performance
```

### 2. Install dependencies
It’s recommended to use a virtual environment.  
```bash
pip install -r requirements.txt
```

> If `requirements.txt` is missing, install manually:
```bash
pip install pandas numpy matplotlib scikit-learn
```

### 3. Run the notebook
```bash
jupyter notebook student-performance.ipynb
```

---

## 📊 Models Implemented
- **Decision Tree Classifier** – predict pass/fail based on grades.  
- **Linear Regression** – predict continuous final score (G3).  
- **Support Vector Regression (SVR)** – regression analysis with different `C` values.  

---

## 📈 Results
- Classification accuracy for predicting **Pass/Fail**.  
- Regression metrics: **Mean Squared Error (MSE)** and **R² Score**.  
- Visualization of actual vs predicted values for model comparison.  

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License
This project is licensed under the MIT License.  
