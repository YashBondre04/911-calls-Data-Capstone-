# 911 Calls Capstone Project

This repository contains the code and analysis for a capstone project focused on analyzing 911 call data from Montgomery County, PA. The project utilizes Python, pandas, and data visualization libraries like Matplotlib and Seaborn to explore patterns and trends in emergency calls.

## Project Overview

The goal of this project is to analyze a dataset of 911 calls to identify trends, patterns, and insights that could be useful for understanding emergency service demand and potentially improving response strategies.

## Dataset

The dataset used in this project is from [Kaggle](https://www.kaggle.com/mchirico/montcoalert). It contains the following fields:

*   `lat`: String variable, Latitude
*   `lng`: String variable, Longitude
*   `desc`: String variable, Description of the Emergency Call
*   `zip`: String variable, Zipcode
*   `title`: String variable, Title
*   `timeStamp`: String variable, YYYY-MM-DD HH:MM:SS
*   `twp`: String variable, Township
*   `addr`: String variable, Address
*   `e`: String variable, Dummy variable (always 1)

## Analysis

The analysis in this project includes:

*   **Data Loading and Preparation:** Loading the data into a pandas DataFrame and handling missing values.
*   **Analyzing Call Reasons:** Investigating the distribution and frequency of different types of emergency calls (e.g., Traffic, Fire, EMS).
*   **Time-based Analysis:** Examining how the number and type of calls vary by hour, day of the week, and month.
*   **Geographical Analysis (Implicit):** While not explicitly mapped, the zip code and township data allow for some level of geographical understanding of call distribution.
*   **Visualizations:** Using various plots (countplots, line plots, heatmaps, clustermaps) to visualize the findings.

## Getting Started

### Prerequisites

*   Python 3.x
*   Jupyter Notebook or JupyterLab (recommended for running the notebook)
*   Required Python libraries:
    *   pandas
    *   numpy
    *   matplotlib
    *   seaborn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
