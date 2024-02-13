# Ansible course: How to deploy a webapp with ansible

ssh-keygen -t rsa
ssh-copy-id 

Pour utiliser le rôle wordpress:
```ansible-galaxy install -r roles/requirements.yml```

Pour lancer le rôle wordpress:
```ansible-playbook -i host.yml --ask-vault-pass wordpress.yml```
