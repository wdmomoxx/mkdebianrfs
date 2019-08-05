mkdebianrfs
===========

script that uses qemu and debbootstrap to make a core debian rootfs

Go to http://www.elinux.org/How_to_make_a_debian_rootfs_for_MIPS_CI20 for instructions


wget https://raw.githubusercontent.com/wdmomoxx/mkdebianrfs/master/mkdebianrfs.sh

sudo ./mkdebianrfs.sh --tar mipsel jessie debian-jessie-mipsel-rootfs.tar.bz2

sudo ./mkdebianrfs.sh --tar mipsel stretch debian-stretch-mipsel-rootfs.tar.bz2
