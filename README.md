#!/bin/bash
sudo yum -y update
sudo yum -y install ruby
sudo yum -y intsall wget
cd/home/ec2-user
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazon.com/latest/install
sudo chmod +x ./install
sudo ./install auto
sudo yum install -y python-pip
sudo pip install awscli
