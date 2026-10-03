# 📊 Netflix Data Visualization Dashboard

A Data Visualization and Dashboard project developed as part of the **Horizon TechX Internship – Task 4**.

The project analyzes the **Netflix Movies and TV Shows dataset** and transforms the raw data into meaningful visualizations and an interactive dashboard for data-driven exploration and storytelling.

## 🎯 Task Objective

The objective of this task is to convert raw data into clear and informative charts and dashboards using visualization tools such as **Python (Matplotlib/Seaborn) and Power BI**.

The dashboard focuses on understanding Netflix's content library, including content type, genres, countries, ratings, release years, content-added trends, and movie duration.

## 📂 Dataset

The project uses the Netflix Movies and TV Shows dataset containing:

- **8,807 records**
- **12 columns**

Main columns include:

```text
show_id
type
title
director
cast
country
date_added
release_year
rating
duration
listed_in
description
```

The dataset contains information about both **Movies** and **TV Shows** available on Netflix.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI

## 🔄 Data Processing

The data preprocessing workflow includes:

- Data type correction
- Missing-value handling
- Date conversion
- Extraction of year and month from `date_added`
- Movie duration extraction
- TV-show season extraction
- Genre processing
- Country processing
- Creation of processed datasets for visualization

Generated processed files include:

```text
netflix_processed.csv
netflix_genres.csv
netflix_countries.csv
```

## 📊 Dashboard

The Power BI dashboard provides an interactive overview of Netflix content.

### KPI Cards

The dashboard includes key metrics such as:

- Total Titles
- Total Movies
- Total TV Shows
- Average Release Year

### Visualizations

The dashboard analyzes:

- Movies vs TV Shows
- Content added over time
- Top countries by content
- Top genres
- Content ratings
- Release-year distribution
- Movie duration
- Genre distribution by content type

### Interactive Filters

Users can explore the dashboard using filters/slicers such as:

- Type
- Rating
- Country
- Release Year

## 📁 Project Structure

```text
horizontechx_task4-Data-Visualization-Dashboard/
│
├── data/
│   └── netflix.csv
│
├── notebooks/
│   └── Netflix_Dashboard.ipynb
│
├── visualizations/
│   └── charts/
│
├── processed_data/
│   ├── netflix_processed.csv
│   ├── netflix_genres.csv
│   └── netflix_countries.csv
│
├── dashboard/
│   └── Netflix_Dashboard.pbix
│
├── report/
│   └── Netflix_Visualization_Report.pdf
│
├── README.md
└── requirements.txt
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Abhishek-009-Mishra/horizontechx_task4-Data-Visualization-Dashboard.git
cd horizontechx_task4-Data-Visualization-Dashboard
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Netflix_Dashboard.ipynb
```

Run the notebook from top to bottom.

## 📈 Visualization Workflow

```text
Raw Netflix Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Feature Engineering
        ↓
Processed Datasets
        ↓
Python Visualizations
        ↓
Power BI Dashboard
        ↓
Insights & Data Storytelling
```

## 📌 Key Analysis Areas

The project explores:

1. Distribution of Movies and TV Shows
2. Netflix content added over time
3. Popular genres
4. Countries producing Netflix content
5. Content ratings
6. Release-year trends
7. Movie duration patterns
8. Genre distribution across Movies and TV Shows

## 📦 Internship Deliverables

- Cleaned and processed Netflix dataset
- Python/Jupyter Notebook analysis
- Data visualizations
- Interactive Power BI dashboard
- Dashboard/report documentation

## 🔐 Data & Security

No API keys, passwords, or environment secrets are required for this project.

Avoid committing private credentials or other sensitive information to the repository.

## 👨‍💻 Author

**Abhishek Mishra**

B.Tech CSE (AI & ML)  
Vellore Institute of Technology, Bhopal

## 📄 Internship

**Horizon TechX Internship – Task 4: Data Visualization & Dashboard**

---

> This project demonstrates the use of data preprocessing, exploratory visualization, dashboard development, and data storytelling to transform a raw dataset into an interactive analytical solution.
