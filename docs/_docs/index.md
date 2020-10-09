---
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html
---

Welcome to the MCGalaxy documentation.

## About
MCGalaxy is a fully-featured and customisable **[ClassiCube](https://classicube.net) Server Software** based on MCForge/MCLawl.

## Installation
### Release
Download the latest MCGalaxy release [from here](https://github.com/UnknownShadow200/MCGalaxy/releases).
* Windows: You need to install .NET framework 4.0. Windows 8/10 already have this included.
* Linux/macOS: You need to install the [Mono framework](https://www.mono-project.com).

Run **MCGalaxy.exe** for a graphical interface, or run **MCGalaxyCLI.exe** for command line only.

### Compiling  yourself
In order to compile MCGalaxy, you will need a C# compiler software. E.g, [Visual Studio](https://visualstudio.microsoft.com/) or [SharpDevelop](https://github.com/icsharpcode/SharpDevelop).
1. Open **MCGalaxy.sln**
2. Compile the solution*

*Note that on some computers **GUI/Window/Window.resx** is blocked. You may need to right-click on the file and click on **properties**. From there you will be able to unblock it.

## Getting started
### Joining your server
Run **MCGalaxy.exe** or **MCGalaxyCLI.exe** firstly. You'll see something like:
![opt3](https://user-images.githubusercontent.com/6509348/60258728-0e05bd00-9919-11e9-9ae8-f1262719cd50.png)

If you are signed in to classicube.net, you can copy this URL straight into your web browser and start playing.

#### Joining from the desktop client
Click **Direct connect** at the main menu.
![opt1](https://user-images.githubusercontent.com/6509348/60258725-0e05bd00-9919-11e9-8f8c-fbbdc52f04f9.png)

Type your username into *Username*, ```127.0.0.1:25565``` into *IP:Port*, and leave *Mppass* blank. Then click **Connect**.
![opt2](https://user-images.githubusercontent.com/6509348/60258727-0e05bd00-9919-11e9-890d-5c25cdf385c1.png)

#### Making yourself owner
After joining, you will want to rank yourself owner so you can use all commands.

Type ```/rank [your account] superop``` into the bottom text box, then press Enter.

![opt4](https://user-images.githubusercontent.com/6509348/60258729-0e9e5380-9919-11e9-921d-ea7e0c4365af.png)


### Letting others join your server
#### LAN players
You need to find out your LAN/local IP address.
*  Windows: Type ```ipconfig``` into **Command Prompt**. Look for ```IPv4 address``` in the output.

To join from a web browser, add ```?ip=[lan ip]``` to the server's URL.\
(e.g. http://www.classicube.net/server/play/d1362e7fee1a54365514712d007c8799?ip=192.168.1.30)

To join from the desktop client, **Direct connect** to ```[lan ip]:25565``` instead. (e.g. ```192.168.1.30:25565```)


#### Across the internet
You need to port forward your router. Players can then join by entering the server URL into their web browser.

For the desktop client:
* Click **Sign in**.
* Type/paste the hash (e.g. ```d1362e7fee1a54365514712d007c8799```) into the *classicube.net/server/play* text box.
* Click **Connect**.


#### Showing your server in the classicube.net server list
Click **Settings** in the MCGalaxy window, then tick the **Public** checkbox. Then click **Save**.

This makes your server appear in the server list on classicube.net and in the desktop client.

### Copyright/License
See LICENSE for MCGalaxy license, and license.txt for code used from other software.
