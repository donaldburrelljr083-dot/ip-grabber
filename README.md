# 🛡️ Project Honeypot / IP Decoy System

> **⚠️ EDUCATIONAL USE ONLY ⚠️**  
> This software is designed for security research, education, and authorized defensive testing. Unauthorized use against systems you do not own is illegal.

## 📖 Overview
This project simulates a vulnerable service to capture connection metadata (IP addresses, User-Agents) for analysis. It mimics common reconnaissance targets to study attacker behavior and gather threat indicators.

## 🚀 Features
- **IP Capture**: Logs source IPs and User-Agent strings.
- **Hacker Aesthetic**: Terminal output formatted to resemble standard penetration testing tools.
- **Educational Focus**: Designed to teach network monitoring and honeypot concepts.

## 📂 Repository Structure
| File | Description |
|------|-------------|
| `launcher.py` | Main executable script |
| `config/decoy-config.json` | Configuration settings |
| `docs/` | Architecture and deployment guides |
| `logs/` | Directory for captured data |

## 🏃‍♂️ Quick Start
1. Clone the repository.
2. Run `python launcher.py`.
3. Monitor the terminal for incoming connections.

## 📜 License
MIT License - see [LICENSE](LICENSE) for details.
