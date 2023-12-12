# ansible-hardening addition - hardening OS

This ansible role is for hardening an OS 
It' an addition to peedy2495/ansible-desktop-default-software

Tested with: Ubuntu 22.04 LTS

role-dependencies:
- mablanco/ansible-antirootkits
- geerlingguy/ansible-role-clamav

root password: "ChangeMe" as sha-512