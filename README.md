# archdesktop

This is a simple bash script for Arch Linux that Install and Remove Desktop Environments and Extra Packages, Add and Remove Groups, Install and Disable Services.

The **Categories** and **Packages** list are pretty much from **EndeavourOS** ISO Installer. I removed from list **EndeavourOS** related packages, **base**, **coreutils** (except linux), **sudo** and **Bootloaders**. On top of that I added more **Browsers**, **Kernels** and a few more recommended packages.

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

![Arch Desktop](https://github.com/efraimkaov/archdesktop/assets/63643635/56161add-97bf-43bf-b43b-ffc661fcfdb5)

![Desktop-Base](https://github.com/efraimkaov/archdesktop/assets/63643635/7e9322f6-1f14-4ece-984d-7179ba9508ef)

![Audio](https://github.com/efraimkaov/archdesktop/assets/63643635/ea1fe0bd-2f30-4418-8c8e-d8c78079dabb)

### To-Do List

* to implement **Remove selected packages** - in progress

* to prevent users to remove **networkmanager** and all **Kernels** - in progress

* to implement **AUR Helper** - in progress

* to implement **Group**

* to add **Service - avahi-daemon**

* to add **Service - bluetooth**

* to add **Service - Boot Target** (graphical and multi-user)

* to add **Service - cups**

* to add **Service - Display Manager** (gdm, lightdm and sddm)

* to add **Service - firewalld**

* to add **Service - NetworkManager**

* to add **Service - reflector**

* to add **Service - sshd**

* to add **Service - upower**

* to improve README.md

#### Bug report

If you find a bug please open a new [issue](https://github.com/efraimkaov/archdesktop/issues) and send a Bug report.
