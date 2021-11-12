# Ford GoBike System Dataset Exploration
## by Mustafa Moneer


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in February 2019. There are 174,952 bike-share prosses occurred in February 2019 in San Francisco Bay Area only. The dataset came originally with 16 features like (trip durations, start snd end dates and stations, station names, ids, longitude and latitude, users' type, gender, and age, and whether they bike-share for all trips or not. Most variables are numeric in nature, but there're other categorical variables as well. Of course, after data cleaning the dataset there are some changes in order, shape, and data-type. There is 4607 bike in the dataset, the 163544 Subscriber, Customer 19868, 130651 Male, 40844 Female.


## Summary of Findings

### Here's what I have found during the data alanysis prosses of Ford GoBike's Feb 19 data:

1. Users type distributed as **90.5%** subscribers and only **9.5%** are customers.
2. Member gender distributed as **74.6%** are males, **23.3%** are females, and **2.1%** are other gender.
3. The average age of Ford GoBike's members are **33.5**.
4. The top bike frequently used is the bike the the id number **4794** with **176** trips on Feb 19.
5. The rush time for Ford GoBike during the day are **8am** and **5pm**.
6. The average trip duration takes **10.5** minutes. and the most frequent trip time is **4.5** minutes.
7. the top frequent station to begin a trip has **3626** start. The station's id number is **58**. On the other hand, the top frequent station to finish a trip has **4552** end. The station's id number is **67**.
8. Lastly, **90.3%** o not share, and only **9.7%** do share.
9. The top 20 bikes of February 2019 we can see clearly that the most bike used frequently is the bike with id: **4794**. Also, in a regression model, the most frequent time of using the same bike during Feb (19) are between **152-161** trips.
10. There's a strong correlation between the start and end hours by **98%**, and a weak correlation between start and end stations by **34%**. I think it tells us that interestingly there is a recurring pattern by Ford GoBike's members to observe in the bay area of San Francisco.
11. Tuesday has the least duration time, and Saturday has the most. Sunday has the lowest bike trips. Looks like people mostly use this service to go to work.
12. The most active **morning** (start trip) hours are at **8am-9am** and **late- afternoon** at **5pm-6pm**, and the most active days are every day but weekend during the rush hours. That's confirmed my theory that most people in the bay area, San Francisco use Ford GoBike's service to go to work. The same goes for (end trip).
13. Most active **females** with Ford GoBike are **29 years old**, the most active **males** are **32 years old**, and the most active **LGBT** are **36 years old**.
14. Most active **customers'** age are **30 years old**, and the most active **subscribers'** age are **31 years old**.
15. All genders are most active on **Thursday**.
16. Customers and subscribers are most active on **Thursday**.
17. **Males** make the largest segment of customers and subscribers alike.
118. Most variables are concentrated between **4-16** in relation to duration (min) and between **25-35** in relation to age.
19. **Customers** have a higher average of trip duration in minutes than subscribers, and **male** customers are the highest among other genders.
20. **Weekend** has the highest average of trip duration in minutes for all members' gender both customers and subscribers.


## Key Insights for Presentation

> the average trip duration is 11 minutes which is reasonable as the average bike speed is between 22.5-24 km/h which means that on average it takes bikers 11 minutes to cut a distance of 4.3 to 4.6 km. Also, the average members' age is 36. Lastly, bike-sharing on average start and end at noon. Also, the maximum ride duration is 1409 minutes that's 23.48 hours, obviously, it means that the company must have a policy that obliges its members from keeping the bike for more than 24h!

> There're no correlation in general between trip duration time and the trips start day, but the correlation getting stronger at the first 60 minutes, meaning that members mostly don't keep the bike over one hour. There were a perfect correspond between start day and end day in relation to ages and duration (min) in a log scale.

> Interestingly, customers has the higher average of trip duration in minutes then subscribers, and males customers are the highest among other genders. and for both user type and member gender, weekend has the highest average of trip duration in minutes.