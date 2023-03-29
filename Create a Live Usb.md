### Create a Live Usb (not needed for installation in VM)
- Write the ISO to a usb-drive:
	- :warning: the contents of the usb-drive will be deleted
	- Windows:
		- Download [Rufus](https://rufus.ie/en/) (or use another tool for creating a bootable usb-drive that you are more familiar with)
		- Follow the instructions [here](https://www.howtogeek.com/1261/create-a-bootable-ubuntu-usb-flash-drive-the-easy-way/)
	- Linux
		- Determine what the usb device is called by typing `lsblk` in a terminal. This should be something like `/dev/sdc`. (on my system this is usually `/dev/sda` because I have only nvme internal drives).
		- :warning: Make sure that it is NOT `/dev/sdc1` or something else with a number at the end.  The ones with numbers are partitions, the one without a number is the drive itself.
		- Type this command in the terminal (from withing the directory where you downloaded the ISO):
			- `sudo cp [the filename of the ISO] [the name of the usb device]`
			- Example: `sudo cp EndeavourOS.iso /dev/sdc`

