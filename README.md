Linux kernel for NanoPi M3/T3 based on vanilla kernel 4.11.6. 

In development.

###compilation

    make ARCH=arm64 nanopim3_defconfig
    make ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- Image dtbs

