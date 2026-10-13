# Data Pre-processing and Decision Tree on Student Data

Takes a raw, unsorted student dataset, pre-processes it step by step and predicts whether a student will Pass or Fail using a Decision Tree.

## Workflow
Raw Data → EDA → Missing Values → Outliers → Feature Scaling → Feature Selection → Clean Data → Machine Learning

## Topics Covered
- Sorting data, `df.shape`, `df.head()`, `df.info()`, `df.describe()`, `df.isnull().sum()`, `df.duplicated().sum()`
- Histogram and boxplot
- Handling missing values (remove row, mean, median, mode)
- Outlier detection (IQR) and treatment (capping)
- Feature scaling: Normalization and Standardization
- Feature selection: Correlation, RFE, Random Forest importance
- Decision Tree: parts of a tree, Gini impurity, how the best split is chosen

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Run
1. `pip install numpy pandas matplotlib seaborn scikit-learn`
2. Open `Student_Performance_Data_Preprocessing.ipynb` in Jupyter Notebook, VS Code or Google Colab
3. Run all cells
