# ✉️ Email Phishing Simulation — Kali Linux & SET  
**Domain:** Cyber Security  

## 📊 Overview  
This project demonstrates a controlled phishing simulation executed in a safe, isolated virtual lab using **Kali Linux** and the **Social-Engineer Toolkit (SET)**. The objective is to illustrate social engineering risks, evaluate organizational vulnerabilities (e.g., missing MFA, weak email authentication), and propose practical mitigations to improve defenses and user awareness.

---

## ✨ Key Activities & Findings  
- Conducted a simulated phishing campaign in an isolated environment to avoid harm to real users.  
- Simulated cloned login pages and crafted phishing emails to demonstrate how credential-capture attacks operate (no live targets were used).  
- Captured simulated credentials and analyzed attack success vectors to identify weaknesses in authentication and email security.  
- Discovered common issues such as lack of multi-factor authentication (MFA), poor email authentication (SPF/DKIM/DMARC), and low user awareness.  
- Recommended mitigations: enable MFA, enforce SPF/DKIM/DMARC, run regular phishing awareness training, and adopt least-privilege access controls.

---

## 🛠️ Tools & Technologies  
- Kali Linux (virtual lab)  
- Social-Engineer Toolkit (SET) — used within an authorized, controlled environment  
- Virtual machines / sandboxing tools (e.g., VirtualBox, VMware)  
- Email infrastructure emulator and logging tools (lab-only)  
- Analysis: Wireshark, log parsers, CSV/Excel for result aggregation

---

## ⚙️ Methodology (high-level)  
1. Prepare an isolated virtual lab with no connection to public networks.  
2. Configure test accounts and simulated services to act as targets (consent obtained and lab-only).  
3. Deploy simulated phishing messages and measure click/credential-capture rates using lab instrumentation.  
4. Analyze results, identify vulnerabilities, and draft mitigation recommendations.  


## 📌 Use Cases  
- Security awareness exercises for IT teams and employees (training, not deception).  
- Red-team / blue-team training in academic or authorized corporate labs.  
- Evaluations of email security posture and incident response readiness.  
- Research into social engineering attack vectors and human factors.

---

## 🧾 Ethical & Legal Considerations  
- Simulations were performed in a controlled lab with explicit authorization; no real user accounts or external systems were targeted.  
- Phishing simulations must **always** be authorized in writing by stakeholders and comply with local laws and organizational policies.  
- Findings are intended for defensive improvements — never used for malicious activity.

---


## 📄 Deliverables & Artifacts  
- `reports/` — Analysis reports, aggregated metrics, and recommendations.  
- `logs/` — Redacted simulation logs and anonymized telemetry for review.  
- `slides/` — Presentation slides summarizing methodology and findings.  
- `LAB_GUIDELINES.md` — Safe lab setup and authorization process (restricted).


---
**Disclaimer:** This project is for educational and defensive purposes only. Any attempt to replicate phishing techniques outside an authorized lab is illegal and unethical.
