## Archlinux
EndeavourOS is a [[Linux]] distribution that is based on the Archlinux distribution. 

### Properties of Archlinux
- Rolling release
	- This kind of distributions doesn't get a major release once or twice a year, but is constantly kept up-to-date
- `pacman` as default package manager
- AUR or Arch User Repository
	- (Almost) all software that is available for Linux, but doesn't exist in the official Arch repositories (used by `pacman`), can be found in the AUR.
	- An AUR helper is needed to be able to do it
	- Arch doesn't ship with an AUR helper out-of-the-box
- Very minimal installation
	- Manual, console based, installation
	- You need to install `all` packages yourself
	- A text-based installer exists these days
- Can be hard to get your graphics-driver right

### What EndeavourOS adds
- A graphical installer that guides you through the installation
- An AUR helper is installed out-of-the-box: `yay`
	- `yay` can install packages from the AUR
	- it is also a wrapper for `pacman` so you don't need to know if a package is in the AUR or in the official repos
- A desktop environment can be chosen from within the installer
	- but you don't have to, e.g. for a server
- Graphics-drivers are taken into account from your first boot in the live-usb environment

## Sources of information
- [`EndeavourOS Wiki`](https://discovery.endeavouros.com/)
- [`Archlinux Wiki`](https://wiki.archlinux.org/) Since EndeavourOS is based on Archlinux, the Archlinux Wiki is a valuable source of information whenever you get stuck.

## Installation
Installation is explained in detail here: [[Installing EndeavourOS]]

## Things to do first
- **Obligatory:** Install [[Timeshift]]
	- so you can always go back to a working system
- **Optional:** Install [[Printer]](s) if you have any
- **Optional:** [[Mount harddrives]] if you have other drives than your OS drive
- **Optional:** [[Mount network shares]] if you have any
- **Optional:** [[Change your desktop background]]
- [[Flameshot]] for screenshots

## Security
- **Optional:** Install an [[Antivirus]]

## System maintenance
- Update your packages:
	- Type following in a console: `yay -Syu`
	- I do this daily

## Software
Almost all software that is available for Linux, exists for Archlinux, either through `pacman` or the `AUR`. Since EndeavourOS descends from Archlinux, these packages are also available for EndeavourOS. Click on the following link to find out what software I use on my system, and how to install it:
[[Software installation]]




