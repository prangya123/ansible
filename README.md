# ansible

# to run the playbook
#ansible-playbook <playbook-name.yml>

ansible-playbook demo.yml

ansible-playbook demo.yml --syntax-check

#to dry run:
ansible-playbook demo.yml --check

#verbose or in-detail verbose v or vvvvv
ansible-playbook demo.yml -v or ansible-playbook demo.yml -vvvvv

#to change verbose color, change in ansible.cfg

#debug module can print message
