---
title: "Polardeck"
github: "https://github.com/henkers2011/Polardeck"
description: "This is a weather satellite ground station that operates off-grid and works with a RPi 3B+ with a custom built Power+GPS+RTC HAT. It has a custom built 3D printed RF-shielding clamshell case, retractable tripod V-dipole pod, and offline Leaflet.js GIS weather and ice map and weather prediction."
created_at: "2026-11-25"
total_time: "4.5h"
---

## November 27, 2026: Learned how radios work
___
I wanted to know the science behind how radios work before I actually decide on the antenna setup for the project. Here are some of the interesting things that I learned during research!
- I learned that radio waves that are transmitted are just electromagnetic waves, and antennas kind of absorb the waves at the frequency that they were broadcast at.
- The radios can broadcast different kinds of waves that represent different sounds, and the same electromagnetic waves are what let us see colour, use x rays, etc.
![](https://fabricate.hackclub-assets.com/3f6a45c1eecc944ce43bbdaa7ab5da10ea8c2e9d9235c83da5574addec00b15e/image-png/image.png)

- The length of the antenna dictates the frequency of the waves.
![](https://fabricate.hackclub-assets.com/eaccbba34c3edf5f92a007ad9e167cd79e251640808f97a806e295de3d2598ce/image-png/image.png)
**Total time spent: 1.5h**


## November 26, 2026: More PiHAT Research
---
I have decided on the PiHAT setup; I will be doing a base one with power management and some other basic parts as well as a second board on top with a built in mechanical keyboard and trackball that will screw in to the case and connect to the main lower PiHAT. 
![](https://fabricate.hackclub-assets.com/9dd23610796cf5b45e42551bf25dfa36a78d3cb51e3e2a374ebd4a315346997b/image-png/image.png)
(Image is not to scale)
Having most of the case open also allows more passive cooling which will lead to better performance.
**Total time spent: 1.5h**



## November 25, 2026: Startup research

I did some research on cyberdecks, the hardware and software that will be necessary for my  project, and on how realistic this kind of project really is.  I found that this will be a lot of work, but this is a project that I could realistically design, code, and ship, which is exciting. 

-RF shielding: I learned that if I don't shield all of my computer stuff inside of the case it will interfere with the antenna and cause a blurry(er) image.
-The sensors and equipment needed on the cyberdeck (which I have named Polardeck) for it to do it's mission. I will use a little chip that has GPS, a thermometer, barometric preassure, etc. that is part of what is looked at for estimating future weather.
Satellites: Which ones suit my use case the best and what kind of data they stream. I learned that the Meteor M series satellites fit my use case the best as the orbit over the poles.
Features: For this product to be successful, what features and capabilities I need.
PCBs: What goes into designing a custom PCB.



![](https://fabricate.hackclub-assets.com/53bfa5c9f601bfca5c1e4432e3dd764f1dad884ab73d60ddf2a3ed7bcfbf1693/image-png/image.png)
That is the sort of mechanical keyboard that I have decided on, along with a trackball like this.
![](https://fabricate.hackclub-assets.com/d06bef8f2d4cfffd0b508770c2fb0468a92e3535e115bdbcfd2dc0366c894ac8/image-png/image.png)

I will add this blackberry style trackball directly to the pcb for the mouse.

**Total time spent: 1.5h**
