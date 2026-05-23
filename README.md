# Netflix Data Analysis using Seaborn

## Project Overview

This project focuses on analyzing Netflix Movies and TV Shows data using Python libraries such as Pandas, Seaborn, and Matplotlib. The goal of this project is to perform Exploratory Data Analysis (EDA) and visualize trends related to Netflix content.

---

## Objectives

* Analyze Netflix Movies and TV Shows
* Explore content distribution and release trends
* Visualize ratings and country-wise content production.
* Perform data cleaning and statistical analysis
* Create meaningful visualizations using Seaborn

---

## Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Jupyter Notebook

---

## Dataset

The dataset contains information about Netflix titles including:

* Title
* Type
* Director
* Cast
* Country
* Release Year
* Rating
* Duration
* Genre

Dataset File:

```plaintext
netflix_titles.csv
```

---

## Visualizations Included

* Movies vs TV Shows Countplot
* Netflix Ratings Distribution
* Release Year Histogram
* Top Countries Barplot
* Correlation Heatmap

---

## Project Structure

```plaintext
Netflix-Seaborn-Analysis/
│
├── charts/
│   ├── correlation-heatmap.png
│   ├── movies-vs-tvshows_countplot.png
│   ├── netflix-releases_histogram.png
│   └── top-countries_barplot.png
│
├── data/
│   └── netflix_titles.csv
│
├── netflix_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## Key Insights

* Netflix contains more Movies than TV Shows
* Content releases increased significantly after 2015
* Some countries dominate Netflix content production
* TV-MA and TV-14 are among the most common ratings

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/srinidhxi/netflix-seaborn-analysis.git
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run:

```plaintext
netflix_analysis.ipynb
```

---

## Future Improvements

* Build interactive dashboards using Streamlit
* Add more advanced visualizations
* Perform genre-based analysis
* Deploy project online

---

## Author

MSRI NIDHI
