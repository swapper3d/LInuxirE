# LinuxirE
This is my personal blend of Debian (with hardware support for the ASUS UX32LN laptop that I'm currently on). It is a work in progress and it is mostly for my private use. Though, if it can help anybody I'll be very happy.

## About
This repo contains only the configuration (recepie) files for brewing the install media using [Simple-CDD](https://wiki.debian.org/Simple-CDD). 

## Usage
In the project root folder run:

```build-simple-cdd --conf profiles/UX32LN.conf --local-packages profiles/UX32LN.localpkgs```

This generates an ISO-image that may be found in the ```image``` folder. Install as normal.

