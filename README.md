
# Overview of Project


Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, our customer ( Louise )  wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset we can visualize campaign outcomes based on their launch dates and their funding goals.
Client wants trends of theaters and plays to determine the successful, failed, and cancelled campaigns.

## Deliverables 

| Deliverables      | Description |
| ----------- | ----------- |
| Deliverable 1      | Outcomes Based on Launch Date Chart       |
| Deliverable 2       | Outcomes Based on Goals Chart        | 



# Analysis and Challenges


## Analysis on Outcomes Based on Launch Date Chart 

For the first deliverable `Outcomes Based on Launch Date Chart`  clients need the data by the Theater category. I created the Pivot table for Outcome based on launchdate. 
We created 2 filters by Category and Year ( The derived columns based on the data provided ). For a selected year and the category we can predict the campaign outcomes. 
The rows shows the month for the given year selected for a Category and columns consist the campaign status ( Failed, successful, cancelled). 
As per the chart analysis , we can confirm that the May and June are the best campaign which have successful results. We noticed that May and June months have maximum theater campaign. Based on the analysis we can confirm that May 67% success rate and the Dec month have the least success rate 49%.



![image](https://user-images.githubusercontent.com/22928255/185519779-f4f2967e-47fd-4551-9e4d-b7ee3a322c1c.png)

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/22928255/185519720-19cf58b5-a920-4851-8a74-3ca513aeea5c.png)

![SucessPercentage](https://user-images.githubusercontent.com/22928255/185519931-1c1f0885-5efd-4b70-a910-1d4ae7ecc76a.png)




## Challenges faced: on Outcomes Based on Launch Date Chart 

There was no challenges/difficulties while performing this particular analysis. If client need further analysis on this category that may drive to the difficult level up.
1. Include the analysis for backers for each campaign
2. Duration for the Theater campaign generating more fund.
3. Analysis for understanding for failed campaigns



## Analysis on Outcomes Based on Goals Chart

For the second deliverable `Outcomes Based on Goals Chart`  clients need the analysis for the past campaigns based on the Goal amount.
client provided the funds distributions ( By goal range ) in the increment of 5000$ on the range of 5000 and up and two ranges 0-1000 & 1000-4999.
Below two graphs for fundraising campaigns represent the successful , failed and cancelled campaigns and their Percentage.


As the analysis of the graph we noticed that the fundraisers less than 1000$ have 76% success rate and between 1000-5000 had 73% success rate.
Based on the graph we noticed that if the fund goal is increasing more than 40K it is likely to failed. 

If a fundraisers want to raise the fund with greater goal , it should be divided in multiple campaigns to successful. 

![image](https://user-images.githubusercontent.com/22928255/185522482-5f4970f3-2a33-44b9-b674-73ef12f75ef4.png)

 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/22928255/185522297-8ccfe2ff-8d15-49a7-84dc-8c468c4c59ee.png)


## Challenges faced: on Outcomes Based on Goals Chart

There was no challenges/difficulties while performing this particular analysis. If client need further analysis on this category that may drive to the difficult level up.
1. Include the analysis for backers 
2. Duration for the campaign which generate more fund .
3. Analysis by year / Month for this campaigns.




# Result 

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    - The Fundraisers started in May/June have high probability to succeeding.
    - The Fundraisers should avoid the Dec for starting a Fundraisers campaign .

- What can you conclude about the Outcomes based on Goals?

    - Any Goals that are less than 5000$ have high Percentage to be successful. 

- What are some limitations of this dataset?

    - This data set is divided in multiple country and should have more data. We need to consider the geographically        comapign pattern.

- What are some other possible tables and/or graphs that we could create?

   -  Outcomes by country of launch
   -  Bakers for each campaign and their avg share to contribute.
   -  Duration for a comapign. 

