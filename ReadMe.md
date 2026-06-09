## Scale and Load Balance Your Architecture
## Author
## Name: AISHWARYA V
## Register Number: 212223220003

## Objective
The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

## Prerequisites
Basic knowledge of Amazon EC2 and VPC
Completion of previous labs (IAM, EC2, EBS, Database Server)
AWS Academy Lab access
Stable internet connection

## Tools Used
AWS Management Console
Amazon EC2
Elastic Load Balancer (ELB / ALB)
Auto Scaling Groups (ASG)
Amazon CloudWatch

## Tasks Performed
Task 1: Review Existing Architecture
Students review the existing EC2-based application architecture created in previous experiments.

Task 2: Create a Launch Template
Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

Task 3: Create an Auto Scaling Group
Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

Task 4: Configure an Application Load Balancer
Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

Task 5: Register Auto Scaling Group with Load Balancer
Students attach the Auto Scaling Group to the target group of the load balancer.

Task 6: Configure Scaling Policies
Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

Task 7: Test Load Balancing and Scaling
Students test the setup by generating traffic and observing automatic scaling and load distribution.

## Workflow (To be filled by Student)
1.Review the existing EC2-based application architecture to understand current deployment, resource usage, and scalability requirements before implementing automation.

2.Create a Launch Template that defines EC2 configuration such as AMI, instance type, key pair, security group, and user data. This ensures consistent instance creation in scaling environments.

3.Create an Auto Scaling Group (ASG) using the launch template. Configure minimum, maximum, and desired capacity to automatically manage the number of running instances based on demand.

4.Set up an Application Load Balancer (ALB) and create target groups to distribute incoming traffic evenly across EC2 instances, ensuring high availability and fault tolerance.

5.Attach the ASG to the load balancer, configure scaling policies using CloudWatch alarms (based on CPU utilization), and test by generating traffic to verify automatic scaling and load balancing.

## Output Screenshots
<img width="1917" height="902" alt="566058917-53bb9459-2bfd-4d21-aea7-ca7d69bbe8cd" src="https://github.com/user-attachments/assets/8f051618-b94b-4a7f-9685-4d99be23ea36" />
<img width="1919" height="909" alt="566059410-fd1f41cd-92dd-4f3a-b8cd-36ff33f386b3" src="https://github.com/user-attachments/assets/48bd764f-161a-4eb0-a756-65d51e4ca0e3" />
<img width="1915" height="908" alt="566060042-da7e97a8-f273-407c-8149-cc5cb15e5950" src="https://github.com/user-attachments/assets/dfdb3504-7ecb-4820-bee2-706235f65013" />
<img width="1600" height="856" alt="566075024-a196ed0d-e288-4240-a673-45778f429852" src="https://github.com/user-attachments/assets/18baaa03-35e6-4d8c-90b3-304b87ae805b" />
<img width="1600" height="937" alt="566075100-14ec1297-7309-493c-af57-2a4c3010614c" src="https://github.com/user-attachments/assets/680c1cff-1050-4d6c-9001-ea7300c11889" />

## Result
This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
