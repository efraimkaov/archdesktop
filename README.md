# archdesktop

This is a bash script for Arch Linux that Install and Remove Desktop Environments and some Extra Packages, Enable and Disable Services.

The **Categories** and **Packages** list are pretty much from **EndeavourOS** Calamares Installer. I removed from list **EndeavourOS** related packages, **base**, **coreutils**, **sudo** and **Bootloaders**. On top of that I added more **Browsers** and a few more **Recommended packages**.

#### Install dependencies

```sh
sudo pacman -Syy --needed dialog git --noconfirm
```

#### How to use

```sh
git clone https://github.com/efraimkaov/archdesktop.git
```

```sh
cd archdesktop/
```

```sh
chmod +x archdesktop
```

```sh
sudo ./archdesktop
```

#### A few screenshots

![Arch Desktop](https://github.com/efraimkaov/archdesktop/assets/63643635/ca991cb8-1e43-4f01-9010-2f8366334c1b)

![Desktop Environment](https://github.com/efraimkaov/archdesktop/assets/63643635/d1736a81-bf5d-467f-9238-e3112583a11a)

![Budgie-Desktop](https://github.com/efraimkaov/archdesktop/assets/63643635/b7baa614-2bb7-45b9-b353-51446c74b978)

### IMPORTANT!!!

If you want to remove packages I highly recommend you to do this from CLI. You can easily switch to CLI whith the following command:

```sh
sudo systemctl isolate multi-user.target
```

### Troubleshoot

If you have problems to install packages this may be because your system is not updated. You can update your system whith the following command:

```sh
sudo pacman -Syyu archlinux-keyring
```

### Optional

If you want to install the Base-packages list, you can do this whith the following command:

```sh
sudo pacman -Syy --needed - < ./data/Base-packages
```

### To-Do List

* implement **Services**

* show message when no package or service is selected

#### Bug report

If you find a bug please open a new [issue](https://github.com/efraimkaov/archdesktop/issues) and send a Bug report.
