# LaserCube

Laser projectors by Wicked Lasers, played from the free LaserOS app, a DMX desk or your own software.
Manual and guides: [wiki.laseros.com](https://wiki.laseros.com) · Shop: [www.laseros.com](https://www.laseros.com)

## Drive a LaserCube from your own software

**Ultra MK2 and Pro**

- **Your own code:** our [UDP DAC Streaming Protocol Specification](https://wiki.laseros.com/developers/udp-streaming-protocol.pdf) (PDF) describes the commands and data packets and includes a complete example sender in Python. Put the cube in LaserOS control mode.
- **Software that already has a laser output:** [Ether Dream mode](https://wiki.laseros.com/docs/guides/ultra-mk2-pro-manual/#ether-dream-control-mode) (TouchDesigner's Laser Device CHOP is one), IDN, [Art-Net](https://wiki.laseros.com/docs/guides/ultra-mk2-pro-manual/#artnet-control-mode) and [DMX](https://wiki.laseros.com/docs/guides/ultra-mk2-pro-manual/#dmx-control-mode): see [Control modes](https://wiki.laseros.com/docs/guides/ultra-mk2-pro-manual/#control-modes) and the [16 DMX channels](https://wiki.laseros.com/docs/guides/ultra-mk2-pro-manual/#dmxart-net-channel-layout).
- **SD card:** [mk2SDContent](https://github.com/Wickedlasers/mk2SDContent) holds the files of the factory SD card (shows, playlists, APC40 MK2 and APC mini MK2 mappings).

**LaserCube 1W and 2W** (the first, USB-only cubes)

- [laserdocklib](https://github.com/Wickedlasers/laserdocklib): USB client library (C++), with build steps for Linux and Android (tested on macOS).
- [Laser_OS_TouchDesigner](https://github.com/Wickedlasers/Laser_OS_TouchDesigner): TouchDesigner plugin (Windows 64-bit).

## Community libraries

Written by LaserCube owners, not by us, and not tested or supported by us:

- Rust: [nannou-org/lasercube](https://github.com/nannou-org/lasercube) (network)
- C# / .NET: [berkut0/LaserCubeSharp](https://github.com/berkut0/LaserCubeSharp) (network)
- vvvv: [berkut0/VL.Devices.LaserCube](https://github.com/berkut0/VL.Devices.LaserCube)
- Python: [lasercube.py](https://gist.github.com/s4y/0675595c2ff5734e927d68caf652e3af) (network)

## Before you stream

Every LaserCube is a Class 4 laser product: read the [manual's safety section](https://wiki.laseros.com/docs/guides/ultra-mk2-pro-manual/#safety-guidelines-and-proper-usage) first.
Building something bigger with LaserCubes? Write to support@laseros.com.
