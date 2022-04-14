Open CloudShell<br>
<br>
Execute:<br>
wget https://raw.githubusercontent.com/railandermarques/vpc/main/vpc.yaml<br>
aws cloudformation --region <<sua-regiao>> create-stack --stack-name <<nome-da-stack>>> --template-body file://vpc.yaml
