# Welcome!

## About Me

I am a computer/tech enthusiast working remotely as a software engineer in northern Colorado. When not working or spending time with my family,
I'll be pecking at a personal tech project, a home improvement project, or mountain biking.

## Professional Experience

I currently work as a Senior Software Engineer with Cherokee Nation Technologies, performing contract work for the U.S. Fish and Wildlife Service. For more details or history, visit [my LinkedIn profile](https://www.linkedin.com/in/fetherolfjd/).

## Current Personal Projects

### Smart Garage Door

I've been using the [GoControl Z-Wave Garage Door Controller](https://www.gocontrol.com/detail.php?productId=4) for a number of years in conjuction with
[Samsung SmartThings Hub](https://www.smartthings.com/products/smartthings-hub) (though an older version of both) with great success. Upon moving to our current home, the
installed garage door opener is a [Chamberlain MyQ](https://www.chamberlain.com/myq) model which disappointingly does not operate in the same way as a typical
"dumb" garage door opener. Of course, Chamberlain sells their own "gateway", but it does not natively support integration with SmartThings.
Instead someone clever has created a [third party integration](https://github.com/brbeaird/SmartThings_MyQ) that may be shut down at any point.

Research has indicated the most common work-around to using the GoControl device with a Chamberlain MyQ opener is to use one of the wireless remote controls
and connect across one of the buttons with the GoControl, with the idea being to trigger the remote as if a person were pressing the button.

Unfortunately this appears to be a very inconsistent solution. At this time my remote just constantly triggers as if the button is being held down constantly,
causing the door to repeatedly open and close. Some work with a DMM indicates that the voltage being used in the remote opener circuit is 3V
(it uses a CR2032 coin battery) but the voltage that is coming back from the wires of the GoControl is right at 1.5V!! My suspicion is that since the voltage
is right about the mid-point that the circuit expects, the microcontroller on the remote is fluttering between intepreting the button as pressed and unpressed.

My solution for this is to build a voltage booster circuit as described in [this first schematic](https://www.electroschematics.com/one-battery-3-volts-step-boost-converter/). I'm currently in the process of soldering
the circuit, so TBD if it works!

### Home Network Reconfiguration

For some time I've been disappointed with several aspects of our router:
 - It doesn't get updated regularly
 - It only allows 64 devices to be assigned a static IP address
 - The admin UI is painfully slow
 - The admin UI will become completely unresponsive and require a reboot
 
My plan to solve this is to build a pfsense based router. This will allow more flexibility in the administration of the home network since I like to give all "known" devices
in the home static IPs. It will also free up the current router that is also our WiFi hub to be relocated out of the basement, and for a second (and maybe third)
AP to be installed to get better coverage through and around the house.

I'd like to have the pfsense machine installed in a rack with my server, switch, and patch panel, which is making this bit of a longer ordeal since the current rack is only 6U,
and full. On top of that, appropriate hardware needs to be found that is hopefully power efficient and not complete overkill, even though that's probably where I'll end up.
This particular project is pretty low priority at the moment since technically our internet works and I can get 2.4 GHz coverage everywhere in the house I need it.

### Raspberry Pi

I've recently moved my [Pi-hole](https://pi-hole.net/) installation from a Raspberry Pi 3 to a Ubuntu VM on my FreeNAS server. Now that my Pi 3 is free,
I'm trying to figure out what to do with it. It was formerly a RetroPie host, however I barely have time to play games in general,
let alone expand my options with the games from my childhood. Plus I find that the RetroPie experience isn't seamless enough for my kids to manage getting into it and
into games with my help.

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
