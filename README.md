# Call Center Analysis
## Introduction
The objective of this analysis is to reveal hidden insights from the provided dataset of a call center. 
## Data Description
The dataset was sourced from kaggle.com, a free data source where data are shared. The data is a fake real-life type which implies that the data was randomly generated by a user but it is like a simulation of what can be obtained in real life. 
The data consist of 12 columns and 32,941 rows. Nine of the columns are in text format, two are in number format and one is in date format.
## Methodology
The data was cleaned with Power Query and it was visualized with Microsoft Power BI. Cleanong was done particularly on the call_times column where I used locale to correctly get the date, time and day that each call was made.
## Results
Approximately 33,000 calls were made and the average duration of the call was 25 minutes. The most used call channel was the Call Center and the least was Web. Most of the calls were responded to within SLA which indicated that very little customers called were delayed suggesting that improvements can still be done. However, most of the feedbacks obtained from the customers are negative indicating that either their problems were not solved or they were not responded to properly. 71.22% of the customers called to enquire about Billing, it could be as a result of unexpected deductions or other reasons and this can be curtailed by sending SMS or mails to the customers as to why they were billed. The least calls came from customers who complained about Service Outage (14.36%). The major summary of this visualization is that a lot of customers calling to make enquiries were not satisfied as the summation of the "Negative" and "Very Negative" sentiments outnumbers the amount of Positive and Very Positive sentiments significantly.
The Call Center slicer can be used to obtain visuals from each of the four Call Centers.
The second page contains a decomposition tree which can be used to drill down and analyze across State, Channel, Reason and Sentiment of the customers.
## Conclusion
The objective of this project was achieved as hidden insights were unlocked which can aid strategic decisions to be taken.
### Tools Used 
- Microsoft Excel
- Power Query
- Power BI
