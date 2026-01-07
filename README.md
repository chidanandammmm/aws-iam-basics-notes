# aws-iam-basics-notes

# AWS IAM Basics – Practical Notes

This repository contains simple and practical notes to understand AWS Identity and Access Management (IAM).

I created this while learning AWS and wanted to keep the explanations beginner-friendly and easy to revise.

---

## What is IAM?
IAM (Identity and Access Management) is used to control:
- Who can access AWS
- What actions they can perform
- Which resources they can access

---

## Core IAM Components

### IAM Users
- Represents a person or service
- Has login credentials
- Permissions assigned via policies or groups

---

### IAM Groups
- Collection of users
- Permissions assigned once and applied to all users in the group
- Helps manage access at scale

---

### IAM Policies
- JSON documents that define permissions
- Can allow or deny actions
- Attached to users, groups, or roles

---

### IAM Roles
- Used for temporary access
- Commonly used by EC2, Lambda, and cross-account access
- No passwords or access keys required

---

## Common Use Cases
- EC2 accessing S3 using IAM role
- Developer having read-only access to production
- CI/CD pipeline deploying resources securely

---

## Best Practices
- Enable MFA
- Use least privilege access
- Avoid root account usage
- Rotate credentials regularly

---

## Notes
These notes are meant for learning and quick revision.  
I plan to keep improving them as I explore more AWS services.
