# Installation

## clone patches repository including the dwm repository

    git clone https://github.com/jceb/st-patches

## init and load dwm submodule

    cd st-patches
    git submodule update --init --recursive

## activate all patches, including the personal configuration

    quilt push -a

## build dwm (or us the ./build script)

    cd st
    rm -f config.h
    make

# Patch References

* [mysettings.patch](patches/mysettings.patch)                           (no URL yet)
