# Ubuntu autoinstall/cloud-init with PXE

This repository is meant to accompany YouTube video explaining everything:
https://youtu.be/96WB0c7UuGE

## Caution
When using server ISO with additinal installation of ubuntu-desktop both systemd-networkd and network-manager are enabled and can cause extended startup time. It's best to `systemctl disable systemd-networkd` after the system is installed
