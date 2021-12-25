# Kickstarting with Excel

## Overview
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset we will visualize campaign outcomes based on their launch dates and their funding goals. In this repo you will find, written reports based on our analysis and the visualizations we created.

## Analysis and Challenges

### <p align="center">**Campaign Outcomes Based On Launch Date**</p> 
<img src="/resources/CampaginOutcomes-Data.png" alt="Launch Date Outcomes" width="400"> <img src="/resources/PercentageSuccess.png" alt="Launch Date Outcomes" width="400">


After analyzing the data and creating reports for campaign outcomes based on launch date, we can see that for the months from **Feburary** to **June** had the most successful campaigns. This tells us, that we will see a higher success rate and get a better result for running campagins during this months. 


However, you may notice that although **June** had a high number of successfull campaigns, it also had a high number of failed campaigns as well. Infact June was the **third** highest month of failed campaigns. To help us better understand our data visually, I decided to create a line chart displaying the percentage of successful, failed and cancled campaigns. See Below. 




As you can see, we can easily point out that months **Feburary** to **May** were the most successfull for campaign runs, floating between **57%-61%**. June however, drops to about **54%**. Which could be significant if the campaign has a huge budget and has **high impact.** 

Another important insight we can see is that from months **June** to **September** as the success rate for campaign run decresses the percentage of failed campaigns increases.

##
#### **Conculsion**: 
High budget and high impact campaigns should be run through **Feburary** to **May**, whereas low impact, low budget, low risk campagins, can be run throughout the rest of the months.  


##
### <p align="center">**Outcomes Based on Goals**</p>

<img src="/resources/Outcomes_vs_Goals.png" alt="Launch Date Outcomes">

The above line chart, viusalizes the percentage of successful and failed outcomes based on the goal amount set. Goal amount is the amount of money that was expected to be raised through the campaign. To make it easier for us to understand, I filtered the chart above to only show us data for campaigns being run under the **"plays"** category. 


Looking at the chart, there seems to be a direct relationship between failed and successfull campaign runs. It is clear that the lower the campaign goal the higher the success rate. 

We can see that Over time as the campaign goal increases the success percentage decreases and failed percentage increases. However, there is a decent spike in success rate for campaign goals ranging between **$30,000 - $44,000,** Then dropping to a **13%** success rate. 

##
#### **Conculsion**: 
Campaign goals should be aimed to be less than or equal to **$1000** or between **$30,000 - $40,000.** If your campaign goal needs to be more than $1000 and less than $30,000, then I would reccomend running multiple low goal campaigns to increase your change of success. 

##
### Challenges and Difficulties Encountered

It was a real challenge setting up the formula for **Deliverable 2.** It was quite easy to miss a coma, or quation mark and mess up the full formula. I also struggled with setting up the filters for our pivot table. Figuring out which column belongs where does take awareness and a clear understanding of what type of analysis you are trying to make. My biggest strugle or challenge was the date columns. I believe originally I skipped over the module that explained how to convert the unix timestamp to a readable date, but I went back through the modules and was able to find the solution. 

## Results
### Conclusion for Outcomes based on Launch Date
- High budget and high impact campaigns should be run through **Feburary** to **May.** 
- Low impact, low budget and/or low risk campagins, should be run throughout the rest of the months.

### Conclusion for Outcomes based on Goals
- Campaign goals should be aimed to be less than or equal to **$1000** or between **$30,000 - $40,000.** If your campaign goal needs to be more than $1000 and less than $30,000, then I would reccomend running multiple low goal campaigns to increase your change of success.

## Limitations of Dataset

There are quite a few common limitations to the dataset. **Reliability** of this dataset plays a huge role, we are not really sure if this is reliable, it may have missing data, or data inputed incorrectly due to human error. Another gap I see in this dataset comes from the person running the campaigns, for example, were there different people running different campagings? Some people may be able to run a campagin more successfully while others may not have the experience or skills to run an effective campaign. 

## Extra Tables and Charts
The following table and chart represent data based on goals with no filters.
<img src="/resources/Outcomes_vs_Goals(No_Filter).png">

The following chart shows the success, failed and cancle rate in percentage for each month.
<img src="/resources/PercentageD1.png">















