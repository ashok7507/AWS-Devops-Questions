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
2. What are the different database engines supported by Amazon RDS?
3. What is the difference between RDS and running a database on EC2?
4. What are the advantages of using RDS?
5. What is an RDS DB Instance?
6. What is an RDS Endpoint?
7. How do you connect to an RDS database?
8. What is a DB Subnet Group?
9. Why does RDS require a DB Subnet Group?
10. Why should an RDS database generally be placed in a Private Subnet?
11. What is Multi-AZ in RDS?
12. What is the difference between Multi-AZ and Read Replica?
13. Does Multi-AZ improve read performance?
14. How does automatic failover work in RDS Multi-AZ?
15. What happens to the RDS endpoint during a Multi-AZ failover?
16. What is an RDS Read Replica?
17. How does replication work in RDS Read Replicas?
18. Can a Read Replica be created in another AWS Region?
19. Can a Read Replica be promoted to a standalone database?
20. What is the difference between Read Replica and Database Backup?
21. How do you create an RDS Read Replica?
22. What are the limitations of RDS Read Replicas?
23. What is an RDS automated backup?
24. What is the backup retention period in RDS?
25. What is a manual RDS snapshot?
26. What is the difference between automated backup and manual snapshot?
27. How do you restore an RDS database from a snapshot?
28. Can you restore an RDS snapshot to another AWS Region?
29. What is Point-in-Time Recovery in RDS?
30. How would you recover an RDS database after accidental data deletion?
31. What is an RDS Parameter Group?
32. What is an RDS Option Group?
33. What is the difference between Parameter Group and Option Group?
34. How do you modify RDS database parameters?
35. What is a Static Parameter and Dynamic Parameter in RDS?
36. Why does an RDS parameter change sometimes require a reboot?
37. What is an RDS Security Group?
38. How do you allow an EC2 instance to connect to RDS securely?
39. Why should you avoid allowing 0.0.0.0/0 access to an RDS database?
40. What port does MySQL use by default?
41. What port does PostgreSQL use by default?
42. What port does MariaDB use by default?
43. How do you change the default RDS database port?
44. What is RDS encryption?
45. How do you enable encryption for RDS?
46. Can encryption be enabled directly on an existing unencrypted RDS instance?
47. How can you encrypt an existing unencrypted RDS database?
48. What is AWS KMS and how is it used with RDS?
49. What happens if the KMS key used by RDS is disabled?
50. What is RDS Performance Insights?
51. What is Enhanced Monitoring in RDS?
52. What is the difference between CloudWatch Monitoring and Enhanced Monitoring?
53. Which CloudWatch metrics are important for RDS?
54. What is CPUUtilization in RDS?
55. What is FreeStorageSpace in RDS?
56. What is FreeableMemory in RDS?
57. What is DatabaseConnections in RDS?
58. What is ReadIOPS and WriteIOPS?
59. What is ReadLatency and WriteLatency?
60. What is DiskQueueDepth?
61. How would you troubleshoot high CPU utilization in RDS?
62. How would you troubleshoot high database connections?
63. How would you troubleshoot low FreeStorageSpace?
64. How would you troubleshoot high Read/Write latency?
65. What would you check if an application cannot connect to RDS?
66. EC2 and RDS are in the same VPC but the connection is failing. How will you troubleshoot it?
67. EC2 can ping RDS but cannot connect to the database port. What will you check?
68. RDS connection is timing out. What could be the possible reasons?
69. What will you check if RDS returns "Connection refused"?
70. How do Security Groups affect RDS connectivity?
71. How do Route Tables affect RDS connectivity?
72. How do NACLs affect RDS connectivity?
73. How do you check whether an RDS endpoint is resolving correctly?
74. How do you test connectivity from EC2 to RDS?
75. What Linux command can you use to test an RDS port?
76. How do you connect to a MySQL RDS database from Linux?
77. How do you connect to a PostgreSQL RDS database from Linux?
78. What is the difference between RDS endpoint and IP address?
79. Why should applications use the RDS endpoint instead of a hardcoded IP?
80. What happens to the RDS endpoint after a Multi-AZ failover?
81. What is RDS maintenance?
82. What is a Maintenance Window?
83. What is a Backup Window?
84. What happens during RDS maintenance?
85. What is an RDS minor version upgrade?
86. What is the difference between Minor and Major version upgrades?
87. How do you perform an RDS version upgrade safely in production?
88. What is the difference between Storage Autoscaling and manually increasing RDS storage?
89. How do you increase RDS storage?
90. Can you decrease the allocated storage of an RDS instance?
91. What is the maximum storage supported by RDS?
92. What are the different RDS storage types?
93. What is General Purpose SSD in RDS?
94. What is Provisioned IOPS in RDS?
95. When would you choose Provisioned IOPS over General Purpose SSD?
96. How would you reduce RDS costs in a production environment?
97. How do you stop an RDS instance?
98. What are the limitations of stopping an RDS instance?
99. What happens if you stop an RDS instance for a long period?
100. How would you design a highly available RDS architecture for production?
101. How would you design RDS for disaster recovery?
102. How would you migrate a database from EC2 to RDS?
103. How would you migrate an on-premises database to RDS?
104. How would you perform a zero/minimal-downtime database migration?
105. How would you securely store RDS database credentials?
106. What is AWS Secrets Manager?
107. How can an application retrieve RDS credentials from Secrets Manager?
108. How do you rotate RDS database credentials automatically?
109. What IAM permissions are required to access RDS credentials from Secrets Manager?
110. What is RDS Proxy?
111. Why would you use RDS Proxy?
112. How does RDS Proxy help with database connection management?
113. What is the difference between RDS Proxy and Read Replica?
114. How would you troubleshoot an RDS Proxy target that is not available?
115. How would you configure RDS Proxy with Secrets Manager?
116. What is an RDS event notification?
117. How can you receive an SNS notification when RDS fails over?
118. How would you create a CloudWatch alarm for high RDS CPU?
119. How would you create an alarm for low RDS free storage?
120. Your production application is unable to connect to RDS. Explain your complete troubleshooting approach.
121. RDS CPU is continuously above 90%. How will you troubleshoot and resolve it?
122. RDS storage is almost full. What immediate and long-term actions will you take?
123. RDS connections are reaching the maximum limit. How will you troubleshoot it?
124. RDS Multi-AZ failover occurred unexpectedly. How will you investigate the root cause?
125. RDS Read Replica lag is increasing. What could be the reasons and how will you troubleshoot it?
126. Database performance suddenly became slow after a deployment. How will you investigate it?
127. How would you monitor RDS using CloudWatch, Performance Insights, and Enhanced Monitoring?
128. How would you secure RDS in a production environment?
129. How would you implement backup, recovery, monitoring, and alerting for RDS?
130. How would you design a production-ready RDS architecture with high availability, security, performance, and disaster recovery?


