Cubietruck-Image-Builder
=================

Scripts to build images for cubietruck.
Originally cloned from Igor Pecovnik


Installation steps
------------------

```shell
sudo apt-get -y install git
cd ~
git clone https://github.com/jeroenhuisman/Cubietruck-Image-Builder
chmod +x ./Cubietruck-Image-Builder/build.sh
cd ./Cubietruck-Image-Builder
sudo ./build.sh
```



Todo List
------------------
- Add options to create Ubuntu or Debian Base Image.
- Add options to select Ubuntu or Debian version.
- Include command line options to configure networking.
- Add --interactive option.
- Add option to include additional packages to image.
- Include option to build directly to SD card.
- Integrate awdev driver to build directly to NAND flash in FEL mode.
