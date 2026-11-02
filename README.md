# CyLab Academy CTF Writeups 🚩🖥

Welcome to my collection of writeups for [CyLab Academy CTF](https://cylabacademy.org) (formerly picoCTF). As a Computer Science student learning cybersecurity, I use this repository to share my step-by-step solutions, scripts, and notes across different challenge categories.

## 💻 My Setup: Windows-First + Kali Linux

I solve most challenges using **Windows** first, relying on built-in tools and simple graphical apps whenever possible. When a challenge needs Linux-only tools or low-level memory attacks, I switch to **Kali Linux** (using WSL2 or a Virtual Machine).

### 🧰 Tools I Use

**Windows Tools:**
*   **PowerShell & CMD:** Basic file handling, terminal commands, and quick network checks.
*   **Python:** Writing quick scripts for automation, cryptography, and web requests.
*   **Burp Suite / OWASP ZAP:** Inspecting and modifying web traffic for Web Exploitation.
*   **Ghidra / IDA Free:** Breaking down compiled programs for Reverse Engineering.
*   **HxD / CyberChef:** Viewing hex data and decoding text for Cryptography and Forensics.
*   **Wireshark:** Inspecting network traffic files (`.pcap`).

**Kali Linux Tools (When needed):**
*   **pwntools & GDB:** Testing buffer overflows and memory bugs in Binary Exploitation.
*   **Binwalk & Steghide:** Finding hidden files and secret data in Forensics challenges.
*   **Netcat (`nc`):** Connecting to remote challenge servers.
*   **Bash Scripting:** Fast command-line text filtering (`grep`, `awk`, `sed`).

## 📂 Repository Structure

The writeups are organized into folders matching the CyLab Academy CTF categories:

| Category | Description |
| :--- | :--- |
| **`General-Skills/`** | Terminal basics, file handling, and fundamental tools. |
| **`AI/`** | Tricking machine learning models, prompt injection, and bypassing AI filters. |
| **`Web-Exploitation/`** | Finding flaws in websites like SQL injection, XSS, and broken logins. |
| **`Cryptography/`** | Breaking codes, ciphers, and weak encryption. |
| **`Forensics/`** | Finding hidden data in files, images, and network traffic. |
| **`Binary-Exploitation/`** | Exploiting memory bugs and buffer overflows (mostly solved in Kali). |
| **`Reverse-Engineering/`** | Taking apart compiled programs to figure out how they work. |

*Note: I will also add a `Blockchain/` folder once I start working through those challenges.*

## 🚀 How to Use This Repo

1. Open the folder for the category you want to check out.
2. Click on the markdown file for a specific challenge (e.g., `ChallengeName.md`).
3. Every writeup breaks down:
   *   **Challenge Info:** The prompt, category, and points.
   *   **First Steps:** How I looked at the problem on Windows (or why I switched to Kali).
   *   **Solution:** The exact steps taken to get the flag.
   *   **Scripts:** Any Python, Bash, or PowerShell code used to solve it.

## 🤝 Disclaimer

These writeups are for educational purposes only. CyLab Academy is a safe and legal platform for practicing cybersecurity. Never test or attack systems without permission.

Leo.
