## What is this

This is my base node.js development environment as a VMWare Workstation image.

## OS?

Ubuntu 13.04 was chosen because it works well with VMWare - you shouldn't have any issues dropping it straight in.

Username: developer

Password: developer

## VMWare config

The image is given 2GB of ram and 2 CPU cores. If your computer doesn't have that much go and adjust these settings before you power the image up.

## What's on it

- OS essentials (all of the latest updates, git-core, build-essential, openjdk, latest kernel, etc.)
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
