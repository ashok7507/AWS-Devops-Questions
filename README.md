## EC2  
---  
1. What is Amazon EC2?
2. How would you reduce the EC2 cost?
3. What is Instance?
4. What are the different EC2 instance types?
5. What are the different pricing models available for Amazon EC2?
6. What is the difference between On-Demand, Reserved, Spot, and Savings Plans?
7. What is an Dedicated host?
8. What is Templates?
9. What is an AMI?
10. What is different AMI and Template?
11. what is another name of AMI?
12. What is EBS?
13. What is volume and different types of Volume?
14. What is snapshot?
15. What is a Security Group?
16. What is the difference between Security Group and NACL?
17. Is a Security Group stateful or stateless?
18. What is an Elastic IP?
19. What is placement group?
20. What is Key pair?
21. What is Network interface?
22. What is load balancer and Types of load balancer?
23. What is auto scaling and types of auto scaling?
24. What happens when you stop and start an EC2 instance?
25. What is the difference between stop, reboot, and terminate?
26. How do you secure your aws RDS logs.
---  
## IAM  

---
1. What is AWS IAM?
2. What are the main components of IAM?
3. What is an IAM User?
4. What is an IAM Group?
5. What is an IAM Role?
6. What is an IAM Policy?
7. What is the difference between IAM User, Group, Role, and Policy?
8. What is the difference between IAM Role and IAM User?
9. What is the difference between IAM Policy and IAM Role?
10. What is the difference between AWS Managed Policy and Customer Managed Policy?
11. What is an Inline Policy?
12. What is the difference between Inline Policy and Managed Policy?
13. What is the Principle of Least Privilege?
22. What is the difference between identity-based and resource-based policies?
23. What is access key and secret key?
24. what is MFA?
---  
## SNS  
1. What is SNS?
2. What is topic and its types?
3. What is subscriptions and its types?
4. What is secret Manager?


## S3  

---
1. What is Amazon S3?
2. What are the main components of S3?
3. What is an S3 Bucket?
4. What are different types of s3 bucket?
5. What is an S3 Object?
6. What is S3 Versioning?
7. What is s3 bucket lifecycle policies?
8. What is ACL in bucket?
9. What is SSE and CSE?
10. What is the maximum size of an S3 object?
11. What is the maximum number of objects that can be stored in an S3 bucket?
12. What is the difference between S3 and EBS?
13. What is the difference between S3 and EFS?
14. What are the different S3 Storage Classes?
15. What is S3 Standard?
16. What is S3 Intelligent class?
17. What is S3 Standard-IA?
18. What is S3 One Zone-IA?
19. What is S3 Glacier Instant Retrieval?
20. What is S3 Glacier Flexible Retrieval?
21. What is S3 Glacier Deep Archive?
22. How do you choose the correct S3 Storage Class?
23. What is S3 Versioning?
67. What is S3 Static Website Hosting?
68. How do you host a static website using S3?
70. What is the difference between S3 Static Website Hosting and CloudFront?
---  

## VPC  

---  
1. What is Amazon VPC?
2. What is subnet?
3. What is an Internet Gateway?
4. What is a Route Table?
5. What is a NAT Gateway?
6. What is VPC Peering?
7. What is a Network ACL?
8. What is a VPC Endpoint?
9. What is an Availability Zone?
10. What is Transit Gateway?
11. What is target group?
12. What are the main components of a VPC?
13. What is a CIDR block?
14. What is the difference between VPC and Subnet?
15. What is a Public Subnet?
16. What is a Private Subnet?
17. What is the difference between Public and Private Subnet?
19. How does an Internet Gateway provide internet access to a VPC?
21. What is the difference between NAT Gateway and Internet Gateway?
22. Why do we use NAT Gateway in a Private Subnet?
24. What is the difference between Main Route Table and Custom Route Table?
25. How does routing work inside a VPC?
28. What does a Blackhole route mean in a Route Table?

---  

## RDS  

