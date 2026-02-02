# My Big-Ass Light Up Snowflake
## took absolute ages
<img src="https://github.com/CaffeinatedOpe/led-snowflake/blob/master/assets/snowflake_blue.png?raw=true" alt="snowflake" width="400"/></br>

Technically this project was a few months ago, but I might as well make a github for it.

## The Hardware
The hardware in the snowflake is very simple. It uses a lolin s2 mini for it's processor, and all of the led strips are 60led/meter ws2812b led strips. The central hub and end caps are all pla 3d prints, and the tubes were just 1/2 inch pex pipe! I'm not going to write out a full bom for this thing, since the cad model isn't good enough that I'd think people would recreate the thing. The snowflake is powered off a 15w usb C plug at the bottom, and is hung from a loop of twine at the top.

## The Software
Because I'm not delusional enough to try and outdo it, I used the WLED firmware on the snowflake. I didn't try and make a gaps file for it, although the xlights file is in the github in case anyone is crazy enough to sort through my crappy cad model to make one themselves.

## The Build
The build for this thing wasn't complicated, but it was tedious. I had to wire up over 100 connections in pretty tight spaces, and without using so much wire that it was super visible. This made the connections veeery tricky to get stuck, and more than a few pads got ripped off in the process. I also crimped on some connectors for each branch, so they can be taken out and swapped around, or just stored.

## Demos
I'll be honest, this is the real reason I made this github, just to put up some vids of the thing in action. <br/>

<video src="https://github.com/CaffeinatedOpe/led-snowflake/raw/refs/heads/master/assets/0001-0113.mp4" width="320" height="240" controls></video>

<video src="https://github.com/CaffeinatedOpe/led-snowflake/raw/refs/heads/master/assets/0001-0143.mp4" width="320" height="240" controls></video>
