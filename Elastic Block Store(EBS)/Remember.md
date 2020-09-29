1.  IOPS stands for **Inputs Outputs Per Second**
2.  Throughput Optimised Hard Disk Drive is a physical magnetic disk.
3.  Be careful when you choose an EBS for you job. As every EBS type is for specific use-case and uses specific API for fullfill their job. For ex,  
      1.  General purpose SSD for `Most Work Loads` uses `gp2` API  
      2.  Provisional IOPS SSD for `Databases` uses `io1` API  
      3.  Throughput Optimized HDD for `Big Data & Warehouses` uses `st1` API  
      4.  Cold HDD for `File Servers` uses `sc1` API  
      5.  Magnetic for  `Infrequent data access workload` uses `standard` API  
4.  **Provisional IOPS SSD** is the **fastest** one while **Magnetic** is the **slowest** one among all the types.
5.  Considering EBS as a HDD/SSD, keep it always in same region where your EC2 is for avoiding any performance issue.
6.  You can move your EBS from one availblility zone to another one.
7.  You can also add as many EBS as you want to an EC2 instance. In other words, we can attach more than one HDD to our PC.
8.  Be default, root volume is prone to termination when you terminate the EC2 instance. While other types of EBS are not. Though you can control this behaviour when you setup the instance for the first time or when you create new volume/s. You can also change a volume type from above mentioned five to any of them.
9.  A root volumn always start with a prefix of `snap-` under volume section of EC2 service.
10. In terms of creating image, there are two types of virtualization types as following, which gives different types of EC2 options when you lanuch the created image. 
      1.    Hardware-assisted virtualization
      2.    Paravirtual
11. AWS stores `volumes` in `EBS` while `snapshots` in `S3`.
12. First stop the instance then take it's snapshot is one of the best practices.
13. There are two different types of AMI based on volume types:  
    1. EBS Volume        `Created from an Amazon EBS snapshot`
    2. Instance Store Volume/Ephemeral Storage         `Created from a template stored in Amazon S3`
14. Even though the underlying hypervisor/host fails the EBS type volume never loses the data while the instance store type volume does.
15. For **removing the chosen snapshot** you have to first **deregister the respective AMI** you created by using that snapshot.
