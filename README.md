## Authors: Daniel Muniz & Alejandro Suarez
 
 
## Abstract

This project seeks to explore portfolio building techniques that will do well in bear markets. We look at quarterly and daily data that point to a stock being resistant to recessions and we sample portfolios to compare between resistant and non-resistant stocks. We find that some treatments give promising portfolios during both bull and bear markets. These naive results warrant more investigation into the relationship between these metrics and portfolio performance.



## Goals:
- Build a recession resistant portfolio of S&P 500 stocks that beats the overall market during bear markets while maximizing the Sharpe Ratio
- Compare naively constructed portfolios and Sharpe Ratio optimized portfolios against control portfolios
- Establish a proof of concept that will serve as a template for the continuation of building recession resistant portfolios 

<img src="https://github.com/capstonefiu2020/CAP2020_FINAL/master/images/Sharpe_Ratio_Formula.png" width="470" height="200" />





## Results:
### Experiment 1:
* The alternative portfolios produced significantly better results for both the ROE and PEG treatments. In particular, the ROE 
* treatment outperformed controls on both 2019 and recession data. 

### Experiment 2:
* The more the Alternative stocks beat the S&P 500 in 8/2008-12/2008, the better the Alternative portfolio performed in Q1 of 2020
* However there was no statistically significant separability between Alternaive and Control portfolios

## Conclusions:
* ROE and PEG portfolios performed very well
* Using the return threshold as a heuristic is a good start (Experiment 2) to estimate stocks eligible for alternative portfolios 
* Other metrics related to moving averages and D/E ratio need to added to alternative portfolio criteria
* The more stocks to select from, the large the sample space of alternative/control portfolio designs

