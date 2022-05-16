# local-ansible
Install all the stuff I need on localhost

## running this
First install [homebrew](https://brew.sh/)  
Then install [pyenv](https://github.com/pyenv/pyenv#installation)  
Then install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)  
Then install the ansible collection...
```bash
ansible-galaxy collection install geerlingguy.mac
```
Next, run the playbook...
```bash
ansible-playbook local-playbook.yml
```