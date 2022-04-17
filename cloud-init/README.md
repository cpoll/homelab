# Setting up cloud-init on an Ubuntu Server install
Cloud-init is installed by default on Ubuntu Server 20.04

- Copy the cloud-init into the server, and work it into `/etc/cloud/cloud.cfg`
- Update <my_domain> in cloud-init
    Avahi will use this

- cloud-init clean && cloud-init init

Make sure the box can get to the internet, then run
- reboot

# TODO:
- Add datasource from network

# Useful Links
https://cloudinit.readthedocs.io/en/latest/topics/examples.html
