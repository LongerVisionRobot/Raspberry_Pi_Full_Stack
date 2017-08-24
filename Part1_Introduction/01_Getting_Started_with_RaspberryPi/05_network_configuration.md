# 1.5 Network Configuration

So far, we are **NOT** able to surf the Internet yet. In this chapter, we are going to enable our Internet by configuring network settings, and then set up a static IP address for your Raspberry Pi.

## 1.5.1 Connect to Internet
Command
```
ifconfig
```
shows the current network configuration.

![Image](./network_1_ifconfig.jpg)

Obviously, there is **NO** Internet yet, as indicated on the top-right corner.

![Image](./network_2_internet_not_connected.jpg)

And, by clicking on the **Wifi** icon, it will open a list of detected **Wifi** networks:

![Image](./network_3_internet_listing.jpg)

Click on your network, the **Pre Shared Key** dialog will be popped up for you to input the password, as follows:

![Image](./network_4_internet_pre_sharedkey.jpg)

After inputing the correct password to your **Wifi**, you will see the Internet is NOW connected:

![Image](./network_5_internet_connected_1.jpg)

Move your mouse to the **Wifi** icon, you will see the network information about **wlan0**.

![Image](./network_6_internet_connected_2.jpg)

Now, let's have a look at the network configuration by command
```
ifconfig
```
again.

![Image](./network_7_ifconfig.jpg)

As you can see, the IP address is NOW automatically allocated as **192.168.0.105**.


## 1.5.2 Set Static IP (Strongly Suggested)

In order to be more easily and accurately locate which device is of which IP address, without shifting to a **NEW** IP address while reconnecting to the **SAME** network, users would like to set static IPs for frequently-used devices. The file to specify a static IP for the particular device is **/etc/network/interfaces**. Let's have a look at its content by using command **cat**.

![Image](./network_8_interfaces.jpg)


Initial Raspbian comes with an text-mode editor **nano**, which is to be used.

[https://learn.adafruit.com/adafruits-raspberry-pi-lesson-3-network-setup/setting-up-wifi-with-occidentalis](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-3-network-setup/setting-up-wifi-with-occidentalis)
