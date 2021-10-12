# Amazon_Vine_Analysis

## Overview of the analysis

In this project a data set from Amazon reviews of musical instruments (and its derivates) was used with the help of tools such as Pyspark for the ETL process. A connection with the database was made through AWS and pgAdmin4 for visualization of tables. Google Colab was utilized for dataframe manipulation. The objective of this analysis is to determine if there is an effect on reviews regarding paid reviewers in Vine. 

## Results

### How many Vine reviews and non-Vine reviews were there?

There are 2287 Paid Vine reviews and 902476 non-Vine reviews. 
<img width="601" alt="Screen Shot 2021-10-11 at 22 54 55" src="https://user-images.githubusercontent.com/85911181/136890231-5391841f-b18c-4f72-8059-c57ab1a11241.png">


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were 572916 5 Star Reviews with a total of 904765 Reviews. 
<img width="216" alt="Screen Shot 2021-10-11 at 23 01 52" src="https://user-images.githubusercontent.com/85911181/136890242-a6171ae8-c989-446f-b034-d565b34aeb12.png">

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

There was a 64% of 5 star Vine reviews and a 9% of non-Vine reviews. 
<img width="228" alt="Screen Shot 2021-10-11 at 23 14 33" src="https://user-images.githubusercontent.com/85911181/136890361-dbd7f1bc-f795-453a-bcd6-a0fddfcd765c.png">

## Summary

With this analysis it can be easy to conclude that paid reviews will favor 5 star ratings. 64% of 5 star reviews were paid while only 9% weren't. The Vine program seems to have worked significantly in the review of musical instruments. 
