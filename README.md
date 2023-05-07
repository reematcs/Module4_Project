# Module4_Project
## DESCRIPTION
Project Agenda: To deploy the application using the Kubernetes dashboard 

Description:  

Your organization is looking to create a multi-tier application based on PHP and MySQL. Your job is to deploy this application using the Kubernetes dashboard. Create a user (service account) with the name of Sandry and make sure to assign her an admin role. WordPress and MySQL Pods should use node3 as an NFS storage server using static volumes. WordPress applications must verify the MySQL Service before getting it deployed. If the MySQL Service is not present, then the WordPress Pod should not be deployed. These all should be restricted to the namespace called cep-project1 and must have 3 svcs, and 3 Pods as a max quota. All sensitive data should be used using secrets and non-sensitive data using configmaps.  

Tools Required: kubeadm, kubectl, kubelet, and Docker  

Expected Deliverables:

Note: Kubernetes cluster needs to be set up in your lab machine to perform the above project

Requirements:
1. Multi-tier application based on PHP and MySQL
2. Kubernetes dashboard
3. Create a user (service account) with the name of Sandry and make sure to assign her an admin role
4. WordPress and MySQL Pods should use node3 as an NFS storage server using static volumes
5. WordPress applications must verify the MySQL Service before getting it deployed
6. If the MySQL Service is not present, then the WordPress Pod should not be deployed
7. These all should be restricted to the namespace called cep-project1
8. Three services, and 3 Pods as a max quota
9. All sensitive data should be used using secrets
10. All non-sensitive data should be stored using configmaps
11. kubeadm, kubectl, kubelet, and Docker

Project steps:
1. Getting started with Pods, Services, and Deployments
2. Creating and Verifying the Service
3. Creating a token and working on a dashboard
4. Configure the NFS server for MySQL and WordPress Deployment
5. Setting up the NFS Client side
6. Creating and verifying the PV
7. Creating a secret for MySQL Deployments secret data
8. Creating a configmap for WordPress Deployment to store non-sensitive information