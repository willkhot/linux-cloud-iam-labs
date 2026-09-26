# Linux & Cloud Labs

Hands-on labs covering Linux system administration, networking, security, cloud infrastructure, and identity & access management. Each lab has a write-up with objectives, the steps I followed, screenshots, and key takeaways.

## 🐧 [Linux Labs](linux-labs/)

| # | Lab | Topics |
|---|---|---|
| 01 | [Deploy Linux Servers](linux-labs/lab-01-deploy-linux-servers/) | VirtualBox, Ubuntu Server, AWS EC2, Security Groups, SSH key pairs |
| 02 | [Deploy Services, Test, and Manage Workflow](linux-labs/lab-02-deploy-services-and-workflow/) | NAT/Host-only networking, OpenSSH, Apache2, systemctl, Git/GitHub deploy workflow |
| 03 | [Manage Access, Harden Services, Host Security Basics](linux-labs/lab-03-manage-access-harden-services/) | Users/groups, file permissions, sudo, SSH keys, sshd hardening, AllowGroups, ufw firewall |
| 04 | [Internetworking Basics: One Router, Two Networks](linux-labs/lab-04-internetworking-one-router/) | Subnet planning, static IPs, VirtualBox internal networks, IP forwarding, default gateways |
| 05 | [Internetworking Basics: Two Routers, Three Networks](linux-labs/lab-05-internetworking-two-routers/) | /29 subnetting, multi-router topology, static routes, next-hop routing, hop-by-hop troubleshooting |

## ☁️ [Cloud Labs](cloud-labs/)

| Platform | Labs |
|---|---|
| [AWS](cloud-labs/aws/) | *Coming soon* |
| [Azure](cloud-labs/azure/) | *Coming soon* |

## 🔐 [IAM Labs](iam-labs/)

Identity and Access Management with Microsoft Entra ID (SC-300).

| # | Lab | Topics |
|---|---|---|
| | *Coming soon* | |

## Skills Practiced

**Linux & Systems**
- Linux installation and command-line basics
- Virtualization (VirtualBox)
- Installing and managing services (OpenSSH, Apache) with `apt` and `systemctl`
- Linux user, group and permission management
- Git/GitHub version control and deploying to a web server

**Security**
- SSH key-based authentication
- SSH hardening (key-only auth, no root login, group-based access)
- Host firewalls with ufw
- Cloud security best practices

**Networking**
- VM networking (NAT vs. Host-only)
- IPv4 subnet planning and static addressing
- Linux as a router (IP forwarding, default gateways)
- Static routing across multiple routers

**Cloud**
- AWS EC2: launching, securing and terminating instances

## Security Note

Screenshots and commands in this repository are sanitized. Account IDs, public IP addresses, hostnames, emails, usernames and keys are redacted or replaced with placeholders. All cloud resources shown were terminated after each lab.
