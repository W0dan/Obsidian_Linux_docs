If you have an ssh-key that you use for e.g. git and you created it with a passphrase, it can become really cumbersome if you need to enter the passphrase *every* time. 
You can make your shell ask for the passphrase *just once* by adding following two lines to you .zshrc:
* ``eval `ssh-agent -s` `` ``
* `ssh-add ~/.ssh/*_rsa`

The 2nd line can differ based on your ssh-key(s)