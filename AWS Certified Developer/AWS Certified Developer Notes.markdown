# AWS Notes: 
AWS Terminology and Services

## Lecture 1: 
### Region: 
Geographical location where data centres can be located.

### Availability Zone: 
Physical data centre. Regions typically have a number of AZs for failover.

### Edge Location: 
Geographical location used for caching. i.e. if asset is requested from London region by user in Australia there will be network latency. After the first request for specific asset it will be cached in the Edge Location closest to Australia and served from there for subsequent requests. Typically using Cloudfront CDN.
  > Questions:
  > 
  > How are changes pushed out to caches?
  > Is this done automatically or do you have to set up you instances in a specific way to use them?

## Lecture 2:

## Compute:
#### EC2: 
- Elastic Compute Cloud. AWS Virtual Machines.

#### Elastic Container Service: 
- EC2 docker hosting

#### Elastic Beanstalk:
- Some magic service where you upload your code and it figures out what you need and then provisions it for you. 

#### Lightsail:
- VPS Service. Server with fixed IP. Management console.

#### Lambda: 
- Serverless Websites

#### Batch (Outside scope of Certificate):
- Batch computing. 

### Storage:
#### S3 - Simple Storage Service
- Object based storage. Buckets. File into buckets.

#### EFS - Elastic File System
- NAS - network Attached Storage.Mountable to multiple VMs.

#### Glacier
- Data archival.

#### Snowball: 
- Manual import for large amounts of data.

#### Storage Gateway:
- Internal storage that replicate to AWS.

### Databases:
#### RDS - Relational Database Service
- mysql, mssql, mariadb etc. etc. Std sql datbases.

#### Dynamo DB:
- Non relational database. Mongo etc. 

#### Elasticache:
- Database caching.

#### Red Shift: 
- Data warehousing/BI 

### Migration: 
#### AWS Migration Hub:
- Hub for tracking application migration to AWS
- > What?

#### Application Discovery Service
- Tracking of application dependencies.
- > What?

#### Database Migration Service:
- Migration of on premise to AWS.

#### Server Migration Service:
- Migration of on premise to AWS

#### Snowball
- Migration of large amounts of data.

### Network and CDN:
#### VPC: Virtual Private Cloud (Fundamental to cert)
- Virtual data centre. 

#### Cloudfront: 
- AWS CDN service

#### Route 53:
- AWS DNS Service

#### API Gateway:
- Creating APIs for own services
- > What? 

#### Direct Connect:
- Direct line from corporate top AWS.


### Developer Tools:
#### Codestar: 
- Collaborative working plus CI

#### Code Commit: 
- Source control storage.

#### Code Build: 
- CI system.

#### CodeDeploy:
- Automation of code deploy to various AWS services i.e. EC2, Lambda, VPC.

#### CodePipeline:
- Continuous Delivery Service

#### XRay: 
- Debugging of serverless applications. 

#### Cloud 9:
- Development IDE.

### Management Tools:
#### Cloud Watch:
- AWS monitoring system

#### Cloud Formation:
- Infrastructure scripting (Infrastructure as Code)

#### Cloud Trail
- Logs changes to AWS environment

#### Config:
- Montors config of entire AWS setup. Point in time snapshots.

#### OpsWorks:
- Chef/Puppet automation of environment configuration.

#### Service Catalog: 
- Catalog of IT Services approved for use.

#### Systems Manager:
- Interface for managing EC2 resources. 
- Grouping resources
- Departments
- Rollout of patches

#### Trusted Advisor
- Advice around security and utilage. 

#### Managed services: 
- Amazon managed EC2.

### Media Services: 
#### Elastic Transcoder:
- Resizes media so it looks good on a variety of devices.

#### Media Convert:
- File based video transcoder.

#### Media Live:
- Live video streaming

#### Media Package:
- Package videos for download

#### Media Store:
- Media storage

#### Media Tailor:
- Targetted advertising into video streams.

### Machine Learning:
#### Sage Maker:
- Deep learning.
 
#### Comprehend:
- Understand what the market is saying about your products.

#### Deep Lens:
- AR camera.

#### Lex:
- AI customer chat. Powers Alexa.

#### Machine Learning:
- Analysis of data sets. Outcome prediction.

#### Polly:
- Text to speech.

#### Rekognition:
- Video and image recognition.

#### Translate:
- Language translation

#### Transcribe:
- Speech recognition and turns into text.

### Analytics:
#### Athena:
- SQL queries against S3 buckets.

#### Elastic Map Reduce (EMR)
- Big Data

#### Cloud Search:
- Search services

#### Elastic Search:
- Search service

####  Kinesis:
- Ingest large amounts of data. 

#### Kenesis Video Streams:
- As above with video.

#### Quick Sight
- BI tool. View business intelligence data.

#### Data pipeline
- Move data between different AWS services.

#### AWS Glue
- ETL

### Security, Identity and Compliance 
#### IAM (Key Requirement):
- Identity Access Management

#### Cognito:
- Authentication for mobile devices.

#### Guard Duty:
- Watches your AWS setup for suspicious activity

#### Inspector:
- VM agent installable in EC2 etc. for testing for security vunerabilities. 

#### Macie:
- Scans S3 buckets for PII and alters.

#### Certificate Manager:
- SSL cert management.

#### Cloud HSM:
- Hardware security modules

#### Directory Service:
- Integrate Active Directory

#### WAF:
- Web Application Firewall. Stops XSS etc.

#### Shield:
- DDOS mitigation

#### Artifact:
- Audit/Compliance reports.

### Mobile Services:
#### Mobile Hub:
- Manage AWS services for mobile. Mobile backends.

#### Pinpoint:
- Targetted puch notifications for mobile. 

#### Appsync:
- Updates data in real time and for offline for mobile. 

#### Device farm:
- Testing for mobile. Many different device types. 

#### Mobile Analytics:
- Analytics service for mobiles. 


### AR/VR:
#### Sumerian:
- Tools for build VR/AR worlds

### Application Integrations:
#### Step functions:
- Management of Lambda functions.

#### Amazon MQ:
- Message queuing

#### SNS:
- Notification service.

#### SQS:
- Worker queues.

#### SWF:
- Simple Work Flow service.
- Jobs. Can involve human interaction i.e. amazon uses it in Warehouse.

### Customer Engagement:
#### Connect:
- Contact centre as a service

#### Simple Email Service:
- Large emailer.


### Business Productivity:
#### Alexa for Business:
- Extending alexa functionality for corporate.

#### Chime:
- Video conferencing.

#### Work Docs:
- Dropbox for AWS.

#### Work Mail:
- Office 365 for Amazon


### Desktop and App Streaming:
#### Workspaces:
- VDI solution. Desktop in the cloud.

#### Appstream:
- Streaming applications form cloud to device. Citrix-ish

### Internet of Things (IoT):
#### iOT:
#### iOT Device Management:
#### Amazon Free RTOS:
- OS for IoT devices.
#### Green grass
- Integration for other AWS services for IOT devices.

### Game Development:
#### Gamelift:
- Serrice to aid game development.
