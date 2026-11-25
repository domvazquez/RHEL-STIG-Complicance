## 1 System Validation

Following the installation of RHEL 9.9, system validation
was performed to establish the initial system inventory
and verify the operating environment before security hardening.

### System Information

| Command | Purpose |
|---|---|
| `cat /etc/os-release` | Identify the operating system and release version. |
| `uname -r` | Display the currently running Linux kernel version. |
| `hostnamectl` | Verify the system hostname and operating system information. |
| `lscpu` | Display CPU architecture and processor information. |
| `free -h` | Display available and used system memory. |
| `lsblk` | Identify storage devices and disk partitions. |
| `df -h` | Display filesystem capacity and disk utilization. |

### Administrative Privileges

| Command | Purpose |
|---|---|
| `whoami` | Identify the currently authenticated user. |
| `sudo whoami` | Verify that the user can execute commands with elevated privileges. |

## 1.1 Network Validation

Network validation was performed to verify interface
configuration, routing, internet connectivity, and DNS
resolution before registering the system with Red Hat.

| Command | Purpose |
|---|---|
| `ip -br addr` | Display network interfaces and assigned IP addresses. |
| `ip route` | Display the routing table and default gateway. |
| `ping -c 4 1.1.1.1` | Test external IP connectivity. |
| `getent hosts redhat.com` | Verify DNS resolution through the system resolver. |

## Validation Results

| Validation Check | Status |
|---|---|
| Operating system verification | Success |
| Kernel verification | Success |
| Hostname verification | Success |
| CPU and memory verification | Success |
| Storage verification | Success |
| Administrative privileges | Success |
| Network configuration | Success |
| Default gateway | Success |
| Internet connectivity | Success |
| DNS resolution | Success |

## Purpose

System and network validation establish a functional
baseline before implementing security controls. This
helps distinguish existing configuration issues from
issues introduced during STIG remediation.