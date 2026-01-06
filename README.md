# 📊 Data Insights.AI

**Natural language data analysis and visualization using Streamlit and GPT-4**

Data Insights.AI is an interactive data exploration tool that lets users analyze CSV datasets using plain English, without writing code.

## 🎯 Overview

Data analysis often requires technical skills that slow down exploration and decision-making. Data Insights.AI removes that friction by allowing users to upload CSV files and ask questions in natural language. The system uses GPT-4 to generate Python analysis code, executes it safely within a Streamlit environment, and returns clear insights and visualizations in real time.

## ✨ Key Highlights

* Ask analytical questions in plain English and receive immediate, code-backed answers
* Automatically generate charts and visual summaries from raw CSV data
* Execute AI-generated Python code securely within the application
* Preview datasets with schema, statistics, and sample rows instantly
* Export the full analysis and conversation as a shareable HTML report
* Keep data local with no persistent storage of uploaded files

## 🧩 Features

| Component                 | Description                                           | Status   |
| ------------------------- | ----------------------------------------------------- | -------- |
| CSV Upload                | Upload and preview structured datasets                | Complete |
| Dataset Profiling         | Automatic schema, statistics, and sample generation   | Complete |
| Natural Language Querying | Ask analytical questions in plain English             | Complete |
| Code Generation           | GPT-4 generates Python analysis logic                 | Complete |
| Visualization Engine      | Auto-generated charts using Python plotting libraries | Complete |
| Execution Sandbox         | Secure execution of generated Python code             | Complete |
| Report Export             | Download full analysis as HTML                        | Complete |

## 🛠️ Methodology

### 1. Data Collection

* User uploads a CSV file through the Streamlit interface
* File is parsed locally using Pandas

### 2. Exploratory Analysis

* Dataset dimensions, column types, and summary statistics are generated
* Sample rows are displayed for quick inspection

### 3. Core Modeling and Logic

* User submits a natural-language question
* GPT-4 translates the request into executable Python code
* Code includes analysis logic and visualization instructions

### 4. Validation and Evaluation

* Generated code is executed in a controlled environment
* Errors are captured and handled gracefully
* Outputs are rendered as tables or charts in real time

## 📈 Key Results

### Performance Outcomes

* Enables non-technical users to perform meaningful data analysis
* Reduces time from data upload to insight from minutes to seconds
* Eliminates the need for manual scripting during early exploration

### Business and Real-World Insights

* Accelerates exploratory analysis for analysts and product teams
* Supports faster hypothesis testing and decision-making
* Lowers the technical barrier to working with structured data

## 🧰 Technologies

### Tools

| Technology           | Purpose                                            |
| -------------------- | -------------------------------------------------- |
| Streamlit            | Interactive web interface                          |
| OpenAI GPT-4         | Natural language understanding and code generation |
| Python               | Data processing and execution runtime              |
| Pandas               | Data manipulation and analysis                     |
| Matplotlib / Seaborn | Data visualization                                 |

### Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import streamlit as st
from openai import OpenAI
```

---

## 🧠 Skills Demonstrated

* Natural language interface design for data analysis
* Secure execution of dynamically generated code
* Data exploration and visualization workflows
* Prompt-driven analytics and AI-assisted tooling
* Streamlit application development
* Translating user intent into analytical logic

## 🚀 Getting Started

### Prerequisites

* Python 3.9 or higher
* OpenAI API key

### Usage

```bash
git clone https://github.com/<your-username>/data-insights-ai.git
cd data-insights-ai
pip install -r requirements.txt
streamlit run app.py
```
