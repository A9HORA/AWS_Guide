**Essentials**
1. Login to AWS Console.
2. Goto IAM.

**Activate MFA**
1. Install Google or Microsoft Authenticator in your android or iphone device.
2. Click on show QR code and scan it with your authenticator app.
3. Add two codes as per your authenticaor app.
4. Click on Create MFA.1
5. Done.

**Create Individual IAM User**
1. Manage Users
2. Add User  
   * User name: Desired_username
   * Access type: Required access_type  
   **For Programmatic access there is nothing to do while for AWS Management Console access you've to assign other details as per need**
3. Next Permission  
4. Create group  
   * Group name: Desired_Group_name  
   * Choose Policy as per your need  
5. Set permission  boundery if you want to limit the access for created user group.  
6. Next  
   *  Provide tags in Key:Value pair  
7. Review  
8. Create User  
9. There will be two options for you after user creation  
   *  Download .csv  **You can download details in a csv file**  
   *  Send Email  **You can send one to one email**  
