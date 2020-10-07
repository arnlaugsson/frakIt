---
title: Alexa, turn on Broadway!
date: "2020-10-07"
description: "Describing how I got started with smart appliances and home automation."
layout: layouts/post.njk
tags: ['smarthome']
---

It started with some smart plugs a while back. I bought a Sonos One and got around region limitations, so I was able to talk to Alexa. Then I picked up a few (I think two to start with) smart plugs shipped from Ali Express. I started controlling lights via Scenes and using my voice. But I wanted more, and colored lights looked nice. So naturally, I bought my first set of Hue lightbulbs (and a hub and a switch).

> "Alexa, turn on Broadway."

My older daughter's bedroom had a desk with a mirror and surrounding lights called Broadway. "Alexa, turn on Broadway" would trigger the makeup lights, which always seem amusing.

At some point, I figured out my TV (Phillips Ambilight) was able to control some of the lights, so I bought more and put Hue bulbs in most of my living space. Then the kids' rooms and our bedroom. And then a Phillips Hue Go lamp to replace my sunlight alarm clocks. During this, I also got a HomePod. But my smart plugs weren't supported by Siri. So I had full support on Alexa, but only partially on Siri.

It bothered me.

So when I moved earlier this year, I knew I wanted to go further to fix this if possible. I had a Raspberry Pi 4 that I had used for programming on the iPad. I decided to try a setup of [Home Assistant](http://home-assistant.io/). For me, Home Assistant now takes care of communicating with devices that Apple HomeKit doesn't support natively. Besides, by using a [Raspbee II](https://phoscon.de/en/raspbee2), I avoid having to run multiple Bridges.

So far, I have connected an IKEA Trådfri lightbulb, Honeywell Mijia Smoke detectors, Aqara temperature, humidity sensors, and Water Immersing sensors. It's working great.

But I've only scratched the surface. The next steps will be scripting and automation, and later controlling the heat in the apartment. I might do a more thorough walkthrough of my current setup later.
