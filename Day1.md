# ✅ Day 1 – Cloud Basics & AWS Foundation

## What I Learned

### 🌐 Cloud Computing & Its Benefits
- On-demand delivery of computing resources over the internet.
- No upfront capital expense – only pay for what you use.
- Eliminates the need to manage/maintain physical data centers.
- Easily scalable (up or down) based on demand.
- Fast deployment and global availability.

### ☁️ Cloud Deployment Models
- **IaaS (Infrastructure as a Service)**: 
  - You manage OS, runtime, data.
  - Examples: EC2 (compute), S3 (storage), VPC (networking).
- **PaaS (Platform as a Service)**:
  - You focus on code; platform management is handled by provider.
  - Examples: AWS Elastic Beanstalk, AWS Fargate.
- **SaaS (Software as a Service)**:
  - Ready-to-use applications delivered over the internet.
  - Examples: Gmail, Zoom, Salesforce.

### 🌍 AWS Global Infrastructure
- **Region**: A physical location in the world (e.g., Mumbai).
- **Availability Zone (AZ)**: One or more isolated data centers within a region.
- **Edge Location**: Local cache endpoints used for low-latency delivery (e.g., CloudFront).

### 🔐 AWS Shared Responsibility Model
- **AWS is responsible for**:
  - Physical security of data centers.
  - Network infrastructure and foundational services.
- **Customer is responsible for**:
  - Data encryption.
  - Identity & Access Management (IAM).
  - Application-level security.

### 🧱 AWS Well-Architected Framework (6 Pillars)
1. **Operational Excellence** – Monitor and improve systems to deliver business value.
2. **Security** – Protect data and systems through risk assessment and mitigation.
3. **Reliability** – Quickly recover from failure and scale to meet demand.
4. **Performance Efficiency** – Use IT and computing resources effectively.
5. **Cost Optimization** – Avoid unnecessary costs; use right resources at right price.
6. **Sustainability** – Minimize environmental impact of running cloud workloads.

---

## 🎯 Real-World Analogy

> When you play a Netflix video, a small portion of it is cached at an **edge location** near you. This improves streaming speed. Without edge locations, the video would buffer directly from the main region, causing delays.

---

✅ End of Day 1  
🗓️ Date: 2025-07-23  
📂 GitHub Folder: `aws-notes/day1.md`
