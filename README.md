odroid-utility
=====================

Fork of MDRJR's script, created to add support for additional boards + update deprecated functionality

**Original Source:** https://github.com/mdrjr/odroid-utility

**How to Install :**

```
sudo -s

wget -O /usr/local/bin/odroid-utility.sh https://raw.githubusercontent.com/eribbey/odroid-utility/master/odroid-utility.sh

chmod +x /usr/local/bin/odroid-utility.sh

odroid-utility.sh
```

The script references several companion pieces

**Added Functionality :**

* Supports the following new(ish) boards: ODROID-N2
* Streamlines startup process

**Original Functionality :**

* Debian and Ubuntu.
* Xorg on/off,
* Change hostname,
* Configure HDMI (x/x2/u2/u3/c1) only,
* Kernel Update (all boards),
* boot.scr's update (all boards) Oh yes. Updating the kernel doesn't replace your boot.scr's anymore. If you were using custom ones to boot from hdd then they should be safe now,
* Rebuilds Xorg DDX , installs new Mali drivers when they are available and fixes ABI errors,
* Filesystem resize.

**TODO :**

Ideas and patches are welcome. Either post a diff with your e-mail and name or submit a PR on github.
