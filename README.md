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

[View the interactive dashboard](https://datastudio.google.com/reporting/ffcfd000-33ba-4712-8063-d9416b5d3f0d)

> A dashboard preview will be added to this section.

## Repository Structure

```text
ibm-data-analyst-capstone/
├── data/
├── notebooks/
├── dashboard/
├── images/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
