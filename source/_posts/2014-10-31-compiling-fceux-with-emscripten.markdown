---
layout: post
title: "Compiling fceux with Emscripten"
date: 2014-10-31 15:29:13 +0800
comments: false
categories: emu, emscripten
---

I'm trying to compile fceux with Emscripten to see if it's able to run a nes emulator within a mobile browser.
Which means without webGL support.

I tried [RetroArch](https://github.com/libretro/RetroArch) with [fceu-next](https://github.com/libretro/fceu-next), but that means I had to deal with 2 code bases. I decided to try the original [fceux](http://fceux.com/).

After a few days of trial and error, it finally builded successfully.
It seems to run on destop browsers(Firefox, Chrome, Safari), but unfortuanlly the framerate is too low on mobile ones(Safari & Chrome on iOS) and there's no sound.

Repo: [fceux.js](https://github.com/kyle-lu/fceux.js)

End of the story :(