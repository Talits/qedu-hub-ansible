# qedu-hub-ansible

This is a project with php7 and/or nginx 


Create a folder and clone the project, the structure will be :
```
folder created
---file hosts
---file yml
---------folder role
    
```
Created file hosts and yml with your rules, according the examples
 

Execute the role with ansible 

`ansible-playbook -i hosts -u ubuntu --private-key ~/.ssh/key.pem playbook.yml --diff`







