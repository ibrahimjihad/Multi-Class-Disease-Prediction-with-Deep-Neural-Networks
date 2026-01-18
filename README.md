📋 Project Overview: 
This project focuses on the development of an intelligent health risk prediction model using Deep Learning architectures. The primary goal is to identify patterns in patient demographic and clinical data to predict multiple categories of chronic diseases. By leveraging a Deep Neural Network (DNN) built with TensorFlow and Keras, this system achieves high accuracy in multi-class classification, serving as a proof-of-concept for automated diagnostic aids in healthcare.

📊 Dataset:
The model is trained on a real-world healthcare risk factors dataset (available on Kaggle).


Total Samples: 30,000 patient records.


Target Classes: 7 distinct health states (Hypertension, Diabetes, Obesity, Healthy, Asthma, Arthritis, and Cancer).


Features: 17 key attributes including Age, BMI, Glucose, Blood Pressure, Oxygen Saturation, Family History, and lifestyle factors.

🛠️ Key Tasks & Methodology:
The project follows a structured data science pipeline:


Data Preprocessing: Handling missing values, feature scaling (StandardScaler), and label encoding.


Exploratory Data Analysis (EDA): Class distribution visualization and feature importance analysis.


Model Architecture: A multi-layered Deep Neural Network (DNN) with 79,239 trainable parameters.


Optimization: Implementation of early stopping and model checkpoints to prevent overfitting.


Evaluation: Use of confusion matrices, ROC curves, and classification reports.

🚀 Key Results:

Test Accuracy: 91.87%.


Predictive Power: The model effectively identifies high-risk patients across 7 disease categories.


Framework: Scalable and reproducible pipeline for clinical EHR (Electronic Health Record) validation.

📁 Repository Structure:

CSE437_Project_Group6.ipynb: Complete source code for data loading, preprocessing, model training, and evaluation.


Report.pdf: Detailed project documentation including methodology, results, and references.


requirements.txt: Necessary libraries (pandas, numpy, tensorflow, scikit-learn, etc.).

💻 Installation & Usage:
Clone the repository:

Bash
git clone https://github.com/your-username/Multi-Class-Disease-Prediction.git
Install dependencies:

Bash
pip install -r requirements.txt
Run the Jupyter Notebook to train the model or perform predictions.

👥 Authors:
Md. Zobayer (BRAC University) 

Md. Shoyeb Akhter (BRAC University) 

Md. Ibrahim Akanda (BRAC University) 


Mahmudul Hasan Tamal (BRAC University)
