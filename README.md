## What is this

This is my base node.js development environment as a VMWare Workstation image.

## OS?

Ubuntu 13.04 was chosen because it works well with VMWare - you shouldn't have any issues dropping it straight in.

Username: developer

Password: developer

## VMWare config

I have given the image 2gb of ram and 2 CPU cores. If your computer doesn't have that much go and adjust these settings before you power the image up.

## What's on it

- OS essentials (all of the latest updates, git-core, build-essential, latest kernel, etc.)
- NodeJS (via [nave](https://raw.github.com/isaacs/nave) which is at ~/nave.sh)
- MongoDB (via apt-get ppa)
- Redis (via apt-get ppa)
- ElasticSearch
- Sublime Text 3 (with package system)
  - Sidebar Enhancements plugin
  - Jade syntax plugin
  - Coffeescript syntax plugin
  - Gitgutter plugin
  - Prefixr plugin (Adds vendor prefixes to your CSS)
  - SublimeLinter plugin
  - JS Format plugin
  - Git plugin (right click git commands)
  - DocBlockr plugin (simplifies writing jsdoc comments)
