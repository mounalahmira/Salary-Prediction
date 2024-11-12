
---

# Software Developer Salary Prediction

This project is a Streamlit web application that predicts the salary of a software developer based on user input, including country, education level, and years of experience. It also includes an exploratory data analysis (EDA) page for visualizing salary distributions by country and experience level.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Future Improvements](#future-improvements)
- [Acknowledgements](#acknowledgements)

## Overview

This app uses machine learning to predict software developer salaries. It leverages a trained model saved as a pickle file, which is loaded and used for predictions based on user input. Additionally, an exploration page visualizes key salary trends from the Stack Overflow Developer Survey 2020 dataset.

## Features

- **Predict Page:** Estimate software developer salaries based on user inputs.
- **Explore Page:** Visualize mean salaries by country and experience, and analyze distribution through interactive charts.
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourprojectname.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the `saved_steps.pkl` model file and the `dataset/survey_results_public.csv` file in the appropriate directories.

## Usage

Run the Streamlit app locally by navigating to the project folder and running:
```bash
streamlit run app.py
```

### Pages

- **Explore Page**: Analyze salary distributions, compare salaries across countries and by years of experience.
- **Predict Page**: Enter details to predict a software developer’s salary.

## Technologies

- **Python**: Core programming language
- **Streamlit**: Web framework for data apps
- **Pandas**: Data manipulation
- **NumPy**: Numerical calculations
- **Matplotlib**: Visualizations
- **Scikit-Learn**: Machine learning model (trained and saved as a pickle file)

## Future Improvements

- **Enhance model accuracy** with additional features.
- **Expand exploration options** with more dynamic visualizations.

## Acknowledgements

This project utilizes the Stack Overflow Developer Survey 2020 dataset.

--- 
