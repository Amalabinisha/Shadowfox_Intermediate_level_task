# Shadowfox_Intermediate_level_task
# Air Quality Analysis using Python

## Project Overview

This project analyzes air quality data to identify pollution trends, seasonal variations, and public health risk levels. It was completed as part of the **Intermediate Level Data Science Internship** at **ShadowFox**.

The project applies data preprocessing, feature engineering, statistical analysis, and data visualization techniques using Python.

---

## Objectives

- Analyze major air pollutants
- Study seasonal variations in air quality
- Categorize pollution levels based on PM2.5 concentration
- Visualize pollution trends using professional graphs
- Generate meaningful insights from air quality data

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset

**Dataset:** Delhi Air Quality Dataset

The program automatically creates a synthetic dataset if the original dataset (`delhiaqi.csv`) is unavailable, ensuring uninterrupted execution.

---

## Features

- Data loading and preprocessing
- Date and time feature extraction
- Seasonal classification
- Public health risk categorization
- Statistical summary of pollutants
- Correlation analysis
- Automatic output folder creation
- High-quality visualization export

---

## Project Workflow

1. Dataset Loading
2. Data Preprocessing
3. Feature Engineering
4. Health Risk Classification
5. Statistical Analysis
6. Data Visualization
7. Correlation Analysis
8. Output Generation

---

## Visualizations Generated

### RQ1: Pollutant Analysis
- PM2.5 Distribution
- National Air Quality Standard Comparison

### RQ2: Seasonal Analysis
- Seasonal PM2.5 Box Plot

### RQ3: Daily Pollution Pattern
- Hourly PM2.5 Trend
- Thermal Inversion and Dispersion Analysis

---

## Project Structure

```text
Air_Quality_Analysis/
│
├── air_quality_analysis.py
├── delhiaqi.csv
├── README.md
│
└── output_plots/
    ├── rq1_pollutant_dominance.png
    ├── rq2_seasonal_variance.png
    └── rq3_geographical_traps.png
```

---

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Run the Project

```bash
python air_quality_analysis.py
```

---

## Output

After execution, all generated graphs are saved inside:

```text
output_plots/
├── rq1_pollutant_dominance.png
├── rq2_seasonal_variance.png
└── rq3_geographical_traps.png
```

---

## Learning Outcomes

- Data preprocessing using Pandas
- Feature engineering
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Air quality monitoring
- Public health risk assessment
- Data visualization using Matplotlib and Seaborn

---

## Internship

**Organization:** ShadowFox

**Level:** Intermediate Level Data Science Internship

**Project:** Air Quality Analysis using Python
