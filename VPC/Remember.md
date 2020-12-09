* Network ACL works as a first line of defense, a network firewall(stateless).  
  * It let us denie or allow rules as per our need.
  * Also has features of blocking IP/s.
* Security groups are further line of defense, a host based firewall(Stateful).  
* Bastion Hosts are those machines or instances in your public subnet, able to communicate to machines or instances in the private subnet.  
* Inside VPC, you are allowed to use /16 prefix for private subnet as larget one while /28 will be as smallest one.  
* Don't worry if your default VPC is deleted accidently you can recover it.  
* 1 Subnet = 1 AZ, You can have multiple subnets under one region but can not have one subnet over multiple region.  
* On creation of custom VPC below mantioned things takes place automatically:  
  * Route Table will be created.
  * Network ACLs will be created.
  * Security group will be created. `You can identify using VPC ID` 
  * Subnets won't be created.  
  * Internet Gateway won't be created.  
* 
