# COVID-19 Global Data Analysis Using Python

## Project Overview

This project performs exploratory data analysis on the WHO COVID-19 Global Daily Data using Python and Jupyter Notebook.

The analysis covers global trends, country-level comparisons, WHO regional analysis, India-specific trends, time-series smoothing, reported case fatality ratio, and the relationship between reported cases and deaths.

## Dataset

**Source:** World Health Organization (WHO) COVID-19 Dashboard  
**Official data page:** https://data.who.int/dashboards/covid19/data

The submitted CSV file is:

`WHO-COVID-19-global-daily-data.csv`

Dataset shape in this project: **583,440 rows × 8 columns**

Date range: **2020-01-04 to 2026-08-30**

Countries/areas represented: **240**

WHO regions represented: **7**

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Objectives

- Perform data cleaning and quality checks.
- Analyze global COVID-19 reported cases and deaths.
- Identify daily and monthly trends.
- Compare countries by reported cases and deaths.
- Compare WHO regions.
- Analyze India's reported COVID-19 trend.
- Calculate a 7-day moving average.
- Calculate a descriptive reported case fatality ratio.
- Analyze the relationship between reported cases and deaths.

## Project Files

| File | Description |
|---|---|
| `YourName_COVID19_Data_Analysis.ipynb` | Complete Jupyter Notebook project |
| `requirements.txt` | Python dependencies |
| `YourName_COVID19_ProjectReport.docx` | Project documentation/report |
| `README.md` | Project overview and setup instructions |
| `WHO-COVID-19-global-daily-data.csv` | Dataset used by the notebook |

## Setup Instructions

### 1. Install Python

Install Python 3.x and Jupyter Notebook.

### 2. Install dependencies

Open Command Prompt / Terminal in the project folder and run:

```bash
pip install -r requirements.txt
```

### 3. Place the dataset

Keep `WHO-COVID-19-global-daily-data.csv` in the same folder as the notebook.

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

`YourName_COVID19_Data_Analysis.ipynb`

### 5. Run the notebook

Run the cells from top to bottom.

## Important Data Interpretation Note

WHO states that COVID-19 data are subject to continuous verification and may change because of retrospective corrections, differences in case detection, case definitions, testing, reporting practices, and reporting frequency. Some countries changed from daily to weekly reporting.

Therefore, this project describes **reported COVID-19 surveillance data**. It should not be interpreted as an exact measurement of all infections or deaths.

## Key Verified Dataset Summary

- Total reported cases obtained by summing `New_cases`: **779,366,737**
- Total reported deaths obtained by summing `New_deaths`: **7,116,554**
- India reported cases obtained by summing `New_cases`: **45,056,221**
- India reported deaths obtained by summing `New_deaths`: **533,849**

## Reproducibility

The notebook calculates all metrics from the CSV at runtime rather than hard-coding analytical results.

## Author

**Joyeeprita Das**
