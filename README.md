# African Crisis : Overview of dataset 

* __Context__:

This dataset is a derivative of Reinhart et. al's Global Financial Stability dataset which can be found online [here](https://www.hbs.edu/behavioral-finance-and-financial-stability/data/Pages/global.aspx)

The dataset will be valuable to those who seek to understand the dynamics of financial stability within the African context.

The dataset can also be found on Kaggle [here](https://www.kaggle.com/chirin/africa-economic-banking-and-systemic-crisis-data)


* __Content__:

The dataset specifically focuses on the Banking, Debt, Financial, Inflation and Systemic Crisis that occurred from 1860 to 2014 in 13 African countries. Including: Algeria, Angola, Central African Republic, Ivory Coast, Egypt, Kenya, Mauritius, Morocco, Nigeria, South Africa, Tunisia, Zambia and Zimbabwe.


* __Motivation__: 

My inspiration for taking on this project comes first from the fact I was born in Nigeria and wanted to know the financial history of the country I was born in. Second is to determine which factors are most associated with Systemic Crisis in Africa? and at which annual rate of inflation does an Inflation Crisis become a practical certainty?

* __Variables__:

1) Domestic Debt in Default: Domestic debt is a central government's debt. It is debt issued by the lenders within the country (eg.Financial Institutions within the country).


2) Sovereign External Debt Default: External debt is the portion of a country's debt that was borrowed from foreign lenders, including commercial banks, governments, or international financial institutions. These loans, including interest, must usually be paid in the currency in which the loan was made. To earn the needed currency, the borrowing country may sell and export goods to the lender's country.


3) Systemic Crisis: Systemic crisis is a domino effect in which financial trouble spreads between institutions and markets until it affects the whole financial system with dire global economic consequences.


4) Currency Crisis: A currency crisis is a situation in which serious doubt exists as to whether a country's central bank has sufficient foreign exchange reserves to maintain the country's fixed exchange rate. The crisis is often accompanied by a speculative attack in the foreign exchange market. A currency crisis results from chronic balance of payments deficits, and thus is also called a balance of payments crisis. Often such a crisis culminates in a devaluation of the currency.


5) Inflation Crisis: Inflation is a quantitative measure of the rate at which the average price level of a basket of selected goods and services in an economy increases over a period of time. It is the constant rise in the general level of prices where a unit of currency buys less than it did in prior periods.


6) Banking Crisis: A banking crisis is often associated with financial crisis. It refers to a panic or a bank run during which investors sell off assets or withdraw money from savings accounts because they fear that the value of those assets will drop if they remain in a financial institution.




     
## Exploring the Data 
 ![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/EDA_GIF.gif?raw=true)

### Comparing the exchange rates
Observation of the first plot, we can see that for almost all african countries the exachange rates did not start flantuating till after 1960.
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/exchange_rates.png?raw=true)




For the observations from our plot starting with Domestic debt defaults, we can see that on Angola which suffered 10 defaults and Zimbabwe which suffered 30 deafualts were the only 2 countries to suffer domestic debt defaults from 1860-2014.

For Sovereign External Debt Defaults all countries except Mauritius had at lease 1 default between 1860-2014. Central African Republic being the highest with 33 defaults.

For Systemic Crisis between 1860-2014. All countries except Mauritius, Angola, and South Africa had at least 1 Systemic Crisis. The highest being Central African Republic with 19

All countries suffered at least 1 Currency Crisis between the year 1860-2014. Ivory Coast being the least with 1 and Zimbabwe being the highest with 21

All countries had an Inflation Crisis betweent the year 1860-2014. Angola being the highest with 24 and South Africa being the least with 1. 

As for Banking Crisis all countries suffered at least 1 or more Crisis. The country with the highest number of Banking Crisis was Central African Republic with 19 and the least was Mauritius with 1.
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/overrall_default_and_crisis.png?raw=true)


### Comparing Deafaults and Crisis before independence:
The plot below shows the count of deafults and crisis that occured in all 13 African countries before their independence.
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/before_independence_default_and_crisis.png?raw=true)

### Comparing Deafaults and Crisis after independence:
The plot below shows the count of deafults and crisis that occured in all 13 African countries after their independence.
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/after_independence_default_and_crisis.png?raw=true)

### Comparing Sovereign External Debt Defaults and Systemic Crisis for all Countries:
The blue line in the plots represents when Sovereign External Debt Defaults occured and the red line represents when a Systemic Crisis Occured. From the plot we can observe that there is a bit of correlation between both. There is roughly about a 25% correlation, meaning that there is a 25% chance a Systemic Crisis occurs whenever a Sovereign External Debt Default Occurs. 
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/sovereign_defaults_and_systemic_crisis.png?raw=true)

### Comparing when Banking Crisis occured and when Systemic Crisis for all Countries:
The blue line in the plots represents when Banking Crisis occured and the red line represents when Systemic Crisis Occured. From the plot we cam observe that there is heavy correlation between both. There is roughly about a 86% correlation, meaning that there is a 86% chance a Systemic Crisis occurs whenever a Banking Crisis Occurs. 
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/banking_crisis_and_systemic_crisis.png?raw=true)


### Comparing when Currency Crisis occured and when Systemic Crisis for all Countries:
The blue line in the plots represents when a Currency Crisis occured and the red line represents when Inflation Crisis Occured. From the plot we can observe that there is some correlation between both. There is roughly about a 40% correlation, meaning that there is a 40% chance a Systemic Crisis occurs whenever a Currency Crisis occurs. 
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/currency_crisis_and_inflation_crisis.png?raw=true)

### Comparing when Annual Inflation CPI levels and when Inflation Crisis occured for all Countries:
The blue line in the plots represents when a the Annual Inflation Rates and the red line represents when Inflation Crisis Occured. From the plot we can observe that for almost all countries with the exception of Zimbabwe, whenever the Annual Inflation CPI is greater than or equal to 20% an Inflation Crisis is almost certain.
![alt text](https://github.com/faithfulalabi/African_Crisis/blob/main/currency_crisis_and_inflation_crisis.png?raw=true)

## Answering our Motivation behind this project: Which factors are most associated with Systemic Crisis in Africa and at which annual rate of inflation does an Inflation Crisis become a practical certainty?

* For which factors are most associated with Systemic Crisis in Africa; From our plot observations above we can see that the most important factor associated with Systemic Crisis in Africa, is when a Banking Crisis Occurs. There is an 86% chance a Systemic Crisis occurs whenever a Banking Crisis occurs. The second factor is when a Sovereign External Debt Defaults occurs. Though the percentage of a Systemic Crisis occuring is 25% when an Sovereign External Debt Fault occurs, I believe it is high enough to be considered an important factor.

* For the question at which annual rate of inflation does an Inflation Crisis become a practical certainty, we can see from our Inflation Crisis observation that for almost all African countries with the exception of Zimbabwe, whenever the Annual Inflation rate is greater than or equal to 20% an Inflation Crisis is almost certain.

## Install
* Numpy
* Pandas
* Matplotlib
* Seaborn
