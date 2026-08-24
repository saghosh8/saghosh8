# 👋 Hi, I'm Sahana Ghosh

**DevOps & Cloud Engineer | CI/CD Automation | GitHub Actions | AI-Assisted Engineering**

DevOps & Cloud Engineering professional with **11+ years of experience**, specializing in **CI/CD modernization, cloud automation, Kubernetes, and AI-assisted DevOps**. I build automation that turns complex, manual release processes into **repeatable GitHub Actions workflows**.

## 🧰 Technology
`GitHub Actions` · `Python` · `YAML` · `JSON` · `Git` · `GCP` · `Kubernetes` · `Bash` · `Ansible` · `AI-Assisted Engineering`

## 📜 Certifications
[View My Certifications →](https://github.com/saghosh8/CERTIFICATES)

## 🔗 Connect
[LinkedIn](https://www.linkedin.com/in/ghoshsahana/) · [GitHub](https://github.com/saghosh8) · [Email](mailto:sahanaghosh8@gmail.com)

---
# 🚀 Featured Project — Release Automation
## ⚙️ AI-Assisted Release Automation — End-to-End CI/CD Release Management

## 📌 Project Overview

Designed and implemented an **end-to-end release automation framework using GitHub Actions and Python** to standardize application onboarding, release branch management, CI/CD execution, release tagging, UAT deployment, release notes, and production deployment.

The solution reduces repetitive manual release activities across multiple application repositories while improving **release consistency, traceability, and deployment efficiency**.

---

## ⚙️ Key Automations

### 1. Application Onboarding

Automates creation and initial setup of application repositories required for the release process.

**Workflow:**
`Create App Repo → Initial Configuration → Application Ready`

[View Onboarding Automation](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/create-app-repos.yml)

---

### 2. Release Branch Automation

Creates release branches across all application repositories participating in a release.

**Inputs:**

* Release branch name
* Application repository names

**Workflow:**
`Release Input → Identify Applications → Create Branch from main`

[View Release Branch Automation](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/create-release-branch.yml)

---

### 3. Production CI & Release Tagging

Triggers CI from the release branch for the selected application and generates the release tag required for deployment.

**Inputs:**

* Application name
* Release branch

**Workflow:**
`Release Branch → Prod CI → Build → Release Tag`

[View CI Trigger Automation](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/create-release-branch.yml)

---

### 4. Release Notes & Version Management

Generates release information by comparing the newly generated release tag with the previous production tag.

**Inputs:**

* Release branch
* Previous production tag (`prod-old-tag`)

**Workflow:**

```text
Release Branch
      ↓
Generate Release Tag
      ↓
Compare Old Tag vs New Tag
      ↓
Generate Release Notes
      ↓
Update prod-new-tag
```

[View Release Notes Automation](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/publish-release-notes.yml)

---

### 5. Production Deployment

Triggers the production CD pipeline using the release branch and the validated production tag stored in `prod-new-tag`.

**Inputs:**

* Release branch
* Production release tag

**Workflow:**

```text
prod-new-tag
     ↓
Production CD
     ↓
Deployment
     ↓
Production
```

[View Production CD Automation](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/prod_cd.yml)

---

## 🧩 Technology Stack

`GitHub Actions` · `Python` · `YAML` · `Git` · `CI/CD` · `GCP` · `Kubernetes` · `Release Automation` · `AI-Assisted Engineering`

---

## 📈 Engineering Impact

* Automated a multi-step release process spanning **multiple application repositories**.
* Eliminated repetitive manual release branch and configuration activities.
* Standardized CI, UAT and production release workflows.
* Improved release traceability through **automated tagging and release notes**.
* Reduced opportunities for manual configuration and deployment errors.
* Enabled a **repeatable, parameter-driven release process** through GitHub Actions.

---

## 🔗 Project Resources

| Resource                         | Link                                                                                                             |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| 📦 Release Automation Repository | [Repo Link](https://github.com/saghosh8/release-automation)                                                       |
| 🔧 Create App Repository         | [YAML URL](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/create-app-repos.yml)      |
| 🌿 Release Branch Automation     | [YAML URL](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/create-release-branch.yml) |
| 🚀 Trigger CI Pipeline           | [YAML URL](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/prod_ci.yml)               |
| 📝 Release Notes Automation      | [YAML URL](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/publish-release-notes.yml) |
| 🚢 Production CD                 | [YAML URL](https://github.com/saghosh8/release-automation/blob/main/.github/workflows/prod_cd.yml)               |



---

### 🎯 Key Takeaway

**A parameter-driven GitHub Actions release framework that automates the journey from application onboarding to production deployment — with controlled branching, CI/CD, release tagging, UAT validation, release documentation, and production deployment.**

⭐ **Explore my repositories to see practical examples of DevOps, CI/CD, cloud automation and AI-assisted engineering.**
