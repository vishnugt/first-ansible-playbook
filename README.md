#Ansible playbook

Execute by running - `ansible-playbook main.yml`




File | Purpose 
--- | --- 
main.yml | Starting point of the script, that contains the list of tasks to be run
hosts | Where all the servers/IPs are declared
vars.yml | Variables file
setup.sh | In WSL the ansible.cfg is not recognized, so a hacky way to fix that
tasks/ | Tasks definitions like apt upgrade, install docker, add ssh key
tasks/containers | Docker containers information that needs to be created