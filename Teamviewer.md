## Installation
- `yay -S teamviewer`
- In order to run teamviewer, you need to run
	- `sudo teamviewer --daemon start`
- I don't need it to run all the time, so I created a script as follows:
	- Make sure you are in your home directory (or wherever you want to create this script)
	- `nano start-teamviewer.sh`
		- the `nano` editor starts
		- enter `sudo teamviewer --daemon start`
		- press `ctrl+x`
		- press `y` to save
		- press `enter` to confirm the filename
	- `chmod 700 start-teamviewer.sh` 
		- this makes it executable

## Run Teamviewer
- run the script: `./start-teamviewer.sh`
- start Teamviewer like you would start any other application

## Access your computer remotely through Teamviewer
- start Teamviewer
- choose `Extras|Options` in the menu
- Security -tab
	- Set a personal password
		- this password will be asked anytime you want to access this computer
	- Disable Random password
	- Configure the Block and allowlist, so only PartnerIds that you trust can access your computer
	- Configure Two-factor authentication
		- You need to install the Teamviewer app on your phone
		- Follow the constructions from the application
