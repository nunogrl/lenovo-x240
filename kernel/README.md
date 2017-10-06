Kernel
======

This kernel is based on the work of Markus Demleitner and his instructions can be found at http://www.tfiu.de/x240/

Considerations
--------------

The only reason I've been making modifications on the kernel is because there 
are some components that I realize I miss for my work or for specific 
periferics.

Building
--------

To build the kernel just type

    make-kpkg --append-to-version -thinkpadx240 --revision 2 binary kernel_headers


TODO
=====

Virtual Box
-----------

Error from Virtual Box:

> Kernel driver not installed (rc=-1908)
>    
> The VirtualBox Linux kernel driver (vboxdrv) is either not loaded or there is a permission problem with /dev/vboxdrv.
> Please reinstall virtualbox-dkms package and load the kernel module by executing
>    
>     'modprobe vboxdrv'
>    
>    as root.
>    
>    where: suplibOsInit what: 3 VERR_VM_DRIVER_NOT_INSTALLED (-1908) - The support driver is not installed. On linux, open returned ENOENT. 
    
Docker
------

Information at https://docs.docker.com/engine/installation/linux/linux-postinstall/#use-a-different-storage-engine

Soundcard
---------

Fix for pulseaudio


Power Management
----------------

Fix for suspend
