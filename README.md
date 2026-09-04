# AWS ec2 intanstance
This is a project from roadmaps for setting up an AWS ec2 instance and can be found here:

https://roadmap.sh/projects/ec2-instance

## Requirements
Goal is to create an AWS account, setup a Linux server on AWS EC2 and deploy a simple website.
- create an AWS account or use an existing account
- familiarize yourself with AWS Management Console
- launch an EC2 instance
  - use Ubuntu Server AMI
  - instance type: `t2.micro`
  - use default VPC and subnet for your region
  - config security group to allow inbound traffic on
    - port 22 for SSH
    - port 80 for HTTP
  - create a new key pair or use existing one for SSH access
  - assign a public IP address to the EC2 instance
- connect to the EC2 instance using SSH and private key
- update system packages
- install a web server like Nginx
- create simple HTML file for the static website
- deploy static website to the EC2 instance
- access website using the public IP of the EC2 instance

### Stretch goal
- setup up a custom domain name for the website
  - use Amazon Route 53
- implement HTTPS
  - use free SSL/TLS certificat from Let's Encrypt
- create a CI/CD pipeline using AWS CodePipeline
  - use to deploy changes to your website
  