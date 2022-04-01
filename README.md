# eks-mongodb-with-express
express-frontend-with-mongodb-backend


######################
Creating a deployment
######################

1. Express deployment running a single pod and one replica.
- to scale run: kubectl edit deployment  <NameOfDeployment.yaml>.
2. MongpBD deployment running a single pod.

- kubectl apply -f <NameOfDeployment.yaml>

  
######################
Creating a service
######################
 - for ingress traffic
  
######################
Creating a ConfigMaap
######################
  
- used for the database url

######################
Creating a secret
######################

for encryption of database password and username
