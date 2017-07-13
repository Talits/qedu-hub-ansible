# qedu-hub-ansible

This is a project with php7 and/or nginx 

Execute the role with ansible 

`ansible-playbook -i hosts -u user --private-key arquivo.yml --diff`

Configure the file hosts and the file yml 

## hosts

> [php]

>  127.0.0.1


## .yml
 
- hosts: zabbix  
  become: True  
  roles:    
   - nome-da-role


