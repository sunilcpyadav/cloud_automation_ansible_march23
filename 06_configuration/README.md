## Controlling executions

Specify task types (with tags):

```bash
ansible-playbook playbook.yml --list-tags
ansible-playbook playbook.yml --tags tag_name
```

Specify hosts (or groups) where you want to execute your playbook (restirct hosts:):

```bash
ansible-playbook playbook.yml --list hostname
```
