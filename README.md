# Project Title: Connecting a Web App to Aurora Database

This project demonstrates how to create an Amazon Aurora MySQL database and connect it to a web application. 
The project showcases the integration of a scalable and secure database with a web app, enabling real-time data storage and retrieval.

##Pillars of the AWS Well-Architected Framework
Under Cost Optimization , I set the instance configuration to burstable classes and size to db.t3.medium to make the database perform well under high traffic but also cost effective.
I also Leveraged Aurora's automated scaling and caching for Perfomance Efficiency.
Lastly I created IAM user instead using the root to proctect it from security breaches.

##What I Could Have Done Regarding the Selected Pillars
 For Cost Optimization I could have explored Aurora Serverless for automatic scaling.
 Under Performance Efficiency i could have implemented database partitioning and query optimization.
 Under security i could have implemented AWS IAM Identity Center which enables users to manage access to multiple AWS accounts and applications with a single set of login credentials.








