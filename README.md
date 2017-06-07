# rtl8814AU
Realtek 8814AU USB WiFi driver


This should work for kernel up to v4.11.  I tested it on Ubuntu 14.04(kernel v3.18) and Fedora 25(kernel v4.11).


### Installation
To compile the driver, make sure you have all the needed files(headers, gcc, make, etc.) installed.  Be sure your system is up-to-date, especially kernel. Use the following commands to compile and install the driver.
```
git clone https://github.com/lkw16/rtl8814AU.git
cd rtl8814AU/
make
sudo make install
sudo reboot
```


### Uninstall
To remove and clean the installed and compiled driver, you can do the
following within the **rtl8814AU/** folder.
```
sudo make uninstall
make clean
```

