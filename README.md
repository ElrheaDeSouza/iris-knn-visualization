# 🌸 Iris Dataset Classification and Visualization using KNN

This project explores the classic **Iris dataset** using various **visualization techniques** and builds a **K-Nearest Neighbors (KNN)** classification model to predict the species of iris flowers. It serves as a great beginner-level project for understanding both data analysis and machine learning.

---

## 📁 Dataset

The Iris dataset is a well-known dataset in machine learning, containing:
- 150 samples of iris flowers
- 4 features: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`
- 3 target species: `setosa`, `versicolor`, `virginica`

Used `sklearn.datasets.load_iris()` to load the data.

---

## ✅ Tasks Covered

### 🧼 1. Data Loading & Inspection
- Load dataset using `sklearn.datasets.load_iris()`
- Converted to a Pandas DataFrame
- Checked dataset type, structure, and head

### 📊 2. Data Visualization
- **Pair Plot** using Seaborn to visualize feature relationships
- **Violin Plot** to see feature distributions across species
- **Correlation Heatmap** to explore feature correlations
- **Andrews Curves** to view high-dimensional patterns
- **3D Scatter Plot** for spatial separation of species
- **Decision Boundary Visualization** using KNN and meshgrid

### 🧠 3. Model Building (KNN)
- Selected important features
- Split the dataset using `train_test_split(test_size=0.3)`
- Trained a **K-Nearest Neighbors Classifier**
- Made predictions on test data

### 📈 4. Model Evaluation
- Printed **Classification Report**
- Calculated **Accuracy Score**
- Plotted **Confusion Matrix**
- Plotted **Accuracy vs. k-value** to find optimal `k`

---

## 📌 Libraries Used

- `pandas` – for data handling
- `numpy` – for numerical operations
- `matplotlib`, `seaborn` – for plotting and visualization
- `sklearn` – for machine learning models and evaluation metrics

---

## 📷 Visualizations

- 🔍 **Pairplot** to view how each feature interacts with others
- 🎻 **Violin Plot** to compare distribution across species
- 🔥 **Heatmap** to reveal feature correlations
- 🧬 **Andrews Curves** to visualize high-dimensional patterns
- 🌐 **3D Scatter Plot** of flower features
- 🧭 **Decision Boundary Plot** to visualize classification regions

---

## 📊 Results

- Achieved **high accuracy** with KNN
- Found optimal `k` by plotting accuracy vs. k
- Visualized clear **class separation** in feature space



