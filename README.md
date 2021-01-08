# Predicting and Visualizing Airbnb prices in NYC using Python
I used Laura Lewis's Project as a baseline (https://towardsdatascience.com/predicting-airbnb-prices-with-machine-learning-and-deep-learning-f46d44afb8a6). The difference in my project is that focused on airbnb Listings in NYC. I also used NPL libarires to do a sentiment analyis to see how positive reviews were for each listing as well as bringing outside data to try to increase my explained variance score. I  obtained airbnb listings prior to COVID (September 2020) since COVID prices would prove to be a huge outlier.

My project is split to 5 different notebooks:
1) gettingZipcodes.ipynb , is where I attempt to get the zipcode for each listing using their longitude and latitude coordinates.
2) Data_Cleansing.ipynb , is where I do data wrangling and cleaning as well as obtaing the average polarity score for each listings
3) restaurnat_data_cleansing, is where I obtain a dataset that has number of restaurants in each zipcode of nyc which I later use to merge 
4) Visualization/Modeling.ipynb , is where I do  visualizations and modeling to predict the prices.
5) subwayData.ipynb , is where I obtained a dataset that has the number of subways for each listing in a 1 mile radius.
