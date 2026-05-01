# Linux Infrastructure Lab

Home lab simulating a production-grade infrastructure built on Ubuntu Server 26.04.

## Stack
- **OS:** Ubuntu Server 26.04
- **Virtualization:** KVM / Virtual Machine Manager (Fedora host)
- **Load Balancer:** HAProxy
- **Automation:** Ansible
- **Monitoring:** Nagios, ELK Stack
- **CI/CD:** GitLab CI
- **Security:** WireGuard VPN, OSSEC HIDS

## Architecture
| Machine | IP | Role |
|---|---|---|
| web01 | 192.168.122.10 | Web server |
| web02 | 192.168.122.11 | Web server |
| db01 | 192.168.122.20 | Database |

## Status
- [x] VM setup & network configuration
- [ ] Ansible automation
- [ ] Load balancing (HAProxy)
- [ ] Monitoring (Nagios + ELK)
- [ ] CI/CD pipeline
- [ ] VPN & security hardening

## Progress log
See [docs/progress.md](docs/progress.md)
