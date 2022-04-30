# Amazon_Vine_Analysis
use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin

## Overview
In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Utilities
We will be using `Google Colab`, `Amazon Web Services`, `PostgreSQL`, and Python's`PySpark` 

## Results 
* Paid Vine DataFrame: 

<img width="1379" alt="Paid Vine DF" src="https://user-images.githubusercontent.com/95068439/163657495-fc224e4a-e6c5-42e8-804c-a0b2ed956e5b.png">

* Unpaid Vine DataFrame:

<img width="1335" alt="Unpaid Vine DF" src="https://user-images.githubusercontent.com/95068439/163657507-994b5b8f-4fd6-4512-b358-6f7985243b20.png">

* **How many Vine reviews and non-Vine reviews were there?**

<img width="1352" alt="Total # of Reviews" src="https://user-images.githubusercontent.com/95068439/163657403-226bfc93-96bb-4e49-90d3-be305c20a3a0.png">

> The total number of video games reviews from the VINE is 94 

> The total number of non-VINE reviews is 40,471.

* **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

<img width="847" alt="Total 5 Star" src="https://user-images.githubusercontent.com/95068439/163657645-bf71a6be-2417-4376-bf01-8fe840fc4c8c.png">

> Out of 94 VINE reviews, the datasets have 48 5-Star reviews

> Out of 40,471 non-VINE reviews, the datasets have 15,663 5-Star reviews

* **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**

<img width="895" alt="Pct 5 Star" src="https://user-images.githubusercontent.com/95068439/163657734-073bd9c3-239a-42c1-a3a2-80eaba016960.png">

> The percentage of 5-Star VINE reviews is approximately 51.06 %

> The percentage of 5-Star non-VINE reviews is approximately 38.7 %

## Summary 

The majority of reviews for the video games product are coming for non-VINE participants with 40,471 non-Vine reviews while there are only 94 reviews from VINE participants. Overall, majority of the 5-Star reviews are coming from the non-VINE participants but we need to highlight that not all of the 5-Star reviews are coming from non-VINE participants. There might be a bias from the non-VINE participants but we need to perform additional analysis to have a deeper understanding. 

> LinkedIn: https://www.linkedin.com/in/wilson-alexei/

> Email: wils.alexei@gmail.com
