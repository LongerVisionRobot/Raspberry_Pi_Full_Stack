# 1.6 Package Update and Upgrade

After Internet is successfully enabled, you can upgrade all installed packages to the **NEWEST** version by the following 2~3 commands:

```
sudo apt update
apt list --upgradable (optional)
sudo apt upgrade
```

In fact, every time you reboot into Raspbian Linux, you can always execute these 2~3 commands in sequence to upgrade all upgradable packages.

* **sudo apt update**: Find all upgradable packages
* **apt list --upgradable** (Optional): List all upgradable packages found by **sudo apt update**
* **sudo apt upgrade**: Upgrade all upgradable packages


