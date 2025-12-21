# 🛡️ Malicious URL Detection using Machine Learning

This project detects whether a given URL is **malicious** or **benign** using **Machine Learning** techniques.  
It includes **Exploratory Data Analysis (EDA)**, **feature engineering**, and a **Random Forest Classifier** implemented in a Jupyter Notebook.

---

## 📌 Project Overview

Malicious URLs are commonly used in:
- Phishing attacks  
- Malware distribution  
- Credential theft  
- Financial fraud  

This project analyzes URL patterns and textual features to classify URLs accurately.

## 🔍 Example URLs and Classification (Benign vs Malicious)

| URL | Classification | Reason |
|----|----|----|
| www.google.com | Benign | Official and trusted Google domain |
| www.google.inn | Malicious | Fake domain using extra character (`.inn`) |
| www.netfIix.com | Malicious | Uses capital **I** instead of lowercase **l** (look-alike attack) |
| www.g00gle.com | Malicious | Uses zero `0` instead of letter `o` |
| http://www.abcd.com | Malicious | Invalid protocol format (missing `https`) |

> ⚠️ These malicious URLs are examples of **phishing or spoofing attacks**, where attackers create look-alike domains to trick users.



---

## 🚀 How to Clone the Repository

```bash
git clone https://github.com/doondi30/Malicious-URL-Detection.git
cd Malicious-URL-Detection
```

---

## Links 📌

- Project Repository: [Click Here](https://github.com/doondi30/Malicious-URL-Detection)
- Let's Connect: [LinkedIn](https://www.linkedin.com/in/doondi)




