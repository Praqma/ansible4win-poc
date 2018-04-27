---
maintainer: mortench3000
---

# Ansible4win-poc

### Description
This project is made as a proof-of-concept demonstrating configuration management for a set of build and test nodes primarily (but not exclusively) based on Windows.

## Prepare Ubuntu Ansible node
1) Install Git, libssl-dev, Python, Python-pip, pyWinRm (python package), python-requests
2) Checkout this repo
3) pip install -r docs/py-requirements.txt
4) Follow the Ansible installation guide for Ubuntu:
[Ansible installation](http://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-apt-ubuntu)

## Prepare Windows node
1) Create local admin user for Ansible: ansibleuser
2) Follow the Ansile setup guide for Windows: [Setting up a Windows host](http://docs.ansible.com/ansible/latest/user_guide/windows_setup.html)

## References
[Nice Ansible project template](https://github.com/cow-co/ansible-template)

[A shot at Ansible Best Practices](https://github.com/enginyoyen/ansible-best-practises)
