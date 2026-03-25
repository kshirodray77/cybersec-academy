# 🛡️ CyberForge Academy

> An interactive cybersecurity learning platform with hands-on labs, CTF challenges, and structured learning paths.

![CyberForge Academy](https://img.shields.io/badge/CyberForge-Academy-00e5ff?style=for-the-badge&logo=shield&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-39ff14?style=for-the-badge)

---

## 🚀 Overview

CyberForge Academy is a comprehensive, browser-based cybersecurity training platform designed to take learners from fundamentals to advanced security expertise through interactive, hands-on experiences.

### Key Features

- **6 Structured Learning Paths** — Network Defense, Penetration Testing, Malware Analysis, Cloud Security, Application Security, and Digital Forensics
- **CTF Challenge Engine** — Capture-the-flag challenges spanning Easy to Expert difficulty with a point-based ranking system
- **Knowledge Base** — Deep-dive reference materials covering network protocols, cryptography, Linux security, compliance, threat intelligence, and AI/ML in security
- **Built-in Lab Tools** — Browser-based Port Scanner, Hash Analyzer, Packet Inspector, Cipher Suite, Web Vulnerability Scanner, and SIEM Dashboard
- **Leaderboard System** — Competitive ranking with badges (Grandmaster, Elite, Diamond) to track progress
- **Interactive Terminal** — Live terminal simulation demonstrating real-world security scanning workflows

---

## 🖥️ Screenshots

The platform features a dark, cyberpunk-inspired interface with:
- Matrix rain background animation
- Animated terminal with real security tool output
- Glow effects and scanline overlays
- Responsive design for all devices

---

## 🛠️ Tech Stack

| Layer        | Technology                               |
|-------------|------------------------------------------|
| Frontend    | HTML5, CSS3 (Custom Properties), Vanilla JS |
| Typography  | JetBrains Mono, Outfit, Space Mono (Google Fonts) |
| Animations  | CSS Keyframes, Intersection Observer API |
| Canvas      | HTML5 Canvas (Matrix rain effect)        |
| Design      | Custom cyberpunk/dark theme, fully responsive |

---

## 📦 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- No build tools or server required — it's a single HTML file!

### Quick Start

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/cyberforge-academy.git

# Navigate to the project
cd cyberforge-academy

# Open in browser
open index.html
# or on Linux:
xdg-open index.html
# or simply drag index.html into your browser
```

### Using a Local Server (Optional)

```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .

# Then visit http://localhost:8080
```

---

## 📁 Project Structure

```
cyberforge-academy/
├── index.html          # Main application (self-contained)
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── assets/             # (Optional) Additional assets
    └── screenshots/    # Project screenshots
```

---

## 🎯 Platform Sections

### Learning Paths
Six structured curricula designed by security professionals:
1. **Network Defense** — Firewalls, IDS/IPS, packet analysis, incident response
2. **Penetration Testing** — Ethical hacking, vulnerability assessment, exploitation
3. **Malware Analysis** — Reverse engineering, sandboxing, threat intelligence
4. **Cloud Security** — AWS/Azure/GCP hardening, IAM, container security
5. **Application Security** — OWASP Top 10, secure coding, DevSecOps
6. **Digital Forensics** — Evidence acquisition, memory forensics, timeline analysis

### CTF Challenges
| Challenge            | Category            | Difficulty | Points |
|---------------------|---------------------|------------|--------|
| Broken Authentication | Web Exploitation   | Easy       | 100    |
| Packet Forensics     | Network Analysis    | Medium     | 250    |
| SQL Injection Lab    | Web Exploitation    | Medium     | 250    |
| Ransomware Reverse   | Reverse Engineering | Hard       | 500    |
| Privilege Escalation | System Exploitation | Hard       | 500    |
| APT Simulation       | Incident Response   | Expert     | 1000   |

### Built-in Tools
- 🔍 Port Scanner — TCP SYN, Connect, and UDP scan modes
- 🔑 Hash Analyzer — Hash identification and integrity verification
- 📡 Packet Inspector — PCAP analysis and protocol decoding
- 🧩 Cipher Suite — Multi-algorithm encryption/decryption
- 🕸️ Web Vuln Scanner — Automated XSS, SQLi, CSRF detection
- 📊 SIEM Dashboard — Log correlation and alerting practice

---

## 🔮 Roadmap

- [ ] Backend API for user accounts and progress persistence
- [ ] Dockerized lab environments for hands-on challenges
- [ ] Real-time multiplayer CTF competitions
- [ ] Certificate generation on path completion
- [ ] Community forums and discussion boards
- [ ] Mobile app (React Native)

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-challenge`)
3. Commit your changes (`git commit -m 'Add SQL injection challenge'`)
4. Push to the branch (`git push origin feature/new-challenge`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

Built with passion for the cybersecurity community.

---

<p align="center">
  <strong>⭐ Star this repository if you find it useful!</strong>
</p>
