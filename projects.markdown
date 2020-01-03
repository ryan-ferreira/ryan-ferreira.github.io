---
layout: page
title: Projects
permalink: /projects/
---

# My own Minecraft launcher

I'm working on my own Minecraft launcher for Android.

It should be able to download Minecraft - Pocket Edition v0.13.2 Alpha directly from Google Play Store and launch it without installing. Obviously, you have to buy Minecraft.

I chose v0.13.2 Alpha because it has not JSON-based UI and still has debug symbols, which makes modding easier. Soon I want to add every features from the recent versions through modding.

**To do list:**

- [ ] Add Google Play API to download Minecraft.
- [x] Extract Minecraft libraries and assets to app's data folder.
- [ ] Get the app to launch Minecraft without having it installed.

# Multinomial theorem app

I'm also working on a Multinomial theorem app for Android and a web version.

According to [Wikipedia](https://en.wikipedia.org/wiki/Multinomial_theorem), the multinomial theorem describes how to expand a power of a sum in terms of powers of the terms in that sum.

I want the app to instantly provide the expansion of the input multinomial.

This project should use [Boost C++ libraries](https://www.boost.org/) for factorial functions and more.

**To do list:**

- [ ] Port Boost C++ libraries to Android.
- [ ] Make the app user interface.
- [ ] Able to expand the multinomial.