## Wifi-shredder
This project was developed for the Wikitopia 2016 Cryptoparty organised by Dimsumlabs and CCC HK.

## What is the meaning of this Project?

This is a Python code that makes a symbolic Stand for Privacy and the value of your privat data.

It should raise your cautioness and awareness of the insecurity of your mobile devices.

It is intended as a demonstration where the output is beeing printed into a shredder where the Data gets distroyed. 

The data includes the Mac adress of the Smartphone or Laptop and the SSID it searches for.

Please note that currently there isn't a implemented way to actually print it since the endless paper printer at out hacker space isn't working ;) So i was to lazy and just made it console only output... The output isn't saved in any form and is only visible in the console.

## What do you need to make it work?

You need a running Python 2 enviroment with pyshark and tabulate installed over pip. And a working tshark that can be called as well as the following cli-tools: iw, ip link.

By all means, this tool isn't meant to be used to spy, it is only intended as a demonstration and you should destroy all collected data immediatly!


PS: Thx to Leviathan (https://github.com/leviathanch) for some help :)
