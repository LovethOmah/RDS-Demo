# RDS-Demo
1) Create an RDS database

2) Create EC2 instance and add the bootstrap script in the user data to install the mysql client

3) Configure RDS security group to accept incomig traffic from the EC2 SG

4) Connect to the EC2 via SSH

5) Confirm mysql client was installed properly

6) Connect to mysql database through the endpoint using the EC2 instance. The command is in commands.txt
   Note: In the command -U= username, -P= password, -h= endpoint
