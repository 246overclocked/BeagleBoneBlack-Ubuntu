BeagleBoneBlack-Ubuntu
======================

Scripts, Binaries, and Sources used to get Ubuntu 14.04 on the BeagleBone Black, following [this tutorial](https://eewiki.net/display/linuxonarm/BeagleBone+Black)

## Setup
On Ubuntu or Debian host machine (not BeagleBone)
### Dependencies:
```Bash
$ sudo apt-get update && sudo apt-get install libc6:i386 libstdc++6:i386 libncurses5:i386 zlib1g:i386
```
### Variables
```Bash
$ cd BeagleBoneBlack-Ubuntu
BeagleBoneBlack-Ubuntu$ export CC=`pwd`/gcc-linaro-arm-linux-gnueabihf-4.9-2014.09_linux/bin/arm-linux-gnueabihf-
BeagleBoneBlack-Ubuntu$ export kernel_version=3.18.1-bone1
```

# Installing Ubuntu
Follow the tutorial from [here](https://eewiki.net/display/linuxonarm/BeagleBone+Black#BeagleBoneBlack-SetupmicroSD/SDcard) (Setup of microSD card).

## Credit
Thank you to [Robert C. Nelson](https://github.com/RobertCNelson?tab=repositories) for your great [tutorial](https://eewiki.net/display/linuxonarm/BeagleBone+Black)!
