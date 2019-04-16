# cloudFormation
Go to Amazon management console login into AWS account:
1) I am creating my aws resources in US East (N. Virginia) region. 
2) Before that create a .pem key file in AWS Account. I am using the key file cft.pem 
3) Creating the key file just following below steps
•	Goto Aws management console
•	Goto Network and security
•	Goto KeyPair
•	click on create a keypair... Give your required name to create a key
4)Under services select Cloud Formation
click on  create new stack option:
Under this select upload a template using amazon s3. and upload the cft.yaml file:
and click on next
5) Here give your stack name and key file name:
   my values:
   stack name webserver
   key file: cft
   SSHLocation: 131.247.0.0/16
   then click next
6)Here you can give tags, rollback monitoring time..
Otherwise click on next
7)Review the templates and click on create 
8)Stack creation of Webserver is completed 
using the
•	CloudFormation
•	AWS EC2
•	AWS EBS
•	AWS S3
•	AWS DEFAULT VPC

9)just click on events to know the created resources in AWS.
For checking the webserver is ping or not:
Using the Pinging tool to know 
https://www.site24x7.com/ping-test.html
 
and paste your Public DNS of webserver instance and click on Ping now you can find the DNS on outputs section of stack
 

you can check the test results now.
 


