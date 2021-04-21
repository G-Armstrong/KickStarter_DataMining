# KickStarter_DataMining
A Data Science Project Investigating Features  Common to Successful KickStarter Campaigns 


**Overall task:** We decided to use the Kickstarter Dataset made available on Kaggle. This dataset is from 2018 and contains 375,765 instances with 15 attributes. We plan to determine the metrics common to successful Kickstarter campaigns. These include the category, the optimal window for funding, asking amount, the average amount contributed per backer, and the differences between the US and UK in terms of these metrics. As per suggestion on Piazza, we would also like to categorize the successful projects by type as it will allow the customer to better understand what to look for in a product they are trying to develop.
 
**Data to be used:** [Kickstarter Projects | Kaggle] -> (https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201801.csv)
Columns of interest include launched, state, main_category, category, deadline, backers, and country. The ‘state’ column names 52% of projects failed, 35% successful, and 12% other (cancelled or live).
 
**Target Customers:** This project would be targeted towards individuals that want to post on Kickstarter with the knowledge of what makes a project succeed on the platform. Another use of this project could be for people who are interested in backing or investing into a Kickstarter project, as seeing its prospective state might draw more people in.
 
**Operation:** We will primarily be using supervised classification methods. One task of interest is predicting the value of the ‘state’ column (whether or not the project succeeds) based on values of other attributes. We are thinking of using a decision tree to visualize the values of attributes that lead to success or failure. To clean the data, we will remove the ongoing/live projects but consider the canceled projects as either its own classification to be predicted or simply as a failure.
