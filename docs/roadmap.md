---
layout: default
title: Roadmap
---

[Home](./)

# Roadmap

My path from GitHub fundamentals to infrastructure as code on AWS. Each step has a certification and a project that proves it. I update this page as each step is completed.

| Step | Certification | Project | Status |
|------|---------------|---------|--------|
| 1 | GitHub Foundations | [devops-journey](https://github.com/VictorPinero21/devops-journey) | In progress |
| 2 | GitHub Actions | Project 1: CI/CD pipeline | Planned |
| 3 | AWS Solutions Architect Associate | Project 2: AWS app deployed from Actions | Planned |
| 4 | Terraform Associate | Project 3: Infrastructure as code | Planned |

## Projects

### Project 1: CI/CD pipeline with GitHub Actions
A complete pipeline for a small API: lint, tests, Docker build, vulnerability scan, publish to GitHub Container Registry and automatic release.

### Project 2: AWS app deployed from Actions
A three-tier app on AWS (load balancer, containers, database) inside a VPC, deployed from GitHub Actions with OIDC instead of static keys.

### Project 3: Infrastructure as code with Terraform
The same stack rebuilt with Terraform: own modules, remote state, separate environments and a pipeline that plans on pull requests and applies on merge.