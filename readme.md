
<h1 align="center">
  <br>Remote Tools for TouchDesigner<br>
</h1>

<div id="header" align="center">
  <img src="https://igalabs.net/assets/assets/images/tdremotetools/appicon.png" width="120" style="border-radius:25%">/>
</div>

<h4 align="center">Tools for working with <a href="https://derivative.ca/" target="_blank">TouchDesigner</a> on mobile devices</h4>

<p align="center">
  <a href="https://github.com/iga-labs/TD-Remote-Tools/releases"><img src="https://img.shields.io/github/v/release/iga-labs/TD-Remote-Tools"></a>
  <a href="https://github.com/iga-labs/TD-Remote-Tools/issues"><img src="https://img.shields.io/github/issues/iga-labs/TD-Remote-Tools"></a>  
</p>

<p align="center">
  <a href="#description">Description</a> •
  <a href="#downloads">Downloads</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#parameters">Parameters</a> •
  <a href="#roadmap">Roadmap</a> •
  <a href="#support">Socials</a> •
  <a href="#contributions">Support</a> •
  <a href="#license">License</a>
</p>


## Description

All-in-one tool (planned) for handling/controlling with TouchDesigner

Currently implemented functionality for remote control (or broadcasting) of the container and its settings in local network 

## Downloads

**TouchDesigner Component**
>[TDRemote.tox](https://github.com/iga-labs/TD-Remote-Tools/releases/latest/download/TDRemote.tox) COMP


**Android app** 
<!-- > **not yet released**, write directly to [me](https://t.me/confirmedancient) -->

> **not yet released**, [ALPHA TEST](https://play.google.com/store/apps/details?id=com.igalabs.tdremotetools)

<!-- <a href="https://play.google.com/store/apps/details?id=com.zhiga_stud.td_remote"><img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white"></a> -->

 **iOS app**
<!-- > **not yet released**, write directly to [me](https://t.me/confirmedancient) -->

> **not yet released**, [ALPHA TEST](https://testflight.apple.com/join/BpYeSkk8)

<!-- <a href="https://apps.apple.com/app/id6670328640"><img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white"></a> -->

## How To Use

**How to connect**

1. Place TD Remote.tox in your project

2. Select the network interface to which mobile device is connected - **Local address** parameter

3. Select the required container and place in the **Panel COMP** parameter

4. Click on the container that appears on the list of panels in the mobile application to connect

> If you are using multiple **TDRemote COMP**s in the same project, make sure that the **Port** parameter is differentfor all instances

---

**Usage moments**

> Swipe left from right side to open menu on panel page (in the app)

> Text selection in text fields is possible only with **Mouse** control type (in the app)

> Make sure that TouchDesigner computer and mobile device are not using VPN 



## Parameters

* **Local address** - `StrMenu` Network interface to which mobile device is connected
* **Port** - `Int` Connection port, must be unique for each instance 
  - **Local ip** - `read only` Same as **Local address**
  - **Machine name** - `read only` Сomputer name, displayed on the panel list
  - **Panel name** - `read only` Same as **Panel COMP**
  - **Status** - `read only` Current connection/error status
* **Panel COMP** - `COMP` Container selected that is going to be used for control
* **Audio CHOP** - `CHOP` Broadcast audio
* **Reset Sensors on Disconnect** - `Toggle` Resets all sensor values when disconnected from the panel
* **Reset Sensors** - `Pulse` Resets all sensor values
* **Scannable codes Max Lines** - `int` Maximum number of rows in the table of scanned codes
* **Clear Scannable codes** - `CHOP` Clear the table of scanned codes


## Roadmap

- [x] Container remote control
- [x] Container resize
- [x] Keyboard support (in test)
- [x] Scannable codes data sharing (QR, Barcodes, Aztec, Datamatrix, etc.)
- [x] InApp Kiosk mode
- [x] Sending data from device sensors
- [x] Onboarding
- [ ] Camera broadcasting
- [ ] Different broadcast protocols/quality
- [ ] Connection to the last panel at startup
- [ ] Multi-language
    - [x] English
    - [ ] German
    - [ ] Russian


## Support

Join our Telegram channel for quick communication and information about the project

<a href="https://t.me/+dqmj1kbrBnU3ZGFi"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a>
<a href="https://www.youtube.com/@iga_labs"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>

Direct mail: **support@igalabs.net**


## Сontributions

<!-- <a href=""><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white"></a> -->
<a href="https://www.patreon.com/iga_labs"><img src="https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white"></a>


## License
>You can check out the full license [here](https://github.com/iga-labs/TD-Remote-Tools/blob/main/LICENSE)

This project is licensed under the terms of the **MIT** license
