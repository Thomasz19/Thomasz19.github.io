---
title: "Digital Monster Pet Embedded System"
collection: publications
category: manuscripts
permalink: /project/2024-11-17-digital-monster-pet
excerpt: 'An interactive embedded system simulating a virtual pet with emotional states, health tracking, and real-time responses using STM32 microcontroller.'
date: 2024-11-17
venue: 'EGR 326 Final Project, Grand Valley State University'
#slidesurl: ''
paperurl: 'http://academicpages.github.io/files/EGR326Project.pdf'
citation: 'Thomas Zoldowski, Emmett Topp. (2024). "Digital Monster Pet Embedded System." <i>GVSU EGR 326 Final Report</i>.'
---

The Digital Monster Pet is an autonomous embedded system built on the STM32F446 Nucleo board that simulates a virtual pet capable of reacting to user interaction, tracking its health, and expressing emotional states. The system integrates multiple hardware peripherals, including a graphic LCD, Hall effect sensor, proximity sensor, real-time clock (RTC), rotary encoder, stepper motor, and speaker.

Users interact with the pet by petting it (via magnet and Hall sensor), feeding it with a button, or setting its internal clock through a menu-driven interface. The LCD displays animated emotional states like Happy, Hungry, Sleeping, and Content, while system logic manages health degradation, alerts, and memory retention across power cycles using EEPROM and RTC.

The project emphasized real-time behavior, user interface design, sensor integration, and power-conscious microcontroller programming. It demonstrated full-cycle embedded system design from hardware wiring to software logic and verification, all within budget and safety constraints.
