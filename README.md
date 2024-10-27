# st-patched
### This is a custom version of the famous (for it's simplicity and speed) "suckless terminal" made for daily use by anybody. A select number of patches have been applied that improve the use and comfort of this program, form basic scrolling to displaying pixel art and transparency, this fork has everything the user might need. (pre-applied patches can be found in the "patches-default" folder).

## Installation
- Clone the repo
- edit the config.def.h to your liking
- To install run this inside the repo
  ```
  sudo make clean install
  ```
## Uninstall
- Navigate to where you cloned the repo
- Exexute this inside the repo
  ```
   sudo make clean uninstall
  ```
- Delete the repo

## Installing patches
- Navigate to where you cloned the repo
- Download and extract your patches inside the "patches" folder
- Execute this inside the repo
 ```
patch -p# -i patch-name-goes-here (# a number to identify a patch eg: 1 for the first patch applied etc)
 ```
