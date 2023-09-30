Installation for Brother MFC-J6920DW

AUR
https://aur.archlinux.org/packages/brother-mfc-j6920dw

Installation
- `yay -S brother-mfc-j6920dw lib32-glibc`
- If you are installing the printer as network printer
	- navigate to the printer settings
	- remove the printer that was installed with the driver
	- add a new printer as follows:
		- click 'Add Printer'
		- select the 'Internet Printing Protocol (ipp)'
		- enter the address like this: `ipp://192.168.1.49/ipp` 
			- this will probably be another address
		- after clicking next, select the correct printer driver from the list

It is important for this specific printer, to install the driver through `yay` first, because the drivers are not shipped with [[endeavouros]].