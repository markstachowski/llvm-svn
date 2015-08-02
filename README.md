# llvm-svn

This is a fork of the already nice [llvm-svn](https://aur4.archlinux.org/packages/llvm-svn/) PKGBUILD from Arch Linux AUR. The fork makes the switch to cmake in lieu of autotools, and supports out-of-source builds.

___IMPORTANT:___ _This PKGBUILD uses a slightly different version scheme. Instead of being simply the SVN revision number, it also adds the LLVM version number itself, e.g. `llvm-svn 3.8.0_r243840-1`._

## TODO

* Lots of things need refining. Some nasty bugs may still be lurking around.
