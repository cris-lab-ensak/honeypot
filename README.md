# 🍯 Honeypot

> **CRIS Club** — Academic Year 2025/2026

## 📌 About This Project

This project deploys a **honeypot** system to lure, detect, and study malicious actors in a controlled environment. By simulating vulnerable systems, we capture real attack patterns and gather threat intelligence.

## 📄 Document

| File | Description |
|------|-------------|
| `honeypot.pdf` | Full honeypot project documentation |

## 🎯 Objectives

- Deploy a realistic-looking honeypot environment
- Log and monitor all attacker interactions
- Analyze attack techniques, tools, and patterns (TTPs)
- Generate threat intelligence from captured data

## 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| **Cowrie** | SSH/Telnet honeypot — captures brute-force and shell commands |
| **Dionaea** | Captures malware samples via fake vulnerable services |
| **OpenCanary** | Lightweight multi-protocol honeypot |
| **ELK Stack** | Log aggregation and attack visualization |
| **Kippo / Glastopf** | Web & SSH honeypots |

## 🗂️ Architecture

```
[Internet / Attacker]
        ↓
  [Honeypot System]  ← isolated network segment
   (Cowrie / Dionaea)
        ↓
  [Log Collector]
        ↓
  [ELK Dashboard] — visualize attacks in real-time
```

## ⚠️ Ethical & Legal Notice

> This honeypot is deployed **only in controlled, isolated lab environments** for educational purposes. Never deploy honeypots on production networks without proper authorization.

## 🏫 About CRIS Club

**CRIS** (Cybersecurity Research & Innovation Students) is a student-led cybersecurity club focused on hands-on learning, research projects, and real-world security challenges.

📅 Academic Year: **2025/2026**

---

> 📬 For questions or contributions, open an issue or contact the CRIS Club team.
