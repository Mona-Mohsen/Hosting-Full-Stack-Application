## Udagram Infrastructure Description


### **AWS Cloud Services**
#### **1 - RDS Postgres**
The application server uses AWS RDS Postgres as database for storing and retrieving information.

Database URL: 

`udagram.ch9rhr1utic7.us-east-1.rds.amazonaws.com`

#### **2 - S3 Bucket**
The frontend is hosted using AWS S3 Bucket. 
S3 Bucket URL: 

`http://myudagrambucket2396646.s3-website-us-east-1.amazonaws.com`

#### **3 - Elastic Beanstalk**
Server API is hosted on AWS Elastic Beanstalk service. The application is uploaded archieve file
to S3 bucket.

Elastic Beanstalk URL: 

`http://udagram-api-dev.eba-3dvw8mm5.us-east-1.elasticbeanstalk.com/`
udagram-api-dev.eba-3dvw8mm5.us-east-1.elasticbeanstalk.com



