# vdo-install-ck
install vdo and its modules on a CentOS7/ RHEL7 server running a custom kernel

If you run a custom kernel, such as kernel-ml, then the pre-packaged vdo kmdo-kvdo kernel module won't work.

To get around it, build from source, the vdo stuff against your current kernel and it will work.

This uses Ansible for familiarity/ modularity and because system changes with Ansible make sense.
Tested with Ansible 2.6.
NOTE: This playbook is NOT entirely idempotent, so consider it to be more of a pave-over approach. It is generally not harmful.

