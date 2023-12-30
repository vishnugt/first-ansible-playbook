#Ansible playbook

Execute by running - `ansible-playbook main.yml`




File | Purpose 
--- | --- 
tasks/ | Tasks definitions like apt upgrade, install docker, add ssh key
tasks/containers | Docker containers that needs to be created
ansible.cfg | Ansible configuraion
hosts | Where all the servers/IPs are declared
main.yml | Starting point of the script, that contains the list of tasks to be run
setup.sh | In WSL the ansible.cfg is not recognized, so a hacky way to fix that
vars.yml | Variables file