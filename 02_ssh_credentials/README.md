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

