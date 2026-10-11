---
layout: single
title: Projects
permalink: /projects/
---

Here is a curated list of some interesting or useful personal projects of mine. Check out my [GitHub](https://github.com/vesuvisian) for everything I've pushed and the latest updates.

## amr2mqtt
This reads utility meter data with a low-cost software-defined radio and publishes it to MQTT for use with Home Assistant. It is essentially a Python service that conveniently wraps _rtl_tcp_ and _rtlamr_.
* [Repo](https://github.com/vesuvisian/amr2mqtt)
* [Blog Post](https://vesuvisian.com/2026/08/10/automatic-meter-reading/)

## hires-rs
This is a Rust/Burn port of the HiRes algorithm. It detects through-hole resistors in an image, finds their color bands, and decodes those colors into the resistance value in ohms. It can run via the command line, as a GStreamer element, and on the web.
* [Repo](https://github.com/vesuvisian/hires-rs)
* [Live Demo](https://vesuvisian.com/hires-rs/)

## jigsaw
This is a simple jigsaw puzzle generator and solver. It can be run both as a desktop app and on the web.
* [Repo](https://github.com/vesuvisian/jigsaw)
* [Live Demo](https://vesuvisian.com/jigsaw/)

## radish
This is a Python parser and custom ESPHome component for listening to and controlling Daikin/Amana/Goodman HVAC systems locally.
* [Repo](https://github.com/vesuvisian/radish)
* [Documentation](https://vesuvisian.com/radish/)
* [Blog Post](https://vesuvisian.com/2026/10/06/radish/)

## theremin
This is a "virtual" theremin. A real theremin uses antennas to sense hand position through changes in capacitance; this one uses Google MediaPipe to track body and hand positions and generates tones from their relative locations. It works entirely in the browser and even with multiple performers.
* [Repo](https://github.com/vesuvisian/theremin)
* [Live Demo](https://vesuvisian.com/theremin/)
