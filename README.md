# Amazon_Vine_Analysis
## Overview:

Big data is viral in the industry now, for example, for social media, stock markets, and many more.  It’s an extensive, more complex collection than traditional data. Within big data and Hadoop, we learned about MapReduce and how it helped improve the process and handling of big data.  And then, we learned about Byspark, which has become the leader in technology in handling big data.  
Things covered in this module:

  •	Define big data and describe the challenges associated with it.

  •	Define Hadoop and name the main elements of its ecosystem.

  •	Explain how MapReduce processes data.

  •	Define Spark and explain how it processes data.

  •	Describe how NLP collects and analyzes text data.

  •	Explain how to use AWS Simple Storage Service (S3) and relational databases for essential cloud storage.

  •	Complete analysis of an Amazon customer review.

## Analysis:

The purpose of this project was to work on a large project called the “Amazon Vine Program.” The program is a service that allows manufacturers and publishers to receive reviews of their products and determine if there is any bias between Vine members and non-Vine members.  Companies like SellBy pay a small fee to Amazon and provide free products to Amazon Vine members, who, in return, are required to post a review of the product.  So, To determine if there are any biases in the reviews between Vine members and non-members, we were asked to choose between 50 datasets to extract, transform, and load into a data frame to complete our analysis. 

    1.	We used PySpark to connect to Amazon AWS RDS, extract the dataset, and transfer data.

    2.	Google collab to import Pyspark, connect to PostgreSQL, create tables, and export them. 

## Results:

![total reviews](https://user-images.githubusercontent.com/114379268/217968715-5f0b969f-f065-499d-b22e-fb5584f29209.png)

Results of the total number of reviews of paid and unpaid vine customers of Amazon wireless dataset.


![five star review](https://user-images.githubusercontent.com/114379268/217968823-beafe995-a6b1-42a8-92a3-0698e7ee154d.png)

Results of the five star review of paid and unpaid vine customers.

![percentage of reviews](https://user-images.githubusercontent.com/114379268/217968838-738f4f95-3ce2-4442-b843-902701aaa3ee.png)

Results of the percentage of reviews of the paid and unpaid Vine customers.

## Summary:


![paid customers 20 ](https://user-images.githubusercontent.com/114379268/217971817-200202cc-b7e0-4ae2-b62f-573fade56119.png)


![unpaid customers](https://user-images.githubusercontent.com/114379268/217971865-2587b462-06fa-411e-b63b-22dba2652d83.png)

I conducted my analysis on the wireless dataset Amazon category.  When I first looked at the charts and tables presented above, especially at the star ratings.  I immediately thought that there was bias in the reviews.  Looking closely, most studies in the paid vine table are between 5 and 4.  And in the unpaid table, there’s a mix; you can see some 2s and a couple of 1s. However, when I ran the functions to determine the total number of reviews and the number of five-star reviews, I realized that the reviews were not biased.  31,390 five-star reviewers are not Vine members compared to the 223 Vine members.  And there’s a slightly higher percentage of unpaid vine members than the vine paid members.
