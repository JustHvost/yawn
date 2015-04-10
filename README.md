yawn 0.1
===

yawn is a simple bash program that checks for updates on your apt-based distro.
Tested on Trisquel GNU/Linux.
yawn is under the GPL2 License.

Dependencies required:

libnotify-bin

How to install (The easy way):

```

$ sudo dpkg -i yawn_0.1-1_all.deb 
$ sudo apt-get -f install 

```
And add "yawn" to your startup programs list.

On Trisquel: System Settings -> Startup Programs -> Add 


How to install (The "I don't trust your package" way):

```
$ sudo apt-get install libnotify-bin #run this command only if you don't have libnotify-bin installed on your system
$ chmod +x yawn
$ sudo mv yawn /usr/bin
$ echo "I DON'T TRUST YOUR PACKAGE!!! HURR DURR!!!"

```

And add "yawn" to your startup programs.

On Trisquel: System Settings -> Startup Programs -> Add 