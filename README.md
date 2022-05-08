# Welcome!

## About Me

I am a computer/tech enthusiast working remotely as a software engineer in northern Colorado. When not working or spending time with my family,
I'll be pecking at a personal tech project, a home improvement project, or mountain biking.

## Current Personal Projects

### Smart Garage Door *Finished*

This turned into a bit of a bust. It was working for awhile, but eventually something in the circuit
died. I think it was the voltage boosting chip. I'm in the process of switching to [Home Assistant][1], which
has a built in integration with the Chamberlain MyQ service, and that's working great so far, negating the
need for any of the nonsense I was doing before.

Check out all the details [here](https://github.com/fetherolfjd/smart-garage-painful-diy)!

### Home Network Reconfiguration

For some time I've been disappointed with several aspects of our router:
 - It doesn't get updated regularly
 - It only allows 64 devices to be assigned a static IP address
 - The admin UI is painfully slow
 - The admin UI will become completely unresponsive and require a reboot

I've since transitioned to a [Ubiquiti EdgeRouter 6p][2] which is serving well as the home router.
I've re-purposed the old router to serve as the access point for the home, but it is
generally dissappointing in this role. The 2.4Ghz coverage is good, but some devices
periodically lose internet access when connected to that network. The 5GHz network
coverage is pretty bad anywhere by the basement; which is the location of the WAP.

### Raspberry Pi

The Raspberry Pi is back to running [Pi-hole][3].


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

[1]: <https://www.home-assistant.io> "Home Assistant"
[2]: <https://store.ui.com/collections/operator-edgemax-routers/products/edgerouter-6-port> "Ubiquiti EdgeRouter 6p"
[3]: <https://pi-hole.net> "Pi-Hole"
