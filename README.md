❤️ Heart Disease Prediction using Neural Network (NumPy)
📌 Project Overview

This project implements a Neural Network from scratch using NumPy to predict the presence of heart disease based on patient medical data.
The goal of this project is to demonstrate how forward propagation, backpropagation, and gradient descent work internally without using deep learning frameworks such as TensorFlow or PyTorch.

The model is trained on clinical features such as age, blood pressure, cholesterol levels, chest pain type, ECG results, and more to classify whether a patient has heart disease.

__________________________________________________________________________________________________________________________________________________________________

🚀 Features:

Data preprocessing using Pandas
Feature scaling using StandardScaler
One-hot encoding for categorical variables
Neural network implemented from scratch using NumPy
Forward propagation
Backpropagation
Binary cross-entropy loss
Gradient descent optimization
Model evaluation using accuracy score

__________________________________________________________________________________________________________________________________________________________________

🧠 Neural Network Architecture:

Input Layer → Hidden Layer → Output Layer
Input Layer: Patient features
Hidden Layer: 16 neurons with tanh activation
Output Layer: 1 neuron with sigmoid activation (binary classification)
__________________________________________________________________________________________________________________________________________________________________

📊 Dataset:

The dataset contains various medical attributes used for heart disease prediction.

Example Features:
Age
Blood Pressure
Cholesterol
Maximum Heart Rate
Chest Pain Type
ST Depression
Number of Major Vessels
Thallium Test Results
Target Variable
0 → Absence of Heart Disease
1 → Presence of Heart Disease
__________________________________________________________________________________________________________________________________________________________________

⚙️ Technologies Used :

Python
NumPy
Pandas
Scikit-learn
Matplotlib
__________________________________________________________________________________________________________________________________________________________________

📂 Project Structure:
heart-disease-neural-network-from-scratch
├── Heart_Disease_Prediction.csv
├── heart_diagnosis.ipynb
├── README.md
__________________________________________________________________________________________________________________________________________________________________

🔄 Workflow :

1️⃣ Load dataset

2️⃣ Data preprocessing
Feature scaling
One-hot encoding

3️⃣ Train-test split

4️⃣ Neural network implementation
Weight initialization
Forward propagation
Loss computation
Backpropagation

5️⃣ Model training

6️⃣ Model evaluation
__________________________________________________________________________________________________________________________________________________________________

📈 Model Evaluation :

The model is evaluated using accuracy score on both training and testing data.
Example output: Train Accuracy: 0.878
Test Accuracy: 0.876

__________________________________________________________________________________________________________________________________________________________________

🧮 Loss Function

Binary Cross Entropy:
Loss=−m1​∑(ylog(p)+(1−y)log(1−p))

This loss function is used for binary classification problems.

__________________________________________________________________________________________________________________________________________________________________

🎯 Learning Objectives :

This project helps understand:
Neural networks from scratch
Backpropagation mathematics
Gradient descent optimization
Data preprocessing techniques
Binary classification problems

__________________________________________________________________________________________________________________________________________________________________

📌 Future Improvements :

Add multiple hidden layers (Deep Neural Network)
Implement regularization
Add training visualization
Implement mini-batch gradient descent
Compare with Scikit-learn models

__________________________________________________________________________________________________________________________________________________________________

👨‍💻 Author

Developed as a Machine Learning project to understand neural networks from first principles using NumPy.
