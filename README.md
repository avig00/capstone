# Capstone Project with Brown & Brown Insurance

# Investigating Wellness and Rx Benefit Adherence Rates as Inputs for Forecasting Future Healthcare Insurance Claims Costs


## Project Executive Summary
In the insurance industry, it is well-known that providing preventive healthcare benefits to employees is correlated with future healthcare claims costs to employers. Nevertheless, the precise strength of this relationship is less clear. In this project, the strength of this relationship is explored by engineering metrics to quantify employee adherence for wellness and Rx benefits to investigate if these factors serve as useful inputs for predictive models to forecast future claims costs. The results show that an Autoregressive Integrated Moving Average (ARIMA) model shows promise for forecasting future claims costs based solely on historical information about wellness benefit adherence and corresponding costs. Although the ARIMA model does suffer from underestimating the ground truth, it still achieves a low relative RMSE of 0.05. This is an impressive result considering the lack of availability of data. With more historical information and/or the inclusion of more input features, the ARIMA model would be more performant and could prove to be an industrially viable tool for utilizing employee wellness benefit adherence rates for forecasting future healthcare claims costs for employers.


## Repository Structure
1. All source data files are stored in the `data` folder in `.csv` format.
2. All the code needed to produce the results is included in the comprehensive notebook titled `CapstoneScript.ipynb`.
3. The final presentation slides are presented in the `PDF` file titled `CapstonePresentation`.
4. The final report is presented in the `PDF` file titled `CapstoneReport`.

## Environment Requirements
The following packages must be installed to reproduce this project in a Jupyter Notebook environment:
```
pandas
numpy
sklearn
statsmodels
matplotlib
seaborn
itertools
```
## Readability
Docstrings and comments have been included in the notebook to explain the functions and key steps used to produce the results. 

## Note about the Data Source
The source of the data used for this project is the Benefits Science Technologies (BST) website. This is not a public website, and thus accessing the data harbored on the website requires special authorization.
