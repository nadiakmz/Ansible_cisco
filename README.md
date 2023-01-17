# Ansible_cisco
Ansible Scripts for Cisco Switches

### L3 Interfaces Script:
This script gathers the L3 Interfaces of the given Cisco switches, then it will configure them from TEMPLATE.J2

You can enter your switches IP in ./inventory/switches and you have to enter your **username** and **password** in ./inventory/group_vars/all.yml.

You can enter your configuration which you want to configure for each L3 interface in ./roles/L3_Interface/templates/TEMPLATE.j2

