---
layout: en/post
title: "New control board for CoderBot"
subtitle: "New motor control and I/O board for CoderBot."
splash: "blog/coderbot_control_board_v5_splash.png"
date: 2020-05-08 10:00:00
category: blog
tags: news
author: CoderBot
language: en
---

![coderbot_control_board_v5]({{site.baseurl}}/img/blog/coderbot_control_board_v5.jpg)

CoderBot's code board computer is the Raspberry Pi, which has a custom motor control board mounted on it (referred to as an RPi "hat") to connect the Raspberry Pi to sensors and actuators.

![coderbot_control_board_v5]({{site.baseurl}}/img/blog/coderbot_control_board_v5_design.png)

We are pleased to introduce a completely redesigned motor control "hat" that expands the input and output options available to CoderBot programmers. The new board offers several new features:

- Support for two motor digital encoders
- Integrated inertial platform (MPU) with accelerometer, gyroscope, and compass
- Integrated atmega328p to provide an additional 12 digital GPIO (input/output) and 2 analog inputs
 -Support for an additional ultrasonic sensor

The digital encoders are used by the CoderBot software to improve directional movement by adjusting motor power through a PID algorithm.

The MPU can be utilized in the blockly programming blocks and can be used as input in user-created programs.

The atmega328p inputs and outputs are also integrated in the software, and can be accessed through special blocks to read or write to the additional GPIOs.

In addition to the enhanced features, the new board also has a more secure mechanical design, it has the standard size for Raspberry Pis and has holes on the edges for secure mounting on top of the Raspberry Pi.