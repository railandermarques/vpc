Open CloudShell and execute:<br>
<br>
$ wget https://raw.githubusercontent.com/railandermarques/vpc/main/vpc.yaml<br>
$ aws cloudformation --region us-xxxx-x create-stack --stack-name vpc-padrao --template-body file://vpc.yaml
