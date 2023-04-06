# livezilla-deluxe
Note: this project is far from finished.



Live rescue toolkit based on Debian GNU/Linux, now with more bloat.

I have created a live rescue toolkit, containing useful programs such as Clonezilla, GParted, Firefox, etc. and even some games to play while you wait for a lengthy operation to complete. This is a special version of that system, with more packages included, as well as the XFCE desktop environment instead of LXDE.
This software toolkit is considered bloated (intentionally). If you don't like having many applications included by default, consider the non-deluxe version of Livezilla.

Created using live-build.

A list of the included packages can be found in config/package-lists/pkgs.list.chroot

Instructions to build:
You will need a Debian GNU/Linux system, I recommend 11, the latest stable release at the time of writing.
Install live-build and build-essential with apt. (sudo apt install live-build build-essential)


If you want a tested, release version of Livezilla, download a release.
If you want to try the absolute latest Livezilla (untested, possibly unstable), clone this repository.

make sure that you are using a Debian system (can be a real computer, or a VM) with live-build and build-essential installed, then run make in the repo directory.
