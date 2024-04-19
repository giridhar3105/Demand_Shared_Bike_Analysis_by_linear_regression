# Project Title: Demand_Shared_Bike_Analysis_by_linear_regression
# Linear_Regression Algorithm
# Overview
- This project outlines a method for predicting bike sharing demand using a linear regression model. By analyzing factors like weather, seasonality, and day of the week, the model can help bike-sharing companies 
  optimize their services.

## Project Structure

- data/: Contains the bike rental data (day.csv).
- notebooks/: Jupyter notebooks for analysis:
- 01_data_exploration.ipynb: Explores the data.
- 02_data_preprocessing.ipynb: Cleans and prepares the data.
- 03_model_building.ipynb: Builds the linear regression model.
 -04_model_evaluation.ipynb: Evaluates the model's performance.
README.md: Provides project overview, instructions, and key findings.
## How to Run the Analysis

- Clone the repository.
- Install required libraries (listed in requirements.txt).
- Run the Jupyter notebooks in the notebooks directory sequentially (you can use jupyter notebook in your terminal).
## Requirements

- Python 3.x
- Jupyter Notebook
- Several data science libraries (Pandas, NumPy, etc.) - Use pip install pandas numpy etc. in your terminal for installation.
- Scikit-learn for machine learning - Use pip install scikit-learn
- Statsmodels for statistical analysis - Use pip install statsmodels
## Results
- The model achieved an R-squared of 0.8372, indicating a good fit to the data.
- Key factors influencing demand include temperature, specific weather conditions, and year.
## Future Improvements

- Include additional features like marketing campaigns or holidays.
- Experiment with different machine learning algorithms.
- Develop a web app or API for real-time demand prediction.
## License

- This project is licensed under the MIT License.
