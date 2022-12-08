# wordpress-deployment
if you want to install wordpress with ansible then I can show You how to do it

first clone this repo and save wordpress.yml file in Your ansible directory

after You have to run these commands

ansible-galaxy install git+https://github.com/nexo8937/ansible-role-mysql-php-packgages.git
 
ansible-galaxy install git+https://github.com/nexo8937/ansible-role-apache.git

ansible-galaxy install git+https://github.com/nexo8937/ansible-role-wordpress.git


after that You can run playbook

ansible-playbook wordpress.yml

thank You

