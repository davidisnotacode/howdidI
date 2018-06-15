# How Did I?
Remember when we... how did we do that? This repo is dedicated to helping me remember how I did things that I might have to do again.

## The List
#### Setup dual-boot on a Dell XPS 13 (9370) with Fedora 28 and Windows 10
 - It is a really good idea to have a local admin account on the system before starting this
 - Also, before starting, update the BIOS to the latest version (there are known issues before 1.3.2)
 - [Dell Instructions](http://www.dell.com/support/article/nz/en/nzdhs1/sln301754/how-to-install-ubuntu-and-windows-8-or-10-as-a-dual-boot-on-your-dell-pc)
   * After shrinking the partition, disable local encryption for the Windows disk
 - Then switch from RAID to AHCI in the BIOS - [Here](https://askubuntu.com/questions/696413/ubuntu-installer-cant-find-any-disk-on-dell-xps-13-9350) or [Here](https://gist.github.com/chenxiaolong/4beec93c464639a19ad82eeccc828c63)
