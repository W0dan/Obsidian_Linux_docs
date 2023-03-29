**Installing [[EndeavourOS]] with KDE Plasma from scratch (:warning: no dual boot)**

## Who this manual is for
- Future me, if I screw up again
- Anyone who wants to get started with Linux with a capable desktop environment, **without** too much clutter and **without** dual booting into Windows.
- :warning: If you follow these instructions, you need an entire drive dedicated to Linux. Everything that is on that drive, will be erased. 
- :warning: Now is a good time to create a backup, because everything will be gone.

## Getting started
- Download the [ISO](https://endeavouros.com/)
- Check the SHA512 of the ISO
- If you are installing to a real machine (not a VM), you need to [[Create a Live Usb]].

## Installation
- For a **real machine** (not a VM):
	- Make sure that your BIOS is configured to boot from USB. Consult your motherboard manual when in doubt howto.
	- Reboot your computer with the usb-drive inserted
- For a **VM**:
	- Create a new VM in [Virtual Box](https://www.virtualbox.org/) or [VmWare](https://www.vmware.com/be.html) or whatever takes your fancy
	- Attach the ISO so you can boot from it
	- Start the VM
- Select the option from the boot-menu that matches your system
	- for Intel and AMD graphics cards: EndeavourOS default
	- for NVidia graphics cards: EndeavourOS NVIDIA
- Click on the `start the installer` on the welcome screen.
- In the dialog that comes next, choose `online`.
- Follow the instructions on the `Welcome`, `Location` and `Keyboard` tabs
- In the `Desktop` tab, select `Plasma KDE`
- In the `Packages` tab, make sure that following packages are selected:
	- Desktop base
	- Microcode
	- Firefox
	- KDE-Desktop
	- if you have a **printer**, and CUPS is listed, select it also
	- **Don't** select any other desktop environment
	- **Don't** select any other Kernel
- In the `Bootloader` tab, make sure **only** `systemd-boot` is selected. (I had some bad experiences with GRUB in the past, and `systemd-boot` has become the default recently)
	- [More on `GRUB` vs `systemd-boot` (aka `gummiboot`)](https://www.maketecheasier.com/grub-vs-systemd-boot/)
- In the `Partitions` tab, select `Erase disk`. 
	- :warning: at this point, it is wise to reflect on your decision, because soon there is no way back.
- In the next set of screens, add your user account details. And followed by a summary of the changes. And finally, hit “Install Now” to start the installation.

## The Welcome screen
- **Obligatory**: Work through the first 5 buttons of the welcome-screen:
	- Update Mirrors (Arch)
	- Update Mirrors (EndeavourOS)
	- Update System (yay)
	- Package cleanup configuration
	- Configure eos-update-notifier
- **Optional**: Explore the rest of the welcome-screen
- Personally, I click the `Don't show me anymore` button after the obligatory tasks.

