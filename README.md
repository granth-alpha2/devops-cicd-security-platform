# Conftest

[![Go Report Card](https://goreportcard.com/badge/open-policy-agent/opa)](https://goreportcard.com/report/open-policy-agent/conftest) [![Netlify](https://api.netlify.com/api/v1/badges/2d928746-3380-4123-b0eb-1fd74ba390db/deploy-status)](https://app.netlify.com/sites/vibrant-villani-65041c/deploys)

Conftest helps you write tests against structured configuration data. Using Conftest you can
write tests for your Kubernetes configuration, Tekton pipeline definitions, Terraform code,
Serverless configs or any other config files.

Conftest uses the Rego language from [Open Policy Agent](https://www.openpolicyagent.org/) for writing
the assertions. You can read more about Rego in [How do I write policies](https://www.openpolicyagent.org/docs/how-do-i-write-policies.html)
in the Open Policy Agent documentation.

Here's a quick example. Save the following a# DevOps CI/CD Security Platform

## Objective
This project demonstrates:

- Linux Administration
- Git & GitHub Workflow
- CI/CD Automation using GitHub Actions
- SonarQube Integration
- Open Policy Agent (OPA) Policy Enforcement

---

## Project Structure

company-devops-platform/
├── configs/
├── deployments/
├── policies/
├── reports/
├── artifacts/
├── backup/

---

## Branching Strategy

- main → stable branch
- development → active development
- staging → testing branch
- production → deployment branch

---

## Implemented Features

### Linux Administration
- User and group management
- File permissions
- Backup creation
- Process management
- Archive generation

### Git & GitHub
- Branching workflow
- Merge conflict resolution
- stash
- cherry-pick
- rebase
- revert
- reset
- recovery operations

### CI/CD
- GitHub Actions pipeline
- Automated workflow triggers
- Deployment stages
- Artifact storage

### SonarQube
- Static code analysis
- Quality gate validation
- Security scanning

### OPA / Conftest
- Deployment validation
- Root user restriction
- Image tag enforcement
- Privileged container prevention

---

## Repository

GitHub Repository:
https://github.com/granth-alpha2/devops-cicd-security-platform
