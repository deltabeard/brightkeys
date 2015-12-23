# brightkeys
Two bash scripts that I use to turn my brightness up &amp; down in Linux.
On some laptops, the brightness keys don't work. These two scripts are a work-around for that.

To use, copy the scripts in to /usr/bin/ then bind them to your brightness keys using xbindkeys. The scripts require root, so run them as ``sudo bup'' in your xbindkeysrc.
To stop asking for a password when running the script as sudo, set an exception for the scripts only using visudo.
