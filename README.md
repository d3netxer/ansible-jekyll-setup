# ansible-jekyll-setup

Use Ansible to provision an Ubuntu Xenial (16.04) instance to run Jekyll.

-You can easily test this by just starting up a basic Ubuntu machine on VirtualBox or by using Vagrant

## Steps

1. On your server clone this repo

2. Navigate to the script directory and run the ansible shell script ('source ansible.sh'). This will install ansible.

3. Install the rvm1-ansible role by running this command: ```ansible-galaxy install rvm_io.ruby```
  - (repo used is https://github.com/rvm/rvm1-ansible, in Oct 2018 the command changed to ```ansible-galaxy install rvm.ruby```)

4. Navigate to the ansible directory and run the main-step1 playbook ('ansible-playbook main-step1.yml')


### other notes

- You may need to source rvm after running ansible, ex: ```source /usr/local/rvm/scripts/rvm```

using rvm1-ansible role from:  https://github.com/rvm/rvm1-ansible

http://stackoverflow.com/questions/13246429/i-am-getting-rvm-command-not-found-after-installation-of-rvm

rvm tips: https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-on-ubuntu-14-04-using-rvm

tips on Linux file permissions: http://linuxcommand.org/lts0070.php

how to deploy jekyll blogs with git: https://www.digitalocean.com/community/tutorials/how-to-deploy-jekyll-blogs-with-git

http://bencane.com/2013/09/16/understanding-a-little-more-about-etcprofile-and-etcbashrc/
