---
layout: distro
category: distro

# distro metadata
title: Arch Linux
id: arch
homepage: "//archlinux.org"
wikipedia: "//en.wikipedia.org/wiki/Arch_Linux"
logo: "/assets/images/distros/arch/logo.svg"
colour: "#3ba3d7"
screenshot:
    - ["/assets/images/distros/arch/screenshot.png", "The install disc terminal."]
desktops: ["none", "awesome", "bspwm", "budgie", "cinnamon", "cutefish", "deepin", "enlightenment", "gnome", "i3-wm", "i3-gasp", "kde-plasma", "lxqt", "mate", "sway", "xfce", "qtile"]
default-shell: bash
parent: null
base: arch # debian, redhat, suse, arch, or other
packaging-system: pacman
supports-ppas: false
app-store: false # out-of-the-box GUI package manager
other-packaging-systems: []
compatible-packaging-systems: ["flatpak", "snap"]
usecase: universal # desktop, server, embedded, mobile, or universal
initialiser: systemd
kernel: linux
coreutils: gnu
free-by-default: true # is all core (preintalled and non-optional) software free?
free-only-repos: false # is all software in the official repos free?
proprietary-drivers: true # does it offer proprietary drivers or binary blobs?
proprietary-codecs: true # does it offer the option to install patented media codecs?
fsf-approved: false # is it approved by the FSF as a fully free OS?
supported-architectures: ["x86-64", "i686", "arm64", "armhf", "powerpc", "risc-v"]
working-state: true # is it still being worked on and supported?
rolling: true # is it a rolling release?
release-each: 0 # delay between releases, in months
lts-each: 0 # in releases
interim-support: 0 # in months
lts-support: 0 # in months
gui-installer: false
cli-installer: true
live: true # can it run in live mode?
difficulty: # 1 to 5, 1 being the easiest
    installation: 4
    daily-usage: 2
    maintenance: 3
    upgrading: 2
    troubleshooting: 3
price: [0, 0] # price range in euros
commercial: false # is it developed by a for-profit business?
since: 2002 # first release year
country: "United States of America" # country of origin

# system requirements
minimum-requirements:
    ram: 512 # MB
    storage: 2 # GB
    network: true # internet
recommended-requirements:
    ram: 2048 # MB
    storage: 20 # GB
    display: null # pixels
    network: true # internet
---

Arch Linux is an extremely customisable and minimalist operating system known for its rolling release model and extensive software options provided by the community in the Arch User Repository (AUR). The comprehensive ArchWiki serves as a valuable resource and is renowned for its documentation and troubleshooting guides. The active, loyal community plays a large role in the development, maintenance, and support of Arch Linux.

<!--more-->

* A very customisable, light and minimal operating systems.
* Offers a very wide range of software through the AUR.
* Loyal, dedicated community.
* Comprehensive wiki with a wide range of tutorials.