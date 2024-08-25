This repository contains two Ansible roles for automating the deployment of:

LEMP Stack with Filebeat: A full LEMP stack setup (Linux, Nginx, MySQL, PHP) with Filebeat configured to forward logs to an ELK stack.
ELK Stack: An ELK stack (Elasticsearch, Logstash, Kibana) for centralized logging and monitoring.
Each role is designed to simplify the setup process and ensure consistent deployments across environments. Feel free to explore, modify, and use these roles in your projects!

Simply review and run it in a terminal on a system where Ansible is installed—let the automation unfold

ansible-playbook playbooks/lemp.yml
and 
ansible-playbook playbooks/elk.yml
