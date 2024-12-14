# XFCE-Additions
### Some XFCE Plugins & Additions for Entropy Linux

---

# Menus
> ### XFCE Application Menus
> `/etc/xdg/menus/` \
![image](https://github.com/user-attachments/assets/a7f58f09-65fa-4821-81e5-183313d4131a)

> Example .menu file structure
```bash
<!DOCTYPE Menu PUBLIC "-//freedesktop//DTD Menu 1.0//EN"
 "http://www.freedesktop.org/standards/menu-spec/1.0/menu.dtd">
 <!-- EXAMPLE LAYOUT -->

<Menu>
  <Name>Menu Name</Name>
  <DefaultAppDirs/>
  <DefaultDirectoryDirs/>
  <!-- Example layout -->

  <Menu>
    <Name>Category Name</Name>
    <Include>
      <Filename>Launcher-Name.desktop</Filename>
    </Include>
  </Menu>
</Menu>
```
---

# Applications
> ### Launcher .desktop files
> `/usr/share/applications/` \
![image](https://github.com/user-attachments/assets/1d824bae-1cc0-4b45-b9a2-fed6ab8977d9)

> Example .desktop file structure
```bash
[Desktop Entry]
Version=1.0
Type=Application
Name=Postinstall Manager
Comment=Simple post installation scripts in GUI manager.
Exec=./postinstall
Icon=dots
Path=/bin/postinstall.d
Terminal=false
StartupNotify=false
GenericName=Post Install Manager
Categories=System;Utility;Szmelc;
```
