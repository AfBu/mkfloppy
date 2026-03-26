# mkfloppy

Simple Bash script to create 1.44MB DOS floppy images.

Usage:
- mkfloppy create <imagefile> # creates new empty image
- mkfloppy build <imagefile> <directory> # creates new image and copy all files from given directory
- mkfloppy mount <imagefile> <mountpoint> # mount image
- mkfloppy unmout <mountpoint> # unmount image
