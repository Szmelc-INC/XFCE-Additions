# XFCE `Application Menus` .menu files
> Dir `/etc/xdg/menus/`

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
