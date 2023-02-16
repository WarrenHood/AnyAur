# AnyAur
AnyAur is a very rough and experimental attempt at getting AUR packages on non-Arch Linux distros.
This is very experimental and should be used at your own risk.

## Setup    
Clone the repo and make the scripts executable:

```sh
git clone TODO: Insert repo name here
cd anyaur
chmod +x anyaur anypkg
```

Simply ensure that both the `anypkg` and `anyaur` scripts are in your PATH.

## Usage
Simply run `anyaur <list-of-packages` to build a bunch of packages from the AUR.

If you have a repo with a PKGBUILD, simply cd into it and run `anypkg` to build it.
