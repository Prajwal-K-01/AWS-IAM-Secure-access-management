---

# 3. `documentation/iam-roles.md`

```markdown
# AWS IAM Roles

## 1. Introduction

An IAM role is an AWS identity that provides temporary permissions to trusted entities.

Unlike IAM users, IAM roles are not associated with permanent passwords or long-term access keys.

Roles are commonly used by:

- EC2 instances
- Lambda functions
- AWS services
- Applications
- Federated users
- Cross-account access

---

## 2. Objective

The objective of using an IAM role in this project is to demonstrate how an AWS resource can access another AWS service without storing long-term credentials.

---

## 3. Project Role

Example role:

```text
EC2-S3-Access-Role
