# Windows Subsystem for Linux

This is a feature in windows 10+ that lest you install and run Linux programs and utilities on windows. We'll be using 
to set up ubuntu.

- [Enabling WSL](##Enabling WSL)
- [Installing Ubuntu](##Installing Ubuntu)

## Enabling WSL
To run WSL you need to firstly enable it as a feature on windows; then install and run the app from the microsoft store.

To enable WSL on windows 10+:
1. Open Settings
2. Click on Apps
3. Under related settings, click Programs and Features
![](https://www.windowscentral.com/sites/wpcentral.com/files/styles/large/public/field/image/2019/12/apps-features-programsfeatures-option.jpg)
4. Click Turn Windows Features on or Off on the left pane:
![](https://www.windowscentral.com/sites/wpcentral.com/files/styles/large/public/field/image/2019/12/controlpanel-turn-windows-features-option.jpg)
5. Scroll Down and check "Windows Subsystem for Linux" option.  
![](https://www.windowscentral.com/sites/wpcentral.com/files/styles/large/public/field/image/2019/12/enable-windows-subsystem-linux-windows-10.jpg)
6. Press OK and Restart your computer.

## Installing Ubuntu

1. Open the Microsfot store (windows key and type "Microsoft Store")
2. Search for "Ubuntu". You want to install the version that does not have a version number next to it (it'll have the most reviews)
3. Install it, and press Launch. It will take a moment to install.
4. An on-screen pop up will appear, create a username, and a password. I advise "password" as a password; we will not be hosting web servers. If you decide for a secure password write it down, you can recover without it but it's a pain.
5. Repeat thje password and press confirm. You should see something like this once finished:
![](https://www.windowscentral.com/sites/wpcentral.com/files/styles/large/public/field/image/2019/12/setup-ubuntu-wsl-windows10.jpg)

Courtesy of [windowscentral](https://www.windowscentral.com/install-windows-subsystem-linux-windows-10)