# Budget Allocation Project
The following is a data science and optimization project that achieved 5th place in a global competition. The project focuses on predicting the volume of hectoliters to be sold for different products over two horizon periods and then optimizing the net revenue while minimizing the investment budget (discounts).

## Project Overview
The primary goal of this project was to use data-driven approaches to predict product sales volumes and optimize budget allocation for discounts in order to maximize net revenue. We employed machine learning, optimization techniques, and data visualization to achieve this goal.

### Problem Statement
The problem can be summarized as follows:

* Predict the volume of hectoliters to be sold for each product over two horizon periods.
* Optimize the allocation of discounts to maximize net revenue while keeping the investment budget within bounds and adhering to business constraints.

### Key Metrics
We evaluated the model's performance using the following key metrics:

* Mean Absolute Percentage Error (MAPE): 21.66%
* Root Mean Square Error (RMSE): 0.9163
* Mean Absolute Error (MAE): 0.5277

## Machine Learning Model
We used the XGBoost algorithm for the regression problem and optimized its hyperparameters using Optuna. The trained regression model was used for volume predictions.

### Optimization Approach
To optimize budget allocation, we employed non-linear constraint optimization using the COBYLA algorithm. The objective function was constructed to:

* Maximize net revenue.
* Minimize the investment budget (discounts).
* Introduce a lambda value to balance the trade-off between net revenue and discount values.
* Account for business constraints and variation predictions.

## Global Competition
Our project achieved 5th place in a global competition, showcasing the effectiveness of our approach in solving real-world problems.


# Usage

The project's Jupyter notebooks and scripts can be used to:

* Train and evaluate the machine learning model for volume prediction.
* Perform budget allocation optimization using the COBYLA algorithm.
* Visualize results and generate plots.

Please refer to the individual notebook documentation for detailed usage instructions.

Acknowledgments
We would like to thank the organizers of the global competition and the open-source community for their valuable contributions and support.
