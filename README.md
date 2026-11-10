# GoSH — Go-Based Interactive WebSocket Operator Agent

A lightweight, concurrent Windows operator agent and reverse shell client written in Go. Engineered for low-overhead interactive command sessions, system state telemetry, and encrypted command-and-control channel emulation over WebSockets.

---

## ⚙️ Architectural Overview

* **Language Runtime:** Go (Golang) compiled directly to native 64-bit Windows PE (`PE32+ x86-64`).
* **Transport Protocol:** Encrypted WebSocket duplex channel (`gorilla/websocket`) designed for seamless firewall traversal over standard HTTP/HTTPS infrastructure.
* **System Telemetry:** Real-time host profiling including `GlobalMemoryStatusEx`, display buffer capture, and OS execution metrics.
* **Payload Size:** Self-contained statically linked executable (~6 MB) with zero external runtime dependencies.

---

## 🛡️ Operational & Educational Disclaimer

> **DISCLAIMER:** This software is designed and maintained strictly for authorized penetration testing, adversary emulation, home-lab security simulations, and academic research purposes. Unauthorized access to computer systems is illegal under national and international law. The author assumes no liability for misuse.
