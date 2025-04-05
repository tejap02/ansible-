ansible-vault create aws_credentials.yml 123 123 ansible-vault decrypt aws_credentials.yml

nano vault_pass.txt

ansible-playbook your_playbook.yml --vault-password-file vault_pass.txt
