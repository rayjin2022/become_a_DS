# DS Playground
This repo is a project created to help you to grab technical skills in data science fields through practical projects.

Currently, this repo includes topics of:
1. ** Data Wrangling Scenarios  ** - Data Analysis: basic pandas queries that helps quickly answer business problems
- ** Regression Scenarios ** - Demand Forecasting: projects using Random Forest, Time Series, and Regression Techniques to predict future demand/sales based on historical data
-  ** Model Interpretation  ** - Shapley value: helps identify feature importance and to what extend each feature is affecting final prediction
- ** (WIP) Classification Scenarios ** - Propensity Scoring
- ** (WIP) Classification Scenarios ** - Recommender System


Ready? Let's have fun with real-world data challenges!

## Demand Forecasting
It's one of the most classic scenario of how regression models solving real-world requests. The companies need a scientific way to anticipate future sales, thus avoid issues including but not limit to:

1. Out-of-stock and understocking leads to lost of sales, extra refillment cost
- Overstocking leads to cost of inventory, low turnover, and high working capital
- Preoccupied supply team refrain from focusing on value-added work 

The following datasets and solutions are included regarding this topic:
- [Bike demand forecast based on features such as timing and weather indicators](https://github.com/rayjin2022/ds_playground/tree/main/Demand%20Forecasting/bike%20demand%20forecasting)

- [Item-level demand forecasting for different stores based on trend only](https://github.com/rayjin2022/ds_playground/tree/main/Demand%20Forecasting/store%20item%20demand%20forecasting)

## Data Analysis
Not all projects requires Machine Learning, but definitely requireds Data Analysis.

No matter encounter with what kind of data, it's always important to first have a basic understanding of the data.

It's recommended to use pandas-profiling to quickly screen the basic condition of data, then use visualizations (histograms, box plots, scatter plots) to make deep dives on distributions and correlation among features. Crucial features are often found during EDA process, and otherwise would never be found or thought of if jumped into modelling process directly.

The following datasets and solutions are included regarding this topic:
- [Lego Data - basic pandas manipulation] link tbd

- [Order Data - pandas manipulation + ployly html reports] link tbd

## Model Interpretation
Although the main focus of ML projects is to make as much accurate predictions as possible, model interpretability, as a intermediate output, is more important than the result.

The following datasets and solutions are included regarding this topic:
- [Boston house price] link tbd

## References

### Data Analysis
[Lego Analysis Tutorial Video](https://www.youtube.com/watch?v=eMOA1pPVUc4&list=PLuLGxuyYdOaItQD3Cy9ClPs8vCBGb2N2f&index=2) | [Corresponding code](https://github.com/KeithGalli/Pandas-Data-Science-Tasks)

### Model Interpretation
[Video tutorial on how to calculate shapley values in python](https://www.youtube.com/watch?v=IqT551LjKHw&list=PLuLGxuyYdOaItQD3Cy9ClPs8vCBGb2N2f&index=5) | [Corresponding code](https://christophm.github.io/interpretable-ml-book/shapley.html#the-shapley-value-in-detail)

[Example to show how shapley values are calculated - Ad's marginal contribution ](https://www.youtube.com/watch?v=u7Om2joZWYs)