Airbnb is now one of the most successful modes of sharing economy and millions of homeowners and businesses benefits from listing on Airbnb. Therefore, analysing and exploring the factors that lead to a successful listing is of great value for the investors and hosts. This is the main reason drives the research. Besides, there are many metrics in the Airbnb listing, which is also a good sample to analyse the relationship between various factors and price modelling.

The goals are:
1.	The most common words in the descriptions of successful listings,
2.	Select the most relevant features for price prediction, 
3.	Built price prediction model based on the features selected, several models will be applied. 
4.	Evaluate the models and choose the best one

![Airbnb distribution pie](https://user-images.githubusercontent.com/54901881/69894745-1060bd00-1378-11ea-8dc3-98d4485f5809.png)
Airbnb distribution pie
![Heatmap for selected factors](https://user-images.githubusercontent.com/54901881/69894931-16a46880-137b-11ea-8daf-928c0c5d45f5.png)
Heatmap for related factors
![Listings layout in Sydney Map](https://user-images.githubusercontent.com/54901881/69894960-acd88e80-137b-11ea-9765-96a551f04c54.png)
Listings layout in Sydney Map
![Most common word used in description in top 90 lisings](https://user-images.githubusercontent.com/54901881/69894961-b19d4280-137b-11ea-8c75-423ce8e4f338.png)
Most common word used in description in the top 90 listings

The analysis has focused on analysing the factors in Airbnb listings and get more reliable and complex relationships between them. A few plots in the appendix show that the most popular suburb is Sydney CBD, most popular room type is the entire home and apartment and the most popular property type is apartment. This reveals that the listings tend to be located in a more continent place with more facilities. The description keywords also provide the hosts support for choosing the right word to attract more customers.

The factors for price modelling include nine features, which are accommodates, beds, neighbourhood_cleansed, room_type, cancellation_policy, cleaning_fee, guests_included, minimum_nights. By entering these features, the users will get an indicative price for their listing. 

The price prediction model is relatively reliable as it can successfully predict the price in a range of 5. However, it might be improved by other modelling methods which future analysis needed. Besides, the dataset is only focused on the listings in December, the price predictions for the whole year will also need further analysis.
