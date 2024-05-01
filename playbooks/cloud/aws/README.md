ansible-vault encrypt .env

ansible-playbook -e @.env fetch_hosts.yaml --ask-vault-pass

ansible-vault decrypt .env
