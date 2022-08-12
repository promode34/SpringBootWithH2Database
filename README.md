# Assignment and Instructions

# A retailer offers a rewards program to its customers, awarding points based on each recorded purchase.
A customer receives 2 points for every dollar spent over $100 in each transaction, plus 1 point for every dollar
spent over $50 in each transaction (e.g. a $120 purchase = 2x$20 + 1x$50 = 90 points). Given a record of every 
transaction during a three month period, calculate the reward points earned for each customer per month and total.

# Following is REST API for to get customer reward points based on customer Id 

 http://localhost:8081/customers/rewards/{customerId}
 

# Following are instructions to run project :

1. Download ZIP file from below GitHub URL :
    https://github.com/promode34/SpringBootWithH2Database 

2. UNZIP project and import project as MAVEN project in STS or Intellij idea IDE.

3. Right click on project and run as spring boot application.

4. Once server tomcat server started then test below Rest API : 

 http://localhost:8081/customers/rewards/{customerId}
 
 Example :  http://localhost:8081/customers/rewards/100
            http://localhost:8081/customers/rewards/101
            http://localhost:8081/customers/rewards/102

