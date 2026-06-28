Complete DevOps Interview Question Bank
---------------------------------------------------------------------------------------------------------------------------------------------
1. Linux:

Explain the Linux boot process.
What are the major Linux directories and their purpose?
Difference between Hard Link and Soft Link.
Difference between Process and Thread.
What is a Zombie process?
What is an Orphan proce
Difference between Cron and Anacron.

Commands:

How do you check open ports?
How do you find which process is using a port?
Difference between top and htop.
Explain grep, awk, sed, cut, sort, uniq.
Explain find vs locate.
How do you monitor CPU, Memory and Disk usage?
Commands you use daily as a DevOps Engineer.

Networking:

Difference between TCP and UDP.
Explain SSH.
How DNS resolution works.
Explain CIDR.
Difference between Public IP and Private IP.
Difference between NAT and PAT.
Explain Load Balancing.
Troubleshooting
Server is slow. How do you troubleshoot?
Disk is full. What will you do?
How do you analyze application logs?
Explain the Linux permission model.
---------------------------------------------------------------------------------------------------------------------------------------------
3. Git & GitHub
Git Basics
What is Git?
Difference between Git and GitHub.
Explain Git workflow.
Branching
Explain your Git branching strategy.
What is GitFlow?
What is Trunk-Based Development?
Difference between Feature Branch and Release Branch.
Commands
Difference between Git Fetch, Pull and Merge.
Difference between Merge and Rebase.
What is Cherry Pick?
What is Squash Merge?
Conflict Resolution
How do you resolve merge conflicts?
How do you revert a bad commit?
Difference between Reset, Revert and Restore.
Best Practices
How do you secure Git repositories?
How do you protect the main branch?
---------------------------------------------------------------------------------------------------------------------------------------------
4. Jenkins

Jenkins Basics
What is Jenkins?
Explain Jenkins architecture.
Explain Master-Agent architecture.
How do Jenkins agents communicate with the controller?

Pipelines
Difference between Freestyle and Pipeline.
Difference between Declarative and Scripted Pipeline.
Which pipeline type have you used?
Pipeline Stages

Explain your CI/CD pipeline end-to-end.

Typical stages:

Checkout
Build
Unit Testing
Static Code Analysis
Security Scan
Package
Artifact Upload
Docker Build
Docker Push
Deployment
Smoke Test
Notifications

Jenkins Concepts
What are Environment Variables?
What is agent any?
Difference between node and agent.
What are Shared Libraries?

Security
How do you secure Jenkins?
How do you secure credentials?
Explain Role-Based Access Control.
How do you optimize Jenkins performance?
Integrations
How do you integrate SonarQube?
How do you integrate Nexus?
How do you integrate Docker?
How do you integrate Kubernetes?
How do you trigger pipelines automatically?
Troubleshooting
How do you debug a failed pipeline?
How do you restart a failed stage?
How do you troubleshoot Jenkins performance issues?
---------------------------------------------------------------------------------------------------------------------------------------------
4. Maven

Basics
What is Maven?
Explain Maven architecture.
What is pom.xml?

Lifecycle
Explain Maven lifecycle.

validate
compile
test
package
verify
install
deploy

Commands

Difference between compile, package, install and deploy.
What does mvn clean do?
What does mvn compile do?
Dependency Management
Explain dependencies.
What is Dependency Scope?
What are SNAPSHOT versions?
Packaging
How do you package an application?
Difference between JAR and WAR.
---------------------------------------------------------------------------------------------------------------------------------------------
5. Artifact Repository (Nexus / Artifactory)

What is an Artifact Repository?
Why do we need Nexus?
Where do you store artifacts?
How do you version artifacts?
Difference between Release and Snapshot repositories.
How do you clean old artifacts?
How do you secure Nexus?
Explain the artifact promotion process.
---------------------------------------------------------------------------------------------------------------------------------------------
6. Docker

