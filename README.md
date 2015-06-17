# ansible-jekyll-setup

Use Ansible to provision an Ubuntu trusty (14.04) instance to run Jekyll.

-You can easily test this by just starting up a basic Ubuntu machine on VirtualBox or by using Vagrant

## Steps

1. On your server clone this repo

2. Navigate to the script directory and run the ansible shell script ('source ansible.sh'). This will install ansible.

3. Navigate to the ansible directory and run the main-step1 playbook ('ansible-playbook main-step1.yml')


### other notes
http://stackoverflow.com/questions/13246429/i-am-getting-rvm-command-not-found-after-installation-of-rvm

rvm tips: https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-on-ubuntu-14-04-using-rvm

tips on Linux file permissions: http://linuxcommand.org/lts0070.php

how to deploy jekyll blogs with git: https://www.digitalocean.com/community/tutorials/how-to-deploy-jekyll-blogs-with-git
