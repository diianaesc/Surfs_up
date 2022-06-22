# Overview of Surfs Up Analysis

Create a business case to open a shop for surfboards and ice cream in Oahu. W.Avy, who is our primary investor is interested in knowing the weather trends of the island to measure the probability of success.  

For this project we will focus on running an analysis using Python, Pandas and SQLAlchemy for the months of June and December to determine if the shop business will be sustainable year-round


# Results

- June - has an average temperture of 75°F, maximum tempeture of 85°F and minimum temperature of 64°F
- December - has an average temperture of 71°F, maximum tempeture of 83°F and minimum temperature of 56°F
- Both months have a similar standard deviation of 3, which means that the temperatures stay relatively close to the mean 


                                         June

<img width="164" alt="Screen Shot 2022-06-22 at 3 00 36 PM" src="https://user-images.githubusercontent.com/104380112/175115875-06ed4a66-6479-473c-9c9d-da50792c4c8c.png"> <img width="399" alt="Screen Shot 2022-06-22 at 3 27 12 PM" src="https://user-images.githubusercontent.com/104380112/175120243-d6cd0392-fa01-475d-b62f-a877824cee44.png">

                                        December

<img width="159" alt="Screen Shot 2022-06-22 at 3 01 26 PM" src="https://user-images.githubusercontent.com/104380112/175115939-fa8a0c91-c535-41f8-93eb-41dc416a584b.png"> <img width="408" alt="Screen Shot 2022-06-22 at 3 27 41 PM" src="https://user-images.githubusercontent.com/104380112/175120329-16edbcaa-77c9-4452-ad6a-eddfb2e43a93.png">


# Summary 
In conclusion, temperatures in June and December are relatively similar and only differ by a few degrees. This is good news for our business with weather remaining consistent throughtout the year, the number of locals and tourists will also remain consistent.

The two additional queries I would perform to gather more weather data for June and December:
1. Break out the temperature by hour to see if there are any differences between the two months. It might be that in winter temperatures drop earlier in the day. If they do we might consider closing the shop earlier to save on labour and resources 
2. Include precipitation data broken out by month to understand how this might affect the business 
