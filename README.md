# xutils-dev_7.7-5ubuntu2_amd64_package
xutils-dev , xserver , xorg , development , ubuntu 20.04


libdrm-2.4.102.zip libpciaccess-0.16_griggorii_source.tar.xz inpack /tmp

cd /tmp/libpciaccess-0.16_griggorii_source/

$ sudo ln -s /usr/lib/x86_64-linux-gnu/libcairo.so.2 /usr/lib/x86_64-linux-gnu/libcairo.so && sudo make install

$ cd /tmp/libdrm-2.4.102/build

$ sudo rm /usr/lib/x86_64-linux-gnu/libpciaccess.so && sudo ln -s /usr/lib/x86_64-linux-gnu/libpciaccess.so.0 /usr/lib/x86_64-linux-gnu/libpciaccess.so && ninja install
