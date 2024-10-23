
# **🩺💡 Disease Symptom Prediction 💡🩺**

## **🔍 Overview**
This project utilizes **machine learning** to predict diseases based on input symptoms. By analyzing symptom data, the model aims to assist in early detection and healthcare decision-making.

## **📂 Dataset**
The project uses multiple dataset files that provide detailed information about symptoms, their severity, and precautions for various diseases. The datasets have been preprocessed for **training**, **validation**, and **testing**.

### **🗂️ Dataset Files**:
- **Symptom-severity.csv**: Contains a list of symptoms along with their severity levels 🤒.
- **dataset.csv**: The main dataset with symptoms as features and the corresponding diseases 🩺.
- **symptom_Description.csv**: Provides detailed descriptions of each symptom 📄.
- **symptom_precaution.csv**: Lists recommended precautions for each symptom 🛡️.


## **🤖 Models Used**
Several **machine learning models** were trained on the dataset to predict diseases, achieving high accuracy. The top-performing models are:

- **K-Nearest Neighbors (KNN)** 🌟 (best accuracy: **99.59%**)
- **Random Forest Classifier** 🌳 (accuracy: **99.39%**)
- **Decision Tree Classifier** 🌲 (accuracy: **99.39%**)
- **Support Vector Classifier (SVC)** 🧠 (accuracy: **92.07%**)
- **Logistic Regression** 📉 (accuracy: **90.55%**)

### **🔧 Model Architecture**:
- **K-Nearest Neighbors (KNN)**: Classifies based on the most similar data points.
- **Random Forest**: An ensemble of decision trees to improve prediction accuracy.
- **Decision Tree**: Constructs a tree where decisions are based on features.
- **Support Vector Classifier (SVC)**: Finds the best hyperplane separating the classes (diseases).
- **Logistic Regression**: A linear model used for classification.

### **⚙️ Data Preprocessing**:
- **Data Cleaning**: Managed missing data and handled inconsistencies.
- **Feature Engineering**: Encoded symptoms into a format suitable for machine learning models.

## **📊 Results**
The **K-Nearest Neighbors (KNN)** model achieved the highest accuracy of **99.59%**, with **Random Forest** and **Decision Tree** models closely following at **99.39%**.

- **K-Nearest Neighbors**: 99.59% 🌟
- **Random Forest**: 99.39% 🌳
- **Decision Tree**: 99.39% 🌲
- **Support Vector Classifier**: 92.07% 🧠
- **Logistic Regression**: 90.55% 📉

## **🚀 Future Improvements**
- **Feature Expansion**: Include additional data, such as demographic factors (age, gender, medical history), to improve model accuracy 🧬.
- **Model Optimization**: Fine-tune hyperparameters to enhance performance ⚙️.
- **Deployment**: Develop a web or mobile app for real-time symptom input and disease prediction 📱.
