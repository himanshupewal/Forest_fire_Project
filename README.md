# Forest Fire Prediction Project

## Getting Started

To get started with the Forest Fire Prediction Project, follow the steps below:

### Prerequisites

Make sure you have the following prerequisites installed:

- Python 
- Jupyter Notebook (optional, for running the provided notebooks)
- Additional libraries and dependencies listed in the `requirements.txt` file

### Installation

1. Clone the repository:

   
   git clone https://(https://github.com/himanshupewal/Forest_fire_Project)



# Algerian Forest Fires Dataset

This dataset includes 244 instances that regroup data from two regions of Algeria, namely the Bejaia region located in the northeast and the Sidi Bel-abbes region located in the northwest.

## Dataset Information

- **Number of Instances**: 244
- **Regions**: Bejaia (northeast) and Sidi Bel-abbes (northwest)
- **Instances per Region**: 122
- **Time Period**: June 2012 to September 2012
- **Attributes**: 11
- **Output Attribute (Class)**: fire (138 instances) and not fire (106 instances)
- 
- The dataset includes the following attributes:

1. Date: The date in the format DD/MM/YYYY, representing the day, month ('June' to 'September'), and year (2012) of the weather data observations.
2. Temp: The temperature at noon (maximum temperature) in Celsius degrees, ranging from 22 to 42.
3. RH: Relative Humidity in percentage, ranging from 21 to 90.
4. Ws: Wind speed in km/h, ranging from 6 to 29.
5. Rain: Total precipitation during the day in mm, ranging from 0 to 16.8.
6. FFMC: Fine Fuel Moisture Code, an index from the Fire Weather Index (FWI) system, ranging from 28.6 to 92.5.
7. DMC: Duff Moisture Code, an index from the FWI system, ranging from 1.1 to 65.9.
8. DC: Drought Code, an index from the FWI system, ranging from 7 to 220.4.
9. ISI: Initial Spread Index, an index from the FWI system, ranging from 0 to 18.5.
10. BUI: Buildup Index, an index from the FWI system, ranging from 1.1 to 68.
11. FWI: Fire Weather Index, an index ranging from 0 to 31.1.
12. Classes: The target variable with two classes, namely Fire and not Fire.


## Regression Models

### Linear Regression
Linear regression is a popular regression algorithm that aims to find the best-fitting linear relationship between the input features and the target variable. It assumes a linear relationship between the predictors and the response variable.

### Ridge Regression
Ridge regression is a regularized version of linear regression that adds a penalty term to the loss function. This penalty term helps to reduce the impact of multicollinearity by adding a constraint on the coefficients. Ridge regression can handle multicollinearity well and is effective when there are many correlated features.

### Lasso Regression
Lasso regression, similar to Ridge regression, also adds a penalty term to the loss function. However, Lasso regression uses the L1 norm penalty, which can lead to sparsity in the feature coefficients. This makes Lasso regression useful for feature selection, as it tends to set the coefficients of irrelevant or less important features to zero.

### Elastic Net Regression
Elastic Net regression combines the penalties of both Ridge and Lasso regressions. It uses a linear combination of L1 and L2 regularization terms to overcome the limitations of each individual method. Elastic Net regression can handle multicollinearity, select relevant features, and provide better predictive performance in certain cases.