Basics
What is Docker?
Difference between Virtual Machine and Docker.
Explain Docker architecture.
Dockerfile
Explain Dockerfile.
Explain each Dockerfile instruction.
Difference between CMD and ENTRYPOINT.
Difference between COPY and ADD.
Difference between ARG and ENV.
Multi-stage Builds
Why use Multi-stage Dockerfiles?
Write a Multi-stage Dockerfile.

Docker Components
Difference between Dockerfile, Image and Container.
Difference between Image and Layer.

Networking
How do containers communicate?
How do you expose a container on a specific port?
Docker Compose
What is Docker Compose?
Why use Docker Compose?
Why use Kubernetes if Docker Compose exists?

Commands
Explain commonly used Docker commands.

Examples:

docker ps
docker ps -a
docker images
docker logs
docker exec
docker inspect
docker build
docker pull
docker push
docker rm
docker system prune

Troubleshooting
How do you debug a failed container?
How do you reduce Docker image size?
How do you scan Docker images for vulnerabilities?
---------------------------------------------------------------------------------------------------------------------------------------------
7. Kubernetes

Architecture
Explain Kubernetes architecture.
Explain Control Plane components.
Explain Worker Node components.
What happens if etcd goes down?

Pods
What is a Pod?
Pod lifecycle.
Init Containers.
Sidecar Containers.
Multi-container Pods.

Replica Management
What are ReplicaSets?
What are Replicas?
Workloads
Deployment vs StatefulSet.
DaemonSet.
Job vs CronJob.

Services
Explain Kubernetes Services.
Types of Services.
ClusterIP
NodePort
LoadBalancer
ExternalName

Networking
Service Discovery.
How Pods communicate.
How Microservices communicate.
Explain Kubernetes DNS.
Explain CNI plugins.

Ingress
What is Ingress?
What is Ingress Controller?
Difference between Ingress and LoadBalancer.
Which Ingress Controller have you used?
Difference between Layer 4 and Layer 7 routing.

Types of routing:
Host-based
Path-based
Header-based
TLS routing

Storage
PV
PVC
StorageClass
Dynamic Provisioning

Configurations
ConfigMaps
Secrets

Environment Variables
Secret Injection methods

Scheduling
Node Selector
Taints
Tolerations
Node Affinity
Pod Affinity
Pod Anti-Affinity

Security
RBAC
Service Accounts
Network Policies
Pod Security Standards
Secret Management
Image Security

Scaling
Horizontal Pod Autoscaler
Vertical Pod Autoscaler
Cluster Autoscaler

Deployment Strategies
Rolling Update
Recreate
Blue-Green
Canary
A/B Testing

Rollbacks
How do you rollback deployments?
How do you debug failed deployments?

Troubleshooting
CrashLoopBackOff
ImagePullBackOff
Pending Pods
OOMKilled
Failed Scheduling
Node NotReady

Cluster Operations
How do you upgrade Kubernetes?
How do you drain a node?
What does cordon do?
Explain Pod Disruption Budget.
Daily kubectl commands.

8. Terraform
Basics
What is Infrastructure as Code?
Why Terraform?
Why Terraform over CloudFormation, ARM or Pulumi?
Architecture
Explain Terraform workflow.
Terraform lifecycle.

State
What is Terraform State?
Where do you store state?
Remote Backend.
State Locking.
State Security.

Variables
Variables
Locals
Outputs
tfvars

Resources
Difference between Resource and Data Source.
Count vs For_each.
Dynamic Blocks.

Modules
What are Modules?
Module Versioning.
Registry Modules.
How do you apply a specific module?

Workspaces
What are Workspaces?
Multi-environment deployment.

Lifecycle
lifecycle block
create_before_destroy
ignore_changes
prevent_destroy
Deployment
terraform init
plan
apply
destroy

Troubleshooting
State corruption.
Lost state file.
Simultaneous apply.
Partial apply failures.
Drift detection.
Manual AWS changes.
Import existing resources.

