---
title: "Local Media Server"
excerpt: "How to listen to a music library on a low-storage device"
sidebar:
  - title: "Software Kitten"
    image: https://placekitten.com/200/600
    image_alt: "logo"
    text: "This is a virtual kitten. Please enjoy."
---

Recently, I managed to break my phone (water damage from being in my pocket while it was raining), and had to switch to my old, retired device, which only has 32GB of storage. And yes, I mean storage, not RAM. With less than half of that available after formatting, installing a custom ROM and the Play Store, as well as F-Droid and some specialty apps, there would be no space for a music library.

Thus, I have my Raspberry Pi 3A+, connected to a M.2->USB hard drive adapter with a 512gb hard drive. Installed is Raspbian Lite, ZeroTier (for connectivity across devices and while on restricted networks), PiHole (as personalDNSFilter and ZeroTier both rely on a VPN connection on Android, so the former can't be used in favor of the latter), and Jellyfin, for the actual music.