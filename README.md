# LocalDevCertManager

Tools for creating and managing local development TLS certificates on Windows and WSL.

## Features
- Generate `.cer` and `.pfx` certificates with custom SAN names
- Install and trust certs on Windows and in WSL
- Cross-platform scripts for PowerShell and Bash

## Usage

### Windows PowerShell
```powershell
.\scripts\New-LocalDevCert.ps1 -DnsName "dev.local"
