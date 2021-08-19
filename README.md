# PACAUR

## Table of Contents

- [Quick Start](#quick-start)
- [Todo](#Todo)

## Quick Start

1. Set up:

```
git clone https://github.com/acwars/pacaur.git
cd pacaur
sudo make install
```

2. Using Pacaur

```
usage: pacaur [OPTION] [PACKAGE]

[OPTION]
-S PKG      Install target PKG
-R PKG      Remove target PKG
-u          Update all AUR Packages
-d PKG      Download PKGBUILD of PKG, nothing else
-i PKG      Show information for PKG
-s PKG      Search for package by matching PKG
-b SRC      Search By Criteria (give -b option before search STRING)
-p NUM      Number of packages per page (5,25,125)
-m          Make/Compile PKGBUILD of PKG, nothing else
-e          Edit PKGBUILD in installation mode
-k          Keep complie folder
-c          Clean pacaur cache
-h          Print help usage

[SRC] for -b option
 nd         Name, Description (default)
 no         Name Only
 pb         Package Base
 en         Exact Name
 ep         Exact Package Base
 k          Keywords
 m          Maintainer
 cm         Co-maintainer
 mc         Maintainer, Co-maintainer
 s          Submitter

[VARIABLES] change script commands
PACAUR_CACHE        Directory to use for Pacaur Cache ($HOME/.cache/pacaur)
TAR_CMD             Tar command to use (tar)
TAR_FLG             Pass arguments to Tar (xf)
MAKEPKG_CMD         Makepkg command to use (makepkg)
MAKEPKG_INS_FLG     Pass arguments to Makepkg install (-rsif)
MAKEPKG_COM_FLG     Pass arguments to Makepkg Compile (-s)
PACAUR_EDITOR       Editor to use when editing PKGBUILDs ($EDITOR)
```

