# Installation

## clone patches repository including the dwm repository

    git clone https://github.com/jceb/st-patches

## init and load dwm submodule

    cd st-patches
    git submodule update --init --recursive

## activate all patches, including the personal configuration

    quilt push -a

## build st (or us the ./build script)

    cd st
    rm -f config.h
    make

## install st locally (or use ./install script)

    make DESTDIR=~/.local PREFIX= install

# Patch References

* [mysettings.patch](patches/mysettings.patch)                           (no URL yet)
* [fix_delete_key.patch](patches/fix_delete_key.patch)                   (no URL yet)
