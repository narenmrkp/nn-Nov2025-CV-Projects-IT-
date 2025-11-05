This project explains deploy of Swiggy App on EKS with Jenkins CICD

aws CLI install:
-----------------
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
aws --version
aws configure
----------------------------------------------------------------------------------------------------
Terraform Install:
-------------------
wget https://releases.hashicorp.com/terraform/1.3.7/terraform_1.3.7_linux_amd64.zip
unzip terraform_1.3.7_linux_amd64.zip
mv terraform /usr/local/bin
sudo mv terraform /usr/local/bin
terraform -v
-----------------------------------------------------------------------------------------------------

Medium Ref Blog:
https://muditmathur121.medium.com/securing-swiggy-clone-app-deployment-on-aws-a-comprehensive-guide-to-building-a-devsecops-pipeline-67bdd7ea004e
