# A/B Testing-Method

A/B Testing Method¶
A/B testing is a method where two versions (A and B) are compared. This test helps find out which version works better. For example, two different designs of a webpage are tested to see which one gets more conversions.

Comparison of Conversion Rates Between A/B Testing and Bidding Methods

Business Problem¶

![image](https://github.com/user-attachments/assets/f91e332e-12fb-4b31-af89-dd0a06468f84)
Facebook recently introduced a new bidding type called "averagebidding" as an alternative to the existing "maximumbidding" bidding type. One of our customers, bombabomba.com, decided to test this new feature and wants to run an A/B test to find out if averagebidding brings more conversions than maximumbidding.

The A/B test has been running for one month, and bombabomba.com is now asking you to analyze the results of this A/B test. The final success measure for bombabomba.com is "Purchase." Therefore, the focus of the statistical tests should be on the Purchase metric.

Dataset Story

This dataset contains information about a company's website, including the number of ads seen and clicked by users, as well as the revenue generated from these actions. There are two separate datasets: Control and Test groups. These datasets are in separate sheets of the ab_testing.xlsx Excel file. The Control group has been given Maximum Bidding, and the Test group has been given Average Bidding.

Variables:

Impression: Number of ad views

Click: Number of clicks on the viewed ad

Purchase: Number of products purchased after clicking on the ad

Earning: Earnings from the purchased products


