# VDIAS

**Infrastructure Architect**  
*Cloud infrastructure · Systems engineering · Automation*

I design, automate and operate infrastructure with a strong focus on **simplicity, security, maintainability and repeatability**.

## Focus

- **Microsoft Azure** architecture and platform engineering
- **Linux** infrastructure
- **PowerShell** and **Bash** automation
- **Networking, DNS and security**
- **Identity and access management**
- and self-hosted infrastructure...

## Principles

**Automation first**  
Reduce repetitive operations wherever automation is practical and maintainable.

**Keep infrastructure simple**  
Prefer clear, maintainable designs over unnecessary complexity.

**Least privilege by default**  
Access should be granted deliberately and only where required.

**Make systems observable**  
Infrastructure should expose enough information to understand its state and behaviour.

**Reproducible deployments**  
Changes should be repeatable, predictable and documented.

**Security by design**  
Security should be considered from the beginning, not added afterwards.

**Prefer supported solutions**  
Use documented and supported approaches whenever possible.

## `profile.yaml`

```yaml
identity:
  name: VDIAS
  role: Infrastructure Architect

domains:
  cloud:
    - Microsoft Azure

  systems:
    - Linux
    - Windows Server

  automation:
    - PowerShell
    - Bash
    - GitHub Actions

  infrastructure:
    - Networking
    - DNS
    - Identity
    - Security

principles:
  automation: first
  complexity: minimize
  privilege: least
  observability: required
  deployments: reproducible
  security: by_design
  solutions: supported_and_documented
```
