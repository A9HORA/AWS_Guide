1.  IOPS stands for **Inputs Outputs Per Second**
2.  Throughput Optimised Hard Disk Drive is a physical magnetic disk.
3.  Be careful when you choose an EBS for you job. As every EBS type is for specific use-case and uses specific API for fullfill their job. For ex,  
      1.  General purpose SSD for `Most Work Loads` uses `gp2` API  
      2.  Provisional IOPS SSD for `Databases` uses `io1` API  
      3.  Throughput Optimized HDD for `Big Data & Warehouses` uses `st1` API  
      4.  Cold HDD for `File Servers` uses `sc1` API  
      5.  Magnetic for  `Infrequent data access workload` uses `standard` API  
