# Ansible


If there is no ssh key: Add -k option
If you need a password for root authority: Add -bK option

Variables are included in "{{ foo }}".

If you don't have ssh key and need root authority?
following this command,
ansible-playbook playbook.yml -e foo=foo -e bar=bar -bkK