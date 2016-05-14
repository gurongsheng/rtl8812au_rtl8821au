# rtl8812au_rtl8821au
Driver for rtl8812au and rtl8821au (rtl8811au) based on Realtek's 4.3.14 version

##Arch Linux port
https://aur.archlinux.org/packages/rtl8812au_rtl8821au-dkms-git


1.) ~$sudo apt-get install linux-headers-generic build-essential git -y 

Note: for the above command, you will have to enter your password, then hit enter key (notice - it will not show your typing).

2.) ~$ mkdir wireless_driver && cd wireless_driver

3.) ~/wireless_driver$ git clone https://github.com/Grawp/rtl8812au_rtl8821au.git

4.) ~/wireless_driver$ cd rtl8812au_rtl8821au

5.) ~/wireless_driver/rtl8812au_rtl8821au$ make
Note: the process from #5 above may run for a time, have several lines of output, and should end with something like 'make[1]: Leaving directory '/usr/src/linux-headers-4.4.0-12-generic'... no errors.

6.) ~/wireless_driver/rtl8812au_rtl8821au$ sudo make install

7.) ~/wireless_driver/rtl8812au_rtl8821au$ sudo modprobe 8812au
