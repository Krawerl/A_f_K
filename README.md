Project was created to find a purpose to play with ansible.
Don't think i will continue the work on this project.

**Ansible_for_Klipper**

*Ansible script to install/update Klipper-Moonraker-Mainsail-(KIAUH) on multiple pi's*

Basic Idea: configure once and keep your klipper systems up to date with one command or a cron job

Compatible with [kiauh](https://github.com/th33xitus/kiauh)

**TODO**
- Doc
- multi instance support
	- Klipper make/flash


**Quick Start**

Install ansible (ex.: sudo apt-get install ansible), Download the script
create your inventory (hosts) file https://docs.ansible.com/ansible/latest/network/getting_started/first_inventory.html
you have to set "ansible_user" in the hosts file for every host (user must be allowed to become root(sudo))
install ssh-key auth or (not recommended) set ansible_ssh_password in the hosts file
execute the script: ansible-playbook -i hosts main.yml