---  

## Cloud Watch  

---  
1. What is Amazon CloudWatch?
2. What are the main components of CloudWatch?
3. What is a CloudWatch Metric?
4. What is a CloudWatch Namespace?
5. What is a CloudWatch Dimension?
6. What is a CloudWatch Statistic?
7. What is the difference between Average, Sum, Minimum, Maximum, and Sample Count?
8. What is a CloudWatch Alarm?
9. How does a CloudWatch Alarm work?
10. What are the different states of a CloudWatch Alarm?
11. What is the difference between OK, ALARM, and INSUFFICIENT_DATA?
12. What is CloudWatch Logs?
13. What is a CloudWatch Log Group?
14. What is a CloudWatch Log Stream?
15. What is the difference between Log Group and Log Stream?
16. How do you send application logs to CloudWatch?
17. How do you send EC2 logs to CloudWatch?
18. What is the CloudWatch Agent?
19. Why do we use the CloudWatch Agent?
20. What is the difference between CloudWatch Agent and default EC2 monitoring?
21. What is Basic Monitoring in EC2?
22. What is Detailed Monitoring in EC2?
23. What is the default EC2 CloudWatch monitoring interval?
24. What additional metrics can be collected using the CloudWatch Agent?
25. Does CloudWatch collect RAM utilization by default for EC2?
26. How can you monitor RAM utilization of an EC2 instance?
27. How can you monitor disk utilization of an EC2 instance?
28. How can you monitor disk space using CloudWatch?
29. What are the important EC2 CloudWatch metrics?
30. What is CPUUtilization?
31. What is NetworkIn?
32. What is NetworkOut?
33. What is StatusCheckFailed?
34. What is StatusCheckFailed_Instance?
35. What is StatusCheckFailed_System?
36. How do you create a CloudWatch Alarm for high CPU utilization?
37. How do you configure an alarm when CPU goes above 80%?
38. How do you configure an alarm when CPU remains above 80% for 5 minutes?
39. How can CloudWatch Alarm trigger an SNS notification?
40. What is Amazon SNS?
41. How can CloudWatch automatically restart an EC2 instance?
42. How can CloudWatch automatically recover an EC2 instance?
43. What is EC2 Auto Recovery?
44. What is the difference between EC2 Auto Recovery and Auto Scaling?
45. What is CloudWatch Dashboard?
46. How do you create a CloudWatch Dashboard?
47. What is a Custom CloudWatch Dashboard?
48. How can you monitor multiple EC2 instances using one dashboard?
49. How can you monitor CPU, memory, disk, and network metrics on one dashboard?
50. What is CloudWatch Logs Insights?
51. How do you search logs using CloudWatch Logs Insights?
52. What is a CloudWatch Logs Insights query?
53. How do you find ERROR messages in CloudWatch Logs?
54. How do you find the latest application errors using Logs Insights?
55. How do you search logs for a specific IP address?
56. How do you filter logs based on status code such as 500?
57. What is a Metric Filter in CloudWatch Logs?
58. How can you create a metric from application logs?
59. How can you create an alarm when the word ERROR appears in logs?
60. What is CloudWatch Logs Retention?
61. How do you configure log retention in CloudWatch?
62. Why should you configure log retention?
63. How would you reduce CloudWatch Logs costs?
64. What is CloudWatch Events?
65. What is Amazon EventBridge?
66. What is the difference between CloudWatch Events and EventBridge?
67. How can EventBridge trigger a Lambda function?
68. How can CloudWatch detect an EC2 instance state change?
69. How can you automatically stop an EC2 instance at a specific time using AWS services?
70. How can you automatically start an EC2 instance at a specific time?
71. What is CloudWatch Synthetics?
72. What is a CloudWatch Canary?
73. How can CloudWatch monitor application availability?
74. How can CloudWatch monitor an HTTP/HTTPS endpoint?
75. What is CloudWatch Application Signals?
76. What is CloudWatch ServiceLens?
77. What is CloudWatch Container Insights?
78. How can you monitor Docker containers using CloudWatch?
79. How can you monitor ECS using CloudWatch?
80. How can you monitor EKS using CloudWatch?
81. What is CloudWatch Container Insights used for?
82. How can you monitor Lambda using CloudWatch?
83. What are the important CloudWatch metrics for Lambda?
84. What is Lambda Duration?
85. What is Lambda Errors?
86. What is Lambda Invocations?
87. What is Lambda Throttles?
88. How would you troubleshoot a Lambda function with high error rates using CloudWatch?
89. How can you monitor RDS using CloudWatch?
90. What are the important CloudWatch metrics for RDS?
91. What is RDS CPUUtilization?
92. What is RDS FreeStorageSpace?
93. What is RDS DatabaseConnections?
94. What is RDS FreeableMemory?
95. How would you create an RDS alarm for low free storage?
96. How would you create an RDS alarm for high CPU utilization?
97. How can you monitor Application Load Balancer using CloudWatch?
98. What are important CloudWatch metrics for an ALB?
99. What is RequestCount?
100. What is TargetResponseTime?
101. What is HTTPCode_ELB_5XX_Count?
102. What is HTTPCode_Target_5XX_Count?
103. What is HealthyHostCount?
104. How would you troubleshoot high 5XX errors using CloudWatch?
105. How would you troubleshoot high response time using CloudWatch?
106. How can you monitor S3 using CloudWatch?
107. What are important S3 CloudWatch metrics?
108. How can you monitor SQS using CloudWatch?
109. What are important SQS CloudWatch metrics?
110. What is ApproximateNumberOfMessagesVisible?
111. How can you create an alarm when an SQS queue has too many messages?
112. How can you monitor DynamoDB using CloudWatch?
113. What are important DynamoDB CloudWatch metrics?
114. How can you monitor NAT Gateway using CloudWatch?
115. What are important NAT Gateway CloudWatch metrics?
116. How can you monitor VPN connections using CloudWatch?
117. What is a CloudWatch Composite Alarm?
118. What is the advantage of using Composite Alarms?
119. What is Anomaly Detection in CloudWatch?
120. How does CloudWatch Anomaly Detection work?
121. What is CloudWatch Contributor Insights?
122. What is CloudWatch Metric Math?
123. How can you calculate a custom metric using Metric Math?
124. What is a High-Resolution Metric?
125. What is the difference between Standard and High-Resolution Metrics?
126. What is a Custom Metric?
127. How do you publish a Custom Metric to CloudWatch?
128. How can an application send custom metrics to CloudWatch?
129. What IAM permissions are required to publish CloudWatch metrics?
130. What IAM permissions are required to write logs to CloudWatch?
131. What is the CloudWatch Agent configuration file?
132. Where is the CloudWatch Agent configuration stored on Linux?
133. How do you install the CloudWatch Agent on Ubuntu?
134. How do you start and stop the CloudWatch Agent?
135. How do you check whether the CloudWatch Agent is running?
136. How do you troubleshoot CloudWatch Agent if logs are not appearing?
137. EC2 CPU is high. How will you troubleshoot it using CloudWatch?
138. EC2 memory is high but CloudWatch does not show memory usage. What will you do?
139. EC2 disk is 90% full. How will you create an alarm for it?
140. Application logs are not appearing in CloudWatch. How will you troubleshoot it?
141. CloudWatch Alarm is stuck in INSUFFICIENT_DATA. What could be the reason?
142. CloudWatch Alarm is not sending an SNS notification. How will you troubleshoot it?
143. CloudWatch shows an EC2 instance as healthy, but the application is down. How will you investigate it?
144. Application response time suddenly increases. How will you use CloudWatch to troubleshoot it?
145. Production server CPU suddenly reaches 100%. Explain your complete CloudWatch troubleshooting approach.
146. How would you monitor EC2, RDS, ALB, and application logs from a single CloudWatch Dashboard?
147. How would you design CloudWatch monitoring and alerting for a production DevOps environment?
148. How would you implement centralized logging and monitoring for multiple EC2 instances?
149. How would you design CloudWatch alarms to avoid unnecessary alerts and alert fatigue?
150. How would you build a complete production monitoring solution using CloudWatch, SNS, Lambda, and EventBridge?

