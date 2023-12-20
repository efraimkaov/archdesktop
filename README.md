# archdesktop

This is a simple bash script for Arch Linux that Install and Remove Desktop Environments and some Extra Packages, Enable and Disable Services.

The **Categories** and **Packages** list are pretty much from **EndeavourOS** Calamares Installer. I removed from list **EndeavourOS** related packages, **base**, **coreutils**, **sudo** and **Bootloaders**. On top of that I added more **Browsers** and a few more **Recommended packages**.

#### Install dependencies

```sh
sudo pacman -S --needed dialog git --noconfirm
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

### To-Do List

* ask for confirmation to remove **networkmanager**

* implement **Services**

* improve **README.md**

#### Bug report

If you find a bug please open a new [issue](https://github.com/efraimkaov/archdesktop/issues) and send a Bug report.
