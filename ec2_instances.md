# EC2 Instances
1. Open the AWS Management Console
2. Select EC2 from the list of services
3. Click 'Instances' on the navigation pane.
4. Click 'Launch Instances'
5. AMI --> Select an AMI, make sure to check the free-tier box. Ubuntu Server 18.04 is a good option.
6. Instance --> Select the 'free tier eligible' option this is typically a 't2 micro'.
7. Configure Instance Details --> Set 'Auto assign Public IP' to 'Enable'. Leave the rest as default
8. Add Storage --> Leave as default
9. Add Tags --> Set Key as 'Name' and Value as a descriptive name.
10.  Configure Security Group --> Create a new security groups. Add a rule for SSH, HTTP and Custom TCP Rule on Port 3000. Set the  source as 'My IP' for all three rules.
11. Review and Launch Instance. If needs be, generate a new key, ensuring to store in a secure place.
