# Install LAMP with Ansible


## Prerequisite

1. You'll need one Ubuntu 18.04 server to serve as node / host.
1. You'll need one Ubuntu 18.04 server to serve as worker
2. Install Ansible
3. generate ssh keys and place your pub key on the Ansible worker ~/.ssh/auth 



## Steps to run Ansible set up

1. Clone this repository
2. Set up your inventory file - you can use `inventory-example` as base
3. Adjust values on your `group_vars/all.yml` file
4. Run the `svr-setup.yml` playbook to set up the LEMP server
5. Run the `laravel-deploy.yml` playbook to deploy the demo Laravel application
6. Access your server's IP address or hostname to test the setup