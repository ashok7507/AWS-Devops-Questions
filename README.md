## EC2  
---  
1. What is Amazon EC2?
2. What are the different EC2 instance types?
3. What is the difference between On-Demand, Reserved, Spot, and Savings Plans?
4. What happens when you stop and start an EC2 instance?
5. What is the difference between stop, reboot, and terminate?
6. What is an AMI?
7. How do you create an AMI from an existing EC2 instance?
8. What is the difference between Public IP and Elastic IP?
9. What happens to the Public IP after stopping and starting an EC2 instance?
10. How do you connect to a Linux EC2 instance?
11. What is a Security Group?
12. What is the difference between Security Group and NACL?
13. Is a Security Group stateful or stateless?
14. Can you SSH into an EC2 instance without opening port 22?
15. How would you restrict SSH access to only your office IP?
16. What happens if port 80 is open in the Security Group but the application is not accessible?
17. How do you troubleshoot a Connection Timed Out error while connecting to EC2?
18. How do you troubleshoot Permission Denied (publickey) error?
19. What is an IAM Role for EC2?
20. Why is an IAM Role preferred over storing AWS access keys on an EC2 instance?
21. What is EBS?
22. What is the difference between EBS and Instance Store?
23. Can you increase an EBS volume size without stopping the EC2 instance?
24. After increasing EBS volume size, why might df -h still show the old size?
27. What happens to EBS when an EC2 instance is terminated?
28. What is an EBS Snapshot?
29. How would you restore an EC2 instance if its root volume is corrupted?
30. What is the difference between EBS Snapshot and AMI?
31. What is the difference between Public Subnet and Private Subnet?
32. How does an EC2 instance in a private subnet access the internet?
33. What is an Internet Gateway?
34. What is a NAT Gateway?
35. Why can't an EC2 instance in a private subnet directly receive internet traffic?
36. How does a public EC2 instance get internet connectivity?
37. What is a Route Table?
38. What does a Blackhole route mean?
39. An EC2 instance has a Public IP but you still cannot SSH into it. What will you check?
40. An EC2 instance can access the internet but cannot be accessed from the internet. Why?
41. EC2 CPU utilization is 100%. How will you troubleshoot it?
42. EC2 is running but your website is not opening. What will you check?
43. SSH suddenly stopped working. What could be the reasons?
44. EC2 disk usage reached 100%. What will you do?
45. EC2 is showing Status Check Failed. How will you troubleshoot it?
46. Application is running on port 8080, but you cannot access it. What will you check?
47. curl localhost:8080 works inside EC2, but curl Public-IP:8080 does not work. Why?
48. EC2 can ping another EC2 but cannot connect to port 8080. What could be wrong?
49. EC2 cannot download packages from the internet. How will you troubleshoot it?
50. EC2 suddenly became very slow. What metrics and Linux commands will you check?
51. How would you deploy an application on EC2 using Jenkins?
52. How do you automatically deploy code whenever developers push to GitHub?
53. How would you create an EC2 instance using Terraform? 
55. What is User Data in EC2?
56. How would you install Docker automatically on a newly launched EC2 instance?
57. How do you monitor EC2 using CloudWatch?
58. Which CloudWatch metrics are important for EC2?
59. How would you create a CloudWatch alarm when CPU utilization goes above 80%?
60. How would you automatically recover or replace an unhealthy EC2 instance?

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
14. Why is the Principle of Least Privilege important in IAM?
15. What is the IAM Policy JSON structure?
16. What are Effect, Action, Resource, and Condition in an IAM Policy?
17. What is the difference between Allow and Deny in an IAM Policy?
18. Which one has higher priority, Allow or Explicit Deny?
19. What is an Explicit Deny?
20. What is an Implicit Deny?
21. How does AWS evaluate IAM policies?
22. What is the difference between identity-based and resource-based policies?
23. Which AWS services support resource-based policies?
24. What is an IAM Trust Policy?
25. What is the difference between Trust Policy and Permissions Policy?
26. How does an EC2 instance assume an IAM Role?
27. How do you attach an IAM Role to an EC2 instance?
28. Can you change the IAM Role attached to a running EC2 instance?
29. Why should we use IAM Roles instead of Access Keys for EC2?
30. What happens if an EC2 instance has an IAM Role with S3 permissions?
31. How can an EC2 instance access an S3 bucket securely?
32. How do you give an IAM User read-only access to S3?
33. How do you give a user access to only one specific S3 bucket?
34. How do you restrict a user from deleting objects from an S3 bucket?
35. How do you allow a user to access only specific EC2 instances?
36. How do you provide read-only access to all AWS resources?
37. What is the AWS managed ReadOnlyAccess policy?
38. What is the difference between AdministratorAccess and PowerUserAccess?
39. What is MFA in IAM?
40. Why is MFA important for IAM Users?
41. How do you enable MFA for an IAM User?
42. How do you enforce MFA using an IAM Policy?
43. What is an IAM Access Key?
44. What is the difference between Access Key ID and Secret Access Key?
45. Where should you store AWS Access Keys securely?
46. What will you do if an AWS Access Key is accidentally exposed on GitHub?
47. How do you rotate IAM Access Keys?
48. Can an IAM User have multiple Access Keys?
49. How do you check when an IAM Access Key was last used?
50. What is IAM Access Analyzer?
51. How do you identify unused IAM Users?
52. How do you identify unused IAM Roles?
53. What is IAM Credential Report?
54. How do you generate an IAM Credential Report?
55. What information is available in an IAM Credential Report?
56. What is AWS STS?
57. What is AssumeRole in AWS?
58. How does cross-account IAM Role access work?
59. How would you allow an IAM User from Account A to access resources in Account B?
60. What is the difference between cross-account Role and cross-account User access?
61. What is a Service Role in AWS?
62. How does a service like Lambda use an IAM Role?
63. How do you create an IAM Role for Lambda?
64. What permissions are required for Lambda to write logs to CloudWatch?
65. How would you allow a Lambda function to read from S3?
66. How would you allow an ECS task to access S3 securely?
67. What is an Instance Profile in IAM?
68. What is the difference between IAM Role and Instance Profile?
69. What is a permissions boundary?
70. What is the difference between IAM Policy and Permissions Boundary?
71. What is an IAM Organization SCP?
72. What is the difference between IAM Policy and Service Control Policy?
73. Can an SCP grant permissions to a user?
74. What happens if IAM Policy allows an action but SCP denies it?
75. How do you restrict access to a specific AWS Region using IAM?
76. How do you restrict an IAM User from deleting EC2 instances?
77. How do you allow a user to start and stop EC2 instances but not terminate them?
78. How do you allow a user to access only specific S3 objects?
79. How do you restrict an IAM User based on source IP?
80. How do you restrict access based on MFA?
81. An IAM User gets AccessDenied. How will you troubleshoot it?
82. A user has AdministratorAccess but still cannot perform an action. What could be the reason?
83. An EC2 instance has an IAM Role but cannot access S3. How will you troubleshoot it?
84. Lambda is getting AccessDenied while accessing S3. How will you troubleshoot it?
85. An IAM User can access S3 but cannot delete an object. What will you check?
86. An application is using hardcoded AWS credentials. How would you improve the security?
87. How would you securely provide AWS permissions to a Jenkins server?
88. How would you allow Jenkins running on EC2 to deploy resources in AWS?
89. How would you give Terraform permission to create AWS resources securely?
90. How would you design IAM for a production DevOps environment?

