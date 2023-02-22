# Ansible palybook for Pi-Hole

It installs and manages multiple Pi-Hole instances
providing config for your lan/lab zones and hosts

Perfect to run on Proxmox LXC (256Mb RAM, 2Gb disk)

1. `git clone https://github.com/buldezir/ansible-pihole.git && cd ./ansible-pihole`
2. `cp hosts.yml.example hosts.yml` and configure hosts.yml for yourself
3. `ansible-playbook pihole.yml`