# Retail-Price-Optimization

## Goal of the Project:
The goal of this project was to optimize retail prices using machine learning techniques. The aim was to find the optimal selling price for products or services that would maximize revenue and profit while attracting enough customers.

## Objective:
The objective of the project was to use data and pricing strategies to determine the right price for products, taking into account factors such as product quantity, unit price, competitor prices, product score, and the difference in prices compared to competitors.

## Tools and Techniques Used:
- Python: The project utilized Python programming language for implementing the machine learning model and data analysis.
- Pandas: Pandas library was used for data manipulation and analysis.
- Plotly: Plotly library was used for creating visualizations such as histograms, box plots, and scatter plots.
- Scikit-learn: Scikit-learn library was used for training and evaluating the machine learning model.
- Decision Tree Regressor: A decision tree regression model was employed to predict the retail prices based on the given features.

## Project Development:
The project started with importing the necessary Python libraries and loading the dataset using Pandas. Data cleaning and exploration were performed to check for null values and understand the descriptive statistics of the dataset. Visualizations were created to analyze the distribution of prices, unit prices, and the relationship between quantity and total prices. The average total prices by product category, prices by weekday and holiday were also examined. Correlation analysis was conducted to identify the relationships between numerical features.

The project then moved on to analyzing competitor pricing strategies by calculating the average competitor price difference by product category. Finally, a machine learning model (Decision Tree Regressor) was trained using the selected features and the target variable (total price). The model was evaluated using mean squared error (MSE), and predictions were made to compare the predicted retail prices with the actual prices.

## Important Features of the Project:
1. Data exploration and visualization techniques to gain insights into the dataset.
2. Calculation of average competitor price difference by product category.
3. Training a decision tree regression model to predict retail prices.
4. Evaluation of the model using mean squared error (MSE).
5. Comparison of predicted retail prices with actual prices using scatter plot visualization.

## Conclusion:
The project successfully demonstrated how machine learning techniques can be utilized to optimize retail prices. By considering various factors such as product quantity, unit price, competitor prices, and product score, a decision tree regression model was trained to predict retail prices. The analysis of competitor pricing strategies provided insights into price differences across product categories. The project aimed to find the right price that maximizes sales and profits while keeping customers satisfied.

Overall, the project highlighted the potential of machine learning in retail price optimization and provided a framework for implementing similar solutions.
