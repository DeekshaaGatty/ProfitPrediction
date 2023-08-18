# Profit Predictor: Exploring Regression Algorithms

## Objective:
This project aims to identify the most suitable regression algorithm for optimizing profit forecasting accuracy based on R&D spend, Administration cost, and Marketing spend of various startups. The goal is to develop a predictive model that accurately estimates a startup's profit based on its spending patterns.

## Dataset:
The project utilizes the `50_Startups.csv` dataset, which contains information on different startups, including their expenditures on research and development, administration, marketing, and their respective profits. The dataset is analyzed to predict profits using various regression techniques.

## Getting Started:
1. Clone this repository to your local machine using `git clone https://github.com/DeekshaaGatty/ProfitPrediction.git`
2. Navigate to the project directory using `cd ProfitPrediction`
3. Install the necessary Python libraries using `pip install -r requirements.txt`
4. Run the `StartupsProfitPredictor.ipynb` Jupyter Notebook to explore the dataset, preprocess the data, train different regression models, and evaluate their performance.

## Contents:
- `StartupsProfitPredictor.ipynb`: Jupyter Notebook containing the project code, including data visualization, preprocessing, model training, and evaluation.
- `50_Startups.csv`: The dataset used for analysis.
- `requirements.txt`: List of required Python libraries for easy setup.
- `README.md`: This file, providing an overview of the project.
- `ProfitPrediction_Report.pdf`: This report contains the details about the existing method, proposed method, methodology and implementation.
- `Profit_Prediction.pptx`: This file is the power point presentation of the project.
- `ProfitPrediction_DemoVideo.mp4`: This video file contains the explanation of the code.

## Analysis Steps:
1. Import necessary libraries for data manipulation, visualization, preprocessing, and model evaluation.
2. Load and describe the dataset, including columns, data types, and missing values.
3. Visualize data correlation using a heatmap and explore the distribution of profit values.
4. Preprocess the data by splitting it into training and testing sets and applying feature scaling.
5. Train and evaluate various regression models, including Linear Regression, Decision Tree, Elastic Net Regression, Random Forest, and K-Nearest Neighbors.
6. Compare models based on metrics such as Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, R-squared, and Mean Absolute Percentage Error.
7. Choose the best model based on the lowest RMSE and visualize model comparison using a bar chart.
8. Visualize predicted vs. actual profit values for the best model.

## Conclusion:
After comprehensive analysis and evaluation of different regression algorithms, one of the models was identified as the best performing model for profit prediction based on R&D spend, Administration cost, and Marketing spend. The project demonstrates the process of data preprocessing, model training, evaluation, and comparison, providing insights into optimizing profit forecasting accuracy.

Feel free to explore the code, dataset, and findings in the `profit_predictor.ipynb` notebook. If you have any questions or suggestions, please open an issue.

