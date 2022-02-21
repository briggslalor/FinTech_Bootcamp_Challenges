# Columbia University FinTech Bootcamp Weekly Challenges

The following challenges were completed each week of class to display a grasp of the skills and tools that were taught during that week. Each individual challenge can be viewed by following the hyperlinks provided. 
---



# Major Module 3: Blockchain Technologies

---
#### Module 21: Tokenomics

[Challenge 21](https://github.com/briggslalor/Challenge_21)

The goal of this project was to build and deploy the contracts required to create a new token, the KaseiCoin, ad deploy it to a test Ethereum network with the ultimate goal of being used as a new cryptocurrency on Mars. To complete this task, a contract was written to create the KaseiCoin using inherited compliance with ERC20. Next, the Crowdsale and CrowdsaleDeployer contracts were written to allow the coin and the crowdsale to be deployed to the blockchain network and allow new accounts to interact with and buy the created KaseiCoin.

---

#### Module 20: Smart Contracts with Solidity

[Challenge 20](https://github.com/briggslalor/Challenge_20)

The goal of challenge 20 was to build, deploy and test a smart contract on the Ethereum blockchain that would allow a user to create a joint savings account wallet. Then, using the wallet, the user can send and receieve transactions as well as deposit and withdraw funds from the address created with the smart contract. It adds a level of security by ensuring that only the owners can deposit and withdraw from the created joint savings account, but allows for the public to transact with it. 

---

#### Module 19: Blockchain Wallets

[Challenge 19](https://github.com/briggslalor/Challenge_19)

In challange 19, I built a web application that would allow you to find and hire a fintech professional and then pay them through the Ethereum blockchain. In order to do this, the project uses a locally generated instance of the Ethereum blockchain generated using the Ganache application. Then, using Streamlit, a web application is built and run, allowing a user to browse professionals, select one to hire and for how long and then send the necessary funds in a transaction.

---

#### Module 18: Blockchain with Python

[Challenge 18](https://github.com/briggslalor/Challenge_18)

The goal of this project was to build and test a local instance of a blockchain using Python and Streamlit. This blockchain was built to store transactional data for sending a specified amount between two parties. The bolckchain uses hashing and proof of work to ensure its validity. Additionally, a Streamlit application was built to allow users a more friendly experience with which to interact with the blockchain.  

---



# Major Module 2: Machine Learning Applications in Finance

---

#### Module 14: Algorithmic Trading

[Challenge 14](https://github.com/briggslalor/Challenge_14)

The goal of this challenge was to build an effective algorithmic trading model, using machine learning, for an emerging markets ETF. The goal of the model is to most accurately predict when to buy long or sell short. The trading signals are based off of Standard Moving Average (SMA) calculations over both short and long periods and the times that these cross. With that strategy determined, a number of different supervised machine learning models are trained and tested to see if any could better predict the trading signals. The models tested were the Support Vector Classification (SVC), Linear Regression, Decision Tree Classifier, and AdaBoost Classifier models contained within the Scikit-Learn Module.   

---

#### Module 13: Neural Networks

[Challenge 13](https://github.com/briggslalor/Challenge_13)

In challenge 13, the goal is to use data imported from a CSV file to analyze potential venture capital investments in different companies. Using sci-kit learn, TensorFlow, and Keras, the project builds a nueral network model from the binary classification model framwework to try and predict whether or not a business venture may be succesful in the future. In addition to building the model, the challenge contains efforst to best optimize the model's predictions using different configurations of layers and nodes and testing different actiavation functions.  

---

#### Module 12: Supervised Learning

[Challenge 12](https://github.com/briggslalor/Challenge_12)

In this project, the goal was to analyze data for potential loans and predict whether or not they are healthy or high-risk loans using supervised learning  techniques, including sci-kit learn's logistic regression and imbalanced-learn's random oversampler. The analysis is conducted based on the financial data of potential borrowers, inlcuding their income, debt-to-income ratio, number of accounts, derogatory marks and total debt. Given these variables and the desired loan size and interest rate, a model was built to predict whether or not the loan is a healthy option.

---

#### Module 11: Time Series

[Challenge 11](https://github.com/briggslalor/Challenge_11)

This project is built to analyze hourly Google search trend data and stock closing prices for MercadoLibre to detect trends and predict potential forecasts for both. It uses the FBProphet library to build the model and provide answers to the research questions presented throughout the project file. In addition to the trend and stock data, there is also an analysis and model built to provide a revenue growth forecast for MercadoLibre.

The project first analyzes time series patterns and trends in the hourly data and across the seasons and relates them to trends within the stock price data. It provides an analysis of the correlation between the two across the timeframe. It then builds a model and near-term forecast prediction for the hourly Google search trend data. Finally, it builds another model based on the revenue data to predict potential cases for revenue growth over the next quarter.

---

#### Module 10: Unsupervised Learning

[Challenge 10](https://github.com/briggslalor/Challenge_10)

The goal of challange 10 was to perform analysis on cryptocurrency using unsupervised machine learning techniques inclduing KMeans Clustering and PCA. This project uses the KMeans algorithm and Principle Components Analysis to cluster cryptocurrencies based on their performance during a set time period. It then visualizes how the different clusters of cryptocurrencies performed similarly during different time periods. 

---



# Major Module 1: Financial Programming using Python

---

#### Module 7: Financial Databases with SQL

[Challenge 7](https://github.com/briggslalor/Challenge_7)

This project contains an analysis of an ETF portfolio using data imported from the contained SQL database. The project demonstrates creating and using SQL queries to access the data and import it into a Pandas dataframe. With the data read into a dataframe, financial analysis, including calculating the daily and cumulative returns of a single asset, PYPL, and the entire ETF portfolio, is completed and visualized using HVPlot.

---

#### Module 6: Data Visualizations with PyViz

[Challenge 6](https://github.com/briggslalor/Challenge_6)

The goal of this challenge was to use data visualization techniques to better understand pricing trends within the San Fransisco rental market. It uses data, including sales prices per square foot and gross rent, to analyze and identify trends within the San Fransisco rental housing market between 2010 and 2016. In addition to providing aggregated data and research analysis, this project includes a number of interactive plots to help visualize and better understand the identified trends in the data.

---

#### Module 5: Financial Simulations and APIs

[Challenge 5](https://github.com/briggslalor/Challenge_5)

This challenge creates a retirement planner and emergency fund calculator. Using the Alpaca Trade API, this project obtains the current prices of different cryptocurrencies, stocks, and bonds to use in calculating the current value of a given retirement fund and determine whether or not it is large enough to create a secondary emergency fund. In addition, it runs a series of Monte Carlo simulations on differently weighted retirement portfolios to determine if there is a chance for an earlier retirement based on the potential future performance of the given retirement fund. 

---

#### Module 4: Quantative Analysis with Pandas

[Challenge 4](https://github.com/briggslalor/Challenge_4)

This challenge represents a statistical analysis of different retirement funds offered by 4 major money managers: Soros Fund Management, LLC, Paulson & Co. Inc., Tiger Global Management LLC, and Berkshire Hathaway, Inc. The project includes calculations and quantative analysis of daily and cumulative returns, analysis of their volatility and risk, and calculations and analysis of their risk-return profiles using Sharpe Ratio calculations. Additionally, it includes further analysis of the rolling betas of the funds offered by Berkshire Hathaway, Inc. and Tiger Global Management LLC. Finally, the project offers analysis and recommendation as to the best fund to be included within a firm's offerings.

---

#### Module 3: Financial Analysis with Pandas

[Challenge 3](https://github.com/briggslalor/Challenge_3)

The goal of challenge 3 was to collect, prepare and analysis pricing data for Bitcoin and other cryptocurrencies and determine whether or not opportunities for arbitrage existed within the market. This challenge relies heavily on the use of the Pandas library to import the pricing data from provided CSV files and prepare and clean the data to use in the analysis and visualization of potential arbitrage opportunities. 

---

#### Module 2: Financial Applications with Python

[Challenge 2](https://github.com/briggslalor/Challenge_2)

The purpose of this application is to provide a user with an application capable of comparing their given loan requriements with a list of available lendors and determining if the user can qualify for a loan. The application can then save the qualified loans to a CSV file determined by the user. The application takes into account the user's credit score, monthly debt, monthly income, desired loan amount and home value to determine their qualification status.

---

#### Module 1: Financial Programming with Python

[Challenge 1](https://github.com/briggslalor/Challenge_1)

The goal of module 1's challenge was to automate the valuation for microlending loans using Python. Using basic Python operations, I defined new functions and filters to automate the calculations of different loans and determine their potential value. 
