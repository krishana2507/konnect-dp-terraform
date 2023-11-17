# konnect-dp-terraform
Once the EKS cluster is created, configure kubectl to connect to the cluster by using the authentication details provided by AWS. You can obtain the cluster configuration using the AWS CLI:
aws eks --region ap-south-1 update-kubeconfig --name konnect-cluster
