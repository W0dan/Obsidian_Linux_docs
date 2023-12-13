# `/etc/fstab`

The file `/etc/fstab` is used to permanently mount local drives, but also remote shares. 

For local drives, an entry might look like this:
`UUID=af676f25-3247-4a52-8482-94f75675cce0 / ext4 defaults,noatime 0 1`

For network shares, an entry looks like this:
`//192.168.1.132/fotos /home/wodan/archserver/fotos cifs _netdev,x-systemd.automount,nofail,credentials=/home/wodan/.fileshare-passwords 0 0`

As you can see, no credentials are stored in the `/etc/fstab` file. Instead it refers to the file `/home/wodan/.fileshare-passwords`. This file has the `chmod` mask `600`, so only the owner of the file can read or modify it. The content of the passwords-file is as follows:
`username=******`
`password=******`

