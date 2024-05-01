ansible-vault encrypt .env

ansible-playbook -e @.env playbook.yaml --tags create --ask-vault-pass

ansible-playbook -e @.env playbook.yaml --tags info --ask-vault-pass

ansible-vault decrypt .env