---  

## S3  

---
1. What is Amazon S3?
2. What are the main components of S3?
3. What is an S3 Bucket?
4. What is an S3 Object?
5. What is an S3 Object Key?
6. What is the maximum size of an S3 object?
7. What is the maximum number of objects that can be stored in an S3 bucket?
8. What is the difference between S3 and EBS?
9. What is the difference between S3 and EFS?
10. What are the different S3 Storage Classes?
11. What is S3 Standard?
12. What is S3 Intelligent-Tiering?
13. What is S3 Standard-IA?
14. What is S3 One Zone-IA?
15. What is S3 Glacier Instant Retrieval?
16. What is S3 Glacier Flexible Retrieval?
17. What is S3 Glacier Deep Archive?
18. How do you choose the correct S3 Storage Class?
19. What is S3 Versioning?
20. Why is S3 Versioning important?
21. How do you enable Versioning on an S3 bucket?
22. What happens when you delete a versioned S3 object?
23. What is an S3 Delete Marker?
24. How do you permanently delete an object from a versioned bucket?
25. What is S3 Lifecycle Management?
26. How do you automatically move objects from S3 Standard to Glacier?
27. How do you automatically delete objects after a specific number of days?
28. What is an S3 Lifecycle Rule?
29. What is S3 Bucket Policy?
30. What is the difference between S3 Bucket Policy and IAM Policy?
31. What is an S3 Access Control List?
32. What is the difference between ACL and Bucket Policy?
33. What is S3 Block Public Access?
34. Why should S3 Block Public Access be enabled?
35. How do you make an S3 bucket private?
36. How do you make an S3 bucket publicly accessible?
37. How do you allow a specific IAM User to access an S3 bucket?
38. How do you allow an EC2 instance to access an S3 bucket?
39. How can an EC2 instance securely access S3 without Access Keys?
40. What IAM permissions are required to upload an object to S3?
41. What IAM permissions are required to download an object from S3?
42. What IAM permissions are required to delete an object from S3?
43. How do you restrict a user to access only one specific S3 bucket?
44. How do you restrict a user to access only a specific folder/prefix in S3?
45. How do you deny everyone except a specific IAM Role from accessing an S3 bucket?
46. What is S3 Encryption?
47. What is the difference between SSE-S3 and SSE-KMS?
48. What is SSE-C?
49. What is client-side encryption in S3?
50. Why would you use AWS KMS with S3?
51. What happens if an S3 object is encrypted with KMS and the user does not have KMS permissions?
52. How do you enable default encryption on an S3 bucket?
53. What is S3 Object Lock?
54. What is S3 Object Lock Retention?
55. What is Governance Mode in S3 Object Lock?
56. What is Compliance Mode in S3 Object Lock?
57. What is S3 Bucket Replication?
58. What is Cross-Region Replication?
59. What is Same-Region Replication?
60. What are the prerequisites for S3 Replication?
61. How would you replicate objects from one AWS Region to another?
62. How do you replicate only specific objects using S3 Replication?
63. What is S3 Static Website Hosting?
64. How do you host a static website using S3?
65. What permissions are required for S3 Static Website Hosting?
66. What is the difference between S3 Static Website Hosting and CloudFront?
67. How would you serve a private S3 bucket through CloudFront?
68. What is Origin Access Control in CloudFront?
69. How do you upload a file to S3 using AWS CLI?
70. How do you download a file from S3 using AWS CLI?
71. How do you copy files between two S3 buckets?
72. What is the difference between aws s3 cp and aws s3 sync?
73. How do you upload an entire directory to S3?
74. How do you download an entire S3 bucket?
75. How do you list all objects in an S3 bucket using AWS CLI?
76. How do you check the size of an S3 bucket?
77. How do you delete an S3 object using AWS CLI?
78. How do you delete an entire S3 bucket using AWS CLI?
79. What is S3 Multipart Upload?
80. When would you use Multipart Upload?
81. What happens if a Multipart Upload fails?
82. How do you troubleshoot an S3 AccessDenied error?
83. A user can list the S3 bucket but cannot download objects. What will you check?
84. A user can upload objects but cannot delete them. What could be the reason?
85. An EC2 instance cannot access S3. How will you troubleshoot it?
86. An S3 bucket is accidentally made public. How will you secure it?
87. A file exists in S3 but gives "Access Denied" when accessed. What will you check?
88. You uploaded a file to S3 but users are receiving "Access Denied". How will you troubleshoot it?
89. You uploaded index.html to S3 Static Website Hosting but the website is not opening. What will you check?
90. S3 returns "Specified Key Does Not Exist". What does this error mean and how will you troubleshoot it?
91. How would you protect important S3 data from accidental deletion?
92. How would you design a secure S3 bucket for a production environment?
93. How would you reduce S3 storage costs for a large production bucket?
94. How would you monitor S3 bucket activity?
95. What is S3 Server Access Logging?
96. What is AWS CloudTrail data event logging for S3?
97. What is S3 Event Notification?
98. How can S3 trigger a Lambda function when a file is uploaded?
99. How can S3 trigger an SQS or SNS notification?
100. How would you design a production-grade S3 architecture with security, versioning, lifecycle, encryption, logging, and backup?

