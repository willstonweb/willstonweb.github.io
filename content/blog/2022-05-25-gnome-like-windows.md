---
title: Making Fedora Linux Look a Little More Like Windows
date: 2022-05-25
description: Using GNOME Tweaks and GNOME Shell Extensions with the Dash to Panel plugin
author: Jonathan Buchholz
url: gnome-like-windows
---

There are a few simple modification that you can make to stock GNOME to make the
transition from Windows to Linux a little easier. They are pretty simple: adding
a couple of additional buttons to the window titlebar and combining the
application launcher and system tray to make the taskbar more similar to that
found in Windows. Below are screenshots of before and after the tweaks. Look
carefully for the aforementioned changes:

<figure>
   <img alt="Before Dash to Panel" src="/images/2022-05-25-before.png">
   <figcaption>Stock GNOME 42</figcaption>
</figure>

<figure>
   <img alt="After Dash to Panel" src="/images/2022-05-25-after.png">
   <figcaption>After changes. Notice the additional buttons in the titlebar and
   the addition of a Windows-like taskbar.</figcaption>
</figure>

As you can see, the changes are subtle, but can make a Windows user feel a lot
more at home using the GNOME desktop environment. Here are the steps to
replicate these changes on Fedora:

## Update all packages

`$ sudo dnf update`

## Install GNOME Tweaks

1. `$ sudo dnf install gnome-tweaks`
2. Open GNOME Tweaks
3. Navigate to: Window Titlebars > Titlebar Buttons
4. Turn the following settings on:
    - Maximize
    - Minimize

## Install Dash to Panel

1. Visit the [Dash to Panel](https://extensions.gnome.org/extension/1160/dash-to-panel/) page
2. Install the GNOME Shell integration by selecting `Click here to install the
   browser extension` and following the subsequent instructions
3. Refresh the page
4. Switch the toggle labeled `OFF` to `ON`
5. Select `Install`
