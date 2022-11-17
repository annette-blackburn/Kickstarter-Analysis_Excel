**Annette Blackburn**

  

**Purpose of Kickstarter Analyis**

 The purpose of this analysis is to provide Louise with meaningful insight to make her theatre crowdfunding campaign successful, so she can produce her play, “Fever.” The analysis focuses on the factors of other successful theatre campaigns such as date of crowdfunding launch and budget. 

  

**Analysis and Challenges**

To determine theatre outcomes by launch date, I created a pivot table of successful, failed, and canceled theatre productions by month. I filtered the data to exclude “live” outcomes and all other parent categories (games, journalism, etc.). I created a line chart to better display the results: theatre campaigns that are started in May and June are the most successful.

 To figure out the outcomes based on goal, I created a new sheet with goals, outcomes, total projects, and percentages of outcomes. I used the COUNTIF command to calculate the number of successful, failed, and canceled campaigns whose goals were less than $1,000 and greater than $50,000 (i.e., =COUNTIFS(Kickstarter Data!$F:$F, "successful", Kickstarter Data!$D:$D, "<1000”)). I watched videos on the COUNTIF command, VLOOKUP, and filters to try and sort the data incrementally (between $1000 and $4999, between $5000 and $9999, etc.), but could not figure out how to get it to work. I was able to sort the data into the goal ranges in the “Kickstarter Data” sheet, but couldn’t get it to transfer to the “Outcomes Based on Goals” sheet. Considering that Louise’s goal is $10,000, I believe that that having data on the success rate of theatre campaigns in her goal range would have been very useful.
  

https://www.youtube.com/watch?v=UcDMke1kzhU

https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9?ui=en-us&rs=en-us&ad=us

https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us

https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us
    

**Results**

**Conclusions about Theatre Outcomes by Launch Date**

 Theatre campaigns that are started in May and June are the most successful, while ones started in October have roughly an equal failure rate to success rate.


**Conclusions about Outcomes based on Goals**

Campaigns with very large goals (over $50,000) have higher rates of being canceled and higher rates of failure than those with smaller goals.  
    
**Limitations of Dataset**

While the dataset was large enough to draw meaningful conclusions (n>4000), there are only 83 theatre campaigns. Of course, a sample size of 30 or greater is sufficient to be statistically significant, but these 83 campaigns were not all from the same country and how successful theatre is varies from culture to culture. It would be helpful to analyze the data based on the country Louise wants to produce her play in and/or where she plans to advertise her crowdfunding campaign.
    
**Other Possible Tables and/or Graphs**
If we qualitatively coded the theatre campaign “blurbs” into type of theatre production (horror, comedy, romantic, etc.), we could create tables based on the most successful kind of production. This might help Louise gauge how popular her play might be and from there, whether or not her crowdfunding goal is reasonable.
