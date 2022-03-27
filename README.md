# kickstarter-analysis
## Overview of Project

Purpose of this analysis to help Loiuse to raise fund on her play *Fever* which came close to it's fundaraising goal.
By using the Kickstarter dataset, we will analysis data and present them to Louise to see if there are any specific
factors that she can use to make her campain successful.    
          
## Analysis and Challenges

In order to perform the analysis for Louise I use conditional formatting on Outcome column to visualize it better,
there are four categories in outcome column, Successful, failed, canceled and Live. I applied **conditional formatting**
and highlight each outcome with different colors.
To figure out the percentage of a campaign funding I added new column named Percentage Funded.
Added Average Donations column to help Louise set up her incentives by looking at the amount pledged previously by people.
Added two more columns to split parent category and subcategory from category and subcategory column by using the text to column option.
![Text to Column](https://github.com/Hanitapatel/kickstarter-analysis/blob/main/Analysis_Images/Text%20to%20column.png)

Creat pivot tabls to summerise and visulize data better. Created piviot table into category statestic tab to see how all the fundraising category perfom. 
This pivot table help summrise outcomes by category and by looking at the table we can say that theater has 
most amout of successful kickstarters and Journalism has least
amout of kickstarters. We can filter it by country if we like to visualize outcomes by countrie.  
![Parent category outcome pivot](https://github.com/Hanitapatel/kickstarter-analysis/blob/main/Analysis_Images/parent%20category%20outcome%20Pivot.png)
        
 Adding chart in pivot table provided much better view  analysing outcomes by each category.
![Parent category outcome chart](https://github.com/Hanitapatel/kickstarter-analysis/blob/main/Analysis_Images/parent%20Category%20outcome%20chart.png)
               
Added two more columns Date created conversion and date Ended Conversion to convert the launched date and 
         deadline date from Unix timestamps to readable format which will help Louis to plan her campaign timeline by comparing
         length of campaign in dataset.
![Unix Timestamps](https://github.com/Hanitapatel/kickstarter-analysis/blob/main/Analysis_Images/Unix%20timestamps.png)
         
 ## Analysis of Outcome based on Launch Date 
 
Analysis based on Launch Date will help Louise to consider the time and length of her campaign. To present the 
          outcome by Launch Date I created the Pivot table which contain outcomes, Date Created Conversion, Parent category and
          years columns. Adding Line chart help Louise visualizes trends.
![outcome by launch date pivot](https://github.com/Hanitapatel/kickstarter-analysis/blob/main/Analysis_Images/outcome%20by%20launch%20date%20pivot.png)
![outcome by launch date chart](https://github.com/Hanitapatel/kickstarter-analysis/blob/main/Analysis_Images/Outcome%20by%20launch%20date%20chart.png)
          
From the chart above we can see that most successful campaigns were in May and month of December wasn’t a good
          month for campaign. Month of January, June, July and October has same number of failed campaigns, so those months were
          not good months for campaigns.
 ### Theater Outcome by Launch Date       
      
                  
Theater outcome by Launch Date provide the information about outcomes for the theater category. Conclusion based
           on that pivot table and Chart
* Theater category has total of 839 successful companies. Month of May and June were the great months for this campaign. May has 111 and June has 100      successful campaigns. Based on that data, campaigns for the Theater category will most likely get successful outcomes if they are launched in these two months. 
* October and December were the worst month for this category. Based on the outcome we can see that in October out of 115 campaigns 65 were successful and 50 were failed and in December out of total of 75 campaigns only 37 were successful and 35 were failed.

## Analysis of Outcomes Based on Goals 

By outcomes based on goals analysis we can help Louise to determine her funding amount to run the successful campaign.
* Based on the outcomes by the Goals, we can see those campaigns with funding amount less than or equal to $4,999 are more successful than any other funding amount. Also goals between the $35,000 to 44,999 also has greater success but there were only 9 projects that falls under that category.
So, most likely Louise will succeed in her campaign if she set her funding goal less than $5000.

We could add successful and failed percentage on outcomes based on theater category sheet which could provide in failed and successful rate based on total amount of campaigns. In same sheet I think bar chart would help better than line chart. 
