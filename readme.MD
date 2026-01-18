# **Automation Hub**

### **Production-Grade n8n Workflows for Compliance, FinTech, and AI Safety**

This repository contains a suite of high-reliability automation workflows designed to bridge the gap between business operations and security compliance. 

---

## **📂 Featured Workflows**

### **1. Compliance Evidence Vault (Audit Automation)**

* **Problem:** Manual collection of audit evidence takes 15+ hours weekly and risks data exposure on third-party clouds.
* **Solution:** A self-hosted pipeline that extracts, parses, and files compliance evidence automatically.
* **Impact:** Eliminated 60 hours of manual labor per month with 100% data sovereignty.
* **Key Tech:** JavaScript Path Parsing, Gmail API, Local File System.

### **2. Revenue Operations (RevOps) & Recovery Engine**

* **Problem:** Failed payments and siloed financial data lead to lost revenue and "blind" stakeholder reporting.
* **Solution:** A real-time webhook listener for payment recovery coupled with a monthly automated financial auditor.
* **Impact:** Instant "rescue" sequences for failed transactions and zero-manual-entry reporting.
* **Key Tech:** Webhooks, Google Sheets API, Conditional Logic.

### **3. Privacy-First Medical Lead Agent**

* **Problem:** Handling patient data in the cloud creates HIPAA/Privacy risks.
* **Solution:** A hybrid AI architecture using OpenAI for interaction and **Local Ollama** for sensitive data processing.
* **Impact:** Secure lead qualification with hard-coded safety guardrails to prevent unauthorized medical advice.
* **Key Tech:** OpenAI, Ollama (Llama 3), Docker.

---

## **🛠 Infrastructure & Security**

These workflows are architected for **Enterprise Security**:

* **Self-Hosted Environment:** Run on a private Contabo VPS using Docker and Docker Compose.
* **Data Sovereignty:** Sensitive data never leaves the internal network; APIs are consumed via secure, encrypted webhooks.
* **Error Handling:** Every workflow includes "Error Trigger" nodes that log failures to gmail.
* **State Management:** Utilizes n8n's Static Data and local JSON files to maintain execution state across restarts.

---
<!-- n8n-automation-hub -->

## * How to Use This Repo**

1. **Clone the Repo:**
```bash
git clone https://github.com/kodervine/n8n_workflows.git

```


2. **Import Workflows:**
Open your n8n instance, go to **Workflows > Import from File**, and select any `.json` file from the `/` directory.
3. **Configure Credentials:**
Each workflow requires specific credentials (API Keys, OAuth2). 
<!-- Refer to the `setup.md` in each subfolder for detailed permission requirements. -->

---

<!-- ## **📜 Certifications & Expertise**

* **Google Cybersecurity Professional**
* **Microsoft Azure AI Fundamentals (AI-900)**
* **ISC2 Certified in Cybersecurity (Candidate)** -->

---

## **🤝 Let's Connect**

* **Portfolio:** [chinenyeanikwenze.netlify.app](https://chinenyeanikwenze.netlify.app/portfolio)
* **LinkedIn:** [Chinenye Anikwenze](https://www.linkedin.com/in/chinenye-anikwenze)
* **Blog:** [UnDebugged Logs](https://undebuggedlogs.substack.com/)

---
