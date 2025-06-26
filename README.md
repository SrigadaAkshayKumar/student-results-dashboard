# Student Results Dashboard

A **Streamlit-based web application** to analyze and visualize student results data for the **Data Science Department**. This dashboard provides section-wise and subject-wise performance insights, pass/fail statistics, top performers, and interactive charts — all containerized using **Docker** for smooth deployment.

---

## Features

- **Batch, Year, and Semester Navigation**
- **Section-wise Subject Analytics**: Pass/Fail counts and percentages
- **Pie and Bar Charts**: Result distribution and performance breakdown
- **Top Performers**: Section-wise and overall toppers
- **Pass/Fail Summary Tables**: Interactive and export-ready
- **Dockerized**: Fully containerized for easy deployment on Render or any cloud platform

---

## Project Structure

student-results-dashboard/
│
├── app.py # Main Streamlit application
├── Dockerfile # Docker configuration
├── requirements.txt # Python dependencies
├── render.yaml # Render deployment config
├── utils/
│ └── loader.py # Optional helper scripts (e.g., data loading)
└── data/
└── 3rd_year/
├── sem1.csv
└── sem2.csv

---

## Installation (Local)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/student-results-dashboard.git
cd student-results-dashboard
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the App

```bash
streamlit run app.py
```

## Acknowledgements

This project is built as part of the mini project for the Data Science Department to improve transparency, performance tracking, and decision-making based on academic performance data.
