# 1.4 Locale Configuration

## 1.4.1 raspi-config
[**raspi-config**](https://www.raspberrypi.org/documentation/configuration/raspi-config.md) is the Raspberry Pi configuration tool specifically for the Raspberry Pi.
Command
```
sudo raspi-config
```
will pop up the following configuration page:

![Image](./raspi-config.jpg)
As you can see, the very **FIRST** item is just **Expand Filesystem**, which has been talked about in the previous section, and has already been done when booting Raspberry Pi.

## 1.4.2 dpkg-reconfigure
**dpkg-reconfigure** is to reconfigure an already installed package.

* **dpkg-reconfigure tzdata**
* **dpkg-reconfigure locales**
* **dpkg-reconfigure keyboard-configuration**
