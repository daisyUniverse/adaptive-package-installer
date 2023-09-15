# adaptive-package-installer
Detect your Distro and use your appropriate package installer to install from a pre-defined list of packages

How this will basically work:
  1. detect your distro
  2. depending on the package manager, use it to install a package list from a file named after the package manager (eg apt.txt, pacman.txt)
  3. That's it

This is basically intended for use with other scripts that have dependencies but don't want to have their users fuss around with finding equivelant packages, without having basically remake this every time
