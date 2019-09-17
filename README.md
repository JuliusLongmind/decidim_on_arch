# Ansible for Decidim on Arch

[![Build Status](https://travis-ci.org/geerlingguy/ansible-for-devops.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-for-devops)

This repository contains an Ansible playbook to support Decidim installation with all dependencies on Arch Linux.

Example install command:

> ansible-playbook site.yml -i hosts -u decidim --ask-become-pass --extra-vars '{"host":"192.168.122.100"}'


## License

MIT
