### CI/CD
- This was sufficiant for the CI/CD part explains the deployment type conceptually very well, however there are lack of labs or handson. I suggest you to do some parctice of these by your own.
- [Practicing Continuous Integration and Continuous Delivery on AWS](https://d0.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf)
- [AWS Certified DevOps Engineer | COURSE 1 | Continuous Delivery and Automation](https://www.youtube.com/watch?v=s6HShJzq3TY&list=PLd115Y1edsKLnP3JgFI5LjcpMzPhhMLAy)



### Blue Green Deployment
- **Blue Green Deployment should be studied throughly**. Some of the materials as below
	- [Blue/Green Deployments on AWS](https://d0.awsstatic.com/whitepapers/AWSBlueGreen_Deployments.pdf)
	- [Deep Dive into Blue/Green Deployments on AWS](https://www.youtube.com/watch?v=aX54mhZbN58&feature=youtu.be)
	- [Choosing the Right Software Deployment Technique (DEV310)](https://www.youtube.com/watch?v=bSXRF1poE8g)

### Cloud formation
- Next was the Cloud formation, it was fair amount of explaination however this one is extreamly important and advance topic hence suggest to understand it completly. Some of the complicated parts of these involves CFN Nesting, VPC Formation and Custom Resources. It requires a lot of deep dive and hands on. Clearly there are not enough example and explaination of this in the course carriculam hence suggest you to cover it completly from external resources i.e from you tube and other available resources. Some of the topics to cover -
	- Cloud formation to create one or more servers with different security groups, subnets within one VPC to understand the concept of these component use [Amazon Virtual Private Cloud (VPC)](https://www.youtube.com/watch?v=fpxDGU2KdkA) You tube video.
	- An important and very crucial point about the [Subnet and Internet Gatway association](https://stackoverflow.com/questions/42437814/cloudformation-vpc-routing-table-with-no-route-for-internet-gateway)
	- Many questions that test knowledge on cfn wait condition and handlers
	- questions on custom resources
	- lot of questions on cloudwatch logs and filters
	- autoscaling lifecycle hooks

### Opswork
- [Managing Multi-Tiered Applications with AWS OpsWorks](https://d0.awsstatic.com/whitepapers/managing-multi-tiered-web-applications-with-opsworks.pdf)
	
### Cloudwatch 
- [CloudWatch User Guide](http://docs.amazonaws.cn/en_us/AmazonCloudWatch/latest/monitoring/)
- [AWS Certified DevOps Engineer | COURSE 2 | Monitoring, Metrics, and Logging](https://www.youtube.com/playlist?list=PLd115Y1edsKKzNJfHWjY9CoUZCBYHPhv-)

### Remaining Bits
- **Read about datapipeline**
- **Beanstalk**
- **Many/most questions required knowledge of how to use tools at a deeper level and how to extend them,**
- **if you see realtime, just select Kinesis.**
- **How to build app environment using Cloudformation, beanstalk and Opswork. (differences of those services.)**
- **Skip the ACG's DynamoDB Videos from DevOps Pro exam and just learn it from Associate Developer's Course, should be more than enough to save time and effort**
- **"pending:complete" does not exist as autoscaling lifecycle hook name. Then, an answer includes that cannot be a right answer.**
- **FailedDeployment command does not exist with ElasticBeanstalk.**
- **Focus on question requirements: High availability or/and cost-effective or/and fault-tolerance, ...etc. then pick the answer accordingly.**
- **Encrypted S3 is a good place to share keys/passwords**
- **Kinesis is for real-time streaming, But read carefully question to check if it is the case.**


### Other Links
- [AWS Certified DevOps Engineer | COURSE 3 | Security, Governance, and Validation](https://www.youtube.com/watch?v=uOyMDdTMeIg&list=PLd115Y1edsKL4c-If5nzypF6J337IFkIt)
- [AWS Certified DevOps Engineer | COURSE 4 | High Availability, and Elasticity](https://www.youtube.com/watch?v=OtpFLcnEGvU&list=PLd115Y1edsKI6Lx5kUK5scI8USMcxwgjE)

*Desclaimer*
>This is on going study notes and there are various sources for these. Credit belongs to respective authors and sources for it.
>This is work in progress hence should be considered as one. This doesn't guaranty of success in anyway for the exam.