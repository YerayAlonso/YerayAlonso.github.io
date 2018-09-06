---
layout: post
title:  "OS performance comparison"
categories: [blog, comparison]
tags: [hot, comparison, linux, performance]
---

There are many linux distributions out there, I've tested some of the full-featured to compare them to try to find which one consumes less memory and CPU, at least running in a virtual machine.  
Trying to be as fair as possible, I'm always installing the machines into a virtual machine under a Windows 10 x64.

I'm always taking the numbers with a few programs opened:
- LibreOffice Writter with a blank document
- Firefox: w3schools.com (found google.com takes a looot or CPU)
- File explorer: Home
- Terminal: uname -a
- System Monitor

The physical machine:
- CPU: Intel i7 4771
- Motherboard: Gigabyte Z87-HD3
- Memory: 2x8GB DDR3 Corsair
- GPU: GeForce GTX 760

The virtual machine:
- Memory: 2GB
- CPU: 2
- Screen
  - Memory: 128MB
  - 3D acceleration: activated
- Disk: 200GB

| | CPU | RAM
| -- | -- | -- |
Ubuntu (Gnome) 18.04.1 | 3% | 1.6 GB
Ubuntu (Gnome) 17.10 | 10% | 1.4 GB
Ubuntu Mate 18.04 | 1% | 1.3 GB
Ubuntu Gnome 16.04 | 22% | 1.2 GB
DeepIn 15.5 | 24% | 1.1 GB
ElementaryOS 0.4.1 | 7% | 1.1 GB
Ubuntu (Unity) 16.04 | 28%| 1 GB
Ubuntu Mate 17.10 | 6% | 990 MB
Kubuntu 16.04 | 8% | 950 MB
DeepIn 15.6 | 2% | 936 MB
Kubuntu 15.10 | 10% | 900 MB
Debian Mate 9.3 | 10% | 890 MB
Ubuntu Gnome 15.10 | 20% | 850 MB
DeepIn 15.7 | 2% | 814 MB
Kubuntu 18.04.1 | 2% | 810 MB
Lubuntu 18.04	| 0% | 758 MB
Kubuntu 17.10	| 8% | 740 MB
Ubuntu (Unity) 15.10 | 27% | 727 MB
Ubuntu (Unity) 14.04.3 | 28% | 728 MB
Xubuntu 17.10 | 8% | 675 MB
KDE Neon 180301 | 13% | 660 MB
Ubuntu Mate 16.04 | 9% | 645 MB
Ubuntu Mate 15.10 | 12% | 606 MB
Lubuntu 17.10 | 4% | 570 MB
Ubuntu 14.04.3 lxde | 8% | 565 MB
Xubuntu 16.04 | 8% | 550 MB
Xubuntu 15.10 | 5% | 553 MB
Ubuntu 14.04.3 lxde without Unity | 9% | 383 MB
Lubuntu 15.10 | 7% | 380 MB
