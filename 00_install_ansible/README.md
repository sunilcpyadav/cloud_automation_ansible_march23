* How to install Ansible

** On Windowns

1. Install WSL 2 (Windows Subsystem for Linux)
	
	- Please follow the steps from here: https://docs.microsoft.com/en-us/windows/wsl/wsl2-install
	
2. We recommend to use Visual Studio Code with the Remote WSL Extension
	
	- Download Visual Studio Code: https://code.visualstudio.com/download
	- Remote WSL Extension: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl
	
3. Open the WSL terminal and install ansible:

	```bash
	$ sudo apt update
	$ sudo apt install software-properties-common
	$ sudo apt-add-repository --yes --update ppa:ansible/ansible
	$ sudo apt install ansible	
	```
	
** On OS X

The preferred way to install Ansible on a Mac is with pip.

```bash
$ curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
$ python get-pip.py --user

$ pip install --user ansible

$ pip install --user git+https://github.com/ansible/ansible.git@devel
```

Documentation page: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#from-pip
