---
layout: distro
category: distro

# distro metadata
title: Debian GNU/Linux Stable
id: debian
homepage: "//www.debian.org"
wikipedia: "//en.wikipedia.org/wiki/Debian"
logo: "/assets/images/distros/debian/logo.svg"
colour: "#d80150"
screenshot:
    - ["/assets/images/distros/debian/screenshot.png", "The default desktop interface."]
desktops: ["none", "gnome", "kde-plasma", "xfce", "lxqt", "mate", "cinnamon", "lxde"]
default-shell: bash
parent: null
base: debian # debian, redhat, suse, arch, or other
packaging-system: apt
supports-ppas: false
app-store: false # out-of-the-box GUI package manager
other-packaging-systems: ["flatpak"]
compatible-packaging-systems: ["snap"]
usecase: universal # desktop, server, embedded, mobile, or universal
initialiser: systemd
kernel: linux
coreutils: gnu
free-by-default: true # is all core (preintalled and non-optional) software free?
free-only-repos: true # is all software in the official repos, except drivers, free?
proprietary-drivers: true # does it offer proprietary drivers or binary blobs?
proprietary-codecs: false # does it offer the option to install patented media codecs?
fsf-approved: false # is it approved by the FSF as a fully free OS?
supported-architectures: ["x86-64", "armhf", "aarch64", "mips64el", "mipsel", "risc-v", "s390x", "armel", "i386", "mips", "ppc64el", "risc-v64"]
working-state: true # is it still being worked on and supported?
rolling: false # is it a rolling release?
release-each: 24 # delay between releases, in months
lts-each: 1 # in releases
interim-support: 0 # in months
lts-support: 60 # in months
gui-installer: true
cli-installer: true
live: true # can it run in live mode?
difficulty: # 1 to 5, 1 being the easiest
    installation: 2
    daily-usage: 1
    maintenance: 2
    upgrading: 3
    troubleshooting: 2
price: [0, 0] # price range in euros
commercial: false # is it developed by a for-profit business?
since: 1993 # first release year
country: "United States of America" # country of origin

# system requirements
minimum-requirements:
    ram: 256 # MB
    storage: 2 # GB
    network: false # internet
recommended-requirements:
    ram: 512 # MB
    storage: 10 # GB
    display: null # pixels
    network: true # internet
---

Debian is a highly respected and one of the oldest Linux distributions, known for its very high standard of stability, security, and commitment to free software principles. Debian's package management system, APT, simplifies software installation and updates. The project's focus on rigorous testing ensures a reliable operating system. Debian is the basis for many popular Linux systems, such as Ubuntu. Excluding drivers, Debian is committed to only including and offering free software packages in its default repositories.

<!--more-->

* One of the earliest Linux distros.
* Release cycle is slow and stable.
* Has a wide community, and is the base for distros such as Ubuntu.
* Universal OS, supporting a wide range of hardware.
* Committed to free software. The only nonfree software included or available in the repos are drivers.