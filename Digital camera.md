**Disclaimer:** I use a canon digital camera (actually 3, a 200D, a 550D and an R6 Mk II), the software below works with those cameras. I cannot guarantee compatibility with anything else.

## Needed software for digital camera support
- `gphoto2`
	- `yay -S gphoto2 gvfs-gphoto2`
- ~~Thunar filemanager~~
	- ~~The default filemanager of KDE Plasma doesn't support gphoto2, so you need to install an alternative~~
	- ~~Other possibilities are: `Nemo`, `PCManFM`, ...~~
	- ~~`yay -S thunar`~~
- Dolphin
	- *The old setup I used for my 200D and my 550D worked perfectly with Thunar, but my new R6 Mk II didn't*
	- *Thunar also has the annoying habit of freezing the system while copying/moving files*
	- I think you still need gphoto2 for this to work (did not test without)
	- Dolphin comes preinstalled with KDE
	- If you need to install it manually, type `yay -S dolphin`
	- In the location-bar, type `camera:` in order to view the files on your camera
	- You have but read-only access to your camera, so you cannot accidentally delete files
- Darktable
	- Needed for processing RAW files
	- `yay -S darktable`
