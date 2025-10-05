# About Me

## Personal Information
Hello! I am a network, systems, and DevOps engineer with 2 years of experience in designing, implementing, and securing IT infrastructure. Focusing on complex system integration, process automation, and enterprise network optimization, I am currently working in Vietnam and contributing to open-source projects related to cloud infrastructure and security.

- **Name**: Nguyen Trung Hoang Hai
- **Email**: hainthvl@gmail.com
- **LinkedIn/GitHub**: github.com/abxst
- **Interests**: Solving network security issues (such as 802.1x), deploying Kubernetes for serverless environments, and auditing systems according to NIST/ISO 27001 standards.

## Key Skills
I am proficient in core skills across networking, systems management, and DevOps, applied practically in large-scale projects to ensure high availability, scalability, and compliance with international standards like NIST, ISO 27001, and COBIT. Below is a detailed description of each skill group, including operating principles, implementation steps, and real-world application examples.

| Skill | Detailed Description | Supporting Tools |
|-------|----------------------|------------------|
| **Networking** | Designing and configuring advanced network authentication systems, including RADIUS Server integration with Active Directory for group user management (e.g., creating the HAI\RADIUS-User group for access rights); implementing 802.1x on RouterOS devices with PEAP-MSCHAPv2 for securing wireless connections; troubleshooting authentication errors by checking logs and testing connections (using radtest tool to validate UDP ports 1812/1813). Principle: Leveraging EAP protocol for secure certificate exchange, supporting zero-trust architecture for enterprises. Application: Deploying internal networks for 500+ devices, reducing authentication time from 10 seconds to under 2 seconds. | NPS (Network Policy Server), RouterOS (MikroTik), Wireshark (packet analysis), Cloud Unifi (control AP from cloud) |
| **Systems Management** | Managing hybrid Windows/Linux servers, including Active Directory configuration for domain controllers and group policies; containerization with Docker for application packaging (using docker run commands with flags like --network host for network integration); auditing software processes according to ISO 27001 by reviewing source code, independent test cases, and risk assessments. Principle: Applying the principle of least privilege for permissions, combined with monitoring tools to track resources (CPU/RAM). Application: Building serverless infrastructure for enterprise applications, supporting auto-scaling based on load. | Active Directory (user/group management), Docker (container orchestration), Burp Suite (application security testing) |
| **DevOps** | Building comprehensive CI/CD pipelines with Jenkins (configuring master-slave for load distribution, integrating Git for version control, Maven for Java builds, and Docker for container deployment); deploying Kubernetes for serverless workloads (using pods, deployments, and services for orchestration, Helm charts for configuration templating). Comparing MQTT/HTTP protocols for IoT: MQTT suits low-bandwidth (publish-subscribe model), HTTP for request-response. Principle: End-to-end automation from code commit to production deployment, with rollback mechanisms. Application: Reducing release time from weeks to hours for microservices systems. | Jenkins (CI/CD pipeline), Kubernetes (orchestration), Git (source control) |

## Experience & Notable Projects
- **802.1x Authentication System Deployment**: Configuring RADIUS Server on Windows Server with Active Directory group (HAI\RADIUS-User), integrating RouterOS for PEAP-MSCHAPv2 authentication. **Detailed Explanation**: Using NPS to handle authentication requests, checking Event Viewer logs to debug errors (common causes: firewall blocking UDP 1812/1813 or mismatched certificates). **Validation**: Stable operation after connection testing with radtest tool, ensuring fast and secure authentication for enterprise networks.
- **DevOps Automation with Jenkins & Kubernetes**: Building CI/CD pipelines on Jenkins (integrating Git/Maven/Docker), deploying master-slave for scaling; using Kubernetes to handle serverless workloads (pod orchestration, auto-scaling). **Detailed Explanation**: Principle: Triggering builds from Git commits, executing test/deploy stages via Jenkins plugins; Kubernetes managing stateless containers with Helm charts for easy updates. **Validation**: Free core (MIT license), supporting cloud integration like AWS EKS for production environments.
- **System Security Audit & Policy**: Conducting audits of software processes and domain user policies (AUP/PAA/SAP) according to NIST, focusing on reducing human behavior risks (e.g., Kaiser Permanente 2016 incident). **Detailed Explanation**: Reviewing source code/independent test cases; applying zero-trust for public/private organizations (SOX/HIPAA compliance). **Validation**: Based on COBIT framework, with CFO/IT roles in policy development, ensuring comprehensive compliance.

## Similar Approaches for Portfolio
1. **Expand with Network Case Studies**: Add demos of RADIUS/Kubernetes via private GitHub repo. **Similar**: Use Terraform for IaC (Infrastructure as Code) to automate infrastructure provisioning.
2. **Integrate Audit Reports**: Embed sample PDF audits (with real data hidden). **Similar**: Tools like Trivy for scanning Docker image vulnerabilities before deployment.
3. **Demo Video for Pipelines**: Use Loom for Jenkins deployment walkthroughs. **Similar**: Integrate with ArgoCD for GitOps workflows, automatically syncing configs from Git.

## Contact
Contact me to discuss network/systems/DevOps projects or collaborate on audits!
