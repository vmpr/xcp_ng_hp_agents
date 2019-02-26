xcp_ng_hp_agents
======================

this ansible role can be used to automate the installation of HP Agents and Tools for XCP-NG bare metal systems.

Requirements
------------
for the role:

- minimum ansible version: 2.7 ( never tested below)

Role Variables
--------------

Description of all variables are documented here: [defaults/main.yml](https://github.com/vmpr/xcp_ng_hp_agents/tree/master/defaults/main.yml)

Installation
------------
`ansible-galaxy install vmpr.xcp_ng_hp_agents`


Example Playbook
----------------
```
    - hosts: hp_servers_xcpng
      roles:
         - { role: vmpr.xcp_ng_hp_agents }
```         

License
-------
Apache

Todo:
-----
- [ ] enable role to use it for normal Citrix XenServer Systems

Author Information
------------------

Ringo Gierth
