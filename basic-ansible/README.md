First example of using vagrant with ansible.

Here we are creating a centos/7 box using vagrant.
This box is then provisioned with ansible provisioner to install and run ntp server.

# Usage
- Run and build the box:
    vagrant up
- Destroy the box:
    vagrant destroy -f
