Ansible Playbook to check services
=======

Example playbook to check if nginx and nolio services are running and make sure one of the path exists 

ansible-playbook -i hosts site.yml -v --ask-sudo-pass