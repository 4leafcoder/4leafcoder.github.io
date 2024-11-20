### Data Professional Survey Analysis

When I think of surveys, I can't help but think of the hosts of Family Feud saying "We surveyed 100 people..." and "Survey Says?!" And while entertaining, it is also a good example of how survey responses vary based on those targeted. For example, surveying attendees of a Family Feud taping about their favorite game show will likely yield different results than asking those attending a Jeopardy taping. Therefore, when looking at survey data, it is always important to also consider the group participating. For this project, I am looking at data collected from a survey targeted at data professionals. Specifically, those who interact with the YouTuber "Alex the Analyst." There were 630 responses before the survey was closed. 

So what can be learned from this data? 
To conduct my analysis, I used PowerBI to analyze responses to the survey. 
First, I created some questions to answer with the data.

-What is the average salary reported for each Job Title?

-Which Programming language is preferred by each role?

-Which role has the best work/life balance?


With these questions in mind, I dove into the data. I received the data set in a CSV file which I loaded into PowerBI. I then formatted and cleaned the data to my needs. For example, several of the questions offered an "Other" option where users could answer in free text. This created a lot of varied responses. I chose to standardize the free text responses to all be categorized as "Other." 

The salary information collected also needed to be cleaned. The survey provided response choices of salary ranges (0-40k, 41-65k, etc). From an analysis perspective, the ranges are difficult to work with. To resolve this, I took the average of each range and created a column with those values. If a user reported their salary was between 0-40k, the average of that range is 20k. I created an average salary column with the averages from the range chosen by the user. Once the data was cleaned and formatted, I created a dashboard to provide answers to the questions of interest.

Here is a quick look at the overall dash.
<img src="images/2024-11-14_16h06_18.gif?raw=true"/>

From this dashboard, I was able to find the information I was interested in. 
Looking at the average salary, I found that overall, Data Scientists had the highest salaries. However, slicing the data by country revealed that Data Scientist is not the highest-earning title globally.  I also discovered that the job titles may not exist in all countries. In India, for example, the title of Data Architect was not reported at all. Since this is a small data set (only 73 respondents from India) more data is certainly necessary to draw any conclusions around this.
<img src="images/salary gif.gif?raw=true"/>

Another aspect I was interested in was which programming languages were most popular among each job title. 

![2024-11-19_13h51_57](https://github.com/user-attachments/assets/ada1e1ce-7887-432f-a412-d762c613e310) 
The chart above uses a stacked bar chart to show the popularity of each language by job title. Overwhelmingly, Python is the preferred choice among all job titles, especially data analysts. One thing I was disappointed in was that SQL was not an option on the survey. Instead, users added it in the "other" field but in many variations (SQL, Structured Query Language, MySQL, etc). I feel like this was a missed opportunity as it's a popular language, though some may argue it is not a programming language.

Now let's look at the last area of Ineterst: Work/Life Balance. 
![2024-11-20_09h47_30](https://github.com/user-attachments/assets/c76f7480-4ce7-4001-9060-e17a3b9be3e7)
here we can see that Students or those looking for a data job are the least satisfied with work/life balance. This makes sense since they are not in active data roles. We can also see that most of the roles are near the average rating, with only about .5 point variation at most. Data Architects are the least happy with work-life balances, but interestingly very satisfied with their salary. 

I enjoy looking at data in dashboards and visualizations because it allows so many relationships to be on display at once. Visualizations can lead to new questions and deeper analysis. While this project looked at a very focused set of data, I really enjoyed looking at the relationships between job title, salary, work/life balance, and location! 
