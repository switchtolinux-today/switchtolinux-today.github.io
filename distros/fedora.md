---
layout: distro
category: distro

# distro metadata
title: Fedora Workstation
id: fedora
homepage: "//www.fedoraproject.org"
wikipedia: "//en.wikipedia.org/wiki/Fedora_Linux"
logo: "/assets/images/distros/fedora/logo.svg"
colour: "#50a3db"
screenshot:
    - ["/assets/images/distros/ubuntu/screenshot.png", "The default desktop interface."]
desktops: ["gnome", "kde-plasma", "xfce", "lxqt", "mate", "cinnamon", "lxde", "soas", "i3-wm", "phosh", "budgie", "sway"]
default-shell: bash
parent: redhat
base: redhat # debian, redhat, suse, arch, or other
packaging-system: rpm
supports-ppas: false
app-store: true # out-of-the-box GUI package manager
other-packaging-systems: ["flatpak", "ostree"]
compatible-packaging-systems: ["snap"]
usecase: desktop # desktop, server, embedded, mobile, or universal
initialiser: systemd
kernel: linux
coreutils: gnu
free-by-default: true # is all core (preintalled and non-optional) software free?
free-only-repos: true # is all software in the official repos, except drivers, free?
proprietary-drivers: true # does it offer proprietary drivers or binary blobs?
proprietary-codecs: false # does it offer the option to install patented media codecs?
fsf-approved: false # is it approved by the FSF as a fully free OS?
supported-architectures: ["x86-64", "armhf", "aarch64", "mips64el", "mipsel", "ppc64le", "risc-v", "s390x"]
working-state: true # is it still being worked on and supported?
rolling: false # is it a rolling release?
release-each: 6 # delay between releases, in months
lts-each: 0 # in releases
interim-support: 12 # in months
lts-support: 0 # in months
gui-installer: true
cli-installer: true
live: true # can it run in live mode?
difficulty: # 1 to 5, 1 being the easiest
    installation: 1
    daily-usage: 1
    maintenance: 3
    upgrading: 1
    troubleshooting: 2
price: [0, 0] # price range in euros
commercial: false # is it developed by a for-profit business?
since: 2003 # first release year
country: "United States of America" # country of origin

# system requirements
minimum-requirements:
    ram: 2048 # MB
    storage: 20 # GB
    network: false # internet
recommended-requirements:
    ram: 4096 # MB
    storage: 40 # GB
    display: null # pixels
    network: true # internet
---

Fedora is a widely recognized and respected Linux distribution known for its commitment to free software principles and innovative features. Developed by the Fedora Project, Fedora embraces a fast-paced release cycle, ensuring users have access to the latest software advancements. Its default desktop environment for the Workstation edition, GNOME, provides a modern and polished user interface. The Fedora community, as well as upstream developers, actively contribute to its development, offering support and fostering collaboration, resulting in a robust and dynamic Linux distribution.

<!--more-->
