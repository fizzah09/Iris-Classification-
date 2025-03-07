# 🌸 **Iris Dataset Classification with Random Forest** 🌸

## 🚀 **Overview**
This project explores the **Iris dataset** 🌿, a well-known dataset for classification tasks. The goal is to classify iris flowers 🌼 into one of **three species** (*Setosa, Versicolor, Virginica*) based on their **sepal length, sepal width, petal length, and petal width* 📏. We use the **Random Forest Classifier** 🌲 to achieve high accuracy. 🎯

## 📂 **Dataset**
The dataset consists of **150 samples** 📊, with **four numerical features** and a categorical target variable (*species*). It is available in CSV format and can be found on **Kaggle** 📑.

## 🔍 **Steps Performed**

1️⃣ **Data Loading & Preprocessing** 📥  
   - Loaded the dataset using `pandas` 🐼.
   - Checked for missing values ❌ and performed data cleaning 🧹.
   - Encoded the categorical target variable using `LabelEncoder` 🎛️.

2️⃣ **Exploratory Data Analysis (EDA)** 📊  
   - Visualized data distributions using histograms 📈 and pair plots 🔎.
   - Created a **correlation matrix** 📌 to understand feature relationships.
   - Plotted scatter plots 🌈 to analyze species separability.

3️⃣ **Feature Engineering & Model Training** 🤖  
   - Selected **sepal length, sepal width, petal length, and petal width** as features 🎯.
   - Split the dataset into **training (80%)** and **testing (20%)** sets 🔀.
   - Trained a **Random Forest Classifier** 🌲 (`n_estimators=100, random_state=42`).

4️⃣ **Model Evaluation** 🏆  
   - Achieved **100% accuracy** 🎯 on the test set.
   - Generated a **classification report** 📝 with precision, recall, and F1-score.
   - Verified model performance using **cross-validation** ✅.

5️⃣ **Feature Importance Analysis** 🌟  
   - Identified that **petal length and petal width** were the most significant features 🔥.
   - Visualized feature importance using a bar chart 📊.

6️⃣ **Prediction on Unseen Data** 🔮  
   - Created synthetic flower samples 🌺.
   - Used the trained model to predict their species 🤖.
   - Converted numerical predictions back to species names 🏷️.

## 🎯 **Results**
✔️ The **Random Forest model achieved 100% accuracy** 🏅, confirming the dataset’s well-separated nature.  
✔️ **Feature importance analysis** revealed that **petal length and petal width** were the strongest predictors 🔑.  
✔️ No **data leakage** was detected 🛡️, and cross-validation showed stable performance 📈.  

## ⚙️ **Installation & Usage**
### 🛠️ **Requirements**
- Python 3.10+ 🐍
- `pandas`, `numpy`, `matplotlib`, `seaborn` 📦
- `scikit-learn` 🤖

### ▶️ **Run the Notebook**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```
Then, open the notebook and execute the cells 🎯.

## 🚀 **Future Enhancements**
✨ Implement **other models** like SVM or Neural Networks for comparison 🧠.  
✨ Apply **hyperparameter tuning** for further optimization 🔧.  
✨ Deploy the model using a **Flask API** or **Streamlit web app** 🌐.  

---
📌 **Author**: Fizzah Abdullah 👩‍💻  
📌 **Platform**: Kaggle 🏆  
🚀 **Goal**: Classify iris species using machine learning 🌿  

