# 🛡️ CyberSecurity & Pentesting Notes

<p align="left">
  <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintained" />
  <img src="https://img.shields.io/badge/Topic-Infosec%20%7C%20Pentest-red.svg" alt="Topic" />
  <img src="https://img.shields.io/badge/OS-BlackArch%20%7C%20Linux-1793D1?logo=arch-linux" alt="OS" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License" />
</p>

Welcome to the ultimate repository of comprehensive cybersecurity notes, vulnerability write-ups, cheat sheets, and practical pentesting methodologies. This database is structured to cover various attack vectors, misconfigurations, and security best practices.

> 📚 **Credits & Open Source Spirit:**  
> This knowledge base is curated and compiled from various open-source intelligence (OSINT) resources, security blogs, whitepapers, and public GitHub repositories. **Massive respect and full credits to all the original authors, researchers, and creators** within the InfoSec community whose work made this compilation possible. Keep sharing! 🤝

---

## 🗂️ Knowledge Base Index

### 🌐 Web Application Security & Injection Vulnerabilities
*   **Injection Attacks:** [Command Injection](./Command%20Injection), [CRLF Injection](./CRLF%20Injection), [CSS Injection](./CSS%20Injection), [CSV Injection](./CSV%20Injection), [GraphQL Injection](./GraphQL%20Injection), [LDAP Injection](./LDAP%20Injection), [LaTeX Injection](./LaTeX%20Injection), [NoSQL Injection](./NoSQL%20Injection), [Prompt Injection](./Prompt%20Injection), [XPATH Injection](./XPATH%20Injection), [XSS Injection](./XSS%20Injection), [XXE Injection](./XXE%20Injection)
*   **Client-Side & Logic Flaws:** [Account Takeover](./Account%20Takeover), [Business Logic Errors](./Business%20Logic%20Errors), [Clickjacking](./Clickjacking), [CORS Misconfiguration](./CORS%20Misconfiguration), [Cross-Site Request Forgery (CSRF)](./Cross-Site%20Request%20Forgery), [DOM Clobbering](./DOM%20Clobbering)
*   **Auth & Session Management:** [JSON Web Token (JWT)](./JSON%20Web%20Token), [OAuth Misconfiguration](./OAuth%20Misconfiguration), [Insecure Deserialization](./Insecure%20Deserialization)

### 📂 Server-Side & Infrastructure Security
*   **File & Directory Flaws:** [Directory Traversal](./Directory%20Traversal), [Client Side Path Traversal](./Client%20Side%20Path%20Traversal), [File Inclusion](./File%20Inclusion), [Zip Slip](./Zip%20Slip)
*   **Network & Infrastructure:** [DNS Rebinding](./DNS%20Rebinding), [Denial of Service (DoS)](./Denial%20of%20Service), [Virtual Hosts](./Virtual%20Hosts)
*   **API & Information Leaks:** [API Key Leaks](./API%20Key%20Leaks), [HTTP Parameter Pollution](./HTTP%20Parameter%20Pollution), [Hidden Parameters](./Hidden%20Parameters), [ORM Leak](./ORM%20Leak)

### 🛠️ Advanced Concepts & Architecture
*   **Flaws & Configurations:** [Brute Force Rate Limit](./Brute%20Force%20Rate%20Limit), [CVE Exploits](./CVE%20Exploites), [Dependency Confusion](./Dependency%20Confusion), [Insecure Direct Object References (IDOR)](./Insecure%20Direct%20Object%20References), [Insecure Management Interface](./Insecure%20Management%20Interface), [Insecure Randomness](./Insecure%20Randomness), [Insecure Source Code Management](./Insecure%20Source%20Code%20Management), [Java RMI](./Java%20RMI), [Mass Assignment](./Mass%20Assignment), [Open Redirect](./Open%20Redirect), [Race Condition](./Race%20Condition), [Type Juggling](./Type%20Juggling), [Web Cache Deception](./Web%20Cache%20Deception), [Web Sockets](./Web%20Sockets), [XS-Leak](./XS-Leak), [XSLT Injection](./XSLT%20Injection)

---

## 📈 Tools & Ecosystem
This repository heavily interacts with scripts and security toolkits running on:
*   **Environment:** Arch Linux / BlackArch 🐧
*   **Core Scripts:** Written mostly in Python (99%+) 🐍 and automated via Bash scripts.

---

## 🤝 Contributing
Contributions, bug reports, and new vulnerability notes are welcome! 
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingNotes`)
3. Commit your Changes using signed GPG keys (`git commit -m 'Add some AmazingNotes'`)
4. Push to the Branch (`git push origin feature/AmazingNotes`)
5. Open a Pull Request

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Disclaimer: This repository is created strictly for educational purposes and authorized penetration testing. Use responsibly.*
