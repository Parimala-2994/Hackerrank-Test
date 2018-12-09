# Hackerrank-Test
Jade Hacker rank Test
Software management configuration using ansible

System: Linux Server 

Softwares:

    Apache
    Mysql
    Tomcat

Required: Ansible
Setup ansible: yum install ansible

Configure mysql and setup a test db

ansible-playbook -i hosts mysql.yml

Configure apache

ansible-playbook -i hosts apache.yml

Configure tomcat

ansible-playbook -i hosts tomcat.yml

Single Step Configuration

ansible-playbook -c local -i hosts site.yml
