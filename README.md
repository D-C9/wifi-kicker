wifi-kicker
===========

**Wifi kicker is a program that kick automatically peoples that are connected to the same wifi as you do**
**very useful when you need 5 minutes alone in a train station where the wifi is usually saturated**

you need Linux, python 2.7 and aircrack suite

if you append to have 2 wifi card all you have to do is to connect to a wifi and lunch the program

> **wifi-kicker configure itself automatically.**

But you can override automatic configuration by forcing params like this

> **wifi-kicker.py [bssid] [essid] [channel] [interface] [whitelist]**

you can use a whitelist to not kick your selphone and other friends

### TODO:
	* -make the use of params more flexible
	* -fix issue with subprocess.Popen and airodump in the long run
	* -use C bindings to comunicate with aircrack tools
	* -get rid of aircrack by crafting packets directly
