# configure-as-labmachine

Download this project into an openSUSE Leap 15.0/15.1/15.2, openSUSE Tumbleweed or SLE 15 SP1/SP2 image and run the `configure-as-labmachine.sh` script to configure that image to be basically the standard SUSE Training lab machine image.

Once the machine has been configured as a lab machine, if there are additional disk attached, the `create-and-mount-courses-disk.sh` and `create-and-mount-home-disk.sh` scripts can be used to automatically partition/format and then mount the additional disks on `/install/courses` and `/home` in the case that the additional disk space is needed for the lab environments to be installed and run (i.e. as in Azure).
