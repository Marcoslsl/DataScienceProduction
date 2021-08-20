# DataScienceProduction

## Business Problem

Obs: It's a context created by me to simulate a real business problem. together with some information got from Kaggle.

This project is motivated by Rossmann CFO. Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. They feel like doing this because they want to invest to reform the drug stories. Rossmann operates over 3,000 drug stores in 7 European countries. Currently,  Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances.

## Solution Proposal

The idea is to produce a solution based on machine learning because is a clear prediction model problem. And make this solution accessible by smartphone (telegram)


## Steps For This Solution:

1. Data Description
2. Feature Engineering
3. Filtering Variables
4. EDA
5. Data Preparation
6. Select the Main Variables 
7. Machine Learning Model
8. Hyperparameter Fine Tuning
9. Understanding the Error
10. Deploy


## Data Information

- Id - an Id that represents a (Store, Date) duple within the test set

- Store - a unique Id for each store

- Sales - the turnover for any given day (this is what you are predicting)

- Customers - the number of customers on a given day

- Open - an indicator for whether the store was open: 0 = closed, 1 = open

- StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None

- SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools

- StoreType - differentiates between 4 different store models: a, b, c, d

- Assortment - describes an assortment level: a = basic, b = extra, c = extended

- CompetitionDistance - distance in meters to the nearest competitor store

- CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor was opened

- Promo - indicates whether a store is running a promo on that day

- Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating

- Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2

- PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

This Dataset came from Kaggle: https://www.kaggle.com/c/rossmann-store-sales/data