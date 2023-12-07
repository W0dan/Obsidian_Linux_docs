For dotnet, you have to install several runtimes and sdks. I currently use .NET 6.0, .NET 7.0 and .NET 8.0 . I have the impression that only the LTS release and the current non-LTS release of dotnet are kept available. Older versions seem to dissapear. These versions below where available at the time of writing this documentation.
#### update 07-12-2023
I seem to be having problems with the dotnet versions available from the [[Arch User Repository (AUR)]].  A better way seems to be using the `dotnet-install.sh` script.

## Installation
- ~~`yay -S dotnet-runtime-6.0 aspnet-runtime-6.0 dotnet-sdk-6.0`~~
- ~~`yay -S dotnet-runtime-7.0 aspnet-runtime-7.0 dotnet-sdk-7.0`~~
- download the latest `dotnet-install.sh` script
	- see [this microsoft page](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-install-script)
	- follow the instructions on that page
-  tldr;
	- check the integrity of the script
	- make the script executable
	- execute the script as follows:
		- `./dotnet-install.sh --channel 6.0`
		- `./dotnet-install.sh --channel 7.0`
		- `./dotnet-install.sh --channel 8.0`
		- ...

see [here](https://wiki.archlinux.org/title/.NET) for more information.

~~As described in the link above, it is also possible to install very specific versions of dotnet using the `dotnet-install.sh` script, but I would not recommend it unless absolutely necessary, because uninstallation and updates must then be done manually.~~