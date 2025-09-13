EC2 Instance Tear configuration & Teardown Instructions

Configuration
1. Build your own security group. 
2. Click Ec2 Instance button. 
3. Input name of EC2 instance. Configure key pairs. 
4. Configure network settings. 
5. Make sure to select IPv4 and HTTP (port 80) not HTTPs (port 443). 
6. Add previously customized security group in add personal security group settings. 
7. Add text script from GitHub repo. 
8. Click Launch instance button. 

Tear Down
1. Click on empty box next to instance 
2. Click on instance states
3. Select Terminate instance. 
4. Instance will display "shutting down". 
5. Refresh screen Instance will say "Terminated". 
