# Dev3 - Default VHost Files

This repository contains all the default VHost files that the Dev3 [scripts](https://github.com/ejanus/dev3-scripts/wiki) will use to handles sites.

If you have an older copy of the Dev2 prior to Jan 6th, 2016 you need to follow these instructions: 

1. Change to your home directory:  
    `cd ~`  
2. Clone the repo:  
    `git clone https://github.com/ejanus/dev3-vhost-defaults.git`  
3. Change to your sites available directory:  
    `cd /etc/apache2/sites-available`  
4. Remove the existing drupal-default.conf vhost file:   
    `sudo rm drupal-default.conf`  
5.  Create the symlink:  
    `sudo ln -s ~/dev3-vhost-defaults/drupal-default.conf drupal-default.conf`  

Done!

***

## Dev3 Links

* [Setup & Installation](https://github.com/ejanus/dev3/wiki)
* [Site management scripts](https://github.com/ejanus/dev3-scripts)
