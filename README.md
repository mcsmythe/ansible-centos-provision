Compiled Ansible roles for provisioning a Centos 7 server with key roles that I use to set up a base Centos 7 server.

- Install FirewallD and configure SSH
- Install and Configure Fail2Ban
- Install Base server packages.
- Installs Docker & Docker-Compose
- Creates a User (feel free to include a group_vars/all file with variables for user).


All Credit for these roles can be attributed to the following sources.

- Provision Role: https://github.com/bngsudheer/ansible-role-centos_base
- Docker Role: https://github.com/iMartzen/ansible-role-centos-docker-compose-setup
- Users Role: https://github.com/singleplatform-eng/ansible-users
