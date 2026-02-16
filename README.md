# Formula 1 Data Analysis with Plotly 🏎️

This repository contains an exploratory data analysis (EDA) and visualization project focused on the rich history of the Formula 1 World Championship. The project leverages historical F1 data to uncover insights into team dominance, driver performance, and the correlation between qualifying and race pace in the modern era.

## 📊 Project Overview

This project was developed to visualize complex F1 data using Python and Plotly. It processes multiple datasets detailing races, results, drivers, constructors, circuits, and race statuses from 1950 onwards to generate interactive, web-ready graphs.

**Key Visualizations:**
* **Hierarchy of Dominance:** An interactive Sunburst chart illustrating the distribution of race wins by constructors and their respective drivers, filtered for top-performing teams (10+ wins).
* **Qualifying vs. Race Pace (Hybrid Era):** A scatter plot analyzing the correlation between starting grid position and final race position from 2014 to 2023. It features an Ordinary Least Squares (OLS) trendline and categorizes results by completion status (Finished vs. DNF/Issue).

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3
* **Data Manipulation:** `pandas`
* **Visualization:** `plotly.express`, `plotly.graph_objects`, `plotly.io` (customized with the `plotly_dark` template)
* **Data Sourcing:** `kagglehub`

## 📂 Dataset

The data is sourced directly from Kaggle using the `kagglehub` library.
* **Dataset:** [Formula 1 World Championship (1950 - 2020)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
* **Core Files Processed:** * `races.csv`
  * `results.csv`
  * `drivers.csv`
  * `constructors.csv`
  * `circuits.csv`
  * `status.csv`

## 🚀 Getting Started

### Prerequisites
Ensure you have Python 3 installed. You will need to install the following dependencies:

```bash
pip install pandas plotly kagglehub
