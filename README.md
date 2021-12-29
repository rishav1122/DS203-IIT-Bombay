# DS203-IIT-Bombay
## Project Code Explanation 
[![Project Code Explanation](https://github.com/rishav1122/DS203-IIT-Bombay/blob/main/project%20title.png)](https://drive.google.com/file/d/1bExwnU_ZUwkCfQMnWvf4Sq8YbzStVdET/view?usp=sharing)

## [Link to all the Datasets used](https://drive.google.com/drive/folders/1Pve9a5HRI-K0sMGpliUeqmY5TKuWKvMV?usp=sharing)

## Short term Bitcoin Price Prediction and Analysis Using Machine Learning
Abstract—Bitcoin is a decentralized crypto-currency, which is a type of digital asset that provides the basis for peer-to-peer financial transactions based on blockchain technology. One of the major problems with decentralized cryptocurrencies is price volatility, which indicates the need for studying the underlying price model. Moreover, Bitcoin prices exhibit non-stationary behavior, where the statistical distribution of data changes over time. This paper demonstrates high-performance machine learning-based classification and regression models for predicting Bitcoin price movements and prices in short term. We found that ARIMA outperforms other machine learning models tested. Deep learning solutions like Long short Term Networks were also explored.

## INTRODUCTION
Bitcoin is a digital currency, introduced in 2008 by Nakamoto. It is enabled by the blockchain technol- ogy and allows for peer-to-peer transactions secured by cryptography. In this study, we analyze the short-term predictability of the bitcoin market. Therefore, we utilize a variety of machine learning methods and consider a comprehensive set of potential market-predictive features.  
Empirical asset pricing is a major branch of financial research. Machine learning methods have been imple- mented increasingly within this domain, due to the ability to flexibly select amongst a potentially large num- ber of features and to learn complex, high-dimensional relationships between features and target labels.

## CONCLUSION 
As directly conclusive from our Exploratory data analysis that bitcoin prices are highly volatile which we also know from domain knowledge as bitcoin price highly depends on market news such as tweets or policies from government authorities with regards to cryptocurrency and sentiments of successful investors. Although from our autocorelation plot we know that there is some dependence of day’s price on price of previous days, the model developed to predict the prices still were not able to optimally learn the data distribution.  

The SVR model achieved a high R2 score of about 0.995 on both test and training set. It also achieved a low MAE(Mean absolute error) score of 0.0367 and MSE(Mean Squared Error) score of 0.0021. The Random Forests model performed better on training set but failed to generalise over the test set. This makes Random Forests model not helpful when the test set is not in the range of values of the train set. The ARIMA model was able to achieve a good mean absolute error value and a good correlation between the actual and predicted values in the test dataset but the RMSE value was quite high even though the R2 score was quite good. 

The Lstm model rapidly overfitted the data, where one of the possible way to solve this problem is to have high frequency data with less granularity. Along with this, having more related features like blockchain related predictors which act as technical indicators.For Further improvement in results, We can add additional features which can respond to market news impact on price such as positive and negative and could use it to identify sudden increase or decrease.
## REFERENCES
1. Andrianto, Y. The Effect of Cryptocurrency on Investment Port- folio Effectiveness. J. Financ. Account. 2017, 5, 229.
2. Derbentsev, V.; Babenko, V.; Khrustalev, K.; Obruch, H.; Khrustalova, S. Comparative Performance of Machine Learning Ensemble Algorithms for Forecasting Cryptocurrency Prices. Int. J. Eng. Trans. A Basics 2021, 34, 140–148.
3. Patel,M.M.;Tanwar,S.;Gupta,R.;Kumar,N.ADeepLearning- based Cryptocurrency Price Prediction Scheme for Financial Institutions. J. Inf. Secur. Appl. 2020, 55, 102583.
4. Miura, R.; Pichl, L.; Kaizoji, T. Artificial Neural Networks for Realized Volatility Prediction in Cryptocurrency Time Series. In Advances in Neural Networks—ISNN 2019; Lu, H., Tang, H.,Wang, Z., Eds.; Lecture Notes in Computer Science; Springer: Cham, Switzerland, 2019; Volume 11554.
5. Karasu, S.; Altan, A.; Sarac, Z.; Hacioglu, R. Prediction of Bitcoin prices with machine learning methods using time series data. In Proceedings of the 26th Signal Processing and Com- munications Applications Conference (SIU), Izmir, Turkey, 2–5 May 2018
6. Saad,M.;Mohaisen,A.Towardscharacterizingblockchain-based cryptocurrencies for highly-accurate predictions. In Proceedings of the IEEE INFOCOM—IEEE Conference on Computer Com- munications Workshops (INFOCOM WKSHPS), Honolulu, HI, USA, 15–19 April 2018.
7. Yiying, W.; Yeze, Z. Cryptocurrency Price Analysis with Arti- ficial Intelligence. In Proceedings of the 5th International Con- ference on Information Management (ICIM), Cambridge, UK, 24–27 March 2019; pp. 97–101.
8. Chen, Z.; Li, C.; Sun, W. Bitcoin price prediction using machine learning: An approach to sample dimension engineering. J. Comput. Appl. Math. 2019, 365, 112395.
9. Valencia, F.; Go ́mez-Espinosa, A.; Valde ́s-Aguirre, B. Price Movement Prediction of Cryptocurrencies Using Sentiment Analysis and Machine Learning. Entropy 2019, 21, 589.
