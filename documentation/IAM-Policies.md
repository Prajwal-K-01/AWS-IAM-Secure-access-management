---

# 4. `documentation/iam-policies.md`

```markdown
# AWS IAM Policies

## 1. Introduction

IAM policies are JSON documents that define permissions for AWS identities and resources.

A policy determines which actions are allowed or denied on specific AWS resources.

---

## 2. Policy Structure

A basic IAM policy contains:

```text
Version
Statement
   |
   +-- Effect
   +-- Action
   +-- Resource
   +-- Condition
