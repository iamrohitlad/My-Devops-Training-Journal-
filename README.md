# My-Devops-Training-Journal-
This repository chronicles my journey into the world of DevOps, combining daily notes, hands-on experiments, and project learnings across CI/CD, automation, cloud services, and containerization. It includes: - Lab exercises and mini-projects using Jenkins, Docker, and Kubernetes.
DAY 1 
What is Devops ?
Devops is a collabrative approach to software development that emphasizes communication , collabration , integration and co-operation between the software developers and IT operation professionals . The goal of devops is to streamline the development , deployment and operations of software automating processes ,improving team collabration , and fostering culture of continous improvement or development .
Core Principles in Devops : 
Core Principles of DevOps
Automation: Automation plays a central role in DevOps, from code deployment to infrastructure management. By automating tasks such as code builds, testing, deployment, and infrastructure provisioning, teams can improve efficiency, reduce human error, and release software faster.
Continuous Integration and Continuous Delivery (CI/CD):
Continuous Integration (CI) involves frequently integrating code changes into a shared repository, triggering automated builds and tests. This helps catch errors early and ensures code is always in a deployable state.
Continuous Delivery (CD) goes a step further by automating the deployment of code to production, ensuring software can be released at any time without manual intervention.
Infrastructure as Code (IaC): DevOps teams manage infrastructure (servers, networks, databases) using code, allowing them to version control, automate, and replicate configurations across different environments. Tools like Terraform, Ansible, and AWS CloudFormation enable IaC.
Monitoring and Feedback Loops: DevOps emphasizes the use of real-time monitoring, logging, and analytics to gain insights into application performance and user behavior. This feedback is used to improve applications continuously and address issues proactively.
Collaboration and Culture: DevOps is as much about culture as it is about tools and processes. It encourages transparency, shared responsibility, and open communication, helping break down the traditional silos between development and operations teams.
Teams in Devops : 
A successful DevOps ecosystem involves various teams working together, each with specific responsibilities and contributions to the software lifecycle. Here’s a breakdown of the primary teams involved in DevOps:

1. DEVELOPER :
Developers are primarily responsible for writing, testing, and maintaining the code that powers applications. They play a key role in DevOps, focusing on:
Coding: Writing high-quality code in collaboration with DevOps teams to ensure it can be efficiently built, tested, and deployed.
Unit Testing: Developers perform initial testing of their code to ensure that it functions as expected before integrating with other components.
Feature Development: Developers work closely with product teams to develop and deliver features based on customer needs.
Collaboration on CI/CD: Developers work with DevOps engineers to create CI/CD pipelines that automate testing and deployment, ensuring code reaches production efficiently.
Key Skills for Developers in a DevOps Environment:
Familiarity with CI/CD tools (e.g., Jenkins, GitLab CI/CD)
Knowledge of testing frameworks and practices (e.g., JUnit, pytest)
Version control systems (e.g., Git)
Understanding of containerization (e.g., Docker) and orchestration (e.g., Kubernetes)
 
2. INFRASTRUCTURE TEAM ( OPS TEAM ) :
   The Infrastructure team, or IT operations team, manages the physical and virtual resources needed to support application deployment. They ensure the infrastructure is stable, secure, and scalable to meet application demands. Key responsibilities include:
Provisioning and Managing Infrastructure: This involves setting up servers, storage, networking, and other resources that applications need.
Security and Compliance: The infrastructure team ensures systems meet security standards, performing tasks such as patching, firewall configuration, and vulnerability management.
Monitoring and Troubleshooting: They monitor infrastructure health, usage, and performance, ensuring systems remain operational and troubleshooting issues as they arise.
Infrastructure as Code (IaC): The team manages infrastructure configurations programmatically, using tools like Terraform and Ansible to ensure consistency across environments.
   
3. DEVOPS TEAM :
   The DevOps team bridges the gap between development and operations, focusing on building and maintaining pipelines, automating workflows, and enhancing collaboration. This team usually consists of DevOps Engineers, Developers, and Testers specialized in DevOps practices. The responsibilities of the DevOps team include:
Pipeline Development and CI/CD Implementation: DevOps engineers create and manage CI/CD pipelines that automate the build, test, and deployment process, enabling faster and more reliable software releases.
Automation and Scripting: They write scripts to automate various processes, such as code deployment, infrastructure provisioning, and configuration management.
Monitoring and Incident Response: DevOps engineers implement monitoring tools and systems to provide insights into application performance, helping detect and respond to incidents quickly.
Security Integration (DevSecOps): DevOps engineers work closely with security teams to incorporate security practices into CI/CD pipelines, ensuring security is considered at every stage of development.
Key Roles within the DevOps Team:

DevOps Developers: These developers specialize in building infrastructure and automation tools. They work on developing scripts, managing IaC, and enhancing CI/CD processes.

DevOps Testers: Testers in the DevOps team focus on automated testing, quality assurance, and test environment setup. They create automated tests to run in CI/CD pipelines, ensuring
