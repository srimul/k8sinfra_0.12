# k8sinfra_0.12
#Prerequisits - create a bucket in S3 to store state file/edit the key file and security group info in variable.tf
git clone https://github.com/srimul/k8sinfra_0.12.git'
cd k8sinfra_0.12/env/ec2
terraform init
terraform plan
terraform apply -auto-approve
