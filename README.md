# qedu-hub-ansible

Execute the role with ansible 

>> ansible-playbook -i hosts -u user --private-key arquivo.yml --diff

example hosts:


[php]
 127.0.0.1


example playbook.yml:

- hosts: php 
  become: True  
  roles:    
    - nome-da-role
