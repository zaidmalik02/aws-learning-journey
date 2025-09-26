# Day 2 – Elastic IP, Target Groups & Load Balancer  

## What I Learned  
- How **Elastic IPs** provide a fixed public IPv4 for instances  
- Re-associating an Elastic IP between instances  
- How **Elastic Load Balancer (ELB)** distributes traffic across multiple instances  
- Role of **Target Groups** in routing traffic to registered EC2s  
- Using **Security Groups** for both instances and the Load Balancer  
- Best practice: **release unused resources** to avoid costs  

## Steps I Did  
1. Launched **two EC2 instances**.  
2. Created an **Elastic IP** and:  
   - Associated it with **Instance 1**  
   - Disassociated, then re-associated it with **Instance 2**  
3. Created a **Target Group** and registered both instances in it.  
4. Set up an **Application Load Balancer (ALB)** and:  
   - Linked it to the Target Group  
   - Configured **Security Groups** to allow HTTP traffic (port 80)  
   - Allowed ELB to communicate with the EC2s  
5. Tested that requests to the Load Balancer DNS name were distributed across both instances.  
6. Released Elastic IP and cleaned up resources (Elastic IP, Target Group, ELB, EC2s).  

## Output  
- Successfully reassigned Elastic IP between instances.  
- Load Balancer DNS routed traffic to both EC2 instances.  
- Learned the role of Target Groups + Security Groups in load balancing.  
- Practiced **responsible cloud usage** by releasing resources.  
