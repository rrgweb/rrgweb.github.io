---
permalink: /echolink/
title: "Echolink Information"
classes: wide
---


Echolink allows repeaters to be connected to each other through the Internet, or for users connected to the internet to connect directly to repeaters. You need to be a radio amateur to use Echolink, but once you are set up on the system at [www.echolink.org](http://www.echolink.org) you can connect to repeaters and conferences from your computer or even your smartphone (iPhones or Android devices).
 
#### Download Echolink software

For PC: [Download]
For iPhone/iPad: [Download]
For Android: Search for 'Echolink' in the Android Market or scan the QR code below:

!["Echolink QR Code"]({{ site.url }}{{ site.baseurl }}/assets/images/echolink_qr_code.jpg)

#### Using Echolink on GB3TD

Our UHF voice repeater, GB3TD, is available via Echolink.  

When it is online, you can connect to TD from an Echolink connected PC or smartphone by entering 43307 (node number) or by searching for GB3TD in the station list.
By default Echolink is disabled – if you are a radio user and need to make a connection you need to enable it with the DTMF 2# command. The response from the system will be the voice announcement “Echolink activated”.  The Echolink module will automatically timeout after 20 minutes of inactivity.
To connect to another station, just send the node number ended with a hash (#). To disconnect the last connected station, send just the hash sign. To exit the module, send a hash when not connected.

##### Sub-commands

There are a number of sub-commands that can be used once Echolink has been activated.

|DTMF Code| Meaning |
|---|---|
|0|Play the help message|
|1|List all connected stations|
|2|Play local EchoLink node ID|
|31|Connect to a random link or repeater|
|32|Connect to a random conference|
|4|Reconnect to the last disconnected station|
|50|Deactivate listen only mode|
|51|Activate listen only mode|
|6*|Use the connect by callsign feature|

Commands may also be executed even if the Echolink module is not currently active.  For example, to play the local Echolink Node Id (Command 2) Just send 22#, Echolink will be activated and the node id will be read back.

##### Connect by callsign

The "connect by callsign" feature makes it possible to connect to a station even if the node number is unknown. Callsigns are mapped to digits by using the following method: ABC=2, DEF=3, GHI=4, JKL=5, MNO=6, PQRS=7, TUV=8, WXYZ=9. That is the same mapping as on many phones. Letters are mapped to its corresponding digit and digits are of course mapped to their corresponding number. All other characters are mapped to digit 1.

**A few important things to remember:-**

1. Please give your callsign before sending tones or using echolink.
2. Please leave gaps for stations on echolink so they have time to respond..
3. Please disconnect the link when you have finished the QSO if no other station is   continuing with the QSO.