---  

## Terraform 

**1. What is Terraform?**

**2. What language does Terraform use?**

**3. What does "declarative" mean in Terraform's context?**

**4. What is a Provider in Terraform?**

**5. What is a Resource in Terraform?**

**6. What is a Terraform Variable?**

**7. What is a Terraform Output?**

**8. What does `terraform init` do?**

**9. What does `terraform plan` do?**

**10. What does `terraform apply` do?**

**11. What does `terraform destroy` do?**

**12. What does `terraform validate` do?**

**13. What does `terraform fmt` do?**

**14. What does `terraform show` do?**

**15. What does `terraform output` do?**

**16. What is `terraform apply -auto-approve` used for?**

**17. What does `terraform destroy -target <resource>` do?**

**21. What does `terraform apply -refresh-only` do?**

**22. What is `terraform get` used for?**

**23. What is `terraform version` used for?**

**24. What file extension do Terraform files use?**

**25. What is `main.tf` typically used for?**

**26. What is the Terraform State file?**

**27. Is Terraform open-source or paid?**

**28. Name a few cloud providers Terraform supports.**

**29. What is the Terraform Registry?**

**30. What is a `.tfvars` file used for?**

**31. What is IaC (Infrastructure as Code)?**

**32. What is Idempotency, and why does it matter in Terraform?**

