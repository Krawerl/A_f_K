
Ansible script to install/update Klipper-Moonraker-Mainsail on multiple pi's

Compatible with [kiauh](https://github.com/th33xitus/kiauh)

TODO

~Doc

~Klipper config/make/flash

~mjpg-streamer support

~multiinstance support

Quick Start

Install ansible (ex.: sudo apt-get install ansible), Download the script
create your inventory (hosts) file https://docs.ansible.com/ansible/latest/network/getting_started/first_inventory.html
you have to set "ansible_user" in the hosts file for every host (user must be allowed to become root(sudo))
install ssh-key auth or (not recommended) set ansible_ssh_password in the hosts file
execute the script: ansible-playbook -i hosts main.yml
