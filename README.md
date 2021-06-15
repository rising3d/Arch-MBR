# Arch-MBR


<h2>Installing Arch Linux on an old machine with MBR, no UEFI.</h2>
I am using the official instructions on <a src=archlinux.org>archlinux.org</a>

If you want to install alongside Windows, other instructions apply. 

<h2>Boot Arch Linux from USB</h2>
This assumes you have downloaded and created a bootable drive of Arch Linux.

<h3>Check Network Connectivity</h3>
ip a
ping archlinux.org
timedatectl set-ntp true

<h3>Check Hard Disks</h3>
> lsblk (or) > fdisk -l
> fdisk /dev/sdx =>Where x is the letter of the hard drive you are installing Linux
> 
