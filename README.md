# 🩺 Diabetes Prediction using Machine Learning

This project predicts whether a person has diabetes or not using the **Pima Indians Diabetes Dataset** from Kaggle. The solution is built using **Python**, **Pandas**, **Scikit-learn**, and **Seaborn** for data visualization.

---

## 📁 Dataset

- **Source**: [Kaggle - Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (Target: 0 = No Diabetes, 1 = Diabetes)

---

## 🚀 Project Workflow

1. Upload dataset on Google Colab.
2. Explore the dataset (missing values, class balance, feature types).
3. Visualize distributions and relationships using Seaborn.
4. Preprocess data (feature scaling using `StandardScaler`).
5. Train Logistic Regression model.
6. Evaluate using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
   - Accuracy Bar Chart

---

## 📊 Sample Output

- **Model Accuracy**: ~75-80%
- **Confusion Matrix**:

- **Accuracy Visualization**: Clean bar chart using Matplotlib

---

## 📷 Visualizations

- 📌 Outcome Distribution Count Plot
- 📌 Confusion Matrix Heatmap
- ![Screenshot 2025-05-27 144936](https://github.com/user-attachments/assets/242b2841-e1bd-4bc1-8f0c-f0addd3576ad)

- 📌 Accuracy Percentage Bar Chart
![Screenshot 2025-05-27 144837](https://github.com/user-attachments/assets/632ca188-0466-4665-b330-a4dacc3eb0f2)

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab

---

## 🧪 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload `diabetes.csv` when prompted using the file upload cell.
3. Run all cells from top to bottom.
4. View predictions, performance metrics, and visualizations.

---

## 📎 Future Improvements

- Add multiple ML models (Random Forest, KNN, SVM).
- Hyperparameter tuning using GridSearchCV.
- Deploy with Streamlit for real-time input predictions.
- Handle zero values in medical columns as missing data.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- Dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)
- Kaggle community for providing the data.

