# Linux & Cloud Labs

Hands-on labs covering Linux system administration and cloud infrastructure on AWS. Each lab folder has a write-up with objectives, the steps I followed, screenshots, and key takeaways.

## Labs

| # | Lab | Topics |
|---|---|---|
| 01 | [Deploy Linux Servers](lab-01-deploy-linux-servers/) | VirtualBox, Ubuntu Server, AWS EC2, Security Groups, SSH key pairs |
| 02 | [Deploy Services, Test, and Manage Workflow](lab-02-deploy-services-and-workflow/) | NAT/Host-only networking, OpenSSH, Apache2, systemctl, Git/GitHub deploy workflow |
| 03 | [Manage Access, Harden Services, Host Security Basics](lab-03-manage-access-harden-services/) | Users/groups, file permissions, sudo, SSH keys, sshd hardening, AllowGroups, ufw firewall |
| 04 | [Internetworking Basics: One Router, Two Networks](lab-04-internetworking-one-router/) | Subnet planning, static IPs, VirtualBox internal networks, IP forwarding, default gateways |

## Skills Practiced

- Linux installation and command-line basics
- Virtualization (VirtualBox)
- AWS EC2: launching, securing and terminating instances
- SSH key-based authentication
- Installing and managing services (OpenSSH, Apache) with `apt` and `systemctl`
- VM networking (NAT vs. Host-only)
- Git/GitHub version control and deploying to a web server
- Linux user, group and permission management
- SSH hardening (key-only auth, no root login, group-based access)
- Host firewalls with ufw
- IPv4 subnet planning and static addressing
- Linux as a router (IP forwarding, default gateways)
- Cloud security best practices

## Security Note

Screenshots and commands in this repository are sanitized. Account IDs, public IP addresses, hostnames, emails, usernames and keys are redacted or replaced with placeholders. All cloud resources shown were terminated after each lab.
