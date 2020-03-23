SSH key configuration:

```bash
chmod 600 keyfile.pem
```

Log in to the machine with SSH:
```bash
ssh -i keyfile.pem ubuntu@public-ip
```

Try to run:

```bash
ansible -m ping all
```

Execute command remotely:

```bash
ansible -m command -a 'cat /etc/hosts' all
```

Other modules which are "similar" to command:

Shell: https://docs.ansible.com/ansible/latest/modules/shell_module.html

Raw: https://docs.ansible.com/ansible/latest/modules/raw_module.html (does not require python to be installed on target)

Command: https://docs.ansible.com/ansible/latest/modules/command_module.html
