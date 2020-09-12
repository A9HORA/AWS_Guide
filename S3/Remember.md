* Bucket name should be gloablly unique.
* Successful upload responsed with 200 OK.
* There are different AWS tiers you can use as per your need.
* For public sharing you have to make two things public `1. The bucket which contains the file` and `2. The file you want to make public.`
* **Bucket Policies** work at a **bucket level** while **Access Control Lists** works for **individual object**.
* You can create access logs for your bucket, which can be sent to another bucket in another account.
* `Encryption in Transit` where data will remain encrypted during transfer, achieved by SSL/TLS.  
* `Encryption at rest(Server Side)` where data will be encrypted when it gets stored. For ex, you encrypt your HDD.(In case of S3, it could take place either at client side          or server side)  
* Versioning  
  1. A great backup tool. 
  2. Stores all the versions of the object even if you delete an object.
  3. Once enabled can not be disabled only suspended. (You have to delete that bucket & create a new one to turn versioning off)
  4. Integrates with life-cycle rules.
  5. Has MFA delete capability.
* Whenever you upload the same file in S3 after making certain changes, you have to reasssign the permission because S3 versioning maintains different version ids of files if versioning is enabled.  
* 
