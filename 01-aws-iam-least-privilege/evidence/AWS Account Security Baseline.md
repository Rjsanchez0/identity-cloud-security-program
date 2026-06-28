# AWS Account Security Baseline

## Purpose

This document records the initial security controls applied before creating AWS IAM lab resources.

## Root Account Protection

| Control | Status | Notes |
|---|---|---|
| Root user MFA enabled | Complete | MFA enabled for the AWS account root user |
| Root access keys created | Not created | Root access keys should not be used |
| Root used for daily work | No | Root will only be used for account-level setup or emergency tasks |

## Billing Protection

| Control | Status | Notes |
|---|---|---|
| AWS Budget created | Complete | Monthly budget alert configured |
| Budget alert email configured | Complete | Alert email added for cost notifications |

## Screenshot Decision

Screenshots were intentionally not included for root MFA or billing setup because those pages may expose sensitive account, billing, or security information.

## Lab Safety Rules

- Do not use real company data.
- Do not store real secrets in GitHub.
- Do not create root access keys.
- Do not use the root user for daily lab work.
- Delete unused resources after each lab.
- Review AWS billing during and after lab sessions.
- Do not upload screenshots that expose account IDs, emails, QR codes, MFA setup keys, billing details, or secrets.