# Fraud_Credit_Card_Detection_Application
Here's your concise README file:  

---

# **Credit Card Fraud Detection**  

This project implements a fraud detection system for credit card applications using **Self-Organizing Maps (SOM)** and **Artificial Neural Networks (ANNs)**.  

## **Overview**  
1. **Data Preprocessing:**  
   - The dataset is normalized using **MinMaxScaler**.  

2. **Unsupervised Fraud Detection with SOM:**  
   - A **10x10 SOM** is trained to identify potential fraud cases based on outliers.  
   - Fraudulent customer IDs are extracted from SOM mappings.  

3. **Supervised Learning with ANN:**  
   - An **Artificial Neural Network (ANN)** is trained to classify fraudulent applications using labeled data from the SOM step.  
   - The model is compiled using **Adam optimizer** and **binary cross-entropy loss**.  

4. **Evaluation:**  
   - The ANN predictions are evaluated using **classification reports**, including **precision, recall, and F1-score**.  

## **Usage**  
1. Install dependencies:  
   ```bash
   pip install numpy pandas matplotlib minisom tensorflow scikit-learn
   ```
2. Run the script:  
   ```bash
   python fraud_detection.py
   ```  

## **Results**  
The trained model achieves a **binary cross-entropy loss of 0.2106**, providing accurate fraud detection.  
