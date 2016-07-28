# igr
Used to install the latest version of GNU Radio as part of a lab install in Ubuntu LTS.
It is **untested for other distros**.

Usage:
 `dash igr`
 
Or:
 `sh igr`
  
Or:
 `bash igr`

This script bootstraps the `build-gnuradio` script provided [here](http://gnuradio.org/redmine/projects/gnuradio/wiki/InstallingGRFromSource).
It ensures that the correct python environment variables are included in the users `.bashrc` file.
It also adds devices entries to a modprobe.d blacklist so that the os does not capture the devices. See [here](http://reactivemusic.net?p=10462).

