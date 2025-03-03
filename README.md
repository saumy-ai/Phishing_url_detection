# Phishing URL Detection using Machine Learning

## Project Overview
This project aims to detect **phishing URLs** using machine learning techniques. It extracts **22 lexical features** from raw URLs and applies various machine learning models to classify URLs as **malicious or benign**. The best-performing model, **Random Forest**, achieved an accuracy of **96.6%**.

## Features
- **Feature Extraction**: Extracting 22 lexical features from URLs.
- **Machine Learning Models**:
  - **XGBoost**
  - **LightGBM**
  - **Random Forest** (Best Model with **96.6% Accuracy**)
- **Feature Importance Analysis**: Identifying key attributes contributing to phishing detection.
- **Prediction System**: Classifies URLs as phishing or legitimate.

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Processing)
- **Scikit-Learn, XGBoost, LightGBM** (Machine Learning)
- **Matplotlib, Seaborn** (Data Visualization)
- **Flask/Django** (For Web Interface, if applicable)

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/phishing-url-detection.git
   cd phishing-url-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application (if applicable):
   ```sh
   python app.py
   ```

## Dataset
The dataset consists of URLs labeled as **phishing** or **legitimate**. Features extracted include:
- **URL Length**
- **Number of Special Characters**
- **Presence of HTTP/HTTPS**
- **Subdomain Count**
- **Entropy of URL String**

## Model Performance
The **Random Forest** model achieved an accuracy of **96.6%**, outperforming other models.

## Future Enhancements
- Integration of **deep learning models**.
- Deployment as a **browser extension or web service**.
- Real-time URL scanning using external APIs.
- Addition of **network-based features** for improved detection.

## Contribution
Feel free to contribute by submitting pull requests. For major changes, open an issue to discuss proposed modifications.



---
**Author:** [saumya]  
**Email:** [saumyav395@gmail.com]


