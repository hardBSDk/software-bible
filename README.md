# Software Bible

In this list you will found my most *brutal* software recommendations, the software listed here is perfect.

My focus is functionality/usability, several software have annoying bloat (Electron) that reduce the portability/security and increase resource consumption, I try to replace it whenever I can.

- [Operating Systems](#operating-systems)
- [Networking](#networking)
- [Files](#files)
- [Video](#video)
- [Image](#image)
- [Audio](#audio)
- [Games](#games)
- [Emulators](#emulators)
- [Other](#other)

## Operating Systems

- [Redox OS](https://www.redox-os.org/) ([repository](https://gitlab.redox-os.org/redox-os/redox)) - An Unix-like operating system written in Rust with a microkernel design.

It aims to be correct, reliable and secure, a microkernel design move the system components to user-space (to reduce kernel panics and improve security) while the Rust compiler/syntax produce secure (memory-safety) and efficient code (inspired by Plan 9, Minix, BSD, seL4 and Linux).

- [HardenedBSD](https://hardenedbsd.org/) ([repository](https://git.hardenedbsd.org/hardenedbsd/HardenedBSD)) - Hardened fork of FreeBSD with a implementation of the [grsecurity](https://grsecurity.net/) exploit mitigations and many other state-of-the-art mitigations.

## Networking

- [OnionShare](https://onionshare.org/) ([repository](https://github.com/onionshare/onionshare)) - Easily host your websites, files or chats on the Tor network (.onion websites), can be installed via pip with `pip install onionshare-cli`.
- [Lokinet](https://lokinet.org/) ([repository](https://github.com/oxen-io/lokinet)) An protocol-agnostic onion-routing network layer (same network type of Tor but not dependent on TCP like Tor) which tries to be more decentralized using a blockchain and improving the servers uptime with compensation.
- [Jami](https://jami.net/) ([repository](https://git.jami.net/savoirfairelinux)) - Most decentralized messaging app of the world, yet supporting advanced features such as file sharing, screen sharing, voice/video calls, groups and moderation.
- [Lagrange](https://gmi.skyjake.fi/lagrange/) ([repository](https://github.com/skyjake/lagrange)) - small and beautiful [Gemini](https://gemini.circumlunar.space/) browser.
- [NetSurf](https://www.netsurf-browser.org/) ([repository](https://source.netsurf-browser.org/)) - Small/advanced web browser, yet supporting some features from bloated web browsers (Chromium/Firefox).
- [Manyverse](https://www.manyver.se/) ([repository](https://gitlab.com/staltz/manyverse)) - A revolutionary social network app based on the [SSB protocol](https://www.scuttlebutt.nz/)

It replicate messages/posts with your peers/followers, creating an endless chain of backup (can't be censored in any way) - **Electron-based**.

- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - Fork of youtube-dl with improvements.
- [NewPipe](https://newpipe.net/) ([repository](https://github.com/TeamNewPipe/NewPipe/)) - The most complete streaming app for Android, it supports YouTube, SoundCloud, PeerTube and Bandcamp.
- [Syncthing](https://syncthing.net/) ([repository](https://github.com/syncthing/syncthing)) - BitTorrent-like file sharing tool with a cluster of connected devices with folder states.
- [Warpinator](https://github.com/linuxmint/warpinator) - A tool to share files via LAN.

## Files

- [XFE](http://roland65.free.fr/xfe/) ([repository](https://github.com/roland65/xfe)) - Small yet powerful file manager, image viewer and text editor (low resource usage)
- [jExifToolGUI](https://hvdwolf.github.io/jExifToolGUI/) ([repo](https://github.com/hvdwolf/jExifToolGUI)) - Tool to edit/remove EXIF from media files using the powerful ExifTool.

## Video

## Image

- [Flameshot](https://flameshot.org/) ([repository](https://github.com/flameshot-org/flameshot)) - The most complete screenshot tool of the world.
- [Upscayl](https://upscayl.github.io/) ([repository](https://github.com/upscayl/upscayl)) - AI image upscaler that use your GPU offline - **Electron-based**.

## Audio

- [Ardour](https://ardour.org/) ([repository](https://git.ardour.org/ardour/ardour)) - Powerful digital audio workstation similar to FL Studio and Ableton Live.

## Games

- [OpenSpades](https://openspades.yvt.jp/) ([repository](https://github.com/yvt/openspades)) - Open source client for the Ace Of Spades protocol, a wonderful voxel FPS multiplayer game.
- [ZeroSpades](https://github.com/siecvi/zerospades) - fork of OpenSpades with improvements/fixes.
- [San Andreas Unity](https://github.com/GTA-ASM/SanAndreasUnity) - A reimplementation of the Grand Theft Auto San Andreas on the Unity engine with improvements and unlimited modding.
- [Xash3D FWGS](https://github.com/FWGS/xash3d-fwgs) - Clean-room implementation of GoldSrc from Half Life with wonderful improvements.
- [FlightGear](https://www.flightgear.org/) ([repository](https://github.com/FlightGear/flightgear)) - Most reallistic flight simulator of the world.

## Emulators

- [DuckStation](https://www.duckstation.org/) ([repository](https://github.com/stenzek/duckstation)) - Most complete PS1 emulator focused on accuracy and compatibility.
- [RPCS3](https://rpcs3.net/) ([repository](https://github.com/RPCS3/rpcs3)) - Wonderful PS3 emulator with advanced features.
- [Ruffle](https://ruffle.rs/) ([repository](https://github.com/ruffle-rs/ruffle)) - Flash Player emulator reimplementation in Rust with high performance.
- [Libretro](https://www.libretro.com/) ([repository](https://github.com/libretro)) - A umbrella of emulators and games based on the libretro multimedia library, similar to [SDL](https://www.libsdl.org/).
- [RetroArch](https://www.retroarch.com/) ([repository](https://github.com/libretro/RetroArch)) - Most complete libretro frontend, supporting dozens of libretro cores and bleeding-edge emulation features.

## Other

- [Virtual Machine Manager](https://virt-manager.org/) ([repository](https://github.com/virt-manager/virt-manager)) - A powerful virtual machine manager with advanced customization.
- [OpenZFS](https://openzfs.github.io/openzfs-docs/) ([repository](https://github.com/openzfs/zfs)) - This implementation of ZFS aim to modernize the code for several Unix systems.
- [Arcan](https://arcan-fe.com/) ([repository](https://github.com/letoram)) - An overlay operating system that replace X11, Wayland, GTK, Qt, Electron and D-Bus.

It aims to improve security, be fail-resistant and OS-agnostic.

<!-- - []() ([repository]()) - -->
