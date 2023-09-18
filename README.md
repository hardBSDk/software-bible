# Software Bible

In this list you will found my most *brutal* software recommendations, the software listed here is perfect.

My focus is functionality/usability, several software have annoying bloat (Electron) that reduce the portability/security and increase resource consumption, I try to replace it whenever I can.

- [Operating Systems](#operating-systems)
- [System](#system)
- [Terminal](#terminal)
- [Networking](#networking)
- [Files](#files)
- [Video](#video)
- [Image](#image)
- [Audio](#audio)
- [Games](#games)
- [Emulators](#emulators)
- [Other](#other)

## Operating Systems

- [Redox OS](https://www.redox-os.org/) - An Unix-like operating system written in Rust with a microkernel design.

It aims to be correct, reliable and secure, a microkernel design move the system components to user-space (to reduce kernel panics and improve security) while the Rust compiler/syntax produce secure (memory-safety) and efficient code (inspired by Plan 9, Minix, BSD, seL4 and Linux).

- [HardenedBSD](https://hardenedbsd.org/) - Hardened fork of FreeBSD with a implementation of the [grsecurity](https://grsecurity.net/) exploit mitigations and many other state-of-the-art mitigations.

## System

- [topgrade](https://github.com/topgrade-rs/topgrade) - A tool to update the packages on many distribution formats (system packages, Flatpak, Snap, Cargo and many others).
- [bottom](https://github.com/ClementTsang/bottom) - A terminal-based system monitor written in Rust.
- [macchina](https://github.com/Macchina-CLI/macchina) - A system information tool focused on performance (like neofetch).

## Terminal

- [starship](https://github.com/starship/starship) - A customizable prompt for Unix shells.

## Networking

- [Servo](https://servo.org/) - A browser engine written in Rust with a focus on high-performance/security.
- [Warp](https://apps.gnome.org/Warp/) - A tool to share files using the Magic Wormhole protocol, it's a P2P file protocol without limits.
- [OnionShare](https://onionshare.org/) - Easily host your websites, files or chats on the Tor network (.onion websites), can be installed via pip with `pip install onionshare-cli`.
- [ZeroTier](https://www.zerotier.com/) - A program to share your LAN over the Internet (like Hamachi).
- [Lokinet](https://lokinet.org/) An protocol-agnostic onion-routing network layer (same network type of Tor but not dependent on TCP like Tor) which tries to be more decentralized using a blockchain and improving the servers uptime with compensation.
- [Arti](https://tpo.pages.torproject.net/core/arti/) - The Rust implementation of Tor.
- [Jami](https://jami.net/) - Most decentralized messaging app of the world, yet supporting advanced features such as file sharing, screen sharing, voice/video calls, groups and moderation.
- [Lagrange](https://gmi.skyjake.fi/lagrange/) - small and beautiful [Gemini](https://gemini.circumlunar.space/) browser.
- [NeoSurf](https://github.com/CobaltBSD/neosurf) - A NetSurf fork with improvements to make more websites work.
- [gping](https://github.com/orf/gping) - A `ping` implementation with a graph.
- [Sniffnet](https://sniffnet.net/) - A nice tool to monitor your Internet traffic.
- [Manyverse](https://www.manyver.se/) - A revolutionary social network app based on the [SSB protocol](https://www.scuttlebutt.nz/) - **Electron-based**.

It replicate messages/posts with your peers/followers, creating an endless chain of backup (can't be censored in any way).

- [youtube-tui](https://github.com/Siriusmart/youtube-tui) - A terminal-based YouTube frontend with advanced customization.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - Fork of youtube-dl with improvements.
- [NewPipe](https://newpipe.net/) - The most complete streaming app for Android, it supports YouTube, SoundCloud, PeerTube and Bandcamp.
- [Syncthing](https://syncthing.net/) - BitTorrent-like file sharing tool with a cluster of connected devices with folder states.

## Files

- [XFE](http://roland65.free.fr/xfe/) - Small yet powerful file manager, image viewer and text editor (low resource usage)
- [jExifToolGUI](https://hvdwolf.github.io/jExifToolGUI/) - Tool to edit/remove EXIF from media files using the powerful ExifTool.
- [tokei](https://github.com/XAMPPRocky/tokei) - A tool to count lines of each type of file in a folder.
- [onefetch](https://onefetch.dev/) - Show the Git repository information (like neofetch).

## Video

- [Pitivi](http://www.pitivi.org/) - A flexible and easy-to-use video editor with fast encoding.
- [t-rec](https://github.com/sassman/t-rec-rs) - A terminal recorder written in Rust (like asciinema).

## Image

- [Flameshot](https://flameshot.org/) - The most complete screenshot tool of the world.
- [Upscaler](https://gitlab.gnome.org/World/Upscaler) - AI-based image upscaler with a GTK interface (works offline).
- [Upscayl](https://upscayl.github.io/) - AI image upscaler with folder selection support (works offline) - **Electron-based**.

## Audio

- [Festival](https://festival.pm/) - Amazing music player written in Rust.
- [Ardour](https://ardour.org/) - Powerful digital audio workstation similar to FL Studio and Ableton Live.

## Games

- [OpenSpades](https://openspades.yvt.jp/) - Open source client for the Ace Of Spades protocol, a wonderful voxel FPS multiplayer game.
- [ZeroSpades](https://github.com/siecvi/zerospades) - fork of OpenSpades with improvements/fixes.
- [Minetest](https://www.minetest.net/) - A voxel game engine with a game similar to Minecraft, it focus on modding.
- [Mindustry](https://mindustrygame.github.io/) - An advanced tower defense game written in Java.
- [San Andreas Unity](https://github.com/GTA-ASM/SanAndreasUnity) - A reimplementation of the Grand Theft Auto San Andreas on the Unity engine with improvements and unlimited modding.
- [Xash3D FWGS](https://github.com/FWGS/xash3d-fwgs) - Clean-room implementation of GoldSrc from Half Life with wonderful improvements.
- [GZDoom](https://www.zdoom.org/index) - The best Doom engine with advanced features and mod support.
- [FlightGear](https://www.flightgear.org/) - Most reallistic flight simulator of the world.
- [Godot Engine](https://godotengine.org/) - Powerful and flexible 2D/3D game engine with support for many programming languages (GDNative).
- [GDevelop](https://gdevelop.io/) - The most easy game engine of the world - **Electron-based**.

## Emulators

- [DuckStation](https://www.duckstation.org/) - Most complete PS1 emulator focused on accuracy and compatibility.
- [RPCS3](https://rpcs3.net/) - Wonderful PS3 emulator with advanced features.
- [Ruffle](https://ruffle.rs/) - Flash Player emulator reimplementation in Rust with high performance.
- [Libretro](https://www.libretro.com/) - A umbrella of emulators and games based on the libretro multimedia library, similar to [SDL](https://www.libsdl.org/).
- [RetroArch](https://www.retroarch.com/) - Most complete libretro frontend, supporting dozens of libretro cores and bleeding-edge emulation features.
- [Bottles](https://usebottles.com/) - The best Wine manager of the world, it support many Wine forks, API translators and customization options.

## Other

- [fend](https://github.com/printfn/fend) - A unit-aware calculator (can understand unit names/symbols to do conversions).
- [Virtual Machine Manager](https://virt-manager.org/) - A powerful virtual machine manager with advanced customization.
- [OpenZFS](https://openzfs.github.io/openzfs-docs/) - This implementation of ZFS aim to modernize the code for several Unix systems.
- [Arcan](https://arcan-fe.com/) - An overlay operating system that replace X11, Wayland, GTK, Qt, Electron and D-Bus.

It aims to improve security, be fail-resistant and OS-agnostic.
