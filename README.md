# k8sinfra_0.12
#Prerequisits - 
#1.create a bucket in S3 to store state file
#2.Edit the key filename and security group info in variable.tf
git clone https://github.com/srimul/k8sinfra_0.12.git'
cd k8sinfra_0.12/env/ec2
terraform init
terraform plan
terraform apply -auto-approve
