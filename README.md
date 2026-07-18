<div align="center">

# 🔴 PHANTOM-OS 
### Blue Team Command Center & Threat Intelligence Portfolio

[![Status: Active](https://img.shields.io/badge/Status-Active-00ff88?style=for-the-badge&logo=statuspage&logoColor=000)](https://the-old-manl.github.io/)
[![Deployment: GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-111b2e?style=for-the-badge&logo=github&logoColor=fff)](https://the-old-manl.github.io/)
[![Clearance: Public](https://img.shields.io/badge/Clearance-Public-ffb800?style=for-the-badge&logo=shield&logoColor=000)](#)

<br/>

```text
       ___ _  _   _   _  _ _____ ___  __  __     ___  ___ 
      | _ \ || | /_\ | \| |_   _/ _ \|  \/  |___/ _ \/ __|
      |  _/ __ |/ _ \| .` | | || (_) | |\/| |__| (_) \__ \
      |_| |_||_/_/ \_\_|\_| |_| \___/|_|  |_|   \___/|___/
                                              v2.7.0
```

*An interactive, enterprise-grade Security Operations Center (SOC) dashboard simulating a military-spec Blue Team operating system.*

[View Live Command Center](https://the-old-manl.github.io/) • [Report Vulnerability](#)

</div>

---

## 📡 Architecture Overview

Phantom-OS is an interactive cybersecurity portfolio engineered to look, feel, and function like a live SOC dashboard. It eschews traditional web design paradigms in favor of a "terminal-first, glassmorphism-second" cybernetic aesthetic, aiming to provide recruiters and engineering teams with an immersive demonstration of Blue Team culture.

### Technology Stack
- **Core Layer:** Semantic HTML5
- **Style Engine:** Tailwind CSS (JIT via CDN)
- **Interactive Layer:** Vanilla JavaScript (ES6+)
- **Hosting Infrastructure:** GitHub Pages

> **Zero Dependency Architecture:** The portal intentionally runs without heavy frameworks (React, Next.js) to guarantee instantaneous load times and eliminate supply chain vulnerabilities. It relies entirely on native browser APIs.

---

## 🛡️ Active Threat Operations (Projects)

This command center highlights hands-on defensive security engineering, moving beyond theory into practical, real-world deployment:

### 1. Azure Sentinel SIEM & Live Cyber Attack Map
**[OP-001] Threat Level: CRITICAL**
* **Mission:** Architect a live Cloud SOC environment.
* **Execution:** Deployed a vulnerable Windows Honeypot VM in Microsoft Azure. Engineered custom PowerShell scripts to extract RDP brute-force logs, query geolocation APIs, and feed the enriched data into Log Analytics Workspace.
* **Output:** A live, globally mapped dashboard of active attacker telemetry visualized via KQL.
* **Link:** [View Repository](https://github.com/ThE-Old-MaNl/Azure-SIEM-Honeypot)

### 2. Phishing Header Analysis
**[OP-002] Threat Level: HIGH**
* **Mission:** Dissect credential harvesting campaigns.
* **Execution:** Analyzed real-world phishing samples, mapping DMARC, DKIM, and SPF failures. Identified attacker infrastructure and mapped TTPs (Tactics, Techniques, and Procedures).
* **Output:** Documented IOCs (Indicators of Compromise) for threat intel sharing.

### 3. [ENCRYPTED LABS] — *Coming Soon*
* **Status:** In Development
* **Mission:** Deploy MITRE ATT&CK adversary emulation frameworks and automated incident response playbooks. 

---

## 🎨 UI/UX Design System: "Phantom"

The visual architecture uses a custom token system injected directly into Tailwind CSS. It is built on three core pillars:

1. **Cybernetic Glassmorphism:** Cards and panels utilize heavy background blur (`backdrop-filter: blur(20px)`) layered over a deep void background (`#05080f`), mimicking holographic HUDs.
2. **Neon Threat Accents:** 
   * `Phantom Green (#00ff88)`: Active status, successful executions, primary interactive elements.
   * `Phantom Red (#ff2d55)`: Critical alerts, high-severity indicators.
   * `Phantom Amber (#ffb800)`: Encrypted/Classified data, warnings.
3. **Kinetic Feedback:** Every interaction provides immediate visual feedback. 
   * A simulated 3-second OS Boot Sequence.
   * CSS-based text glitching on the primary operator title.
   * A live Canvas API particle network drawing constellation lines between moving nodes.
   * Background radar pulse animations behind project cards.

---

## ⚙️ Deployment Instructions

To deploy a local instance of the command center:

```bash
# Clone the repository
git clone https://github.com/ThE-Old-MaNl/ThE-Old-MaNl.github.io.git

# Navigate to the directory
cd ThE-Old-MaNl.github.io

# Start a local web server (Python 3)
python -m http.server 8000

# Access the interface
# Open browser to: http://localhost:8000
```

---

## 📬 Secure Comms Channel

Currently accepting connections for **SOC Analyst**, **Security Engineer**, and **Blue Team** roles.

- **GitHub Uplink:** [@ThE-Old-MaNl](https://github.com/ThE-Old-MaNl)
- **LinkedIn Uplink:** [My LinkedIn Profile](https://www.linkedin.com/in/abdessamad-jedd/)

<br/>

<div align="center">
  <p><code>connection_terminated. session_logged.</code></p>
  <p>&copy; 2026 ThE-Old-MaN</p>
</div>
