---
layout: distro
category: distro

# distro metadata
title: Ubuntu Desktop
id: ubuntu
homepage: "//www.ubuntu.com"
wikipedia: "//en.wikipedia.org/wiki/Ubuntu"
logo: "/assets/images/distros/ubuntu/logo.svg"
colour: "#ea4f06"
screenshot:
    - ["/assets/images/distros/ubuntu/screenshot.png", "The default desktop interface."]
desktops: ["gnome"]
default-shell: bash
parent: debian
base: debian # debian, redhat, suse, arch, or other
packaging-system: apt
supports-ppas: true
app-store: true # out-of-the-box GUI package manager
other-packaging-systems: ["snap"]
compatible-packaging-systems: ["flatpak"]
usecase: desktop # desktop, server, embedded, mobile, or universal
initialiser: systemd
kernel: linux
coreutils: gnu
free-by-default: true # is all core (preintalled and non-optional) software free?
free-only-repos: false # is all software in the official repos, except drivers, free?
proprietary-drivers: true # does it offer proprietary drivers or binary blobs?
proprietary-codecs: true # does it offer the option to install patented media codecs?
fsf-approved: false # is it approved by the FSF as a fully free OS?
supported-architectures: ["x86-64", "armhf", "arm64", "risc-v", "ppc64le", "s390x"]
working-state: true # is it still being worked on and supported?
rolling: false # is it a rolling release?
release-each: 6 # delay between releases, in months
lts-each: 4 # in releases
interim-support: 9 # in months
lts-support: 60 # in months
gui-installer: true
cli-installer: false
live: true # can it run in live mode?
difficulty: # 1 to 5, 1 being the easiest
    installation: 1
    daily-usage: 1
    maintenance: 2
    upgrading: 1
    troubleshooting: 1
price: [0, 0] # price range in euros
commercial: true # is it developed by a for-profit business?
since: 2004 # first release year
country: "United Kingdom" # country of origin

# system requirements
minimum-requirements:
    ram: 2048 # MB
    storage: 15 # GB
    network: false # internet
recommended-requirements:
    ram: 4096 # MB
    storage: 25 # GB
    display: null # pixels
    network: true # internet
---

Ubuntu Desktop is the flagship edition of the Ubuntu Linux distribution, designed for personal computer use. It provides a user-friendly and intuitive interface, making it accessible to users of all levels of experience. Ubuntu Desktop offers a comprehensive suite of applications, including productivity tools, multimedia software, and web browsers, to meet various computing needs. It emphasizes stability, security, and regular updates to ensure a reliable and up-to-date operating system. With its large and active community, Ubuntu Desktop benefits from extensive user support, online forums, and documentation resources, making it a popular choice for individuals seeking a user-friendly and reliable Linux desktop environment. It offers a flexible release cycle.

<!--more-->

* Only GNOME is officially supported.
* Includes a wide range of applications for everyone.
* Wide software repositories and support for PPAs which provide more packages.
* Flexible release cycle, offers both regular and LTS releases.
* The widest Linux community.