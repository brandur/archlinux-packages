Archlinux Packages
==================

These are my contributions for buildable packages for the [Archlinux AUR](http://aur.archlinux.org) (Arch User Repository). Contact me with problems/fixes should they arise.

Installation
------------

AUR installation is normally accomplished through [Yaourt](https://wiki.archlinux.org/index.php/Yaourt):

```
yaourt -Sy libmpio-git
```

However, it can almost be accomplished manually by changing to one of the package directories, building the package, then installing it:

```
makepkg
pacman -U libmpio-git-20110719-1-i686.pkg.tar.xz
```

Publishing
----------

A gzipped tarball suitable for submission to the AUR can be built using:

```
makepkg --source
```

See also [submitting packages](https://wiki.archlinux.org/index.php/AUR#Submitting_packages).
