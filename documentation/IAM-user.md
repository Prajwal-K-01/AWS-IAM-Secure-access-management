# AWS IAM Users

## 1. Introduction

An IAM user represents an individual person or application that needs long-term identity-based access to AWS resources.

In this project, IAM users were created to represent different organizational roles and demonstrate controlled access to AWS resources.

---

## 2. Objectives

The main objectives of creating IAM users were:

- Create individual identities for AWS access.
- Assign users to appropriate IAM groups.
- Apply permissions through group-based policies.
- Follow the principle of least privilege.
- Avoid using the AWS root user for daily activities.
- Demonstrate role-based access management.

---

## 3. Users Created

The project uses sample users representing different organizational responsibilities.

| User | Purpose | Group |
|------|---------|-------|
| admin-user | Administrative activities | Administrators |
| developer-user | Application development | Developers |
| security-user | Security monitoring | SecurityTeam |
| readonly-user | Auditing and monitoring | ReadOnly |

> These are sample identities created for the project. They do not represent real employees.

---

## 4. IAM User Creation Process

### Step 1

Open the AWS Management Console.

### Step 2

Navigate to:

`IAM → Users`

### Step 3

Select:

`Create user`

### Step 4

Enter the required username.

### Step 5

Configure the appropriate access method according to the project requirements.

### Step 6

Assign the user to an appropriate IAM group.

### Step 7

Review the permissions and create the user.

---

## 5. Group-Based Access

Users were organized into groups instead of assigning individual permissions wherever possible.

Example:

```text
developer-user
      |
      v
Developers Group
      |
      v
Developer Policy
