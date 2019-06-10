# This is a fork

Changes:
 - Added VoidGreen
 - Modified build.sh (a little bit)

<a href="https://github.com/KaizIqbal/Bibata_Extra_Cursor">
<p align="center"><img title="Bibata Extra" src="https://github.com/KaizIqbal/Bibata_Extra_Cursor/blob/master/image/Bibata_extra.png"></p>
</a>

<p align="center">

[![HitCount](http://hits.dwyl.io/KaizIqbal/Bibata_Extra_Cursor.svg)](http://hits.dwyl.io/KaizIqbal/Bibata_Extra_Cursor)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![GitHub contributors](https://img.shields.io/github/contributors/KaizIqbal/Bibata_Extra_Cursor.svg)](https://GitHub.com/KaizIqbal/Bibata_Extra_Cursor/graphs/contributors/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/KaizIqbal/Bibata_Extra_Cursor/graphs/commit-activity)
![PRs](https://img.shields.io/badge/PRs-Welcome-red.svg)
[![Donate](https://img.shields.io/badge/Donate-yes-yellow.svg)](https://www.paypal.me/kaizkhatri)
[![Code Of Conduct](https://img.shields.io/badge/COC-yes-pink.svg)](https://github.com/KaizIqbal/Bibata_Extra_Cursor/blob/master/CODE_OF_CONDUCT.md)
</p>

<p align="center">

![Open Source Love png1](https://badges.frapsoft.com/os/v1/open-source.png?v=103)
![Bash Shell](https://badges.frapsoft.com/bash/v1/bash.png?v=103)
[![GitHub forks](https://img.shields.io/github/forks/KaizIqbal/Bibata_Extra_Cursor.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/KaizIqbal/Bibata_Extra_Cursor/network)
[![GitHub watchers](https://img.shields.io/github/watchers/KaizIqbal/Bibata_Extra_Cursor.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/KaizIqbal/Bibata_Extra_Cursor/watchers/)
[![GitHub stars](https://img.shields.io/github/stars/KaizIqbal/Bibata_Extra_Cursor.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/KaizIqbal/v/stargazers/)
[![GitHub followers](https://img.shields.io/github/followers/KaizIqbal.svg?style=social&label=Follow&maxAge=2592000)](https://github.com/KaizIqbal?tab=followers)
</p>


## How to get Project Message and Updates

I'll release messages on
 * [Google+](https://plus.google.com/+KaizKhatri)
 * [Twitter](https://twitter.com/ful1e5_)



## Table Of Contents
<!--ts-->
   * [How to get Project Message and Updates](#how-to-get-project-message-and-updates)
   * [Table Of Contents](#table-of-contents)
   * [Donate](#donate)
      * [One-time donation](#one-time-donation)
   * [What is Bibata](#what-is-bibata)
   * [Dependencies](#dependencies)
      * [Build dependencies](#build-dependencies)
   * [Installation](#installation)
      * [Build From Source Code](#build-from-source-code)
      * [Package](#package)
   * [Quick Fixes](#quick-fixes)
      * [Inherits Problem](#inherits-problem)
   * [Work in Progress](#work-in-progress)
   * [Gallery](#gallery)
   * [Bugs](#bugs)
   * [License & Terms](#license-and-terms)
   * [Getting help](#getting-help)
   * [Contributions & Suggestions](#contributions-and-suggestions)
<!--te-->

## Donate

**Who Am I?**

I'm a _ComputerScienceStudent_, _GraphicsDesigner_ and _OpenSourceEnthusiast_. I mostly do  _ComputerGraphics_ stuffs and love them 💕

Currently I'm making lots of Linux Themes to Improve [Linux](https://en.wikipedia.org/wiki/Linux) Experience, if you enjoy my works please consider making a donation. My ultimate goal is to become a full-time open-source ninja.

### One-time donation

<p align="center">
<a  href="https://www.paypal.me/kaizkhatri"><img title="Become Kaiz's Paypal" width=47% src="https://www.paypalobjects.com/webstatic/mobile/hob/web/pp_here_flat.png"></a>
</br>
<sub>My PayPal Email : kaizmandhu at google's mail</sub>
</p>



## What is Bibata

|      Name      |     Description     |
| :-----------:  | :------------------ |
|     Bibata     | Bibata is **OpenSource** ,Compact and Material Designed Cursor set.This project masterelop for improve ```Linux``` Experience and Feel _openness_ in ```OpenSoftwareWorld```.|
|   Bibata Pink   | Pink  Theme  |
|   Bibata Turquoise  | Turquoise Theme  |
|   Bibata DodgerBlue | Dodger-Blue Theme |
|   Bibata DarkRed | Brownies Theme |
|   Bibata VoidGreen | A Green like the one from Void Linux |

## Dependencies

### Build dependencies

* [Xcursorgen](https://github.com/freedesktop/xcursorgen)
* [Inkscape](https://gitlab.com/inkscape/inkscape)
* [gnome-themes-standard](https://launchpad.net/ubuntu/+source/gnome-themes-standard)

## Installation

**Note :** Latest ```Stable``` & ```BETA``` releases can be downloaded from [Here](https://github.com/KaizIqbal/Bibata_Extra_Cursor/releases)

### Build From Source Code

1. Make sure you have installed all [Dependencies](#dependencies).

2. **Build & Install**:
    ```bash
    $git clone https://github.com/KaizIqbal/Bibata_Extra_Cursor.git
    $cd Bibata_Extra_Cursor/
    $chmod +x build.sh
    $./build.sh
    $chmod +x ./Installer_Bibata.sh
    ```
    Install (As ROOT User)
    ```bash
    $sudo ./Installer_Bibata.sh
    ```
    Install (As Local User)
    ```
    $./Installer_Bibata.sh
    ```
3. **Uninstall**:

     Using ```Script``` :

      ```bash
      #From ROOT
      $sudo ./Installer_Bibata.sh
      #From Local User
      $./Installer_Bibata.sh
      ```

     Without ```Script``` :
     ```bash
     #From ROOT
     $sudo rm -r /usr/share/icons/Bibata_*
     #from Local User
     $rm -r ~/.icons/Bibata_*
     #Note : Your replace * with flavor Name to remove individual
     ```

## Quick Fixes
##### *Inherits* Problem
issue [#8](https://github.com/KaizIqbal/Bibata_Cursor/issues/8)

edit ```/usr/share/icons/default/index.theme``` and replace your cursor.

     [Icon Theme]
     Inherits=Adwaita

edited to

     [Icon Theme]
     Inherits=Bibata_Pink                     #replace here

## Work in progress
[Bibata Project](https://github.com/KaizIqbal/Bibata_Cursor#work-in-progress)

## Gallery

<p align="center"><img title="Bibata Pink" src="https://github.com/KaizIqbal/Bibata_Extra_Cursor/blob/master/image/Bibata_Pink.png">
</br><sub>Bibata Pink</sub></p>

<p align="center"><img title="Bibata Turquoise" src="https://github.com/KaizIqbal/Bibata_Extra_Cursor/blob/master/image/Bibata_Turquoise.png">
</br><sub>Bibata Turquoise</sub></p>

<p align="center"><img title="Bibata Dodger-Blue" src="https://github.com/KaizIqbal/Bibata_Extra_Cursor/blob/master/image/Bibata_DodgerBlue.png">
</br><sub>Bibata Dodger-Blue</sub></p>

<p align="center"><img title="Bibata Dodger-Blue" src="https://github.com/KaizIqbal/Bibata_Extra_Cursor/blob/master/image/Bibata_DarkRed.png">
</br><sub>Bibata Dark-Red</sub></p>

No preview of Bibata Void-Green

## Bugs

Bugs should be reported [here](https://github.com/KaizIqbal/Bibata_Extra_Cursor/issues) on the Github issues page.


## License and Terms

```Bibata Cursor SET``` Collection is available under the terms of the GPL-3.0 license See [`LICENSE`](https://github.com/KaizIqbal/Bibata_Extra_Cursor/blob/master/LICENSE) for details.

## Getting help

You can create a issue, I will help you.

## Contributions and Suggestions

Any suggestions for features and contributions to the continuing code masterelopment can be made via the issue tracker or code contributions via a ```Fork``` & ```Pull requests```.

OR

You give suggestions on _slack_ @ [#bibata-cursor](https://kaizkhatri.slack.com/messages/CCK84QYQ4/)

## Based On

Forked From Original [Bibata](https://github.com/KaizIqbal/Bibata_Cursor)

<p align="center"></br>
<a style="text-decoration: none;color:#009688;margin:0;padding:0 0 10px 0" href="https://github.com/KaizIqbal">
<span style="font-size:15px">Your Boy</span></br>
<span style="font-size:20px">Kaiz Khatri</span>
<h1 align="center">.^.</h1>
</p>
