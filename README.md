# Machine Learning for Real Estate
Machine Learning for Real Estate

## Outlook for 2020

It might be a good time to start thinking about investing in real estate as Zillow experts predicted that recession will start in 2020. The money policies compounded with the COVID-19 pandemic will likely result in the prediction becoming reality.

https://www.investopedia.com/investing/next-housing-recession-2020-predicts-zillow/
http://zillow.mediaroom.com/2018-05-22-Experts-Predict-Next-Recession-Will-Begin-in-2020

## Data source

### Zillow Housing Data

Zillow housing data can be found here. Data is refreshed on the monthly basis.
https://www.zillow.com/research/data/

We are particularly interested in the following datasets:
1. Zillow Home Value Index (ZHVI) for Single Family Homes. This data set can be downloaded here: http://files.zillowstatic.com/research/public_v2/zhvi/Zip_Zhvi_SingleFamilyResidence.csv

ZHVI is a smoothed, seasonally adjusted measure of the typical home value and market changes across a given region and housing type. In this project I chose to investigate the home value in a certain ZIP code.

2. Zillow forecast across all regions. This data set can be downloaded here: http://files.zillowstatic.com/research/public_v2/zhvif/AllRegionsForePublic.csv

This is a one-year forecast from the date of the data release.

3. Zillow monthly listing for all homes. This data set can be downloaded here: http://files.zillowstatic.com/research/public/Zip/MonthlyListings_SSA_AllHomes_Zip.csv

There are other datasets that are quite interesting for further exploration but will not be utilized in this projects: ZHVI for all type of home, including condo/co-op, rental data set, and actual inventory and sales.

## Visualization

![Forecast by State](/image/state_forecast.png)

This is quite interesting: Zillow forecasted that the real estate market will come to a recession in the aforementioned articles, but also sent the same message in their forecast dataset. AZ is the only state that median home value is not going down. State-wide, the real-estate market is not looking strong for 2020.

![New Listing](/image/new_listing.png)

If the number of new listing is an indicator of market growth, the real-estate marker is not looking very well starting 2019. The downward trending started Jan 2019 in most of the state that I looked at. This chart only show 7 states - CA, CO, FL, GA, MA, MS, TX.

On the other hand, this one can be explain that the real-esate value is growing (which is directly opposite with Zillow forecast) so people are holding on to their properties with the hope to sell at a much higher price later on.

![Massachusetts](/image/massachusetts.png)
