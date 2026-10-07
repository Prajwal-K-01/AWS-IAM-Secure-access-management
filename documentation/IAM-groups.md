---

# 2. 'iam-groups.md`

```markdown
# AWS IAM Groups

## 1. Introduction

An IAM group is a collection of IAM users.

Groups allow administrators to manage permissions for multiple users by attaching policies to the group rather than managing permissions separately for every user.

---

## 2. Objectives

The objectives of using IAM groups in this project were:

- Organize users according to their responsibilities.
- Simplify permission management.
- Implement role-based access control.
- Apply consistent policies to multiple users.
- Support the principle of least privilege.

---

## 3. Groups Created

The project uses the following sample groups:

| Group | Purpose | Access Level |
|-------|---------|--------------|
| Administrators | AWS administration | Administrative |
| Developers | Application development | Limited |
| SecurityTeam | Security monitoring | Security-focused |
| ReadOnly | Auditing | Read-only |

---

## 4. Group Architecture

```text
                    IAM
                     |
        +------------+------------+
        |            |            |
 Administrators  Developers  SecurityTeam
        |            |            |
     Admin       Developer     Security
     Policy        Policy       Policy
                     |
                  ReadOnly
                     |
               ReadOnly Policy
