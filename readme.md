Gold is a valuable commodity widely used for trading, investment, and hedging purposes. Recently, the increasing volatility in gold prices has attracted significant attention from investors. However, gold transactions remain inherently risky due to the unpredictable nature of the gold market. This necessitates the development of robust gold price prediction models to assist investors, marketers, and financial institutions in making informed economic and monetary decisions.
This research investigates the relationship between gold price movements and the sentiment of news headlines related to key global economic factors. Employing an event-driven approach, the study examines the impact of economic news on short-term gold price trends using machine learning models and sentiment analysis techniques.

The research explores three scenarios for gold price prediction:
1.	Using historical gold prices and news sentiment
2.	Using historical gold prices and macroeconomic variables
3.	Combining news sentiment with macroeconomic variables

The macroeconomic variables include the USD Index, interest rates, inflation rates, bond yields, and oil prices. Additionally, the study introduces a classification model to predict gold market movements, categorizing the output into buy, hold, and sell decisions.
A dataset of news headlines covering factors influencing gold prices (e.g., geopolitical events, economic crises, US dollar trends, oil prices, inflation, and interest rates) from January 2015 to 2024 was collected from MarketWatch. Sentiment analysis was applied to the news headlines to determine polarity, and this sentiment data was integrated with historical gold price data and macroeconomic indicators for model training.

Three machine learning models—Linear Regression, Random Forest, and XGBoost—were implemented for the three scenarios, and their performance was compared using Root Mean Square Error (RMSE). The Linear Regression model consistently achieved the best performance across all scenarios. For instance, in the scenario combining macroeconomic variables and news sentiment, Linear Regression achieved an RMSE of 14.36, outperforming Random Forest (RMSE: 16.14) and XGBoost (RMSE: 18.15).

The findings reveal that news sentiment alone is insufficient for predicting gold prices or movements. However, incorporating macroeconomic variables alongside news sentiment significantly enhances predictive accuracy. This study highlights how a combination of sentiment and macroeconomic factors can serve as an early warning indicator for market trends and offers a novel approach to gold price forecasting.
