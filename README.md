[![Circle CI](https://circleci.com/gh/jpoirier/librtlsdr.svg?style=svg)](https://circleci.com/gh/jpoirier/librtlsdr)


# Description

rtl-sdr turns your Realtek RTL2832 based DVB dongle into a SDR receiver


# Build with cmake:

    cd librtlsdr/
    mkdir build
    cd build
    cmake ../
    make
    sudo make install
    sudo ldconfig

To use the dongle as a non-root user replace the "cmake ../" with:

    cmake ../ -DINSTALL_UDEV_RULES=ON
    
# For more information see:

http://sdr.osmocom.org/trac/wiki/rtl-sdr
