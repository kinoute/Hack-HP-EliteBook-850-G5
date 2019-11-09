# HP EliteBook 850 G5 Hackintosh

A HP EliteBook 850 G5 Hackintosh running Mojave 10.14.6.

![](screenshots/specs.png)

## Description

I have already two Hackintoshes :

* A desktop [Hackintosh](https://github.com/kinoute/Hack-Z370-HD3P-i5-8400) at home with a i5-8400 and a Gigabyte Z370-HD3P ;
* A Dell Latitude E6430 [Hackintosh](https://github.com/kinoute/Hack-Dell-Latitude-E6430) I was given at work.

I had the change to put my hands on a nice HP EliteBook 850 G5 Laptop and couldn't resist, again, to install macOS on it.

## Laptop Specs

* macOS Mojave 10.14.6
* Intel i5-8350U vPro @ 1.7 Ghz, TurboBoost @ 3.6 Ghz (4 cores, 8 threads)
* Samsung M471A2K43CB1-CTD 32GB DDR4-RAM SDRAM SO-DIMM @ 2400 Mhz
* Intel HD Graphics 620 1536 Mb
* Toshiba XG5 KXG50ZNV1T02 1TB NVMe SSD PCIe 3.1a 
* 15.6" FHD IPS anti-glare LED-backlit with HD camera (1920 x 1080)

## What works

* Speakers
* Sound output (line out)
* Trackpad with gestures
* USB 3 Ports
* USB-C (tested with a HP Docking station)
* LAN/Ethernet
* Fn keys to change volume or brightness
* Battery percentage/status
* Sleep/Wake-up
* HDMI Out
* HP Sure View (makes your screen difficult for onlookers to view from the sides)

## Doesn't work / Not tested

* **Webcam :** The camera seens recognized by the system but doesn't work
* **WIFI :** Need to change the internal card. I use a [TP-Link-TL-WN725N](https://www.tp-link.com/us/home-networking/usb-adapter/tl-wn725n/) USB Dongle since I don't own the laptop (drivers for macOS [here](https://www.tp-link.com/us/support/download/tl-wn725n/#Driver)).

_Work in progress.._

## Benchmarks

![](screenshots/benchmarks.png)

Link: https://browser.geekbench.com/v4/cpu/14899859

## Credits

Huge thanks to [kecinzer](https://www.tonymacx86.com/members/kecinzer.1373007/) from tonymacx86 for making his EFI available and fixing the touchpad issues. Props to him for everything.

