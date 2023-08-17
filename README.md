# TripleTen AB test project

## Project description
### Context
For this project, I assumed the role of an analyst at a large online store. I have worked alongside the marketing department to compile a list of hypotheses aimed at boosting revenue. Now, my task is to prioritize these hypotheses, conduct an A/B test, and analyze the resulting data.

### Description of the data
#### Data used in the first part of the project
hypotheses_us.csv
 - Hypotheses — brief descriptions of the hypotheses
 - Reach — user reach, on a scale of one to ten
 - Impact — impact on users, on a scale of one to ten
 - Confidence — confidence in the hypothesis, on a scale of one to ten
 - Effort — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

#### Data used in the second part of the project
orders_us.csv
 - transactionId — order identifier
 - visitorId — identifier of the user who placed the order
 - date — of the order
 - revenue — from the order
 - group — the A/B test group that the user belongs to
 - date — date
 - group — A/B test group
 - visits — the number of visits on the date specified in the A/B test group specified

### Part 1: Prioritizing Hypotheses

I began by analyzing the hypotheses provided in the file hypotheses_us.csv, each associated with Reach, Impact, Confidence, and Effort scores. To prioritize these hypotheses effectively, I followed these steps:

 - Utilized the ICE framework to assess and prioritize the hypotheses based on the calculated scores. I then sorted them in descending order of priority.

 - Employed the RICE framework to assess and prioritize the hypotheses, considering Reach, Impact, Confidence, and Effort. Once again, I sorted them in descending order of priority.

 - I noticed a significant shift in the prioritization when transitioning from ICE to RICE. This was expected as RICE considers the potential reach of each hypothesis, leading to changes in priorities based on their potential impact on a larger audience. I provided a detailed explanation for these changes, highlighting the significance of considering reach.

### Part 2: A/B Test Analysis

In the A/B test analysis, I completed the following tasks and drew conclusions:

 - Graphed the cumulative revenue by group, leading to observations and insights about revenue trends.

 - Plotted cumulative average order size by group, which provided insights into how the order size evolved over time for each group.

 - Visualized the relative difference in cumulative average order size between group B and group A, helping me draw conclusions about the effect of the changes on average order size.

 - Calculated and plotted the daily conversion rates for both groups, showcasing the difference between the groups and making conclusions about their conversion behaviors.

 - Created a scatter chart depicting the number of orders per user, leading to insights about user behavior and potential outliers.

 - Determined the 95th and 99th percentiles for the number of orders per user, allowing me to identify anomalies.

 - Generated a scatter chart for order prices, leading to observations about the distribution of prices and potential outliers.

 - Calculated the 95th and 99th percentiles of order prices, establishing thresholds for identifying anomalous data points.

 - Assessed the statistical significance of the difference in conversion rates between groups using both raw and filtered data, drawing conclusions about the impact of the changes.

 - Similarly, evaluated the statistical significance of the difference in average order size between the groups using both raw and filtered data, drawing relevant conclusions.

 - Finally, based on the comprehensive test results, I made a well-informed decision regarding the next steps for the test, considering options such as stopping the test and declaring a leader, stopping the test due to lack of difference, or continuing the test based on the observed outcomes.



## Screenshots

![image](https://github.com/elem86/AB_test_project/assets/48759327/ca54dde9-a5a1-49ee-a833-12cc9c69a738)

![image](https://github.com/elem86/AB_test_project/assets/48759327/a96ded24-22d9-4903-ba34-b50518636d04)

![image](https://github.com/elem86/AB_test_project/assets/48759327/8330a0b2-8d66-4365-b40b-d6654e0c6038)

![image](https://github.com/elem86/AB_test_project/assets/48759327/8ec261e8-78dd-4d07-b831-be08556dc992)




