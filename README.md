
# 🍎 Hackintosh on ThinkPad E330

Hackintoshing... ahh, it was only a matter of time before I made my own. Here is my try (not fully successful) on putting macOS on Lenovo ThinkPad E330.

If you want just the EFI, jump straight to [Lenovo ThinkPad E330 EFI and support](https://github.com/AdamBru/Hackintosh-ThinkPad-E330#%EF%B8%8F-lenovo-thinkpad-e330-efi-and-support) section. However, you're more than welcome to read my story.

![macOS High Sierra on ThinkPad E330](https://github.com/user-attachments/assets/f03a9cd2-20da-46bb-b6ff-5e269e7bebd6)
![macOS Bootloader](https://github.com/user-attachments/assets/8f11618a-f322-4dd0-8bec-934e78280860)

## 💬 r/Hackintosh

Special NOT thanks to r/Hackintosh mods for not accepting my post there. In fact, they didn't even review my post I tried posting twice. That's not cool guys 😕.

  
## ⚠️ Required disclaimer (and my take on it)

Okay, so let's get over with this stuff I have to say for "legal" reasons.
Do not treat this as a guide or a ready-to-go solution. Please go and read about Hackintoshing on [Dortania's OpenCore Offifcial Guide](https://dortania.github.io/OpenCore-Install-Guide/). (Hackingtoshers are for some weird reason obsessed with that you ***must*** learn from this process. In my opinion, on the other hand, if you want to, you should be allowed to use all the resources Internet provides, such as: ready EFIs for your specific computer/laptop, great tools like [OpCore Simplify](https://github.com/lzhoang2801/OpCore-Simplify) 💖 or any other easy way to get macOS running on your hardware.)

Welcome all the "Pro" Hackintoshers! Here, throw your stone at me!

![](https://pbs.twimg.com/media/EVxQOFeWoAAwtWw.jpg)


## 💻 Laptop config

| **Category** | **Component**                                      |
|--------------|----------------------------------------------------|
| **Model**    | Lenovo ThinkPad Edge E330                          |
| **CPU**      | Intel Core i3-2370M (Sandy Bridge)                 |
| **RAM**      | 2x4GB                                              |
| **GPU**      | Intel HD Graphics 3000                             |
| **Chipset**  | Intel HM77                                         |
| **Disk**     | 250GB GOODRAM SSD                                  |
| **OSes**     | Dualbooting Windows 10 / macOS High Sierra 10.13.6 |
| **WLAN**     | Intel Centrino Wireless-N 2230 BGN                 |

## 🗂️ Lenovo ThinkPad E330 EFI and support

This repository contains (almost) all the files needed to run macOS High Sierra 10.13.6 on Lenovo ThinkPad E330. The only thing you need to get is macOS recovery image, which you can get in [Dortania's Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install-recovery.html) (with Python) or through my beloved [OpCore Simplify](https://github.com/lzhoang2801/OpCore-Simplify), both ways reliable and secure, directly from Apple. 
Feel free to reach out to me and ask any questions on it. We will try to solve together your problem.
[<kbd> Email me </kbd>](mailto:werterowski334@int.pl?subject=Hackintosh%20ThinkPad%20E330) (my fake email because I was too scared to give out my real one)

## 🛠️ Problems and how you can help me

![Wi--Fi](https://img.shields.io/badge/Wi--Fi-not%20working-red?logo=wifi)
![macOS High Sierra](https://img.shields.io/badge/macOS-High%20Sierra%2010.13.6-yellow?logo=apple&logoColor=white)

Well, there are some issues with this project... First of them being not able to use Wi-Fi in macOS 😕. Kinda sucks but you can still use ethernet (Bluetooth still works, tho 🤔).
The other issue is that macOS High Sierra is the highest version this CPU officially supports. I tried using OpenCore Legacy Patcher to update my system to Ventura but it completely messes up my EFI and no OS would boot.

If you know anything that would solve either of these problems, please [<kbd> Email me </kbd>](mailto:werterowski334@int.pl?subject=Hackintosh%20ThinkPad%20E330). I'll be extremely thankful for any hints 🫶.

## 🎨 BONUS: hydrodipping

Also, check out my first attempt at hydrodipping I did with my team! I think it looks really cool. I also hydrodipped Logitech wireless mouse, as you can see on the picture below.

![Hydrodipped ThinkPad and mouse](https://github.com/user-attachments/assets/35527a56-54f1-44fb-b56f-c31d898d3a79)

## 🙌 Credits

I'm not good at writing READMEs, but that will do, I guess 😅.

OpCore Simplify and of course Me, Myself and I.
AdamBru &copy; VII 2025
