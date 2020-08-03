
# A minimal feature set workaround to initialize FreeBSD images in openstack.

Please find the workaround script for OPNsense in branch **opnsense-cloudinit**.

## Usage:
* Copy `bsd-cloudinit` into the target image folder `/root/`
* In target image execute: 
	* `echo /root/bsd-cloudinit >> /etc/rc.local` 
	* `chmod u+x /root/bsd-cloudinit`

