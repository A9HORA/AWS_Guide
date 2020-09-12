* Bucket name should be gloablly unique.
* Successful upload responsed with 200 OK.
* There are different AWS tiers you can use as per your need.
* For public sharing you have to make two things public `1. The bucket which contains the file` and `2. The file you want to make public.`
* **Bucket Policies** work at a **bucket level** while **Access Control Lists** works for **individual object**.
* You can create access logs for your bucket, which can be sent to another bucket in another account.
* `Encryption in Transit` where data will remain encrypted during transfer, achieved by SSL/TLS.  
* `Encryption at rest(Server Side)` where data will be encrypted when it gets stored. For ex, you encrypt your HDD.(In case of S3, it could take place either at client side          or server side)  
*       
