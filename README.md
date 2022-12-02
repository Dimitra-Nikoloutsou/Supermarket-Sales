# Supermarket-Sales

The dataset was taken from <a href="https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales">Kaggle</a> .

<h2>About Data</h2>

The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. 

<h2>Business Task</h2>

The business task is to explore and analyse the data in order to answer the following questions:

<p>• Who spends more depending on gender and customer type? </p>
<p>• Which product line is more profitable? </p>
<p>• How many units were sold per product line? </p>
<p>• Which is the most popular payment method? </p>
<p>• Which is the most popular day and time of the week? </p>
<p>• What is the growth rate of each branch across these three months? </p>

<h3>1.Ask</h3>

First step is to identify the business task.  The task is to uncover insights and trends related to sales of every branch.


<h3>2.Prepare</h3>

I downloaded the .csv file from Kaggle and imported in MS SQL Server database management system in order to clean and analyse the data.

<h3>3.Process</h3>

The dataset was ckecked for nulls and duplicates. Then I fixed date and time format. Then I explored the data and proceed to the analysis.

<h3>4.Analyse</h3>

View <a href="https://github.com/Dimitra-Nikoloutsou/Supermarket-Sales/blob/main/SQL">SQL File</a>

I exported it in .csv file and imported it in Tableau Public.

<h3>5.Share</h3>
<h2>Visualisation</h2>

<a href="https://public.tableau.com/app/profile/dimitra.nikoloutsou/viz/supermarketsales_16690347034990/Dashboard1">Tableau link</a> (Interactive Dashboard)

![Dashboard 1](https://user-images.githubusercontent.com/114480002/205246685-b870b04b-cab2-4f50-bb7a-d42e1702ba49.png)

<h1> INSIGHTS </h1>

There are 1000 records of 3 branches, A branch is in Yangon with 340 customers, B branch is in Mandalay with 332 customers and C is in Naypyitaw with 328 customers.
There are 501 members and 499 normal customers. Also 501 of the customers are women and 499 men.

<p>• Female members and generally females tend to spend more than males.</p>
<p>• Food & Beverage is the most popular product category. </p>
<p>• Most units sold were about electronic accessories however they are in the third place regarding sales. This is happening because there are electronic accessories that are more economical than Food & Beverage products and Sport & Travel products which are in the first and second place of sales respectively. </p>
<p>• EWallet and Cash is the most popular payment method between the three branches. </p>
<p>• Saturday is the most popular day for shopping and Sunday is the second. People prefer to go to the supermarket on the weekends that don't work and are more relaxed. </p>
<p>• Month over month growth rate: </p>

![month_growth](https://user-images.githubusercontent.com/114480002/203508357-26ad2d18-289f-4a5c-9e96-7f6a58a5d664.jpg)




