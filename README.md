# Hi, I'm Jarno Nousiainen

IT Specialist from Finland with 20+ years of experience in Windows Server, Active Directory, Group Policy, Microsoft 365, Microsoft Entra ID, Microsoft Intune, Exchange Online, PowerShell, Linux administration and infrastructure operations.

My roots go back to late 1980s and early 1990s DOS systems, especially MS-DOS 5 era PCs. Since then, the tools have changed from `CONFIG.SYS` and `AUTOEXEC.BAT` to cloud portals, endpoint management and automation pipelines, but the core idea is still the same: understand the system, document it clearly and fix things without creating new chaos. Humanity has bravely renamed this “modern IT operations”.

I build practical PowerShell, Bash and batch-based tools for IT auditing, operational visibility, health checks, reporting and controlled endpoint remediation.

## Focus areas

- Windows Server and Active Directory
- Group Policy
- Microsoft 365
- Microsoft Entra ID
- Microsoft Intune
- Exchange Online
- PowerShell automation
- Linux Mint, Debian, Ubuntu and LMDE systems
- Bash scripting
- Endpoint management
- IT auditing and reporting
- Operational documentation
- Public-safe scripting practices
- Retro DOS healthcheck tooling

## Featured work

### PowerShell Audit Scripts

Public-safe PowerShell audit and reporting toolkit for Windows Server, Active Directory, Group Policy, Microsoft 365, Exchange Online, Microsoft Entra ID and Microsoft Intune environments.

The repository demonstrates read-only audit scripting, structured reporting, GitHub Actions quality checks, Pester tests, PSScriptAnalyzer, secret scanning, public safety checks, MIT licensing, branch protection and GitHub Pages documentation.

- Repository: https://github.com/Jarnon404/powershell-audit-scripts
- Documentation: https://jarnon404.github.io/powershell-audit-scripts/

### Intune Winget App Updater

Controlled Microsoft Intune Proactive Remediation package for updating approved Windows applications with `winget`.

The repository includes detection and remediation scripts, offline technician tooling, GitHub Actions quality checks, Pester tests, PSScriptAnalyzer, secret scanning, public safety checks, MIT licensing, versioned releases and GitHub Pages documentation.

This repository is intentionally documented as a remediation package, not as a read-only audit project, because the remediation script can update applications on managed Windows devices.

- Repository: https://github.com/Jarnon404/intune-winget-app-updater
- Documentation: https://jarnon404.github.io/intune-winget-app-updater/

### Linux Health & Security Audit

Read-only Bash audit tool for Debian, Ubuntu, Linux Mint and LMDE systems.

The repository generates TXT, HTML and JSON reports for Linux workstation and small server baseline checks. It focuses on system health, update status, kernel information, failed services, firewall state, SSH configuration, AppArmor status, disk usage, firmware tooling and other practical operational indicators.

The goal is simple: collect useful Linux health and security information without changing the system. Revolutionary stuff, apparently.

- Repository: https://github.com/Jarnon404/linux-health-security-audit
- Documentation: https://jarnon404.github.io/linux-health-security-audit/
- Release: https://github.com/Jarnon404/linux-health-security-audit/releases/tag/v1.1.0

### DOS Healthcheck

Retro-style DOS 3.x, 4.x, 5.x and 6.x system audit and health check toolkit using classic batch files and plain text reports.

This project is a small nod to where my IT path started: DOS PCs, conventional memory, `CONFIG.SYS`, `AUTOEXEC.BAT`, drivers, paths and the beautiful simplicity of text-based diagnostics. It includes a baseline `HEALTH.BAT` for DOS 3.x to 6.x and an extended `HEALTH6.BAT` for DOS 6.x systems.

It is intentionally simple, because DOS does not need a YAML pipeline, a Kubernetes operator or seventeen dashboards to tell you that conventional memory is tight.

- Repository: https://github.com/Jarnon404/dos-healthcheck
- Documentation: https://jarnon404.github.io/dos-healthcheck/
- Release: https://github.com/Jarnon404/dos-healthcheck/releases/tag/v1.0.0

## Repository principles

The repositories I publish are intended to be:

- practical
- documented
- testable where useful
- public-safe
- reusable
- clear about risk and operational impact
- honest about whether they only audit or actually change something

I prefer controlled scripts, readable output and explicit documentation over clever one-liners that become archaeology after six months.

## Background

I have worked with IT infrastructure, support, systems administration, identity, endpoint management and Microsoft environments across on-premises, hybrid and cloud-based setups.

My work usually combines hands-on troubleshooting, scripting, documentation, operational improvement and translating technical issues into something people can actually act on.

The technical timeline is fairly clear:

```text
DOS and classic PC troubleshooting
→ Windows Server, Active Directory and Group Policy
→ Microsoft 365, Entra ID, Exchange Online and Intune
→ PowerShell automation and endpoint management
→ Linux health and security auditing
