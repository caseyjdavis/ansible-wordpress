# ansible-wordpress
Creating an instance of Wordpress inside a Docker container using Ansible

I started with a clean install of Ubuntu on Windows Subsystem for Linux, then ran prerequistes commands

Prerequisites
- sudo apt update
- sudo apt upgrade
- sudo apt install ansible

Clone repository
```
git clone https://github.com/caseyjdavis/ansible-wordpress.git
```

Run the playbook
```
cd ansible-wordpress/
sudo ansible-playbook dockerwordpressplaybook.yml
```

Installs
- MariaDB
- Nginx
- PHP
- Wordpress latest

### Command prompt output
![Log output of ansible](log-output.png)

### Welcome Screen for Wordpress
![Wordpress welcome install page](wordpress-welcome.png)

### Docker process monitor
![Screenshot of process monitoring](docker-process.png)
