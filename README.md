# Checking connection to hosts

`ansible -i inventory.yaml all -m ping -u nkosl`


# Run playbook
`ansible-playbook deploy_dev.yaml -i inventory.ini --ask-become-pass`