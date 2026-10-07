I
---

# 5. `documentation/iam-security.md`

```markdown
# AWS IAM Security Best Practices

## 1. Introduction

AWS IAM is a critical component of AWS security because it controls who can access AWS resources and what actions they can perform.

This project focuses on implementing secure identity and access management principles.

---

## 2. Root User Security

The AWS root user has extensive privileges over the AWS account.

The root user should not be used for everyday AWS operations.

Recommended practices include:

- Enable MFA on the root user.
- Do not create root access keys.
- Use IAM identities for normal administration.
- Store root credentials securely.
- Monitor account activity.

---

## 3. Multi-Factor Authentication

MFA provides an additional authentication factor.

Instead of relying only on a password:

```text
Password
    +
MFA
    |
    v
Stronger Authentication
