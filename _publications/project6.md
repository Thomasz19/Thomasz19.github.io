---
title: "Frog Flap FPGA Game Emulator"
collection: publications
category: projects
permalink: /project/2025-03-20-frog-flap
excerpt: 'An FPGA-based game emulating Frog Flap with HDMI output, sprite animation, collision detection, and audio using a Spartan-7 board.'
date: 2025-03-20
venue: 'EGR 426 Project 2, Grand Valley State University'
slidesurl: ''
paperurl: ''
citation: null
---

Frog Flap is a real-time game emulator designed on a Spartan-7 FPGA, inspired by the Frog Flapper game from the Wario Party series. The system produces 640x480 HDMI video output by generating VGA signals internally and converting them to HDMI using a Real Digital HDMI IP core.

Game elements, including the background and character sprites, were managed through custom ROM-based image maps. Backgrounds were upscaled for performance, while clouds and objects were generated and animated using an LFSR for randomized behavior. Modules included a merger unit to layer sprites, a collision detection engine, and a sprite-based character controller.

Additional features included real-time score display, a basic audio engine using sine table generation, and multiple audio tracks selectable via onboard switches. This project demonstrated advanced digital design, hardware-accelerated graphics, and the use of IP cores and ROMs for animation, audio, and gameplay logic.
