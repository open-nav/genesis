# The Genesis

It's the repo manifest for the Open Navigation project

## What is Open Navigation?

Open source hardware and software platform for marine applications

## What hardware does it support?

  * Raspberry Pi3
  * Dragonboard 410c
  * Dragonboard 820c
  * Compulab IoT Gateway
  * Intel 

## What about the software?

The core of Open Navigation is based on the [Foundries.io](https://github.com/open-nav/genesis.git) Linux microPlatform. Docker containers are used to loosely couple data producers, such as gpsd, rtl-ais, opencpn, etc. The data is then aggerated by a client like OpenCPN.
