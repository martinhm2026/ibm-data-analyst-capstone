# Technology Trends Analysis

## IBM Data Analyst Capstone Project

An end-to-end data analysis project exploring current and emerging
technology trends through developer survey data, job postings, and
publicly available web data.

This project was completed as part of the
**IBM Data Analyst Professional Certificate**.

## Project Overview

The technology landscape evolves rapidly, making it important for
professionals and organizations to understand which programming
languages, databases, cloud platforms, and development tools are
currently used and which are expected to grow in the future.

This project analyzes technology adoption and developer demographics
using multiple data sources. The analysis combines data collection,
data cleaning, exploratory data analysis, visualization, and dashboard
development to identify relevant trends in the technology industry.

## Business Questions

The project aims to answer the following questions:

- Which programming languages are most widely used?
- Which programming languages are developers interested in learning?
- Which databases are currently the most popular?
- Which databases show the strongest future demand?
- Which technologies are most relevant in the job market?
- What are the main demographic characteristics of survey respondents?
- How do current technology usage and future preferences compare?

## Data Sources

The analysis uses three main data sources:

1. **Stack Overflow Developer Survey 2024**  
   Used to analyze developer demographics, current technology usage,
   and future technology preferences.

2. **Job postings data obtained through an API**  
   Used to explore the demand for technology-related skills across
   selected locations.

3. **Publicly available web data**  
   Collected through web scraping to complement the analysis of
   programming languages and technology trends.

## Methodology

The project followed these main stages:

1. Data collection from CSV files, APIs, and web pages.
2. Data inspection and quality assessment.
3. Identification and removal of duplicate records.
4. Detection and treatment of missing values.
5. Data type and categorical variable standardization.
6. Analysis and treatment of outliers.
7. Exploratory data analysis.
8. Data visualization.
9. Interactive dashboard development.
10. Interpretation and communication of findings.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Requests
- Beautiful Soup
- Jupyter Notebook
- Looker Studio

## Key Findings

- JavaScript, Python, and SQL are among the most widely used
  programming languages.
- These languages also show strong future interest among developers,
  suggesting continued relevance.
- PostgreSQL leads both current database usage and future database
  preferences.
- Relational databases remain dominant, while MongoDB maintains a
  significant presence among NoSQL technologies.
- Python, SQL, PostgreSQL, and cloud platforms appear consistently
  across current and future technology trends.
- Survey respondents represent a global developer community with
  diverse educational backgrounds and professional experience.

## Dashboard

The interactive dashboard is organized into three sections:

- **Current Technology Usage**
- **Future Technology Trends**
- **Developer Demographics**

> A dashboard preview will be added to this section.

## Repository Structure

```text
ibm-data-analyst-capstone/
├── notebooks/
│   ├── 01_data_collection/
│   │   ├── Collecting Job Data Using APIs.ipynb
│   │   ├── Web-Scraping-Lab.ipynb
│   │   └── README.md
│   ├── 02_data_wrangling/
│   │   ├── 01_finding_duplicates.ipynb
│   │   ├── 02_removing_duplicates.ipynb
│   │   ├── 03_finding_missing_values.ipynb
│   │   ├── 04_imputing_missing_values.ipynb
│   │   ├── 05_normalizing_data.ipynb
│   │   ├── 06_complete_data_wrangling.ipynb
│   │   └── README.md
│   ├── 03_exploratory_data_analysis/
│   │   ├── 01_exploratory_data_analysis.ipynb
│   │   ├── 02_data_distribution.ipynb
│   │   ├── 03_outlier_analysis.ipynb
│   │   ├── 04_correlation_analysis.ipynb
│   │   └── README.md
│   └── 04_data_visualization/
│       ├── 01_data_visualization.ipynb
│       ├── 02_histograms.ipynb
│       ├── 03_box_plots.ipynb
│       ├── 04_scatter_plots.ipynb
│       ├── 05_bubble_plots.ipynb
│       ├── 06_pie_charts.ipynb
│       ├── 07_stacked_charts.ipynb
│       ├── 08_line_charts.ipynb
│       ├── 09_bar_charts.ipynb
│       └── README.md
├── reports/
│   ├── technology-trends-presentation.pdf
│   └── README.md
└── README.md
```
