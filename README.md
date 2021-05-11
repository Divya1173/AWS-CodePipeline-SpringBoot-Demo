# AWS-CodePipeline-SpringBoot-Demo
#!/bin/bash 
sudo yum update 
sudo yum install ruby 
sudo yum install wget 
cd /home/ec2-user 
wget https://aws-codedeploy-us-east-2.s3.us-east-2.amazonaws.com/latest/install 
chmod +x ./install 
sudo ./install auto 
sudo yum install -y python-pip 
sudo pip install awscli 
sudo yum install java-1.8.0-openjdk
