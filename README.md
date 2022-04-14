Open CloudShell
Execute:
wget https://raw.githubusercontent.com/railandermarques/vpc/main/vpc.yaml
aws cloudformation --region <<sua-regiao>> create-stack --stack-name <<nome-da-stack>>> --template-body file://vpc.yaml
