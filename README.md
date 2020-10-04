# data-analytics-in-supply-chain

The data for this project is stored in a google drive folder and can be accessed by request: https://drive.google.com/drive/folders/1XrgaRp9ts6SK10pGPPTW75btIYmeta3I?usp=sharing

https://htmlpreview.github.io/?https://github.com/shaneg1507/data-analytics-in-supply-chain/blob/main/Analysis_Explained.html

The analysis for my ME in Engineering with Business thesis at University College Dublin's School of Mechanical and Materials Engineering in May 2020.

If the final customer demand were constant, supply chain management (SCM) would simply be a
backwards scheduling exercise. However, the demand is unknown and changeable and it must
therefore be forecasted. The uncertainty surrounding this forecast is where the complexity of SCM
arises and, in this regard, more accurate forecasts will result in a better overall supply chain
performance. My thesis examined various applications of data analytics in SCM, in particular the
application of demand forecasting techniques.

My thesis was conducted using data from the 2020 MSOM Data Drive Research Challenge.
To support the 2020 MSOM Data Driven Research Challenge, JD.com, China’s largest retailer,
offers transaction level data to MSOM members for conducting data-driven research. This article
describes the transactional data associated with over 2.5 million customers (anonymized) and
31,868 SKUs over the month of March in 2018.

My literature review indicated that there was a gap between the analytics techniques that were prescribed by academia and what was practised in the real world. To address this
gap, various forecasting techniques and strategies were applied to the supply chain data of a Chinese Ecommerce company, JD.com. 
- Initially, the ease of implementation and accuracy of three forecasting models were compared, namely the Holt-Winters exponential smoothing model, a seasonal autoregressive integrated moving average (SARIMA) model, and Facebook’s Prohet model. HoltWinters’ exponential smoothing model achieved the highest forecast accuracy and was the simplest model to implement. 
- Next, several aggregation strategies were tested to examine their impact on demand forecast accuracy. The demand was aggregated by customer segment, product type, and location, and the demand was forecasted for the various groups. The aggregation was primarily done by manually segregating the groups according to a criteria; however, a K-Means clustering algorithm was also used to cluster products and customers. Forecast accuracy was improved by aggregating products based on their price and their descriptive features. Forecasting demand by customer segment or by location did not lead to any increase in forecast accuracy. 
- A strong correlation was identified between orders and discounts, and discounts were suggested to be the strongest predictor of demand in the available dataset; however causality should be established through controlled experiments. 

Some recommendations were included in my thesis (that aren't included in the analysis notebooks). To improve forecast accuracy in JD.com, the use of HoltWinters’ exponential smoothing model is recommended, owing to its simplicity and accuracy; the use of judgemental adjustments to forecasts in certain situations is recommended; and the aggregation techniques that improved forecast accuracy, or improved forecast granularity in this analysis are recommended for use in JD.com. 
