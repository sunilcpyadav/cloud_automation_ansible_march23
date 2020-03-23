To run playbooks:

```bash
ansible-playbook install_nginx.yml
```

If you need to provide password for sudo, use this command:

```bash
ansible-playbook install_nginx.yml --ask-become-pass
```

Ansible module index: https://docs.ansible.com/ansible/latest/modules/modules_by_category.html
Apt module documentation: https://docs.ansible.com/ansible/latest/modules/apt_module.html
