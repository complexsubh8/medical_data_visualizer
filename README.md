# Medical Data Visualizer

This project is part of the freeCodeCamp **Data Analysis with Python** certification.

## Project Overview

The goal of this project is to analyze medical examination data and visualize relationships between cardiovascular disease, body measurements, blood test results, and lifestyle choices using Python.

The project uses:

* Pandas for data analysis
* Matplotlib for visualization
* Seaborn for statistical plotting
* NumPy for numerical operations

## Dataset

The dataset contains information collected during medical examinations, including:

* Age
* Height
* Weight
* Blood pressure
* Cholesterol levels
* Glucose levels
* Smoking habits
* Alcohol consumption
* Physical activity
* Presence of cardiovascular disease

Dataset file:

```text
medical_examination.csv
```

## Features Implemented

### Data Processing

* Added an `overweight` column using BMI calculations
* Normalized cholesterol values
* Normalized glucose values
* Cleaned invalid records from the dataset

### Visualizations

#### Categorical Plot

Shows counts of:

* Cholesterol
* Glucose
* Smoking
* Alcohol consumption
* Physical activity
* Overweight status

for patients with and without cardiovascular disease.

#### Correlation Heat Map

Displays correlations between medical variables after removing incorrect data records.

## Project Structure

```text
medical-data-visualizer/
│
├── medical_examination.csv
├── medical_data_visualizer.py
├── main.py
├── catplot.png
├── heatmap.png
└── README.md
```

## Installation

Install the required libraries:

```bash
pip install pandas matplotlib seaborn numpy
```

## Usage

Run the project:

```bash
python main.py
```

This generates:

```text
catplot.png
heatmap.png
```

## Example Analysis

The project helps identify patterns between:

* Cardiovascular disease and obesity
* Cholesterol levels and heart disease
* Glucose levels and health outcomes
* Lifestyle choices and cardiovascular risk

## Author

Subham Sarkar

## Certification

freeCodeCamp – Data Analysis with Python
