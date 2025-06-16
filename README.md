# Liver Cirrhosis Stage Prediction

This project predicts the stage of liver cirrhosis using machine learning algorithms on a structured dataset. The notebook explores various models and concludes with Random Forest as the best performer.

## 📁 Dataset

The dataset used is `liver_cirrhosis.csv`, which contains clinical and diagnostic data related to liver cirrhosis.

## 🧠 Models Explored

- Logistic Regression
- K-Nearest Neighbors (KNN)
- XGBoost
- Random Forest (final choice)

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Joblib (for model serialization)

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/liver-cirrhosis-prediction.git
   cd liver-cirrhosis-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook jpduminy.ipynb
   ```

## ✅ Results

- Random Forest outperformed other models in terms of accuracy and reliability.
- Includes a sample input test at the end of the notebook.

## 📌 Note

Ensure `liver_cirrhosis.csv` is placed in the correct path as specified in the notebook, or update the path accordingly.
