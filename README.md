RUN playbook ec2
================

ansible-playbook dbservers.yml -i production --private-key=~/.ssh/ssh_key.pem
