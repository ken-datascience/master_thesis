# Source code for my capstone project: Strategic Energy Trading on the Japan Electric Power Exchange (JEPX)

## Description about this repository
All the source code for my capstone project is stored here. Please feel free to download and use them if you are interested in this project.

## Purpose of the capstone project
This capstone ptoject focuses on strategic electricity trading on JEPX, and aims to construct and examine trading strategy of combined trading position both on the Day-Ahead market and the intraday market in order to investigate a research question: How can market participants trade electricity actively on the intraday market?

## The contents of this repository
The main contents of this repository are as follows:

- [01_Pipeline_CapstoneProject_(Preparation for all_data).ipynb](https://github.com/ken-datascience/master_thesis/blob/master/01_Pipeline_CapstoneProject_(Preparation%20for%20all_data).ipynb) contains pre-processing for all the collected datasets. It includes also time-series data analysis and expropatory data analysis for the datasets.

![Comparison between close price and system price](https://github.com/ken-datascience/master_thesis/blob/master/Images/Comparison%20of%20close%20price%20with%20System%20price.png)

![Correlation marrix of all_data](https://github.com/ken-datascience/master_thesis/blob/master/Images/CorrelationMatrix_all_data.png)

- [02-1_Pipeline_CapstoneProject_(Prediction_before_DA)](https://github.com/ken-datascience/master_thesis/blob/master/02-1_Pipeline_CapstoneProject_(Prediction_before_DA).ipynb) contains core pipeline of the prediction process where the prediction timing is before Day-Ahead market close. Please note that this notebook includes only the part that are directly related to the conclusion for reducing calculation cost. If you are interested in all the processes including any other prediction models, please find them in the Original_analysis(All_algorithms) folder  

![Prediction result (Before DA)](https://github.com/ken-datascience/master_thesis/blob/master/Images/PredictionResults_BeforeDA.png)

- [02-2_Pipeline_CapstoneProject_(Prediction_after_DA)](https://github.com/ken-datascience/master_thesis/blob/master/02-2_Pipeline_CapstoneProject_(Prediction_after_DA).ipynb) contains core pipeline of the prediction process where the prediction timing is after Day-Ahead market close. Please note that this notebook includes only the part that are directly related to the conclusion for reducing calculation cost. If you are interested in all the processes including any other prediction models, please find them in the Original_analysis(All_algorithms) folder  
![Prediction result (Before DA)](https://github.com/ken-datascience/master_thesis/blob/master/Images/PredictionResult_AfterDA.png)

- [03_Pipeline_CapstoneProject_(Strategic_Trading)](https://github.com/ken-datascience/master_thesis/blob/master/03_Pipeline_CapstoneProject_(Strategic_Trading).ipynb) contain pipeline of investigation for electricity trading strategies based on the predicted price. Please note that some code for back-testing process on this notebook require large amount of  calculation cost.
![Strategic portfolios for sellers](https://github.com/ken-datascience/master_thesis/blob/master/Images/Strategic_Portfolios_Seller.png)
![Strategic portfolios for buyers](https://github.com/ken-datascience/master_thesis/blob/master/Images/Strategic_Portfolios_Buyer.png)

- [Original_analysis(All_algorithms) folder](https://github.com/ken-datascience/master_thesis/tree/master/Original_analysis(All_algorithms)) contains all the source code that is used on the project. If you are interested in prediction models such as other linear models and non-linear models, you can find them here. Please note that some prediction models take a lot of time for calculation.
![Virtual bidding performance for traders](https://github.com/ken-datascience/master_thesis/blob/master/Images/VirtualBiddingPorformance_Trader.png)
