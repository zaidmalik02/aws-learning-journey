# Day 7 – AWS Storage Services  

## What I Learned  

- **Amazon S3 Glacier**  
  - Archival storage for long-term data  
  - Glacier vs Deep Glacier retrieval times & pricing  

- **Storage Types**  
  - Block Storage (low latency, used for databases/boot volumes)  
  - File Storage (shared storage, hierarchical structure)  
  - Object Storage (scalable, metadata + data, like S3)  

- **Block Storage in AWS**  
  - **Instance Store** – temporary storage tied to EC2 lifecycle  
  - **EBS (Elastic Block Store)** – persistent block storage for EC2  
    - SSD (gp2, gp3, io1, io2)  
    - HDD (st1, sc1)  

- **EBS vs Instance Store**  
  - Instance Store: ephemeral, deleted when instance stops  
  - EBS: persistent, survives reboots/stop/start  

- **File Storage in AWS**  
  - **EFS (Elastic File System)** – scalable, serverless file storage  
  - **FSx** – fully managed file systems (FSx for Windows, FSx for Lustre)  

- **Hybrid Storage (Storage Gateway)**  
  - Volume Gateway  
  - Tape Gateway  
  - File Gateway  

## Steps I Did  
1. Explored **Amazon S3 Glacier** and storage class differences.  
2. Compared **block vs file vs object storage** in AWS.  
3. Understood **EBS types (SSD vs HDD)** and performance trade-offs.  
4. Compared **Instance Store vs EBS** behavior.  
5. Learned about **EFS and FSx file storage solutions**.  
6. Reviewed **Storage Gateway** hybrid options.  

## Output  
- Gained clarity on **AWS storage classes and use cases**.  
- Learned the differences between **EBS, Instance Store, EFS, and FSx**.  
- Understood how **Storage Gateway** connects on-premises and AWS.  
- Built a solid foundation for storage-related AWS exam topics.  
