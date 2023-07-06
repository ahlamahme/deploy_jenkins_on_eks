# Deploy jenkins on private eks cluster 

 
 

1. create infrastructure <br> 

2. install jenkins on the cluster use this link (https://www.jenkins.io/doc/book/installing/kubernetes/) <br> 

2.1 to expose jenkins create loadbalancer service using command 

 $ kubectl expose deployment <deployment name> --type=LoadBalancer --name=my-service <br> 

Use this link (https://kubernetes.io/docs/tutorials/stateless-application/expose-external-ip-address/) <br> 

![alt text](/home/ahlam/deploy_jenkins_on_eks/k8s/img/Screenshot from 2023-07-06 16-55-36.png) 