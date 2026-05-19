# cloud-cost-assessment
# Cloud Pricing Comparison Report: AWS vs Azure

 Project Overview

This report compares the estimated monthly cost of hosting a small web application on Amazon Web Services (AWS) and Microsoft Azure. The comparison focuses on compute resources, storage, networking, and discount mechanisms. The goal is to determine which cloud provider is more cost-effective for different business environments.

Small Web Application Specifications

The application requirements are:

| Resource | Specification |
|---|---|
| Compute | 1 vCPU, 2 GB RAM |
| Storage | 50 GB SSD Storage |
| Database | Basic managed database |
| Monthly Data Transfer | 200 GB outbound traffic |
| Operating System | Linux and Windows comparison |
| Availability | Single region deployment |


 AWS Pricing Estimate

AWS Services Used

- Amazon EC2 (Linux t3.small instance)
- Amazon S3 Storage
- AWS Data Transfer

 Estimated Monthly Cost

| Service | Estimated Cost |
|---|---|
| EC2 Linux Instance | $18/month |
| S3 Storage (50GB) | $1.50/month |
| Data Transfer (200GB) | $18/month |
| Total Estimated Cost | **$37.50/month** |

AWS Discount Mechanisms

AWS offers several cost-saving options including:

- Savings Plans
- Reserved Instances
- Free Tier
- Spot Instances

Savings Plans provide lower pricing when users commit to a one-year or three-year usage plan.

- Azure Pricing Estimate

 Azure Services Used

- Azure Virtual Machine (B1s Linux VM)
- Azure Blob Storage
- Azure Bandwidth

 Linux-Based Estimate

| Service | Estimated Cost |
|---|---|
| Linux VM | $15/month |
| Blob Storage (50GB) | $1.20/month |
| Data Transfer (200GB) | $17/month |
| Total Estimated Cost | **$33.20/month** |

Windows-Based Estimate (Hybrid Benefit)

| Service | Estimated Cost |
|---|---|
| Windows VM | $25/month |
| Blob Storage | $1.20/month |
| Data Transfer | $17/month |
| Total Estimated Cost | **$43.20/month** |

Azure Discount Mechanisms

Azure provides several discount options:

- Azure Reserved Instances
- Azure Hybrid Benefit
- Spot Virtual Machines
- Free Account Credits

Azure Hybrid Benefit allows organizations with existing Windows Server licenses to reduce licensing costs.



Networking Cost Comparison

Inter-Zone Data Transfer Costs

| Provider | Estimated Cost |
|---|---|
| AWS | Higher inter-zone transfer charges |
| Azure | Slightly lower networking costs |

Azure generally provides more affordable networking for small workloads compared to AWS.

 Cost Optimization Strategies

1. Use Reserved Instances or Savings Plans for long-term workloads.
2. Use auto-scaling and smaller VM sizes during low traffic periods.

---

Conclusion

Azure appears more cost-effective for Microsoft-based organizations because of Hybrid Benefit licensing advantages and lower networking costs. AWS is highly flexible and preferred for Linux-heavy startups due to its broad ecosystem and scalability options.

For small web applications with limited budgets, Azure Linux deployments provide slightly lower monthly operating costs. However, AWS remains a strong option for organizations prioritizing flexibility and global infrastructure availability.
