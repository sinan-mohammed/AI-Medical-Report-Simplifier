# 🩺 AI Medical Report Simplifier

Transforming complex medical reports into simple, patient-friendly explanations using AI and NLP.

---

## 📌 Project Overview

Medical reports often contain complex medical terminology that can be difficult for patients to understand.
The **AI Medical Report Simplifier** is an AI-powered tool that converts technical clinical text into simple explanations.

The system uses **Natural Language Processing (NLP)** and **Large Language Models (LLMs)** to analyze medical reports, detect key medical entities, and generate patient-friendly summaries.

---

## 🎯 Objectives

* Simplify complex medical terminology
* Improve patient understanding of clinical reports
* Detect important medical entities (symptoms, diseases, tests)
* Identify critical medical conditions
* Provide clear explanations using AI

---

## ⚙️ Technologies Used

| Technology               | Purpose                   |
| ------------------------ | ------------------------- |
| Python                   | Core programming language |
| HuggingFace Transformers | AI language models        |
| spaCy                    | NLP entity detection      |
| Streamlit                | Web interface             |
| FLAN-T5                  | Text simplification model |

---

## 🏗 System Architecture

```
Medical Report Input
        ↓
Medical Entity Extraction (spaCy)
        ↓
Clinical Concept Identification
        ↓
LLM Simplification Engine (FLAN-T5)
        ↓
Risk Detection Module
        ↓
Patient-Friendly Explanation
        ↓
Streamlit Web Interface
```

---

## 🧠 Features

* AI-powered medical report simplification
* Medical entity detection using NLP
* Risk warning for serious conditions
* Interactive Streamlit web interface
* Patient-friendly explanations

---

## 📥 Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/AI-Medical-Report-Simplifier.git
cd AI-Medical-Report-Simplifier
```

---

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 3️⃣ Download spaCy language model

```
python -m spacy download en_core_web_sm
```

---

### 4️⃣ Run the Streamlit app

```
streamlit run streamlit_app.py
```

Open in browser:

```
http://localhost:8501
```

---

## 📊 Example

### Input Medical Report

```
Patient presents with dyspnea and tachycardia. ECG shows abnormal ST elevation.
```

### Simplified Explanation

```
The patient is experiencing difficulty breathing and a fast heart rate.
Heart monitoring shows unusual patterns that may indicate a heart condition.
The patient should seek medical evaluation.
```

---

## 📁 Project Structure

```
AI_Medical_Report_Simplifier
│
├── medical_report_simplifier.ipynb
├── streamlit_app.py
├── architecture.png
├── sample_reports.txt
├── requirements.txt
└── README.md
```

---

## 🔮 Future Improvements

* Multilingual medical explanations (English, Hindi, Malayalam)
* Medical knowledge retrieval using RAG
* Severity classification (Mild / Moderate / Critical)
* Highlight medical terms with definitions

---

## 📜 License

This project is for **educational and research purposes**.
