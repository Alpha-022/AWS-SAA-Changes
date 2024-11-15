## Slide no. 16 
### Multiple regions
The last line got cut off from the slide.

## Slide no. 17
### Regions

- AWS now has 34 regions.  
- The map has also been changed to show the new regions.

**Source:** https://aws.amazon.com/about-aws/global-infrastructure/

## Slide no. 19
### Regions

AWS services can be:
- Zonal
- Regional
- Global

**Source:** https://docs.aws.amazon.com/whitepapers/latest/aws-fault-isolation-boundaries/aws-service-types.html


## Slide no. 24
### EC2 Features

Last line got cut out from the slide


## Slide no. 54
### Three Types of Elastic Load Balancers

A new type of load balancer is available: `Gateway Load Balancer`.

**Source:** https://docs.aws.amazon.com/autoscaling/ec2/userguide/autoscaling-load-balancer.html


## Slide no. 101
### EC2 Pricing Models Overview

- Savings Plans provide 72% discount, in slide it's mentioned as 66% . 
- Reserved provides 72% discount, slide mentions 75%.
 
**Source:** https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/amazon-ec2.html

## Slide no. 104
### EC2 Spot Block and Spot Fleet

_**Update July 2021 –**  Spot Instances with a defined duration (also known as Spot blocks) are no longer available to new customers as of July 1, 2021._

**Source:** https://aws.amazon.com/blogs/aws/new-ec2-spot-blocks-for-defined-duration-workloads/

## Slide no. 107
### EC2 Reserved Instances

- Scheduled type reserved instance option is not available in the documentation.
**Source:** https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html

- Scheduled Reserved Instances are discontinued by AWS, the notice is given below:
>*You cannot purchase Scheduled Reserved Instances at this time. AWS does not have any capacity available for Scheduled Reserved Instances or any plans to make it available in the future.*

**Source:** https://aws.amazon.com/blogs/aws/new-scheduled-reserved-instances/

**Suggestion:** We can add the following line:  
**`AWS recommends Savings Plans over Reserved Instances.`**

**Source:** https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html


## Slide no. 110
### EC2 Scheduled Reserved Instances

- Scheduled Reserved Instances is deprecated by AWS

>_**Update 9/3/2024 –**  You cannot purchase Scheduled Reserved Instances at this time. AWS does not have any capacity available for Scheduled Reserved Instances or any plans to make it available in the future._

**Source:** https://aws.amazon.com/blogs/aws/new-scheduled-reserved-instances/

## Slide no. 111
### EC2 Reserved Instances - Summary

- Scheduled Reserved Instances is deprecated by AWS

- **`Standard Reserved Instances`** provide a 72% discount, but the slide mentions 75%.

**Source:** https://aws.amazon.com/ec2/pricing/reserved-instances/

## Slide no. 129
### Architecture Considerations for EC2 & ELB

The last line got cut off from the slide.

## Slide no. 131
### Reference

- Reference or links aren't given.

## Slide no. 165
### AWS Lambda Function

- AWS Lambda now allows you to configure ephemeral storage (`/tmp`) between 512 MB and 10,240 MB.

**Source:** https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-lambda-function.html

## Slide no. 169
### Amazon API Gateway - Remember

The last line got cut off from the slide.

## Slide no. 214 
### Amazon S3 Event Notifications

**Suggestion:** Amazon EventBridge can be added in **`Event Destinations`**, as it's one of the destinations mentioned in the documentation.

**Source:** https://docs.aws.amazon.com/AmazonS3/latest/userguide/EventNotifications.html

## Slide no. 218
### Amazon S3 Storage Classes

- There is a new storage class known as **`S3 Express One Zone`**.

- There are three classes related to Glacier:
S3 Glacier  Instant Retrieval  
S3 Glacier Flexible Retrieval
S3 Glacier  Deep Archive

**Source:** https://aws.amazon.com/s3/storage-classes/

## Slide no. 219
### Amazon S3 Storage Classes - Comparison

The table can be updated with the newly added storage classes, as mentioned above.

## Slide no. 221
### Amazon S3 Replication - Same Region and Multiple Region

Last line got cut out from the slide


## Slide no. 224
### Amazon S3 Presigned URL

There are other ways to share using a presigned URL, as listed below:
- Using the S3 console
- Using the AWS CLI
- Using the AWS SDKs
- Using the AWS Toolkit for Visual Studio (Windows)
- Using AWS Toolkit for Visual Studio Code

**Source:** https://docs.aws.amazon.com/AmazonS3/latest/userguide/ShareObjectPreSignedURL.html


## Slide no. 233
### Amazon S3 Glacier

**Suggestion:** Below line can be added in slide.

> AWS doesn't recommend using the S3 Glacier service for your long-term data.

**Source:** https://docs.aws.amazon.com/AmazonS3/latest/userguide/glacier-storage-classes.html


## Slide no. 234
### Amazon S3 vs S3 Glacier

The last line got cut off from the slide.

