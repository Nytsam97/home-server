# WELCOME TO THE VAULT

## This is a collection of handy commands and setups that work for my setup.

### Proxmox

### NFS Share
Mounting an NFS  Share: sudo mount server-ip-address:/path/to/nfs/share /path/to/mount/ 

Fstab Entry for auto mount on boot: server-ip-address:/path/to/nfs/share /path/to/mount nfs defaults,auto,noatime,nofail,x-systemd.automount,x-systemd.mount-timeout=60_netdev 0 0