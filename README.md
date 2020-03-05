# Financial Analysis     
               
This script takes a stock ticker, performs a discounted cash flow valuation, identifies support and resistance levels alongside entry and exit points. This leads to a final sentiment vs price analysis conducted with data from twitter.
        
<p float="center"> 
  <img src="images/technical_g.PNG" width="400" />
  <img src="images/sentimentPlot_g.PNG" width="400" /> 
</p>
<p float="center">
  <img src="images/price_g.PNG" width="400" />  
  <img src="images/dcf_ss.PNG" width="300" />
</p> 

## Discounted Cash Flow ##

A discounted cash flow does what it implies. It estimates a companies future cash flows, and discounts these cash flows at some rate to arrive at the intrinsic value of the company and is the most widely used technique.

This DCF model is broken into these 3 parts
* Forecasting Free Cash Flows (FCF)
  ![FCF](/images/FCF_ss.PNG)

* Weighted Average Cost of Capital (WACC)
  ![WACC](/images/wacc_ss.PNG)

* Terminal and Intricsic Value
  ![VALUATION](/images/valuation_ss.PNG)
 
## Technical Analysis ##
Technical analysis allows us to determine patterns not usually found through financial analysis.

This portion of the program is split into determining the following
* Entry/Exit Points to Determine Support and Resistance Regios
![SupRes](/images/region_ss.PNG)

## Sentiment Analysis ## 

I scraped tweets from twitter corresponding to a specific stock ticker and plot the sentiment and price correlation.
* Determining Sentiment
![Sentiment](/images/sentiment_ss.PNG)

* Relating Sentiment and Price
![Plot](/images/plot_ss.PNG)

### Dependencies/Libraries Used ###
1. Pandas
2. Numpy
3. MatPlotLib
4. GOT3
5. TextBlob
6. Requests
7. BeautifulSoup
