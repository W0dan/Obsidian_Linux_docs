[official thinlinc website (cendio)](https://www.cendio.com/thinlinc/how-to-get-started/)
Installation
- Server
	- `yay -S thinlinc-server`
	- just follow the steps in the wizard
	- install any missing packages
		- I had to `yay -Rns thinlinc-server` and install it again a couple of times, because of missing packages
- Client
	- `yay -S thinlinc`
## Run Thinlinc
- run the script: `./start-teamviewer.sh`
- start Teamviewer like you would start any other application

## Access your computer remotely through Thinlinc
- Boot your host computer, but don't log in
	- or log out if you are logged in
	- if you are logged in with the same user with which you try to connect remotely, you will not be able to reach the desktop
- Make sure port 22 (or whatever custom port you might use for SSH) is forwarded from your router to your host computer
- 
