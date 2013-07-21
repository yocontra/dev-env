## What is this

This is my base development environment in a VMWare Workstation image. You can get VMWare Workstation [here](https://www.vmware.com/products/workstation/) or [here if you are poor](http://thepiratebay.sx/torrent/8234229/VMware.Workstation.v9.0.2.1031769.Incl.Keymaker-ZWT)

## OS

Ubuntu 13.04 was chosen because it has the best hardware support. You should be able to double click and run with no issues.

Username: developer

Password: developer

## VMWare config

The image is given 2GB of ram and 2 CPU cores. If your computer doesn't have that much go and adjust these settings before you power the image up.

## What's on it

- OS essentials (all of the latest updates, git-core, build-essential, openjdk, latest kernel, etc.)
- Chromium
  - Adblock Plus extension (with tracking removal and social media button removal)
  - HTTPS Everywhere extension
  - Search by Image extension
  - JSONView extension
  - Edit This Cookie extension
- Arduino IDE (so you can use [johnny-five](https://github.com/rwldrn/johnny-five) and make cool robots)
- NodeJS 0.8 (via [nave](https://github.com/isaacs/nave) which is at ~/nave.sh)
- MongoDB 2.4.5 (via apt-get ppa)
- Redis 2.6.14 (via apt-get ppa)
- ElasticSearch 0.90.2
- Sublime Text 3 Beta (with package system)
  - Sidebar Enhancements plugin
  - Jade syntax plugin
  - Coffeescript syntax plugin
  - Gitgutter plugin
  - Prefixr plugin (Adds vendor prefixes to your CSS)
  - SublimeLinter plugin
  - JS Format plugin
  - Git plugin (right click git commands)
  - DocBlockr plugin (simplifies writing jsdoc comments)
- Empty ~/Projects folder

## Contribution Guide

If you have an improvement or update please compact the disk before commiting the file. You can do this by select the disk in Virtual Machine settings and the option is under Utilities.
