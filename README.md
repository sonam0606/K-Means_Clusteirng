# K-Means_Clusterinng

## Abstract

To examine a set of customers and identify those that behave similarly to tailor marketing K-Mean Clustering Algorithm is used.
All the customers are grouped on the basis of purchases of four products.


## Data Exploration: 
Data :
Customer#	ProductA	ProductB	ProductC	ProductD
1	        0	          0	         1	     1
2	        0	          1	         0	     1
3	        1	          1	         0	     0
4	        1	          1	         0	     1
5	        1         	0	         0	     0
6	        0	          0	         1	     0
7	        1	          0     	   1	     1
8	        1	          1	         0	     0
9	        1	          0	         0	     0
10      	0	          0	         1	     1
11	      0	          0	         1	     1
12	      1	          1	         0	     0
13	      1	          0	         1	     0
14	      0	          1	         0	     0
15	      0	          1        	 0    	 1
16	      0	          0	         1	     1
17	      1	          0	         0	     0
18	      0	          0	         0	     1
19	      0	          1	         1	     1
20	      0	          1	         0	     1

20 customers.  4 products + customer ID.  Binary where 1 = purchased.  0 = no purchase.
•	9 / 20 (45%) have purchased product A
•	9 / 20 (45%) purchased product B
•	8 / 20 (40%) purchased product C
•	11/ 20 (55%) purchased product D

1.	Start by calculating the distance of each customer from the three starting centroids.
Use Euclidean Distance to measure how far apart the customers are from the centroids.
Starting with Cluster # 1 and determine which cluster the customers belong to.

2.  Update the centroids.

3.	Repeat steps  1 and 2 for three iterations

A.	Group the individuals into three clusters using K-Means cluster method and the Euclidean distance measure.

## Below are the steps.Detailed solution is in the excel file


##Iteration 1:
Step1: Used the centroids which were randomly identified
Step2: Calculated the Euclidean distance of each customer form these points and calculate which customer belongs to which cluster.
Step3: Calculate the new centroid

##Iteration 2:
Step 4: Used the centroids calculated in last iteration.
Step 6: Calculate the new centroid.

##Iteration 3:
Step 7: Used the centroids calculated in last iteration
Step 8: Calculated the Euclidean distance of each customer form these points and calculate which customer belongs to which cluster.
Step 9: Calculate the new centroid.

Since Centroids in iteration 3 did not change, we can say for k=3 the cluster assignments are stable. 




