# IOC-Extraction-Threat-Intelligence-Enrichment-Lab
Absolutely — here’s a polished, professional **GitHub README.md** you can drop directly into your repository. It’s structured like a real SOC analyst project and showcases your skills clearly for recruiters, hiring managers, and anyone reviewing your portfolio.

You can paste this into a `README.md` file in your repo.

---

# 🛡️ IOC Extraction & Threat Intelligence Enrichment Lab  
*A hands‑on SOC Analyst home‑lab project*

---

## 📌 **Overview**  
This project simulates a real SOC analyst workflow for extracting Indicators of Compromise (IOCs) and enriching them using multiple threat‑intelligence sources. The goal is to build practical, job‑ready skills in alert triage, IOC validation, and threat‑intel analysis — all within a safe home‑lab environment.

---

## 🎯 **Goal of the Lab**  
- Learn how SOC analysts extract and enrich IOCs  
- Build a Linux‑based Threat Intelligence (TI) workstation  
- Practice multi‑source enrichment (VirusTotal API, OTX AlienVault)  
- Develop automation skills using curl, jq, and shell scripts  
- Document findings like a real SOC analyst  
- Create a repeatable workflow for future investigations  

---

## 🛠️ **Tools & Technologies Used**  
### **Operating Systems**
- Windows VM (IOC generation)
- Linux VM (Threat‑Intel workstation)

### **Threat Intelligence**
- VirusTotal API  
- OTX AlienVault  
- MISP (optional)

### **Utilities**
- curl  
- jq  
- Python3 + vt-py (optional)  
- PowerShell (hash generation)  

### **Documentation**
- Markdown  
- GitHub  

---

## 🧪 **What I Did (Step‑by‑Step)**  

### **1. Built the Lab Environment**
- Configured Windows VM as the “endpoint”  
- Configured Linux VM as the “analyst workstation”  
- Created a dedicated IOC working directory  

### **2. Collected Basic IOCs**
- Generated SHA‑256 hashes from benign files  
- Created a list of test domains (benign + phishing‑style)  
- Added safe IP addresses for enrichment  
- Organized everything into a single IOC list  

### **3. Set Up Threat‑Intel Tooling on Linux**
- Installed curl, jq, Python3, and vt‑py  
- Stored VirusTotal API key securely  
- Created scripts for hash, domain, and IP lookups  

### **4. Performed IOC Enrichment**
- Queried VirusTotal programmatically  
- Parsed JSON responses using jq  
- Checked OTX AlienVault for Pulse associations  
- Documented malicious/suspicious/benign verdicts  

### **5. Documented Findings Like a SOC Analyst**
- Created structured enrichment notes  
- Included verdicts, confidence levels, and reasoning  
- Highlighted discrepancies between TI sources  

---

## 📂 **Repository Contents**
```
├── ioc_lab/
│   ├── ioc_list.txt               # Hashes, domains, IPs
│   ├── vt_hash_test.sh            # Hash enrichment script
│   ├── vt_domain_test.sh          # Domain enrichment script
│   ├── vt_ip_test.sh              # IP enrichment script
│   └── enrichment_examples/       # Sample outputs (JSON + notes)
├── screenshots/                   # Optional: terminal outputs
└── README.md                      # This file
```

---

## 🧠 **Skills Demonstrated**
- Threat Intelligence Analysis  
- IOC Extraction & Classification  
- API‑based enrichment workflows  
- Linux command‑line proficiency  
- JSON parsing & automation  
- SOC investigation methodology  
- Documentation & reporting  
- Understanding of multi‑source TI validation  

---

## 📘 **How to Use This Lab**
1. Clone the repo  
2. Add your own IOC list  
3. Insert your VirusTotal API key  
4. Run the enrichment scripts  
5. Review and document results  

This lab is intentionally modular — you can expand it with:  
- MISP integration  
- SOAR automation  
- SIEM lookup tables  
- Detection engineering rules  

---

## 🌟 **Why This Matters**
IOC enrichment is one of the most essential skills for SOC analysts.  
This lab demonstrates your ability to:

- Validate alerts  
- Investigate suspicious artifacts  
- Use real TI sources  
- Automate enrichment  
- Make informed decisions  
- Document findings clearly  

It’s the foundation of real‑world incident response and threat‑hunting workflows — and a strong addition to any cybersecurity portfolio.

---

## 🔗 **Connect With Me**
If you found this project helpful or want to collaborate on more SOC labs, feel free to reach out on LinkedIn!

---

If you want, I can also help you:

- Add diagrams to the README  
- Add sample enrichment reports  
- Build a second lab (SIEM, EDR, MITRE ATT&CK, etc.)  
- Turn this into a full SOC portfolio series
