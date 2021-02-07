# termux-ubuntu-proot-distro
# Run ubuntu in termux with proot-distro
# Use folowing commands


pkg install proot-distro

proot-distro install ubuntu-20.04

proot-distro login ubuntu-20.04

# in one line command

pkg install proot-distro && proot-distro install ubuntu-20.04 && proot-distro login ubuntu-20.04
