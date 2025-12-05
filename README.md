# 🏥 Patient Safety Culture Survey — Kajiado County Hospitals

This repository contains all files and data related to the analysis of a **Patient Safety Culture Survey** conducted across hospitals within **Kajiado County, Kenya**. 
The goal of this study was to measure safety-related perceptions among hospital staff and provide actionable insights to support continuous improvement in healthcare service delivery.

## 🎯 Objective of the Study

To understand how healthcare workers perceivekey patient safety dimensions, including::

* Teamwork and collaboration
* Staffing adequacy and workload
* Communication and handover efficiency
* Unit-level operational support
* Shift handovers
* Safety culture & blame climate
* Overall patient safety environment

The results provide a foundation for **policy decisions**, **hospital management strategies**, and **future quality improvement interventions**.

### The analysis aims to answer:

How do staff across different hospitals perceive patient safety?

What are the common views on teamwork, staffing, shift handovers, and safety climate?

Which departments contributed insights, and where are the data gaps?

What strengths and improvement areas can hospital leadership act on?

## 📊 Dataset Description

* **Type:** Primary survey data
* **Format:** Likert-scale responses (Strongly Agree → Strongly Disagree)
* **Participants:** Health workers across multiple departments and units
* **Location:** Kajiado County, Kenya

The dataset records perceptions across various patient safety culture dimensions.

## 🧠 Analytical Approach
* **Data Cleaning**

  * Handling invalid and ambiguous values
  * Structuring tabular data

* **Descriptive Analysis**

  * Frequency tables
  * Percentage distribution

* **Safety Culture Interpretation**

  * Favorability scoring
  * Identifying areas of strength vs. concern

* **Graphical Summaries**

  * Top units represented
  * Likert response behaviors
  * Distribution trends
 
The analysis includes:
* 🔍 **Frequency counts and distributions** (Hospital, Staff Role, Work Unit)
* 📊 **Likert scale summarization** (Mean, Median, Agreement Percentages)
* 📈 **Visualization of safety culture indicators**
* 📚 **Interpretation and insight generation**
* 🧽 **Full data-cleaning workflow**

The findings offer **evidence-based insights** that can support:

* Hospital quality improvement initiatives
* Staff training and development programs
* County-level healthcare policy and resource decisions

All analysis was performed in Python using:

* **Pandas**
* **NumPy**
* **Matplotlib/Seaborn**
* **Jupyter Notebook**

## 📁 Repository Structure

```
├── data/
│   └── input_dataset.xlsx                 # Raw survey dataset collected from hospitals in Kajiado County
│
├── Notebooks/
│   └── Kajiado_Safety_Analysis.ipynb      # Full analysis pipeline:
│                                          #   - Cleaning and preparation
│                                          #   - Likert frequency & percentages
│                                          #   - Favorability scoring
│                                          #   - Insights & interpretations
│
├── outputs/
│   └── charts/                            # Stored graphs/visuals generated from the notebook
│
└── README.md                              # Project documentation and usage guide
```

---

## 🚀 How to Run the Analysis

1. Clone the repository:

```bash
git clone https://github.com/USERNAME/Kajiado-Safety-Culture-Analysis.git
```

2. Open the analysis notebook:

```bash
cd Kajiado-Safety-Culture-Analysis
jupyter notebook
```

Run the notebook sequentially.

---

## 🧾 Key Deliverables

This study provides:

* Evidence-backed insights into hospital safety culture
* Identification of risk areas affecting patient outcomes
* Interpretation of trends based on respondent perceptions
* Structured scoring to support decision-making

---

## 📌 Potential Applications

* Hospital quality improvement planning
* Policy development for patient safety
* County-level healthcare performance evaluation
* Research and academic reference
* Benchmarking across hospitals

---

## ✍️ Author

**Tevin Mark Simiyu**
Data Scientist | Software Engineer | CloudDev | SAP Associate
📧 Email: **[tevinsmark@gmail.com](mailto:tevinsmark@gmail.com)**






