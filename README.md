Abra o CloudShell e execute:<br>
<br>
$ wget https://raw.githubusercontent.com/railandermarques/vpc/main/vpc.yaml<br>
$ aws cloudformation --region us-east-1 create-stack --stack-name vpc-padrao --template-body file://vpc.yaml
