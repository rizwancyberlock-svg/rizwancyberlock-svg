<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Rizwan%20Ahmed&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Security%20Engineer%20%E2%80%A2%20Blue%20Team%20%E2%80%A2%20Detection%20Engineering&descAlignY=58&descSize=18" alt="Rizwan Ahmed - Security Engineer" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=36BCF7&center=true&vCenter=true&width=640&lines=Building+open-source+tools+for+defenders+%F0%9F%9B%A1%EF%B8%8F;SIEM+%2F+SOAR+%E2%80%A2+Google+SecOps+%E2%80%A2+YARA-L;Database+Activity+Monitoring+%E2%80%A2+IBM+Guardium;HSM+%26+Key+Management+%E2%80%A2+Thales+Luna;Detect+%E2%86%92+Triage+%E2%86%92+Respond" alt="Typing intro"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/<your-linkedin>/)
[![Detection Gallery](https://img.shields.io/badge/Detection%20Gallery-Browse%20237%20rules-1a5fd0?style=for-the-badge&logo=googlecloud&logoColor=white)](https://<your-username>.github.io/open-yaral-detections/)

</div>

---

## 👋 About me

I'm a **Security Engineer on the defender side**. I build detections, design SOC workflows and harden the systems that hold an organization's most sensitive data and keys.

- 🛡️ **SIEM / SOAR:** Google Security Operations (Chronicle), YARA-L 2.0, UDM, detection-as-code
- 🗄️ **Database Activity Monitoring:** IBM Guardium policies, SQL threat detection, data-access governance
- 🔐 **Cryptography & HSMs:** Thales Luna HSM, CipherTrust Manager, PKI and key custody
- 📚 **Learning in public:** I explain security concepts clearly and turn them into tools other defenders can use

## 🚀 Featured projects

<table>
<tr>
<td width="33%" valign="top">

### 🛡️ [open-yaral-detections](https://github.com/<your-username>/open-yaral-detections)
The largest open YARA-L 2.0 library for Google SecOps: **237 ATT&CK-mapped rules** across Windows, Linux, AWS, Azure, Entra, GCP, FortiGate, Cisco, CrowdStrike, SentinelOne, Defender, F5, Guardium, DLP, CyberArk, ARCON and Thales HSMs. Includes 7 dashboards and a searchable web gallery.

</td>
<td width="33%" valign="top">

### 🧭 [soc-triage-playbooks](https://github.com/<your-username>/soc-triage-playbooks)
**23 decision-tree playbooks** that turn an alert into a verdict: Mermaid flowcharts, UDM pivot queries, TP/FP indicators, containment and escalation steps. Covers identity, endpoint, cloud, network, DAM, DLP, PAM and HSM.

</td>
<td width="33%" valign="top">

### 🪨 [rosetta-siem](https://github.com/<your-username>/rosetta-siem)
Translate detection queries between **YARA-L ⇄ KQL ⇄ SPL ⇄ AQL**, in any direction. Zero dependencies, round-trip tested, and it warns explicitly instead of silently mistranslating. Converts 235 of the 237 rules in the library.

</td>
</tr>
</table>

```mermaid
flowchart LR
  D["🛡️ open-yaral-detections<br/>Detect"] --> T["🧭 soc-triage-playbooks<br/>Triage & respond"]
  D --> R["🪨 rosetta-siem<br/>Run it on any SIEM"]
  R --> T
```

## 🧰 Tech I work with

**Security platforms**
![Google SecOps](https://img.shields.io/badge/Google%20SecOps-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![IBM QRadar](https://img.shields.io/badge/IBM%20QRadar-052FAD?style=flat-square&logo=ibm&logoColor=white)
![IBM Guardium](https://img.shields.io/badge/IBM%20Guardium-052FAD?style=flat-square&logo=ibm&logoColor=white)
![Thales Luna HSM](https://img.shields.io/badge/Thales%20Luna%20HSM-242A75?style=flat-square)
![CyberArk](https://img.shields.io/badge/CyberArk-0066B3?style=flat-square)
![CrowdStrike](https://img.shields.io/badge/CrowdStrike-FC0000?style=flat-square)

**Languages & frameworks**
![YARA-L](https://img.shields.io/badge/YARA--L%202.0-34A853?style=flat-square)
![KQL](https://img.shields.io/badge/KQL-0078D4?style=flat-square)
![SPL](https://img.shields.io/badge/SPL-65A637?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Compliance context:** PCI DSS · SOC 2 · HIPAA · GDPR

## 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=<your-username>&show_icons=true&hide_border=true&theme=tokyonight" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=<your-username>&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages"/>

</div>

## 🌱 Currently

- 🔭 Expanding detection coverage: Okta, Kubernetes, Palo Alto and Zscaler packs
- 🧪 Building a browser playground for rosetta-siem
- ✍️ Writing deep-dives on DAM and HSM monitoring, two areas few people publish about

## 🤝 Let's collaborate

Open to collaborating on **detection engineering, SOC automation and data-security monitoring**. If one of my projects helped your team, a ⭐ helps other defenders find it. PRs with new rules and playbooks are always welcome.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" alt=""/>
