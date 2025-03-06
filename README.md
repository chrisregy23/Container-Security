# Hands-On Container Security: Studying the Implementation of Recent Attacks and Related Security Applications

This project provides a hands-on exploration of container security, focusing on the implementation and mitigation of recent attacks such as runc exploits, Kubernetes MITM attacks, and Docker image backdooring. It offers a comprehensive analysis of vulnerabilities in container environments and demonstrates practical mitigation strategies using tools like AppArmor, cgroups, and Kubernetes RBAC. By setting up a controlled lab environment on AWS, this project enables learners to simulate attacks, implement security measures, and monitor container activities, providing a deep understanding of container security risks and defenses.

## Key Features
- **Comprehensive Security Evaluation**: Conducts an in-depth analysis of container security vulnerabilities, including runc exploits, Kubernetes MITM attacks, Docker image backdooring, and privilege escalation.
- **Real-World Attack Simulations**: Demonstrates the implementation of recent container attacks such as CVE-2024-21626 (runc vulnerability), cr8escape, and Kubernetes MITM service exploitation.
- **Mitigation Strategies**: Proposes and implements security measures like user namespace remapping, cgroups, AppArmor policies, and Kubernetes RBAC to mitigate vulnerabilities.
- **Hands-On Lab Environment**: Utilizes AWS and Docker to create a controlled environment for testing and validating security vulnerabilities and mitigations.
- **Focus on Container-Centric Security**: Explores security features of container-specific operating systems like CoreOS and RancherOS, emphasizing resource isolation, mandatory access control, and logging.

## Deliverables
- **Security Analysis Report**: Detailed documentation of vulnerabilities, attack methodologies, and mitigation strategies for container environments.
- **Attack Simulations**: Step-by-step implementation of attacks such as runc exploits, Kubernetes MITM, and Docker image backdooring.
- **Mitigation Implementations**: Deployment of security applications like AppArmor, cgroups, and Kubernetes RBAC to prevent and mitigate attacks.
- **Lab Environment Setup**: Configuration of Docker and Kubernetes environments on AWS for testing and validation.
- **Code and Scripts**: Includes Dockerfiles, Kubernetes YAML configurations, and Python scripts for monitoring and logging runtime activities.

## Learning Objectives
- **Understand Container Security Risks**: Gain insights into common vulnerabilities in container environments, including runc exploits, Kubernetes MITM, and privilege escalation.
- **Implement Real-World Attacks**: Learn how to simulate and exploit vulnerabilities like CVE-2024-21626, cr8escape, and Docker image backdooring.
- **Develop Mitigation Strategies**: Apply security measures such as user namespace remapping, cgroups, AppArmor, and Kubernetes RBAC to mitigate risks.
- **Configure Secure Environments**: Set up and manage secure container environments using Docker and Kubernetes on AWS.
- **Explore Container-Centric OS Features**: Understand the security benefits of container-specific operating systems like CoreOS and RancherOS.
- **Monitor and Log Container Activities**: Implement Python scripts to monitor runtime activities and detect suspicious behavior in containerized environments.
- **Enhance Kubernetes Security**: Configure Role-Based Access Control (RBAC) in Kubernetes to prevent privilege escalation and unauthorized access.
- **Apply Defense-in-Depth Principles**: Learn how to layer security measures to create a robust defense against container threats.
