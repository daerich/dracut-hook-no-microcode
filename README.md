# dracut-hook-no-microcode
## Hack on dracut-hook on the AUR to be sync with grub-mkconfig
Modified PKGBUILD not to interfere with grub-mkconfig boot config creation.
Excludes microcode cpio packaging and adds explicit dracut flags to ensure functionality.
