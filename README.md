1. Install pip3:
sudo apt install python3-pip

2. Install ansible:
pip3 install ansible

3. PATH:
export PATH=$PATH:/home/user/.local/bin

4. Add user in /etc/sudoers:
ansible ALL=(ALL:ALL) NOPASSWD:ALL

5. Run (vault-pass = 123):
 ansible-playbook playbook.yml -i inventory --ask-vault-pass
"# Ansible" 
"# Ansible" 
