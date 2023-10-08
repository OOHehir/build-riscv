# build-riscv

Yocto build for StarFive VisionFive 2

Work in progress!

Amongs the usual Yocto requirements the following are required:
kas
git-lfs


## Misc tasks

### Build individual recipe with verbose
kas shell poky-qt-visionfive2.yml -c 'bitbake -v qt6'

### Clean individual recipe 
kas shell poky-qt-visionfive2.yml -c 'bitbake -c cleanall gcc'
kas shell poky-qt-visionfive2.yml -c 'bitbake -c cleanall qtbase'

