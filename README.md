# Anomaly Detection Using Smartphone Dataset Project  
**Infosys Springboard 5.0 Internship | October-November 2024**  

This project applies advanced **anomaly detection techniques** to analyze smartphone sensor data in crowded environments. The aim is to identify unusual behaviors or patterns that may indicate safety issues, anomalies, or suspicious activities, leveraging machine learning methods for effective predictions.  

---

## **Table of Contents**  
1. [Overview](#overview)  
2. [Features](#features)  
3. [Project Resources](#project-resources)  
4. [Deployment Links](#deployment-links)  
5. [Usage](#usage)  
6. [How It Works](#how-it-works)  
7. [Acknowledgments](#acknowledgments)  

---

## **Overview**  

In crowded settings, smartphone sensors can provide valuable insights into movements, gestures, and unusual activities. This project utilizes data from **accelerometers**, **gyroscopes**, and other smartphone features to detect anomalies in a precise and scalable manner. A **Gradient Boosting Classifier** serves as the core algorithm, offering high accuracy and robust anomaly detection capabilities.  

### **Core Objectives**  
- Analyze real-time and batch data for detecting anomalies.  
- Ensure high accuracy, precision, recall, and F1 score for the detection algorithm.  
- Provide an easy-to-use platform for custom input testing and bulk file processing.  

---

## **Features**  

### **1. Real-Time Anomaly Detection**  
- Input specific sensor readings manually and receive instant predictions.  

### **2. Batch Processing**  
- Upload CSV files containing multiple sensor data rows to process and classify anomalies efficiently.  

### **3. Interactive User Interface**  
- Deployed as a web app for seamless user interaction, leveraging **Streamlit**.  

### **4. Robust Performance**  
- Achieved metrics:  
  - **Accuracy:** 97.82%  
  - **Precision:** 97.58%  
  - **Recall:** 98.75%  
  - **F1 Score:** 98.16%  

---

## **Project Resources**  

### **Demo Video**  
[📹 Watch the Demo Video](https://drive.google.com/file/d/1m3lrMVD4Ig9r6MjQrmDMjnE8cwAeLJoU/view?usp=sharing)  

### **Documentation**  
[📄 View the Documentation](https://drive.google.com/file/d/1UW7MiltPtBNdah8IMA2TgQlHn8xfJ5-4/view?usp=sharing)  

### **Presentation**  
[📑 Access the PPT](https://docs.google.com/presentation/d/1emY6SoHMc9_ZDs6vkGavcVyXi5o3S4Q2/edit?usp=sharing&ouid=112195040657871254632&rtpof=true&sd=true)  

---

## **Deployment Links**  

### **Live Application on Hugging Face**  
[🌐 Anomaly Detection App](https://huggingface.co/spaces/DishaMondal2024/Anomaly_Detection_Smartphone_Dataset)  

### **Website Demo**  
[📹 Watch Website Demo](https://drive.google.com/file/d/1FL9g-Xn4c9jwYIVh4Lg0DwoL3RhikTlY/view?usp=sharing)  

---

## **Usage**  

### **1. Prerequisites**  
- Python 3.9 or above  
- Libraries: `scikit-learn`, `streamlit`, `pandas`, `numpy`, `joblib`, `matplotlib`, and `seaborn`  

### **2. Clone Repository**  
```bash  
git clone https://github.com/yourusername/Smartphone_Anomaly_Infosys_Internship_Oct2024.git  
cd Smartphone_Anomaly_Infosys_Internship_Oct2024  
```  

### **3. Run the Application**  
Install dependencies:  
```bash  
pip install -r requirements.txt  
```  
Run the app locally:  
```bash  
streamlit run app.py  
```  

---

## **How It Works**  

### **Input Features**  
The model was trained using the following smartphone sensor features:  
- **Location and Movement:** Longitude, Latitude, Speed, Distance  
- **Accelerometer Data:** Acc X, Acc Y, Acc Z, Acc Magnitude, Acc Change  
- **Gyroscope Data:** Gyro X, Gyro Y, Gyro Z, Gyro Magnitude, Gyro Change  
- **Derived Metrics:** Speed Change, Heading Change, Net Displacement  
- **Statistical Metrics:** Rolling Acc Mean, Rolling Acc STD, Acc Mean, Gyro STD  

### **Backend**  
- The machine learning model and scaler are serialized using `joblib`.  
- Predictions are made through **Gradient Boosting Classifier**, optimized for anomaly detection.  

### **Frontend**  
- Built using **Streamlit**, ensuring an intuitive and responsive interface.  

---

## **Acknowledgments**  
This project was developed as part of the **Infosys Springboard 5.0 Internship Program** in October 2024. Special thanks to the mentorship team for their guidance and support.  

--- 
