# 📊 Data Analytics Chatbot

An **AI-powered Data Analytics Chatbot** developed using Python, Streamlit, and Gemini LLM.
This chatbot is designed to help **students learn and apply Data Analytics techniques** by providing real-time insights, visualizations, and support for ML algorithms.

---

## 🚀 Objectives

- **Interactive Learning**: Real-time interaction with datasets, code suggestions, and visualizations.
- **ML Support**: Apply basic ML models (supervised & unsupervised) and evaluate them.
- **Visualization**: Generate detailed plots for quick dataset understanding.
- **Code Snippets & Explanations**: Easily understand EDA, statistical analysis, and ML with code & output.
- **NLP Assistance**: Gemini integration helps with complex queries using GPT-style responses.

---

## 🛠️ Software Requirements

> ❗ Jupyter Notebook is **not suitable** due to integration limitations.  
> ✅ Preferred IDEs: **VS Code** / **PyCharm**

---

## 🧰 Modules Used

### 🔙 Backend
- `python`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `statistics`
- `requests`
- `scikit-learn`
- `plotly`
- `re` (Regex for query parsing)

### 🔜 Frontend
- `streamlit`
- Gemini API (for LLM-based query support)

---

## 🧩 Key Features

- **📁 Data Upload**: Upload CSV files and preview datasets instantly.
- **📊 EDA**: Perform Exploratory Data Analysis using built-in visualizations and insights.
- **📐 Statistical Analysis**: Fetch descriptive and inferential statistics with ease.
- **🤖 ML Assistance**: Train basic models and evaluate them using accuracy, classification reports, etc.
- **💬 Gemini LLM Integration**: Gemini 1.5 Flash provides human-like responses for advanced queries.
- **🧠 Query Parsing**: Regex used to identify and process structured queries automatically.

---

## 🔮 Future Improvements

- ✅ Add support for Excel, JSON, and other file types.
- 🧠 Support advanced ML models (e.g., Random Forest, SVM).
- 🔍 Implement advanced NLP capabilities for complex queries.
- 📈 Interactive visual dashboards using advanced libraries.

---

## 🔁 Project Workflow

```text
User Interaction (Streamlit Interface)
        ↓
Query Parsing (Regex / Keywords)
        ↓
LLM Invocation (if complex → Gemini API)
        ↓
Task Execution (EDA / ML / Stats using Python libs)
        ↓
Response Display (Visuals + Code via Streamlit)
