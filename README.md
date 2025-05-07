# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

**SOLUTIONS:**
Problem 1: Encryption Time Calculation 
A company uses AES-256 encryption to secure its data before uploading it to the cloud. 
It takes 0.05 seconds to encrypt 1 MB of data. 
Q: How long will it take to encrypt 2 TB of data before upload? 
AES-256 encryption takes 0.05 seconds per 1 MB 
Step 1: Convert 2 TB to MB 
1 TB=1024 GB 
1 GB=1024 MB 
⇒2 TB=2×1024×1024=2,097,152  
Step 2: Calculate encryption time 
Encryption time=2,097,152 MB×0.05 sec/MB=104,857.6 seconds  
Step 3: Convert seconds to hours 
104,857.6÷3600≈29.13 hours  
Final Answer: 
It will take approximately 104,857.6 seconds, or about 29.13 hours, to encrypt 2 TB of data. 
Problem 2:CPU Utilization Efficiency 
A VM is allocated 8 vCPUs, but only uses 5.5 vCPUs on average. 
Q: What is the CPU utilization efficiency? 
CPU utilization efficiency: 
CPU Utilization Efficiency=(Average vCPU UsageAllocated vCPUs)×100  
Given: 
• Allocated vCPUs = 8 
• Average vCPU usage = 5.5 
Step-by-step calculation: 
Efficiency=(5.58)×100%=68.75%  
Final Answer: 
The CPU utilization efficiency is 68.75%. 
Problem 3: Network Throughput Efficiency 
A cloud server has a maximum bandwidth of 1 Gbps, but during peak hours it only 
uses 600 Mbps. 
Q: What is the network throughput efficiency? 
To calculate network throughput efficiency, use the formula: 
Throughput Efficiency=(Actual UsageMaximum Bandwidth)×100%  
Given: 
• Maximum bandwidth = 1 Gbps 
• Actual usage during peak hours = 600 Mbps 
Convert both to the same unit (e.g., Gbps): 
600 Mbps=0.6 Gbps 
Step-by-step calculation: 
Efficiency=(0.61)×100%=60%  
Final Answer: 
The network throughput efficiency is 60%. 
Problem 4:Energy Efficiency 
Two cloud setups process the same workload: 
• Setup A uses 500W for 2 hours. 
• Setup B uses 300W for 3.5 hours. 
To determine energy efficiency, we need to calculate the total energy consumption for 
each setup and compare them. 
Step 1: Calculate Energy Consumption 
• Energy (in watt-hours)=Power (W)×Time (hours)  
•   Setup A: 
• 500 W×2 hrs=1000 Wh  
•   Setup B: 
• 300 W×3.5 hrs=1050 Wh  
Step 2: Compare Energy Usage 
• Setup A uses 1000 Wh 
• Setup B uses 1050 Wh 
• So, Setup A is more energy efficient because it completes the same workload using 
less energy. 
Final Answer: 
• Setup A uses 1000 Wh 
• Setup B uses 1050 Wh 
Setup A is more energy efficient 
Problem 5:  
CPU Utilization Efficiency 
A physical server has 16 cores and each VM uses 2 cores. CPU utilization is optimal at 
75%. 
Q: What is the maximum number of VMs that can be efficiently hosted? 
Step 1: Determine total usable CPU cores at 75% utilization 
16 cores×0.75=12 cores usable for efficient hosting 
Step 2: Each VM uses 2 cores 
Max VMs=12 usable cores2 cores/VM=6 VMs  
Final Answer: 
A maximum of 6 VMs can be efficiently hosted to maintain 75% CPU utilization.
