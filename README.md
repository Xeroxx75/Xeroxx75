# Xeroxx

Cybersecurity engineering student at CentraleSupélec and ECE Paris, focused on **DFIR, malware analysis, Windows internals, and reverse engineering**.

I build reproducible labs to connect low-level behavior with forensic evidence: PE structure, assembly, debugging, memory, Windows artifacts, detection rules, and incident timelines.

## Current focus

- Windows reverse engineering with Ghidra and x64dbg
- Static and dynamic malware analysis in isolated environments
- Memory and disk forensics with Volatility 3, KAPE, Sysmon, and Windows artifacts
- Detection engineering with YARA, Sigma, and MITRE ATT&CK
- Python and C/C++ tooling for analysis and automation

## Featured projects

### [Linux Vulnerability Monitor](https://github.com/Xeroxx75/linux-vulnerability-monitoring)

Educational proof of concept for centralized Linux vulnerability monitoring on Ubuntu and Debian.

A non-root agent inventories packages with Syft and sends the SBOM over HTTPS to a central API. Grype performs version-aware analysis, PostgreSQL preserves findings and history, while Prometheus, Grafana, and Alertmanager expose bounded metrics, dashboards, and grouped alerts.

The full path was validated in disposable QEMU/KVM environments, including Debian and Ubuntu backports, systemd execution, reboot, network outage, local spooling, and recovery.

**Stack:** Python, Syft, Grype, PostgreSQL, Prometheus, Grafana, Alertmanager, Podman, Ansible, systemd, QEMU/KVM.

### [Windows RE Source-to-Binary Labs](https://github.com/Xeroxx75/windows-re-source-to-binary-labs)

Progressive Windows reverse engineering experiments built from small C/C++ programs.

Each lab starts with source-level predictions, compiles PE variants, then compares the source with PE metadata, disassembly, decompiler output, runtime behavior, and debugger observations. The goal is to understand what comes from the developer, compiler, CRT, loader, and operating system before moving to unknown binaries.

**Topics:** x86/x64 assembly, PE internals, calling conventions, Win32 APIs, processes, threads, DLL loading, TLS callbacks, compiler optimizations, and packing fundamentals.

### [DFIR & Reverse Labs](https://github.com/Xeroxx75/DFIR_Reverse_Labs)

Hands-on investigations combining memory forensics, Windows artifact analysis, malware reverse engineering, timeline reconstruction, and detection engineering.

The repository includes a simulated Windows compromise, an academic ransomware analysis, crackme reverse engineering, a TrueCrypt/KeePass memory investigation, defensive recovery tooling, and YARA rules derived from observed artifacts.

### DisCover: Control-Flow Graph Recovery

Academic C++ team project for recovering control-flow graphs from x86-64 and AArch64 ELF binaries.

DisCover uses recursive-descent disassembly with Capstone and LIEF, enriches analysis with DWARF information, renders CFGs as SVG, reports recovery coverage and unresolved indirect branches, and checks structural graph invariants across real binaries.

The project source belongs to the school and cannot be published on GitHub.

## Contact

- [LinkedIn](https://www.linkedin.com/in/ibrahim-diallo75/)
- [Email](mailto:ibrahim.diallo@student-cs.fr)
