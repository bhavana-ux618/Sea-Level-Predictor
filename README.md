# Sea Level Predictor

## Overview

This project is part of the freeCodeCamp Data Analysis with Python Certification. The objective is to analyze historical sea level data and predict future sea level rise through the year 2050 using linear regression.

Using data provided by the U.S. Environmental Protection Agency (EPA), this project visualizes long-term sea level trends and compares predictions based on the entire dataset versus more recent data.

## Features

* Imports and analyzes historical global sea level data.
* Creates a scatter plot showing sea level measurements from 1880 onwards.
* Uses linear regression to determine the overall trend in sea level rise.
* Predicts future sea level changes through 2050.
* Generates a second prediction model using only data from the year 2000 onward.
* Visualizes both trend lines on a single chart for comparison.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy

## Dataset

**File:** `epa-sea-level.csv`

The dataset contains:

* Year
* CSIRO Adjusted Sea Level (inches)

### Data Source

Global Average Absolute Sea Level Change (1880–2014)

Source: U.S. Environmental Protection Agency (EPA)

Data provided by:

* Commonwealth Scientific and Industrial Research Organisation (CSIRO)
* National Oceanic and Atmospheric Administration (NOAA)

## Visualization

### Sea Level Prediction Plot

The visualization includes:

* Historical sea level measurements displayed as a scatter plot.
* A regression line based on all available data (1880–present).
* A regression line based on data from 2000 onward.
* Sea level predictions extended to the year 2050.

**Output:** `sea_level_plot.png`

## Project Structure

```text
sea-level-predictor/
│
├── epa-sea-level.csv
├── sea_level_predictor.py
├── main.py
├── test_module.py
├── requirements.txt
├── README.md
└── sea_level_plot.png
```

## Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project folder:

```bash
cd sea-level-predictor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the project:

```bash
python main.py
```

The program will generate:

```text
sea_level_plot.png
```

## Learning Outcomes

Through this project, I learned:

* Time-series data analysis
* Data visualization with Matplotlib
* Linear regression using SciPy
* Trend forecasting and prediction
* Working with real-world environmental datasets
* Scientific data interpretation

## Skills Demonstrated

* Data Analysis
* Data Visualization
* Statistical Modeling
* Linear Regression
* Forecasting
* Pandas
* Matplotlib
* SciPy
* Python Programming

## Future Improvements

* Explore advanced forecasting models.
* Add confidence intervals for predictions.
* Build an interactive dashboard for climate data analysis.
* Compare sea level trends across different regions.

## Acknowledgements

This project was completed as part of the freeCodeCamp Data Analysis with Python Certification.

## Author

Bhavana R
