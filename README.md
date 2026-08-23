<h1 align="center">Ibrahim Diallo</h1>

<p align="center"><strong>DFIR | Malware Analysis | Reverse Engineering</strong></p>

<p align="center">
  <a href="https://www.linkedin.com/in/ibrahim-diallo75/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMDEtMi4wNjMtMi4wNjUgMi4wNjQgMi4wNjQgMCAxMTQuMTI3IDBjMCAxLjE0LS45MjQgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg==" alt="LinkedIn">
  </a>
  &nbsp;
  <a href="mailto:ibrahim.diallo@student-cs.fr">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIgNWgyMHYxNEgyVjV6bTIgMnYuNWw4IDUgOC01VjdINHptMTYgMTBWOS45bC04IDUtOC01VjE3aDE2eiIvPjwvc3ZnPg==" alt="Email">
  </a>
  &nbsp;
  <a href="https://tryhackme.com/p/xeroxx75">
    <img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe">
  </a>
</p>

<p align="center">
  <a href="https://profile.hackthebox.com/profile/019fee30-a361-7166-ac85-0807fc0845f9">
    <img src="https://img.shields.io/badge/Hack%20The%20Box-111927?style=for-the-badge&logo=hackthebox&logoColor=9FEF00" alt="Hack The Box">
  </a>
  &nbsp;
  <a href="https://www.root-me.org/Xeroxx">
    <img src="https://img.shields.io/badge/Root--Me-000000?style=for-the-badge&logo=rootme&logoColor=white" alt="Root-Me">
  </a>
</p>

Dual-degree cybersecurity engineering student at CentraleSupélec and ECE Paris, ranked first in my specialization. I am completing my final-year internship in an internal CERT and looking for my first full-time role in DFIR, malware analysis or reverse engineering.

I build practical projects that connect low-level behavior with defensible forensic evidence: binary structure, debugging, memory, endpoint artifacts, timelines and detection.

## Featured Projects

### [DFIR and Reverse Engineering Labs](https://github.com/Xeroxx75/dfir-reverse-labs)

Hands-on investigations covering Linux and Windows incidents, memory and disk forensics, malware analysis, crackmes and YARA. It includes a six-stage Honeynet Collapse investigation with cross-host timeline correlation.

`Volatility 3` `KAPE` `Eric Zimmerman tools` `EVTX` `APFS` `YARA`

### [Incident to RCE](https://github.com/Xeroxx75/incident-to-rce)

Controlled binary-exploitation case study reconstructed from a PCAP and C source audit. The complete chain was tested end to end in the original lab environment: format-string leak, off-by-one, pointer corruption, RET hijacking, x86 shellcode and RCE, followed by remediation analysis.

`PCAP` `C` `GDB` `Python` `x86 shellcode` `RCE`

### [Windows Source-to-Binary Labs](https://github.com/Xeroxx75/windows-re-source-to-binary-labs)

Progressive C/C++ experiments that compare source predictions with PE metadata, disassembly, decompiler output, debugger state and runtime artifacts. The goal is to distinguish developer logic from compiler, CRT, loader and operating-system behavior before reversing unknown binaries.

`C/C++` `PE` `x86/x64` `Ghidra` `x64dbg` `Win32`

### [Linux Vulnerability Monitor](https://github.com/Xeroxx75/linux-vulnerability-monitoring)

Centralized Linux vulnerability monitoring proof of concept. A non-root agent inventories Ubuntu and Debian systems, sends SBOMs over HTTPS, correlates findings with Grype and preserves current and historical state in PostgreSQL. The project includes observability, alerting, Ansible deployment and QEMU/KVM validation of reboot, outage, spooling and recovery paths.

`Python` `Syft` `Grype` `PostgreSQL` `Prometheus` `Grafana` `Podman` `Ansible` `QEMU/KVM`

### [DFIR and Reverse Engineering Notes](https://github.com/Xeroxx75/dfir-reverse-notes)

My public French-language knowledge base: concise entry points, detailed technical procedures and reusable commands for DFIR, malware analysis and reverse engineering.

### DisCover - Control-Flow Graph Recovery

Academic C++ team project that recovers control-flow graphs from x86-64 and AArch64 ELF binaries through recursive-descent disassembly, DWARF enrichment and structural validation. The source belongs to the school and cannot be published.

`C++` `Capstone` `LIEF` `DWARF` `ELF` `SVG`
