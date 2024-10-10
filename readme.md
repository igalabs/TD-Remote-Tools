
<h1 align="center">
  <br>TouchDesigner Remote Tools<br>
</h1>

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
  <a href="#socials">Socials</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>


## Description

All-in-one tool (planned) for handling/controlling with TouchDesigner

Currently implemented functionality for remote control (or broadcasting) in local network of the container and its settings


## Downloads

**TouchDesigner Component**
>[TDRemote.tox](https://github.com/iga-labs/TD-Remote-Tools/releases/latest/download/TDRemote.tox) COMP


**Android app** 
> **not yet released**, write directly to [me](https://t.me/confirmedancient)

<!-- <a href="https://play.google.com/store/apps/details?id=com.zhiga_stud.td_remote"><img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white"></a> -->

 **iOS app**
> **not yet released**, write directly to [me](https://t.me/confirmedancient)

<!-- <a href="https://apps.apple.com/app/id6670328640"><img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white"></a> -->

## How To Use

**How to connect**

1. Place TD Remote.tox in your project

2. Select the network interface to which mobile device is connected - **Local address** parameter

3. Select the required container and place in the **Panel COMP** parameter

4. Click on the container that appears in the list of panels in the mobile application to connect

> If you are using multiple **TDRemote COMP**s in the same project, make sure that the **Port** parameter is differentfor all instances

---

**Usage moments**

> Swipe left from right side to open menu on panel page (in the app)

> Text fields text selection is possible only with **Mouse** control type (in the app)

## Parameters

* **Local address** - `StrMenu` Network interface to which mobile device is connected
* **Port** - `Int` Connection port, must be unique for each instance 
  - **Local ip** - `read only` Same as **Local address**
  - **Machine name** - `read only` Сomputer name, displayed in the panel list
  - **Panel name** - `read only` Same as **Panel COMP**
  - **Status** - `read only` Current connection/error status
* **Panel COMP** - `COMP` Container selected for control
* **Audio CHOP** - `CHOP` Broadcast audio


## Roadmap

- [x] Container remote control
- [x] Container resize
- [x] Keyboard support (in test)
- [ ] Different broadcast protocols/quality
- [ ] Multi-language Support
    - [x] English
    - [ ] Russian
- [ ] Gyroscope, accelerometer data sharing
- [ ] Camera sharing


## Socials

<a href="https://t.me/+dqmj1kbrBnU3ZGFi"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a>
<a href="https://www.youtube.com/@iga_labs"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>


## Support

<!-- <a href=""><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white"></a> -->
<a href="https://www.patreon.com/iga_labs"><img src="https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white"></a>


## License
>You can check out the full license [here](https://github.com/iga-labs/TD-Remote-Tools/blob/main/LICENSE)

This project is licensed under the terms of the **MIT** license
