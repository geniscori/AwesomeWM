# **AwesomeWM forked and modified files:**

## [**rc.lua**](./rc.lua) modifications:
___

### Autorun programs:
---
- **compton** (transparent terminal)
- **xfce4-power-manager** (enable function hotkeys to change display brightness)
- **xfce4-volumed** (enable function hotkeys to inc/decrease volume)
- **vertex** (actually using vertex theme)
---
### Code modifications:
---
- Changed terminal, editor and gui-editor 

- Changed number of workspaces and order of layouts

- Changed brightness and volume *show help* menu hotkeys

- Changed *prompt* to *dmenu* using `dmenu` command

- Changed theme wallpaper and made *random* and *previous* wallpaper hotkeys using `nitrogen` command

- Open Visual Studio hotkey

- Shutdown hotkey that calls a bash script

- Take screenshot using `flameshot gui` command

- Added Spotify startup app initalizing in "music" workspace

- Added `Anaconda` hotkey

- Changed workspace-2 tiling method

- Deleted screen-locker hotkey

- Edited workspace layouts

- Added `Set wallpaper manually` hotkey

- Added `SPOTIFY` SKIP/PREVIOUS/STOP hotkeysz
___
___

<br/><br/>
## [**theme.lua**](./themes/vertex/theme.lua) modifications:
---
### Code modifications:
---
- Changed wallpaper path to `/usr/share/backgrounds/wallpapers-derek-taylor/wallpapers/`

- Deleted and changed vertical wibox icons

- Changed wifi applet to `nm-applet` and disabled vertex wifi icon from horitzontal wibox

- Added volume icon

- Changed vertical wibox height to 
`(22 * s.workaera.height)/100`

- Dissabled `rspace0`

- Deleted blanckspaces in sidebar

- Dissabled useless gaps from 5 to 0
