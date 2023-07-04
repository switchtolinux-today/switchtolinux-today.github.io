---
layout: distro
category: distro

# distro metadata
title: openSUSE Leap
id: opensuse
homepage: "//www.opensuse.org"
wikipedia: "//en.wikipedia.org/wiki/OpenSUSE"
logo: "/assets/images/distros/opensuse/logo.svg"
colour: "#74bb20"
screenshot:
    - ["/assets/images/distros/opensuse/screenshot.png", "The default desktop interface."]
desktops: ["none", "kde-plasma", "gnome", "xfce"]
default-shell: bash
parent: suse
base: suse # debian, redhat, suse, arch, or other
packaging-system: zypp
supports-ppas: false
app-store: true # out-of-the-box GUI package manager
other-packaging-systems: ["rpm"]
compatible-packaging-systems: ["flatpak", "snap"]
usecase: universal # desktop, server, embedded, mobile, or universal
initialiser: systemd
kernel: linux
coreutils: gnu
free-by-default: true # is all core (preintalled and non-optional) software free?
free-only-repos: false # is all software in the official repos, except drivers, free?
proprietary-drivers: false # does it offer proprietary drivers or binary blobs?
proprietary-codecs: false # does it offer the option to install patented media codecs?
fsf-approved: false # is it approved by the FSF as a fully free OS?
supported-architectures: ["i686", "x86-64", "aarch64", "armv7hl", "ppc64", "risc-v", "s390", "ppc64le"]
working-state: true # is it still being worked on and supported?
rolling: false # is it a rolling release?
release-each: 12 # delay between releases, in months
lts-each: 0 # in releases
interim-support: 18 # in months
lts-support: 0 # in months
gui-installer: true
cli-installer: true
live: true # can it run in live mode?
difficulty: # 1 to 5, 1 being the easiest
    installation: 3
    daily-usage: 2
    maintenance: 3
    upgrading: 2
    troubleshooting: 3
price: [0, 0] # price range in euros
commercial: false # is it developed by a for-profit business?
since: 2005 # first release year
country: "Germany" # country of origin

# system requirements
minimum-requirements:
    ram: 1024 # MB
    storage: 1.5 # GB
    network: false # internet
recommended-requirements:
    ram: 2048 # MB
    storage: 10 # GB
    display: null # pixels
    network: true # internet
---

OpenSUSE Leap is a stable and reliable Linux distribution based on the SUSE Linux Enterprise (SLE) codebase. It combines the best of both worlds, offering enterprise-grade stability and a community-driven approach. It is suitable for both desktop and server environments. It provides a user-friendly desktop experience, officially supporting KDE Plasma, GNOME, and Xfce. OpenSUSE Leap emphasizes useability, flexibility, and a strong focus on open-source collaboration, making it a compelling choice for users seeking a balance between stability and up-to-date software.

<!--more-->

* Balanced release cycle with 18 months of support.
* Based on the enterprise SUSE Linux.
* Comfortable, polished desktop experience.
* Flexible and universal, suitable for both desktop and server.
* Community-driven.