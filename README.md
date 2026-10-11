# CyLab Academy CTF Writeups 🚩

Welcome to my repository of writeups for [CyLab Academy CTF](https://cylabacademy.org), the educational platform formerly known as picoCTF. As a Computer Science student dedicated to mastering cybersecurity, I use this repository to document my thought processes, scripts, and step-by-step solutions across multiple challenge categories.

## 💻 The Workflow: Windows-First + Kali Linux

I tackle most of these challenges using a **Windows-first approach**. While the offensive security industry leans heavily on Linux, I prefer maximizing native Windows capabilities and graphical tools before pivoting. When a challenge specifically requires Linux-exclusive binaries or low-level memory exploitation suites, I transition to **Kali Linux** (via WSL2 or Virtual Machine) to get the job done. 

### 🧰 Toolkit Breakdown

**Native Windows Tools:**
*   **PowerShell & CMD:** For native file manipulation, environment scripting, and quick network checks.
*   **Python (Windows Build):** Core scripting for automation, cryptography, and basic web requests.
*   **Burp Suite / OWASP ZAP:** For Web Exploitation and intercepting HTTP traffic.
*   **Ghidra / IDA Free:** For Reverse Engineering compiled executables and statically analyzing binaries.
*   **HxD / CyberChef:** For fast Cryptography solving and Forensics decoding.
*   **Wireshark:** Analyzing network packet captures (`.pcap`) directly in a native Windows GUI.

**Kali Linux Tools (When needed):**
*   **pwntools & GDB:** Essential for Binary Exploitation, format string bugs, and memory corruption challenges.
*   **Binwalk & Steghide:** For advanced Forensics, file carving, and steganography tasks.
*   **Netcat (`nc`):** Connecting to remote challenge servers and catching reverse shells.
*   **Bash Scripting:** Quick Linux terminal automation and piping (`grep`, `awk`, `sed`).

## 📂 Repository Structure

The writeups are organized by the core CyLab Academy CTF tracks:

| Category | Description |
| :--- | :--- |
| **`General-Skills/`** | Fundamentals, terminal usage, file handling, and basic tool proficiency. |
| **`Web-Exploitation/`** | Attacking web applications, SQL injection, XSS, and directory traversals. |
| **`Cryptography/`** | Breaking ciphers, encoding/decoding, and exploiting cryptographic flaws. |
| **`Forensics/`** | File carving, memory analysis, steganography, and packet capture investigation. |
| **`Binary-Exploitation/`** | Low-level attacks, buffer overflows, and memory corruption (Heavy Kali usage). |
| **`Reverse-Engineering/`** | Taking apart compiled programs and analyzing logic execution. |

*Note: CyLab Academy also features newer AI and Blockchain categories, which I will add folders for as I complete those tracks.*

## 🚀 How to Use This Repository

1. Navigate to the category folder you are interested in.
2. Each challenge has its own dedicated markdown file (e.g., `ChallengeName.md`).
3. Each writeup includes:
   *   **Challenge Details:** Description, category, and point value.
   *   **Initial Recon:** How I approached the problem on Windows (or why I immediately booted Kali).
   *   **The Exploit:** The step-by-step methodology to retrieve the flag.
   *   **Code:** Any custom Python or PowerShell scripts written to automate the solve.


## 🤝 Disclaimer

These writeups are purely for educational purposes. CyLab Academy provides a legal, safe environment to learn offensive security skills. Hacking systems without explicit authorization is illegal.
