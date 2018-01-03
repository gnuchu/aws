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

### Media Services: 

### Machine Learning:

### Analytics:

### Security, Identity and Compliance 

### Mobile Services:

### AR/VR:

### Application Integration:

### Customer Engagement:

### Business Productivity:

### Desktop and App Streaming:

### Internet of Things:

### Game Development:
