# Cyre3x — Educational Malware Analysis & Defense Simulation Platform

> **For educational use only.** All simulations run in a sandboxed, offline environment. No real system damage can occur.

A Python desktop application built for cybersecurity training. Cyre3x lets security students and professionals experience both sides of an attack simulating real malware behavior (red team) and learning how to detect and respond to it (blue team).

Built as my Master's term project at **Üsküdar University, Istanbul (2025–2026)**.

---

## What It Does

Cyre3x provides six malware simulation modules, each paired with a blue team defense guide:

| Module | What It Simulates |
|---|---|
| Ransomware | File encryption using AES 256 GCM, RSA 4096 key wrapping, ECC ECIES hybrid encryption |
| Virus | Self-replicating file infection behavior |
| Worm | Network propagation simulation |
| Keylogger / Spyware | Keystroke capture and screen monitoring |
| Trojan | Disguised payload delivery |
| Backdoor / C2 | TCP socket command-and-control (localhost only), screen streaming, file transfer |

Each module includes:
- Step by step guided attack workflow

- Real time activity console and session logging
- Blue team defense guide: detection methods, indicators of compromise (IoCs), and incident response steps

---

## Tech Stack

- **Language:** Python
- **GUI:** PyQt6
- **Cryptography:** `cryptography` library (AES-256-GCM, RSA-4096, ECC-ECIES / secp256r1)
- **Networking:** TCP sockets (localhost / 127.0.0.1)
- **System interaction:** pynput, psutil, Pillow, pywin32
- **Packaging:** PyInstaller (self-contained Windows installer)

---

## Architecture

- All simulations are **isolated to localhost** no external network traffic
- Designed as a **safety-first** platform: no actual files are permanently damaged
- Runs fully **offline** after installation
- Packaged as a Windows `.exe` no Python environment needed on the target machine

## Blue Team defense guide 
## Red Team attack guide
---

## Screenshots
<img width="1726" height="1250" alt="Screenshot 2026-05-28 195937" src="https://github.com/user-attachments/assets/aa45cfe7-0087-419c-a01f-3dab25e8d73a" />

<img width="1299" height="937" alt="image" src="https://github.com/user-attachments/assets/676c7df2-b9ab-4340-9613-6b8e258ae13b" />

<img width="1726" height="1251" alt="Screenshot 2026-05-28 200409" src="https://github.com/user-attachments/assets/bb73ea14-a90f-4bc2-a6b9-adf430ba685c" />

<img width="1686" height="829" alt="image" src="https://github.com/user-attachments/assets/45a93e78-db1c-4d33-a1a0-1f5abb03c506" />



>

---

## Source Code

The full source code is available **upon request** for academic or professional review or use.
Contact: m.deiab08@gmail.com 

---

## Author

**Mohammad Abu Deiab**

