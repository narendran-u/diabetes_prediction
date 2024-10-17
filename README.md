---

# **🩺 Diabetes Prediction System**

## **📌 Project Overview**
The **Diabetes Prediction System** predicts the likelihood of diabetes in individuals using various health parameters. This project utilizes machine learning techniques to provide early diagnosis and risk assessment, assisting healthcare professionals in patient management. 🚀

## **🎯 Objective**
To develop a predictive model that identifies patients at risk of diabetes, enabling timely intervention and better management of health outcomes. 🏥

## **🛠 Tech Stack**
- **Programming Language:** Python 🐍
- **Libraries:**
  - **Pandas**: For data manipulation
  - **NumPy**: For numerical calculations
  - **Scikit-learn**: For machine learning models (BaggingClassifier and DecisionTreeClassifier) 🤖
  - **Matplotlib & Seaborn**: For data visualization 📊

## **📊 Dataset**
The dataset used in this project is the **Pima Indians Diabetes Database** sourced from **Kaggle**. It includes various health-related features such as:
- Age
- Body Mass Index (BMI)
- Blood Pressure
- Glucose levels
- Insulin levels

## **🔍 Methodology**
1. **Data Preprocessing**  
   Clean and preprocess the dataset, handling missing values and normalizing features.

2. **Exploratory Data Analysis (EDA)**  
   Analyze data patterns and visualize relationships among features.

3. **Model Building**  
   Implement machine learning algorithms:
   - **Bagging Classifier** with **Decision Tree Classifier** for improved prediction accuracy.
  
   ```python
   from sklearn.ensemble import BaggingClassifier
   from sklearn.tree import DecisionTreeClassifier
   ```

4. **Model Evaluation**  
   The models are evaluated based on:
   - **Precision, Recall, and F1-Score**:
     ```
     precision    recall  f1-score   support
           0       0.96      0.91      0.94       104
           1       0.84      0.92      0.88        50
     
     accuracy                           0.92       154
     macro avg       0.90      0.92      0.91       154
     weighted avg       0.92      0.92      0.92       154
     ```

## **✨ Key Features**
- **User Input for Prediction**: Users can input health metrics to receive diabetes risk predictions. 📈
- **Visualizations**: Insights through charts and graphs to better understand risk factors.
- **User-friendly Interface**: Easy-to-navigate interface for non-technical users.

## **🔔 Conclusion**
The **Diabetes Prediction System** significantly assists healthcare providers in identifying at-risk patients, facilitating early diagnosis and intervention. This project aims to enhance patient care through technology. 💡

## **💻 How to Use**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/narendran-u/diabetes_prediction.git
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the application** to input data and obtain predictions.

## **📧 Contact**
For more information or inquiries, feel free to contact:
- **Narendran U**  
  - **Email:** [narenshankar2004@gmail.com](mailto:narenshankar2004@gmail.com)

---
