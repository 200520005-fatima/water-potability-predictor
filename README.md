# Water Quality Prediction Web App

A Machine Learning-driven Web Application built using **Flask** that evaluates whether water is safe for human consumption based on its biochemical propertie.

## 🚀 Live Demo & Resources
* **Web App:** [Link to Website](https://water-quality-prediction.herokuapp.com)
* **Jupyter Notebook:** [View Notebook](https://datalore.jetbrains.com/view/notebook/R7vg78cqDWRrL3zDoHnjlz)
* **Dataset Source:** [Kaggle Water Potability Dataset](https://www.kaggle.com/adityakadiwal/water-potability)

---

## 📊 Dataset Overview
The dataset contains water quality metrics for **3,276** different water bodies. It includes 10 features:
1. **pH:** Evaluates the acid-base balance of water.
2. **Hardness:** Capacity of water to precipitate soap.
3. **Solids (Total Dissolved Solids):** Mineralization level of the water.
4. **Chloramines:** Amount of Chlorine and Ammonia used as disinfectants.
5. **Sulfate:** Naturally occurring minerals.
6. **Conductivity:** Electrical conductivity determined by dissolved ionic matter.
7. **Organic Carbon:** Measure of the total amount of carbon in organic compounds.
8. **Trihalomethanes:** Chemicals formed as a byproduct of water chlorinatio.
9. **Turbidity:** Measure of light-emitting properties dependent on suspended solids.
10. **Potability (Target):** Indicates if water is safe for human consumption (`1` = Safe, `0` = Unsafe).

---

## 🛠️ Tech Stack & Libraries
* **Backend:** Flask (Python)
* **Machine Learning:** `scikit-learn`, `pandas`, `numpy`
* **Data Visualization:** `seaborn`, `matplotlib`
* **Deployment:** Gunicorn, Procfile (Heroku ready)

---

## 💻 Local Installation & Setup

1. **Clone the Repository:**
```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd water-quality-prediction
