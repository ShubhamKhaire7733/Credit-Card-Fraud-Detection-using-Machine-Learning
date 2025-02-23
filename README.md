# Fraud Detection in Financial Transactions  
🚀 Python | Scikit-learn | Plotly | 2025  

## 📌 Overview  
This project implements a **fraud detection system** using multiple **machine learning models** to predict fraudulent transactions in financial datasets. The system is trained on a dataset of **28,221 transactions** and evaluated using **10-fold cross-validation** for accurate predictions.

## 📂 Dataset  
The dataset consists of:  

✅ **28,221 transactions** containing features like transaction type, amount, and account balances.  
✅ **Target variable**: **isFraud** (1 for fraud, 0 for non-fraud).

**Data preprocessing** includes handling missing values and encoding categorical features for model training.

## 🛠️ Technologies Used  
- Python (Pandas, NumPy, Matplotlib)  
- Scikit-learn  
- Plotly  
- Jupyter Notebooks  

## 📖 Model Architecture  
Multiple machine learning models were implemented for fraud detection, including:

- **Logistic Regression**  
- **Decision Trees**  
- **K-Nearest Neighbors (KNN)**  
- **Naive Bayes (NB)**  
- **Support Vector Machines (SVM)**

**Evaluation** was done using **10-fold cross-validation** to ensure robust model performance.

## 📊 Performance  
- **High accuracy** achieved in detecting fraudulent transactions.  
- Evaluated using **accuracy** and **cross-validation** metrics.  

## 🚀 How to Run  
1️⃣ **Clone the Repository**  
```bash  
git clone https://github.com/ShubhamKhaire7733/Online_Payments_Fraud_Detection_with_Machine_Learning.git  
cd Online_Payments_Fraud_Detection_with_Machine_Learning
```
2️⃣ **Install Dependencies**
```bash
# Install the required Python libraries
pip install -r requirements.txt
```
# 3️⃣ Train the Model
```bash
# Run fraud_detection_model.py to train models on the dataset
python Online_Payments_Fraud_Detection_with_Machine_Learning.py
```
# 4️⃣ Test the Model
```bash
# Run the model on new data
python test_model.py --data path/to/test_data.csv
```
## 📌 Results & Insights  
- The model successfully predicts fraudulent transactions.  
- Data preprocessing and **cross-validation** significantly improved model accuracy.  
- **Plotly** was used to visualize transaction distributions and model insights.

**Future Improvements**:  
- Incorporate **ensemble methods** for better model accuracy.  
- Implement **real-time fraud detection** and monitoring.

## 🔗 **Connect & Contribute**  
Feel free to contribute! Open an issue or pull request. 😊  

📧 **Contact**: [shubhamkhaire7733@gmail.com]  
🌐 **GitHub**: [https://github.com/ShubhamKhaire7733]
