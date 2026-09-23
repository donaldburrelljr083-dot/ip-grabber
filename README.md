# ip-grabber
This project provides a simulated environment for studying attacker behavior and gathering threat indicators. It is strictly intended for educational and authorized defensive security research.
# IP Decoy Project

> A honeypot-based decoy application designed for security research, threat intelligence gathering, and defensive analysis.

## ⚠️ Purpose & Disclaimer

This project is a **defensive honeypot tool** intended for authorized security research and education only. It is designed to mimic common reconnaissance targets to study attacker behavior, collect threat indicators, and improve defensive postures.

**DO NOT deploy against systems you do not own or have explicit written permission to test.** Unauthorized use violates applicable laws including the Computer Fraud and Abuse Act (CFAA) and international equivalents.

## 🎯 What This Does

When executed in a controlled environment, this decoy application:

- Simulates common service signatures to attract automated scanners and malware
- Logs connection metadata for threat analysis
- Helps identify attack patterns and TTPs (Tactics, Techniques, and Procedures)
- Provides indicators of compromise (IOCs) for SOC teams

## 🏗️ Architecture

See [docs/architecture.md](docs/architecture.md) for detailed system design.

## 🚀 Deployment

1. Configure target parameters in `config/decoy-config.json`
2. Deploy on an isolated network segment or VM
3. Monitor `logs/` directory for captured activity
4. Analyze collected data using your preferred SIEM or custom parsers

Full instructions: [docs/deployment.md](docs/deployment.md)

## 📊 Threat Model

Understand the limitations and assumptions: [docs/threat-model.md](docs/threat-model.md)

## 📝 Changelog

See [CHANGELOG.md](CHANGELOG.md) for version history.

## 📜 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

## 🔒 Responsible Disclosure

If you discover vulnerabilities in this project, please report them responsibly to the maintainers. Do not test against production systems without authorization.

---

*For educational and defensive security research purposes only.*
