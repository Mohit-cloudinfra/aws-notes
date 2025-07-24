# Day 2 – AWS Pricing, Architecture Models, and Service Management

##  What I learned

### 1. AWS Well-Architected Tool
- This tool helps us follow AWS best practices across 6 key pillars.
- We start by defining the workload and then answering questions under each pillar.
- Based on responses, the tool gives recommendations to improve the architecture.
- It helps identify risks and plan next steps to optimize performance, security, reliability, cost, and operational excellence.

---

### 2. AWS TCO and Pricing Calculator

#### Total Cost of Ownership (TCO)
- Compares the cost of running infrastructure on-prem vs on AWS.
- Takes into account hardware, software, networking, facilities, and admin labor costs.
- Useful to justify cloud migration with leadership or finance teams.

#### AWS Pricing Calculator
- Tool to estimate monthly AWS costs before deploying services.
- Steps:
  - Add required services.
  - Configure usage (e.g., storage GBs, vCPU hours).
  - Get detailed estimates for monthly billing.
- Helpful for forecasting costs and budgeting AWS usage.

---

### 3. AWS Pricing Models

| Model                  | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Pay-as-you-go          | Pay only for what you use. Ideal for flexible workloads.                    |
| Save when you reserve  | Commit for 1 or 3 years. Lower pricing for services like EC2, RDS.           |
| Volume-based discount  | The more you use, the cheaper it gets (e.g., S3 has tiered storage pricing).|

---

### 4. Application Communication & Architecture Models

#### Key Concept:
- Applications fulfill requests and stay available by having components communicate with each other.

#### Monolithic Architecture:
- All components (UI, logic, DB) are tightly coupled into one unit.
- If one component fails, the entire app might crash.
- Hard to scale and update specific features independently.

#### Microservices Architecture:
- App is split into independent services that talk to each other.
- If one service fails, others can continue to run.
- Easier to scale, test, and maintain.
- Promotes fault isolation and high availability.

---


### 5. AWS Service Types by Management Level

| Type            | Infra Managed By   | Scaling Type                       | Capacity Configured By  | Cost Model                          |
|-----------------|------------------  |--------------------------          |-------------------------|-------------------------------------|
| Managed         | AWS + Me           | Manual or semi-automatic           | Me                      | Pay for provisioned infrastructure  |
| Fully Managed   | AWS                | Auto (up to limits set by me)      | Me                      | Pay for reserved capacity           |
| Serverless      | AWS                | Fully automatic (no limits are set)| AWS (no config needed)  | Pay only for actual usage           |

#### Examples:
- **Managed**: EC2
- **Fully Managed**: RDS, DynamoDB
- **Serverless**: Lambda, S3, API Gateway

---

End of Day 2

Date: 2025-07-24

