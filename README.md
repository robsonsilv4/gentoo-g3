# Gentoo G3

[English]() | [Português]()

Installation, configuration and stage 4 for Gentoo Linux.

![Preview](./images/preview.png)

## Configurations

Portage

- [make.conf](./configurations/make.conf)
- [packages.use](./configurations/packages/use/)
- [packages.accept_keywords](./configurations/make.conf)

Kernel

- [Gentoo](./configurations/kernels)
- [CK](./configurations/kernels)

## Stage 4

### Minimal Desktop:

Profile:

```bash
default/linux/amd64/17.1/desktop/plasma
```

Kernel
```
linux-5.4.28-gentoo
```


### Plasma/KDE Desktop:

Profile:

```bash
default/linux/amd64/17.1/desktop/plasma
```

Kernel
```
linux-5.4.28-gentoo
```

Ebuilds:

```bash
app-admin/sudo
app-admin/sysklogd
app-misc/neofetch
app-portage/genlop
app-portage/gentoolkit
app-shells/bash-completion
dev-vcs/git
kde-apps/ark
kde-apps/gwenview
kde-apps/kate
kde-apps/kdecore-meta
kde-apps/okular
kde-apps/spectacle
kde-misc/latte-dock
kde-plasma/plasma-meta
media-fonts/liberation-fonts
media-libs/mesa
media-libs/vulkan-loader
media-plugins/alsa-plugins
media-sound/alsa-utils
media-video/ffmpeg
net-misc/aria2
net-misc/networkmanager
sys-apps/bleachbit
sys-apps/haveged
sys-apps/iucode_tool
sys-apps/mlocate
sys-apps/pciutils
sys-apps/usbutils
sys-boot/grub:2
sys-firmware/intel-microcode
sys-fs/dosfstools
sys-fs/ntfs3g
sys-kernel/gentoo-sources
sys-kernel/linux-firmware
sys-libs/pam
sys-power/intel-undervolt
sys-process/cronie
sys-process/htop
www-client/firefox-bin
www-client/links
x11-apps/mesa-progs
x11-base/xorg-server
x11-drivers/nvidia-drivers
x11-misc/xdg-user-dirs
```

## License
