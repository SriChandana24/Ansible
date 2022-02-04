# Ansible

# TO install
yum install python3-pip -y
pip3 install pip --upgrade
pip3 install ansible

# To execute
ansible-playbook -i <inventoryfile location> -u <username> -k <filename>.yml

ansible-playbook -i <inventoryfile location> -e ansible_user=<username> -e ansible_password=<password> <filename>.yml

inventoryfile location here is /home/centos/inv