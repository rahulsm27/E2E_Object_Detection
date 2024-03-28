# E2E_Object_Detection
A end to end project using Yolo object detection

1. Create venv
conda create -n safety python=3.8 
conda activate safety

2. Create I am user
create iam user on aws -> yolov7. download the access key

3. Configure aws
execute 'aws configure' to set secret access key and key id

4. Create S3 Bucket
create 'isd-rahulsm27' s3 bucket
upload zip file on s3 bucket

5. Create ECR repo
666711044981.dkr.ecr.us-east-1.amazonaws.com

6. Create EC2 instance
Download the key pair (.pem file)
Connect

sudo apt-get update -y
sudo apt-get upgrade

7. Install docker on the instance

curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker ubuntu
newgrp docker


AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_REGION
ECR_REPOSITORY_NAME