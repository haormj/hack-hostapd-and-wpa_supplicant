## hack hostapd and wpa_supplicant

### intro

1. http://w1.fi/ 

### hostapd

1. http://w1.fi/releases/hostapd-2.9.tar.gz
2. Linux raspberrypi 5.4.51-v7l+ #1333 SMP Mon Aug 10 16:51:40 BST 2020 armv7l GNU/Linux 
2. build
    ```shell
    cd hostapd
    cp defconfig .config
    ```
3. /usr/bin/ld: cannot find -lnl-genl-3
    ```shell
    sudo apt-get install libnl-genl-3-dev 
    ```
