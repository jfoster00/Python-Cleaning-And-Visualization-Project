# Ford GoBike Analysis 
## by Justin Foster


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area called "Ford GoBike". Ford Gobike was created by the Ford motor company in partnership with the company "Motivate" and introduced to the San Fransisco Bay Area in 2017. The goal of the system is to help reduce traffic congestion in the city by providing an alternative mode of transportation. More information on this system can be located on Ford's media website [HERE](https://media.ford.com/content/fordmedia/fna/us/en/news/2017/06/27/ford-gobike-launching-in-bay-area-bike-sharing.html).

After cleaning the original data set, there are 174538 listed trips that went into my analysis


## Summary of Findings
I wanted to have a loose goal for exploration in mind before cleaning my dataset. It was my assumption that I could help build efficiency if I were to clean up the fields of data I wished to focus on first before trying to plot the data. I found this to be a very helpful way to find the theme I wished to explore. I decided I wanted to observe different features of the two types of users of Ford GoBike and see how or if they differed from one another in qualitative and quantitative metrics. The two different user types were Subscribers and Customers.

#### Univariate exploration: 
I used this section to look at the composition of user base as a whole. I found that 91% of trips taken were Subscribers and 75% of those trips were taken by male gendered users. Only 10% of trips were taken by low-income status users. The largest concentration of users appeared to fall between the ages of 25 and 35 years old and user's trips were mostly concentrated between 4 to 8 minutes. Lastly, each weekday saw a fairly similar number of trips with the weekend seeing a large dip in number of trips taken.

#### Bivariate exploration: 
In this section I began to pair up features. When starting this section, I was mostly curious about looking into low-income status information. I had found that trips taken with low-income status were predominantly taken by male users. I decided this was a dead end however as only Subscribers could have information in this feature since the status only applies to those getting the "Bike Share For All" discount which Customers can not get. Due to this, I ceased looking further into this feature. I then decided to focus more intently on gender differences between the two user types moving forward. I found that the trends of the overall user base in terms of gender composition applied to both Customer and Subscriber user types. Males comprised of about 75% of both types and females/other comprised of about 25%. I also took a look at differences in numbers of trips between Customers and Subscribers. I found that Subscribers had a little more variance in each day of the week than Customers did but both user types took the most trips on Thursdays as the univariate info showed. I was suprised to see Customers stayed consistent over weekend days, however Subscribers took about half as many trips on the weekend days. When checking the correlation between age and minutes taken per trip, I found there was very slight negative correlation. Finally, I found that Customers and Subscribers had very close average ages of aroun 34 years old. Customers and Subscribers visibly differed in their average trip time in minutes with Customers having an average trip time of about 15 and a half minutes while Subscribers had an average of about 9 and a half minutes. 

#### Multivariate exploration: 
While I planned to now focus on gender in regard to user type similarities and differences, I knew I would need to utilize more features to further narrow down these similarities and differences. Since my primary (user types) and secondary (gender) metrics were both qualitative, I wanted to make sure any further features added in my multivariate exploration were quantitative. This led me to plotting the average age and trip time for each gender separated by user type. I found that on average, in both user types, in order from youngest to oldest average age was:

* Female: About 32.5 years of age. 
*   Male: About 34 years of age.
*  Other: About 34.5 years of age.
        
When comparing the different user types seperated by genders based on average minutes per trip, I found there were some differences of note between genders as well as user types. Firstly, all genders matched the same trends as seen in the bivariate exploration of average minutes per trip in that all Subscribers, regardless of gender, took less time on their trips than Customers did. However, time taken by each gender inside each user type was different. Below are the rankings from lease time to most time per gender per user type:

Subscribers:
*   Male: About 9 minutes. 
* Female: About 10 minutes.
*  Other: About 11.5 minutes.

Customers:
*  Other: About 14.7 minutes. 
*   Male: About 15 minutes.
* Female: About 17 minutes.

## Key Insights for Presentation

I will be presenting the Ford GoBike user type general information. I will present the pie charts showing the composition of the entire user base first. These will consist of pie charts for user type division and gender division respectively. I will then build upon those base line setting plots by presenting a clustered bar chart indicating gender composition for both the Customer user type as well as the Subscriber user type. From there, I will end key insights by further building on top of the previous plot with two more cluster bar charts to indicate average user age and trip time in minutes for each gender in the Customer and Subscriber user types. 




