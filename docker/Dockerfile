FROM archlinux:latest
RUN pacman -Syy \
  && pacman --noconfirm -S  wget curl unzip zip \ 
     gcc cmake make automake autoconf libtool \
     git arm-none-eabi-gcc arm-none-eabi-binutils \
     arm-none-eabi-newlib usbip usbutils glibc
