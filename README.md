# Ansible playbook for Decidim on Arch

This repository contains an Ansible playbook to support Decidim installation with all dependencies on Arch Linux.

Example install command:
```
% ansible-playbook site.yml -i hosts -u decidim --ask-become-pass --extra-vars '{"host":"192.168.122.100"}'
```

## License

MIT
