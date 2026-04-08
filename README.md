# 🏥 CSV Agent for Healthcare Analytics

![GitHub stars](https://img.shields.io/github/stars/your-username/your-repo?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/your-repo?style=social)
![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

---

## ✨ Project Overview

This project demonstrates how to build an **AI-powered CSV Agent** for analyzing healthcare datasets using **LangChain + Groq LLM**.

The agent can:

* Answer natural language questions
* Perform data analysis
* Generate insights
* Create visualizations
* Predict patterns (like readmissions)

---

## 🎬 Demo Animation

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExd3k1bWZ5Z3J0c3VqZ3R0b3F6d2Q2d3h0d2R1c3VxZ2F0d3ZqZyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/coxQHKASG60HrHtvkt/giphy.gif" width="600"/>
</p>

---

## 🚀 Features

✔️ Conversational Data Analysis
✔️ Healthcare Insights Extraction
✔️ Automated Visualization
✔️ Predictive Analysis (Readmission Risk)
✔️ Works with Large CSV Files

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas 📊
* LangChain 🧠
* Groq LLM ⚡

---

## ⚙️ Installation

```bash
pip install -U langchain langchain-experimental langchain-groq pandas tabulate
```

---

## 🔑 Setup

```python
import os
import getpass

os.environ["GROQ_API_KEY"] = getpass.getpass("Enter your Groq API key: ")
```

---

## 📂 Dataset

Healthcare dataset includes:

* Patient details
* Diseases
* Departments
* Doctors
* Admission types
* Treatment cost
* Length of stay

---

## 🤖 How It Works

```python
from langchain_groq import ChatGroq
from langchain_experimental.agents import create_csv_agent

agent = create_csv_agent(
    llm=groq_chat,
    path=CSV_PATH,
    verbose=True,
    allow_dangerous_code=True
)
```

---

## 📊 Example Queries

* How many rows and columns are in the dataset?
* What is the gender distribution?
* Which disease has the highest treatment cost?
* Which department generates the most revenue?
* Which doctor handled the most patients?
* What is the average patient stay?

---

## 📈 Visualization Examples

* Department vs Diseases
* Doctor vs Admission Type
* Age vs Days Admitted

---

## 🔮 Advanced Capabilities

* Predict patient readmission risk
* Identify busiest hospital periods
* Generate automated summaries

---

## 📁 Project Structure

```
├── CSV Agent healthcare _csv.ipynb
├── dataset.csv
└── README.md
```

---

## 💡 Use Cases

* Healthcare analytics
* Hospital management insights
* Business intelligence
* Data science projects

---

## 🙌 Contribution

Feel free to fork this repo and improve it 🚀

---

## 📬 Contact

Created by **Aditi Sasankar**
