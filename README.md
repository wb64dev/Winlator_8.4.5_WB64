<p align="center">
	<img src="logo.png" width="376" height="128" alt="Winlator Logo" />  
</p>

![Total Downloads](https://img.shields.io/badge/100k+-wb64?style=for-the-badge&logo=github&logoColor=white&logoSize=14&label=Total%20Downloads&labelColor=gray&color=66BA32)

# Winlator

Winlator is an Android application that lets you to run Windows (x86_64) applications with Wine and Box86/Box64.
![WINE](https://img.shields.io/badge/Wine%20Is%20Not%20an%20Emulator-F00000)

# Installation

1. Download and install the APK (Winlator_8.5.5.apk) from __[GitHub Releases >> DOWNLOAD <<](https://github.com/wb64dev/Winlator-WB64/releases)__
2. Launch the app and wait for the installation process to finish

# Useful Tips

- If you are experiencing performance issues, try changing the Box64 preset to __`Performance (Gaming Mode)`__ in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing __`Wine Mono`__ found in Start Menu -> System Tools.
- If some older games don't open, try adding the environment variable __`MESA_EXTENSION_MAX_YEAR=2003`__ in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
- To __speed up the installers__, try changing the Box64 preset to __`Intermediate (Speed-up Installer)`__ in Container Settings -> Advanced Tab.
- To __improve stability__ in games that uses Unity Engine, try changing the Box64 preset to __`Stability (Unity Games)`__ or in the shortcut settings add the exec argument __`-force-gfx-direct`__.

# Information

Results can vary based on the device used, environmental conditions, and other factors, such as simultaneous processing, and different processor capabilities. 

(Freedreno and Turnip are only compatible with Adreno 610 and above with exceptions like 710, 642L, etc)

# Credits and Third-party apps
- Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- PRoot ([proot-me.github.io](https://proot-me.github.io))
- Mesa (Turnip/Zink/VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- VKD3D ([gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d))
- D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))

Many thanks to [ptitSeb](https://github.com/ptitSeb) (Box86/Box64), [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/) (Turnip), [alexvorxx](https://github.com/alexvorxx) (Mods/Tips) and others.<br>
Thank you to all the people who believe in this project.
