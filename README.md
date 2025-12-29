# Iris Flower Species Classification using Machine Learning

## 📌 Project Overview
This project implements a **supervised machine learning classification model** to predict the species of an Iris flower based on its physical features. The project compares **Logistic Regression** and **Random Forest** models and evaluates their performance using standard classification metrics.

---

## 🎯 Objective
To build and evaluate machine learning models that accurately classify Iris flower species and identify the best-performing algorithm.

---

## 📂 Dataset
- **Iris Dataset** (from `sklearn.datasets`)
- 150 samples
- 4 numerical features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- 3 classes:
  - Setosa
  - Versicolor
  - Virginica

---

## 🛠️ Tools & Technologies
- Python 3.x
- scikit-learn
- NumPy
- Matplotlib
- Google Colab
- GitHub

---

## ⚙️ Methodology
1. Loaded the Iris dataset from scikit-learn
2. Preprocessed the data using feature scaling
3. Split data into training and testing sets (80/20)
4. Trained two classification models:
   - Logistic Regression
   - Random Forest Classifier
5. Evaluated models using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
6. Visualized results with:
   - Confusion Matrices
   - ROC-AUC Curve
7. Compared models to select the best performer

---

## 📊 Results
| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression | ~97%     |
| Random Forest       | ~100%    |

- Random Forest achieved the highest accuracy
- Confusion matrices and ROC curves confirm strong model performance

---

## ▶️ How to Run
1. Open Google Colab or Jupyter Notebook
2. Upload `ML_Classification_Iris_Project.ipynb`
3. Run all cells sequentially
4. View metrics, confusion matrices, and ROC curve outputs

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Curve

---

## 🧠 Conclusion
The project demonstrates how supervised machine learning algorithms can effectively classify Iris flower species. Random Forest outperformed Logistic Regression due to its ability to handle non-linear relationships.

---

## 🚀 Future Enhancements
- Evaluate additional algorithms (SVM, Gradient Boosting)
- Apply cross-validation for robustness
- Deploy the model as a web application

---

## 👩‍💻 Author
Durga
