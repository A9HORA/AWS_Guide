* RDS is not serverless and run on virtual machines.  
* We can't log in RDS machines's logs directly that is why we need to publish the log to cloudwatch in a log group.  
* Patching the RDS OS is the part of amazon not yours.  
* Automated backup allow you to recover your DB to any point in time within a "retention period" can be between 1 ot 35 days. This takes place automatically in daily manner.  
* During the backup process storage I/O may be suspended so you may experience elevated latency.  
* DB snapshot will be present even after you delete the original DB instance.  
* For creating read replica of the DB instance the backup shuld be turned on.  
