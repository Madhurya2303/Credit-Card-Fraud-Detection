# Credit-Card-Fraud-Detection
This project focuses on detecting fraudulent credit card transactions using machine learning models. Since fraud cases are significantly fewer than legitimate transactions, an under-sampling technique is used to balance the dataset and improve model performance.
Understood! Since your notebook uses **undersampling** instead of SMOTE, here’s the correct README file for your GitHub repository:  

---

# **Credit Card Fraud Detection**  

## **Description**  
This project focuses on detecting fraudulent credit card transactions using machine learning models. Since fraud cases are significantly fewer than legitimate transactions, an **undersampling** technique is used to balance the dataset and improve model performance.  

The notebook was developed in **Google Colab**, leveraging cloud-based resources for efficient computation.  

## **Dataset**  
- **Source:** (e.g., Kaggle’s "Credit Card Fraud Detection" dataset)  
- **Features:** 28 principal components (PCA-transformed) + `Time` and `Amount`  
- **Target:** `Class` (0 = Legitimate, 1 = Fraudulent)  
- **Imbalance Issue:** Fraud cases account for <1% of total transactions  

## **Techniques Used for Data Balancing**  
- **Undersampling:** Reducing the number of majority class samples (legitimate transactions) to match the minority class (fraudulent transactions).  
- **Why Undersampling?** Helps prevent the model from being biased toward non-fraudulent transactions while maintaining a reasonable dataset size for training.  

## **Technologies Used**  
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn (Logistic Regression, Decision Trees, Random Forest, etc.)  
- **Google Colab Features:** GPU acceleration, Google Drive integration  

## **Installation & Usage**  
1. Open the Colab notebook (`Credit_Card_Fraud_Detection.ipynb`).  
2. Upload the dataset (if required).  
3. Run the cells sequentially to preprocess data, apply undersampling, train models, and evaluate performance.  

To use locally:  
```bash
pip install -r requirements.txt
```
Then, open the notebook with:  
```bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

## **Results**  
- **Evaluation Metrics:** Accuracy
---
