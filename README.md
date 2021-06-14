# Bike-Sharing
Present a business proposal for a bike-sharing company. Imported, styled, and portrayed data accurately and created worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.

## Overview

  - The purpose of this analysis was to find compelling compelling information from a NYC Citi Bike dataset and use it to make a business proposal to a potential investor to start our own bike-sharing company. 


## Results

![Total rides by hour](https://user-images.githubusercontent.com/78178900/121843768-7f76db80-cca8-11eb-925c-b737fd72758c.png)

- We can visualize the bike ride use for each hour during August. The top six hours ranked by highest volume of bike use are highlighted here as 8am-9am and 4pm-7pm. This information is a good indicator for when you want to place bikes and when to perform maintenance on them.


![NYC Startimes map](https://user-images.githubusercontent.com/78178900/121843875-ae8d4d00-cca8-11eb-99ff-7471f693f902.png)

- This is a map of New York City that shows the most popular and unpopular startimes for bike rides. As noted, there are quite a large amount of tourists that travel to NYC from all over the world and this could be why the use seems so high in this area. This is a good indicator of a few things: this can tell us the best places to place bikes for users, it can also be an indicator of new places to place bikes and measure success, finally this could be a good indicator that cities known for its tourist population may be a good location to place a fair amount of the fleet of bikes.


![Number of rides and duration](https://user-images.githubusercontent.com/78178900/121843918-bf3dc300-cca8-11eb-9276-f418217c2499.png)

- This shows the correlation between the number of bikes used and the duration of time it is used for. The line begins at zero and each marker leads up to the peak: 5 minutes. The increasing number of rides from 1min duration to 5min duration is almost equal to the decreasing number of rides from 5min to 15min; nonetheless, this appears to show that the majority of rides are between 1 and 15 minutes. A smaller graph may show that it would be skewed to the right.


![Checkout times by gender](https://user-images.githubusercontent.com/78178900/121843949-cfee3900-cca8-11eb-858c-3a527225aa15.png)

- We can see that the MALE population is the clear dominant user of the bike, FEMALE following second. It is noteworthy that there are ~8k Unknown users; however, that data would not be enough to overturn the current dominant user group. Knowing that the MALE population is the dominant group could help with marketing campaigns. 


![Trips by weekday per hour](https://user-images.githubusercontent.com/78178900/121843992-dd0b2800-cca8-11eb-8a99-b0a918d02c30.png)

- As shown in the August Peak Hours at the beginning of the story, this portrays the same conclusion: peak hours are 8am-9am and 4pm-7pm. Interestingly though, Wednesday shows a drop in the usual (comparing to the first chart) popular demand for its evening hours and then Thursday morning shows an increase in its usual popular demand at 8am. 


![Trips by gender (weekday_hr)](https://user-images.githubusercontent.com/78178900/121844051-f3b17f00-cca8-11eb-91bd-6d8dd4a75657.png)

- Now we can see that the majority of MALE users and FEMALE users fall within the peak usage hours but the UNKNOWN population lacks a clear popular time. The same patter for the lack of demand on Wednesday evening and increase in demand on Thursday morning is portrayed here as well.


![Trips by gender weekday](https://user-images.githubusercontent.com/78178900/121844085-0330c800-cca9-11eb-8193-670f481213d4.png)

- It would appear that the customer use does not indicate a clear peak or valley for demand of use. Meanwhile, it is clear that MALE Subscribers use it the most. So, to begin the new bike-sharing venture it would be advisable to have a heavy marketing campaign geared towards MALE population; however, marketing to FEMALE population (or both simultaneously) could increase the demand for that particular demigraphic as well.


## Summary

- Overall, it appears that the MALE population would be a good target market to begin the new venture. Deploying bikes in major city areas that tend to see a higher foot traffic of travelers and tourists, ensure availability from 8am to 7pm. According to the data, these decisions would be advisable to generate a high volume of use upon initial fleet deployment. 

- Two visualizations I suggest for future analysis:
  
  - With this data I would also like to see the bike utilization chart that was created before we formated the 'duration' column with the 'to_datetime(... , unit 's')' format:

  ![Bike utilization](https://user-images.githubusercontent.com/78178900/121846773-2bbac100-ccad-11eb-8b53-798936a8a9d8.png)


  - The second visualization I suggest for future analysis is the Gender use by Birth Year. This chart indicates what looks like a discrepency in the data: it shows all of the UNKNOWN population as having a birth year of 1969.
  
  ![Gender use by Birth Year](https://user-images.githubusercontent.com/78178900/121847631-7be65300-ccae-11eb-837f-340be2c2d7f9.png)

