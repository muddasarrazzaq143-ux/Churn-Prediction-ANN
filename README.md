📘 Customer Churn Prediction (Neural Network From Scratch)

This project predicts customer churn for a bank using a manually built neural network—implemented entirely from scratch without Scikit-Learn, TensorFlow, or PyTorch.
The model identifies customers likely to leave so the bank can take proactive retention actions.

🚀 Project Summary

Predict whether a customer will exit (churn) or stay

Implemented a full ANN from scratch using NumPy

Includes forward pass, backpropagation, gradient descent

Data preprocessing: encoding, scaling, and manual train/test split

Provides business insights on churn patterns

📊 Dataset

10,000 customers

Churn rate: 20% (imbalanced dataset)

Features include age, credit score, geography, balance, salary, etc.

🧠 Model Architecture
Input Layer: 11 features  
Hidden Layer 1: 16 neurons (ReLU)  
Hidden Layer 2: 8 neurons (ReLU)  
Output Layer: 2 neurons (Softmax)

📉 Performance

Loss: 0.48 → 0.32

Training Accuracy: 86.3%

Test Accuracy: 85.7% (no overfitting)

🔍 Key Insights

Churn is highest among 40–60 age customers

Salary has weak correlation with churn

German customers churn more

Active members churn less

📁 Files

Churn_ANN_Project.ipynb – full implementation

Churn_Modelling_Presentation.pptx – slides

Use_Case_Summary.pdf – summary document

Churn_Modelling.csv – dataset
