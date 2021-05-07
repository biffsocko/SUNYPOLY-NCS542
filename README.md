# SUNYPOLY-NCS542
# Tom Murphy 
# Spring 2021

Goal:
Implement Chapter 3 (Networking) from CIS Benchmarks for CentOS 8 and Ubuntu 20.04 LTS

Notes:
I simplified the firewall rules and stuck with the basics.  I verified that the firwall was installed and running, however I strayed from turning on/off 
specific rules because of the day to day functionality of the two laptops in question.  

Also, I did not turn off wireless networking - because they are laptops are rely on wireless networking.  



Ansible Modules used:
in Ubuntu I used the apt module for package management:  https://docs.ansible.com/ansible/2.3/apt_module.html

In CentOS I used the dnf module for package management:  https://docs.ansible.com/ansible/2.3/dnf_module.html

in both CentOS and Ubuntu I used the copy module to copy over modprobe configuration files:  https://docs.ansible.com/ansible/2.3/apt_module.html

in both CentOS and Ubuntu I used the service module to make sure the firewall was running:  https://docs.ansible.com/ansible/2.3/service_module.html


