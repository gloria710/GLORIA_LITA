# GLORIA_LITA
 EC2 PROJECT LAUNCHING AND DEPLOMENT OF APACHE WEB SERVER
### CREATING SECURITY GROUP USING VPC PROVIDED BY LITA
open the security group from the search bar on the aws console,input my sgname allow,the description is to allow ssh and http traffic,then i use the lita provided vpc below is the picture
![security group details](/security-group1.png)
###CREATING INBOUND RULES
#I created inbound rules by allowing ssh and http traffiC
In the inbound rules info i click on add rules, click on type cursor and choose ssh, close to the type cursor is the custom cursorthen i choose anywhere ipv4, i follow the same process for the http below is the picture
![inbound rules picture details](/inbound-rules.png)
### CREATING OUTBOUND RULES 
I created outbound rules without making any changes to the default below is the picture
![outbound rules picture details](/outbound-rules.png)
### SUCCESSFULLY CREATED THE SECURITY GROUP
After i checked my details and they are correct i then pressed the create security group at the down of the page, security group was successfully created below is the picture
![successfully created security group picture details](/successfully-createdsg.png)
### LAUNCHING THE EC2 INSTANCE USING THE SUBNETS PROVIDED BY LITA
# I create the name and tag
i type out ec2 on the aws console,i choose the region i want to launch my instance i click on instances then i checked for LAUNCH INSTANCE by the corner of the  console,i clicked on it i write the name i wanted for the ec2 below is the picture
![launch instance picture details](/instancelaunch.png)
### CHOOSING THE AMI
I choose amazon linus as the operating system under quick start then i go down under AMI to choose Amazon Linus 2 AMI(HVM) and t2.micro as the instance type below is the picture
![AMI picture details](/instance-launch2.png)
### CREATING THE KEYPAIR
I created my keypair from the keypair info under the launch instance,beside was create new keypair i clicked on it and it bring options that i had to fill,my keypair name ,the type and the file format. i write the name i want for my keypair,i choose RSA as my keypair type and .pem as my file format below is the pictureof the 
keypair
![keypair picture details](/keypair.png)
### CREATING THE NETWORK SETTING
I created the network setting with the lita_project-vpc,lita_project-subnet-public1,i then enable the auto assign publicIP and i choose my previous created security group as the firewall and i leave the configure storage at 8gb, i then review all the settings when they are all in order i clicked on launch
instance at the end of the page. below is the picture of the network setting and it was successfully launched.
![network settings picture details](/network-setting.png)
![successfully launched picture details](/instance-successful-running)

-