Security
How do you secure state files?
How do you handle secrets?
Sensitive variables.
Secret Managers integration.
---------------------------------------------------------------------------------------------------------------------------------------------
9. CI/CD (Missing)

These are frequently asked but missing.

What is Continuous Integration?
What is Continuous Delivery?
What is Continuous Deployment?
Difference between CI, CD and CD.
Explain your end-to-end CI/CD process.
How do you rollback deployments?
How do you implement approval gates?
How do you version releases?
---------------------------------------------------------------------------------------------------------------------------------------------
10. SonarQube 
What is SonarQube?
How does SonarQube work?
What are Quality Gates?
What happens if the Quality Gate fails?
Which metrics do you monitor?
How do you integrate SonarQube with Jenkins?
---------------------------------------------------------------------------------------------------------------------------------------------
11. Nexus / Artifactory (Missing)
What is Nexus?
Explain Hosted, Proxy and Group repositories.
Snapshot vs Release repositories.
How do you promote artifacts?
Cleanup policies.
---------------------------------------------------------------------------------------------------------------------------------------------
12. AWS / Cloud (Very Important - Missing)

EC2
Explain EC2.
Security Groups vs NACL.
EBS vs EFS.
Networking

VPC
Subnets
Route Tables
Internet Gateway
NAT Gateway

IAM
IAM Users
Roles
Policies
Least Privilege
Storage

S3
Lifecycle Policies
Versioning
Load Balancing
ALB
NLB
Target Groups

Scaling
Auto Scaling Groups

Monitoring
CloudWatch
CloudTrail

Database
RDS
---------------------------------------------------------------------------------------------------------------------------------------------
13. Monitoring 

Explain Prometheus architecture.
What are Exporters?
What are PromQL queries?

Explain Grafana.
How do you create dashboards?

Explain AlertManager.
How do alerts work?

What metrics do you monitor?
---------------------------------------------------------------------------------------------------------------------------------------------
14. Logging 
ELK Stack.
EFK Stack.
Fluentd vs Fluent Bit.
Logstash.
Kibana.
Centralized logging.
---------------------------------------------------------------------------------------------------------------------------------------------
15. Security 

DevSecOps.
Shift Left Security.
SAST vs DAST vs SCA.

Trivy.
OWASP Top 10.
Container Image Scanning.
Secret Management.
Vault.
IAM Best Practices.
Least Privilege.
---------------------------------------------------------------------------------------------------------------------------------------------
16. Helm (Very Common - Missing)
What is Helm?
Helm Chart structure.
values.yaml.
Helm lifecycle.
Helm upgrade.
Helm rollback.
Helm hooks.
Difference between Helm and Kustomize.
---------------------------------------------------------------------------------------------------------------------------------------------
17. Ansible (If Mentioned in Resume)
What is Ansible?
Inventory.
Playbooks.
Roles.
Variables.
Idempotency.
Vault.
---------------------------------------------------------------------------------------------------------------------------------------------
18. Scenario-Based Questions (Most Important)

These are among the most common interview questions for experienced DevOps engineers:

Your production deployment failed. What are your immediate steps?
Jenkins pipeline is failing after a successful build. How do you debug it?
Kubernetes pods are in CrashLoopBackOff. Walk through your troubleshooting process.
A pod cannot connect to the database. How would you diagnose the issue?
terraform apply fails halfway through after creating some resources. How do you recover?
Two engineers run terraform apply simultaneously. What happens, and how is it prevented?
Someone manually modifies infrastructure in the cloud console. How do you detect and prevent configuration drift?
Docker container exits immediately after startup. How do you troubleshoot it?
Kubernetes deployment completed successfully, but the application is inaccessible. How would you investigate?
A node becomes NotReady. What steps do you take?
The application is slow in production, but CPU usage is low. What would you check?
Your cluster is running out of resources. How do you identify the cause and resolve it?
How would you migrate a monolithic application to Kubernetes?
Explain your end-to-end CI/CD pipeline for a microservices application, including build, test, security scanning, artifact management, containerization, deployment, and rollback.
