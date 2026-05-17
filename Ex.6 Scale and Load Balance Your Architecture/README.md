# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture


Author :VISHAL V

Reg no :212224040366

Date :17.05.2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.

---

## Output Screenshots 
<img width="1286" height="784" alt="image" src="https://github.com/user-attachments/assets/6408957d-9a41-4d18-87ca-02a0c631c6c3" />
<img width="1264" height="704" alt="image" src="https://github.com/user-attachments/assets/592ee799-812c-4f62-a478-04ed7dd62929" />
<img width="1261" height="712" alt="image" src="https://github.com/user-attachments/assets/fef4e184-da44-4586-a21a-5ecf6d2bb920" />
<img width="1275" height="843" alt="image" src="https://github.com/user-attachments/assets/cfcc3970-e647-40c1-8672-d0218f762a20" />
<img width="1276" height="818" alt="image" src="https://github.com/user-attachments/assets/c3305f8b-73cf-4052-869b-7429e9228d99" />

---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
