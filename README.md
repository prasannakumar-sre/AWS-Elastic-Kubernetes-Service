AWS EKS (Elastic Kubernetes Service) is a fully-managed Kubernetes service provided by Amazon Web Services (AWS). It allows users to run Kubernetes clusters on AWS without the need to manage the underlying infrastructure.
Kubernetes is an open-source container orchestration system used for automating the deployment, scaling, and management of containerized applications. AWS EKS provides users with a managed Kubernetes control plane, which handles tasks such as scheduling, scaling, and updating the Kubernetes cluster.
Users can use AWS EKS to run their containerized applications in a scalable and highly available environment. AWS EKS integrates with other AWS services, such as Amazon Elastic Container Registry (ECR) and Amazon Elastic File System (EFS), to provide users with a complete end-to-end solution for deploying and managing containerized applications.
To use AWS EKS, users need to create an Amazon EKS cluster, which includes the Kubernetes control plane and worker nodes. They can then deploy their applications using Kubernetes manifests or Helm charts. Users can also use tools such as kubectl or the AWS Management Console to manage their Kubernetes cluster and applications.
AWS EKS provides users with features such as automatic scaling, cluster upgrades, and security features such as encryption and identity and access management (IAM) integration. It also integrates with other AWS services to provide users with additional functionality, such as logging and monitoring.

========================================================================================================


##  AWS EKS Content 

| S.No | AWS Service Name |
| ---- | ---------------- |
| 1.   | Create AWS EKS Cluster using eksctl CLI |
| 2.   | Docker Fundamentals
| 3.   | Kubernetes Fundamentals
| 4.   | EKS Storage with AWS EBS CSI Driver |
| 5.   | Kubernetes Important Concepts for Application Deployments |
| 5.1  | Kubernetes - Secrets |
| 5.2  | Kubernetes - Init Containers |
| 5.3  | Kubernetes - Liveness & Readiness Probes |
| 5.4  | Kubernetes - Requests & Limits |
| 5.5  | Kubernetes - Namespaces, Limit Range and Resource Quota |
| 6.   | EKS Storage with AWS RDS MySQL Database |
| 7.   | Load Balancing using CLB & NLB |
| 7.1  | Load Balancing using CLB - AWS Classic Load Balancer |
| 7.2  | Load Balancing using NLB - AWS Network Load Balancer |
| 8.   | Load Balancing using ALB - AWS Application Load Balancer |
| 8.1  | ALB Ingress Controller - Install |
| 8.2  | ALB Ingress - Basics |
| 8.3  | ALB Ingress - Context path based routing |
| 8.4  | ALB Ingress - SSL |
| 8.5  | ALB Ingress - SSL Redirect HTTP to HTTPS |
| 8.6  | ALB Ingress - External DNS |
| 9.   | Deploy Kubernetes workloads on AWS Fargate Serverless |
| 9.1  | AWS Fargate Profiles - Basic |
| 9.2  | AWS Fargate Profiles - Advanced using YAML |
| 10.  | Build and Push Container to AWS ECR and use that in EKS |
| 11.  | DevOps with AWS Developer Tools CodeCommit, CodeBuild and CodePipeline |
| 12.  | Microservices Deployment on EKS - Service Discovery |
| 13.  | Microservices Distributed Tracing using AWS X-Ray |
| 14.  | Microservices Canary Deployments |
| 15.  | EKS HPA - Horizontal Pod Autosaler |
| 16.  | EKS VPA - Vertical Pod Autosaler |
| 17.  | EKS CA - Cluster Autosaler |
| 18.  | EKS Monitoring using CloudWatch Agent & Fluentd - Container Insights |


## AWS Services Covered

| S.No | AWS Service Name |
| ---- | ---------------- |
| 1.   | AWS EKS - Elastic Kubernetes Service  |
| 2.   | AWS EBS - Elastic Block Store  |
| 3.   | AWS RDS - Relational Database Service MySQL  |
| 4.   | AWS CLB - Classic Load Balancer  |
| 5.   | AWS NLB - Network Load Balancer  |
| 6.   | AWS ALB - Application Load Balancer  |
| 7.   | AWS Fargate - Serverless  |
| 8.   | AWS ECR - Elastic Container Registry  |
| 9.   | AWS Developer Tool - CodeCommit  |
| 10.  | AWS Developer Tool - CodeBuild  |
| 11.  | AWS Developer Tool - CodePipeline  |
| 12.  | AWS X-Ray  |
| 13.  | AWS CloudWatch - Container Insights  |
| 14.  | AWS CloudWatch - Log Groups & Log Insights  |
| 15.  | AWS CloudWatch - Alarms  |
| 16.  | AWS Route53  |
| 17.  | AWS Certificate Manager  |
| 18.  | EKS CLI - eksctl  |


## Kubernetes Concepts Covered

| S.No | Kubernetes Concept Name |
| ---- | ------------------- |
| 1.   | Kubernetes Architecture  |
| 2.   | Pods  |
| 3.   | ReplicaSets  |
| 4.   | Deployments  |
| 5.   | Services - Node Port Service  |
| 6.   | Services - Cluster IP Service  |
| 7.   | Services - External Name Service  |
| 8.   | Services - Ingress Service  |
| 9.   | Services - Ingress SSL & SSL Redirect  |
| 10.  | Services - Ingress & External DNS  |
| 11.  | Imperative - with kubectl  |
| 12.  | Declarative - Declarative with YAML  |
| 13.  | Secrets |
| 14.  | Init Containers |
| 15.  | Liveness & Readiness Probes |
| 16.  | Requests & Limits |
| 17.  | Namespaces - Imperative |
| 18.  | Namespaces - Limit Range |
| 19.  | Namespaces - Resource Quota |
| 20.  | Storage Classes |
| 21.  | Persistent Volumes |
| 22.  | Persistent Volume Claims |
| 23.  | Services - Load Balancers |
| 24.  | Annotations |
| 25.  | Canary Deployments |
| 26.  | HPA - Horizontal Pod Autoscaler |
| 27.  | VPA - Vertical Pod Autoscaler |
| 28.  | CA - Cluster Autoscaler |
| 29.  | DaemonSets |
| 30.  | DaemonSets - Fluentd for logs |
| 31.  | Config Maps |

