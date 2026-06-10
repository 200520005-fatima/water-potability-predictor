# Water Quality Prediction Web App

A Machine Learning-driven Web Application built using **Flask** that evaluates whether water is safe for human consumption based on its biochemical properties[cite: 1, 4].

## 🚀 Live Demo & Resources
* **Web App:** [Link to Website](https://water-quality-prediction.herokuapp.com)[cite: 1]
* **Jupyter Notebook:** [View Notebook](https://datalore.jetbrains.com/view/notebook/R7vg78cqDWRrL3zDoHnjlz)[cite: 1]
* **Dataset Source:** [Kaggle Water Potability Dataset](https://www.kaggle.com/adityakadiwal/water-potability)[cite: 1]

---

## 📊 Dataset Overview
The dataset contains water quality metrics for **3,276** different water bodies[cite: 2]. It includes 10 features:
1. **pH:** Evaluates the acid-base balance of water[cite: 2].
2. **Hardness:** Capacity of water to precipitate soap[cite: 2].
3. **Solids (Total Dissolved Solids):** Mineralization level of the water[cite: 2].
4. **Chloramines:** Amount of Chlorine and Ammonia used as disinfectants[cite: 2].
5. **Sulfate:** Naturally occurring minerals[cite: 2].
6. **Conductivity:** Electrical conductivity determined by dissolved ionic matter[cite: 2].
7. **Organic Carbon:** Measure of the total amount of carbon in organic compounds[cite: 2].
8. **Trihalomethanes:** Chemicals formed as a byproduct of water chlorination[cite: 2].
9. **Turbidity:** Measure of light-emitting properties dependent on suspended solids[cite: 2].
10. **Potability (Target):** Indicates if water is safe for human consumption (`1` = Safe, `0` = Unsafe)[cite: 2].

---

## 🛠️ Tech Stack & Libraries
* **Backend:** Flask (Python)[cite: 4]
* **Machine Learning:** `scikit-learn`, `pandas`, `numpy`[cite: 2, 5]
* **Data Visualization:** `seaborn`, `matplotlib`[cite: 2]
* **Deployment:** Gunicorn, Procfile (Heroku ready)[cite: 5, 6]

---

## 💻 Local Installation & Setup

1. **Clone the Repository:**
```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd water-quality-prediction
