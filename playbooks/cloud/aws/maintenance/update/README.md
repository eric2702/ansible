ansible -i ../hosts.ini ubuntu -m ping --user <username> --private-key /path/to/private_key.pem

ansible-playbook -i ../hosts.ini playbook.yaml --user <username> --private-key /path/to/private_key.pem --ask-become-pass
