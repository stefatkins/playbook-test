# playbook-test
Ansible Playbook

[mywebsite]
IP

[mywebsite:vars]
db_user=postgres 
db_name=***
db_password=***
ruby_version=***
gemset_name=*** 
secret_key_base_name=***

[all:vars]
ansible_user = root
ansible_python_interpreter=/usr/bin/python3

