# Intrusion-Detection-System for network traffic
This project detects cybersecurity threats in real-time using Machine Learning. It preprocesses network traffic data, selects important features using Recursive Feature Elimination (RFE), and trains models like Decision Tree, Random Forest, and Gaussian Naïve Bayes to identify intrusions with high accuracy.

## Features
- Monitors network traffic for malicious activities
- Uses signature-based & anomaly-based detection
- Implements feature selection (RFE) for optimization
- Trains Decision Tree, Random Forest, and GaussianNB models
- Achieves high accuracy (95.6%) with low false positive rate

## Tech Stack
- Languages: Python
- Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- Techniques: Machine Learning, Feature Engineering, Data Preprocessing

## Dataset
- Source: UNSW_NB15 Dataset
- Size: 257,673 records (Train: 175,341, Test: 82,332)
- Labels: "Benign" (Normal traffic) & "Attack" (Malicious traffic)

## Installation & Setup  
- Clone the repository: 
   ```bash
   git clone https://github.com/riya1220/IDS-Project.git  
   cd IDS-Project
   ```
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- Run the project:
  ```bash
  python main.py
  ```


## Results
- Accuracy: 95.6%
- Best Model: Random Forest + RFE
