# 📱 Hybrid ML-Based Multilingual SMS Scam Detection

## 📌 Project Details

- **Project Type:** Research-Based Machine Learning Project  
- **Domain:** Cybersecurity / NLP  
- **Team Members:**  
  - Monalika (2210990582)  
  - Payal Dhiman (2210990647)  
  - Prachi Malik (2210990661)  

---

## 🚀 Overview
This project focuses on detecting SMS-based scams, especially in **Hinglish (Hindi + English mixed language)**, which is commonly used in India. Traditional spam detection systems fail to identify such messages due to informal structure and code-mixing.

To solve this, we developed a **Hybrid Machine Learning + Deep Learning model** using:
- **TF-IDF** → for keyword-based feature extraction  
- **LSTM** → for contextual understanding  

The model uses a **Late Fusion approach** to combine both techniques and classify SMS messages into **12 scam categories**.

---

## 🎯 Features
- Detects **Hinglish SMS scams**
- Classifies into **12 categories** (not just spam/ham)
- Uses **Hybrid ML + DL model**
- Achieves **92.47% accuracy**
- Handles **real-world informal text**

---

## 🧠 Tech Stack

### 👨‍💻 Programming Language
- Python

### 📚 Libraries
- NumPy  
- Pandas  
- Scikit-learn  
- TensorFlow / Keras  

### ⚙️ Tools
- Google Colab  
- Jupyter Notebook  

---

## 🏗️ Project Structure
📂 SMS-Scam-Detection
│── 📂 IPR_Submission_Proof
│── 📂 Report_and_PPT
│── 📂 Source_Code
│── 📄 README.md

---

## ⚙️ How It Works

1. User inputs an SMS message  
2. Text is preprocessed (cleaning, tokenization)  
3. TF-IDF extracts important keywords  
4. LSTM analyzes sequence and context  
5. Outputs are combined using Late Fusion  
6. Final classification into 12 categories  

---

## 📊 Results

- Accuracy: **92.47%**  
- Precision: **0.93**  
- Recall: **0.92**  
- F1 Score: **0.93**  

✔ Hybrid model outperforms individual ML and DL models  

---

## 🧪 Sample Predictions

| Input Message | Prediction |
|--------------|-----------|
| Aapka KYC pending hai | Banking Scam |
| OTP share karein aur reward paayein | OTP Scam |
| Kal class hai | Conversation |

---

## 📁 Files Included

- 📂 **Report_and_PPT/** → Project report + presentation  
- 📂 **Source_Code/** → Model implementation  
- 📂 **IPR_Submission_Proof/** → Supporting documents  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
```
2.Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the project:
```bash
python main.py
```

🙏 Acknowledgement
We thank the faculty of Chitkara University for their guidance and support throughout this project.





Current Status:In Progress
