# Iris-dataset-with-SVM-model
# Iris Dataset Classification with SVM

## 📌 Project Overview
This project uses the **Iris dataset** to build a classification model using **Support Vector Machine (SVM)** from `scikit-learn`.  
The Iris dataset is a classic dataset in machine learning, containing 150 samples of iris flowers, each described by four features:

- Sepal length
- Sepal width
- Petal length
- Petal width

The goal is to classify the flowers into one of three species:
- **Setosa**
- **Versicolor**
- **Virginica**

---

## ⚙️ Technologies Used
- **Python 3**
- **Jupyter Notebook**
- **scikit-learn**
- **pandas**
- **matplotlib**
- **seaborn**

---

## 📂 Dataset
The dataset is available in the `sklearn.datasets` module or from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris).

---

## 🔍 Steps in the Project
1. **Import the Dataset**
   - Load the Iris dataset using `sklearn.datasets.load_iris()`.

2. **Data Exploration**
   - View dataset structure, features, and target classes.
   - Perform exploratory data analysis (EDA) with plots.

3. **Data Preprocessing**
   - Split the dataset into training and testing sets.
   - Scale the features for better SVM performance.

4. **Model Training**
   - Train an SVM classifier with different kernels (linear, polynomial, RBF).
   - Compare model performance for each kernel.

5. **Evaluation**
   - Evaluate the model using accuracy, confusion matrix, and classification report.

6. **Visualization**
   - Plot decision boundaries (for 2D feature projections).
   - Show confusion matrix heatmaps.

---

## 📊 Results
- **Best Kernel**: Linear (or specify which one performed best)
- **Accuracy**: ~XX% (replace with your accuracy score)
- **Observations**:  
  - Setosa is easily separable.
  - Some overlap between Versicolor and Virginica.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone git@github.com:OmarAhmedElwekeil/Iris-dataset-with-SVM-model.git
2. Navigate to the project folder:
   ```bash
   cd Iris-dataset-with-SVM-model
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Open Jupyter Notebook:
   ```bash
   jupyter notebook

5. Run the SVM.ipynb notebook.