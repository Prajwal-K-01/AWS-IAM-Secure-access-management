# 🔐 AWS IAM Secure Access Management

<p align="center">
  <strong>AWS Identity & Access Management | Cloud Security | Least Privilege | RBAC</strong>
</p>

<p align="center">
  A hands-on AWS security project demonstrating secure identity and access management using IAM Users, Groups, Roles, Policies and MFA.
</p>

---

## 📌 Project Overview

**AWS IAM Secure Access Management** is a hands-on cloud security project designed to demonstrate how Identity and Access Management (IAM) can be implemented in an AWS environment using real-world security principles.

The project simulates an organizational environment called **Cloud Security Lab**, where different users have different responsibilities and therefore require different levels of AWS access.

The implementation focuses on:

- 🔐 Identity management
- 👥 User and group management
- 🎭 Role-based access control
- 📜 Custom IAM policies
- 🛡️ Multi-Factor Authentication
- 🔒 Least-privilege access
- ☁️ Secure AWS resource access
- 📊 IAM security best practices

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Understand AWS IAM architecture and components.
- Secure the AWS Root User.
- Create and manage IAM users.
- Organize users using IAM groups.
- Create custom JSON-based IAM policies.
- Implement role-based access control.
- Understand and configure IAM roles.
- Apply the Principle of Least Privilege.
- Configure Multi-Factor Authentication (MFA).
- Understand secure AWS credential management.
- Test IAM permissions.
- Document IAM security best practices.
- Build a professional AWS cloud-security portfolio project.

---

# 🏗️ Architecture

```text
                         AWS ACCOUNT
                              │
                         Root User
                              │
                              ▼
                            IAM
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
       Users                Groups                Roles
        │                     │                     │
        │          ┌──────────┼──────────┐          │
        │          │          │          │          │
        ▼          ▼          ▼          ▼          │
     Admin      Developer  Security    ReadOnly     │
      User        Group      Team        Group      │
        │          │          │          │          │
        └──────────┴──────────┴──────────┘          │
                           │                         │
                           ▼                         ▼
                      IAM Policies            EC2-S3 Role
                           │                         │
                           ▼                         ▼
                    AWS Permissions              EC
