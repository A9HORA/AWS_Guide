* In terms of pricing, the longer you will utilize the AWS the lower you'll have to pay.
* You should choose [EC2 instance type](https://aws.amazon.com/ec2/instance-types/) as per your usage. As every EC2 type is use case specific.
* In terms of Spot Pricing, **if the spot instance is terminated by AWS, you won't be charged for partical hour of usage. However, if you terminate the instance yourself, you will be charged for the total hours the instace ran**.
* It would be better if you remember which type of instance shold be chosen per use case.
* **Amazon Linux** is based on **CentOS 6.x** while **Amazon Linux 2** is based on **CentOS 7.x**.
* VPC stands for **Virtual Private Cloud**. In other words, your own virtual network you have to manage for your instances as per your requirements.
* Free tier eligible customers can get up to 30 GB of EBS General Purpose (SSD) or Magnetic storage.
* The status check tab for selected instance shows two types of checks as follows:
    * System status checks    `Checks status of the physical system which is AWS hypervisor.`
    * Instance status checks    `Checks status of the selected EC2 instance.`
* To teminate the instance, first check if the termination protection is `Enabled` or not. If it's `Enabled` then first disable by going in instance settings and then you can terminate the selected instance.
* You can define certain commands when the instance boots up using **bootstrap scripts**.  
* A BootStrap script is a way of 
  1. Automating the EC2 instance deployment  
  2. Running things at command line when your instance first boots up  
* To do so you can use advanced options when you setup the instance for the first time.  
* You can get metadata(additional information) of your instance by curl command by following steps:  
  1. SSH your ec2 instance.  
  2. Use command `curl http://169.254.169.254/`.  
  3. You'll be able to see multiple directories. From here you can choose whatever you want and dive deep in it.  
* The name you specify for placement group must be unique within your AWS account.  
* Homogenous instances are recommanded for clustered placement group by AWS.  
* You can not merge placement groups.  
* Certain types of instance can be launched within in placement groups such as:  
   *  Compute Optimized  
   *  GPU  
   *  Memory Optimized  
   *  Storage Optimized  
