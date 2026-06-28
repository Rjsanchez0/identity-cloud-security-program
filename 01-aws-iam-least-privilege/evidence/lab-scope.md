# Lab Scope

## Company

Northstar Financial Group

## Project

AWS IAM Least Privilege Lab

## Objective

Design and validate least-privilege access for AWS users based on job role.

## In Scope

- AWS IAM users
- AWS IAM groups
- AWS IAM policies
- Amazon S3 test bucket
- CloudTrail evidence
- Access review documentation

## Out of Scope

- Production AWS accounts
- Real company data
- Real customer data
- Publicly exposed sensitive information
- Long-running paid AWS services
- Destructive testing

## Lab Users

| User | Role | Purpose |
|---|---|---|
| dev-jordan | Developer | Needs limited access to a project S3 bucket |
| auditor-sam | Security Auditor | Needs read-only visibility into IAM and CloudTrail |
| helpdesk-riley | Help Desk Analyst | Needs limited IAM read-only access for support verification |

## Security Goal

Replace broad permissions with scoped access that matches each user's job role.