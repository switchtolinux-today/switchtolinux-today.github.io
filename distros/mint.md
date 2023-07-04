---
layout: distro
category: distro

# distro metadata
title: Linux Mint
id: mint
homepage: "//www.linuxmint.com"
wikipedia: "//en.wikipedia.org/wiki/Linux_Mint"
logo: "/assets/images/distros/mint/logo.svg"
colour: "#67b23e"
screenshot:
    - ["/assets/images/distros/mint/screenshot.png", "The default desktop interface."]
    - ["/assets/images/distros/mint/screenshot1.jpg", "The installer."]
    - ["/assets/images/distros/mint/screenshot2.jpg", "The Software Manager, a graphical installer."]
desktops: ["cinnamon", "mate", "xfce"]
default-shell: bash
parent: ubuntu
base: debian # debian, redhat, suse, arch, other, or independent
packaging-system: apt
supports-ppas: true
app-store: true # out-of-the-box GUI package manager
other-packaging-systems: ["flatpak"]
compatible-packaging-systems: ["snap"]
usecase: desktop # desktop, server, embedded, mobile, or universal
initialiser: systemd
kernel: linux
coreutils: gnu
free-by-default: true # is all core (preintalled and non-optional) software free?
free-only-repos: false # is all software in the official repos free?
proprietary-drivers: true # does it come with proprietary drivers or binary blobs?
proprietary-codecs: true # does it offer the option to install proprietary media codecs?
fsf-approved: false # is it approved by the FSF as a fully free OS?
supported-architectures: ["x86-64"]
working-state: true # is it still being worked on and supported?
rolling: false # is it a rolling release?
release-each: 6 # delay between releases, in months
lts-each: 1 # in releases
interim-support: 9 # in months
lts-support: 60 # in months
gui-installer: true
cli-installer: false
live: true # can it run in live mode?
difficulty: # 1 to 5, 1 being the easiest
    installation: 1
    daily-usage: 1
    maintenance: 1
    upgrading: 2
    troubleshooting: 1
price: [0, 0] # price range in euros
commercial: false # is it developed by a for-profit business?
since: 2006 # first release year
country: "France" # country of origin

# system requirements
minimum-requirements:
    ram: 2048 # MB
    storage: 20 # GB
    network: false # internet
recommended-requirements:
    ram: 4096 # MB
    storage: 100 # GB
    display: [1024, 768] # pixels
    network: true # internet
---

Linux Mint is a Linux distribution widely recognised for its classic user-friendly interface, familiar design, and emphasis on stability, reliability, and security. The operating system is very customisable and provides a wide variety of applications through its software repository, catering to a variety of user preferences and needs. It is compatible with diverse hardware components and benefits from a wide and active community, with developers actively interacting with users and listening to them. It is based on Ubuntu LTS and compatible with it.

<!--more-->

* Cinnamon, MATE or XFCE desktops, providing a traditional interface.
* Compatible with Ubuntu LTS.
* Over 90,000 free applications in the repositories.
* Suitable for desktop use.
* Developer of the Cinnamon desktop, ensuring a tightly integrated experience.
* Developers actively listen to the comunnity.
* All releases are LTS.