# Google Cloud vs AWS in 2018 (Comparing the Clouds)

![vs](https://github.com/sudiptninja/Amazon-Web-Services/blob/master/AWS%20vs%20GCP/Media/vs.png)
## Cloud Computing Trends
![market share](https://github.com/sudiptninja/Amazon-Web-Services/blob/master/AWS%20vs%20GCP/Media/market_share.png)
>AWS is a clear leader in terms of user adoption. AWS has a 5-year headstart. AWS offers a lot more 
>cloud products and options. In contrast, GCP is fairly new to the scene, and although it offers 
>comparable solutions, it still lags behind. In terms of worldwide accessibility, AWS has many more
>data centers around the world.

## Services

| Services | GCP | AWS |
| ------ | ------ | --
| Compute Services | Google Compute Engine | Amazon Elastic Compute Cloud (Amazon EC2) |
| App Hosting | Google App Engine | AWS Elastic Beanstalk |
| Container Support | Google Container Engine | Amazon EC2 Container Service |
| Serverless Computing | Google Cloud Functions | AWS Lambda |
| Scaling Options | Autoscaler | Auto Scaling |
| Object Storage | Cloud Storage | Amazon Simple Storage (S3) |
| Block Storage | Persistent Disk | Amazon Elastic Block Storage (EBS) |
| Networking Options | Cloud Virtual Network | Amazon VPC |
| Load Balancing | Cloud Load Balancing | Elastic Load Balancing |
| Administration & Security | Access Management (IAM) | AWS Directory Service AWS Identity and Access Management (IAM) |


> It is true that AWS offers a lot more cloud products, but quite frankly, unless your 
> applications specifically require them, Sometimes less is more when it comes to cloud options.

## Compute

![COMPUTE](https://github.com/sudiptninja/Amazon-Web-Services/blob/master/AWS%20vs%20GCP/Media/COMPUTE.png)
- AWS: Elastic Compute Cloud (EC2) is Amazon’s flagship for scalable computing on demand, Amazon’s 
service is the most comprehensive, but as mentioned, the pricing for EC2 can get very intricate, 
If you want to deploy software containers with Docker, you should look at Amazon’s EC2 Container 
Service (ECS) and EC2 Container Registry (ECR).
- GCP:  Google’s Compute Engine offering is somewhat less flexible, but the pricing is a lot easier
 to follow .If you want to deploy software containers with Docker,Google’s equivalent are Container
Engine and Container Registry.

## Storage/Disk

![block](https://github.com/sudiptninja/Amazon-Web-Services/blob/master/AWS%20vs%20GCP/Media/block.png)


![OBJECT](https://github.com/sudiptninja/Amazon-Web-Services/blob/master/AWS%20vs%20GCP/Media/OBJECT.png)

- AWS: S3 Amazon Simple Storage Service (S3) is the service that’s been running the longest, and as 
such it has extensive documentation, including free webinars, tons of sample code and libraries, 
articles and tutorials and very active discussion forums where Amazon developers provide very useful 
feedback on a regular basis. Price: $0.007 gb/Month
- GCP: Google Cloud Storage  provide a service that’s as reliable and robust, but the resources you’ll 
find don’t come even close that of Amazon’s. That being said, Google may have an edge on the price. 
Price: $0.01 (storage) + $0.01 (retrieval) Gb/Month.

## Network Latency

- [GCP Ping](http://www.gcping.com/) (measure latency to Google Cloud)
- [CloudPing.info](http://www.cloudping.info/) (measure latency to AWS)

> Google Cloud latency was definitely the winner here.  One of the best ways to measure latency and ping times is to spin up small instances on each provider and run your own tests. 


## Billing and Pricing

![PRICING](https://github.com/sudiptninja/Amazon-Web-Services/blob/master/AWS%20vs%20GCP/Media/pricing.png)

- Google Cloud offers a $300 credit which lasts for 12 months. And as of March 2017, they also
 have a free tier with no time limits attached. Here is an example of an instance you could run 
forever for free with GCP:

    - f1-micro instance with 0.2 virtual CPU, 0.60 GB of memory, backed by a shared physical core. 
    (US regions only) 30 GB disk with 5 GB cloud storage

- AWS also offers a 12-month free trial. Here is an example of an instance you can run:
   - t2.micro instance with 750 hours/month
    30 GB disk (including 750 hours/month of a managed MySQL database) with 5GB cloud storage

> Google cloud is cheaper than AWS.
> For example, a 2 CPUs/8GB RAM instance will cost $69/month with AWS,
> compared to only $52/month with GCP (25% cheaper). As for cloud storage costs, 
> GCP’s regional storage costs are only 2 cents/GB/month vs 2.3 cents/GB/month for AWS. 


## Support
- Google Cloud Premium Support

    - Google offers three different levels of support: Silver, Gold, and Platinum
    Cheapest support plan, Silver, starts at $150/month minimum
    The next level support plan, Gold, starts at $400/month minimum, but at this level, you’ll
    also be billed a minimum of 9% of product usage fees (decreases as spend increases)

- AWS Support

    - AWS offers four different levels of support: Basic, Developer, Business, and Enterprise
    Cheapest paid support plan, Developer, starts at $29/month or 3% of monthly AWS usage
    The next level support plan, Business, starts at $100/month minimum, but at this level,  
    you’ll also be billed a minimum of 10% of product usage fees (decreases as spend increases)

## Security
### Google Cloud Security

- When looking at Google Cloud Platform’s security, it’s important to remember that this is 
one area where they have been improving long before GCP even launched. You get the benefit 
of a security model that has been built upon over the course of 15 years, and currently secures
products and services like Gmail, Search, etc. Google currently employs more than 500 full-time
security professionals. 
- All data is encrypted in transit between Google, the customers, and data centers by default; 
as well as the data in all of the Cloud Platform services. The data stored on persistent disks 
is encrypted under 256-bit AES and each encryption key is also encrypted with a set of regularly 
changed master keys.

### AWS Security

- Just like Google Cloud Platform, the AWS platform has a security model that has been improved 
 upon for over a decade. Some of their security features include:
- All data is encrypted in transit between AWS, the customers, and data centers; as well as the 
 data in all of the AWS cloud. The data stored on EC2 instances is encrypted under 256-bit AES
and each encryption key is also encrypted with a set of regularly changed master keys.



## Summary
- We could discuss this for days. Comparing complex platforms like GCP and AWS is not easy.  
As always, it’s all about what you need to do, how you want to do it, what are your limits
and constraints. That’s why it’s important to have a good knowledge about all the available 
options to make a wise choice. Learn both, practice with both, then make your choice. 
That’s probably the best way to understand what is the best cloud platform around.
