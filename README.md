 docker build -t abhishekf5/python-sample-app-demo:v1 .

 kubectl apply -f deployment1.yaml

 eksctl create cluster --name dev --version 1.24 --region us-east-1 --nodegroup-name standard-workers --node-type t2.medium --nodes 1 --nodes-min 1 --nodes-max 2 --managed

eksctl delete cluster --name dev