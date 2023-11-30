# LXD.Desktop
# Guide:
- [How to launch an instantly functional Linux desktop VM with LXD](https://ubuntu.com/tutorials/how-to-launch-an-instantly-functional-linux-desktop-vm-with-lxd)

# Viewer
https://discuss.linuxcontainers.org/t/gui-in-virtual-machines-vms/9223
>To access the Graphical console of a Virtual machine, follow the instructions below:
>
>On Linux:
>Note: Package names might be different on certain distributions.
>
>Install virt-viewer (remote-viewer) or spice-gtk-client (spicy) on your client system.
>Login with: `lxc console --type=VGA`

install:
`sudo apt install virt-viewer`
