# 05 — Infrastructure as Code (Terraform + LocalStack)

> Status: ✅ Done

## What I Built

Simulated AWS infrastructure locally using LocalStack — no cloud costs, real Terraform practice.

## Completed

- [x] Provisioned S3 buckets via Terraform
- [x] IAM roles and policies simulation
- [x] Destroy/apply cycles, state management
- [x] LocalStack setup and configuration

## Key Learnings

- Terraform state is everything — lose it and you lose track of your infra
- LocalStack is not 100% AWS but good enough for learning core concepts
- IAM least-privilege principle in practice

## Stack

```
Terraform
LocalStack
AWS CLI (configured for LocalStack endpoint)
```
