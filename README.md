Tool to detect DVD/BluRays and keep the latter mounted.
=======================================================

Kodi has the weird "feature" that you need to have DVDs unmounted and BluRays
mounted to watch them.

This is a script to check on inserting a disc, if this is a BluRay or a DVD and
unmount DVDs.

Your `/etc/fstab` should look like this:

    /dev/sr0 /media/cdrom0 auto ro,noauto 0 0

