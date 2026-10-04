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
| [AWS](cloud-labs/aws/) | [01 — Introduction to AWS IAM](cloud-labs/aws/lab-01-intro-to-iam/) |

## 🔐 [IAM Labs](iam-labs/)

Identity and Access Management with Microsoft Entra ID. Documenting what I'm learning as I study for SC-300.

| # | Lab | Topics |
|---|---|---|
| 01 | [Manage Users, Groups, Licenses, and Custom Security Attributes](iam-labs/lab-01-manage-users-groups-licenses/) | Users, security groups, dynamic membership, group-based licensing, custom security attributes |
| 02 | [Company Branding, Entra Roles, Custom Roles, and Administrative Units](iam-labs/lab-02-branding-roles-admin-units/) | Sign-in branding, role assignment, role-assignable groups, custom roles, administrative units, custom domains, tenant settings |
| 03 | [External Identities: Guest Users, Cross-Tenant Access, and Collaboration Settings](iam-labs/lab-03-external-identities/) | Guest vs member users, B2B invitations, cross-tenant access settings, identity providers, external collaboration settings |

## What I've Been Learning

Here's what I've picked up so far:

**Linux**
- Setting up Ubuntu Server VMs and getting comfortable on the command line
- Installing and running services like SSH and a web server (Apache)
- Managing users, groups, and who can access which files
- Getting a website from my laptop onto a server with Git and GitHub

**Networking**
- How a VM connects to the internet and to my own computer
- Planning subnets and giving machines static IPs
- How routers pass traffic between networks, and why every router needs to know the way there and the way back

**Security**
- Using SSH keys instead of passwords, and limiting who's allowed to log in
- Setting up a basic firewall that only lets in what's needed
- Always leaving myself a way back in before changing login settings (I learned that one by locking myself out)

**Cloud (AWS)**
- Launching a server on EC2, connecting to it, and shutting it down when I'm done
- Using IAM groups and policies so each user only gets the access their job needs

**Identity (Microsoft Entra ID)**
- Creating and managing users and groups, including groups that add people automatically based on a rule
- Giving out licenses to a whole group instead of one person at a time
- Tagging users with custom attributes, like a security clearance level

The same idea keeps coming up in every lab, whether it's Linux, AWS, or Entra: give people only the access they actually need. It's called least privilege, and it shows up everywhere.

## Author

**Will Khotsyphom**

[![GitHub](https://img.shields.io/badge/GitHub-willkhot-181717?logo=github)](https://github.com/willkhot)

## Security Note

Screenshots and commands in this repository are sanitized. Account IDs, public IP addresses, hostnames, emails, usernames and keys are redacted or replaced with placeholders. All cloud resources shown were terminated after each lab.
