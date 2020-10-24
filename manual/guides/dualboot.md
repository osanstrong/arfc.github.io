---
layout: manual
title: Dual Booting Windows and Ubuntu
subtitle: "A Helpful List of Resources"
permalink: /manual/guides/dualboot
---


## Why Dual Boot

Dual booting simply means installing two operating systems on one hard drive.

In your career as a computational scientist, you will
quickly outgrow the limited capabilities of Windows command prompt.
Why Linux is better for programming:
1. Compiling code like C++ or SQL is difficult in Windows.
2. Linux terminal is much more powerful than Windows command prompt
3. Native support for SSH
4. Linux is "light-weight" and therefore faster than Windows.

## How to Dual Boot

You will need:
- An empty flashdrive with at least 5 GB of storage
- At least 25 GB of available hard drive space on the computer you wish to dual
boot (I recommend 50 GB)
- Some patience

Once you have those things, you will be able to dual boot. This [dual booting tutorial](https://www.youtube.com/watch?v=Z-Hv9hOaKso) is
very clear and will walk you through each step.

**As of October, 2020: The recommended version is Ubuntu 20.04 LTS**

## After You've Installed Linux

When you boot up Linux for the first time you will have very few applications
available. A graduate student, Sam Dotson, wrote a bash script that quickly installs some essential
applications, as well as some helpful productivity tools. The script is available on GitHub, [here](https://github.com/samgdotson/ubuntu-post-installer). All you need to do
in order to execute this script is the following
```bash
wget https://raw.githubusercontent.com/samgdotson/ubuntu-post-installer/master/ubuntu-post-installer.sh

bash ubuntu-post-installer.sh
```

### Alternatives to Dual Booting

If you don't want to dual boot and just want to use the Linux terminal, Windows
offers an application called "Windows Linux Subsystem." It works, but you will
probably be frustrated because the Linux subsystem doesn't interface well with
the Windows graphical user interface.

E.g. You cannot* open an application from the Linux subsystem.
However, if that is the path you would like to take you can follow this
[tutorial](https://docs.microsoft.com/en-us/windows/wsl/install-win10).




*It's not technically _impossible_, but it is well beyond the scope of this
tutorial.
