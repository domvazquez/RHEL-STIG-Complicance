# RHEL STIG Compliance Lab

![Status](https://img.shields.io/badge/Status-In_Progress-orange)
![OS](https://img.shields.io/badge/OS-RHEL_9-red)
![Security](https://img.shields.io/badge/Security-DISA_STIG-blue)
![Compliance](https://img.shields.io/badge/Compliance-OpenSCAP-green)

## Overview

This project demonstrates the deployment, security hardening, assessment, and validation of Red Hat Enterprise Linux systems using Department of Defense (DoD) security standards.

## Purpose

The purpose of this project is to simulate the process of deploying and securing enterprise Linux systems within a defense-oriented environment. The lab focuses on implementing DISA STIG requirements, identifying security misconfigurations, remediating vulnerabilities, and validating system security without compromising operational functionality.

This project also aims to develop hands-on experience in Linux systems integration, security compliance, configuration management, and automated operating system deployment while applying principles of the NIST Risk Management Framework (RMF).

## Objectives

- Deploy and configure a RHEL 9 environment.
- Perform baseline DISA STIG assessments using OpenSCAP.
- Analyze and prioritize CAT I, II, and III findings.
- Manually remediate insecure system configurations.
- Validate security improvements through reassessment and functional testing.
- Automate security hardening using Ansible.
- Implement repeatable operating system deployments using Kickstart.
- Document security findings, remediation procedures, and validation results.

## Technologies

| Technology | Purpose |
|---|---|
| RHEL 9.9 | Enterprise Linux operating system |
| DISA STIG | Security configuration requirements |
| OpenSCAP | Automated compliance assessments |
| SCAP Security Guide | Security assessment content |
| Ansible | Configuration and remediation automation |
| Kickstart | Automated OS deployment |
| Bash | System administration and automation |
| SELinux | Mandatory access control |
| Auditd | Security auditing |
| Firewalld | Network access control |

## Project Roadmap

- [ ] Phase 1 — Environment Setup
- [ ] Phase 2 — Baseline STIG Assessment
- [ ] Phase 3 — Manual Security Remediation
- [ ] Phase 4 — Compliance Validation
- [ ] Phase 5 — Ansible Automation
- [ ] Phase 6 — Kickstart Deployment
- [ ] Phase 7 — Final Documentation

## Compliance Results

Results will be recorded following baseline assessment and remediation.

| Metric | Baseline | Hardened |
|---|---|---|
| Compliance score | TBD | TBD |
| Passed controls | TBD | TBD |
| Failed controls | TBD | TBD |
| CAT I findings | TBD | TBD |
| CAT II findings | TBD | TBD |
| CAT III findings | TBD | TBD |

## Risk Management Framework

This lab explores technical activities associated with the NIST Risk Management Framework, particularly:

- **Implement:** Apply security controls and system hardening requirements.
- **Assess:** Evaluate implemented controls through automated and manual assessments.
- **Monitor:** Identify configuration drift and maintain system security over time.

## Disclaimer

This project is an independent educational lab. It does not represent an officially authorized or certified DoD information system.

## References

- [DISA STIGs](https://public.cyber.mil/stigs/)
- [OpenSCAP](https://github.com/OpenSCAP/openscap)
- [ComplianceAsCode](https://github.com/ComplianceAsCode/content)
- [NIST SP 800-37](https://csrc.nist.gov/pubs/sp/800/37/r2/final)
- [Ansible RHEL9-STIG](https://github.com/ansible-lockdown/RHEL9-STIG)
