# Online Payments Fraud Detection using Machine Learning
## 📌 Project Overview
This project focuses on detecting online payment fraud using Machine Learning techniques.  
We trained a classification model to identify whether a transaction is fraudulent or not based on transaction features.
We also deployed the model using **Flask Web Framework** so that users can interact with the model through a simple web interface.

---

## 👩‍💻 Team Members
- Gajjala Srithika
- Bandi Ramyasree
- Bollineni Lekhana
- Varikuti Pallavi

---

## 🚀 Technologies Used

- Python
- Scikit-learn (for Machine Learning)
- Flask (for Web App deployment)
- Pandas, NumPy, Matplotlib (for data handling and visualization)
- HTML, CSS (for frontend UI)

---

## 📂 Project Structure
online-payment-fraud-detection-ml/
├── app.py # Flask application
├── paymets.pkl # Trained Machine Learning model 
├── templates/ # HTML templates (home.html, predict.html, result.html)
├── static/ # CSS file
├── Online_Fraud_Detection.ipynb #  ML model training and evaluation
├── Documentation
└── README.md # Project overview and documentation

---

## 📥 Dataset Information

**Important Note:**  
We have **NOT uploaded the dataset file in this repository** because the dataset size is large (~25GB) and exceeds GitHub's upload limits.

### Dataset Source:

- Kaggle: [Online Payment Fraud Detection Dataset](/kaggle/input/online-payments-fraud-detection-dataset)  

---

## 🛠️ Machine Learning Workflow

1. **Data Collection:**  
  Downloaded online payment transaction dataset.

2. **Exploratory Data Analysis (EDA):**  
  Cleaned the data, handled missing values, explored fraud patterns.

3. **Feature Engineering:**  
  Selected important features for better model accuracy.

4. **Model Building:**  
  Trained different models like Random Forest Classifier, Decision Tree Classifier etc.

5. **Model Evaluation:**  
  Used metrics like Accuracy, Precision, Recall, F1-score.

6. **Deployment:**  
  Built a simple Flask web app for end-user predictions.

---

**Note:**  
The application will run on your local machine and can be used to predict whether an online payment transaction is fraudulent or legitimate.
The project is also deployed on Render and can be accessed using the deployment link provided below.
##How to run the project locally 
1. Clone this repository.
2. Install the required dependencies using:
```bash
pip install -r requirements.txt
```
3. Run the Flask application using:
```bash
python app.py
```
4. Open your web browser and visit:
```
http://127.0.0.1:5000
```


## 🌐 Deployment Link 

The project is deployed and running live on Render. You can access the live app here:
👉 https://online-payment-fraud-detection-1-pshw.onrender.com

---

## Conclusion
This project demonstrates how Machine Learning can help detect online payment frauds.
It covers model training, evaluation, and web deployment using Flask.

---

📞 Contact
For any queries, contact:
Srithika Gajjala, 
email : srithikareddy06@gmail.com
