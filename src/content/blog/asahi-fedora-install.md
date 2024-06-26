---
title: "Installing Fedora Asahi Remix on Apple M-series Devices"
pubDatetime: 2023-04-28T09:21:40-05:00
description: "Step-by-step instructions to install Fedora Linux on Apple M-series Devices utilizing Fedora Asahi Remix."
ogImage: "https://asahilinux.org/img/far_landing/far_laptop.svg"
draft: false
featured: true
---

## Before you begin

- The website for Fedora Asahi Remix can be found [here](https://fedora-asahi-remix.org/).
- Fedora Asahi Remix is based on Fedora Linux. More information about Fedora Linux can be found [here](https://fedoraproject.org/).
- See currently supported features [here](https://github.com/AsahiLinux/docs/wiki/Feature-Support).

## I. Installation Script

1. Copy `curl https://fedora-asahi-remix.org/install | sh` and paste into terminal.
2. Enter `N` when asked to enter expert mode.
3. Enter `r` to resize your current macOS partion.
4. Enter your desired partition sizes.
5. Allow the installer to complete the installation process.
   _Note:_ Before you reboot, be sure to remember your username. This can be found by entering `id -un` into a terminal.

## II. Recovery Mode

1. Enter the boot selection menu by holding down the power button until the "Loading startup options..." text appears.
2. Select Fedora Asahi Remix in the menu using the arrow keys.
3. Enter your username and password as prompted.
4. Reboot and you should be automatically booted into Fedora Asahi Remix.

## III. Post-install Steps

1. Update your packages with `dnf upgrade`.
2. _(Optional)_ [Follow my personal post-installation steps for Fedora](https://leitzke.me/posts/fedora-post-install).
