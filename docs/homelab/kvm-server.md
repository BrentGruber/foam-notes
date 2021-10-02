https://linuxize.com/post/how-to-install-kvm-on-ubuntu-20-04/

1. ```sudo apt update```
2. ```sudo apt install cpu-checker```
3. ```kvm-ok```
4. ```sudo apt install qemu-kvm libvirt-daemon-system libvirt-clients bridge-utils virtinst virt-manager```
5. ```sudo systemctl is-active libvirtd```
6. ```sudo usermod -aG libvirt $USER```
7. ```sudo usermod -aG kvm $USER```
8. copy public key from mist to ~/.ssh/authorized_keys