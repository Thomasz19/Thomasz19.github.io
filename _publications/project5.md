---
title: "Shot Counter with Custom PCB and Embedded System"
collection: publications
category: manuscripts
permalink: /project/2025-04-18-shot-counter
excerpt: 'A compact shot tracking device built with a custom 6-layer PCB, STM32 microcontroller, piezo knock sensor, and OLED display.'
date: 2025-04-18
venue: 'EGR 436 Design Project, Grand Valley State University'
#slidesurl: ''
#paperurl: ''
citation: 'Thomas Zoldowski, Lucas Meyers. (2025). "Shot Counter with Custom PCB and Embedded System." <i>GVSU EGR 436 Final Report</i>.'
---

The Shot Counter is a low-power, embedded system designed to detect and display firearm shot counts using a piezoelectric knock sensor and OLED screen. Powered by a 300mAh Li-ion battery, the device operates for over 7 hours and is built around the STM32F103CBT6 microcontroller.

Key features include a split-color I2C OLED for displaying count and menu options, dual tactile buttons for navigation, and support for UART, I2C, and SPI communication protocols. The custom 6-layer ENIG PCB was designed in Altium and included robust power and signal layout separation. A lightweight PLA enclosure with M-LOK mounting enabled field use and secure attachment.

This project emphasized embedded firmware development, PCB manufacturing, and power-conscious design. Lessons learned included improvements for sensor quality, display visibility in sunlight, and hardware debug accessibility, providing a foundation for future commercial refinement.