---  
1. What is Amazon RDS?
2. Why do we use RDS instead of installing a database on an EC2 instance?
3. Which database engines does RDS support?
4. What is a DB Subnet Group?
5. What is a DB Parameter Group?
6. What is a DB Security Group?
7. What is an RDS endpoint?
8. How does an application connect to an RDS database?
9. What is an RDS snapshot?
10. What is the difference between RDS and running a database on an EC2 instance?
11. What is a parameter group in RDS?
12. What are RDS endpoints?
13. What happens when the primary RDS instance fails in a Multi-AZ setup?
14. How do you restore an RDS database?
15. What is Point-in-Time Recovery?
16. How do you secure an RDS database?
17. How would you manage database credentials securely?
18. How do you monitor RDS?
19. Which RDS metrics would you monitor?
20. An RDS database has suddenly become very slow. What would you check first?

---  

## Cloud Watch  

---  
1. What is Amazon CloudWatch?
2. What are the main components of CloudWatch?
3. What is a CloudWatch Metric?
4. What is a CloudWatch Namespace?
8. What is a CloudWatch Alarm?
10. What are the different states of a CloudWatch Alarm?
11. What is the difference between OK, ALARM, and INSUFFICIENT_DATA?
12. What is CloudWatch Logs?
13. What is a CloudWatch Log Group?
17. How do you send EC2 logs to CloudWatch?
18. What is the CloudWatch Agent?
19. Why do we use the CloudWatch Agent?
20. What is the difference between CloudWatch Agent and default EC2 monitoring?
21. What is Basic Monitoring in EC2?
22. What is Detailed Monitoring in EC2?
38. How do you configure an alarm when CPU remains above 80% for 5 minutes?
39. How can CloudWatch Alarm trigger an SNS notification?
40. What is Amazon SNS?
41. How can CloudWatch automatically restart an EC2 instance?
45. What is CloudWatch Dashboard?
46. What are diffrent types of cloudwatch dashbord?
47. How do you create a CloudWatch Dashboard?
48. What is a Custom CloudWatch Dashboard?

---  
## Route-53  
1. What is Amazon Route 53?
2. What is DNS?
3. What is a Hosted Zone?
4. What are DNS Records?
5. What are Route 53 routing policies?
6. What is Route 53 Health Check?
7. What is diffrence between Public vs Private Hosted Zone?
8. What is the difference between A, CNAME, and Alias records?
9. I have an application running on two EC2 instances. If one instance goes down, users should automatically be redirected to the healthy instance. How would you design this?

## Terraform 

**1. What is Terraform?**   
**2. What language does Terraform use?**  
**3. What is a Provider in Terraform?**  
**5. What is a Resource in Terraform?**  
**6. What is a Terraform Variable?**  
**7. What is a Terraform Output?**  
**8. What does `terraform init` do?**  
**9. What does `terraform plan` do?**  
**10. What does `terraform apply` do?**  
**11. What does `terraform destroy` do?**  
**12. What does `terraform validate` do?**  
**13. What does `terraform show` do?**  
**14. What does `terraform output` do?**  
**15. What is `terraform apply -auto-approve` used for?**  
**16. What does `terraform destroy -target <resource>` do?**  
**17. What file extension do Terraform files use?**  
**18. What is `main.tf` typically used for?**  
**19. What is the Terraform State file?**  
**20. Is Terraform open-source or paid?**  
**21. Name a few cloud providers Terraform supports.**  
**22. What is the Terraform Registry?**  
**23. What is a `.tfvars` file used for?**  
**24. What is IaC (Infrastructure as Code)?**  
**25. What is Mutable vs Immutable Infrastructure?**  
**26. What is the basic difference between Terraform and AWS CloudFormation?**  
**27. What is the `terraform {}` block used for?**  
**28. What is the purpose of a module block?**  
**29. What is the `.terraform` folder?**  
**30. What is `terraform.lock.hcl`?**  
**31. Should you commit `.tfstate` to Git?**  
**32. Should you commit the `.terraform/` directory to Git?**  
**33. What is a Terraform variable?**  
**34. What is the difference between `variables.tf` and `terraform.tfvars`?**  
**35. What is a Terraform output?**  
**36. Why are outputs used in Terraform?**  
**37. What is a Provisioner in Terraform?**  
**38. What is the difference between `local-exec` and `remote-exec`?**  
**39. What is the difference between `terraform plan` and `terraform apply`?**  
**40. Why is Terraform called an Infrastructure as Code tool?**  
**41. What is terraform plugins?**  
**42. Which terraform language used to write terraform code?**
**43. What is difference between terraform and cloud formation?**
