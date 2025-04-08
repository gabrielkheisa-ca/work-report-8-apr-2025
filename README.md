# Work Report: 26 Mar 2025 - 8 Apr 2025

**Date:** April 9, 2025

**Overview**

This document summarizes my key activities and accomplishments during the work period from March 26, 2025, to April 8, 2025.  This period focused on client project tasks related to Google Cloud Platform (GCP) security and infrastructure management, as well as personal professional development through Google Professional Cloud Architect (PCA) exam preparation.

**Key Activities & Accomplishments**

1. **Client Task: GCP Security Compliance**

   * **Task Description:**  Addressed a critical security compliance requirement for the banking GCP projects to align with ISO/IEC 27001 standards. This involved identifying and removing GCP members utilizing personal Gmail accounts (*@gmail.com) within the project.
   * **Actions Taken:**
      * Identified GCP members using personal Gmail accounts within the specified project.
      * Implemented the necessary procedures to revoke access and remove these members from the project.
      * Ensured the changes were properly documented and communicated to relevant stakeholders (screenshot of proof of revocations).
   * **Outcome:** Enhanced the security posture of the banking-related GCP project by enforcing the use of corporate or authorized accounts, contributing to ISO/IEC 27001 compliance.

2. **Client Task: Windows VM Partitioning in GCP**

   * **Task Description:**  Fulfilled a client request to create partitions on multiple Windows Virtual Machines (VMs) hosted in GCP.  This involved configuring partitions with specific sizes as requested by the client.
   * **Actions Taken:**
      * Established secure Remote Desktop Protocol (RDP) access to the target Windows VMs via IAP (Identity-Aware Proxy) tunnel for enhanced security.
      * Utilized appropriate disk management tools within the Windows VMs to create partitions with the client-specified sizes.
      * Verified the successful creation and configuration of partitions on each VM.
   * **Outcome:** Successfully provisioned partitioned disks on Windows VMs in GCP, meeting the client's infrastructure requirements for organization, application deployment, or other specific use cases. The use of IAP tunnel ensured secure access during the configuration process.

3. **Documentation Repository: Blue-Green Deployment with Terraform on GCP**

   * **Task Description:**  Developed comprehensive documentation for implementing blue-green deployment strategies on GCP using Terraform. [This documentation](https://github.com/gabrielkheisa-ca/blue-green-manual/tree/add-kubectl-command) focuses on leveraging key GCP services and technologies.
   * **Documentation Content:**
      * **Technology Stack:** The documentation covers the following technologies:
         * **Terraform:** For infrastructure-as-code deployment and management.
         * **Google Cloud Container Registry (GCR):** For storing both blue and green container images.
         * **Google Kubernetes Engine (GKE):** For container orchestration and application deployment.
         * **Load Balancers:**  For traffic routing and seamless switching between blue and green environments.
      * **Conceptual Overview:** Explanation of blue-green deployment principles and benefits.
      * **Step-by-Step Guide:** Detailed instructions on setting up a blue-green deployment pipeline using Terraform and the specified GCP services.
      * **Code Examples:**  Practical Terraform code snippets and configurations for each stage of the deployment process.
      * **Best Practices:**  Recommendations for optimizing blue-green deployments on GCP.
   * **Outcome:** Created a valuable resource repository that enables teams to effectively implement blue-green deployment strategies on GCP. This documentation promotes best practices, reduces deployment risks, and improves application availability. The repository is ready to be shared and utilized by relevant teams.

4. **Professional Development: Google PCA Exam Preparation**

   * **Task Description:**  Dedicated time to prepare for the Google Professional Cloud Architect (PCA) certification exam. This involved focused study and practice to enhance my GCP knowledge and skills.
   * **Study Activities:**
      * **Mock Exam Practice:**  Worked through PCA mock exams to simulate the exam environment, identify knowledge gaps, and improve time management.
      * **Topic Deep Dive:**  Focused on understanding common and critical PCA exam topics, including:
         * **IAM & Admin (Identity and Access Management & Administration):**  Deepened understanding of GCP IAM best practices, roles, policies, and organizational structures.
         * **Networking:** Reviewed VPC networking concepts, subnetting, firewall rules, and network peering in GCP.
         * **Compute Engine:** Studied instance types, instance templates, managed instance groups, and autoscaling options.
   * **Outcome:**  Progressed significantly in my preparation for the PCA exam. Mock exams provided valuable insights into exam format and areas for improvement. Focused study on key topics strengthened my understanding of GCP architecture and best practices, contributing to my professional growth and future exam success.

**Technologies Utilized**

* Google Cloud Platform (GCP)
* Terraform
* Google Kubernetes Engine (GKE)
* Google Cloud Container Registry (GCR)
* Identity-Aware Proxy (IAP)
* Remote Desktop Protocol (RDP)
* Windows Server Operating Systems
* Disk Management Tools

**Challenges & Learnings**

* **Client Security Policy Nuances:** Navigating specific client security policies for the banking-related projects required careful attention to detail during the Gmail account removal task. Learned more about the practical application of ISO/IEC 27001 compliance in cloud environments and the importance of clear communication with stakeholders regarding security protocols.
* **Terraform Documentation Depth:**  Ensuring the blue-green deployment documentation was comprehensive and user-friendly required a deeper dive into Terraform modules and best practices for documentation clarity.  Discovered new techniques for structuring Terraform code examples within documentation to improve readability and maintainability.

**Next Steps**

* **PCA Exam Focus:** Continue PCA exam preparation focusing on Data Analytics services in GCP (BigQuery, Dataflow, Dataproc) and Cost Optimization strategies. Schedule the exam within the next month.
* **Blue-Green Documentation Sharing & Feedback:** Share the blue-green deployment documentation repository with the relevant DevOps and Engineering teams.  Gather feedback and iterate on the documentation to improve its usability and address any questions or gaps.  Potentially create a short training session based on the documentation.
* **Explore GCP Security Automation:** Investigate opportunities to automate GCP security compliance tasks, such as user account auditing and policy enforcement, to proactively prevent similar situations in the future.

**Conclusion**

This work period was productive, contributing to both client project deliverables and personal professional development.  The tasks completed directly addressed client needs and security requirements, while the PCA exam preparation enhanced my GCP expertise.  The inclusion of "Challenges & Learnings" and "Next Steps" sections provides valuable context and forward-looking perspective to this report. I am looking forward to continuing to contribute effectively in the next work period.
