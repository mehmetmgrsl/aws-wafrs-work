# WIP

### What is the AWS Well-Architected Framework Review (WAFR)

- Clients often seek validation of their architecture's alignment with 
   - AWS best practices, 
   - inquiring about workload adequacy, 
   - adherence to cloud best practices, and 
   - solution implementation guidance. 
   
- The AWS Well-Architected Framework addresses these concerns through its six pillars: 
   1. Operational Excellence, 
   2. Security, 
   3. Reliability, 
   4. Performance Efficiency, 
   5. Cost Optimization, and 
   6. Sustainability.

### Why would we need do it?

- The ultimate goal of WAFR is to improve your systems' architecture so that these systems can better support business needs.


### 6 Pillars

#### 1. Operational Excelence

-  Perform operations as code
-  Make frequent, small, reversible changes
-  Refine operations procedures frequently
-  Anticipate failure
-  Learn from all operational failures

#### 2. Security

- Implement a Strong Identify Foundation
- Apply Securoty at all Layers
- Protect Data in Transit and at Rest
    - Encrypt data at rest
    - Use server-side encryption with provider managed keys
    - Encrypt data in transit


#### 3. Reliability

- The ability of a workload to perform its reqired function:
   - correctly and
   - consistently
  over an expected period of time.

To do this, design principles are:
  - Automatically recover from failure
  - Test recovery procedures
  - Scale horizontally to increase aggregate workload availability
  - Stop guessing capity
  - Manage change in automation
    - using IaC (CloudFormation or Terraform)

#### 5. Cost Optimization

  - Terminate unused resources
  - Resize resources that are overprovisioned
  - Automate shutdown on schedule

### References:

1. https://aws.amazon.com/architecture/well-architected/

2. https://aws.amazon.com/blogs/mt/how-to-perform-a-well-architected-framework-review-part1/

3. [AWS Well-Architected for Startups - Cost Optimisation | Amazon Web Services](https://www.youtube.com/watch?v=tXRPicLruWc&list=PLhr1KZpdzukdc8hT9hCF8hwfWkYAX-frO&index=2)

4. [AWS Well-Architected for Startups - Security](https://www.youtube.com/watch?v=s9vf3r2fGXI&list=PLhr1KZpdzukdc8hT9hCF8hwfWkYAX-frO&index=3)

5. [AWS Well-Architected for Startups - Reliability](https://www.youtube.com/watch?v=U5CIFoWG00A&list=PLhr1KZpdzukdc8hT9hCF8hwfWkYAX-frO&index=4)

6. [AWS Well-Architected for Startups - Operational Excellence](https://www.youtube.com/watch?v=m0iUkVYUYeY&list=PLhr1KZpdzukdc8hT9hCF8hwfWkYAX-frO&index=5)

7. https://aws.amazon.com/blogs/mt/how-to-perform-a-well-architected-framework-review-part1/