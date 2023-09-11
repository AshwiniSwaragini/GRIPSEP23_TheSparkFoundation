# GRIPSEP23_TheSparkFoundation
GRADUATED INTERNSHIP PROGRAMME
Internship-Tasks
This is one of the tasks given to us in the internship we are doing with The Sparks Foundation i.e GRIP(Graduate Rotational Internship Program )

Task1
Prediction using Supervised ML
● Predict the percentage of an student based on the no. of study hours.

● What will be predicted score if a student studies for 9.25 hrs/ day?

● This is a simple linear regression task as it involves just 2 variables.

● Dataset : http://bit.ly/w-data

Task2
Prediction using Unsupervised ML
● From the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually.

● Dataset : https://bit.ly/3kXTdox

Task 3
Exploratory Data Analysis
● Perform ‘Exploratory Data Analysis’ on dataset ‘SampleSuperstore’

● As a business manager, try to find out the weak areas where you can work to make more profit.

● What all business problems you can derive by exploring the data?

● Dataset: https://bit.ly/3i4rbWl

Task 4
Exploratory Data Analysis-Terrorism
● Perform ‘Exploratory Data Analysis’ on dataset ‘Global Terrorism’

● As a security/defense analyst, try to find out the hot zone of terrorism.

● What all security issues and insights you can derive by EDA?

● Dataset: https://bit.ly/2TK5Xn5

Task 5
Exploratory Data Analysis - Sports
● Perform ‘Exploratory Data Analysis’ on dataset ‘Indian Premier League’

● As a sports analysts, find out the most successful teams, players and factors contributing win or loss of a team.

● Suggest teams or players a company should endorse for its products.

● Dataset:https://bit.ly/34SRn3b

Task 6
Prediction using Decision Tree Algorithm
● Create the Decision Tree classifier and visualize it graphically.

● The purpose is if we feed any new data to this classifier, it would be able to predict the right class accordingly.

● Dataset : https://bit.ly/3kXTdox

Task 7
Stock Market Prediction using Numerical and Textual Analysis
● Objective: Create a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines

● Stock to analyze and predict - SENSEX (S&P BSE SENSEX)

● Download historical stock prices from finance.yahoo.com

● Download textual (news) data from https://bit.ly/36fFPI6

Task 8
Timeline Analysis : Covid-19
● Create a storyboard showing spread of Covid-19 cases in your country or any region (Asia, Europe, BRICS etc) using Tableau, Power BI or SAP

● Use animation, timeline and annotations to create attractive and interactive dashboards and story

● Identify interesting patterns and possible reasons helping Covid-19 spread with basic as well as advanced charts

● Screen-record the completed storyboard along with your audio explaining the charts and giving recommendations.

● Dataset: Daily updated .csv file on https://bit.ly/30d2gdi


TASK-7 : STOCK PRICE PREDICTION USING NUMERICAL AND TEXTUAL ANALYSIS

Steps: Step 1: Stock Price Analysis and Prediction Step 1.1: Importing Required Libraries for numerical analysis and prediction of stock prices Technical Stack used :

Numpy Array Matplotlib Pandas Keras Scikit Learn Math Step 1.2: Importing the Numerical dataset and performing Exploratory Analysis Step 1.3: Creating a dataframe for storing the Closing stock data per day Step 1.4: Data Normalization and Division into Training and Test sets Step 1.5: Creating a LSTM Neural Network Model for Numerical Analysis Step 1.6 : Making Predictions of the Model Step 2: Textual Data(News Headlines) Analysis Step 2.1: Importing Required Libraries for Textual (News Headlines) analysis Step 2.2: Importing the Textual dataset and performing Exploratory Analysis

Step 2.5: Sentiment Analysis of News Headlines Step 3: Creating Hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines Step 3.1: Importing Required Libraries Step 3.2 : Importing the Numerical and Textual dataset Step 3.3: Creating Hybrid data from Numerical and Textual Data Step 3.4: Performing Sentiment Analysis on Hybrid Data Step 3.4.1: Sentiment Analysis using TextBlob Step 3.4.2: Adding subjectivity and polarity Scores to Textual Data (News Headlines) Step 3.4.3: Visualizing the polarity and Subjectivity scores Step 3.4.4: Performing Sentiment Analysis over the news Headlines of Hybrid Data Step 3.5: Training and Testing the Models for Stock Price/Performance Analysis

I have found the accuracy of each model as mention below:

The LSTM model can be tuned for various parameters such as changing the number of LSTM layers, adding dropout value or increasing the number of epochs. But are the predictions from LSTM enough to identify whether the stock price will increase or decrease? Certainly not!

As I mentioned at the start of the article, stock price is affected by the news about the company and other factors like demonetization or merger/demerger of the companies. There are certain intangible factors as well which can often be impossible to predict beforehand
