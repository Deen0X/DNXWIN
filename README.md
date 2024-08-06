# DNXWIN Project

![DNXWIN_AVATAR_c](https://github.com/Deen0X/DNXWIN/assets/3720302/3a44af6d-6a55-4b2e-85b6-9e823f769ca2)

## What is DNXWIN Project?
At first instance, i want to create my own version of "Windows Lite/tiny/etc" for use with my gaming devices (GPD WIN, WIN2, WIN3, WIN4, WINMAX, WINMAX2, Steam Deck, etc) that bring me the experience of windows, but without "extra" stuff that i don´t need.

After creating this windows, and testing it, i finally get the conclussion that this is not really what i want on my machines, or at least, not on all my devices.

There are some of them that are low on resources and they need a special windows with minimal services, etc, for bring resources to games. this may be the case of GPD-WIN and GPD-WIN2, but since GPD-WIN3/WINMAX there are enough resources for running games without the need of short services/programs on windows (because these programs or services really will not affect on general performance on gaming, so i decided to get another point of view about the way to install and use windows (and create an iso or it), so i point to optimize windows instead of eliminating services from the oiginal ISO.

With this in mind, i created a "BASE" Windows ISO, where i did "light" tweaks on it. These tweaks are based on my project [DNXDOSScript](https://github.com/Deen0X/DNXDOScript), where i divided these tweaks into two parts.

1- Regitry tweaks focussed on gain performance on a Windows installation.

2- Script that do more in-deep modifications on windows, disabling or deleting some components, etc.

So, on the main Windows ISO "BASE", i only applied the Registry level tweaks
After this, i included some basic software that i consider essential in any windows installation, and this is the list of some of these software:
- Autowall \* -> A small and light software for bring live wallpapers on windows.
- Common Runtimes and frameworks, such VC, .NET, etc.
- 7-Zip -> For general compressed file management.
- Notepad++ -> essential tool
- Google Chrome -> I think is the best choice, but if the user don´t want, simply can uninstall from control panel.
- Steam \*\* -> Most popular launcher.
- WizTree -> A small and quick tool for grahpical check disk usage

>[!NOTE]
>\* Really is not an essential software, but i like the impact of the iso on their first boot and see an animated wallpaper on the desktop. Of course this program can be stoped or removed if don´t like to the final user.
>
>\*\* I decided to include Steam because is the most popular library/launcher, and because the program update itself on each launch, so there is no problem really using an "old" version (in case the user is installing this iso on future), because steam always will be up to date.

There maybe other small programs included on the iso that i will try to keep this list up to date.

With the previous configuration of essential software, light tweaked iso and optimization (using the reg) i generated a BASE ISO for the main project. This ISO can be used on any computer for installing windows, but user will need to install their own drivers.
This BASE Project is called DNXWIN10 and come in two versions: PRO and HOME

## Extra Software Project

The iso come with [Extra Software](https://github.com/Deen0X/DNXExtraSoftware) Project.

This project born from previous versions of DNXWIN versions, where i included some useful stuff but not necessary all users will use. So i decided to "externalize" some parts, and allow to users to install "on demand".

The best example of this is the WSA (Windows Subsystem for Android), that adds near to 2GB extra size to the ISO, and even if the project is so interesting and useful (running android applications as native windows apps), not all users will use it really, so i create a way to easy install this with a simple click, that will download the project from their original repository on github, and install on the system (enabling needed components for running it)

So, taking this as a base idea, i generated a complete menu for more software with the same philosophy. Download from original source (when possible) and install on the system. This way i'm not including the software on the ISO and allow to user to install what want on their windows system.

## DNXRAMDrive Project

The ISO come with the [DNXRAMDRive](https://github.com/Deen0X/DNXRamDrive) Project included. This script basically will launch if the ISO is installed as Windows To Go (Win2Go) on a MicroSD or external drive. It will check the write speed of the system (the first time the system runs) and, depending on the media speed, configure a RAMDrive for use on the system, and point the TEMP directories there, and CACHE forlders from Chrome and Edge. With this the system gain in performance because avoid to write on the slow media, but at cost of less ram available.


## EDITIONS
Note that all editions will be uploaded to Telegram, because is the best way i found to share this project without worry about bandwith limit.

* [![image](https://github.com/Deen0X/DNXWIN/assets/3720302/483cac8c-1831-4744-87fe-d44ea81dc7b8) BASE/GENERIC Edition](https://github.com/Deen0X/DNXWIN/tree/main/BASE_GEN_EDITION) -> for any device. Not drivers or software specific included.

* [![image](https://github.com/Deen0X/DNXWIN/assets/3720302/38e0d5c1-91ec-4fb8-b291-75380dc523eb) GPD-WIN](https://github.com/Deen0X/DNXWIN/tree/main/GPDWIN)

* [![image](https://github.com/Deen0X/DNXWIN/assets/3720302/c295a2ee-4f85-4923-9e28-0f4252460baa) GPD-WIN2](https://github.com/Deen0X/DNXWIN/tree/main/GPDWIN2)

* [![image](https://github.com/Deen0X/DNXWIN/assets/3720302/336ad51a-0595-4d9a-be44-0aa305af0d53) GPD-WIN3](https://github.com/Deen0X/DNXWIN/tree/main/GPDWIN3)

* [![image](https://github.com/user-attachments/assets/6b24fd06-e331-44dd-81f8-fb297cd98c2b) GPD-WINMINI](https://github.com/Deen0X/DNXWIN/tree/main/GPDWINMINI)

* [![image](https://github.com/user-attachments/assets/55eaef37-f99b-46d3-a7e7-aa387a56b1fb) GPD-WINMAX](https://github.com/Deen0X/DNXWIN/tree/main/GPDWINMAX)

* [![image](https://github.com/Deen0X/DNXWIN/assets/3720302/385ed081-feee-497f-ab5a-cea44dfdc4e3) STEAM DECK](https://github.com/Deen0X/DNXWIN/tree/main/STEAMDECK)
