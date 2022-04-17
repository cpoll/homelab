# Setting up cloud-init on an Ubuntu Server install
Cloud-init is installed by default on Ubuntu Server 20.04

- Copy the cloud-init into the server, and work it into `/etc/cloud/cloud.cfg`
- Update <my_domain> in cloud-init

- ?? cloud-init validate command?
- `cloud-init clean`
- `cloud-init init`


# avahi
sudo insserv avahi-daemon
conf in /etc/avahi/services/multiple.services
- avahi-daemon.conf?

https://wiki.archlinux.org/title/Avahi#Using_Avahi



# TODO:
- Add datasource from network


# Useful Links
https://cloudinit.readthedocs.io/en/latest/topics/examples.html
