# Project-ocuhome2016

## ⚠️ IMPORTANT INFO ⚠️

First off, I am not affiliated with Meta or Reality Labs (originally Oculus VR / Oculus) and I do not condone the act of just, and I quote, "Stealing code for the act of piracy." I'm doing this for preservation's sake.

> One more thing for devs who use this: I recommend installing the editor ~~5.4.3p4 or the latest Unity 5 LTS release.~~ **Use the editor its asking for.** The SDK is simple to find, and plus recovering this stuff takes a hot min. Ok, enough yapping, just getting this out of the way. All the setup links are low, low, low, low, low, low, low, low.

## About

This is my direct port of the original Oculus Home from 2016 (specifically version `1.20.0.466754`). It’s basically a Unity game, so I just ripped it and restored all the scripts. It’s fully open source and can be ported to all Quest devices. The PCVR version can be used on any VR headset that can run Revive and/or SteamVR.

<details>
<summary>How It Works</summary>

#### How I Made It

I got Unity Hub and installed the latest version of Unity 5 LTS. I asset-ripped a version of Oculus Home (because it's just a Unity game). Unlike **Meta Horizon OS**, it's not baked directly in. That’s why it was mostly separate from [**Oculus Dash**](https://developers.meta.com/horizon/documentation/native/pc/dg-dash/), unlike Horizon OS where it *is* the OS (kinda).

So I ripped the project, got Unity, recovered all the scripts, and fixed the shaders. That allowed me to port it to most Oculus, PCVR, Pico, and even the DK1/2 headsets (future me will prove me wrong).

</details>

## Supported Devices

<details>
<summary>Oculus / Meta Quest</summary>

- DK1 / DK2 (Depends)
- Oculus Rift Family  
  - CV1 without touch controllers (may be lackluster)  
  - CV1 with touch controllers (full control)
- Rift S (Should be fine)
- Gear VR (not supported)
- Oculus Go (possibly; may need to look like a PS1 game)
- Meta Quest 1 (may resemble a PS2 game, but better than Go)
- Meta Quest 2 (Should work fine)
- Quest Pro (Should have great performance)
- Meta Quest 3 Family (Should work fine; supports higher texture resolution)

</details>

<details>
<summary>SteamVR Headsets</summary>

All SteamVR headsets are supported, including:

- Valve Index  
- HTC Vive  
- [**Oculus Link Devices**](https://www.meta.com/help/quest/140991407990979/?srsltid=AfmBOork6S-Rplz3UCZth5N3rBtkyAOza77iJfAfzbKAcfS_QaY_jyqH)  
- Custom DIY headsets
- [Headsets Running Revive](https://github.com/LibreVR/Revive)

This project is designed with PCVR in mind, so support should be excellent.

</details>

</details>

<details>
<summary>How to setup for your system</summary>


  # Windows
  1. Get the zip file and extract it
  2. Locate the installer exe
  3. Do the question and get the app installed
  4. Run the app
  5. Make sure that your headset has [Revive](https://github.com/LibreVR/Revive) and [Oculus Link](https://www.meta.com/help/quest/140991407990979/?srsltid=AfmBOork6S-Rplz3UCZth5N3rBtkyAOza77iJfAfzbKAcfS_QaY_jyqH)
  6. Put on your rift or quest and enjoy your new home! (or old, or revised, idk)

 ## Android 
 
 1. Get the APK file for your system in the releases tab and make sure it has "Quest -----", not Rift - or Revive.
 2. Make sure you have [Sidequest](https://github.com/SideQuestVR/SideQuest/releases/download/v0.10.42/SideQuest-Setup-0.10.42-x64-win.exe) and a [Oculus Developer Account](https://developers.meta.com/horizon/documentation/native/android/mobile-device-setup/)
 3. Sideload the Apk that you have onto your headset. It wont be in your standard "Apps" folder in horizen os, you have to go to Unknown Resources to open it. it will be called "Ocuhome 2016" or "Oculus Home" depending on your version.
 4. Continue with the setup steps and boom!
</details>
