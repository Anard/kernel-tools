# kernel-tools
Tools for compiling and updating Gentoo's kernel

## update-grub
Simply replace common `grub-mkconfig -o /boot/grub/grub.cfg` command to update Grub bootloader. Or give a different file in parameter.

## build-kernel
Tool to build an updated kernel from current or choosen kernel configuration
Use `build-kernel --help` or `man build-kernel` for more information

# Installation instructions
The preferred way to install these Gentoo's kernel-tools is to add [overlay](https://github.com/Anard/anard-overlay) and `# emerge -a kernel-tools`

It's also possible to clone this repository and copy scripts in /usr/sbin and config files in /etc/conf.d, but need to manually check dependencies and configuration.
