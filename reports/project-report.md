# AWS IAM Secure Access Management
## Project Report

---

## 1. Project Title

**AWS IAM Secure Access Management**

---

## 2. Project Overview

This project demonstrates the design and implementation of a secure Identity and Access Management (IAM) environment using Amazon Web Services (AWS).

The project focuses on controlling access to AWS resources through IAM Users, User Groups, Roles, Policies, and Multi-Factor Authentication (MFA). The implementation follows important AWS security principles such as the Principle of Least Privilege, Role-Based Access Control (RBAC), separation of responsibilities, and secure credential management.

A fictional organizational environment called **Cloud Security Lab** was used to simulate real-world AWS access management requirements.

---

## 3. Project Objectives

The primary objectives of this project are:

- Understand AWS Identity and Access Management (IAM).
- Understand the AWS Root User and its security responsibilities.
- Create and manage IAM users.
- Organize users using IAM groups.
- Create and configure IAM policies.
- Implement role-based access control.
- Create IAM roles for AWS service access.
- Configure Multi-Factor Authentication (MFA).
- Apply the Principle of Least Privilege.
- Test and verify IAM permissions.
- Understand secure AWS credential management.
- Document IAM security best practices.
- Build a professional AWS security project for GitHub.

---

## 4. Technologies and Services Used

| Technology / Service | Purpose |
|---|---|
| AWS IAM | Identity and access management |
| AWS Management Console | AWS resource configuration |
| IAM Users | Individual identities |
| IAM Groups | User organization and permission management |
| IAM Roles | Temporary/service-based access |
| IAM Policies | Permission control |
| MFA | Additional authentication security |
| Amazon EC2 | Demonstrating role-based service access |
| Amazon S3 | Demonstrating resource access |
| JSON | IAM policy definition |
| GitHub | Project documentation and version control |

---

## 5. AWS IAM Fundamentals Studied

Before implementing the project, the following IAM concepts were studied:

### 5.1 Root User

The AWS Root User is created when an AWS account is initially created and has extensive privileges over the account.

The project follows the security principle that the root user should not be used for routine AWS operations.

Important root-user security practices include:

- Enable MFA.
- Do not create root access keys.
- Use IAM identities for regular operations.
- Protect root credentials.
- Use the root user only when specifically required.

---

### 5.2 IAM Users

IAM users represent individual identities that require access to AWS resources.

Sample users were created to represent different organizational responsibilities.

Example:

```text
admin-user
developer-user
security-user
readonly-user
