# AnyAur
AnyAur is an attempt at getting AUR packages to build on non-Arch Linux distros.
This probably won't work on many AUR packages, will probably need manual installation of dependencies, etc.
This is very experimental and should be used at your own risk.

## Setup    
Clone the repo and make the scripts executable:

```sh
git clone git@github.com:WarrenHood/AnyAur.git
cd AnyAur
chmod +x anyaur anypkg
```

Then ensure that both the `anypkg` and `anyaur` scripts are in your PATH.

## Usage
Simply run `anyaur <list-of-packages` to build a bunch of packages from the AUR.

If you have a repo with a PKGBUILD, simply cd into it and run `anypkg` to build it.

Installing the built files is up to you. A command will be given to you after the package has been built, use it at your own risk to place the built files where they belong. (I am not responsible if you break your system)
