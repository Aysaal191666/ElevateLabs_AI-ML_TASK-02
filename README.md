# ElevateLabs_AI-ML_TASK-02
# Exploratory Data Analysis (EDA) on Titanic Dataset
This project performs EDA on the Titanic dataset using Pandas, Matplotlib, and Seaborn to uncover patterns and insights.

## 🔍 Objective
Understand the structure, distribution, and patterns in the data using visual and statistical tools.

## 📊 What’s Covered
- Summary statistics (mean, median, std)
- Handling missing data
- Visualizations (histograms, boxplots, pairplot)
- Correlation matrix
- Feature-level insights and trends

## 🛠 Tools Used
- Pandas
- Seaborn
- Matplotlib
- Plotly (optional)

## 📁 Dataset
Titanic Dataset from Kaggle: [Link](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## 📊 Visualizations Included

### 🔹 Individual Visualizations
- 📊 **Histograms** of all numeric features (`Age`, `Fare`, `SibSp`, `Parch`, etc.)
- 📦 **Boxplot** showing the distribution of `Age` by `Survived` status
- 🔥 **Correlation heatmap** to observe linear relationships between numeric features
- 🌀 **Pairplot** of `Age`, `Fare`, and `Pclass` against survival status for multivariate exploration

### 🖼️ Combined Visual Summary in `results.png`
The following visualizations are saved in one single image file named **`results.png`**:
- Histogram of `Fare`
- Boxplot of `Age` vs `Survived`
- Correlation Heatmap
- Scatter Plot: `Age` vs `Fare` colored by `Survived`

This compact summary provides a quick visual overview of key relationships and patterns in the Titanic dataset.

## 📌 How to Run
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open `titanic_eda.ipynb` and run all cells.

---
