---
title:  "Linux performance comparison"
categories: [blog, comparison]
tags: [hot, comparison, linux, performance]
---

There are many linux distributions out there! I've tested some of the full-featured Debian/Ubuntu based to compare them to try to find which one consumes less memory and CPU, at least running in a virtual machine.

<!--more-->

## In this page

- [Introduction](#introduction)
- [Comparison](#comparison)
- [Specifications](#specifications)

## Introduction

Why Debian/Ubuntu based? Developing under Windows (RAD Studio and Visual Studio) sometimes you want to test how your project performs or looks in linux. For these scenario, a virtual machine where you can easily install [PAServer](http://docwiki.embarcadero.com/RADStudio/Rio/en/Installing_the_Platform_Assistant_on_Linux) or [mono](https://www.mono-project.com/download/stable/#download-lin-ubuntu) helps a lot. And you don't want that virtual machine to take much memory or CPU from your physical machine...

## Comparison

Here's a chart comparing the memory taken in the tested distributions:

<div>
    <a href="https://plot.ly/~norike/16/?share_key=wmTnkYFGbHxCISYTURmpR9" target="_blank" title="Plot 16" style="display: block; text-align: center;"><img src="https://plot.ly/~norike/16.png?share_key=wmTnkYFGbHxCISYTURmpR9" alt="Plot 16" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="norike:16" sharekey-plotly="wmTnkYFGbHxCISYTURmpR9" src="https://plot.ly/embed.js" async></script>
</div>

Here the Historic:

<div>
    <a href="https://plot.ly/~norike/2/?share_key=WExi0zGekCmfmUJGVPywdb" target="_blank" title="Plot 2" style="display: block; text-align: center;"><img src="https://plot.ly/~norike/2.png?share_key=WExi0zGekCmfmUJGVPywdb" alt="Plot 2" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="norike:2" sharekey-plotly="WExi0zGekCmfmUJGVPywdb" src="https://plot.ly/embed.js" async></script>
</div>

## Specifications

Trying to be as fair as possible, I'm always installing the machines into a virtual machine under a Windows 10 x64.

I'm always taking the numbers with a few programs opened:
- LibreOffice Writter with a blank document
- Firefox: w3schools.com (found google.com takes a looot or CPU in some cases)
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
