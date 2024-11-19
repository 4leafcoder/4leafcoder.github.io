### Data Professional Survey Analysis

Over the past few years, data jobs have exploded. Data Engineers, Analysts, Architects, and others each play a crucial part in the end to end data analysis process. A data professional, known as "Alex the Analyst" posted a survey to his online community asking for information from other data professionals about their job titles, salary, and location among other things. There were 630 responses before the survey was closed. So what can be learned from this data? 
To conduct my analysis, I used PowerBI to analyze responses to the survey. 

First, I created some questions to answer with the data.

-What is the average salary reported for each Job Title?

-Which Programming language is preferred by each role?

-Which role has the best work/life balance?

-Did happiness with salary or work/life balance vary by country?


With these questions in mind, I dove into the data. I received the data set in a CSV file which I loaded into PowerBI. I then formatted and cleaned the data to my needs. For example, several of the questions offered an "Other" option where users could answer in free text. This created a lot of varied responses. I chose to standardize the free text responses to all be categorized as "Other." 

The salary information collected also needed to be cleaned. The survey provided response choices of salary ranges (0-40k, 41-65k, etc). From an analysis perspective, the ranges are difficult to work with. To resolve this, I took the average of each range and created a column with those values. If a user reported their salary was between 0-40k, the average of that range is 20k. I created an average salary column with the averages from the range chosen by the user. Once the data was cleaned and formatted, I created a dashboard to provide answers to the questions of interest.

Here is a quick look at the overall dash.
<img src="images/2024-11-14_16h06_18.gif?raw=true"/>

From this dashboard, I was able to find the information I was interested in. 
Looking at the average salary, I found that overall, Data Scientists had the highest salaries. However, slicing the data by country revealed that Data Scientist is not the highest earning title globally.  I also discovered that the job titles may not exist in all countries. In India, for example, the title of Data Architect was not reported at all. Since this is a small data set (only 73 respondents from India) more data is certainly necessary to draw any conclusions around this.
<img src="images/salary gif.gif?raw=true"/>

Another aspect I was interested in was which programming languages were most popular among each job title. Overwhelmingly, Python is the preferred choice among all job titles, especially data analysts. 

![2024-11-19_13h51_57](https://github.com/user-attachments/assets/ada1e1ce-7887-432f-a412-d762c613e310)
