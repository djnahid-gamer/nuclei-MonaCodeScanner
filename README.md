# 🧠 Nuclei Source Code Analysis Templates
This repository contains a collection of custom **Nuclei templates** designed for **source code security analysis**. It includes rules to detect:
- 🔐 Hardcoded secrets (API keys, tokens)
- ⚙️ Configuration and `.env` leaks
- 🐞 Debug and test routes
- 📄 Exposed source code and backup files
- ⚠️ OWASP Top 10 vulnerability patterns in source files

These templates are ideal for **SAST (Static Application Security Testing)** and **CI/CD pipeline integration**.


## 🚀 Usage

```bash
echo "/path/to/source-code-dir/ | nuclei -t /path/to/templates/language/ -file
```
## 🤝 Contributing

Contributions are welcome! Feel free to:

- Submit new templates (for specific languages, frameworks, or patterns)
- Improve existing detection rules
- Report false positives or suggestions via Issues


---

## 🙋‍♂️ Support / Questions

If you find this project useful, feel free to ⭐ star it and share with others in the security community.  
For any questions, feel free to open an [issue]([https://github.com/KaanBicaklar/nuclei-MonaCodeScanner/issues).

---
## 🛡️ Stay Secure

Use responsibly. These templates are designed for ethical source code analysis, red team assessments, and CI/CD integration.
