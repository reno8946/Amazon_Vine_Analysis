# Amazon_Vine_Analysis

## Overview of the analysis:

The purpose of this challenge is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I'll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I'll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results:

* Total Paid Vine Reviews

![image](https://user-images.githubusercontent.com/70483866/103340507-df0a6300-4a49-11eb-932d-71a6442b2438.png)

* Total Unpaid Reviews

![image](https://user-images.githubusercontent.com/70483866/103340613-1842d300-4a4a-11eb-9f1e-da8b7684efbc.png)

* Total 5 Star Paid Vine Reviews

![image](https://user-images.githubusercontent.com/70483866/103340707-5e983200-4a4a-11eb-93b1-6fcd04c7e12d.png)

* Total 5 Star Unpaid Reviews

![image](https://user-images.githubusercontent.com/70483866/103340758-7ff91e00-4a4a-11eb-8845-ad78219c836e.png)

* Percentage of 5 Star Paid Vine Reviews

![image](https://user-images.githubusercontent.com/70483866/103340818-b20a8000-4a4a-11eb-8c92-a48e42b4dd66.png)

* Percentage of 5 Star Unpaid Reviews

![image](https://user-images.githubusercontent.com/70483866/103340849-c8b0d700-4a4a-11eb-91d7-9635e9b8deeb.png)

* Paid vs. Unpaid Reviews

![image](https://user-images.githubusercontent.com/70483866/103340990-32c97c00-4a4b-11eb-87b7-863f7850630f.png)

## Summary: 

Based on the results generated for the baby data set, the data shows that there was not a positivity bias towards paid vine reviews as nearly 48% of the unpaid reviews were 5-star as compared to nearly 44% total 5-star reviews for the paid reviews. Overall, there was not much of a difference between percentage of 5 star reviews between both paid and unpaid reviews. However, it is important to keep in mind that there were nearly 54 times as many unpaid total reviews as compared to paid total reviews and nearly 60 times as many unpaid total 5-star unpaid reviews as compared to total 5-star paid reviews. It might be worth looking into whether performing an analysis by each product returns a differential impact on reviews between paid and unpaid reviews.
