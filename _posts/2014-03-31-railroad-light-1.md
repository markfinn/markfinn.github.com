---
layout: post
title: "Railroad Light 1"
description: ""
category: 
tags: []
---
{% include JB/setup %}

A few years ag I bought an old railroad signal light at a swap meet.  I though it would be fun to convert it into an RGB indicator or some kind of multi-color stop light for my kids to play with outside while riding their bikes.


I don't have the electronics done, but the results so far show some promise:
<video id="video_1" class="video-js vjs-default-skin" controls="" preload="auto" width="640" height="264">
<source src="{{ BASE_PATH }}/images/TRIM_20140331_170021.mp4" type="video/mp4" /> 
</video>


The original light was a little broken, but for $10, I can't complain.  One I'm done, I might replace the circle of black plastic since it's cracked, but I might just be able to glue and screw it to get it to keep the right shape.
![rr1]({{ BASE_PATH }}/images/IMG_20140330_135301.jpg.png "title")


The light is fairly servicable.  The fron swings open, and everything can be disassembled and repaired or replaced.  This one had a broken side lite, so a bird had crawled in at some point.  I'll stick a circle of some cheap plastic in there when I close it up to keep water and future burds out.
The original light is a 10V bulb that is mounted at the focal point of a parabolic mirror.  the focus is even adjustable, which I will make use of.
![rr1]({{ BASE_PATH }}/images/IMG_20140330_135322.jpg.png "title")

I was able to find an 8" clear glass lens to replace the red plastic original.  I got it on Amazon, and it's meant for an underwater pool light housing.  Other than the faint "do not light unless submerged" and the fact that it is clear glass, it is pretty close to a copy of the original.

At this stage I also removed the side lites for fixing, cleaned the mirror, and ran new wiring out the back.
![rr1]({{ BASE_PATH }}/images/IMG_20140330_145457.jpg.png "title")

I decided to use a [BlinkM MaxM](http://thingm.com/products/blinkm-maxm/) as as simple way to get an RGB LED in there.  I haven't done the code yet for my final setup, and the BlinkM is just running its demo program at the moment.

#print
The mount [on github](https://github.com/markfinn/rgb_railroad_rlight) fits in the original bulb socket holder, and allows some focus control.  I made a conduit in the center for the wires, but as you can see in the following pictures, I forgot to thread the wires through.
I made the mount on my reprap, and it was the first thing that I've managed to print since last fall since it's been [cold out by the printer](http://localhost:4000/2014/03/31/reprap-enclosure/).  The mount is held on by double sided tape.  I wanted to make little latching fingers that the BlinkM would snap into, but that would have taken me much longer than the 5 minutes this simple mount did in [OpenSCAD](http://www.openscad.org/), so I went with simple and fast.
![rr1]({{ BASE_PATH }}/images/IMG_20140330_163348.jpg.png "title")


Here's the mount and LED board in place. I wasn't very careful about focus.  
![rr1]({{ BASE_PATH }}/images/IMG_20140331_163135.jpg.png "title")








