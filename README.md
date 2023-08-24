# st-patched
A custom-made fork of the suckless st-terminal

# Why I made this
This fork of st-terminal has very few patches (found in the "Patches" folder) and it was made with ease of use in mind.
It was made so an average user will have no trouble using it right out of the box and for those who desire a lightweight terminal that works

# How to install/uninstall
First, clone the repo:
```bash
git clone https://github.com/Freyja335/st-patched.git
```
To install, inside the repo, execute:
```bash
sudo make clean install
```
To uninstall, inside the repo execute:
  ```bash
  sudo make clean uninstall
  ```
If you wish to apply/remove patches, inside the repo, execute:
```
# Apply a new patch
patch -p# Patches/patch_name.diff   # = any number 

# Remove an existing patch
patch -R Patches/patch_name.diff
```
Find more patches at [suckless.org](https://st.suckless.org/patches/):

Warning: DO NOT delete the repo, simply move it somewhere where is not in the way

# Keyboard Shortcuts
Action      | Key Combination
---         | ---
Copy        | `ctrl` + `shift` + `c`
Paste       | `ctrl` + `shift` + `v`
Zoom In     | `ctrl` + `shift` + `PageUp`
Zoom Out    | `ctrl` + `shift` + `PageDown`
Reset Zoom  | `ctrl` + `shift` + `Home`
Scroll Up   | `shift` + `PageUp`
Scroll Down | `shift` + `PageDown`
Scroll      | `scrollwheel`

# Config
if you wish to change the Font, look for this in the config.h or config.def.h
![2023:08:18:14:17:31](https://github.com/Freyja335/st-patched/assets/92382538/12ab458b-6408-4150-8088-de06b424dced)

if you wish to change the opacity, look for this in the aforementioned configs
![2023:08:18:14:18:53](https://github.com/Freyja335/st-patched/assets/92382538/93192a2f-b2ea-4d4e-8f22-a4ba439654fc)

if you wish to change the colorscheme, look for this in the aforementioned configs
![2023:08:18:14:20:10](https://github.com/Freyja335/st-patched/assets/92382538/a243fd68-3baf-4215-943b-e20a23f7a408)

if you wish to change anything else a quick google search should do the trick.

### Note
After every change to the config you need to recompile the terminal as the source code itself is being modified

# Credits
* This project was made possible thanks to [https://st.suckless.org/](https://st.suckless.org/)
* All patches were supplied by [https://st.suckless.org/patches/](https://st.suckless.org/patches/)

