# ⚛️ AI-Based Analysis of Economic Sanctions Using Policy Text

## 📌 Project Overview
This project focuses on analyzing **economic sanctions** using **official policy text data** and applying **Natural Language Processing (NLP)** and **Deep Learning (DL)** techniques to automatically classify sanctions based on their **severity and characteristics**.

Instead of using news sentiment, this project uses **authoritative sanctions descriptions** published by official institutions (such as the European Council) to build an event-based textual dataset for AI-driven analysis.

---

## 🎯 Objectives
- To collect and structure official sanctions policy text data
- To perform text preprocessing and feature extraction using NLP
- To classify sanctions based on **severity levels** (High / Medium / Low)
- To analyze the **evolution of sanctions over time**
- To demonstrate how deep learning can be applied to policy documents

---

## 🌍 Countries Covered
- **Russia**
- **Iran**

*(Dataset is structured to allow future expansion to other countries.)*

---

## 📂 Dataset Description
The dataset is manually curated from **official sanctions timelines and policy documents**.

### Dataset Columns
| Column Name | Description |
|------------|-------------|
| `news_id` | Unique identifier for each sanction event |
| `date` | Date of the sanction decision |
| `country` | Country targeted by the sanction |
| `source` | Issuing authority (e.g., European Council) |
| `headline` | Title of the sanction decision |
| `summary` | Short description of the sanction |
| `clean_text` | Preprocessed text used for NLP |
| `impact_label` | Severity label (High / Medium / Low) |

---

## 🧠 Methodology

### 1️⃣ Data Collection
- Sanction events were collected from **official policy sources**
- Only **sanction-related decisions** were included (not daily news)
- Data is **event-based**, not time-series based

### 2️⃣ Text Preprocessing
- Lowercasing
- Removal of punctuation and symbols
- Combining headline and summary into a single text field

### 3️⃣ Labeling Strategy
Sanctions are labeled using rule-based classification:

| Severity | Description |
|--------|-------------|
| High | Sector-wide, financial, trade, or energy sanctions |
| Medium | Extensions or expansions of existing sanctions |
| Low | Discussions, warnings, or diplomatic statements |

---

## 🤖 Model Approach
- Text tokenization and embedding
- Deep Learning models such as:
  - LSTM
  - GRU
  - (Optional) Transformer-based models like BERT
- Output: Sanction severity classification

---

## 📊 Analysis & Outcomes
- Identification of sanction escalation patterns
- Comparison of sanction intensity over time
- Automated classification of sanction severity
- Demonstration of NLP-based policy analysis

---

## 🛠️ Tools & Technologies
- Python
- Google Sheets (data preparation)
- NLP preprocessing libraries
- TensorFlow / Keras / PyTorch (for DL models)
- GitHub (version control)

---

## 🚀 Future Enhancements
- Add economic indicators (GDP, trade data) for impact correlation
- Extend dataset to include Venezuela and other countries
- Implement sequence-based models for sanction trend forecasting
- Add visualization dashboards

---

## 📝 Disclaimer
This project is for **academic and research purposes only**.  
All data is collected from **publicly available official sources**.

---

## 📧 Author
**Adithya**  
B.Tech – AI & Data Science  
