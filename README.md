# 🎬 CineStream Content Analytics Dashboard

##  Project Overview

The CineStream Content Analytics Dashboard is an interactive web application developed using Streamlit. The dashboard analyzes the CineStream content catalog and provides insights into genres, languages, revenue, IMDb ratings, production costs, return on investment (ROI), and content quality.

The project helps users explore streaming content through interactive filters, charts, and key performance indicators (KPIs).

---

##  Objectives

- Analyze the CineStream dataset.
- Perform data cleaning and preprocessing.
- Visualize business insights using interactive charts.
- Identify profitable genres and content.
- Analyze IMDb ratings and audience engagement.
- Build an interactive Streamlit dashboard.

---

##  Dataset

**Dataset Name:** CineStream_Catalog.csv

The dataset contains information about:

- Title
- Genre
- Language
- Country
- Content Type
- Release Year
- Runtime
- IMDb Score
- Views
- Revenue
- Production Cost
- Age Rating

---

## Technologies Used

- Python
- Pandas
- NumPy
- Streamlit
- Plotly
- Matplotlib

---

## 📊 Dashboard Features

### Overview
- KPI Cards
- Total Views
- Total Revenue
- Average IMDb Score

### Genre & Language Analysis
- Top Genres by Views
- Language Distribution
- Interactive Treemap

### Revenue Analysis
- Revenue vs Production Cost
- ROI by Genre
- Profitability Analysis

### Quality Analysis
- IMDb Score Distribution
- IMDb Score vs Views
- Low Rated Titles

### Filters
- Genre
- Language
- Content Type
- IMDb Score
- Runtime
- Release Year

---

##  Project Structure

```
CineStream/
│
├── data/
│   └── CineStream_Catalog.csv
│
├── notebooks/
│   └── m1_explore.ipynb
│
├── outputs/
│   ├── cleaned_cinestream.csv
│   └── m7_report.pdf
│
├── cinestream_app.py
├── requirements.txt
└── README.md
```

---

## How to Run

1. Clone the repository.

```
git clone <repository-link>
```

2. Install required libraries.

```
pip install -r requirements.txt
```

3. Run the Streamlit app.

```
streamlit run cinestream_app.py
```

---

##  Dashboard Preview

(Add dashboard screenshots here after deployment.)

---

##  Key Insights

- Thriller is among the highest viewed genres.
- Romance shows a strong average ROI.
- Most content has IMDb ratings around 7.
- Interactive filters make data exploration easier.
- Revenue and production cost analysis help identify profitable content.

---

##  Developed By

**Name:** Jafla  
**Course:** BCA AI & Data Science  
**Semester:** 4

---

##  License

This project was developed for academic purposes.