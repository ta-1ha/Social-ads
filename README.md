# Social-ads

 i am using the four different algos for model training mainly the Support Vector Machine (SVM) for a classification. It includes:

Data loading with pandas

Exploratory Data Analysis (EDA) using Seaborn and Matplotlib

Data preprocessing

SVM model training


# SVM Classification on Social Network Ads Dataset

This project demonstrates a complete machine learning pipeline using Support Vector Machine (SVM) to classify user purchase behavior based on features from the Social Network Ads dataset.

## 📁 Dataset

- **Name**: Social_Network_Ads.csv
- **Features**: Age, Estimated Salary
- **Target**: Purchased (0 = No, 1 = Yes)

## 🔍 Workflow

1. **Import Libraries**  
   Libraries used: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

2. **Load Dataset**  
   Read the dataset using `pandas` and inspect for missing values and dimensions.

3. **EDA (Exploratory Data Analysis)**  
   Visualizations created using `seaborn` to understand feature distribution and relationships.

4. **Preprocessing**  
   - Encoding categorical data (if needed)
   - Feature scaling (standardization)

5. **Modeling**  
   - Splitting dataset into training and test sets
   - Fitting the **SVM classifier** (`sklearn.svm.SVC`)
   - Model evaluation using accuracy, confusion matrix, etc.

6. **Results**  
   Model performance is evaluated, and decision boundaries may be visualized.

## ⚙️ Technologies

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Seaborn
- Matplotlib

## 📊 Output

- Visual analysis of features
- Confusion matrix of model predictions
- Accuracy score of the SVM model



