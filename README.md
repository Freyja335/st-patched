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
## Configuration
To configure st you need to either edit "config.def.h" and delete "config.h" or by sudo editing "config.h", after you are done recompile using the "Installation" command. (below are some common options)

- To change font, edit this: ![Screenshot from 2024-10-28 16-33-20](https://github.com/user-attachments/assets/0a10229e-824c-4b1c-bc67-8b5dd9ac047f)

- To change the opacity, look for this: ![Screenshot from 2024-10-28 16-34-38](https://github.com/user-attachments/assets/016a3542-adf5-4ee3-acd9-40927333bd43)

- To change colorscheme, edit this: ![Screenshot from 2024-10-28 16-35-14](https://github.com/user-attachments/assets/94bc86d2-92c0-40f4-a96f-92a1dc0891a2)
