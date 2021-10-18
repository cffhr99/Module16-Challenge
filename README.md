# Module16-Challenge: Amazon Review ETL
## Overview of the analysis
A dataset of office product was selected to performan the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance and load the transformaed data into pgAdmin by using PySpark. Then, PySpark was selected to determine if there was any bias toward favorable reviews from Vine members in office product dataset.
## Results
### From the filtered dataset, the folloing picture showed the total reviews, paid reviews and unpaid reviews:
![total_reviews](https://github.com/cffhr99/Module16-Challenge/blob/main/img/Total_review.png?raw=true).   
![total_paid_unpaid](https://github.com/cffhr99/Module16-Challenge/blob/main/img/Total_Paid_Unpaid.png?raw=true)

### The table below is the number of paid/unpaid reviews with 5 star rating.
![5Star_paid_unpaid](https://github.com/cffhr99/Module16-Challenge/blob/main/img/5Star_Paid_Unpaid.png?raw=true)

### The table below is the percentage of paid/unpaid reviews.  
![percentage of paid and unpaid](https://github.com/cffhr99/Module16-Challenge/blob/main/img/Paid_Unpaid_Percentage.png?raw=true)
## Summary
### Conclusion:
From the results above, there is not strong bias toward five-star reviews from paid Amazon Vine reviewers on office products dataset.
### Additional Analysis:
The table below is the average rating star between paid and unpaid Vine reviewers:
![average_paid_unpaid_rate](https://github.com/cffhr99/Module16-Challenge/blob/main/img/Paid_Unpaid_Rate_average.png?raw=true)
The table above shows there is no significant difference between the average rate of paid and unpaid reviewers` star rating.
