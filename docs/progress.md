# Project Progress Log

## Stage 1 - VM Setup 

 - Initial virtual machine setup - install, network configuration, disk	setup

 - Installed OpenSSH for remote management from host

## Stage 2 - Ansible  

 - Configured inventory with groups [web_servers] and [databases]

 - Generated SSH keys and uploaded them to the machines

 - Configured passwordless sudo for Ansible automation

 - Wrote and applied base_setup.yml playbook, installing base tools on all machines

 - Wrote and applied webservers_setup.yml - Nginx installed and running on web servers

 - Wrote and applied database_setup.yml - MySql installed and running on database

 - Wrote and applied users.ymp - created dedicated ansible user on all machines

 - Configured ProxyJump for remote management from second machine

## Stake 3 - Load Balancing

 - Installed and configured HAProxy on haproxdy01 (192.168.122.30)

 - Configured roundrobin load balancing between web01 and web02

 - Verified traffic distribution via HAProxy logs

