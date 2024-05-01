ansible-vault encrypt .env

ansible-playbook -i ../hosts.ini -e @.env playbook.yaml --user <username> --private-key /path/to/private_key.pem --ask-become-pass

ansible-vault decrypt .env
