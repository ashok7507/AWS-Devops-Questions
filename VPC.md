### 1. What is VPC?  
Ans:  An Amazon VPC (Virtual Private Cloud) is a private, logically isolated network inside AWS where you can run resources such as EC2 instances, databases, and applications.  

### 2. What is subnet?  
Ans:  A subnet (subnetwork) is a smaller network created inside a VPC.  

### 3. What is an Internet Gateway?  
Ans:  An Internet Gateway (IGW) is an AWS-managed component that allows resources in a VPC to communicate with the internet.  

### 4. What is a Route Table?  
Ans:  A Route Table is a collection of rules that tells AWS where network traffic should be sent.  
      EC2  
      ↓  
      Route Table  
      ↓  
      Internet Gateway  
      ↓  
      Internet

### 5. What is a NAT Gateway?  
Ans:  NAT Gateway is mainly used for outbound internet access from private subnets.  
It does not make the private EC2 directly accessible from the internet.  
Private EC2
    ↓
NAT Gateway
    ↓
Internet Gateway
    ↓
Internet
