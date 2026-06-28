# AWS IAM Least Privilege Lab

## Overview

This project demonstrates how to design, test, and document least-privilege access in AWS IAM.

The lab simulates a small company environment where users require different levels of access to AWS resources. The goal is to identify excessive permissions, replace them with scoped IAM policies, verify access, and document the process like a cloud IAM or cloud security analyst.

## Business Scenario

Northstar Financial Group is improving its cloud security posture. Several users have access to AWS resources, but some permissions are broader than necessary.

The objective is to apply least privilege by ensuring users only have access required for their job responsibilities.

## Skills Demonstrated

- AWS IAM fundamentals
- IAM users, groups, roles, and policies
- Least privilege access design
- S3 access control
- Access review methodology
- Cloud security documentation
- Security risk explanation
- Evidence collection and verification

## Planned Lab Tasks

1. Secure AWS account basics
2. Create IAM users and groups
3. Create an S3 bucket for testing
4. Assign overly broad access
5. Test access behavior
6. Replace broad permissions with least-privilege policies
7. Verify allowed and denied actions
8. Document findings and remediation

## Tools Used

- AWS Management Console
- AWS IAM
- Amazon S3
- CloudTrail
- VS Code
- GitHub
- Markdown

## Security Concepts

- Least privilege
- Role-based access control
- Authentication vs authorization
- Access reviews
- Cloud audit evidence