## Slide no. 267
### Server Side Encryption - S3

**Suggestion:** SSE-S3 encryption is applied by default.

*Amazon S3 now applies server-side encryption with Amazon S3 managed keys (SSE-S3) as the base level of encryption for every bucket in Amazon S3. Starting January 5, 2023, all new object uploads to Amazon S3 are automatically encrypted at no additional cost and with no impact on performance.*

**Source:** https://docs.aws.amazon.com/AmazonS3/latest/userguide/serv-side-encryption.html

## Slide no. 281
### Amazon Elastic Block Store (EBS) SSD Types

There are 2 new additions to the EBS SSD types as below:  
- io2 Block Express  
- gp3

**Source:** https://aws.amazon.com/ebs/volume-types/

## Slide no. 292
### Amazon EBS Scenarios - with EC2

- The table needs to be updated based on the new EBS types.  
Details for the table can be found below:

https://docs.aws.amazon.com/ebs/latest/userguide/ebs-volume-types.html


## Slide no. 323
### Relational Databases

OLAP stands for **Online Analytical Processing**, but the slide mentions **`Online Analytics Processing`**.

## Slide no. 340
### Read Replicas - Few Tips

- The maximum number of read replicas for MySQL, MariaDB, PostgreSQL, and SQL Server is **`15`** as mentioned in the documentation.
-   Oracle: **5** 

**Source:** https://aws.amazon.com/rds/features/read-replicas/
- Aurora: **15**

**Source:** https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-replicas-adding.html


## Slide no. 343
## RDS - Scaling

- Now SQL server also supports 64TB scaling.

**Source:** 
- https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Storage.html
- https://aws.amazon.com/about-aws/whats-new/2024/06/amazon-rds-sql-server-64tib-256000-iops-io2-block-express-volumes/


## Slide no. 344
### RDS - Operations

**The slide mentions:** If you do not configure a 30 minute backup window, RDS chooses one randomly.

**But documentation mentions:** If you don't specify a preferred backup window when you create the DB instance or Multi-AZ DB cluster, Amazon RDS assigns a default 30-minute backup window.

**Source:** https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ManagingAutomatedBackups.html


## Slide no. 457
### Amazon S3 Query in Place

- Glacier Select is not found in the documentation or features page.

- S3 Select is deprecated
> Amazon S3 Select is no longer available to new customers.

**Source:** https://docs.aws.amazon.com/AmazonS3/latest/userguide/selecting-content-from-objects.html


## Slide no. 458
### Amazon S3 Query in Place - Recommendations

- S3 Select is deprecated
> Amazon S3 Select is no longer available to new customers.

**Source:** https://docs.aws.amazon.com/AmazonS3/latest/userguide/selecting-content-from-objects.html




## Slide no. 479
### Amazon Cognito - Identity pools

**Suggestion:** We should mention that the Identity Pool grants **temporary** access to users for accessing other AWS services.

**Source:** https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html


## Slide no. 483
### AWS AppSync

- AWS recommends using AWS AppSync rather than Amazon Cognito Sync.

**Source:** https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-sync.html

## Slide no. 501
### AWS Snowball
The AWS Snowball service is going through some changes:
> *Effective November 12, 2024, AWS will discontinue previous generation AWS Snowball devices and both Snowcone devices (HDD and SDD). We will continue to support existing customers using these end-of-life devices until November 12, 2025.*

**Change:** The Snowball devices were transitioned out of service and Snowball Edge Storage Optimized **210TB** are now the primary devices used for data transfer.

**Source:** https://aws.amazon.com/snowball/


## Slide no. 503
### AWS Snowmobile

AWS has stopped offering this service.

**Source:** https://www.datacenterdynamics.com/en/news/aws-retires-snowmobile-truck-based-data-transfer-service/

## Slide no. 504
### AWS DataSync - Transfer File Storage to Cloud
On-premises storage transfers also support:  
- Hadoop Distributed File System (HDFS)  
- Object storage

**Source:** https://docs.aws.amazon.com/datasync/latest/userguide/what-is-datasync.html

- Last line got cut out from the slide


## Slide no. 515
### DevOps - IAAC

Last line got cut out from the slide

## Slide no. 527
### AWS OpsWorks - Configuration Management

**Deprecated:** 
> The AWS OpsWorks services have reached end of life and have been disabled for both new and existing customers.

**Source:** https://docs.aws.amazon.com/opsworks/latest/userguide/welcome.html

## Slide no. 552
### AWS Elemental MediaConvert

- Amazon Elastic Transcoder will be deprecated soon.

> On November 13, 2025, AWS will discontinue support for Amazon Elastic Transcoder. After November 13, 2025, you will no longer be able to access the Amazon Elastic Transcoder console or Amazon Elastic Transcoder resources.

**Source:** https://aws.amazon.com/elastictranscoder/

## Slide no. 564
### Pre-Trained Models in AWS

Amazon Forecast is no longer available; it has been deprecated.

**Source:** https://aws.amazon.com/forecast/
