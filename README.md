# Surfs up

## Purpose

In this analysis project we are tasked with creating temperature data for a potential new surf and ice cream shop.  W. Avy is planning on opening a new surf shop and would like to know the temperature data for the area during the months of June and December.  With this information, they are looking to see if the surf and ice cream shop would be a sustainable, year-round business.  Using Python, Pandas functions and methods, and SQLAlchemy, we will filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the months of June and December. Then, we will convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

## Results
### June Statistics and Graph for the Temperature 
![June_Temp_Stats](https://user-images.githubusercontent.com/103154070/172430166-4f287ed2-b7f7-4f8a-8673-b71623d06eb0.png)
![Junetempgraph](https://user-images.githubusercontent.com/103154070/172430257-ab07c1f7-0257-49c7-a6b8-f63e0b5d8858.png)

### December Statistics and Graph for the Temperature 
![December_Temp_stats](https://user-images.githubusercontent.com/103154070/172430398-bfbc8d18-f6e0-4519-aff7-72202dbdae62.png)
![dectempgraph](https://user-images.githubusercontent.com/103154070/172430412-0e9022b5-78aa-423b-8d09-0c50982dc616.png)

- The maximum temperatures for June and December are 85 and 83 Degrees Fahrenheit, respectively.  These are both fairly close to one another.
- The minimum temperatures for June and December are 64 and 56 Degrees Fahrenheit, respectively.  There is a 8 degree decrease in the minimum temperature from June to December. 
- The average temperatures for June and December are 75 and 71 Degrees Fahrenheit, respectively. The average temperatures in both June and Decemeber rest fairly close to one another, with there being a 4 degree difference bewteen the two.
- The standard deviation in the month of June is 3.26 and that from Decemebr is 3.75.  The graphs of both months show a a normal distribution.  There are a few more fluctuations depicted on the June graph, but overall it is a normally distributed graph.

### Additional Queries 
To better provide an accruate recommendation, it would be helpful to have more information around the precipitation statistics for both June and December.  After performing new queries for June and December that include precipitation statistics, the results are as follows: 



#### June Temperature (0) and Precipitation (1)
![june_query](https://user-images.githubusercontent.com/103154070/172436859-6b271f7f-3fdb-4ba4-b80b-8959feabe7ef.png)
![junescatter](https://user-images.githubusercontent.com/103154070/172436888-e29c0316-2d56-4c40-a0bb-83310c33a743.png)


#### December Temperature (0) and Precipitation (1)
![dec_quiery](https://user-images.githubusercontent.com/103154070/172436930-88751224-935b-4cbf-a245-d24dfc1c2518.png)
![decscatter](https://user-images.githubusercontent.com/103154070/172436968-c9090aa4-f694-4087-a07e-7ef291bee790.png)


For both months, the temperature and precipitation data were graphed on a scatterplot with a trendline.  The slope of June is -.0367 and Decembers slope is -.0186.  This is telling us that as the temperature increases, the preceipitation decreases; this is a slightly higher shift in June as compared to December.  The precipitation average in June (.136) is slightly lower than that of December (.217), but the graphs for both show that the precipitation amounts mostly stay around 3 inches or lower.  


## Summary

From the statistics obtained, it appears that the overall statistics around the temperature are very similiar when comparing the month of June to December. The minimum temperatures between June and December have the largest gap, with December having the lower minimum.  However, the maximum temperatures as well as the average temperatures between the two months lie very close to one another.  Additionally, the precipitation amounts in both June and December are very simular.  The data would support the Surf and Ice Cream shop being sustainable year-round.