---  

## VPC  

---  
1. What is Amazon VPC?
2. What are the main components of a VPC?
3. What is a CIDR block?
4. How do you choose a CIDR range for a VPC?
5. What is the difference between VPC and Subnet?
6. What is a Public Subnet?
7. What is a Private Subnet?
8. What is the difference between Public and Private Subnet?
9. What is an Internet Gateway?
10. How does an Internet Gateway provide internet access to a VPC?
11. What is a NAT Gateway?
12. What is the difference between NAT Gateway and Internet Gateway?
13. Why do we use NAT Gateway in a Private Subnet?
14. What is a Route Table?
15. What is the difference between Main Route Table and Custom Route Table?
16. How does routing work inside a VPC?
17. What is a default route 0.0.0.0/0?
18. What is a local route in a VPC Route Table?
19. What does a Blackhole route mean in a Route Table?
20. How do you create a Public Subnet?
21. How do you create a Private Subnet?
22. How do you make a subnet public?
23. What is an Availability Zone?
24. Why should we deploy resources across multiple Availability Zones?
25. What is a VPC Endpoint?
26. What is the difference between Gateway Endpoint and Interface Endpoint?
27. Why would you use an S3 VPC Endpoint?
28. What is VPC Peering?
29. What are the limitations of VPC Peering?
30. Can two VPCs with overlapping CIDR blocks be peered?
31. What is Transit Gateway?
32. What is the difference between VPC Peering and Transit Gateway?
33. When would you use Transit Gateway?
34. What is a Security Group?
35. What is a Network ACL?
36. What is the difference between Security Group and NACL?
37. Is a Security Group stateful or stateless?
38. Is a NACL stateful or stateless?
39. Can you explicitly deny traffic using a Security Group?
40. Can you explicitly deny traffic using a NACL?
41. How does NACL rule numbering work?
42. What happens when no NACL rule matches the traffic?
43. What is an Elastic Network Interface?
44. What is an ENI?
45. Can an ENI be attached to multiple EC2 instances?
46. What is a Public IP address in a VPC?
47. What is an Elastic IP address?
48. What is the difference between Public IP and Elastic IP?
49. What happens to a Public IP when an EC2 instance is stopped and started?
50. What is a private IP address?
51. Can an EC2 instance have multiple private IP addresses?
52. What is a Secondary Private IP?
53. What is DNS Resolution in VPC?
54. What is DNS Hostnames in VPC?
55. What is DHCP Options Set in VPC?
56. What is the default VPC?
57. What resources are automatically created with a default VPC?
58. What is the difference between Default VPC and Custom VPC?
59. Can you delete the default VPC?
60. How do you create a VPC using AWS CLI?
61. How do you create a VPC using Terraform?
62. How do you create a subnet using Terraform?
63. How do you attach an Internet Gateway to a VPC?
64. How do you associate a Route Table with a subnet?
65. How do you create a NAT Gateway?
66. Why does a NAT Gateway require an Elastic IP?
67. Can a Private Subnet access the internet without a NAT Gateway?
68. How does an EC2 in a Private Subnet access the internet?
69. How does an EC2 in a Public Subnet access the internet?
70. Why can't an EC2 in a Private Subnet receive direct inbound internet traffic?
71. What happens if a Public Subnet does not have a route to an Internet Gateway?
72. What happens if a Private Subnet has no route to a NAT Gateway?
73. EC2 has a Public IP but cannot access the internet. How will you troubleshoot it?
74. EC2 has a Public IP but you cannot SSH into it. What will you check?
75. EC2 can connect to the internet but cannot receive inbound traffic. What could be wrong?
76. EC2 in a Private Subnet cannot access the internet. How will you troubleshoot it?
77. Two EC2 instances in the same VPC cannot communicate. What will you check?
78. Two EC2 instances in different subnets cannot communicate. What will you check?
79. Two EC2 instances in different VPCs cannot communicate. How will you troubleshoot it?
80. An application works inside EC2 using localhost but cannot be accessed from another EC2. What will you check?
81. An EC2 instance can ping another EC2 but cannot connect to port 8080. What will you check?
82. A VPC Route Table shows a Blackhole route. Why does this happen?
83. How do you troubleshoot a Blackhole route?
84. NAT Gateway is running but Private EC2 still cannot access the internet. What will you check?
85. NAT Gateway is costing too much. How would you reduce the cost?
86. What happens if the NAT Gateway is deployed in a single Availability Zone and that AZ goes down?
87. How would you design a highly available VPC?
88. How would you design Public and Private Subnets for a production application?
89. Where would you deploy a Load Balancer in a VPC?
90. Where would you deploy application servers in a VPC?
91. Where would you deploy an RDS database in a VPC?
92. Why should databases generally be placed in Private Subnets?
93. What is a DB Subnet Group?
94. How does an Application Load Balancer communicate with EC2 instances in Private Subnets?
95. How would you design a three-tier architecture using VPC?
96. What is the difference between Internet Gateway, NAT Gateway, and VPC Endpoint?
97. How would you securely connect an on-premises network to AWS VPC?
98. What is AWS Site-to-Site VPN?
99. What is AWS Direct Connect?
100. What is the difference between Site-to-Site VPN and Direct Connect?
101. How would you connect two VPCs securely?
102. How would you connect multiple VPCs in different AWS accounts?
103. How would you troubleshoot a VPC connectivity issue step by step?
104. How do Security Groups, NACLs, Route Tables, and Gateways work together?
105. How would you design a secure, highly available, and production-ready VPC for a DevOps environment?

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
