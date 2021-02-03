## S-Series Drive :: Shell Script

#### A script to manage floppy disks in Akai S-series format

You will need fdutils in order for this script to work. Also because of that this script only works on classic floppy drives(/dev/fdX). No usb!

Prepare drive sets the drive to use 10 sectors per track.
Formating the drive will use superformat to format the disk in the same manner.

Importing and writing just uses cat to get or write the disk.

NOTE: ALways prepare the drive after you insert the floppy. The drive has to be prepared once before performing the other actions and you must prepare the drive each time you switch disks.

Now go make some bangers and backup your disks to your favorite linux distro (or unixlike OS).

Possibly will updates with other functions.
