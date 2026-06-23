# Galaxy XR Keep Awake

[English](README.md) | [한국어](README.ko.md) | [日本語](README.ja.md)

Galaxy XR Keep Awake is a small companion app made to make sleeping in VRChat more convenient while wearing Galaxy XR.

It watches for the Galaxy XR inactivity warning and helps keep the headset active during intentional use.

## Install With Windows Installer

1. Download `GalaxyXRKeepAwakeInstaller.exe` from the latest [Releases](https://github.com/zeee2/gxr-keep-awake/releases).
2. Run the installer on a Windows PC.
3. Choose your language.
4. Follow the Galaxy XR preparation screen.
5. Connect Galaxy XR to the PC with a USB cable.
6. Allow USB debugging inside the headset when prompted.
7. Press the install button in the installer.
8. On Galaxy XR, open Accessibility settings and enable Galaxy XR Keep Awake.

You do not need to manually install APK files or ADB.

## After Installation

Keep the app enabled in Accessibility settings.

The app can stay in the background after setup. Please do not force close it while using the keep awake feature.

## Notes

This app is not an official Samsung, Google, VRChat, SteamVR, or Virtual Desktop app.

Galaxy XR uses OLED panels. Long sessions or repeated static display use may cause burn-in. Please use this app at your own risk. I am not responsible for burn-in or display damage.

## Development Note

While making this app, I found that Samsung had heavily restricted accessibility permissions while modifying the OS.

Because of those restrictions, this release uses a compatibility workaround so the app can be enabled in accessibility settings. It works as of 2026-06-22, but a future software update may block it.

## Credits

- Developer: JINDESU ([X](https://x.com/jindesu_vr), [GitHub](https://github.com/zeee2))
- Big support: ilsubyeega ([GitHub](https://github.com/ilsubyeega))
