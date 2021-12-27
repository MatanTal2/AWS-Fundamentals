# AWS-Fundamentals

## Module 3
### selecting a region

When determining the right Region for your services, data, and applications, consider the following four business factors.

* Compliance with data governance and legal requirements
* Proximity to your customers
* Available services within a Region
* Pricing

### availability zone

an Availability Zone is a single data center or a group of data centers within a Region. Availability Zones are located tens of miles apart from each other. This is close enough to have low latency (the time between when content requested and received) between Availability Zones. However, if a disaster occurs in one part of the Region, they are distant enough to reduce the chance that multiple Availability Zones are affected.

### edge Location

An edge location is a site that Amazon CloudFront uses to store cached copies of your content closer to your customers for faster delivery.

### AWS Elastic Beanstalk

With AWS Elastic Beanstalk, you provide code and configuration settings, and Elastic Beanstalk deploys the resources necessary to perform the following tasks:

* Adjust capacity
* Load balancing
* Automatic scaling
* Application health monitoring

## AWS CloudFormation

With AWS CloudFormation, you can treat your infrastructure as code.
AWS CloudFormation provisions your resources in a safe, repeatable manner, enabling you to frequently build your infrastructure and applications without having to perform manual actions. It determines the right operations to perform when managing your stack and rolls back changes automatically if it detects errors.

