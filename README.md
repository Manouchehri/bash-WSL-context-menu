Adds a "Bash" context menu option in Windows Explorer.

If you installed WSL from the Microsoft Store use these files:

- Ubuntu [Ubuntu-bash.reg](https://github.com/Manouchehri/bash-WSL-context-menu/blob/master/Ubuntu-bash.reg)
- openSUSE Leap 42 [openSUSE-42 bash.reg](https://github.com/Manouchehri/bash-WSL-context-menu/blob/master/openSUSE-42%20bash.reg)
- SUSE Linux Enterprise Server 12 [SLES-bash.reg](https://github.com/Manouchehri/bash-WSL-context-menu/blob/master/SLES-bash.reg)


If you were using the Ubuntu-Beta of WSL (no download from Microsoft Store) you might need this one:
- Ubuntu Beta [bash.reg](https://github.com/Manouchehri/bash-WSL-context-menu/releases/download/v1/bash.reg)

To install:
1. Open Registry Editor (Win+R, then type "regedit")
2. Open "HKEY_CLASSES_ROOT\Directory\Background\shell\WSL"
3. Then, RMB -> Permissions... -> Advanced -> Owner: ... Change -> Advanced -> Find Now. 
4. Find your user, than click OK
5. Change permission "Full Access" for Administrators group.
6. Then, do it for "HKEY_CLASSES_ROOT\Directory\Background\shell\WSL\command"
7. Download the reg-File for your distro from above. Accept the warnings and import it.



![Bash Context Menu](https://cloud.githubusercontent.com/assets/7232674/16479608/6d7de27e-3e6f-11e6-8d01-0e07f8ff8a5d.png)
