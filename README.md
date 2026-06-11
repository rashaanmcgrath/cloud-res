 Azure Cloud Resume & Portfolio Architecture Project

## 📋 Project Overview
This project focuses on deploying a high-performance, secure, and cost-optimized technical portfolio website built completely within the Microsoft Azure ecosystem. Moving beyond standard local hosting, this project establishes a modern web architecture utilizing cloud-native services, automated deployment workflows, and proactive cloud cost governance.

**Live Project URL:** https://rashaanmcgrath.github.io/cloud-res/

---

## 🛠️ Tech Stack & Architecture
* **Hosting Platform:** Azure Static Web Apps (Free/Basic Tier)
* **Source Control & CI/CD:** GitHub (Repository: `cloud-res`)
* **Frontend Foundations:** Semantic HTML5, Custom CSS3 Grid Architecture
* **Cloud Management:** Azure Cost Management + Billing, Azure Budgets

---

## 🏗️ Implementation Milestones

### 1. Version Control & CI/CD Pipeline Setup
To establish an agile development workflow, a secure GitHub repository (`cloud-res`) was initialized. 
* Configured local-to-remote tracking branches linked directly to GitHub.
* Structured a clean deployment pipeline ensuring that updates committed to the `main` branch trigger automated builds and deployment synchronizations.
* Designed a custom, fully responsive `index.html` landing page engineered with a CSS root variable color palette customized for a professional DBA and Cybersecurity aesthetic.

### 2. Azure Cloud Provisioning & Deployment
* Provisioned an **Azure Static Web App** instance to enable global content delivery and high availability.
* Upgraded the default subscription model from a Trial state to an active enterprise-ready tier to ensure full integration capabilities and seamless workflow execution through GitHub Actions.

---

## 💰 Cloud Cost Governance & Incident Remediation

### The Challenge: Unintended Service Spend
During initial provisioning in a rapid configuration environment, the hosting plan inadvertently defaulted to a **Standard App Service Plan** rather than a cost-free basic tier. Proactive monitoring of the dashboard revealed unexpected accrued costs with a projected End-of-Month (EOM) billing cycle climb toward $9.00.

### The Remediation Strategy
Demonstrating strong administrative oversight and cloud financial accountability, the following remediation steps were immediately executed:
1. **Root Cause Analysis (RCA):** Utilized **Azure Cost Management** to isolate the cost driver, identifying the App Service compute tier as the single source of unexpected spend.
2. **Infrastructure Resizing:** Downscaled the infrastructure footprint from the Standard plan down to the cost-optimized tier, immediately halting the billing leak.
3. **Future Proactive Defense:** Formulated a strict infrastructure budget and alert mechanism to enforce compliance and catch future configuration drift before billing execution.

---

## 🧠 Key Technical Takeaways
* **Infrastructure Agility:** Gained deep hands-on experience connecting external Git workflows with cloud-native hosting environments.
* **FinOps & Cloud Governance:** Realized the critical business value of monitoring cloud resources early. Mistakes happen in production settings; the ability to use cloud monitoring tools to quickly audit, isolate, and remediate cost discrepancies is a highly transferable skill in enterprise architecture.

