# Project Progress Log

## Stage 1 - VM Setup 

 - Initial virtual machine setup - install, network configuration, disk	setup

 - Installed OpenSSH for remote management from host

## Stage 2 - Ansible  

 - Configured inventory with groups [web_servers] and [databases]

 - Generated SSH keys and uploaded them to the machines

 - Configured passwordless sudo for Ansible automation

 - Wrote and applied base_setup.yml playbook, installing base tools on all machines

 - Wrote and applied webservers_setup.ymp - Nginx installed and running on web servers
