# 🏏 IPL Data Analysis Using Pandas & PandasAI

This repository contains a complete mini–project on **IPL 2023 player and auction analysis**.
It combines traditional **Pandas-based Exploratory Data Analysis (EDA)** with an AI-augmented
workflow using **PandasAI** (as documented in the included PDF report).

---

## 📂 Project Structure

```text
IPL_Data_Analysis_Using_PandasAI/
├── data/
│   └── ipl_raw_data.csv                 # Raw IPL dataset
├── notebooks/
│   └── IPL_Data_Analysis.ipynb          # Jupyter notebook with code & EDA
├── reports/
│   └── IPL-Data-Analysis-Using-Pandas-AI.pdf   # Project documentation / slides
├── images/
│   └── *.jpg                            # Exported graphs & charts
└── README.md                            # Project documentation (this file)
```

---

## 🎯 Objective

- Perform data cleaning and exploratory analysis on IPL 2023 data  
- Understand player performance, roles, strike rates, economy rates, and match statistics  
- Demonstrate how **AI-powered tools like PandasAI** can simplify querying and visualisation  
- Produce professional visual outputs and a summarized PDF report

---

## 📊 Included Visualizations

The `images/` folder contains plots exported from the notebook, such as:

- Top 10 wicket takers (horizontal bar chart)
- Player role distribution (pie chart)
- Matches played vs batting average (scatter / dot chart)
- Economy rate distribution (box plot)
- Top 10 players by batting average (bar chart)
- Distribution of batting strike rate (histogram / KDE)
- International vs domestic players (donut chart)

These plots are generated from the raw `ipl_raw_data.csv` file using the notebook.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **PandasAI** (for natural-language powered analysis)
- **Jupyter Notebook**

---

## 🚀 How to Run

1. Clone or download this project:
   ```bash
   git clone <your-repo-url>
   cd IPL_Data_Analysis_Using_PandasAI
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn pandasai jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/IPL_Data_Analysis.ipynb
   ```

4. (Optional) Configure **PandasAI** by setting your OpenAI API key inside the notebook
   or as an environment variable before running advanced AI-powered queries.

---

## 📝 Report

A polished presentation-style report is available at:

- `reports/IPL-Data-Analysis-Using-Pandas-AI.pdf`

It explains:
- Why IPL auction and player data matters  
- Advantages and limitations of PandasAI  
- Player valuation insights and team spending patterns  
- Market analysis of unsold players  
- Key takeaways and strategic applications of AI-powered analytics

---

## 👤 Author

**Narendra Bellamkonda**  
MCA Student | Data Analysis & Python Enthusiast  

Feel free to fork this repository, experiment with new visuals,
or extend the analysis with your own questions using PandasAI.
