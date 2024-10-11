## DoorDash Deep Dive

<img src="images/DDPICbig.png?raw=true"/>

On a recent trip to New York City, I walked about 10 miles each day exploring the city, which is about double my daily average. On the second day of the trip, I was pretty tired and dreaded the idea of walking a few blocks for dinner. Then I remembered delivery apps exist! I opened DoorDash and ordered some tacos. While waiting for my order, I wondered who else would have resorted to a delivery app. Would younger people make the walk? Do older people use DoorDash more? Fortunately, there’s data we can look at to find some answers. The data set available to me is from an app called iFood. For this project, I worked in Excel and used aggregate formulas, IF statements, and pivot tables to compare data.

A couple of notes about the data set:

  -It contains user data for a sample of 2,205 iFood app users.

  -Information collected includes age, annual income, amount spent in last 2 years, education level, marital status, marketing campaign responses.

  -Users range from age 24 to age 80.
  
  -The data set was provided for an interview exercise and can be found [here] (https://github.com/nailson/ifood-data-business-analyst-test/blob/master/ifood_df.csv)


First, I broke down the customer sample into age groups to gain some insight into iFood app users. I created 4 age groups using IF statements to categorize users.  The chart below shows that the largest group of users (42%) are between ages 36-50, while the fewest users are aged 24-35.

<img src="images/DD-agegroup.png?raw=true"/>

This information could be used to determine who the target users are. Should iFood work to attract more users in the younger demographic? Or should they focus on targeting the group with the most users? To help answer this question, I looked deeper into the behaviors of each group. 

First, I looked at the spending behavior of all age groups and the annual income. 

<img src="images/DD-incomeage.png?raw=true"/>

Here we can see that the average annual income increases with age. We can also see that users in the older age groups spent a higher percentage of their income on iFood, likely because of their higher earnings. 

So, does age influence spending, or does income? The scatterplot below shows us that there are a few outliers, but consistently, users who earn more annually, spend more on the service. Age is not necessarily a driving factor as to who will use iFood, but instead, it appears that income is a stronger factor.

<img src="images/DD-incometotalspent.png?raw=true"/>


Based on the analysis so far, we can see that the bulk of iFood users are in the two middle age groups, between 36-65. These users also have steady incomes that appear to be increasing with age. Looking at spending habits by user age supports focusing efforts to maintain these customers and acquire users in these demographics.
