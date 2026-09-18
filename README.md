# home-lab
Home lab setup and notes while studying for CompTIA Security+

Documenting my journey building a home lab as I study for CompTIA Security+ 
(exam scheduled October 12, 2026). Goal is to get hands-on with virtualization, 
networking, and security fundamentals beyond what I've picked up doing personal 
PC builds and network troubleshooting.

## Current Setup
- Host: Windows 11, Intel Core i7-12700F, 16GB RAM
- Hypervisor: VirtualBox
- VMs: lab-ubuntu-01 (Ubuntu Server 26.04.1 LTS) — running


## Log

### September 18, 2026
- Installed VirtualBox on host machine
- Created first VM (lab-ubuntu-01) running Ubuntu Server 26.04.1 LTS
- Completed unattended install, logged in successfully
- Confirmed VM networking with `ip a` — enp0s3 interface UP, assigned 10.0.2.15/24
- Next: install pfSense as a second VM to act as a virtual firewall/router

## Why
Background in IT support fundamentals (PC builds, Windows troubleshooting, 
home networking) — using this lab to build practical security and networking 
skills as I work toward Security+ and an entry-level IT/security role.