**33. What is Mutable vs Immutable Infrastructure?**

**34. What is the basic difference between Terraform and AWS CloudFormation?**

**35. What are the different types of blocks in Terraform?**

**36. What is the `terraform {}` block used for?**

**37. What is a `locals` block?**

**38. What is the difference between a variable and a local?**

**39. What is the difference between a resource block and a data block?**

**40. What is the purpose of a module block?**

**41. What is the purpose of a data block?**

**42. What basic data types does Terraform support?**

**47. What is the `.terraform` folder?**

**48. What is `terraform.lock.hcl`?**

**49. Should you commit `.tfstate` to Git?**

**50. Should you commit the `.terraform/` directory to Git?**

**51. What files should typically be added to `.gitignore` in a Terraform project?**

**52. What is a Terraform variable?**

**53. Why are variables used instead of hardcoded values?**

**54. How do you define a variable in Terraform?**

**55. How do you pass values to Terraform variables?**

**56. What is the difference between `variables.tf` and `terraform.tfvars`?**

**57. What is a default value for a Terraform variable?**

**58. What are variable types in Terraform?**

**59. What is variable validation in Terraform?**

**60. What is a Terraform output?**

**61. Why are outputs used in Terraform?**

**64. What are Terraform built-in functions?**

**79. What is a Provisioner in Terraform?**

**81. What is the difference between `local-exec` and `remote-exec`?**

**82. Where does `local-exec` run?**

**83. Where does `remote-exec` run?**

**84. What is `count` in Terraform?**

**86. How do you create multiple resources using `count`?**

**98. What is the difference between `terraform plan` and `terraform apply`?**

**99. What is the difference between `terraform.tfvars` and `variables.tf`?**

**100. What is the difference between a provider and a resource in Terraform?**

**101. What is the difference between a variable and an output?**

**104. Why does Terraform use a state file?**

**107. Why is `terraform plan` important before `terraform apply`?**

**108. Why is `terraform init` required before most Terraform commands?**

**109. Why is Terraform called an Infrastructure as Code tool?**

**110. What are the main advantages of using Terraform?**
