[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 16 - AWS Cloud Servers

## Discussion Questions

### AWS EC2

What is an EC2 Instance?
> A cloud based server. It can be modified to run different specifications for processor, storage sizem operating system etc.

Name 2 use cases for EC2.

> 1) if you dont have the money to invest in physical servers to run/scale up your product
> 2) To optimize CPU features. If you have per/vCPU licensing costs or if you would like to disable Intel Hyperthreading technology for single-threaded high performance computing applications.

Provide 1 reason to use ECS instead of Heroku.
> Allows you to build in a local environment or on the cloud. Integrates into the AWS family of products seamlessly.

### EC2 For Humans

Where can we find EC2 on the AWS Console?
> Under the Compute heading in all services heading.

Explain the general difference between T2 Micro and XL.
> T2 Micro is good for web server or servers with "bursts" of traffic. XL will have more available virtual instances and compute/ram/storage available.

Explain a “Compute Cycle” to a non-technical friend.
> The instance can be launched and it will be in the pending stage until it is fully ready to go. It then enters the running stage. You can do your work and whatever you want. You can then Stop the instance to put it into a hibernation mode. The instance exists but nothing can be done with it until it is resumed. You can also terminate the instance and the server and all its data will disappear.

### Elastic Beanstalk

What is Elastic Beanstalk?
> Service that deploys, manages and scales web applications and services.

Describe the relationship between EC2 and Elastic Beanstalk.
> It uses the amazon EC2 instance type to host the code in the amazon cloud.

Name some benefits of using Elastic Beanstalk.
> It handles the deployment for you including load balancing, auto-scaling and application health monitoring. Taking over tasks for you so you can focus on building your app/service.

## Things I want to know more about

How to make sure not to pay for anything on AWS. It my biggest fear working in the cloud is tha "oopsie" bill in the mail. 

-----
