# gnuarmeclipse-tools
Some tools for gnuarmeclipse. See http://sourceforge.net/projects/gnuarmeclipse/

## build-qemu-osx.sh
This script was adapted from the one in the main gnuarmeclipse repo. See [How_to_build_OS_X_QEMU](http://gnuarmeclipse.livius.net/wiki/How_to_build_OS_X_QEMU) for more information. Currently using it to build on Yosimite. 

This assumes the following packages were installed with homebrew instead of MacPorts:

    brew install libtool automake autoconf pkgconfig wget texinfo

It also installs to ~/build/gnuarmeclipse and will copy the .pkg file to the home folder.

Last known place this was known to work on qemuarmeclipse-qemu: 240a9b744e0e8e0961bbc1de8fc79a8863aeea84

