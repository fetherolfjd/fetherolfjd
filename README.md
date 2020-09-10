# Welcome!

## About Me

Insert more information here!

## Professional Experience

[![Linkedin Badge](https://img.shields.io/badge/-Justin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fetherolfjd/)](https://www.linkedin.com/in/fetherolfjd/)

## Current Personal Projects

### Smart Garage Door

I've been using the [GoControl Z-Wave Garage Door Controller](https://www.gocontrol.com/detail.php?productId=4) for a number of years in conjuction with
[Samsung SmartThings Hub](https://www.smartthings.com/products/smartthings-hub) (though an older version of both) with great success. Upon moving to our new home, the
installed garage door opener is a [Chamberlain MyQ](https://www.chamberlain.com/myq) model which disappointingly does not operate in the same way as a typical
"dumb" garage door opener. Of course, Chamberlain sells their own "gateway", but it does not natively support integration with SmartThings. Instead someone clever has created a [third party integration](https://github.com/brbeaird/SmartThings_MyQ) that may be shut down at any point.

At this point the common work-around to using the GoControl device with a Chamberlain MyQ opener is to use one of the wireless remote controls and connect across one of the
buttons with the GoControl, with the idea being to trigger the remote as if a person were pressing the button.

Unfortunately this appears to be a very inconsistent solution. At this time my remote just constantly triggers as if the button is being held down constantly, causing the door to repeatedly open and close.
Some work with a DMM indicates that the voltage being used in the remote opener circuit is 3V (it uses a CR2032 coin battery) but the voltage that is coming through the wires of the GoControl is right at 1.5V!!
My suspicion is that since the voltage is right about the mid-point that the circuit expects, the microcontroller on the remote is fluttering between intepreting the button as pressed and unpressed.

My solution for this is to build a voltage booster circuit as described in [this first schematic](https://www.electroschematics.com/one-battery-3-volts-step-boost-converter/). I'm currently in the process of soldering
the circuit, so TBD if it works!

### Home Network Reconfiguration

Insert more information here!

### Raspberry Pi

Now that my Pi 3 is not being used as a PiHole, I'm trying to figure out what to do with it. It was formerly a RetroPie host, however I barely have time to play games in general,
let alone expand my options with the games from my childhood.

I'm leaning towards turning it into a weather station, but once again, TBD!

<!--
**fetherolfjd/fetherolfjd** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
