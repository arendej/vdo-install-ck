# vdo-install-ck
This is to install vdo and its module on a CentOS7/ RHEL7 server running a **_custom kernel_**

If you run a custom kernel, such as kernel-ml, then the pre-packaged vdo kmdo-kvdo kernel module won't work.

To get around it, build vdo against your current kernel and it will work.

Tested with Ansible 2.8
