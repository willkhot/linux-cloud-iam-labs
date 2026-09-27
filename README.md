# Linux, Cloud & IAM Labs

Hands-on labs covering Linux system administration, networking, security, cloud infrastructure, and identity & access management. Each lab has a write-up with objectives, the steps I followed, screenshots, and key takeaways.

## 🐧 [Linux Labs](linux-labs/)

| # | Lab | Topics |
|---|---|---|
| 01 | [Deploy Linux Servers](linux-labs/lab-01-deploy-linux-servers/) | VirtualBox, Ubuntu Server, AWS EC2, Security Groups, SSH key pairs |
| 02 | [Deploy Services, Test, and Manage Workflow](linux-labs/lab-02-deploy-services-and-workflow/) | NAT/Host-only networking, OpenSSH, Apache2, systemctl, Git/GitHub deploy workflow |
| 03 | [Manage Access, Harden Services, Host Security Basics](linux-labs/lab-03-manage-access-harden-services/) | Users/groups, file permissions, sudo, SSH keys, sshd hardening, AllowGroups, ufw firewall |
| 04 | [Internetworking: One Router, Two Networks](linux-labs/lab-04-internetworking-one-router/) | Subnet planning, static IPs, VirtualBox internal networks, IP forwarding, default gateways |
| 05 | [Internetworking: Two Routers, Three Networks](linux-labs/lab-05-internetworking-two-routers/) | /29 subnetting, multi-router topology, static routes, next-hop routing, hop-by-hop troubleshooting |

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

## What I've Been Learning

I'm still learning all of this, and these labs are how I've been practicing. So far I've gotten comfortable with:

**Linux**
- Installing Ubuntu Server in VirtualBox and finding my way around the command line
- Installing software with `apt` and starting or stopping services with `systemctl`
- Creating users and groups and setting who can access which files
- Using Git and GitHub to get a website from my laptop onto a server

**Security**
- Logging in with SSH keys instead of passwords
- Locking down SSH so root can't log in and only certain users can
- Setting up a basic firewall with ufw
- Only opening the ports I actually need, and shutting down cloud resources when I'm done with them

**Networking**
- How NAT and Host-only networking work for VMs
- Planning subnets and giving machines static IPs
- Turning a Linux VM into a router
- Adding static routes so traffic can cross more than one router

**Cloud**
- Launching an EC2 instance on AWS, connecting to it, and terminating it when I'm done

## Author

**Will Khotsyphom**

[![GitHub](https://img.shields.io/badge/GitHub-willkhot-181717?logo=github)](https://github.com/willkhot)

## Security Note

Screenshots and commands in this repository are sanitized. Account IDs, public IP addresses, hostnames, emails, usernames and keys are redacted or replaced with placeholders. All cloud resources shown were terminated after each lab.
