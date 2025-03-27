# 🧨 Red vs Blue Lab: Full-Scope Cybersecurity Simulation

Welcome to the **Red vs Blue Lab**, a ready-to-deploy attack & defense simulation environment used for:
- 🛡️ Blue Team SOC/DFIR training
- 🧠 Red Team offensive testing
- 🔁 Purple Team TTP validation
- 🧪 Testing SIEM/EDR/IDS integrations
- 🎯 Real-world scenario simulation based on MITRE ATT&CK

---

## 🚀 What's Included

✅ **Red Team Modules**:  
- Initial access (phishing, payloads)  
- Privilege escalation (Windows/Linux)  
- Credential dumping & lateral movement  
- Persistence & exfiltration  
- Full attack chain automation script  

✅ **Blue Team Stack**:  
- Sysmon, Winlogbeat, Zeek, Suricata  
- Wazuh/Security Onion/ELK integrations  
- Sigma detection rules  
- Incident response playbooks  
- Kibana dashboards  

✅ **Purple Team Tools**:  
- ATT&CK mapping  
- Red/Blue coverage matrix  
- SIEM alert tuning  

✅ **Reports & Templates**:  
- Red/Blue post-engagement reports  
- Timeline analysis template  
- MITRE mapping per scenario  

---

## ⚙️ Lab Setup

**Option 1: Vagrant + VirtualBox**
```bash
cd setup/
vagrant up
