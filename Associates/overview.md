# Amazon Web Services
## Solutions Architect - Associates

### Services Overview
#### High Level Services
* AWS Global Infrastructure
    * Know the differences between the region and availability zone
    * **Availability Zone** - Data center (may be several coupled together).
    * **Region** - Two or more **Availability Zones**.
    * **Edge Locations** - Endpoints for AWS used for caching content (usually CloudFront)
        * **CloudFront** - Is Amazon's Content Delivery Network (CDN).
* Need to know;
    * Analytics
    * _**Computer**_
    * _**Databases**_
    * Desktop & App Streaming
    * Machine Learning
    * Management & Governance
    * Migration & Transfer
    * _**Network & Content Delivery**_
    * _**Security, Identity & Compliance**_ 
    * _**Storage**_

    > **Note**: Bold and italic list items from above are the main ones to study.

#### Compute
*  Elastic Cloud Compute (EC2)
  * Virtual Machine
* Elastic Container Service
  * Management of multiple EC2 instances (like Dockers)
* Elastic Beanstalk
  * Does autoscaling and environment setup for developer
* Lamdba
  * Server-less -- just compute power, good for scripting languages and doing something quickly.

#### Storage
* Simple Storage Service (S3)
  * Object based storage
  * Uses buckets
* Elastic File Service (EFS)
  * Network attached storage
  * Mount to multiple virtual machines
* Glacier
  * Archive data
* Snowball
  * Bringing in large amount of data
* Storage Gateway
  * Virtual machines that replicate information back to S3

#### Databases
* Relation Database Service
  * SQL database
* DynamoDB
  * NoSQL database
* ElastiCache
  * Caches most common queries
* Red Shift
  * Data warehouse or business intelligence

#### Migration
* AWS Migration Hub
  * Track applications as migrated
* Application Discovery Service
  * Tracks applications and dependencies
* Database Migration Service
  * On premises to cloud
* Server Migration Service
  * Helps go from physical or virtual machines to cloud
* Snowball
  * Migrates large amounts of data to cloud
  * Literally send in physical data

#### Networking & Content Delivery
* Amazon Virtual Private Cloud (VPC)
  * Virtual data center
* CloudFront
  * Content Delivery Network (CDN)
  * Media files cached closer to user
* Route53
  * Dynamic Namespace (DNS) service
    * Allows users to look up web site to server IP address
    * *Example*: www.google.com goes to 172.217.9.78 (when I pinged)
* Application Programming Interface (API) Gateway
  * Create services that talk to each other
* Direct Connect
  * Run dedicated line from office directly into Amazon

#### Developer Tools
* CodeStar
  * Collaborate with developers
  * Project Management
* CodeCommit
  * Source Code Management (SCM)
  * Like GitHub, BitBucket, etc.
* CodeBuild
  * Compiles code and tests
  * Software packages that are then ready to deploy
* CodeDeploy
  * Deploys code virtual machines or servers
* CodePipeline
  * Continuous Delivery
* X-Ray
  * Debug or analyze server-less applications
* Cloud9
  * Develop code in AWS console or web browser
  * Integrated Development Environment (IDE)
