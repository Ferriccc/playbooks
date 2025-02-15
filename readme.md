# Commands to install dotfiles:

- WSL 
```
curl -sL -o vault.yml https://raw.githubusercontent.com/Ferriccc/playbooks/main/vault.yml && \
curl -sL -o wsl_playbook.yml https://raw.githubusercontent.com/Ferriccc/playbooks/main/wsl_playbook.yml && \
ansible-playbook -K wsl_playbook.yml --ask-vault-pass
```




