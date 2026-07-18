# 🏥 Healthcare Report Summarization & Medical Entity Extraction

An end-to-end NLP pipeline that transforms unstructured clinical reports into structured medical insights. The system extracts biomedical entities such as diseases, medications, symptoms, and procedures while generating concise AI-powered summaries using transformer-based models.

---

## 📌 Overview

Healthcare reports often contain large amounts of unstructured text that is difficult to analyze efficiently. This project automates the extraction of important medical information and produces concise summaries, enabling faster review and improved healthcare data analysis.

---

## ✨ Features

- Extracts biomedical entities from clinical reports
- Identifies:
  - Diseases
  - Medications
  - Symptoms
  - Procedures
- Generates concise AI-powered summaries
- Produces structured JSON outputs
- Confidence-based filtering of extracted entities
- Handles unstructured healthcare documents

---

## 🛠 Tech Stack

- Python
- Hugging Face Transformers
- BART
- Biomedical Named Entity Recognition (NER)
- Pandas
- JSON

---

## 📂 Project Workflow

Clinical Report
↓
Text Preprocessing
↓
Biomedical NER
↓
Medical Entity Extraction
↓
Transformer-based Summarization
↓
Structured JSON Output

---

## 📊 Sample Output

### Extracted Medical Entities

```json
{
  "Disease": ["Hypertension"],
  "Medication": ["Amlodipine"],
  "Symptom": ["Chest Pain"],
  "Procedure": ["ECG"]
}
```

### Generated Summary

> Patient diagnosed with hypertension presenting with chest pain. Prescribed Amlodipine and advised ECG evaluation.

---

## 📁 Repository Structure

```
Healthcare-Report-Summarization-Medical-Entity-Extraction/
│
├── healthcare_report_summarization.ipynb
├── README.md
├── requirements.txt
├── sample_output.json
└── sample_reports/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/n4vaneeth/Healthcare-Report-Summarization-Medical-Entity-Extraction.git
```

Move into the project directory

```bash
cd Healthcare-Report-Summarization-Medical-Entity-Extraction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Open the notebook

```bash
jupyter notebook healthcare_report_summarization.ipynb
```

or upload the notebook directly to Google Colab.

Run all cells to:
- Load the clinical report
- Extract biomedical entities
- Generate summaries
- Export structured JSON results

---

## 📈 Applications

- Clinical Decision Support
- Electronic Health Records (EHR)
- Medical Document Analysis
- Healthcare Analytics
- Biomedical Research
- Hospital Information Systems

---

## 📚 Future Improvements

- Multi-document summarization
- PDF report ingestion
- Interactive web interface
- Support for multiple languages
- Integration with electronic health record systems
- Real-time API deployment

---

## 👨‍💻 Author

**Navaneeth S**

- LinkedIn: https://www.linkedin.com/in/navaneeth-s21
- GitHub: https://github.com/n4vaneeth

---

⭐ If you found this project useful, consider giving it a star!
