For dotnet, you have to install several runtimes and sdks. I currently use .NET 6.0 and .NET 7.0 . I have the impression that only the LTS release and the current non-LTS release of dotnet are kept available. Older versions seem to dissapear. These versions below where available at the time of writing this documentation.

## Installation
- `yay -S dotnet-runtime-6.0 aspnet-runtime-6.0 dotnet-sdk-6.0`
- `yay -S dotnet-runtime-7.0 aspnet-runtime-7.0 dotnet-sdk-7.0`

see [here](https://wiki.archlinux.org/title/.NET) for more information.

As described in the link above, it is also possible to install very specific versions of dotnet using the `dotnet-install.sh` script, but I would not recommend it unless absolutely necessary, because uninstallation and updates must then be done manually.