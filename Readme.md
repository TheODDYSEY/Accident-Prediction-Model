

# Accident Severity Prediction Model

## Overview

This repository contains a Python script that implements a Multiple Linear Regression model for predicting accident severity. The model uses various independent variables, such as injuries, deaths, types of vehicles, and more, to estimate the number of accidents (dependent variable).

## Dependencies

Before running the code, make sure you have the following dependencies installed on your system:

- Python 3.x
- NumPy
- pandas
- matplotlib

You can install these libraries using `pip`. For example:

```bash
pip install numpy pandas matplotlib
```

## Usage

1. Clone this repository to your local machine.

2. Create a Python environment and install the required dependencies.

3. Modify the data in the script under the section labeled "Create a DataFrame with your data" to reflect the dataset you want to analyze.

4. Ensure that the model coefficients `a0`, `a1`, `a2`, `a3`, and `a4` are set correctly based on your dataset.

5. Run the script using a Python environment.

6. The script will calculate the predicted accident severity and visualize the results using scatter plots and best-fit lines.

7. You can also use the hypothetical data section to make predictions for different scenarios.

## Code Structure

- The code is structured into sections for data setup, coefficient definitions, calculations, and visualization.

- The primary dataset is represented as a Pandas DataFrame, making it easy to swap out data for analysis.

- The script calculates the sum of squares of regression (SSR), sum of squares of error (SSE), and coefficient of determination (R^2).

- The results are visually presented with a scatter plot and a best-fit line for the actual vs. predicted accident severity.

## Hypothetical Predictions

You can use the same script to make hypothetical predictions. Modify the data under "MAKE PREDICTIONS AND VISUALIZE" in the script to specify hypothetical scenarios and observe the model's predictions for different independent variables.

## License

This project is open-source and available under the MIT License. You are welcome to use, modify, or extend this code for your own projects.

---

