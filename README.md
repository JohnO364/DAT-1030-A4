# DAT-1030-A4
Assignment #4 - Data Archive Activity


In this analysis, I have been looking at fictional human resources data.  Specifically I have been examining the sales department. (Information acount the data is found in the data folder)  

I began by looking at the job satisfaction level, monthly income level - rounded to the nearest thousand dollars, and attrition status.  This showed me that those with a higher job satisfaction score seemed less likely to have attrition = yes.  However, due to the 1-4 scale on job satisfaction, no more complex conclusions could be drawn at this stage. (information about transformations to the orginial dataset found in the munge folder)

Next, I looked a certain aggregations of the data. (further infomration about aggregations found in src folder) 
 - First was to look at the count of sales people with and without attrition.  I determined that nearly 4 times as many salespeople did not have attrition compared to those that did.  
 - After that I looked at the average, min, and max monthly income for salespeople both with and without attrition.  This showed that while the min and max were the same, salespeople without attrition had an average monthly income roughly $1300 more than those with attrition.
 - Lastly, I looked at the counts of salespeople, again separated by attrition status, at each rounded monthly income level.  This showed that very few salespeople with attrition had monthly income greater than 10,000 when compared to those without attrition.
 
 Lastly, I created visualizations of two of the aggregations described above. (information and actual visualizations found in reports folder)
  - A dashboard was created for to show the counts of salespeople with and without attrition.  A doughnut graph was used for this visualization.  This reinforced the idea that there were nearly 4 times as many employees without attrition than with.
  - A clustered bar graph was created to show the distribution of monthly income, with red/left bars showing the counts of non-attrition salespeople at each income level, and the blue/right bars showing those wit attrition.  This clearly indicated that there are indeed significantly more salespeople without attrition than with, and that those without attrition, on average, made more per month that those with.
