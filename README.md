# 🛡️ SafeLine WAF – Web Attack Detection and Prevention

## 📌 Project Overview

This project demonstrates the implementation of **SafeLine Web Application Firewall (WAF)** to protect a web application against common web-based attacks.

I created a practical security lab using Ubuntu, Kali Linux, Docker, and SafeLine WAF. I simulated different web attacks from Kali Linux and monitored the security events through the SafeLine dashboard.

## 🎯 Objectives

- Understand how a Web Application Firewall works.
- Deploy SafeLine WAF using Docker.
- Protect a test web application.
- Simulate common web attacks.
- Analyze attack logs and security alerts.
- Understand how WAF detects and blocks malicious requests.

## 🧰 Tools and Technologies

| Tool | Purpose |
|---|---|
| SafeLine WAF | Web application protection |
| Kali Linux | Security testing |
| Ubuntu | WAF deployment and web server |
| Docker | Container management |
| Python HTTP Server | Hosting the test website |
| OpenSSL | SSL certificate generation |

## 🏗️ Lab Architecture

**Kali Linux → SafeLine WAF → Protected Web Application**

- Kali Linux – `10.157.244.165`
- Ubuntu / SafeLine – `10.157.244.172`
- Test Web Application – Port `8080`
- SafeLine HTTP – Port `80`

## ⚙️ Implementation

1. Installed SafeLine WAF using Docker on Ubuntu.
2. Started and verified the SafeLine containers.
3. Created a simple HTML test website.
4. Hosted the website using Python HTTP Server.
5. Connected Kali Linux to the Ubuntu SafeLine server.
6. Configured the protected web application.
7. Performed web attack simulation tests.
8. Investigated security events in the SafeLine dashboard.

## 🔍 Security Testing and Results

| Attack Type | Result |
|---|---|
| SQL Injection | Blocked |
| Cross-Site Scripting (XSS) | Blocked |
| Directory Traversal | Blocked |
| Command Injection | No alert observed |

## 🔎 SOC Analyst Investigation

During the lab, I investigated SafeLine security events and examined:

- Source IP Address
- Attack Type
- Request URL
- Attack Time
- WAF Action (Blocked / Allowed)
- Response Details

This helped me understand how security analysts investigate web attacks and monitor WAF alerts.

## 📸 Project Screenshots

Add your actual lab screenshots in the `screenshots` folder.

1. SafeLine Dashboard
2. SafeLine Docker Containers
3. Protected Web Application
4. SQL Injection Detection
5. XSS Detection
6. Directory Traversal Detection
7. Attack Log Investigation

## 📚 Key Learnings

- Understanding WAF architecture and functionality.
- Deploying security tools using Docker.
- Understanding HTTP requests and responses.
- Identifying common web application attacks.
- Analyzing security alerts and attack logs.
- Understanding attack detection and prevention.

## 👨‍💻 Author

**Sangana Raja Sekhar Reddy**

Aspiring SOC Analyst | Cybersecurity Beginner

GitHub: [SanganaRajaSekharReddy](https://github.com/SanganaRajaSekharReddy)

---

⭐ This project was created for hands-on cybersecurity learning and SOC Analyst skill development.
