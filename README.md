# AnyAur
AnyAur is an attempt at getting AUR packages to build on non-Arch Linux distros.
This is very experimental and should be used at your own risk.

## Setup    
Clone the repo and make the scripts executable:

```sh
git clone https://github.com/WarrenHood/AnyAur
cd AnyAur
chmod +x anyaur anypkg
```

Then ensure that both the `anypkg` and `anyaur` scripts are in your PATH.

## Usage
Simply run `anyaur <list-of-packages` to build a bunch of packages from the AUR.

If you have a repo with a PKGBUILD, simply cd into it and run `anypkg` to build it.
