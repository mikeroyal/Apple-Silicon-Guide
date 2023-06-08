<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/213074824-9155501e-75bc-4557-9cff-b517211dd421.jpeg">
<br />
</p>

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157356993-34a7e1fa-ac06-49aa-991a-bf797a745e64.png">
  <br />
  Apple Silicon Guide
</h1>

 <a href="https://github.com/mikeroyal?tab=followers">
         <img alt="followers" title="Follow me on Github for Updates" src="https://custom-icon-badges.demolab.com/github/followers/mikeroyal?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a> 	

#### A guide covering Apple Silicon including the applications, libraries and tools that will make you better and more efficient with your Apple Silicon powered device.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/05a63ff1-c221-415c-a563-0476cbe28f95">
<br />
Apple M2/M2 Pro/M2 Max/M2 Ultra Architecture.
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157364203-a6c998b9-f15d-465e-81f4-ef888e7c8910.png">
<br />
Apple M1/M1 Pro/M1 Max/M1 Ultra Architectures.
</p>

# Table of Contents

1. [Getting Started with Apple Silicon](https://github.com/mikeroyal/Apple-Silicon-Guide#getting-started-with-apple-silicon)
   
   * [A16 Bionic](https://github.com/mikeroyal/Apple-Silicon-Guide#A16-Bionic)
   * [H2](https://github.com/mikeroyal/Apple-Silicon-Guide#H2)
   * [U1](https://github.com/mikeroyal/Apple-Silicon-Guide#U1)
   * [R1](#R1)
   * [M1](https://github.com/mikeroyal/Apple-Silicon-Guide#m1)
   * [M1 Pro](https://github.com/mikeroyal/Apple-Silicon-Guide#m1-pro)
   * [M1 Max](https://github.com/mikeroyal/Apple-Silicon-Guide#m1-max)
   * [M1 Ultra](https://github.com/mikeroyal/Apple-Silicon-Guide#m1-ultra)
   * [M2](https://github.com/mikeroyal/Apple-Silicon-Guide#m2)
   * [M2 Pro](#M2-Pro)
   * [M2 Max](#M2-Max)
   * [M2 Ultra](#M2-Ultra)
   * [Apple AR and Vision Pro Headset](#apple-ar-and-vision-pro-headset)
   * [Migrating to Apple Silicon](https://github.com/mikeroyal/Apple-Silicon-Guide#Migrating-to-Apple-Silicon)
   * [Devices powered by Apple Silicon](https://github.com/mikeroyal/Apple-Silicon-Guide#Devices-powered-by-Apple-Silicon)
   * [Getting Software](https://github.com/mikeroyal/Apple-Silicon-Guide#Getting-Software)
     - [Productivity & Workflow Apps](https://github.com/mikeroyal/Apple-Silicon-Guide#Productivity--Workflow-Apps)
     - [Secure & Privacy-focused Web Browsers](https://github.com/mikeroyal/Apple-Silicon-Guide#secure--privacy-focused-web-browsers)
        * [Privacy & Security Focused Browser extensions](https://github.com/mikeroyal/Apple-Silicon-Guide#privacy--security-focused-browser-extensions)
        * [Privacy-focused Search Engines](https://github.com/mikeroyal/Apple-Silicon-Guide#privacy-focused-search-engines)
     - [Microsoft Office Alternatives](https://github.com/mikeroyal/Apple-Silicon-Guide#microsoft-office-alternatives) 
   * [Universal Control](https://github.com/mikeroyal/Apple-Silicon-Guide#Universal-Control)
   * [Stage Manager](https://github.com/mikeroyal/Apple-Silicon-Guide#Stage-Manager)
   * [File Sync/Transfer](#File-SyncTransfer)
   - [Replacing iCloud with Nexcloud](#Replacing-iCloud-with-Nexcloud)
   * [Adding Storage(External)](https://github.com/mikeroyal/Apple-Silicon-Guide#Adding-External-Storage)
   * [Backups](#Backups)
   * [SSD Drive Health/Data Recovery](https://github.com/mikeroyal/Apple-Silicon-Guide#SSD-Drive-HealthData-Recovery)
   * [Checking Battery Health](https://github.com/mikeroyal/Apple-Silicon-Guide#Checking-Battery-Health)
      - [Turning on Low Power Mode](#low-power-mode)
   * [Charging/Powerbanks](#ChargingPowerbanks)
   * [MacOS/iOS Security Hardening](https://github.com/mikeroyal/Apple-Silicon-Guide#macosios-security-hardening)

2. [Wafer Level Multi-Chip Packaging Technology](https://github.com/mikeroyal/Apple-Silicon-Guide#wafer-level-multi-chip-packaging-technology)
 
    - [InFO (Integrated Fan-Out) Wafer Level Packaging](https://github.com/mikeroyal/Apple-Silicon-Guide#info-integrated-fan-out-wafer-level-packaging)
    - [Chip on Wafer on Substrate (CoWoS)](https://github.com/mikeroyal/Apple-Silicon-Guide#chip-on-wafer-on-substrate-cowos)

3. [Xcode Development](https://github.com/mikeroyal/Apple-Silicon-Guide#xcode-development)

4. [Core ML Development](https://github.com/mikeroyal/Apple-Silicon-Guide#core-ml-development)

5. [Metal Development](https://github.com/mikeroyal/Apple-Silicon-Guide#Metal-development)

6. [Visual Studio Studio (VSCode) Development](#vscode-development)

     - [VS Code Extensions for Developer Productivity](#VS-Code-Extensions-for-Developer-Productivity) 

7. [Unreal Engine 5 Development](#Unreal-Engine-5-Development)
 
8. [Unity Development](#Unity-Development)
 
9. [Blender Development](#Blender-Development)

10. [Virtualization](https://github.com/mikeroyal/Apple-Silicon-Guide#virtualization)

11. [Docker](https://github.com/mikeroyal/Apple-Silicon-Guide#docker)

12. [Kubernetes](https://github.com/mikeroyal/Apple-Silicon-Guide#kubernetes)

13. [Ansible](https://github.com/mikeroyal/Apple-Silicon-Guide#ansible)

14. [Running Linux on the Apple Silicon](https://github.com/mikeroyal/Apple-Silicon-Guide#running-linux-on-the-apple-silicon)
     * [Linux Virtualization on Apple Silicon](#Linux-Virtualization-on-Apple-Silicon)
     * [Asahi Linux Development](#Asahi-Linux-Development)
     * [Fedora Linux Development](#Fedora-Linux-Development)
     * [NixOS Linux Development](#NixOS-Linux-Development)
     * [Debian Linux Development](#Debian-Linux-Development)
     * [Ubuntu Linux Development](#Ubuntu-Linux-Development)

15. [Running Windows 10/11 on the Apple Silicon](https://github.com/mikeroyal/Apple-Silicon-Guide#running-windows-1011-on-the-apple-silicon)

16. [Gaming](https://github.com/mikeroyal/Apple-Silicon-Guide#gaming)
      
      - [Gaming on Apple Silicon resources](#gaming-on-apple-silicon-resources)
      - [MacOS Game Mode](#macos-game-mode)
      - [Game Porting Tool](#game-porting-tool)
      - [Whisky Wine wrapper](#whisky)
      - [Manage Temps/Fans (CPU and GPU)](#Manage-TempsFans-CPU-and-GPU)
      - [Gaming Peripherals](#Gaming-Peripherals)
        * [Gaming mice, keyboards, and headsets](#RGB-Devices)
        * [Game Controllers](#Game-controllers)
      - [Setting up OBS Studio](#Setting-up-OBS-Studio)
          * [Useful OBS Studio 3rd party Plugins & Themes](#useful-obs-studio-3rd-party-plugins-and-themes)
      - [Discord](#Discord)
      - [Twitch](#Twitch)
      - [Game Stores & Launchers](#Game-Stores--Launchers)
        * [Apple Arcade](#apple-arcade)
        * [CrossOver for MacOS](#CrossOver-for-MacOS)
        * [Steam](#Steam)
        * [Epic Games Store](#Epic-games-store)
        * [Blizzard Battle.net](#Blizzard-Battlenet)
        * [Origin](#Origin)
        * [EA Play](#EA-Play)
        * [Ubisoft Connect](#Ubisoft-Connect)
        * [GOG Galaxy Store](#GOG-Galaxy)
        * [Itch.io Store](#Itchio-Store) 
        * [Prism for Minecraft](#Prism)
        * [XIV on Mac for FF XIV](#XIV-on-Mac)
      - [Game Streaming](#Game-streaming)
        * [Cloud Game Streaming](#Cloud-Game-Streaming)
        * [Local Game Streaming](#Local-Game-Streaming)  
      - [Playing Android Games](#Android-Games)
      - [Game Emulators](#game-emulators)
        * [Emulator Frontends](#Frontends)
        * [Nintendo GameCube & Wii](#Nintendo-GameCube--Wii)
        * [Nintendo Switch](#Nintendo-Switch)
        * [Nintendo 64](#Nintendo-64)
        * [Nintendo 3DS](#Nintendo-3DS)
        * [Super Nintendo Entertainment System (SNES)](#Super-Nintendo-Entertainment-System-SNES)
        * [Nintendo Entertainment System (NES)](#Nintendo-Entertainment-System)
        * [Game Boy Advance](#Game-Boy-Advance)
        * [DOS](#DOS)
        * [Atari](#Atari)
        * [Sega Dreamcast](#Sega-Dreamcast)
        * [PlayStation Portable](#PlayStation-Portable)
        * [PlayStation 1](#PlayStation-1)
        * [PlayStation 2](#PlayStation-2)
        * [PlayStation 3](#PlayStation-3)
        * [Xbox](#Xbox)
        * [MAME](#MAME)
      - [Performance Benchmarks](#performance-benchmarks)

17. [Game Development](https://github.com/mikeroyal/Apple-Silicon-Guide#game-development)

18. [Professional Audio/Video Development](https://github.com/mikeroyal/Apple-Silicon-Guide#professional-audiovideo-development)

19. [3D Graphics & Design](https://github.com/mikeroyal/Apple-Silicon-Guide#3d-graphics-and-design)

20. [Swift Development](https://github.com/mikeroyal/Apple-Silicon-Guide#swift-development)

21. [Objective-C Development](https://github.com/mikeroyal/Apple-Silicon-Guide#objective-c-development)

22. [C/C++ Development](https://github.com/mikeroyal/Apple-Silicon-Guide#cc-development)

# Getting Started with Apple Silicon
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

- [Does it ARM? Apps that are reported to support Apple Silicon](https://doesitarm.com)

- [List of apps with native Apple silicon support](https://isapplesiliconready.com/for/m1)

- [M1 compatible Games Master List | AppleGamingWiki ](https://www.applegamingwiki.com/wiki/M1_compatible_games_master_list)

- [M1 Parallels Windows compatible games list | AppleGamingWiki](https://www.applegamingwiki.com/wiki/M1_Parallels_Windows_compatible_games_list)

- [Bring your game to Mac with the Game Porting Toolkit ](https://developer.apple.com/videos/play/wwdc2023/10123/)

- [Apple Silicon Games](https://applesilicongames.com/games)
  
- [Porting Kit | Install Windows apps in Mac](https://www.portingkit.com/)

- [Games and Apps on Apple Silicon (Compatibility Sheet) by Thomas Schranz(@__tosh on Twitter) ](https://docs.google.com/spreadsheets/d/1er-NivvuIheDmIKBVRu3S_BzA_lZT5z3Z-CxQZ-uPVs)

- [Mac Development Ansible Playbook by Jeff Geerling](https://github.com/geerlingguy/mac-dev-playbook)

- [Running macOS in a Virtual Machine on Apple Silicon Macs](https://developer.apple.com/documentation/virtualization/running_macos_in_a_virtual_machine_on_apple_silicon_macs?language=objc) 

- [Running Intel Binaries in Linux VMs with Rosetta](https://developer.apple.com/documentation/virtualization/running_intel_binaries_in_linux_vms_with_rosetta?language=objc) 

- [Virtualize macOS on a Mac](https://developer.apple.com/documentation/virtualization/virtualize_macos_on_a_mac?language=objc) 

- [Virtualize Linux on a Mac](https://developer.apple.com/documentation/virtualization/virtualize_linux_on_a_mac?language=objc) 

-  [Stable Diffusion with Core ML on Apple Silicon](https://machinelearning.apple.com/research/stable-diffusion-coreml-apple-silicon)

- [CrossOver® Mac](https://www.codeweavers.com/crossover)

- [DevToysMac](https://github.com/ObuchiYuki/DevToysMac) is the mac app version of [DevToys for Windows](https://github.com/veler/DevToys).

- [asitop](https://github.com/tlkh/asitop) is a Performance monitoring CLI tool for Apple Silicon.

- [macOS Security and Privacy Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide#openbsm-audit) is a collection of techniques for improving the security and privacy of a modern MacBook running a recent version of macOS.
 
- [macOS Security Compliance Project](https://github.com/usnistgov/macos_security) is an open source effort to provide a programmatic approach to generating security guidance. The configuration settings in this document were derived from National Institute of Standards and Technology (NIST) Special Publication (SP) 800-53, Security and Privacy Controls for Information Systems and Organizations, Revision 5. 

[Apple Hypervisor](https://developer.apple.com/documentation/hypervisor) is a framework that builds virtualization solutions on top of a lightweight hypervisor, without third-party kernel extensions. Hypervisor provides C APIs so you can interact with virtualization technologies in user space, without writing kernel extensions (KEXTs). As a result, the apps you create using this framework are suitable for distribution on the [Mac App Store](https://www.appstore.com/).

[Apple A-series](https://www.apple.com/) is Apple's 64-bit ARM-based system on a chip (SoC) used in their iPhones and iPads. Though, at WWDC 2020 it was announced that [Apple Silicon](https://developer.apple.com/documentation/apple_silicon) would [transition into Mac laptops](https://www.apple.com/newsroom/2020/06/apple-announces-mac-transition-to-apple-silicon/).

## Apple Silicon Chips

### A16 Bionic
[Back to the Top](#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/189012041-b2d83612-780f-4b57-97ef-c5042cdd7605.png">
<br />
</p>

**[A16 Bionic Chip](https://www.apple.com/iphone-14-pro/specs/)** is Apple's first 4nm SoC for iPhone 14 Pro & Max with a **6-core CPU has two performance cores and 4 high-efficiency cores**. Along with a **5-core GPU** and **16-core neural engine**.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/189012045-f4f64b59-1b43-4b78-86aa-57b018e19040.png">
<br />
A16 Bionic Chip Architecture
</p>

### H2 
[Back to the Top](#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443812-2ea26b51-afa5-4843-a9ef-d595321f2d90.png">
<br />
</p>

**[H2 Chip](https://www.apple.com/newsroom/2022/09/apple-announces-the-next-generation-of-airpods-pro/)** is Apple's SoC for the AiPods Pro that facilitates stronger(2x more) active noise cancellation, personalized spatial audio, and better performance during phone calls.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443814-c360663c-799b-406c-a3e9-4f4ea57a6d7a.png">
<br />
</p>

H2 chip powering the AirPods Pro. Credit: [Apple](https://www.apple.com/newsroom/2022/09/apple-announces-the-next-generation-of-airpods-pro/)


### U1 
[Back to the Top](#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443686-279114d1-789a-4b88-bd5b-1ba9b1f153e1.png">
<br />
</p>

[U1 Ultra Wideband (UWB) chip](https://support.apple.com/en-us/HT212274) is an Apple-designed silicon chip that has Ultra Wideband technology for spatial awareness. The U1 chip enables directional [AirDrop](https://support.apple.com/en-us/HT204144) functionality.

 * **UWB (Ultra-wideband)** is a short-range radio technology that precisely pinpoints and measures distance between other UWB equipped devices.
  
**Apple devices with the U1 chip**
 
 * [Apple AirTags](https://www.apple.com/airtag/)
 * iPhone 11
 * iPhone 11 Pro
 * iPhone 11 Pro Max
 * iPhone 12mini
 * iPhone 12
 * iPhone 12 Pro
 * iPhone 12 Pro Max
 * iPhone 13 mini
 * iPhone 13
 * iPhone 13 Pro
 * iPhone 13 Pro Max
 * iPhone 14
 * iPhone 14 Plus
 * iPhone 14 Pro
 * iPhone 14 Pro Max
 * Apple Watch Series 6
 * Apple Watch Series 7
 * Apple Watch Series 8
 * Apple Watch SE (2nd Gen)
 * Apple Watch Ultra
 * Apple HomePod mini

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443690-4bd78390-fe78-4053-8cf0-1be757486f08.png">
<br />
U1 Chip Die
</p>

### R1

[Back to the Top](#table-of-contents)

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/eacf3128-cc30-4cf8-9d77-12e5bda15e48">
<br />
</p>

The **R1 chip** is dedicated toward real-time sensor processing, taking the input from 12 cameras, five sensors (including a LIDAR sensor) and six microphones on the Vision Pro headset.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/425ff971-6fa4-4ba9-a594-932367662b23)">
<br />
R1 & M2 chips in the Vision Pro Headset
</p>


### M1 
[Back to the Top](#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941790-7886c405-ec76-4900-a405-ab29868485cb.png">
<br />
</p>

[Apple M1 Chip](https://www.apple.com/mac/m1/) is Apple's first SoC chip designed specifically for their ARM Mac products, it delivers incredible performance(8-core CPU and 8-core GPU), custom technologies, and great power efficiency. The M1 Chip is now available for [Macbook Pro 13 with M1](https://www.apple.com/macbook-pro-13/), [Macbook Air 13 with M1](https://www.apple.com/macbook-air/), [Mac Mini with M1](https://www.apple.com/mac-mini/), [iPad Pro](https://www.apple.com/ipad-pro/), and [iPad Air](https://www.apple.com/ipad-air/).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614045-f20a4858-0460-49c1-8d80-0ae815e8bc93.png">
<br />
</p>

**M1 Chip. Source: [Apple](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/)**

### M1 Pro
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941797-887664ba-8184-4849-8379-07113032ef40.png">
<br />
</p>

[Apple M1 Pro Chip](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/) is a 8 or 10-core system-on-a-chip (SoC) architecture designed for pro systems in the [MacBook Pro 14”](https://www.apple.com/shop/buy-mac/macbook-pro/14-inch). The chip features fast unified memory, industry-leading performance per watt, and incredible power efficiency, along with increased memory bandwidth and capacity. The M1 Pro offers up to 200GB/s of memory bandwidth with support for up to 32GB of unified memory and a GPU (14-core or 16-core option).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614048-949a4fa8-71f8-4a2e-97fe-f8db874b3d13.png">
<br />
</p>

**M1 Pro Chip. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

### M1 Max
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941803-e81f20f6-0bda-4a50-9f2c-7f149b67fbeb.png">
<br />
</p>

[Apple M1 Max Chip](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/) is a 10-core system-on-a-chip (SoC) architecture designed for pro systems in the [MacBook Pro 16”](https://www.apple.com/shop/buy-mac/macbook-pro/16-inch). The chip features fast unified memory, industry-leading performance per watt, and incredible power efficiency, along with increased memory bandwidth and capacity. The M1 Pro offers up to 400GB/s of memory bandwidth with support for up to 64GB of unified memory and a GPU (16-core or 32-core option).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614049-eff86f41-cb0c-41c8-8a93-c9590b711227.png">
<br />
</p>

**M1 Max Chip. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614054-fc5dfb69-fa4e-4a1d-a39d-4145466a6a70.png">
<br />
</p>

**M1/ M1 Pro/ M1 Max CPU Performance. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614056-784f775d-2b4d-4273-99ab-6a1025157704.png">
<br />
</p>

**M1/ M1 Pro/ M1 Max GPU Performance. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

### M1 Ultra
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941808-d00d49e6-d6d5-4301-b4ac-7a8d4f2552de.png">
<br />
</p>

[Apple M1 Ultra Chip](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/) is a Apple's most powerful silicon chip in their M1-series lineup. The M1 Ultra is composed of **two M1 Max chips** that are connected together using [Apple's UltraFusion Architecture](https://github.com/mikeroyal/Apple-Silicon-Guide/files/8248834/US20220013504A1.pdf) packaging. This means the M1 Ultra can be configured with up to 128GB of high-bandwidth, low-latency unified memory that can be accessed by the **20-core CPU, 64-core GPU (800GB/s memory bandwidth), and 32-core Neural Engine**. The M1 Ultra is currently available in Apple's **[Mac Studio](https://www.apple.com/shop/buy-mac/mac-studio)**.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157358150-c0e1b60d-787d-4e36-ba12-b4d4c5ea8bd2.png">
<br />
</p>

**M1 Ultra Chip. Source: [Apple](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157357074-8767aba7-a5ca-43a4-b44f-b22bf38c3e57.png">
<br />
</p>

**M1 Ultra CPU Performance. Source: [Apple](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157357079-029db757-9d39-41c7-88d8-bed769b14ec8.png">
<br />
</p>

**M1 Ultra GPU Performance. Source: [Apple](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/)**

### M2
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/210165269-01041deb-4178-40b4-85d7-f84d14ed33c5.png">
<br />
</p>

[Apple M2 Chip](https://www.apple.com/newsroom/) has a **18% faster CPU, 35% faster GPU, and 40% faster Neural Engine than the base [M1 chip](https://github.com/mikeroyal/Apple-Silicon-Guide#M1)**. It can be configured with up to **24GB** of high-bandwidth, low-latency unified memory that can be accessed by the **8-core CPU, 10-core GPU (100GB/s memory bandwidth), and 16-core Neural Engine**. The M2 will be available in Apple's new **[MacBook Air](https://www.apple.com/macbook-air/)**, **[MacBook Pro 13"](https://www.apple.com/macbook-pro/)** with old design, and **[iPad Pro with M2 ](https://www.apple.com/ipad-pro/)**.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230405-e6e015e7-5271-43ef-b097-87ca374db5f2.png">
<br />
</p>

**M2. Source: [Apple](https://www.apple.com/newsroom/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172234868-ea4e4975-fb96-47da-a0cc-6bb5d8fba5af.png">
<br />
</p>

**M2 CPU Performance. Source: [Apple](https://www.apple.com/newsroom/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230446-6fd70598-8dd9-4e5a-b92d-2e1e4ac92791.png">
<br />
</p>

**M2 GPU Performance. Source: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230507-c469930a-7a4e-4289-bb39-d6dddf7ecdcb.png">
<br />
</p>

**M1 vs M2. Source: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230463-b1578f4a-6cce-4738-9835-28d0ac7529ef.png">
<br />
</p>

**M2 Gaming Performance. Source: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230480-80b23096-4db5-467c-97b2-dc52427d49f7.png">
<br />
</p>

**M2 Image Processing Performance. Source: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230485-094fc112-efbd-4b21-90db-d66ac70bafbb.png">
<br />
</p>

**M2 Video editing Performance. Source: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230490-c8c9b8de-54f6-46a8-9f0c-e8375cd9dbea.png">
<br />
</p>

**M2 Image filters & Effects Performance. Source: [Apple](https://www.apple.com/newsroom)**

### M2 Pro

[Back to the Top](#table-of-contents)

 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/216295418-13381e71-6839-42e1-99ae-b22552374348.png">
</p>

[Apple M2 Pro Chip](https://www.apple.com/newsroom/) has a **20% faster CPU, 30% faster GPU, and 40% faster Neural Engine than the base [M1 Pro chip](https://github.com/mikeroyal/Apple-Silicon-Guide#M1-Pro)**. It can be configured with up to **32GB** of high-bandwidth, low-latency unified memory that can be accessed by the **12-core CPU, 19-core GPU (200GB/s memory bandwidth), and 16-core Neural Engine**. The M2 Pro will be available in Apple's **[MacBook Pro 14"](https://www.apple.com/macbook-pro-14-and-16/)**, **[MacBook Pro 16"](https://www.apple.com/macbook-pro-14-and-16/)**, and **[Mac mini](https://www.apple.com/mac-mini/)**.

  <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/213024040-d9389326-f84d-4702-8056-afe6046dd5fe.png">
</p>

M2 Pro Chip. Image Credit: [Apple](https://www.apple.com/newsroom/)

### M2 Max

[Back to the Top](#table-of-contents)

 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/216295429-7cb0f4ce-3b83-4c61-b9da-a937eceb2b27.png">
</p>

[Apple M2 Max Chip](https://www.apple.com/newsroom/) is a Apple's most powerful silicon chip in their M2-series for right now. The M2 has a **20% faster CPU, 30% faster GPU, and 40% faster Neural Engine than the base [M1 Max chip](https://github.com/mikeroyal/Apple-Silicon-Guide#M1-Max)**. It can be configured with up to **96GB** of high-bandwidth, low-latency unified memory that can be accessed by the **12-core CPU, 38-core GPU (400GB/s memory bandwidth), and 16-core Neural Engine**. The M2 Max will be available in Apple's **[MacBook Pro 14"](https://www.apple.com/macbook-pro-14-and-16/)**, **[MacBook Pro 16"](https://www.apple.com/macbook-pro-14-and-16/)**, and **[Mac mini](https://www.apple.com/mac-mini/)**.


  <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/213024048-db42c02f-1379-497f-b96a-7446b31b5f69.png">
</p>

M2 Max Chip. Image Credit: [Apple](https://www.apple.com/newsroom/)


### M2 Ultra

[Back to the Top](#table-of-contents)

 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210165270-8609f92a-8765-4b19-9956-cd04b0593159.png">
</p>

The M2 Ultra is composed of **two M2 Max chips** that are connected together using [Apple's UltraFusion Architecture](https://github.com/mikeroyal/Apple-Silicon-Guide/files/8248834/US20220013504A1.pdf) packaging.

The M2 Ultra can be configured with up to **192GB** of high-bandwidth, low-latency unified memory that can be accessed by the **24-core CPU, 76-core GPU (800GB/s memory bandwidth), and 32-core Neural Engine**. The M2 Ultra is available for the [Mac Studio](https://www.apple.com/mac-studio/) and [Mac Pro](https://www.apple.com/mac-pro/).


## Apple AR and Vision Pro Headset

[Back to the Top](#table-of-contents) 

**Important Terms to Know**

 * [Augmented Reality (AR)](https://en.wikipedia.org/wiki/Augmented_reality) is an interactive experience of a real-world environment where the objects that reside in the real world are enhanced by computer-generated perceptual information.
 * [Virtual Reality (VR)](https://en.wikipedia.org/wiki/Virtual_reality) is a simulated experience that can be similar to or completely different from the real world. The applications of virtual reality include entertainment (video games), education (medical or military training) and business (virtual meetings).
 * [Mixed Reality (MR)](https://en.wikipedia.org/wiki/Mixed_reality) is the merging of real and virtual worlds to produce new environments and visualizations, where physical and digital objects co-exist and interact in real time.
 * [Extended Reality (XR)](https://en.wikipedia.org/wiki/Extended_reality) is a concept referring to all real-and-virtual combined environments and human-machine interactions generated by computer technology and wearables. Including augmented reality (AR), mixed reality (MR) and virtual reality (VR).

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/1eb8474d-ed6b-4c57-a88c-6879db9df78b">
  <br />
 Vision Pro Headset. Image Credit: Apple
</p>

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/4fa96b25-effe-4dc2-a5c9-3c43bcdda285)">
  <br />
 Vision Pro Headset with battery pack. Image Credit: Apple
</p>

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/425ff971-6fa4-4ba9-a594-932367662b23)">
<br />
R1 & M2 chips in the Vision Pro Headset. Image Credit: Apple
</p>

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/e1f5d708-87a8-4b45-bfc9-03860cb6ebea">
  <br />
 visionOS. Image Credit: Apple
</p>

* [visionOS](https://www.apple.com/newsroom/2023/06/introducing-apple-vision-pro/) is Apple's iOS-like operating system for their upcoming AR/VR (Augmented Reality/Virtual Reality) headset powered by Apple's Silicon M2 and R1 chips. It will have an App Store with apps that include mixed-reality versions of their core Apple apps like **[Messages](https://support.apple.com/messages), [FaceTime](https://support.apple.com/facetime), [Maps](https://www.apple.com/maps/), and AR/VR games from [Apple Arcade](https://www.apple.com/apple-arcade/)**. Along with features such as [Memojis](https://apps.apple.com/us/story/id1445637997) and [SharePlay](https://support.apple.com/guide/iphone/use-shareplay-to-watch-and-listen-together-iphb657eb791/ios) that could be central to the user experience. 
 
 **visionOS Resources**
 
 * [Learn about visionOS](https://developer.apple.com/visionos/learn/)
 * [Vision Pro compatibility evaluations (available July 2023)](https://d*eveloper.apple.com/visionos/work-with-apple/)
 * [Vision Pro developer labs (available July 2023)](https://developer.apple.com/visionos/work-with-apple/)
 * [Vision Pro developer kit (available July 2023)](https://developer.apple.com/visionos/work-with-apple/)
 

 **Apple Vision Pro Headset Specs:**
   
   * Powered by an M2 chip and **R1 chip(dedicated toward real-time sensor processing for the 12 cameras and 5 sensors on the Vision Pro headset)**.
   * High-resolution 4K micro OLED displays.
   * Display Pixel Size will be between 3000 ppi-4000 ppi.
   * Display offers a brightness of 5,000 nits.
   * The color gamut is quoted as DCI > 97% DCI.
   * 96W USB-C power adapter.
   * A USB-C port for data transfer.
   * A proprietary magnetic port(MagSafe) to attach the [battery pack](https://www.amazon.com/Apple-MJWY3AM-A-MagSafe-Battery/dp/B099BWY7WT).
   * Expected battery life of about **2 hours per pack**.
   * 12 optical cameras and 5 sensors for tracking movements, mapping the environment, and projecting visual experiences. 
   * WiFi 6E, which adds 6GHz spectrum to the 2.4GHz & 5GHz bands for increased bandwidth and less device interference.

OLEDoS (OLED on Silicon) is a display panel that typically has a diagonal length of less than 1 inch and meets the 3000 ppi-4000 ppi resolution criteria of AR/VR device displays. Existing OLED displays use Low-Temperature-Poly-Silicon (LTPS) or Oxide TFT based on glass substrates. OLEDoS uses silicon-wafer-based CMOS substrates. Using silicon substrates, ultra-fine circuit structures typically used in semiconductor processes can be reproduced, which in turn lead to the creation of ultra-high-resolution OLEDs when organic matter is deposited on them.

 **LG OLEDoS Display Specs:**
 
   * High-resolution 4K micro OLED displays.
   * Display Pixel Size will be between 3000 ppi-4000 ppi.
   * Display offers a brightness of 5,000 nits.
   * The color gamut is quoted as DCI > 97% DCI.
 
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/194017317-b1dbda21-5935-47ef-8843-137cc5540b60.png">
  <br />
 OLEDoS: Solution for ultra-high resolution
</p>

Credit: [LG](https://www.lgdisplay.com/eng/technology/oled)

### Tools and Frameworks

 * [Reality Composer Pro](https://developer.apple.com/videos/play/wwdc2023/10083/) is a tool that let's you discover how to easily compose, edit, and preview 3D content with Reality Composer Pro. Follow along as you explore this developer tool by setting up a new project, composing scenes, adding particle emitters and audio, and even previewing content on your device. 
 * [Reality Composer](https://developer.apple.com/augmented-reality/tools/) is a powerful tool that makes it easy for you to create interactive augmented reality experiences with no prior 3D experience. The Reality Converter quickly converts your existing 3D models to [USDZ](https://graphics.pixar.com/usd/files/USDZFileFormatSpecification.pdf) so it works seamlessly in our tools and on all AR-enabled iPhone and iPad devices.
 * [USDZ](https://graphics.pixar.com/usd/release/spec_usdz.html) is a file format that contains a 3D scene or object saved in the USDZ Universal format, which is developed by Apple and Pixar Animation Studios. It is an uncompressed and unencrypted .ZIP archive that stores a Universal Scene Description (.USD, USDA, or USDC) file, which includes 3D geometry and shading data. USDZ files may also contain .PNG and .JPEG image textures and .M4A, .MP3, or .WAV audio files utilized in the 3D object or scene.
 * [ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.
 * [RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.
 * [RealityUI](https://github.com/maxxfrazer/RealityUI) is a Swift Package for creating familiar UI Elements and animations in a RealityKit rendered Augmented Reality or Virtual Reality scene. 
 * [SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.
 * [MetalFX](https://developer.apple.com/videos/play/wwdc2022/10103/) is a new API that provides platform optimized graphics effects for Metal applications. With MetalFX Upscaling, your application can now render frames at a lower resolution, reducing rendering time, without compromising rendering quality. We'll also show you how and when to use its two effects: spatial upscaling, which delivers substantial performance gains, and temporal AA and upscaling, which delivers the highest quality rendering.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172254747-9308be59-4d79-4677-a5ec-cf40f5762cf7.png">
  <br />
 MetalFX Rendering. Image Credit: Apple
</p>

 * [Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore) is a graphics rendering and animation infrastructure that provides high frame rates and smooth animations without burdening the CPU and slowing down your app.
 * [Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics) is a framework based on the Quartz advanced drawing engine. It provides low-level, lightweight 2D rendering with unmatched output fidelity.
 * [GPUImage3](https://github.com/BradLarson/GPUImage3) is the third generation of the [GPUImage framework](https://github.com/BradLarson/GPUImage), an open source project for performing GPU-accelerated image and video processing on Mac and iOS. This third generation is redesigned to use **[Apple's Metal](https://developer.apple.com/metal/) in place of OpenGL**.

### Developer Resources

 * [AR Creation Tools - Augmented Reality | Apple Developer](https://developer.apple.com/augmented-reality/tools/)
 * [Augmented Reality applications | Apple](https://www.apple.com/augmented-reality/)
 * [iOS, iPadOS, and tvOS Development on Unreal Engine](https://docs.unrealengine.com/5.0/en-US/ios-ipados-and-tvos-support-for-unreal-engine/)
 * [XR Development on Unreal Engine](https://docs.unrealengine.com/5.0/en-US/developing-for-xr-experiences-in-unreal-engine)
 * [Unreal Engine Performance and Profiling](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/PerformanceAndProfiling/)
 * [Unity Learn Training Program](https://learn.unity.com)
 * [Unity Manual: XR](https://docs.unity3d.com/Manual/XR.html)
 * [Intro to XR: VR, AR, and MR Foundations - Unity Learn](https://learn.unity.com/course/introduction-to-xr-vr-ar-and-mr-foundations)
 * [Unity XR: Build VR and AR Apps](https://unity3d.com/learn/unity-xr-apps)


## Migrating to Apple Silicon
[Back to the Top](#table-of-contents)

* [Xcode 13](https://developer.apple.com/xcode/) is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon.

* [Universal App Quick Start Program](https://developer.apple.com/programs/universal/)

* [Writing ARM64 Code for Apple Platforms](https://developer.apple.com/documentation/xcode/writing_arm64_code_for_apple_platforms)

* [Porting Your macOS Apps to Apple Silicon](https://developer.apple.com/documentation/xcode/porting_your_macos_apps_to_apple_silicon)

* [Building a Universal macOS Binary](https://developer.apple.com/documentation/xcode/building_a_universal_macos_binary)

* [Addressing Architectural Differences in Your macOS Code](https://developer.apple.com/documentation/apple_silicon/addressing_architectural_differences_in_your_macos_code)

* [Porting Just-In-Time(JIT) Compilers to Apple Silicon](https://developer.apple.com/documentation/apple_silicon/porting_just-in-time_compilers_to_apple_silicon)

* [Porting Your Audio Code to Apple Silicon](https://developer.apple.com/documentation/audiounit/porting_your_audio_code_to_apple_silicon)

* [Porting Your Metal Code to Apple Silicon](https://developer.apple.com/documentation/metal/porting_your_metal_code_to_apple_silicon)

* [Tuning Your Code’s Performance for Apple Silicon](https://developer.apple.com/documentation/os/workgroups/tuning_your_code_s_performance_for_apple_silicon)

* [Learn how Rosetta translates executables and what Rosetta can’t translate](https://developer.apple.com/documentation/apple_silicon/about_the_rosetta_translation_environment)

* [Running Your iOS Apps on macOS](https://developer.apple.com/documentation/apple_silicon/running_your_ios_apps_on_macos)

* [Adapting iOS Code to Run in the macOS Environment](https://developer.apple.com/documentation/apple_silicon/adapting_ios_code_to_run_in_the_macos_environment)

* [Implementing Drivers, System Extensions, and Kexts](https://developer.apple.com/documentation/apple_silicon/implementing_drivers_system_extensions_and_kexts)

* [Installing a Custom Kernel Extension](https://developer.apple.com/documentation/apple_silicon/installing_a_custom_kernel_extension)

* [Debugging a Custom Kernel Extension](https://developer.apple.com/documentation/apple_silicon/debugging_a_custom_kernel_extension)


## Devices powered by Apple Silicon
[Back to the Top](#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/216298135-374b55aa-566c-412a-a2b5-787ec03d5d6f.png">
<br />
Devices powered by Apple Silicon.
</p>

### macOS
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[macOS](https://www.apple.com/macos) is an advanced desktop operating system (OS) for Apple's series of desktops and laptops.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230572-2d86197a-ce2a-4eaa-a508-e2c148b60057.png">
<br />
</p>

**macOS Ventura. Source: [Apple](https://www.apple.com/macos/monterey/)**

### iOS
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[iOS](https://www.apple.com/ios/) is an advanced mobile operating system (OS) for Apple's series of iPhone products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230685-96be6cd0-118f-48d7-b7b9-e258580cd66a.png">
<br />
</p>

**iOS 16. Source: [Apple](https://www.apple.com/ios)**

### iPadOS
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[iPadOS](https://www.apple.com/ipados/) is an advanced mobile operating system (OS) for Apple's series of iPad products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230690-b628a77f-963c-44bd-b84b-9e76a2082ef3.png">
<br />
</p>

**iPadOS 16. Source: [Apple](https://www.apple.com/ipados)**

###  watchOS
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[watchOS](https://www.apple.com/watchos/) is an advanced mobile operating system (OS) for Apple's series of Watch products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230694-4accbc04-9057-4280-84d2-42927131fc8c.png">
<br />
</p>

**watchOS 9. Source: [Apple](https://www.apple.com/watchos/)**

## Getting Software

[Back to the Top](#table-of-contents)

[Apple App Store](https://www.apple.com/app-store/)

[Developing for the App Store](https://www.apple.com/app-store/developing-for-the-app-store/)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/183509416-3f094b9d-7e9d-4d72-baa7-106cbf360efd.png">
<br />
</p>

[Homebrew](https://brew.sh) is the missing Package Manager for your macOS, Linux, and Windows 10 (with [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/)) system. Homebrew is an essential tool for any developer/engineer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183512138-68b919fe-a970-431d-801e-6982049e9e92.png">
  <br />
</p>

[MacPorts Project](https://www.macports.org/) is an open-source community initiative to design an easy-to-use system for compiling, installing, and upgrading either command-line, X11 or Aqua based open-source software on macOS. 

[Nix package manager](https://nixos.org/) is a cross-platform package manager that utilizes a purely functional deployment model where software is installed into unique directories generated through cryptographic hashes. Choose from Thousands of Packages The Nix Packages collection (Nixpkgs) is a set of over 80 000 packages for the Nix package manager.

 * **[Nix-darwin](https://github.com/LnL7/nix-darwin)** is Nix modules for darwin, ```/etc/nixos/configuration.nix``` for macOS.

**Multi-user installation on macOS:**

```$ sh <(curl -L https://nixos.org/nix/install)```

**Note:** Nix will install all it's packages within ```/nix/store```.

**Note 2:** You may need to source the nix profile at this point.

```source /nix/var/nix/profiles/default/etc/profile.d/nix-daemon.sh```

```source /nix/var/nix/profiles/default/etc/profile.d/nix.sh```


### Productivity & Workflow Apps

[Back to the Top](#table-of-contents)

[Signal](https://www.signal.org/) is a state-of-the-art end-to-end encryption (powered by the open source [Signal Protocol](https://github.com/signalapp)) messaging app that keeps your conversations secure. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287855-d92f2bb8-1839-4ded-8412-a255061292cc.png">
  <br />
  Signal
</p>

[NordVPN](https://nordvpn.com/) is a VPN service and the flagship product of the cybersecurity company Nord Security. It's available for wireless routers, NAS devices, and other platforms. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287860-8ad40bd7-3820-498f-bd08-6f91dee43013.png">
  <br />
  NordVPN
</p>

[WireGuard](https://www.wireguard.com/) is a fast, open-source, and secure VPN tunnel. WireGuard allows users to manage and use WireGuard tunnels. The app can import new tunnels from archives and files, from QR codes, or you can create one from scratch.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287871-b77d5135-e329-4921-ba8e-f037f18ec165.png">
  <br />
 WireGuard
</p>

[Tailscale](https://tailscale.com/) is a open-source mesh VPN alternative built on WireGuard® that makes it easy to connect your devices. It includes features like automatic key rotation, NAT traversal, and single sign-on with two-factor authentication.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188288048-e972845a-51a6-4782-9771-8cf423b6bcf8.png">
  <br />
 Tailscale
</p>

[BitWarden](https://bitwarden.com/) is a free and open-source password management service that stores sensitive information such as website credentials(logins and passwords) in an encrypted vault while conveniently keeping them synced between all of your devices.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188288085-27fa54f7-3f3f-4e6c-9435-15548d24deff.png">
  <br />
  BitWarden
</p>

[1Blocker](https://1blocker.com/) is a fast, secure, and robust tool for iPhone, iPad, and Mac that empowers users to put a stop to invasive online content.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287874-3ed8144d-9103-47b8-80c5-bd33a8bca1cb.png">
  <br />
  1Blocker
</p> 

[Matrix](https://matrix.org/) is a client tool that gives you simple HTTP APIs and SDKs (iOS, Android, Web) to create chatrooms, direct chats and chat bots, complete with end-to-end encryption, file transfer, synchronized conversation history, formatted messages, read receipts and more.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188303122-2160d3f4-0fb4-4936-b475-7f015181dbf3.png">
  <br />
 Matrix
</p>

[Element](https://element.io/) is a Matrix web client built using the [Matrix React SDK](https://github.com/matrix-org/matrix-react-sdk). It is a robust and reliable hosting service for fast, secure real time communication.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188302916-c73507e5-e34c-4a47-9b1e-d43c180a10a4.png">
  <br />
 Element
</p>

[Nextcloud](http://nextcloud.com/) is a suite of client-server software for creating and using file hosting services. It offers an on-premise Universal File Access and sync platform with powerful collaboration capabilities and desktop, mobile and web interfaces.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188302917-dc12e604-33c5-413b-be52-4ada05eb5041.png">
  <br />
 Nextcloud
</p> 

[Synology](https://www.synology.com/) is a tool that allows you to easily access and manage files in your Synology Drive on the go. Apart from common file types, such as documents, images, videos and music, you can also open Synology Office document, spreadsheets and slides in the user-friendly viewer provided by Drive.
 
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188302924-a7a4291c-33da-48ed-9459-c0e82b42d1de.png">
  <br />
 Synology
</p>

[Adobe Lightroom Photo Editor](https://apps.apple.com/us/app/lightroom-photo-video-editor/id878783582) is a free, powerful photo & video editor and camera app that empowers you to capture and edit stunning images. It offers photo & video editing tools like sliders to retouch your images, apply photo filters, fine-tune backgrounds, and use transformative presets to quickly add unique adjustments.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188288045-b50e41f2-557d-490a-aa73-758e17c7aaa1.png">
  <br />
  Adobe Lightroom Photo Editor
</p>

[Things](https://culturedcode.com/things/) is an app that helps you plan your day, manage your projects, and make real progress toward your goals.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707448-44b5bc1b-96d8-4b1e-b33b-fb8a3157c092.png">
<br />
Things
</p>

[Airbuddy 2](https://v2.airbuddy.app/) is a utility that let's you simply open your AirPods case next to your Mac and see the current status right away, just like how it works on your iPhone. A single click gets you connected, a swipe down lets you connect and change listenings modes at the same time. It has a fully customizable battery alerts help you keep track of your device's batteries.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706944-562df794-d9f7-4c3b-ab92-adf19e078d0f.png">
<br />
Airbuddy 2
</p>

[Fantastical 3](https://flexibits.com/fantastical) is a calendar app that works seamlessly across your Mac, iPad, iPhone, and Apple Watch. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706724-d9bde5a3-36fc-453e-80fd-5a6d2a1e1f13.png">
<br />
Fantastical 3
</p>

[Bartender](https://www.macbartender.com/) is an app for macOS that superpowers your menu bar, giving you total control over your menu bar items, what's displayed, and when, with menu bar items only showing when you need them. It improves your workflow with quick reveal, search, custom hotkeys and triggers, and lots more. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509489-c6941bff-7f2a-4a5b-a5e4-a8c24bca3b1d.png">
  <br />
  Bartender menu bar tray
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183511213-02d08283-7432-4afc-988e-f933dc1bd4a5.png">
  <br />
  Bartender Settings
</p>

[Magnet](https://magnet.crowdcafe.com/) is an app that keeps your workspace organized. magnet is activated by dragging, customizable keyboard shortcuts or via menu bar, it declutters your screen by snapping windows into organized tiles.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509955-d6249063-5d17-49c3-bb99-8c952086a6a7.png">
  <br />
  Magnet
</p>

[AltTab](https://alt-tab-macos.netlify.app/) is an app that brings the power of Windows’s “alt-tab” window switcher to macOS.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509490-8def09c4-b8a8-4112-b24a-aa9feeb8a3de.jpg">
  <br />
  AltTab
</p>


[MonitorControl](https://monitorcontrol.app/) is an app that controls your external display brightness and volume and shows native OSD. Use menulet sliders or the keyboard, including native Apple keys.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509539-7d839f11-a975-441d-a683-ca58031ac9f8.png">
  <br />
  MonitorControl
</p>


[WebCatalog](https://webcatalog.io/webcatalog/) is an app that turns any Website into Real Desktop Apps. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509551-bbac5da8-0e77-4a62-89df-19e9a19f9be0.png">
  <br />
  WebCatalog
</p>


[Maccy](https://maccy.app/) is a lightweight clipboard manager for macOS. It keeps the history of what you copy and lets you quickly navigate, search, and use previous clipboard contents.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509534-1843f439-9738-4e40-a6bf-72bf10fa9f5d.png">
  <br />
  Maccy clipboard manager
</p>

[Daisydisk](https://daisydiskapp.com/) is a utility that provides a visual breakdown of your disk space in form of an interactive map, reveal the biggest space wasters, and remove them with a simple drag and drop. It supports all kinds of local drives, as well as the most popular cloud disks.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706628-3f546149-0505-4c10-a75a-295274eb590c.png">
<br />
Daisydisk
</p>

[Page screenshot for Safari](https://alexdenk.eu/mywork/pagescreenshot.html) is an awesome extension, just a click away, ready to use every time you need to capture a webpage screenshot, either the full page or just part of it. Along with your pictures will also automatically open in Preview for easy editing (annotations, blurring sensitive info, printing, drawing, sharing).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706686-c3caa3b0-9855-4c53-b890-c144fd53b1a4.png">
<br />
Page screenshot for Safari
</p>

[Paste](https://pasteapp.io/) is a Clipboard manager for Mac, iPhone, and iPad. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/188302928-e30c9dbc-90df-47cc-a6e4-79edceb928ec.png">
<br />
Paste
</p>

[PasteBot](https://tapbots.com/pastebot/) is an indispensable tool to improve your productivity. It quickly recalls clippings that you have copied before and apply powerful text filters to format before pasting. Queue up multiple clippings to paste in sequence. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706657-79fd7243-c323-4326-9d4f-d716a97b55b6.png">
<br />
PasteBot
</p>

[Speedcut](https://www.speedcut.app/) is a tool that lets your remove backgrounds from photos straight from your Mac's menu bar.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/188302929-d87607fa-c0ca-4eee-95b9-e758b21b968a.png">
<br />
Speedcut
</p>

[Pulse](https://kean.blog/pulse/home) is a powerful logging system for Apple Platforms builtin in SwiftUI. It allows you to record and inspect logs and ```URLSession``` network requests right from your iOS app. Shared logs and view them in [Pulse Pro](https://kean.blog/pulse/pro) or use remote logging to see them in real-time. Logs are stored locally and never leave your devices.

p align="center">
<img src="https://user-images.githubusercontent.com/45159366/218423398-52ed3e3c-fa49-46c7-a6ea-03ba7c431224.png">
<br />
Pulse
</p>

[Cleaner One Pro](https://cleanerone.trendmicro.com/cleaner-one-pro-for-mac/) is an all-in-one Mac Master Cleaner App. It can optimize your disk usage, free up space on your Mac, keep the hard drive clean, remove duplicate photos and other files, manage your apps, and much more. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706738-fafc320d-72b4-4b68-86df-a4d1ccf92ec0.png">
<br />
Cleaner One Pro
</p>

[Yabai](https://github.com/koekeishiya/yabai) is a window management utility that is designed to work as an extension to the built-in window manager of macOS.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185481311-dd5edd37-1bbc-4f86-95ea-f3c3aaee6001.png">
  <br />
</p>

[Bear](https://bear.app/) is a Private Markdown Editor for iPhone, iPad and Mac. It uses todos to stay on task across every device. Organize easily Link notes to each other to build a body of work. Add hashtags to organize the way you think. Use Face/Touch ID to protect sensitive notes.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707343-717aabae-21bf-4f43-b179-68ae339e9d3f.png">
<br />
Bear
</p>

[Obsidian](https://obsidian.md/) is a powerful knowledge base that works on top of a local folder of plain text Markdown files. It comes with 25 core plugins, 638 community plugins, and 130 themes, plus custom styling, you can tweak Obsidian to work and look exactly how you want it. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707401-7ed042a1-9658-45dc-ac16-ffb454eb3be7.png">
<br />
Obsidian
</p>

[MarkText](https://github.com/marktext/marktext) is a simple and elegant open-source markdown editor that focused on speed and usability.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707405-6bc1da24-e8b9-4713-949b-d0a29732224e.png">
<br />
MarkText
</p>

[1Focus](https://onefocusapp.com/) is an App and Website Blocker to keep you focused on your work. Block specific apps such as email, games or unsupported web browsers. Also, block internet access by blocking the installed web browsers and the App Store.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707348-f16430fb-9847-4c58-ba11-80446c293705.png">
<br />
1Focus
</p>

[Harvest](https://www.getharvest.com/) is an easy Time Tracking Software With Invoicing. It creates a project Create entries for your projects and tasks, or import them via one of our integrations.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707378-d412d134-05f6-4a97-affc-cfb3f20b2633.png">
<br />
Harvest
</p>

[MindNode](https://www.mindnode.com/) is a map and brainstorming tool that lets you capture, organize, style and share your thoughts. Capture your thoughts Organize your ideas Style your mind map Discreetly Powerful All the features you need.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707637-0d5c7bd1-9968-4079-9941-8809af3a306e.png">
<br />
MindNode
</p>

[Unclutter](https://apps.apple.com/us/app/unclutter/id577085396?mt=12) is a 3-in-1 productivity app to power up your efficiency and comfort on Mac during the day. It's a smart and super handy place on your desktop for storing notes, files and pasteboard clips.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707426-c385b6ab-5494-45bb-8ddf-5f031fd2cf5d.png">
<br />
Unclutter
</p>

[Warp terminal](https://www.warp.dev/) is a blazingly fast, rust-based terminal reimagined from the ground up to work like a modern app.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707428-351705e2-15bd-4913-80a9-87bf8e0df945.png">
<br />
Warp
</p>

[Jettison](https://www.stclairsoft.com/Jettison/) is a tool that automatically ejects external disks from your Mac before your computer goes to sleep. Simply close the lid of your MacBook and Jettison will automatically eject your backup drive, iPod, or whatever is connected so you can safely unplug it.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707387-4ba9bba2-305e-4976-986d-bf3e2a1113b9.png">
<br />
Jettison
</p>

[Numi](https://numi.app/) is a calculator that magically combines calculations with text, and allows you to freely share your computations. Numi combines text editor and calculator Support plain English.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706707-31ca1206-bfe5-4888-8b83-bbd80961b8ed.png">
<br />
NuMi
</p>

[Dropzone](https://aptonic.com/) is a productivity app for the Mac that makes it faster and easier to move and copy files, launch applications, upload to many different services, and more.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707368-7a3aeeda-79f5-4ad3-af40-f2eeedd3c236.png">
<br />
Dropzone
</p>

[System Color Picker](https://sindresorhus.com/system-color-picker) is the macOS color picker as an app with lots of extra features.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185812204-2bb6073c-0e2f-40f8-83bc-6e981daf33ee.png">
<br />
System Color Picker
</p>

[Raycast](https://www.raycast.com/) is a blazingly fast, totally extendable launcher. It lets you complete tasks, calculate, share common links, and much more.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707470-4473a12f-f17a-419e-af1c-4662db395e09.png">
<br />
</p>

[Tinkertool](https://www.bresink.com/osx/TinkerTool.html) is an application that gives you access to additional preference settings Apple has built into MacOS. This allows to activate hidden features in the operating system and in some of the applications delivered with the system.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707461-1b4e46bb-86d7-4cfc-9d61-6c8d6182a434.png">
<br />
Tinkertool
</p>

[App Cleaner](https://app-cleaner.com/) is an application that uninstall/remove applications from Mac entirely with all their preferences, caches and other bits and pieces.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187094108-4a5c0931-db42-479e-9061-467ca8891bfb.png">
<br />
App Cleaner
</p>

[Infuse](https://firecore.com/) is a Video Player for iOS, Apple TV, and Mac. It plays every video file ever created to avoid wasting hours converting and transcoding files.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/200111122-5e263a8c-2b1b-4425-b599-58ba7016fe20.png">
<br />
Infuse Video Player
</p>

## Secure & Privacy Focused Web Browsers

[Back to the Top](#table-of-contents)

**Note: While [Safari](https://www.apple.com/safari/) is a great browser that comes included on all Apple devices. It may not have all the extensions you need for your workflow so I recommend checking out the several great options below.**

[Mozilla Firefox](https://www.mozilla.org/firefox/) is a free and open-source web browser developed by the Mozilla Foundation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266387-04609c3f-1324-4c21-9186-5ed338835260.png">
  <br />
  Firefox
</p>

[Brave](https://brave.com/) is a fast, private and secure web browser for PC, Mac and mobile. It comes with [Brave Search](https://brave.com/search/), which is a private search engine that puts you first, not big tech for those that don't want to use Google Search.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266393-8891913c-5acd-4a3a-98cf-ce214282126d.png">
  <br />
  Brave
</p>

[Ungoogled-Chromium](https://www.techspot.com/downloads/7181-ungoogled-chromium.html) is a lightweight approach to removing Google web service dependency.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/173683899-a91b5b02-533f-4ad2-ba84-c3a70108e0dd.png">
  <br />
 Ungoogled-Chromium
</p>

[Vivaldi](https://vivaldi.com/) is a fast, private and secure web browser for PC, Mac and mobile. It comes with built-in features like Notes, Screen Capture, Image Properties and (a lot) more.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266396-25f48ceb-9868-4d8f-80a3-30bbd0bbf092.png">
  <br />
  Vivaldi
</p>

[Ghostery Dawn](https://www.ghostery.com/dawn) is a fast, private and secure web browser for PC, Mac and mobile. It comes with the complete Ghostery Privacy Suite including [Ghostery Glow](https://www.ghostery.com/glow) a private search engine that does not log your search history, which means you get served objective results, not results that are filtered by the likelihood you’ll click on them.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509605-9e486350-315c-4c9c-ab65-261cda0dac7f.png">
  <br />
  Ghostery Dawn
</p>

[DuckDuckGo Privacy Browser](https://apps.apple.com/us/app/duckduckgo-privacy-browser/id663592361) is a fast, private and secure web browser for MacOS and mobile(iOS and Android).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509601-0d8382cb-bf4f-41e7-9531-9946c8749a7c.png">
  <br />
 DuckDuckGo
</p>

### Privacy & Security Focused Browser extensions

[Back to the Top](#table-of-contents)

[UBlock Origin](https://ublockorigin.com/) is a free and open-source, cross-platform browser extension for content filtering primarily aimed at neutralizing privacy invasion in an efficient, user-friendly method.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
 
[Privacy Badger](https://privacybadger.org/) is a browser extension that automatically learns to block invisible trackers.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)
 
[DuckDuckGo Privacy Essentials](https://duckduckgo.com/app) is an extension that seamlessly helps prevent your personal information from being exposed during everyday online activity. 

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-for-firefox/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg?hl=fr)
 
[Ghostery](https://www.ghostery.com/ghostery-browser-extension) is a comprehensive privacy protection Ad Blocker browser extension.
 
 * [Firefox extension](https://www.ghostery.com/ghostery-ad-blocker-firefox)
 * [Chrome extension](https://www.ghostery.com/ghostery-ad-blocker-chrome)
 
[HTTPS Everywhere](https://www.eff.org/https-everywhere)  is an extension created by EFF and the Tor Project which automatically switches thousands of sites from insecure "http" to secure "https".

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?hl=en)
 
[CleanURLs](https://gitlab.com/KevinRoebert/ClearUrls) is an extension will automatically remove tracking elements from URLs to help protect your privacy when browsing through the Internet.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/clearurls/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk/)
 
**PixelBlock** is an Gmail extension that blocks email tracking attempts used to detect when you open and read emails. 

 * [Chrome extension](https://chrome.google.com/webstore/detail/pixelblock/jmpmfcjnflbcoidlgapblgpgbilinlem/)

[Sitejabber](https://www.sitejabber.com/) is an extension for consumers to find trustworthy online businesses and avoid scams.

[Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/sitejabber/)

[Chrome extension](https://chrome.google.com/webstore/detail/sitejabber-ratings-review/ckiddbafgcfifpioacgfijgicacanflo)
 
[1Password](https://1password.com/) is a password manager that provides a place for users to store various passwords, software licenses, and other sensitive information in a virtual vault that is locked with a PBKDF2-guarded master password.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/1password-x-password-manager/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/1password-%E2%80%93-password-mana/aeblfdkhhhdcdjpifhhbdiojplfjncoa?hl=en)
 
[Bitwarden](https://bitwarden.com/) is a free and open-source password management service that stores sensitive information such as website credentials in an encrypted vault.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)
 
[Guardio](https://guard.io/) is a lightweight extension designed to help you browse quickly and securely. It will clean your browser, speed it up, and protect your private information.

 * [Chrome extension](https://chrome.google.com/webstore/detail/guardio-protection-for-ch/gjfpmkejnolcfklaaddjnckanhhgegla)
 
[OneTab](https://www.one-tab.com/) is an extension that converts your tabs to a list and speeds up your browser.
 
 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/onetab/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall)
 
### Privacy-focused Search Engines

[Back to the Top](#table-of-contents)

 * [Brave Search](https://brave.com/search/)
 
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009061-21142683-0943-4ef2-9ca1-a66831410ae4.png">
  <br />
 
</p>
 
 * [Ghostery Glow](https://www.ghostery.com/glow)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009065-2d360d4f-9712-4f80-9da2-e8808773ba7f.png">
  <br />
 
</p>
 
 * [DuckDuckGo](https://duckduckgo.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009064-2d753a92-6e80-48a5-9e88-deb9d886162e.png">
  <br />
 
</p>
 
 * [Startpage](https://www.startpage.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009074-7e0ae42e-84b2-4815-9280-d56ff289462b.png">
  <br />
 
</p>
 
 * [Qwant](https://www.qwant.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009070-b652dab1-0f4a-4020-b231-bc7da3897c04.png">
  <br />
 
</p>
 
 * [Ecosia](https://www.ecosia.org/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009066-d81594fe-873f-4aed-ac0f-2f9f6673ebc9.png">
  <br />
 
</p>

 * [Swisscows](https://swisscows.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009076-74c38325-077d-4511-be75-981646dd11c8.png">
  <br />
 
</p>
 
 * [searX](https://searx.info/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009072-54539257-92f9-4f7e-9515-3cb14a2e8695.png">
  <br />
 
</p>
 
 * [Mojeek](https://www.mojeek.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009069-afd5a4e2-aea5-4143-87ba-8882c31476a8.png">
  <br />
 
</p>

## Microsoft Office Alternatives

[Back to the Top](#table-of-contents)

[OnlyOffice](https://www.onlyoffice.com/) is a secure offline/online office suite highly compatible with MS Office formats for Windows, Mac and Linux.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158472597-9ca73786-4e28-497f-9c6d-0a0040e8c3da.png">
  <br />
  OnlyOffice
</p>

[FreeOffice](https://www.freeoffice.com/) is a secure office suite highly compatible with MS Office formats for Windows, Mac and Linux.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266331-321a1004-14cb-473f-a01f-9a9a6e67623a.png">
  <br />
  FreeOffice
</p>

[LibreOffice](https://www.libreoffice.org/) is a free and open-source office productivity software suite similar to Microsoft Office.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158470268-2834d32d-72ef-4e5e-8cd6-02db51a5dcfa.png">
  <br />
  LibreOffice
</p>

## Universal Control
[Back to the Top](#table-of-contents)

[Universal Control](https://www.apple.com/newsroom/2021/10/macos-monterey-is-now-available/) is a software feature for Apple devices such as MacBooks and iPads that makes it possible to use a single keyboard, mouse, and trackpad with your Mac and iPad as long as they're side-by-side. Much like SideCar, there are limited settings for Universal Control. Without a second device connected, you can go to System Preferences -> Displays and click Advanced to pull up Universal Control settings. If a device is already connected, you'll have to go to Displays -> Display Settings -> Advanced.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153113830-cf6380b4-af80-4252-894a-84a4eada82e6.png">
<br />
</p>

Bluetooth, Wi-Fi, and Handoff must be enabled on each device, and they must be within 30 feet. If you prefer to use Universal Control wired, the devices can be connected via USB and you must trust your Mac on your iPad. At the moment, Apple does not mention support for Ethernet but we will test this ourselves during the beta period.

You must also have supported devices. Apple says supported devices include:

 - MacBook Pro (2016 and later)
 - MacBook (2016 and later)
 - MacBook Air (2018 and later)
 - iMac (2017 and later)
 - iMac (5K Retina 27-inch, Late 2015)
 - iMac Pro, Mac mini (2018 and later)
 - Mac Pro (2019)
 - Any iPad Pro
 - iPad Air (3rd generation and later)
 - iPad (6th generation and later)
 - iPad mini (5th generation and later)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153113829-d6ba2c62-4639-4576-90c5-0456b1e2f06e.png">
<br />
</p>

## Stage Manager

[Back to the Top](#table-of-contents)

Stage Manager is an iPadOS feature that provides better support for external displays. Stage Manager allows the iPad Air(**M1 chip**) and iPad Pro(**M1 chip**):

  *  **Fast access to windows and apps**: The windows of the apps you’re working in are displayed prominently in the center, and other apps are arranged on the left side in order of recent use.
  *  **Resizable windows**: Resize your windows to make them the perfect size for your task.
  *  **Center app**: Focus on the app you’re working with without going full screen.
  *  **Overlapping windows**: Create overlapping windows of different sizes in a single view, giving you the control to arrange your ideal workspace.
  *  **Group apps together**: Drag and drop windows from the side or open apps from the Dock to create app sets that you can always get back to.
  
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/179672909-4c040435-65db-4522-8846-1d0b87b4a6fa.png">
<br />
</p>

## File Sync/Transfer

[Back to Top](#table-of-contents)

[Syncthing](https://syncthing.net/) is a continuous file synchronization program. It synchronizes files between two or more computers in real time.

[Seafile](https://www.seafile.com) is an open source file sync&share solution designed for high reliability, performance and productivity. Sync, share and collaborate across devices and teams. 

[Synology](https://www.synology.com/) is a tool that allows you to easily access and manage files in your Synology Drive on the go. Apart from common file types, such as documents, images, videos and music, you can also open Synology Office document, spreadsheets and slides in the user-friendly viewer provided by Drive.

[Nextcloud](http://nextcloud.com/) is a suite of client-server software for creating and using file hosting services. It offers an on-premise Universal File Access and sync platform with powerful collaboration capabilities and desktop, mobile and web interfaces. 

[FileRun](https://hub.docker.com/r/filerun/filerun) is a self-hosted Google Drive alternative. It is a full featured web based file manager with an easy to use user interface.

[FileBrowser](https://hub.docker.com/r/filebrowser/filebrowser) provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory.

[Rsync](https://rsync.samba.org/) is a utility in the command line which enables users to transfer and synchronize files efficiently between a computer and an external hard drive in the entire connected network.

[rsync.net](https://rsync.net/) is a Cloud Storage for Offsite Backup that give you an empty UNIX filesystem to access with any SSH tool. Built on ZFS for data security and fault tolerance with support for rsync/sftp/scp/borg/rclone/restic/git-annex.

[Warpinator](https://github.com/linuxmint/warpinator) is a free, open-source tool for sending and receiving files between computers that are on the same network. 

[FileZilla Client](https://filezilla-project.org/) is a fast and reliable cross-platform FTP, FTPS and SFTP client with lots of useful features and an intuitive graphical user interface. 

[WinFsp](https://github.com/winfsp/winfsp) is a set of software components for Windows computers that allows the creation of user mode file systems. In this sense it is similar to FUSE (Filesystem in Userspace), which provides the same functionality on UNIX-like computers.

[SSHFS-Win](https://github.com/winfsp/sshfs-win) is a minimal port of SSHFS to Windows. Looking under the hood it uses Cygwin for the POSIX environment and WinFsp for the FUSE (Filesystem in Userspace) functionality.

[RiftShare](https://riftshare.app) is a cross platform (Windows, MacOS, Linux) file sharing tool that supports fully encrypted transfers both on the local network and off network using a simple passphrase. RiftShare uses [magic-wormhole](https://github.com/magic-wormhole/magic-wormhole) under the hood and is compatible with other magic-wormhole clients. It is also fully open source and licensed under the GPLv3. 

[Usermode FTP Server](https://gitlab.com/ergoithz/umftpd) is a tool that let's you start an FTP server as user and transfer files with any FTP client. Allowing you to access your files directly with many file browsers' builtin FTP support: Windows File Explorer, Thunar, Gnome Files, Dolphin and many more. 

[TagSpaces](https://www.tagspaces.org/) is a free, no vendor lock-in, open source application for organizing, annotating and managing local files with the help of tags. It features advanced note taking functionalities and some capabilities of to-do apps. It's available for Windows, Linux, Mac OS and Android. 

## Replacing iCloud with Nexcloud

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/218290801-af7efb7b-fd9e-452e-a18e-72e643bdf044.png">
  <br />
  
</p>

**Replacing these iCloud services:**

  * File sync (“iCloud Drive”) -> [Nextcloud Files](https://nextcloud.com/files/)
  * Photos (“iCloud Photo Library”) -> [Nextcloud Photos](https://github.com/nextcloud/photos)
  * Mail -> [Nextcloud Mail](https://apps.nextcloud.com/apps/mail) + [SnappyMail](https://apps.nextcloud.com/apps/snappymail)
  * Contacts -> [Nextcloud Contacts](https://apps.nextcloud.com/apps/contacts)
  * Calendar -> [Nextcloud Calendar](https://apps.nextcloud.com/apps/calendar)
  * Reminders -> [SnappyMail](https://apps.nextcloud.com/apps/snappymail)
  * Browser sync (“Safari”) -> [Nextcloud Bookmarks](https://apps.nextcloud.com/apps/bookmarks) or [Floccus](https://floccus.org/)
  * Notes -> [Nextcloud Notes](https://apps.nextcloud.com/apps/notes)
  * Password sync (“Keychain”) -> [KeePass DB on Nextcloud](https://apps.nextcloud.com/apps/keeweb)
  * Remote access (“Back to my mac”) -> [Tailscale](https://tailscale.com/) + [docker-ddns](https://github.com/dprandzioch/docker-ddns)
  * Find my iPhone -> [Nextcloud PhoneTrack](https://apps.nextcloud.com/apps/phonetrack)
  * iWork for iCloud -> [Nextcloud with Onlyoffice](https://nextcloud.com/onlyoffice/) or [Collabora Online in Nextcloud](https://nextcloud.com/collaboraonline/)
  * News -> [Miniflux](https://miniflux.app/) with [Fever API](https://miniflux.app/docs/services.html)
  * Audiobooks (“iBooks”) -> [audiobookshelf](https://www.audiobookshelf.org/)
  * Repository Hosting -> [GitLab](https://gitlab.com/)


[Nextcloud](https://nextcloud.com) is an industry-leading, on-premises content collaboration platform for file sync & share and communication server. It is fully open source and you can host it yourself or pay a company to do it for you. Also checkout the following links below:

   - [Nextcloud App Store](https://apps.nextcloud.com)

   - [Nextcloud GitHub](https://github.com/nextcloud)

   - [Nextcloud Developer Program](https://nextcloud.com/developer)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/150701961-ac8be115-34c1-4012-bd69-d1f22a10e48c.png">
  <br />
Nexcloud login screen
</p>

[Nextcloud Hub](https://nextcloud.com/hub/) is a tool that allows you to share and collaborate on documents, send and receive email, manage your calendar and have video chats without data leaks. As fully on-premises solution, Nextcloud Hub provides the benefits of online collaboration without the compliance and security risks.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/150701964-df1dd8d9-1d3a-4376-81e8-f49439fb4356.png">
  <br />
Nexcloud Hub
</p>

[Nextcloud AIO (All In One)](https://github.com/nextcloud/all-in-one) is a tool that provides easy deployment and maintenance with most features included in this one Nextcloud instance. 

**Features it includes:**

   * Nextcloud
   * Nextcloud Office
   * High performance backend for Nextcloud Files
   * High performance backend for Nextcloud Talk
   * Backup solution (based on BorgBackup)
   * Imaginary
   * ClamAV
   * Fulltextsearch

[Nextcloud Desktop Client](https://nextcloud.com/install/#install-clients) is a tool to synchronize files from Nextcloud Server with your computer.

[Nextcloud Deck](https://apps.nextcloud.com/apps/deck) is a kanban style organization tool aimed at personal planning and project organization for teams integrated with Nextcloud.

[Nextcloud Files](https://nextcloud.com/files/) is a tool tool that allows your employees have easy access to their files, photos and documents to work and can share and collaborate with team members, customers and partners. So IT knows nobody besides those they shared with has access to those files.

[Nextcloud Talk](https://nextcloud.com/talk/) is a tool that protects your communication better than other team collaboration platforms like Microsoft Teams or Slack, making sure your data stays on your servers. It also goes further than other encrypted communication technologies by keeping even metadata from leaking.

[Nextcloud Home](https://nextcloud.com/athome/) is a tool that allows you store your documents, calendar, contacts and photos on your server at home, at one of at one Nextcloud's providers or in a data center you trust.

[Nextcloud Enterprise](https://nextcloud.com/enterprise/) is a service that gives professional organizations software optimized and tested for mission critical environments.

[Nextcloud Outlook Integration](https://nextcloud.com/outlook/) is a tool that automatically upload files to replace large attachments or integrate Calendars and Contacts in Microsoft Outlook.

[Collabora Online in Nextcloud](https://nextcloud.com/collaboraonline/) is a powerful LibreOffice-based online office suite with collaborative editing, which supports all major document, spreadsheet and presentation file formats and works in all modern browsers.

[ONLYOFFICE integration in Nextcloud](https://nextcloud.com/onlyoffice/) is a service that empowers your users to collaborate on office documents with team members in real time. It has compatibility with Microsoft Office formats means perfect documents, every time.

[Nextcloud VM(virtual machine appliance)](https://download.nextcloudvm.com/) is a set of carefully crafted family of [*nix](https://bit.ly/2UaCC7b) scripts, which interactively guide you through a quality-controlled installation of a Nextcloud instance for Home/SME Server and scripts for Raspberry Pi 4. It is Community developed and maintained.

## Adding External Storage

[Back to the Top](#table-of-contents)

[Sabrent XTRM Q](https://www.sabrent.com/rocket-xtrmq/) is a perfect SSD for all your creative pursuits: high-res photos, videos, sound files, etc. It's perfect for saving, creating and editing available in 500GB, 1TB, 2TB, and 4TB drives.

[Shell Thunder](https://m.fledging.net/products/shell-thunder) is a high-performance Intel-Certified Thunderbolt 3 SSD Enclosure engineered for active cooling with smart fan technology. Shell Thunder is designed for 2280 and 2260 m.2 NVME SSDs for macOS and Windows.

[Orico USB4.0 NVMe SSD Enclosure](https://www.orico.cc/us/product/detail/7328.html) is a high-performance SSD Enclosure engineered with up to a 40Gbps transmission rate and 2 TB capacity. It supports Windows, macOS, and Linux devices.

[USB-C to Lightning Cable (2 m)](https://www.apple.com/shop/product/MQGH2AM/A/usb-c-to-lightning-cable-2-m) is cable to connect your iPhone, iPad, or iPod with Lightning connector to your USB-C or Thunderbolt 3 (USB-C) enabled Mac for syncing and charging, or to your USB-C enabled iPad for charging.

**More fast External Storage options for MacOS/iOS/iPadOS:**

 * [Kingston XS2000 Portable SSD](https://www.amazon.com/Kingston-Performance-Pocket-Sized-SXS2000-2000G/dp/B09F6279PY)
 * [Crucial X8](https://www.amazon.com/Crucial-X8/s?k=Crucial+X8)
 * [Samsung Portable SSD X5](https://www.samsung.com/us/computing/memory-storage/portable-solid-state-drives/portable-ssd-x5-1tb-mu-pb1t0b-am/)
 * [Samsung Portable SSD T7 Touch](https://www.samsung.com/us/computing/memory-storage/portable-solid-state-drives/portable-ssd-t7-touch-usb-3-2-500gb-black-mu-pc500k-ww/)
 * [SanDisk Professional Pro-G40 SSD](https://www.westerndigital.com/products/portable-drives/sandisk-professional-pro-g40-ssd)
 * [SanDisk Professional G-Drive ArmorATD](https://www.westerndigital.com/products/portable-drives/sandisk-professional-g-drive-armoratd-usb-3-1-hdd)
 * [WD Black P10](https://www.westerndigital.com/products/portable-drives/wd-black-p10-game-drive-usb-3-2-hdd)
 * [WD Black D10](https://www.westerndigital.com/products/external-drives/wd-black-d10-game-drive-usb-3-2-hdd)
 * [WD My Passport (5TB)](https://www.westerndigital.com/products/portable-drives/wd-my-passport-usb-3-0-hdd)
 * [OWC Envoy Pro EX With USB-C](https://www.amazon.com/OWC-Envoy-External-Storage-Solution/dp/B07T7X7HRK)
 * [LaCie Rugged SSD Pro](https://www.lacie.com/products/rugged/)
 * [LaCie Rugged RAID Shuttle](https://www.lacie.com/products/rugged/)
 * [LaCie 2big RAID](https://www.lacie.com/products/big/2big/)
 * [LaCie Mobile Drive](https://www.lacie.com/products/mobile-drive/)
 * [CalDigit AV Pro 2](https://www.caldigit.com/av-pro-2/)

## Backups

[Back to the Top](#table-of-contents)

[Proxmox Backup Server](https://www.proxmox.com/en/proxmox-backup-server) is an enterprise backup solution for backing up and restoring VMs, containers, and physical hosts. The open-source solution supports incremental backups, deduplication, Zstandard compression, and authenticated encryption.

[Borgmatic](https://github.com/modem7/docker-borgmatic) is a simple, configuration-driven backup software for servers and workstations. It protects your files with client-side encryption. Backup your databases too. Monitor it all with integrated third-party services. 

[BorgWarehouse](https://borgwarehouse.com/) is a  fast and modern WebUI for a BorgBackup's central repository server.

[Emborg](https://emborg.readthedocs.io/en/latest/) is a simple command line utility to orchestrate backups. It is built as a front-end to Borg, a powerful and fast de-duplicating backup program. 

[Vorta](https://vorta.borgbase.com/) is a backup client for macOS and Linux desktops. It integrates the mighty Borg Backup with your favorite desktop environment to protect your data from disk failure, ransomware and theft. 

[rsync.net](https://rsync.net/) is a Cloud Storage for Offsite Backup that give you an empty UNIX filesystem to access with any SSH tool. Built on ZFS for data security and fault tolerance with support for rsync/sftp/scp/borg/rclone/restic/git-annex.

[BackupPC](https://github.com/backuppc/backuppc) is a high-performance, enterprise-grade system for backing up Linux, Windows and macOS PCs and laptops to a server's disk. BackupPC is highly configurable and easy to install and maintain.

[UrBackup](https://www.urbackup.org/) is an easy to setup Open Source client/server backup system, that through a combination of image and file backups accomplishes both data safety and a fast restoration time. File and image backups are made while the system is running without interrupting current processes. Available for Windows, macOS, and Linux. 

[Kopia](https://kopia.io/) is a user-friendly desktop app for Windows, macOS, and Linux which allows you to create snapshots, define policies, and restore files quickly with Fast and Encrypted Backups. 

[rsnapshot](https://rsnapshot.org/) is a filesystem snapshot utility based on rsync. This makes it easy to make periodic snapshots of local machines, and remote machines over ssh.

[Proton Drive](https://drive.proton.me/) is an end-to-end encrypted Swiss storage space for your files, photos, and videos, ensuring that nobody, except those authorized by you, can access your data. 

[pCloud](https://www.pcloud.com/) is a secure place for your photos, videos and documents from every device, anywhere you go. pCloud starts with 10 GB free storage and automatically backup your photos and videos and free up space from your device. 

## SSD Drive Health/Data Recovery

[Back to the Top](#table-of-contents)

- [How to create a bootable installer for macOS](https://support.apple.com/en-us/HT201372)

 * Restore from Time Machine: [Restore your files](https://support.apple.com/kb/HT203981) from a Time Machine backup.

 * Reinstall macOS: Download and [reinstall MacOS](https://support.apple.com/kb/HT204904).

 * Safari (or Get Help Online): Use Safari to browse the web and find help for your Mac. Links to [Apple's support website](https://support.apple.com/) are included. Browser plug-ins and extensions are disabled.

 * Disk Utility: Use Disk Utility to [repair your disk](https://support.apple.com/kb/HT210898) or [erase your disk](https://support.apple.com/kb/HT208496) or other storage device.

 * Additional utilities are available from the Utilities menu in the menu bar, including [Startup Security Utility](https://support.apple.com/kb/HT208198) (or [Firmware Password Utility](https://support.apple.com/kb/HT204455)), and Terminal. 
 
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/182049332-16b132a4-a02f-42d7-a234-3cc1088c25d6.png">
<br />
MacOS Recovery Options
</p>

[Disk Drill](https://www.cleverfiles.com/) is a free tool that can scan and recover data from virtually any storage device — including internal Macintosh hard drives, external hard drives, cameras, iPhones, iPads, iPods, Android devices, USB flash drives, Kindles, and memory cards. It can read your device even if it is failing, unreadable, or has lost a partition. Combining several powerful scanning algorithms, Disk Drill provides a complete Mac data recovery solution.

[DriveDx](https://binaryfruit.com/drivedx) is an advanced drive-health diagnostic and monitoring utility. It not only monitors the drive’s built-in S.M.A.R.T. status, but also analyzes the changes of all drive health indicators that are closely related to SSD or HDD failures (like SSD wear out / endurance, reallocated bad sectors, offline bad sectors, pending sectors, I/O errors, and more) and alerts the user immediately if anything goes wrong.

[AmorphousDiskMark](https://apps.apple.com/us/app/amorphousdiskmark/id1168254295?mt=12) is a tool that measures storage performance.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/218423387-eee6e655-2e19-414b-bb5c-0c9a6d3215a3.png">
</p>

## Checking Battery Health

[Back to the Top](#table-of-contents)

[coconutBattery](https://www.coconut-flavour.com/coconutbattery/) is a tool that keeps you aware of your current battery health. It shows you live information about the battery quality in your Mac, iPhone and iPad.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/182049312-aeebad9f-c226-4c77-9461-50f41d6100a0.png">
<br />
Checking Battery on your Mac device.
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/182049316-87385a01-d26e-46c6-bbfc-ae5043c57763.png">
<br />
Checking Battery on your iOS device.
</p>

### Low Power Mode

**If you have a Mac laptop, you can change the options below to reduce energy use and optimize the lifespan of your battery.**

 **On your Mac, choose Apple menu  > System Settings, then click Battery in the sidebar. (You may need to scroll down.)**

 **Do any of the following:**

   * Click the pop-up menu next to Low Power Mode on the right, then choose “Always,” “Only on battery,” or “Only on power adapter.”

   * Click the Info button next to Battery Health on the right, then turn on Optimized Battery Charging and “Manage battery longevity.”

   * Click Options on the right, then turn on “Put hard disks to sleep when possible” and “Automatic graphics switching.”
        
   
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/234225969-7bce4b07-a55a-4cb9-aace-6a2f8ed1972f.png">
<br />
</p>
        
        
[Cooldown](https://goodsnooze.gumroad.com/l/cooldown) is a simple menu bar app that allows you to quickly toggle Low Power Mode on and off.

**Planned features**

  * Automatically toggle LPM at certain times.
  * Automatically toggle LPM when certain apps are opened.
  * Design improvements.
  
 <p align="center">
<img src="https://user-images.githubusercontent.com/45159366/234226010-78ab7711-3785-4152-a3da-7f193b293041.png">
<br />
</p>
      

## Charging/Powerbanks

[Back to the Top](#table-of-contents)

While the Apple Silicon Macbooks have great battery life. It's always good to have a portable powerbank for charging your device when you're traveling, conferences, etc..

* [Using USB-C cables with your Mac](https://support.apple.com/guide/mac-help/use-usb-c-cables-mchl447b9239/mac)
* [Apple USB-C Charge Cable (2m) on Amazon](https://www.amazon.com/Apple-USB-C-Charge-Cable-2m/dp/B01MQ5Z080)
* [USB-C to Lightning Cable (2 m)](https://www.apple.com/shop/product/MQGH2AM/A/usb-c-to-lightning-cable-2-m)
* [About the Apple USB-C to Lightning Cable](https://support.apple.com/en-us/HT205807)

[Anker PowerCore III (45W USB-C PD output)](https://www.amazon.com/Anker-PowerCore-Capacity-Delivery-Portable/dp/B08FX8GKJ5)

[Anker 747 Charger (GaNPrime 150W)](https://www.anker.com/products/a2340)

[Anker 737 Charger (GaNPrime 120W)](https://www.anker.com/products/a2148)

[Anker 736 Charger (Nano II 100W)](https://www.anker.com/products/a2145)
 
[Anker 735 Charger (GaNPrime 65W)](https://www.anker.com/products/a2668)
 
[Anker 733 Power Bank (GaNPrime PowerCore 65W)](https://www.anker.com/products/a1651)

[Anker 525 Power Bank 20000mAh](https://www.anker.com/products/a1287?listingPlan=b&variant=41110977642646&discount=WS24A1287011)

[Omni 20+ 20000mAh Laptop Power Bank](https://www.omnicharge.co/products/omni-20/)

[MAXOAK Portable Laptop Charger(26756mAh/99Wh), Portable Power Station with AC Outlet PD 45W USB-C Solar Generator Battery Backup Power Supply](https://www.amazon.com/Portable-TSA-Approved-MAXOAK-26756mAh-Lighting-Bluetti/dp/B07VWNV5S6)

[MAXOAK K2 185Wh/50000mAh Power Bank for Laptop](https://maxoak.net/products/maxoak-k2-185Wh-50000mah-power-bank)

[HenHot 65W USB-C Portable Charger](https://www.amazon.com/HenHot-20000mAh-Laptop-Portable-Charger/dp/B09SLCV819)

[Baseus 65W USB-C Power Bank with Built-in Cable](https://www.amazon.com/Portable-Charger-Baseus-20000mAh-Charging/dp/B08THFDRSZ)


## MacOS/iOS Security Hardening

[Back to the Top](#table-of-contents)

### Resources

 * [Signed system volume security in iOS, iPadOS, and macOS](https://support.apple.com/guide/security/signed-system-volume-security-secd698747c9/web)
 * [Protecting against malware in macOS](https://support.apple.com/guide/security/protecting-against-malware-sec469d47bd8/web)
 * [CIS(Center for Internet Security) Apple iOS Benchmarks](https://www.cisecurity.org/benchmark/apple_ios)
 * [CIS(Center for Internet Security) Apple macOS Benchmarks](https://www.cisecurity.org/benchmark/apple_os)
 * [NIST Security Technical Implementation for macOS](https://ncp.nist.gov/checklist/1017)
 * [Setting a custom umask in macOS](https://support.apple.com/en-us/HT201684)
 * [Personal Security Checklist](https://github.com/Lissy93/personal-security-checklist) is a curated checklist of 300+ tips for protecting digital security and privacy in 2022.

### Enable full disk encryption

Full disk encryption is pretty much self-explanatory. You want to encrypt your disk, so you prevent unauthorized access to your data.

To turn on full disk encryption on macOS:

1. Go to System Preferences > Security & Privacy > FileVault
2. Click on the lock on the bottom left side of the screen to authenticate (you need to authenticate to make changes, in this case, to turn on full disk encryption)
3. Click Turn On FileVault... and follow the procedure step by step

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187093922-072076a7-7c4d-4fc4-a00f-e80d12d31bc2.png">
<br />
File Vault
</p>

[Hardened Runtime](https://developer.apple.com/documentation/security/hardened_runtime) is a tool that along with System Integrity Protection (SIP), protects the runtime integrity of your software by preventing certain classes of exploits, like code injection, dynamically linked library (DLL) hijacking, and process memory space tampering. 

[System Integrity Protection (SIP)](https://support.apple.com/en-us/HT204899) is a security technology in OS X El Capitan and later that's designed to help prevent potentially malicious software from modifying protected files and folders on your Mac.

[Effaceable Storage](https://support.apple.com/guide/security/aside/sec0183122de/1/web/1) is a dedicated area of NAND storage, used to store cryptographic keys, that can be addressed directly and wiped securely.

[SepOS](https://support.apple.com/guide/security/aside/secc3e4f7a43/1/web/1) is the Secure Enclave firmware, based on an Apple-customized version of the L4 microkernel.

[Pulse](https://kean.blog/pulse/home) is a powerful logging system for Apple Platforms builtin in SwiftUI. It allows you to record and inspect logs and ```URLSession``` network requests right from your iOS app. Shared logs and view them in [Pulse Pro](https://kean.blog/pulse/pro) or use remote logging to see them in real-time. Logs are stored locally and never leave your devices.

[Lynis](https://cisofy.com/lynis/) is a security auditing tool for systems based on UNIX like Linux, macOS, BSD, and others. It performs an in-depth security scan and runs on the system itself. The primary goal is to test security defenses and provide tips for further system hardening. It will also scan for general system information, vulnerable software packages, and possible configuration issues. 

[Pareto Security](https://paretosecurity.com/) is a MenuBar app to automatically audit your Mac for basic security hygiene.

[GRR Rapid Response](https://grr-doc.readthedocs.io/) is an incident response framework focused on remote live forensics. 

[mac_apt](https://github.com/ydkhatri/mac_apt) is a DFIR (Digital Forensics and Incident Response) tool for macOS/iOS to process Mac computer full disk images (or live machines) and extract data/metadata useful for forensic investigation. It is a python based framework, which has plugins to process individual artifacts (such as Safari internet history, Network interfaces, Recently accessed files & volumes, etc..)

[AdGuard DNS](https://adguard-dns.io/en/welcome.html) is a tool that let's you control all web traffic on your devices, block ads, trackers, and malicious domains.

[Quad9](https://www.quad9.net/) is a free service that replaces your default ISP or enterprise Domain Name Server (DNS) configuration. When your computer performs any Internet transaction that uses the DNS (and most transactions do), Quad9 blocks lookups of malicious host names from an up-to-the-minute list of threats. This blocking action protects your computer, mobile device, or IoT systems against a wide range of threats such as malware, phishing, spyware, and botnets, and it can improve performance in addition to guaranteeing privacy. 


### MacOS Forensic Analysis

[Back to The Top](#table-of-contents)

**MacOS Forensic Analysis** is the process of building in-depth digital forensics knowledge of MacOS and iOS systems.
 - [SANS FOR518: Mac and iOS Forensic Analysis and Incident Response Course](https://www.sans.org/cyber-security-courses/mac-and-ios-forensic-analysis-and-incident-response/)

* [Memoryze for Mac](https://www.fireeye.com/services/freeware/memoryze.html) - Memoryze for Mac is Memoryze but then for Macs. A lower number of features, however.
* [Knockknock](https://objective-see.com/products/knockknock.html) - Displays persistent items(scripts, commands, binaries, etc.) that are set to execute automatically on MacOS.
* [macOS Artifact Parsing Tool (mac_apt)](https://github.com/ydkhatri/mac_apt) - Plugin based forensics framework for quick mac triage that works on live machines, disk images or individual artifact files.
* [MacOS Auditor](https://github.com/jipegit/OSXAuditor) - Free Mac MacOScomputer forensics tool.
* [MacOS Collector](https://github.com/yelp/osxcollector) - MacOS Auditor offshoot for live response.
* [The ESF Playground](https://themittenmac.com/the-esf-playground/) - A tool to view the events in Apple Endpoint Security Framework (ESF) in real time.

### VPN

[Back to The Top](#table-of-contents)

**VPN (Virtual Private Network)** is a service that encrypts your internet traffic on unsecured networks to protect your online identity, hide your IP address, and shield your online data from third parties. 

* [Wireguard](https://www.wireguard.com/) - A new minimal VPN Solution that is very fast.
* [Tailscale](https://tailscale.com/) - The easiest, most secure way to use WireGuard and 2FA. Tailscale helps you manage and access private or shared resources from anywhere in the world. 
* [NetBird](https://netbird.io/) - An open-source VPN management platform built on top of WireGuard® making it easy to create secure private networks for your organization or home.
* [SoftEther](https://www.softether.org/) - Multi-protocol software VPN with advanced features.
* [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
* [Pritunl](https://pritunl.com/) - OpenVPN based solution that's easy to set up.
* [sshuttle](https://github.com/apenwarr/sshuttle) - Poor man's VPN.
* [strongSwan](https://www.strongswan.org/) - Complete IPsec implementation for Linux.
* [tinc](https://www.tinc-vpn.org/) - Distributed p2p VPN.

### SSH

[Back to The Top](#table-of-contents)

**Secure Shell Protocol (SSH)** is a cryptographic network protocol for operating network services securely over an unsecured network.

* [Tailscale SSH](https://tailscale.com/kb/1193/tailscale-ssh/) is a service that allows Tailscale to manage the authentication and authorization of SSH connections on your tailnet.
* [SSHrc](https://github.com/Russell91/sshrc) - sources ~/.sshrc on your local computer after logging in remotely.
* [StormSSH](https://stormssh.readthedocs.org) - A command line tool to manage SSH connections.
* [Advanced SSH config](https://pypi.python.org/pypi/advanced-ssh-config/) - Enhances ssh_config file capabilities, completely transparent.
* [AutoSSH](https://www.harding.motd.ca/autossh/) - Automatically respawn ssh session after network interruption.
* [Cluster SSH](https://sourceforge.net/projects/clusterssh/) - Controls a number of xterm windows via a single graphical console.
* [DSH](https://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Dancer's shell / distributed shell - Wrapper for executing multiple remote shell commands from one command line.
* [Mosh](https://mosh.org/) - is a command-line program, like SSH. You can use it inside xterm, gnome-terminal, urxvt, Terminal.app, iTerm, emacs, screen, or tmux.
* [Parallel SSH](https://parallel-ssh.org/) is an asynchronous parallel SSH library designed for large scale automation. It differentiates ifself from alternatives, other libraries and higher level frameworks like Ansible or Chef.


### Firewall Filtering

[Back to The Top](#table-of-contents)

**Firewall** is a system that provides network security by filtering incoming and outgoing network traffic based on a set of user-defined rules. In general, the purpose of a firewall is to reduce or eliminate the occurrence of unwanted network communications while allowing all legitimate communication to flow freely.

[Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) is a host-based application firewall for macOS. It can be used to monitor applications, preventing or permitting them to connect to attached networks through advanced rules.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/236665250-e9ecfa42-771e-4e65-962b-6caf8972836c.png">
<br />
</p>

### MFA

[Back to The Top](#table-of-contents)

**Multifactor Authentication (MFA)** is when you sign into your online accounts - a process we call "authentication" - you're proving to the service that you are who you say you are. Traditionally that's been done with a username and a password.

[YubiKey](https://www.yubico.com/) is a security device that makes two-factor authentication as simple as possible. Instead of a code being texted to you, or generated by an app on your phone, you simply press a button on your YubiKey. Each device has a unique code built on to it, which is used to generate codes that help confirm your identity. The YubiKey USB authenticator includes NFC and has multi-protocol support including FIDO2, FIDO U2F, Yubico OTP, OATH-TOTP, OATH-HOTP, Smart card (PIV), OpenPGP, and Challenge-Response capability to give you strong hardware-based authentication.

[Authelia](https://www.authelia.com/) is an open-source authentication and authorization server providing two-factor authentication and single sign-on (SSO) for your applications via a web portal. It acts as a companion for [reverse proxies](https://github.com/authelia/authelia#proxy-support) by allowing, denying, or redirecting requests. 

[ZITADEL](https://zitadel.com/) is an open-source authentication and authorization server providing two-factor authentication combining the best of Auth0 and Keycloak. Built for the serverless era. It includes Multi-tenancy with branding customization, secure login, self-service, OpenID Connect, OAuth2.x, SAML2, LDAP, Passwordless with FIDO2 (including Passkeys), OTP, U2F, and an unlimited audit trail is there for you, ready to use.

[Microsoft Authenticator](https://support.microsoft.com/en-us/account-billing/download-and-install-the-microsoft-authenticator-app-351498fc-850a-45da-b7b6-27e523b8702a) is an app helps you sign in to your accounts when you're using two-step verification. Two-step verification helps you to use your accounts more securely because passwords can be forgotten, stolen, or compromised.

[Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en&co=GENIE.Platform%3DAndroid) is a software authenticator developed by Google that implements multi-factor authentication services using the Time-based one-time password and HMAC-based one-time password, for authenticating users of software applications.


# Wafer Level Multi-Chip Packaging Technology

[Back to the Top](#table-of-contents)

## InFO (Integrated Fan-Out) Wafer Level Packaging

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552824-33363b75-56c4-4f1a-a348-f18f107abdc5.png">
  <br />
</p>

[InFO](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/InFO.htm) is an innovative wafer level system integration technology platform, featuring high density RDL (Re-Distribution Layer) and TIV (Through InFO Via) for high-density interconnect and performance for various applications, such as mobile, and high performance computing. The InFO platform offers various package schemes in 2D and 3D that are optimized for specific applications. 

[InFO_PoP](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/InFO.htm#tbc_InFO_PoP) is the industry's 1st 3D wafer level fan-out package, features high density RDL and TIV to integrate mobile AP w/ DRAM package stacking for mobile application. Comparing to FC_PoP, InFO_PoP has a thinner profile and better electrical and thermal performances because of no organic substrate and C4 bump. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552831-604bc8ee-0bf4-434c-befe-161dbb6cf89e.png">
  <br />
  InFO_PoP 
</p>

[InFO_oS](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/InFO.htm#tbc_InFO_oS) is a packaging process that leverages InFO technology and features higher density 2/2µm RDL line width/space to integrate multiple advanced logic chiplets for 5G networking application. It enables hybrid pad pitches on SoC with minimum 40µm I/O pitch, minimum 130µm C4 Cu bump pitch and > 2X reticle size InFO on >65 x 65mm substrates.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552827-aa529f79-3e44-412d-ab4d-1cd7bb81dac0.png">
  <br />
  InFO_oS 
</p>

## Chip on Wafer on Substrate (CoWoS)
[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732295-4c0ada4e-c237-472c-8bef-58b8eb223747.png">
  <br />
</p>

[CoWoS®](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/cowos.htm) is a platform that provides best-in-breed performance and highest integration density for high performance computing applications. This wafer level system integration platform offers wide range of interposer sizes, number of HBM cubes, and package sizes. It can enable larger than 2X-reticle size (or ~1,700mm2) interposer integrating leading SoC chips with more than four HBM2/HBM2E cubes.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732340-8195fa38-c986-4de1-baa5-e69fb06100ed.png">
  <br />
  TSMC CoWoS®-S Architecture
</p>

[CoWoS-R](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/cowos.htm#tbc_CoWoS-R) is a member of CoWoS advanced packaging family leveraging InFO technology to utilize RDL interposer and to serve the interconnect between chiplets, especially in HBM(high bandwidth memory) and SoC heterogeneous integration. RDL interposer is comprised of polymer and copper traces, and it is relatively mechanically flexible. Such flexibility enhances the C4 joint integrity, and allows the new package can scale up its size to meet more complex functional demands.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732343-9645518b-69b7-4213-b6f3-934373b5176f.png">
  <br />
  TSMC CoWoS®-R Architecture
</p>

[CoWoS®-L](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/cowos.htm#tbc_CoWoS-L) is one of the last for chip packages in the CoWoS® platform, combining the merits of CoWoS®-S and InFO technologies to provide the most flexible integration using interposer with LSI (Local Silicon Interconnect) chip for die-to-die interconnect and RDL layers for power and signal delivery. The offering starts from 1.5X-reticle interposer size with 1x SoC + 4x HBM cubes and will move forward to expand the envelope to larger sizes for integrating more chips.

**The key features of CoWoS®-L service include:**

   - LSI chips for high routing density die-to-die interconnect through multiple layers of sub-micron Cu lines. The LSI chips can feature variety of connection architectures (SoC to SoC, SoC to chiplet, SoC to HBM… etc) within each product, and can also be used repeatedly for multiple products. The corresponding metal types, layer counts, and pitches align with the offering from CoWoS®-S.

   - Molding-based interposer with wide pitch of RDL layers on both front-side and back-side and TIV (Through Interposer Via) for signal and power delivery provides low loss of high frequency signal in high-speed transmission.

   - Capability of integrating additional elements, stand-alone IPD (Integrated Passive Device), right underneath the SoC die to support its signal communication with better PI/SI.

   <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732345-22e0a913-13de-456a-aa36-84d8f4a9c8db.png">
  <br />
  TSMC CoWoS®-L Architecture
</p>

# Xcode Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/141201793-f31f4899-7317-49a7-808b-6e551df23bf9.png">
  <br />
</p>

## Getting Started with Xcode

**Developer Resources:**

 * [Apple Developer Documentation for Xcode](https://developer.apple.com/documentation/xcode)
 * [Apple Professional Training Courses](https://training.apple.com/)
 * [Apple Developer Tools & SDKs](https://developer.apple.com/download/)
 * [Apple API References](https://developer.apple.com/documentation/)
 * [Learn to code with Swift Playgrounds](https://developer.apple.com/swift-playgrounds/)
 * [Develop in Swift Explorations](https://apple.co/teachingcode)
 * [Develop in Swift Fundamentals](https://apple.co/teachingcode)
 * [Develop in Swift Data Collections](https://apple.co/teachingcode)
 * [Develop in Swift App Design Workbook](https://education-static.apple.com/coding-club-kit/appworkbook.key)
 * [Swift Coding Clubs](https://www.apple.com/education/k12/teaching-code/#coding-club)

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 14 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/176965201-6573e818-3b14-42b9-a1c2-5159d4aa33a9.png">
<br />
Developing with SwiftUI in Xcode 14
</p>

[Xcode Cloud](https://developer.apple.com/xcode-cloud/) is a continuous integration and delivery service built into Xcode and designed expressly for Apple developers. It accelerates the development and delivery of high-quality apps by bringing together cloud-based tools that help you build apps, run automated tests in parallel, deliver apps to testers, and view and manage user feedback.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/176965198-b5e29ebf-4c75-4c2f-b10c-32a840371d26.jpg">
<br />
</p>

**Xcode Cloud. Source: [Apple](https://developer.apple.com/xcode-cloud/)**

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/) is a set of Apple APIs that developers can use to rapidly port their iOS apps to [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/) and take full advantage of the new capabilities on the new Apple hardware.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[TestFlight](https://developer.apple.com/testflight/) is a tool that makes it easy to invite users to test your apps and App Clips and collect valuable feedback before releasing your apps on the App Store. It allows you to invite up to 10,000 testers using just their email address or by sharing a public link.

# Core ML Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/132140794-0d4bf654-0884-4068-b5bb-eaee36c36797.png">
  <br />
</p>

## Core ML Learning Resources

[Core ML](https://developer.apple.com/documentation/coreml) is an Apple framework for integrating machine learning models into apps running on Apple devices (including iOS, watchOS, macOS, and tvOS). Core ML introduces a public file format (.mlmodel) for a broad set of ML methods including deep neural networks (both convolutional and recurrent), tree ensembles with boosting, and generalized linear models. Models in this format can be directly integrated into apps through Xcode.

[Introduction to Core ML](https://coremltools.readme.io/docs)

[Integrating a Core ML Model into your App](https://developer.apple.com/documentation/coreml/integrating_a_core_ml_model_into_your_app)

[Core ML Models](https://developer.apple.com/machine-learning/models/)

[Core ML API Reference](https://apple.github.io/coremltools/index.html)

[Core ML Specification](https://apple.github.io/coremltools/mlmodel/index.html)

[Apple Developer Forums for Core ML](https://developer.apple.com/forums/tags/core-ml)

[Top Core ML Courses Online | Udemy](https://www.udemy.com/topic/Core-ML/)

[Top Core ML Courses Online | Coursera](https://www.coursera.org/courses?query=core%20ml)

[IBM Watson Services for Core ML | IBM](https://www.ibm.com/watson/stories/coreml)

[Stable Diffusion with Core ML on Apple Silicon](https://machinelearning.apple.com/research/stable-diffusion-coreml-apple-silicon)

[Generate Core ML assets using IBM Maximo Visual Inspection | IBM](https://developer.ibm.com/technologies/iot/tutorials/ibm-maximo-visual-inspection-apple-devices/)

## Core ML Tools, Libraries, and Frameworks

[Core ML Tools](https://github.com/apple/coremltools) is a tool to convert machine learning models from third-party libraries to the Core ML format. This Python package contains the supporting tools for converting models from training libraries such as the following:

   * [TensorFlow](https://www.tensorflow.org/versions/r1.15/api_docs/python/tf)
   * TensorFlow 2](https://www.tensorflow.org/api_docs)
   * [PyTorch](https://pytorch.org/)
    
**Non-neural network frameworks:**
   * [scikit-learn](https://scikit-learn.org/stable/)
   * [XGBoost](https://xgboost.readthedocs.io/en/latest/)
   * [LibSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/)

[Create ML](https://developer.apple.com/machine-learning/create-ml/) is a tool that provides new ways of training machine learning models on your Mac. It takes the complexity out of model training while producing powerful Core ML models.

[Apple FaceLit](https://github.com/apple/ml-facelit/) is a Neural 3D Relightable Faces.

[TensorFlow](https://www.tensorflow.org) is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

[Keras](https://keras.io) is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.It was developed with a focus on enabling fast experimentation. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[XGBoost](https://xgboost.readthedocs.io/) is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way. It supports distributed training on multiple machines, including AWS, GCE, Azure, and Yarn clusters. Also, it can be integrated with Flink, Spark and other cloud dataflow systems.

[LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) is an integrated software for support vector classification, (C-SVC, nu-SVC), regression (epsilon-SVR, nu-SVR) and distribution estimation (one-class SVM). It supports multi-class classification.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

[Apple Vision](https://developer.apple.com/documentation/vision) is a framework that performs face and face landmark detection, text detection, barcode recognition, image registration, and general feature tracking. Vision also allows the use of custom Core ML models for tasks like classification or object detection.

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[CocoaPods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

# Metal Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172255611-762a151f-6891-44b2-a0cf-657005e317ff.png">
  <br />
</p>

## Metal Learning Resources

[Metal](https://developer.apple.com/metal/) is a low-level API that provides a platform-optimized, low-overhead API for developing the latest 3D pro applications and amazing games using a rich shading language with tighter integration between graphics and compute programs. To help you do more while managing ever more complex shader code, Metal adds an unparalleled suite of advanced GPU debugging tools to help you realize the full potential of your graphics code.

[Metal 3](https://developer.apple.com/metal/) is Apple's newest graphics API that introduces advanced features and compiler tools to load resources faster, compile shader binaries at build time, process complex geometry with mesh shaders, render high-resolution graphics in less time, train machine learning networks faster, and more. 

* [Apple Developer Documentation](https://developer.apple.com/documentation)

* [MetalKit](https://developer.apple.com/documentation/metalkit/)

* [Metal Shading Language Specification](https://developer.apple.com/metal/Metal-Shading-Language-Specification.pdf)

* [Using Metal Feature Set Tables](https://developer.apple.com/documentation/metal/gpu_features/using_metal_feature_set_tables/)

* [Metal Performance Shaders](https://developer.apple.com/documentation/metalperformanceshaders/)

* [Optimizing Performance with the GPU Counters Instrument](https://developer.apple.com/documentation/metal/optimizing_performance_with_the_gpu_counters_instrument?language=objc)

* [Enabling Frame Capture](https://developer.apple.com/documentation/metal/frame_capture_debugging_tools/enabling_frame_capture?language=objc)

* [Reducing the Memory Footprint of Metal Apps](https://developer.apple.com/documentation/metal/reducing_the_memory_footprint_of_metal_apps)

* [Metal Developer Tools for Windows](https://developer.apple.com/download/release/)

* [Metal Sample code](https://developer.apple.com/metal/sample-code/)

* [Metal plugin for TensorFlow](https://developer.apple.com/metal/tensorflow-plugin/)

* [Metal Developer discussions](https://developer.apple.com/forums/tags/metal/)


## Metal Tools, Libraries, and Frameworks

[MTLDevice](https://developer.apple.com/documentation/metal/mtldevice) is the Metal interface to a GPU that you use to draw graphics or do parallel computation.

[Metal-cpp](https://developer.apple.com/metal/cpp/)  is a low-overhead C++ interface for Metal that helps you add Metal functionality to graphics apps, games, and game engines that are written in C++. [Sample Code](https://developer.apple.com/metal/LearnMetalCPP.zip)

[Metal plugin for TensorFlow](https://developer.apple.com/metal/tensorflow-plugin/) is a TensorFlow-Metal PluggableDevice that adds improvements to machine learning training with new operations accelerated on GPU, custom operations, and distributed training support.

[MetalFX](https://developer.apple.com/videos/play/wwdc2022/10103/) is a new API that provides platform optimized graphics effects for Metal applications. With MetalFX Upscaling, your application can now render frames at a lower resolution, reducing rendering time, without compromising rendering quality. We'll also show you how and when to use its two effects: spatial upscaling, which delivers substantial performance gains, and temporal AA and upscaling, which delivers the highest quality rendering.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172254747-9308be59-4d79-4677-a5ec-cf40f5762cf7.png">
  <br />
 MetalFX Rendering. Credit: Apple
</p>

[MetalPetal](https://github.com/MetalPetal/MetalPetal) is a GPU accelerated image and video processing framework based on Metal designed to provide real-time processing for still image and video with easy to use programming interfaces.

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation) is a framework provides a base layer of functionality for apps and frameworks, including data storage and persistence, text processing, date and time calculations, sorting and filtering, and networking. The classes, protocols, and data types defined by Foundation are used throughout the macOS, iOS, watchOS, and tvOS SDKs.

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore) is a graphics rendering and animation infrastructure that provides high frame rates and smooth animations without burdening the CPU and slowing down your app.

[Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)is a framework based on the Quartz advanced drawing engine. It provides low-level, lightweight 2D rendering with unmatched output fidelity.

[Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics) is a framework that implements hardware-accelerated graphics for macOS running in a virtual machine, hereafter known as the guest. The macOS operating system provides a graphics driver that runs inside the guest, communicating with the framework in the host operating system to take advantage of Metal-accelerated graphics.

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[CocoaPods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

##  VSCode Development

[Back to the Top](#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140833078-77973dcf-d3a6-421f-b6a7-b6e63fb1e97c.png">
<br />
</p>

 * [VS Code Documentation](https://code.visualstudio.com/docs)

 * [Working with GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)

[Visual Studio Code](https://code.visualstudio.com) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832435-49e53589-e9e1-47fe-a1bd-d9800cfc1274.png">
<br />
VS Code
</p>

[Visual Studio Code Marketplace](https://marketplace.visualstudio.com/VSCode) is a marketplace for all extensions for Visual Studio, Azure DevOps Services, Azure DevOps Server and Visual Studio Code.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832440-0247a088-4eeb-4c57-ae7d-90894d56d629.png">
<br />
VS Code Marketplace
</p>

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code. Also, from any repo or pull request on GitHub you can simply press the period (.) key on your keyboard to bring up the browser-based VS Code environment with the source code file ready for editing. That dot (.) press to bring up the web-based VS Code editor takes you to https://github.dev/.

[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/) is a tool that defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references.

### VS Code Extensions for Developer Productivity

[Back to the Top](#table-of-contents)

[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) is a service/ extension that enables you to collaboratively edit and debug with others in real time, regardless of the programming languages you're using or app types you're building. You can instantly and securely share your current project, start a joint debugging session, share terminal instances, forward localhost web apps, have voice calls, and more.

[GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs) is a Visual Studio Code extension that allows you to edit GitHub Gists and repositories from the comfort of your favorite editor. You can open, create, delete, fork and star gists and repositories, and then seamlessly begin editing files as if they were local, without ever cloning, pushing or pulling anything.

[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) is an extension for Visual Studio Code that launches a development local Server with live reload feature for static & dynamic pages.

[GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) is an extension for Visual Studio Code that allows you to review and manage GitHub pull requests and issues in Visual Studio Code.

[Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal) is an extension for Visual Studio Code that lets you run terminal command directly in the Editor.

[Profile Switcher](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher) is an extension for Visual Studio Code that allows you to switch between different profiles you have created.

[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) is an extension for Visual Studio Code that gets the Material Design icons into your VS Code.

[One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) is an extension for Visual Studio Code that adds Atom's iconic One Dark theme, which is one of the most installed themes for VS Code.

[VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) is an extension for Visual Studio Code that brings icons to your Visual Studio Code setup.

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) is an extension for Visual Studio Code that helps you visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.

[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) is an extension for Visual Studio Code that will display inline in the editor the size of the imported/required package. The extension utilizes webpack with babili-webpack-plugin in order to detect the imported size.

[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) is an extension for Visual Studio Code that gives you everything you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more).

[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.

[Auto-Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) is an extension for Visual Studio Code that synchronizes Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist.

[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) is an extension for Visual Studio Code that lets you mark lines of code and jump to them.

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) is an extension for Visual Studio Code that improves your code commenting by annotating with alert, informational, TODOs, and more.

[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) is an extension for Visual Studio Code that works as a spelling checker for source code.

[CSS Peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) is an extension for Visual Studio Code that allows peeking to css ID and class strings as definitions from html files to respective CSS. It also allows peek and goto definition.

[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) is an extension for Visual Studio Code that enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) is an extension for Visual Studio Code that is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) is an extension for Visual Studio Code that autocompletes npm modules in import statements.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) is an extension for Visual Studio Code that autocompletes filenames.

[Relative Path](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath) is an extension for Visual Studio Code that gets the relative url paths from files in the current workspace.

[Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete) is an extension for Visual Studio Code that provides path completion for visual studio code.

[Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) is an extension for Visual Studio Code that updates your discord status with a rich presence.

[Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) is an extension for Visual Studio Code that runs code snippets or code files for multiple languages: C/C++, Java, JavaScript, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, BASH/SH, C#, F#, .NET Core, TypeScript, CoffeeScript, Scala, Swift, Julia, OCaml, R, Elixir, Clojure, Haxe, Objective-C, Rust, Racket, Scheme, Kotlin, Dart, Haskell, Nim, D, CUDA, and custom command.

[Kite](https://marketplace.visualstudio.com/items?itemName=kiteco.kite) is an extension for Visual Studio Code that provides an AI-powered programming assistant that helps you write code faster inside Visual Studio Code. Kite works for all major programming languages: Python, Java, Go, PHP, C/C#/C++, Javascript, HTML/CSS, Typescript, React, Ruby, Scala, Kotlin, Bash, Vue and React.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is an extension for Visual Studio Code that provides an AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time in your favorite IDE.


## Unreal Engine 5 Development

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162537763-308611ef-a619-4fcd-99bf-bfe328c50f27.png">
  <br />
</p>

**Recommend Hardware Requirements:**

* **OS:** MacOS 12 or later

* **CPU/GPU:** M1 Pro (10-core CPU, 16-core GPU) 

* **RAM:** 32 GB 

* **Storage:** 1 TB 

[Unreal Engine 5](https://www.unrealengine.com/unreal-engine-5) is a game engine developed by Epic Games with the world's most open and advanced real-time 3D creation tool. Continuously evolving to serve not only its original purpose as a state-of-the-art game engine, today it gives creators across industries the freedom and control to deliver cutting-edge content, interactive experiences, and immersive virtual worlds. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162538256-a3390573-88b8-4925-a92e-70a56da951b3.png">
  <br />
  Unreal Engine 5 with Big City Sample Project
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693087-56cfbc91-3398-425c-90a1-6a2479ca3fce.png">
  <br />
</p>

 Unreal Engine Twinmotion. Source: [Unreal Engine](https://www.unrealengine.com/en-US/blog/twinmotion-2021-1-is-here)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/180627376-15ab099e-f433-4e0b-bf29-3ebf48b95fe8.png">
  <br />
  Unreal Engine 5 Project browser
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/180627379-afa5a3d7-c50a-4d9f-94c8-3b14d39cea36.png">
  <br />
  Unreal Engine 5 Vehicle Project Demo
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172468555-e7f7b4d6-1ba0-4f37-b3dd-f6b17c90b0f1.png">
  <br />
  Unreal Engine Marketplace
</p>

### Unreal Engine Tools
[Back to the Top](#table-of-contents)

[Blueprint Visual Scripting](https://docs.unrealengine.com/en-US/Engine/Blueprints/index.html) is a complete gameplay scripting system in Unreal Engine based on the concept of using a node-based interface to create gameplay elements from within Unreal Editor. As with many common scripting languages, it is used to define object-oriented (OO) classes or objects in the engine.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/180627381-f123e873-909c-410a-887e-51b2ba659439.png">
  <br />
 Blueprint Visual Scripting UI 
</p>

[Datasmith](https://www.unrealengine.com/en-US/datasmith) is a collection of tools and plugins that bring entire pre-constructed scenes and complex assets created in a variety of industry-standard design applications into Unreal Engine.

[Chaos Physics](https://docs.unrealengine.com/5.0/en-US/InteractiveExperiences/Physics/ChaosPhysics/Overview/) is a Beta feature that is the light-weight physics simulation solution used in Fortnite, and it includes the following major features.

   * RBAN (Rigid Body Animation Nodes)
   * Destruction
   * Cloth
   * Ragdoll
   * Vehicles

[Niagara VFX System](https://docs.unrealengine.com/5.0/en-US/RenderingAndGraphics/Niagara/) is one of two tools you can use to create and adjust visual effects (VFX) inside Unreal Engine 5 (UE5). Before Niagara, the primary way to create and edit visual effects in UE4 was to use [Cascade](https://docs.unrealengine.com/4.27/en-US/RenderingAndGraphics/ParticleSystems). It has many of the same of particle manipulation methods that Cascade offers, the way you interact and build visual effects with Niagara is vastly different.

[MetaHuman Creator](https://www.unrealengine.com/en-US/metahuman-creator) is a free cloud-based app that empowers anyone to create photorealistic digital humans, complete with hair and clothing, in minutes. MetaHumans come fully rigged and ready to animate in your Unreal Engine projects.

[Twinmotion](https://www.twinmotion.com/en-US) is a real-time 3D immersion software that produces high-quality images, panoramas and standard or 360° VR videos in seconds. Developed for architecture, construction, urban planning and landscaping professionals.

[Bridgew by Quixel](https://www.unrealengine.com/en-US/bridge) is a gateway to create a world of 3D content right inside the Unreal Engine. it includes Megascans—the world's largest library of AAA, cinema-quality assets based on real-world scan data.

[Lumen](https://docs.unrealengine.com/5.0/en-US/RenderingFeatures/Lumen/TechOverview/) is an Unreal Engine 5 feature that uses multiple ray tracing methods to solve Global Illumination and Reflections. Screen traces are done first, followed by a more reliable method. It uses Software Ray Tracing through Signed Distance Fields by default, but can achieve higher quality on supporting video cards when Hardware Ray Tracing is enabled. **Note:** Lumen works on Apple Silicon with Unreal 5.2 release. 

[Nanite](https://docs.unrealengine.com/5.0/en-US/RenderingFeatures/Nanite/) is Unreal Engine 5's new virtualized geometry system which uses a new internal mesh format and rendering technology to render pixel scale detail and high object counts. It intelligently does work on only the detail that can be perceived and no more.

[Procedural Content Generation Framework (PCG)](https://docs.unrealengine.com/5.2/en-US/procedural-content-generation--framework-in-unreal-engine/) is a toolset for creating your own procedural content inside Unreal Engine. It provides artists and designers the ability to build fast, iterative tools and content of any complexity ranging from asset utilities, such as buildings or biome generation, up to entire worlds. 

[Unreal Engine's VCam system](https://docs.unrealengine.com/5.2/en-US/virtual-cameras-in-unreal-engine/) is a Cine Camera in Unreal Engine that uses a modular component system to manipulate camera data and output the final results to a variety of external output devices. In addition, the Virtual Camera system provides its functionality while in the editor and during Play In Editor (PIE) or Standalone Game mode. 

[nDisplay](https://docs.unrealengine.com/5.2/en-US/ndisplay-overview-for-unreal-engine/) is a tool in Unreal Engine that describes how multiple computers work together in an nDisplay rendering network.

[Unreal Engine Marketplace](https://unrealengine.com/marketplace/en-US/store) is Unreal Engine's Store that has a library Of Textures, Models, Animations, Tutorials, and More for creating amazing 3D projects and games.

[UnrealBuildTool (UBT)](https://docs.unrealengine.com/5.0/en-US/ProductionPipelines/BuildTools/UnrealBuildTool) is a tool that manages the process of building UE4 source code across a variety of build configurations.

[UnrealHeaderTool (UHT)](https://docs.unrealengine.com/5.0/en-US/ProductionPipelines/BuildTools/UnrealHeaderTool) is a custom parsing and code-generation tool supporting the UObject system.

[AutomationTool](https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/BuildTools/AutomationTool) is a generic system used to automate processes, including testing and building games.

[Proxy Geometry Tool](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/ProxyGeoTool/) is a tool-set that was developed as a way to increase your Unreal Engine 4 (UE4) project's performance while keeping the visual quality of your project uneffected.

[Replay System](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/ReplaySystem/) is a tool which can record gameplay for later viewing. This feature is available in all games, from live, multiplayer games played on dedicated servers, to single-player games, and even including Play-In-Editor sessions. At a high level, the Replay system works by using a DemoNetDriver to read data drawn from the built-in replication system, similar to how a NetDriver operates in a live, networked gameplay environment.

### Unreal Engine Developer Resources

[Back to the Top](#table-of-contents)

 * [How to migrate your Unreal Engine 4 projects to Unreal Engine 5 Early Access quickly and smoothly](https://docs.unrealengine.com/5.0/en-US/MigrationGuide/)

 * [Multi-platform development - Unreal Engine](https://www.unrealengine.com/en-US/features/multi-platform-development)

 * [Unreal Engine 5 Documentation](https://docs.unrealengine.com/5.0/)

 * [Unreal Engine Forums](https://forums.unrealengine.com/)

**Note:** you will need to create an Epic Games account to download Unreal Engine.

 * [Sign-up for Epic Games Acount](https://www.epicgames.com/account/password)
 
 * [Sign-up for Epic Games GitHub](https://github.com/EpicGames/Signup)
 
 * [macOS Development Requirements for Unreal Engine](https://docs.unrealengine.com/5.0/en-US/hardware-and-software-specifications-for-unreal-engine/)
 
 * [iOS, iPadOS, and tvOS Development on Unreal Engine](https://docs.unrealengine.com/5.0/en-US/ios-ipados-and-tvos-support-for-unreal-engine/)
 
 * [XR Development on Unreal Engine](https://docs.unrealengine.com/5.0/en-US/developing-for-xr-experiences-in-unreal-engine)

 * [Setting Up Visual Studio for Unreal Engine](https://docs.unrealengine.com/en-us/Programming/Development/VisualStudioSetup)

 * [Unreal Engine Performance and Profiling](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/PerformanceAndProfiling/)

 * [Unreal Engine C++ API Reference](https://docs.unrealengine.com/5.0/en-US/API/index.html)

 * [Unreal Engine Blueprint API Reference](https://docs.unrealengine.com/5.0/en-US/BlueprintAPI/index.html)

 * [Unreal Engine Python API Reference](https://docs.unrealengine.com/5.0/en-US/PythonAPI/index.html)
 
  * [Unreal Online Learning](https://www.unrealengine.com/en-US/onlinelearning-courses) is a free learning platform that offers hands-on video courses and guided learning paths.
 
 * [Unreal Engine Authorized Training Program](https://www.unrealengine.com/en-US/training-partners) 

 * [Unreal Engine for education](https://www.unrealengine.com/en-US/education/)

 * [Unreal Engine Training & Simulation](https://www.unrealengine.com/en-US/industry/training-simulation)
 
 * [Unreal Engine | NVIDIA Developer](https://developer.nvidia.com/unrealengine)

 * [Autodesk for Games](https://www.autodesk.com/campaigns/autodesk-for-games)

 * [Getting Started with DirectX 12 Ultimate](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

 * [Getting Started with Vulkan](https://www.khronos.org/vulkan/)

 * [Getting Started with Apple Metal](https://developer.apple.com/metal/)
 
 ### Unreal Engine 5 Development Books

 * [Unreal Engine 5 for Beginners: Dive into the world of game development with Unreal Engine 5 to build amazing 3D games by Sargey Rose](https://www.amazon.com/Unreal-Engine-Beginners-development-amazing/dp/1800568088)

 * [Blueprints Visual Scripting for Unreal Engine 5: Unleash the true power of Blueprints to create impressive games and applications in UE5, 3rd Edition by by Marcos Romero, Brenden Sewell, Luis Cataldi](https://www.amazon.com/Blueprints-Visual-Scripting-Unreal-Engine/dp/180181158X/) 

 * [Unreal Engine 5 Character Creation, Animation, and Cinematics: Create custom 3D assets and bring them to life in Unreal Engine 5 using MetaHuman, Lumen, and Nanite by Henk Venter, Wilhelm Ogterop](https://www.amazon.com/Unreal-Character-Creation-Animation-Cinematics/dp/1801812446/) 

 * [Elevating Game Experiences with Unreal Engine 5: Bring your game ideas to life using the new Unreal Engine 5 and C++, 2nd Edition by Goncalo Marques, Devin Sherry, David Pereira, Hammad Fozi](https://www.amazon.com/Elevating-Game-Experiences-Unreal-Engine/dp/1803239867/) 

 * [Unreal Engine 5 RPG Development with C++ and Blueprint: Volume I: Basics, Combat, and VFX by Dr. Chihming Chiu](https://www.amazon.com/Unreal-Engine-RPG-Development-Blueprint/dp/B0BHC586PM/r) 

 * [Build Stunning Real-time VFX with Unreal Engine 5: Start your journey into Unreal particle systems to create realistic visual effects using Niagara by Hrishikesh Andurlekar](https://www.amazon.com/Build-Stunning-Real-time-Unreal-Engine/dp/1801072418/) 

 * [Game Development Patterns with Unreal Engine 5: Build maintainable and scalable systems with C++ and Blueprint by Stuart Butler , Tom Oliver](https://www.amazon.com/Game-Development-Patterns-Unreal-Engine/dp/1803243252/) 

 * [Unreal Engine 5 Shaders and Effects Cookbook: Over 70 recipes for creating materials and advanced shading techniques, 2nd Edition by Brais Brenlla Ramos](https://www.amazon.com/Unreal-Engine-Shaders-Effects-Cookbook/dp/1837633088/) 

 * [Game Development with Unreal Engine 5: Learn the Basics of Game Development in Unreal Engine 5 by by Mitchell Lynn, Cliff Sharif](https://www.amazon.com/Game-Development-Unreal-Engine-English/dp/9355513445/) 

 * [Unreal Engine C++ the Ultimate Developer's Handbook: Learn C++ and Unreal Engine by Creating a Complete Action Game by Stephen Seth Ulibarri](https://www.amazon.com/Unreal-Engine-Ultimate-Developers-Handbook/dp/B089M2H7J1/) 

 * [Unreal Engine from Zero to Proficiency (Foundations): A Step-by-step guide to your first game with Unreal Engine by Patrick Felicia](https://www.amazon.com/Unreal-Engine-Proficiency-Foundations-Step/dp/B0B6XJDR3K/) 

 * [Reimagining Characters with Unreal Engine's MetaHuman Creator: Elevate your films with cinema-quality character designs and motion capture animation by Brian Rossney, Ciaran Kavanagh](https://www.amazon.com/Reimagining-characters-Unreal-MetaHuman-Creator/dp/1801817723/) 
 
 
## Unity Development
[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147710942-5da4fef2-5525-4942-98bc-81421b2144e5.png">
  <br />
</p>

**Recommend Hardware Requirements:**

* **OS:** MacOS 12 or later

* **CPU/GPU:** M1 Pro (10-core CPU, 16-core GPU) 

* **RAM:** 32 GB 

* **Storage:** 1 TB 

[Unity](https://unity.com) is a cross-platform game development platform. Unity can be used to build high-quality 3D and 2D games, deploy them across mobile, desktop, VR/AR, consoles or the Web, and connect with loyal and enthusiastic players and customers. Checkout the [Unity Manual](https://docs.unity3d.com/Manual/UnityOverview.html) to get started on your Unity projects.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/221379487-ea59279e-94f0-4caa-9cfb-cb8f48db13e4.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693059-97d5428c-cf3c-48f4-bb29-d35e4044d1d9.png">
  <br />
</p>

Unity Terrain project. Source: [Unity](https://blog.unity.com/technology/evolving-the-unity-editor-ux)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/221379631-40782ba1-c5a2-4854-8cdd-2e4fa3bd63bf.png">
  <br />
  Unity Hub Installs
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147710657-16a6e35a-c78e-408b-a836-45b21a342f11.png">
  <br />
  Unity Asset Store
</p>

## Unity Tools

[Unity Hub](https://unity.com/unity-hub) is a tool that helps manage multiple installations of the Unity Editor, create new projects, and access your work.

[Unity Asset Store](https://assetstore.unity.com)is Unity's Store that has a library Of Textures, Models, Animations, Tutorials, and More for creating amazing 3D projects and games.

[Unity Plus](https://store.unity.com/products/unity-plus) is a version of Unity for small businesses and serious hobbyists get more functionality and training resources to power up their projects.

[Unity Pro](https://store.unity.com/products/unity-pro) is a version of Unity to create and operate amazing applications and immersive experiences with a complete solution for professionals across industries.

[Unity Enterprise](https://store.unity.com/products/unity-enterprise) is a version of Unity for large teams creating at scale, Unity Enterprise delivers comprehensive technology, resources, and support that fuel innovation, reduce risk, and power your success.

[Unity XR](https://docs.unity3d.com/Manual/XR.html) is a plug-in framework that enables XR providers to integrate with the Unity engine and make full use of its features.

[Unity MARS](https://unity.com/products/unity-mars) is a tool that helps you create augmented reality (AR) apps with better workflows and purpose built authoring tools.

[Unity Build Server](https://unity.com/products/unity-build-server) is a tool that offloads your Unity project builds to network hardware, empowering your creative team to iterate more, produce higher quality products, and ship on time.

[Unity Teams](https://unity.com/products/unity-teams) is a tool that helps you and your team create together, faster. It makes it simple to save, share and sync your Unity projects with anyone.

[Unity Automated QA](https://unity.com/products/automated-qa) is a tool that shortens the development feedback loop with on-demand tests that anyone on your team can create and run without writing code.

[Unity Simulation Pro](https://unity.com/products/unity-simulation-pro) is a tool that unlocks the true power of scalable simulations through a simulation-optimized version of the Unity runtime.

[Unity Forma](https://unity.com/products/unity-forma) is a tool that brings the power of real-time 3D to your marketing. It turns 3D product data into interactive 3D configurators, stunning images and more.

[Unity Reflect](https://unity.com/products/unity-reflect) is a tool that helps create an experience immersive and collaborative real-time 3D environments, including in AR and VR, for better decision-making across your entire project lifecycle.

[Unity Reflect Develop](https://unity.com/products/unity-reflect-develop) is a tool that builds your own custom applications to address any problem across the entire building and infrastructure lifecycle for internal or commercial deployment.

[Unity ArtEngine](https://unity.com/products/unity-artengine) is Unity’s material authoring tool. Harnessing the power of assisted creation, the tool helps creators accelerate production pipelines.

[Unity Machine Learning Agents](https://unity.com/products/machine-learning-agents) is a tol that helps train and embed intelligent agents by leveraging state-of-the-art deep learning technology.

[Unity Essential Success ](https://unity.com/products/unity-essential-success) is a tool that is your dedicated Support Coordinator and experienced Unity engineers are ready to help.

[Bolt Visual scripting](https://unity.com/products/unity-visual-scripting) is a tool in Unity empowers creators to develop gameplay mechanics or interaction logic with a visual, graph-based system, instead of writing traditional lines of code.

[VisualLive](https://unity.com/products/visuallive) is a tool for construction professionals can visualize designs and collaborate in real-time by overlaying large BIM and CAD files onto jobsites using AR.

[Professional Services: Optimization Accelerator](https://unity.com/products/optimization-accelerator) is atool that boosts your project and your productivity in a four-day sprint with hands-on guidance from a Unity engineer. It will help you analyze performance problems, test solutions, and implement improvements.

[Odin Inspector Enterprise](https://unity.com/products/odin) is a tool that optimizes your project workflows and save thousands of development hours.

[Multiplay](https://unity.com/products/multiplay) is a resilient, multicloud hybrid server hosting and matchmaking platform without having to build and maintain your own infrastructure. Proven at scale in some of the world’s biggest games.

[Vivox](https://unity.com/products/vivox) is a voice and text comms tool that boosts player engagement, retention rates and create immersive multiplayer experiences by leveraging an easy-to-implement, feature-rich voice and text chat service.

[Relayᴮᴱᵀᴬ](https://unity.com/products/relay) is a tool that provides a great multiplayer gaming experiences with Unity’s Relay service that's now in open beta.

[Lobbyᴮᴱᵀᴬ](https://unity.com/products/lobby) is a tool that connects your players for great multiplayer gaming experiences with Lobby that's now in Open Beta.

[Cloud Codeᴮᴱᵀᴬ](https://unity.com/products/cloud-code) is a tool that runs your game logic in the cloud as serverless functions and interact with other backend services.

[Cloud Saveᴮᴱᵀᴬ](https://unity.com/products/cloud-save) is a tool that builds better player experiences by storing game data to the cloud.

[Furioos](https://unity.com/products/furioos) is a tool that streams fully interactive 3D experiences from Unity, other real-time 3D platforms, and Windows applications with peak visual quality in any web browser.

[OctaneRender® for Unity](https://unity.com/products/otoy-octanerender) is a tool that lets you harness physically accurate rendering directly in Unity and compose gorgeous, cinematic-quality scenes with OctaneRender materials and lighting.

[Pacelab WEAVR](https://unity.com/products/weavr) is a tool that provides a complete XR platform that enables any company, in any industry, to develop and manage enterprise-scale immersive training.

[Interact](https://unity.com/products/interact) is a tool that creates advanced real-time, human-centric simulations on any VR configuration for training, visualization, and safety.

[Prespective](https://unity.com/products/prespective) is a tool that helps you design and simulate your machine, factory, or system in Unity real-time 3D. Create common ground among stakeholders and speed up decision processes with improved visualization tools.

[Pixyz](https://unity.com/products/pixyz) is a tool that lets you can quickly import, prep, and optimize your large CAD, mesh and point cloud models for real-time visualizations in Unity.

[Plastic SCM Cloud Edition](https://unity.com/products/plastic-scm) is a tool that makes Collaboration more efficient with a performant, easy-to-use version control system (VCS) made for programmers, artists and designers.

[Backtrace](https://unity.com/products/backtrace) is a game crash management platform that delivers uninterrupted game experiences by automating your response to errors.

[SpeedTree®](https://store.speedtree.com/) is a group of vegetation programming and modeling software products developed and sold by Interactive Data Visualization, Inc. that generates virtual foliage for animations, architecture and in real time for video games and demanding real time simulations. [Unity Technologies acquired SpeedTree in July 2021](https://investors.unity.com/news/news-details/2021/Unity-Acquires-Interactive-Data-Visualization-Inc.-IDV-Creators-of-SpeedTree-Environment-Creation-Suite/default.aspx).

[ParSec](https://parsec.app/) is a the ultimate remote desktop, powerful enough for teams of developers, designers, architects, and engineers to get the job done and work together from anywhere. [Unity Technologies acquired Parsec in August 2021](https://unity.com/our-company/newsroom/unity-enters-agreement-acquire-parsec).

[SyncSketch](https://syncsketch.com) is a collaboration software for visual artists that allows a team to view, review, and provide feedback on each other’s work. It includes support for both 2D and 3D assets as well as video. As of [December 2021 SyncSketch has been acquired by Unity Technologies](https://blog.syncsketch.com/news/sycncsketch-acquired-by-unity/).

[Weta Digital](https://www.wetafx.co.nz/) is a digital visual effects company created by [Peter Jackson](https://www.imdb.com/name/nm0001392/). It produced the digital special effects for Heavenly Creatures and the Lord of the Rings. [Unity Technologies acquired Weta Digital in November 2021](https://unity.com/our-company/newsroom/unity-announces-intent-acquire-weta-digital).


## Unity Developer Resources

[Unity Knowledge Base](https://support.unity.com/hc/en-us) is a library of articles that helps you troubleshoot common problems, whether it’s creating an account, importing assets, or baking a scene.

 * [Unity Forum](https://forum.unity.com/)

 * [Unity Issue Tracker](https://issuetracker.unity3d.com/)

 * [Unity Certifications](https://unity.com/products/unity-certifications)

 * [Learn game development with Unity](https://learn.unity.com/courses)
 
 * [Getting Started with Apple Metal](https://developer.apple.com/metal/)
 
 * [Autodesk for Games](https://www.autodesk.com/campaigns/autodesk-for-games)

 * [Unity Courses, Training, and Lessons on Udemy](https://www.udemy.com/topic/unity/)

 * [Learn Unity 3D with Online Courses and Lessons on edX](https://www.edx.org/learn/unity-3d)

 * [Unity Certified Programmer Exam Preparation on Coursera](https://www.coursera.org/specializations/unity-certified-programmer)
 
### Unity Develop Books

 * [Hands-On Unity 2022 Game Development: Learn to use the latest Unity 2022 features to create your first video game in the simplest way possible, 3rd Edition by Nicolas Alejandro Borromeo](https://www.amazon.com/Hands-Unity-2022-Game-Development/dp/1803236914/)
 
 * [Unity Game Development Cookbook: Essentials for Every Game 1st Edition by Paris Buttfield-Addison, Jon Manning, Tim Nugent](https://www.amazon.com/Unity-Game-Development-Cookbook-Virtual/dp/1491999152/)
 
 * [Unity 3D Game Development: Designed for passionate game developers―Engineered to build professional games by Anthony Davis, Travis Baptiste, Russell Craig](https://www.amazon.com/Unity-Game-Development-design-beautiful/dp/1801076146/)
 
 * [Game Programming with Unity and C#: A Complete Beginner’s Guide 1st ed. Edition by Casey Hardman](https://www.amazon.com/Game-Programming-Unity-Complete-Beginners/dp/1484256557/)
 
 * [Learning C# by Developing Games with Unity: Get to grips with coding in C# and build simple 3D games in Unity 2022 from the ground up, 7th Edition by Harrison Ferrone](https://www.amazon.com/Learning-Developing-Games-Unity-coding/dp/1837636877/)
 
 * [Mind-Melding Unity and Blender for 3D Game Development: Unleash the power of Unity and Blender to create amazing games
by Spencer Grey](https://www.amazon.com/Mind-Melding-Unity-Blender-Game-Development/dp/1801071551/)
 
 * [C# Game Programming Cookbook for Unity 3D 2nd Edition by Jeff W. Murray](https://www.amazon.com/Game-Programming-Cookbook-Unity-3D-ebook/dp/B08VBMBGN2/)
 
 * [Unity in Action, Third Edition: Multiplatform game development in C# 3rd Edition by Joe Hocking](https://www.amazon.com/Unity-Action-Third-Joseph-Hocking/dp/1617299332/)
 
 * [Massively Multiplayer Game Programming With Unity 3d and Mirror: The Ultimate Guide to Building and Hosting Your MMOGS by Dr Chihming Chiu](https://www.amazon.com/Massively-Multiplayer-Programming-Unity-Mirror/dp/022884410X/)
 
 * [Advanced Unity Game Development: Build Professional Games with Unity, C#, and Visual Studio 1st ed. Edition by Victor G Brusca](https://www.amazon.com/Advanced-Unity-Game-Development-Professional/dp/148427850X/)
 
 * [Mathematics for Game Programming and Computer Graphics: Explore the essential mathematics for creating, rendering, and manipulating 3D virtual environments by Penny de Byl](https://www.amazon.com/Mathematics-Game-Programming-Computer-Graphics/dp/1801077339/)


# Blender Development
[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211848-53765800-e25e-11eb-872d-732aa2e74ad1.png">
  <br />
</p>

**Recommended Hardware Requirements:**

* **OS:** MacOS 12 or later

* **CPU/GPU:** M1 Pro (10-core CPU, 16-core GPU) 

* **RAM:** 32 GB 

* **Storage:** 1 TB 

[Blender](https://www.blender.org) is a professional, free and open-source 3D computer graphics software toolset used for creating animated films, visual effects, art, 3D printed models, interactive 3D applications and video games. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/221347484-b09ef929-3cd2-4d41-9a31-e41dc7d9d6da.png">
  <br />
</p>


## Blender Developer Resources

 * [Blender Documentation](https://docs.blender.org/)

 * [Blender Foundation](https://www.blender.org/foundation/)

 * [Blender Community Fourm](https://devtalk.blender.org/)

 * [Blender Foundation Certification Training](https://www.blender.org/certification/)

 * [Blender Cloud Courses](https://cloud.blender.org/courses)

 * [Blender Institute](https://www.blender.org/institute/)

 * [Blender Demo Project files](https://www.blender.org/download/demo-files/)

 * [Blender YouTube Tutorials and Demos](https://www.youtube.com/user/BlenderFoundation)

 * [Blender Donations & Sponsors](https://www.blender.org/foundation/donation-payment/)

 * [Blender Education](https://www.blender.org/get-involved/)

 * [Blender Network](https://www.blendernetwork.org/)

 * [BlenderNation](https://www.blendernation.com/category/blender/add-ons/)

 * [Blender Market(The indie market for Blender creators)](https://www.blendermarket.com/categories/scripts-and-addons)

## Blender Tools and Addons

[Blender](https://www.blender.org) comes packed with import/export support for many different programs.

Including:

   - Image(JPEG, JPEG2000, PNG, TARGA, OpenEXR, DPX, Cineon, Radiance HDR, SGI Iris, TIFF)

   - Video(AVI, MPEG and Quicktime (on MacOS)).

   - 3D(Alembic, 3D Studio (3DS), COLLADA (DAE), Filmbox (FBX), Autodesk (DXF), Wavefront (OBJ), DirectX (x), Lightwave (LWO), Motion Capture (BVH), SVG, Stanford   PLY, STL, VRML, VRML97, X3D).


[Eevee](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html) is Blender’s realtime render engine focused on speed and interactivity while achieving the goal of rendering PBR materials. Eevee can be used interactively in the 3D Viewport but also produce high quality final renders. Eevee materials are created using the same shader nodes as Cycles, making it easy to render existing scenes. For Cycles users, this makes Eevee work great for previewing materials in realtime.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211855-5a04cf80-e25e-11eb-94cf-f55ecf273049.png">
  <br />
</p>

**Eevee final render – “Temple”. Source: [Dominik Graf](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html#id2)**

[Cycles](https://www.blender.org/features/rendering/) is Blender’s ray-trace based production render engine.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338215-6ec91f00-b4ca-11eb-9c9e-f5cf377ca3c4.png">
  <br />
</p>

 **Blender's Cycles Render Engine. Source: [Blender](https://www.blender.org)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338217-6ffa4c00-b4ca-11eb-92d0-9aa30230495d.png">
  <br />
</p>

 **Blender VFX(Visual Effects). Source: [Blender](https://www.blender.org)**

[FreeStyle](https://docs.blender.org/manual/en/dev/render/freestyle/index.html) is an edge- and line-based non-photorealistic (NPR) rendering engine. It relies on mesh data and z-depth information to draw lines on selected edge types. Various line styles can be added to produce artistic (“hand drawn”, “painted”, etc.) or technical (hard line) looks.

[Modifiers](https://docs.blender.org/manual/en/dev/modeling/modifiers/introduction.html) are automatic operations that affect an object in a non-destructive way. With modifiers, you can perform many effects automatically that would otherwise be too tedious to update manually (such as subdivision surfaces) and without affecting the base geometry of your object.

[UV Unwrapping](https://docs.blender.org/manual/en/latest/modeling/meshes/editing/uv/unwrapping/introduction.html) is a tool that let's you easily unwrap your mesh right inside Blender, and use image textures or paint your own directly onto the model.

[UV Sculpt](https://docs.blender.org/manual/en/dev/modeling/meshes/editing/uv/uv_sculpt.html) is a “mode” in Blender that allows you to grab, pinch and smooth UVs, just like Sculpt Mode.

[Dedicated Workspace](https://www.blender.org/features/sculpting/#dedicated-workspace) is a feature of sculpting organic subjects using the built-in sculpting feature set of Blender.

[Brushes](https://docs.blender.org/manual/en/latest/sculpt_paint/sculpting/introduction.html) is a feature in Blender that comes with built-in brushes such as Crease, Clay Strips, Pinch, Grab, Smooth, Mask and many more.

[Dynamic topology( dyntopo)](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/adaptive.html) is a dynamic tessellation sculpting method, which adds and removes details on the fly, whereas regular sculpting only affects the shape of a mesh.

[Masking](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/hide_mask.html#mask) is a feature used while sculpting, areas might be hidden behind parts of the mesh or they might be too close to other parts. To work through these, it is useful to isolate parts of a mesh to sculpt on. This can be done by either completely hiding parts of the mesh or by masking areas that can not be sculpted on.

[Grease Pencil](https://www.blender.org/features/grease-pencil/) is a particular type of Blender object that allow you to draw in the 3D space. It can be use to make traditional 2D animation, cut-out animation, motion graphics or use it as storyboard tool among other things.

[Constraints](https://docs.blender.org/manual/en/2.80/animation/constraints/index.html) are a way to control an object’s properties (e.g. its location, rotation, scale), using either plain static values (like the “limit” ones), or another object, called “target” (like e.g. the “copy” ones).

[Shape keys](https://docs.blender.org/manual/en/2.80/animation/shape_keys/introduction.html) are used to deform objects into new shapes for animation. In other terminology, shape keys may be called “morph targets” or “blend shapes”. The most popular use cases for shape keys are in character facial animation and in tweaking and refining a skeletal rig. They are particularly useful for modeling organic soft parts and muscles where there is a need for more control over the resulting shape than what can be achieved with combination of rotation and scale.

[Motion Paths](https://docs.blender.org/manual/en/2.80/animation/motion_paths.html) is a tool allows you to visualize the motion of points as paths over a series of frames. These points can be object origins and bone joints.

[Simulations](https://www.blender.org/features/simulation/) is a tool that allows you to create amazing Simulations such as a crumbling building, rain, fire, smoke, fluid, cloth or full on destruction.

[Blender Video Editor](https://www.blender.org/features/video-editing/) is a video editor that comes with a built-in video sequence editor allows you to perform basic actions like video cuts and splicing, as well as more complex tasks like video masking or color grading.

[Blender Compositing](https://www.blender.org/features/vfx/#compositing) is a feature that comes with an impressive library of nodes for creating camera fx, color grading, vignettes and much more
Render-layer support. Along with the ability to render to multiLayer OpenEXR files.

[Blender Motion Tracking](https://www.blender.org/features/vfx/#motion-tracking) is a feature that provides production ready camera and object tracking, allowing you to import raw footage, track it, mask areas and reconstruct the camera movements live in your 3d scene.

### Blender Development Books

 * [3D Environment Design with Blender: Enhance your modeling, texturing, and lighting skills to create realistic 3D scenes by Abdelilah Hamdani , Carlos Barreto](https://www.amazon.com/Photorealistic-Nature-Environment-Creation-Blender/dp/1803235853/)
 
 * [Blender 3D Incredible Models: A comprehensive guide to hard-surface modeling, procedural texturing, and rendering
by Arijan Belec](https://www.amazon.com/Blender-Incredible-Models-comprehensive-hard-surface/dp/1801817812/)

 * [Blender Pro Tips: How Professionals Create 3D Models by Arijan Belec](https://www.amazon.com/Blender-Pro-Tips-Professionals-Create-ebook/dp/B0BTKJVDGK/)
  
 * [Blender 3D By Example: A project-based guide to learning the latest Blender 3D, EEVEE rendering engine, and Grease Pencil, 2nd Edition by Oscar Baechler, Xury Greer](https://www.amazon.com/Blender-3D-Example-project-based-rendering/dp/178961256X/)
 
 * [Taking Blender to the Next Level: Implement advanced workflows such as geometry nodes, simulations, and motion tracking for Blender production pipelines by Ruan Lotter](https://www.amazon.com/Taking-Blender-Next-Level-simulations/dp/1803233567/)
 
 * [The Complete Guide to Blender Graphics: Computer Modeling & Animation 7th Edition by John M. Blain](https://www.amazon.com/Complete-Guide-Blender-Graphics-Animation/dp/103212167X/)
  
 * [Shading, Lighting, and Rendering with Blender EEVEE: Create amazing concept art 12 times faster using a real-time rendering engine 
by Sammie Crowder](https://www.amazon.com/Shading-Lighting-Rendering-Blender-EEVEE-ebook/dp/B09V1CR61X/)
 
 * [Blender 3.2: The beginner's guide by Allan Brito](https://www.amazon.com/Blender-3-2-beginners-Allan-Brito/dp/B0B8RC4KL7/)
 
 * [Sculpting the Blender Way: Explore Blender's 3D sculpting workflows and latest features, including Face Sets, Mesh Filters, and the Cloth brush by Xury Greer](https://www.amazon.com/Sculpting-Blender-Way-sculpting-workflows/dp/1801073872/)
  
 * [Mind-Melding Unity and Blender for 3D Game Development: Unleash the power of Unity and Blender to create amazing games
by Spencer Grey](https://www.amazon.com/Mind-Melding-Unity-Blender-Game-Development/dp/1801071551/)

 * [Squeaky Clean Topology in Blender: Create accurate deformations and optimized geometry for characters and hard surface models by Michael Steppig](https://www.amazon.com/Squeaky-Clean-Topology-Blender-deformations/dp/1803244089/)
 
 * [Learn Blender Simulations the Right Way: Create attractive and realistic animations with Mantaflow, rigid and soft bodies, and Dynamic Paint by Stephen Pearson](https://www.amazon.com/Learn-Blender-Simulations-Right-Way/dp/1803234156/)
 
 * [Game Development with Blender and Godot: Leverage the combined power of Blender and Godot for building a point-and-click adventure game by Kumsal Obuz](https://www.amazon.com/Development-Blender-Godot-point-click/dp/1801816026/)
  
 * [Beginner’s Guide to Creating Characters in Blender Paperback by 3dtotal Publishing](https://www.amazon.com/Beginners-Guide-Creating-Characters-Blender/dp/1912843137/)


# Virtualization
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/139736405-f98ea7e6-899c-4140-ba16-efd8caa1d856.png">
  <br />
</p>


### Developer Quick Links

- [Amazon Elastic Compute Cloud (EC2) M1 Mac instances for macOS](https://aws.amazon.com/about-aws/whats-new/2021/12/amazon-ec2-m1-mac-instances-macos/)

 - [Running macOS in a Virtual Machine on Apple Silicon Macs](https://developer.apple.com/documentation/virtualization/running_macos_in_a_virtual_machine_on_apple_silicon_macs?language=objc) - Install and run macOS in a virtual machine using the Virtualization framework.

 - [Running Intel Binaries in Linux VMs with Rosetta](https://developer.apple.com/documentation/virtualization/running_intel_binaries_in_linux_vms_with_rosetta?language=objc) - Running x86_64 Linux binaries under ARM Linux on Apple silicon.

 - [Virtualize macOS on a Mac](https://developer.apple.com/documentation/virtualization/virtualize_macos_on_a_mac?language=objc) - Configure and run macOS guests on Apple silicon Mac computers.

 - [Virtualize Linux on a Mac](https://developer.apple.com/documentation/virtualization/virtualize_linux_on_a_mac?language=objc) - Configure and run Linux guests on Apple silicon and Intel-based Mac computers.

## Virtualization Tools and Frameworks

[Apple Hypervisor](https://developer.apple.com/documentation/hypervisor) is a framework that builds virtualization solutions on top of a lightweight hypervisor, without third-party kernel extensions. Hypervisor provides C APIs so you can interact with virtualization technologies in user space, without writing kernel extensions (KEXTs). As a result, the apps you create using this framework are suitable for distribution on the [Mac App Store](https://www.appstore.com/).

[Apple Virtualization Framework](https://developer.apple.com/documentation/virtualization) is a framework that provides high-level APIs for creating and managing virtual machines on Apple silicon and Intel-based Mac computers. This framework is used to boot and run a Linux-based operating system in a custom environment that you define. It also supports the [Virtio specification](https://www.redhat.com/en/virtio-networking-series), which defines standard interfaces for many device types, including network, socket, serial port, storage, entropy, and memory-balloon devices.

[Apple Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics) is a framework that implements hardware-accelerated graphics for macOS running in a virtual machine, hereafter known as the guest. The operating system provides a graphics driver that runs inside the guest, communicating with the framework in the host operating system to take advantage of Metal-accelerated graphics.

[Cilicon](https://github.com/traderepublic/Cilicon) is a macOS App that leverages Apple's Virtualization Framework to create, provision and run ephemeral virtual machines with minimal setup or maintenance effort. You should be able to get up and running with your self-hosted CI in less than an hour.

[Parallels Desktop](https://www.parallels.com) is a Desktop Hypervisor that delivers the fastest, easiest and most powerful application for running Windows/Linux on Mac (including the new [Apple M1 chip](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/)) and ChromeOS.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880057-df697a80-8292-11eb-8484-9bbc02592377.jpg">
<br />
Parallels Desktop for Mac
</p>

[UTM](https://getutm.app/) is a full featured system emulator and virtual machine host for iOS and macOS. It is based off of [QEMU](https://www.qemu.org/) that allows you to run Windows, Linux, and more on your Mac, iPhone, and iPad.

 - [UTM (SE) for iOS/iPadOS](https://getutm.app/install/)
 
 - [UTM for macOS](https://mac.getutm.app/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/164793036-c84684fb-be06-4452-bfc9-32f77fb8059f.png">
  <br />
 Ubuntu on UTM
</p>

[VMware Fusion 22H2](https://blogs.vmware.com/teamfusion/2022/07/just-released-vmware-fusion-22h2-tech-preview.html) is a software hypervisor developed by VMware for Mac computers.It creates a virtual machine and install an operating system (such as Windows or Linux) inside that virtual machine.

  * Windows 11 on Intel and Apple Silicon, with 2D graphics and networking support.
  * VMTools installation support for Windows 11 guest operating system on M1-based Macs.
  * Virtual TPM device with fast encryption support.
  * Improved Linux support on M1.
  * 3D Graphics HW Acceleration and OpenGL 4.3(Requires Linux 5.19+ & Mesa 22.1.3+) in Linux virtual machines.
  * Universal Binary for Apple Silicon and Intel Macs.
  
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/182049352-b899b356-57c0-4ec0-8fb1-ff394a1f6403.png">
  <br />
 Windows 11 on VMware Fusion
</p>

[Tart](https://github.com/cirruslabs/tart) is a virtualization toolset to build, run and manage virtual machines on Apple Silicon.

   * Tart uses Apple's own Virtualization.Framework for [near-native performance](https://browser.geekbench.com/v5/cpu/compare/14966395?baseline=14966339).
   * Push/Pull virtual machines from any OCI-compatible container registry.
   * Use Tart Packer Plugin to automate VM creation.
   * Built-in CI integration.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552497-4c820684-5217-452b-ae1e-0e764a9a14b5.png">
  <br />
Tart
</p>

[Multipass](https://multipass.run/) is a tool to generate cloud-style Ubuntu VMs quickly on Linux, macOS, and Windows. It uses [KVM](https://www.redhat.com/en/topics/virtualization/what-is-KVM) on Linux, [Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/) on Windows, and [HyperKit](https://github.com/moby/hyperkit) on macOS.

[VMware Horizon](https://www.vmware.com/products/horizon.html) is a digital workspace with the efficient delivery of virtual desktops and applications that equips workers anywhere, anytime, and on any device.

[VMware Carbon Black](https://www.vmware.com/products/whats-new/carbon-black.html) is a cloud–native endpoint protection platform combines the intelligent system hardening and behavioral prevention needed to keep emerging threats at bay.

[Proxmox Virtual Environment(VE)](https://www.proxmox.com/en/) is a complete open-source platform for enterprise virtualization. It includes a built-in web interface that you can easily manage VMs and containers, software-defined storage and networking, high-availability clustering, and multiple out-of-the-box tools on a single solution.

[VirtManager](https://github.com/virt-manager/virt-manager) is a graphical tool for managing virtual machines via libvirt. Most usage is with QEMU/KVM virtual machines, but Xen and libvirt LXC containers are well supported. Common operations for any libvirt driver should work.

[oVirt](https://www.ovirt.org) is an open-source distributed virtualization solution, designed to manage your entire enterprise infrastructure. oVirt uses the trusted KVM hypervisor and is built upon several other community projects, including libvirt, Gluster, PatternFly, and Ansible.Founded by Red Hat as a community project on which Red Hat Enterprise Virtualization is based allowing for centralized management of virtual machines, compute, storage and networking resources, from an easy-to-use web-based front-end with platform independent access.

[KVM (for Kernel-based Virtual Machine)](https://www.linux-kvm.org/page/Main_Page) is a full virtualization solution for Linux on x86 hardware containing virtualization extensions (Intel VT or AMD-V). It consists of a loadable kernel module, kvm.ko, that provides the core virtualization infrastructure and a processor specific module.

[QEMU](https://www.qemu.org) is a fast processor emulator using a portable dynamic translator. QEMU emulates a full system, including a processor and various peripherals. It can be used to launch a different Operating System without rebooting the PC or to debug system code.

[macOS-Simple-KVM](https://github.com/foxlet/macOS-Simple-KVM) is a set of tools to easily set up a quick macOS VM in QEMU, accelerated by KVM.

[Quickemu](https://github.com/wimpysworld/quickemu) is a program that quickly create and run optimised Windows, macOS and Linux desktop virtual machines.

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) is an open source Virtual Machine Monitor (VMM) that runs on top of [KVM](https://www.kernel.org/doc/Documentation/virtual/kvm/api.txt). The project focuses on exclusively running modern, cloud workloads, on top of a limited set of hardware architectures and platforms. Cloud workloads refers to those that are usually run by customers inside a cloud provider. Cloud Hypervisor is implemented in [Rust](https://www.rust-lang.org/) and is based on the [rust-vmm](https://github.com/rust-vmm) crates.

[Xen](https://github.com/xen-project/xen) is focused on advancing virtualization in a number of different commercial and open source applications, including server virtualization, Infrastructure as a Services (IaaS), desktop virtualization, security applications, embedded and hardware appliances, and automotive/aviation.

[Packer](https://www.packer.io/) is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

[Vagrant](https://www.vagrantup.com/) is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past. It provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

## Virtualization Concepts & Terminologies

[HVM (Hardware Virtual Machine)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/virtualization_types.html) is a virtualization type that provides the ability to run an operating system directly on top of a virtual machine without any modification, as if it were run on the bare-metal hardware.

[PV(ParaVirtualization)](https://wiki.xenproject.org/wiki/Paravirtualization_(PV)) is an efficient and lightweight virtualization technique introduced by the Xen Project team, later adopted by other virtualization solutions. PV does not require virtualization extensions from the host CPU and thus enables virtualization on hardware architectures that do not support Hardware-assisted virtualization.

[Network functions virtualization (NFV)](https://www.vmware.com/topics/glossary/content/network-functions-virtualization-nfv) is the replacement of network appliance hardware with virtual machines. The virtual machines use a hypervisor to run networking software and processes such as routing and load balancing. NFV allows for the separation of communication services from dedicated hardware, such as routers and firewalls. This separation means network operations can provide new services dynamically and without installing new hardware. Deploying network components with network functions virtualization only takes hours compared to months like with traditional networking solutions.

[Software Defined Networking (SDN)](https://www.vmware.com/topics/glossary/content/software-defined-networking) is an approach to networking that uses software-based controllers or application programming interfaces (APIs) to communicate with underlying hardware infrastructure and direct traffic on a network. This model differs from that of traditional networks, which use dedicated hardware devices (routers and switches) to control network traffic.

[Virtualized Infrastructure Manager (VIM)](https://www.cisco.com/c/en/us/td/docs/net_mgmt/network_function_virtualization_Infrastructure/3_2_2/install_guide/Cisco_VIM_Install_Guide_3_2_2/Cisco_VIM_Install_Guide_3_2_2_chapter_00.html) is a service delivery and reduce costs with high performance lifecycle management Manage the full lifecycle of the software and hardware comprising your NFV infrastructure (NFVI), and maintaining a live inventory and allocation plan of both physical and virtual resources.

[Management and Orchestration(MANO)](https://www.etsi.org/technologies/open-source-mano) is an ETSI-hosted initiative to develop an Open Source NFV Management and Orchestration (MANO) software stack aligned with ETSI NFV. Two of the key components of the ETSI NFV architectural framework are the NFV Orchestrator and VNF Manager, known as NFV MANO.

[Magma](https://www.magmacore.org/) is an open source software platform that gives network operators an open, flexible and extendable mobile core network solution. Their mission is to connect the world to a faster network by enabling service providers to build cost-effective and extensible carrier-grade networks. Magma is 3GPP generation (2G, 3G, 4G or upcoming 5G networks) and access network agnostic (cellular or WiFi). It can flexibly support a radio access network with minimal development and deployment effort.

[OpenRAN](https://open-ran.org/) is an intelligent Radio Access Network(RAN) integrated on general purpose platforms with open interface between software defined functions. Open RANecosystem enables enormous flexibility and interoperability with a complete openness to multi-vendor deployments.

[Open vSwitch(OVS)](https://www.openvswitch.org/)is an open source production quality, multilayer virtual switch licensed under the open source Apache 2.0 license. It is designed to enable massive network automation through programmatic extension, while still supporting standard management interfaces and protocols (NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag).

[Edge](https://www.ibm.com/cloud/what-is-edge-computing) is a distributed computing framework that brings enterprise applications closer to data sources such as IoT devices or local edge servers. This proximity to data at its source can deliver strong business benefits, including faster insights, improved response times and better bandwidth availability.

[Multi-access edge computing (MEC)](https://www.etsi.org/technologies/multi-access-edge-computing) is an Industry Specification Group (ISG) within ETSI to create a standardized, open environment which will allow the efficient and seamless integration of applications from vendors, service providers, and third-parties across multi-vendor Multi-access Edge Computing platforms.

[Virtualized network functions(VNFs)](https://www.juniper.net/documentation/en_US/cso4.1/topics/concept/nsd-vnf-overview.html) is a software application used in a Network Functions Virtualization (NFV) implementation that has well defined interfaces, and provides one or more component networking functions in a defined way. For example, a security VNF provides Network Address Translation (NAT) and firewall component functions.

[Cloud-Native Network Functions(CNF)](https://www.cncf.io/announcements/2020/11/18/cloud-native-network-functions-conformance-launched-by-cncf/) is a network function designed and implemented to run inside containers. CNFs inherit all the cloud native architectural and operational principles including Kubernetes(K8s) lifecycle management, agility, resilience, and observability.

[Physical Network Function(PNF)](https://www.mpirical.com/glossary/pnf-physical-network-function) is a physical network node which has not undergone virtualization. Both PNFs and VNFs (Virtualized Network Functions) can be used to form an overall Network Service.

[Network functions virtualization infrastructure(NFVI)](https://docs.vmware.com/en/VMware-vCloud-NFV/2.0/vmware-vcloud-nfv-reference-architecture-20/GUID-FBEA6C6B-54D8-4A37-87B1-D825F9E0DBC7.html) is the foundation of the overall NFV architecture. It provides the physical compute, storage, and networking hardware that hosts the VNFs. Each NFVI block can be thought of as an NFVI node and many nodes can be deployed and controlled geographically.

[Virtualization-based Security (VBS)](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-vbs) is a hardware virtualization feature to create and isolate a secure region of memory from the normal operating system.

[Hypervisor-Enforced Code Integrity (HVCI)](https://docs.microsoft.com/en-us/windows-hardware/drivers/bringup/device-guard-and-credential-guard) is a mechanism whereby a hypervisor, such as Hyper-V, uses hardware virtualization to protect kernel-mode processes against the injection and execution of malicious or unverified code. Code integrity validation is performed in a secure environment that is resistant to attack from malicious software, and page permissions for kernel mode are set and maintained by the hypervisor.

[NVIDIA virtual GPU (vGPU)](https://www.nvidia.com/en-us/data-center/virtual-solutions/) is a software enables powerful GPU performance for workloads ranging from graphics-rich virtual workstations to data science and AI, enabling IT to leverage the management and security benefits of virtualization as well as the performance of NVIDIA GPUs required for modern workloads.

[AMD MxGPU](https://www.amd.com/en/graphics/workstation-virtual-graphics) is a hardware-based virtualized GPU solution, is built on industry standard SR-IOV (Single-Root I/O Virtualization) technology and allows multiple virtualized users per physical GPU to work remotely.

# Docker
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521410-2e32c900-954e-11eb-8311-065fa0099546.png">
  <br />
</p>

### Running Docker on Apple Silicon (M1/M2)

**[Docker Desktop for Apple silicon](https://docs.docker.com/desktop/mac/apple-silicon/)**

**[Lima](https://github.com/lima-vm/lima)** is a tool that launches Linux virtual machines with automatic file sharing and port forwarding (similar to WSL2), and [containerd](https://containerd.io/). It's a great free and open-source alternative for [Docker Desktop](https://www.docker.com/products/docker-desktop).

#### Install Lima using Homebrew

```brew install lima docker docker-credential-helper```

**[Colima](https://github.com/abiosoft/colima)** is a container runtimes on macOS (and Linux) with minimal setup.

**Included Features:**

   * M1/M2 Macs and Intel support
    
   * Docker and Containerd support
    
   * Kubernetes
    
   * Port Forwarding
    
   * Volume mounts
    
#### Installing Colima

**Homebrew**

```brew install colima```

**MacPorts**

```sudo port install colima```

**Nix**

```nix-env -iA nixpkgs.colima```

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**Container Architecture. Source: [Containerd.io](https://containerd.io)**

## Docker Learning Resources

[Docker Training Program](https://www.docker.com/dockercon/training)

[Docker Certified Associate (DCA) certification](https://training.mirantis.com/dca-certification-exam/)

[Docker Documentation | Docker Documentation](https://docs.docker.com/)

[The Docker Workshop](https://courses.packtpub.com/courses/docker)

[Docker Courses on Udemy](https://www.udemy.com/topic/docker/)

[Docker Courses on Coursera](https://www.coursera.org/courses?query=docker)

[Docker Courses on edX](https://www.edx.org/learn/docker)

[Docker Courses on Linkedin Learning](https://www.linkedin.com/learning/topics/docker)

## Docker Tools
 
[Lima](https://github.com/lima-vm/lima) is a tool that launches Linux virtual machines with automatic file sharing and port forwarding (similar to WSL2), and [containerd](https://containerd.io/). It's a great free and open-source alternative for [Docker Desktop](https://www.docker.com/products/docker-desktop).

[Colima](https://github.com/abiosoft/colima) is a container runtimes on macOS (and Linux) with minimal setup.

[Docker](https://www.docker.com/) is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly working in collaboration with cloud, Linux, and Windows vendors, including Microsoft.

[Docker Enterprise](https://www.mirantis.com/software/docker/docker-enterprise/) is a subscription including software, supported and certified container platform for CentOS, Red Hat Enterprise Linux (RHEL), Ubuntu, SUSE Linux Enterprise Server (SLES), Oracle Linux, and Windows Server 2016, as well as for cloud providers AWS and Azure. In [November 2019 Docker's Enterprise Platform business was acquired by Mirantis](https://www.mirantis.com/company/press-center/company-news/mirantis-acquires-docker-enterprise/).

[Docker Desktop](https://www.docker.com/products/docker-desktop) is an application for MacOS and Windows machines for the building and sharing of containerized applications and microservices. Docker Desktop delivers the speed, choice and security you need for designing and delivering containerized applications on your desktop. Docker Desktop includes Docker App, developer tools, Kubernetes and version synchronization to production Docker Engines.

[Docker Hub](https://hub.docker.com/) is the world's largest library and community for container images. Browse over 100,000 container images from software vendors, open-source projects, and the community.

[Docker Compose](https://docs.docker.com/compose/) is a tool that was developed to help define and share multi-container applications. With Docker Compose, you can create a YAML file to define the services and with a single command, can spin everything up or tear it all down.

[Docker Swarm](https://docs.docker.com/engine/swarm/) is a Docker-native clustering system swarm is a simple tool which controls a cluster of Docker hosts and exposes it as a single "virtual" host.

[Dockerfile](https://docs.docker.com/engine/reference/builder/) is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.

[Docker Containers](https://www.docker.com/resources/what-container) is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

[Docker Engine](https://www.docker.com/products/container-runtime) is a container runtime that runs on various Linux (CentOS, Debian, Fedora, Oracle Linux, RHEL, SUSE, and Ubuntu) and Windows Server operating systems. Docker creates simple tooling and a universal packaging approach that bundles up all application dependencies inside a container which is then run on Docker Engine.

[Docker Images](https://docs.docker.com/engine/reference/commandline/images/) is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings. Images have intermediate layers that increase reusability, decrease disk usage, and speed up docker build by allowing each step to be cached. These intermediate layers are not shown by default. The SIZE is the cumulative space taken up by the image and all its parent images.

[Docker Network](https://docs.docker.com/engine/reference/commandline/network/) is a that displays detailed information on one or more networks.

[Docker Daemon](https://docs.docker.com/config/daemon/) is a service started by a system utility, not manually by a user. This makes it easier to automatically start Docker when the machine reboots. The command to start Docker depends on your operating system. Currently, it only runs on Linux because it depends on a number of Linux kernel features, but there are a few ways to run Docker on MacOS and Windows as well by configuring the operating system utilities.

[Docker Storage](https://docs.docker.com/storage/storagedriver/select-storage-driver/) is a driver controls how images and containers are stored and managed on your Docker host.

[Kitematic](https://kitematic.com/) is a simple application for managing Docker containers on Mac, Linux and Windows letting you control your app containers from a graphical user interface (GUI).

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.


# Kubernetes
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95383873-a884d800-08a0-11eb-8eaf-57af5b119f56.png">
  <br />
</p>

**Running Kubernetes Locally on Apple Silicon (M1/M2)**

**[kind](https://kind.sigs.k8s.io/)** is a tool for running local Kubernetes clusters using Docker container “nodes”. It was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

**macOS home-brew command**

 ```brew install kind```


**[Okra (Orchestration with Kubernetes on Apple)](https://www.macstadium.com/orka)** is a virtualization layer created for Mac build infrastructure, Orka allows you to orchestrate macOS in a cloud environment using Kubernetes on genuine Apple hardware.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732013-d0b9a6d3-d135-49df-bf2b-cc1f4e8970b4.png">
  <br />
  OKRA CLI
</p>

**[Colima](https://github.com/abiosoft/colima)** is a container runtimes on macOS (and Linux) with minimal setup.

**Included Features:**

   * M1/M2 Macs and Intel support
    
   * Docker and Containerd support
    
   * Kubernetes
    
   * Port Forwarding
    
   * Volume mounts
    
#### Installing Colima

**Homebrew**

```brew install colima```

**MacPorts**

```sudo port install colima```

**Nix**

```nix-env -iA nixpkgs.colima```


## Kubernetes Learning Resources

[Kubernetes (K8s)](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications.

[Getting Kubernetes Certifications](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[Getting started with Kubernetes on AWS](https://aws.amazon.com/kubernetes/)

[Kubernetes on Microsoft Azure](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Intro to Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Azure Red Hat OpenShift ](https://azure.microsoft.com/en-us/services/openshift/)

[Getting started with Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

[Getting started with Kubernetes on Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[Getting started with Kubernetes on IBM](https://www.ibm.com/cloud/learn/kubernetes)

[Red Hat OpenShift on IBM Cloud](https://www.ibm.com/cloud/openshift)

[Enable OpenShift Virtualization on Red Hat OpenShift](https://developers.redhat.com/blog/2020/08/28/enable-openshift-virtualization-on-red-hat-openshift/)

[YAML basics in Kubernetes](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Elastic Cloud on Kubernetes](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker and Kubernetes](https://www.docker.com/products/kubernetes)

[Running Apache Spark on Kubernetes](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[Kubernetes Across VMware vRealize Automation](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid)

[All the Ways VMware Tanzu Works with AWS](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu Education](https://tanzu.vmware.com/education)

[Using Ansible in a Cloud-Native Kubernetes Environment](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Managing Kubernetes (K8s) objects with Ansible](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Setting up a Kubernetes cluster using Vagrant and Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Running MongoDB with Kubernetes](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[Understanding the new GitLab Kubernetes Agent](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Intro Local Process with Kubernetes for Visual Studio 2019](https://devblogs.microsoft.com/visualstudio/introducing-local-process-with-kubernetes-for-visual-studio%E2%80%AF2019/)

[Kubernetes Contributors](https://www.kubernetes.dev/)

[KubeAcademy from VMware](https://kube.academy/)

[Kubernetes Tutorials from Pulumi](https://www.pulumi.com/docs/tutorials/kubernetes/)

[Kubernetes Playground by Katacoda](https://www.katacoda.com/courses/kubernetes/playground)

[Scalable Microservices with Kubernetes course from Udacity ](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)

## Kubernetes Tools, Frameworks, and Projects

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for running containerized applications.

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) is serverless Kubernetes, with a integrated continuous integration and continuous delivery (CI/CD) experience, and enterprise-grade security and governance. Unite your development and operations teams on a single platform to rapidly build, deliver, and scale applications with confidence.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) is a tool that runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability.

[AWS Controllers for Kubernetes (ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/) is a new tool that lets you directly manage AWS services from Kubernetes. ACK makes it simple to build scalable and highly-available Kubernetes applications that utilize AWS services.

[Container Engine for Kubernetes (OKE)](https://www.oracle.com/cloud-native/container-engine-kubernetes/) is an Oracle-managed container orchestration service that can reduce the time and cost to build modern cloud native applications. Unlike most other vendors, Oracle Cloud Infrastructure provides Container Engine for Kubernetes as a free service that runs on higher-performance, lower-cost compute.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Red Hat Openshift](https://www.openshift.com/) is a fully managed Kubernetes platform that provides a foundation for on-premises, hybrid, and multicloud deployments.

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[Rook](https://rook.io/) is a tool that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances.

[Helm](https://helm.sh/) is a Kubernetes Package Manager tool that makes it easier to install and manage Kubernetes applications.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking.

[KubeFlow](https://www.kubeflow.org/) is a tool dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[MicroK8s](https://microk8s.io/) is a tool that delivers the full Kubernetes experience. In a Fully containerized deployment with compressed over-the-air updates for ultra-reliable operations. It is supported on Linux, Windows, and MacOS.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features) is a well integrated, turn-key, conformant Kubernetes platform, optimized for your multi-cloud environments developed by Canonical.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app) is a toll that allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment.

[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge.

[Lens](https://k8slens.dev/)  is the most powerful IDE for people who need to deal with Kubernetes clusters on a daily basis. It has support for MacOS, Windows and Linux operating systems.

[Flux CD](https://fluxcd.io/) is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you've supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don't need a separate continuous delivery tool.

[Platform9 Managed Kubernetes (PMK)](https://platform9.com/managed-kubernetes/) is a Kubernetes as a service that ensures fully automated Day-2 operations with 99.9% SLA on any environment, whether in data-centers, public clouds, or at the edge.

# Ansible
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113448802-62bd4e00-93b1-11eb-9114-419e758af23b.png">
  <br />
</p>

**[Mac Development Ansible Playbook by Jeff Geerling](https://github.com/geerlingguy/mac-dev-playbook)**

## Ansible Learning Resources

[Ansible](https://www.ansible.com/) is a simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. It uses a very simple language (YAML, in the form of Ansible Playbooks) that allows you to describe your automation jobs in a way that approaches plain English. Ansible works on Linux (Red Hat EnterPrise Linux(RHEL) and Ubuntu) and Microsoft Windows.

[Red Hat Training for Ansible](https://www.ansible.com/products/training-certification)

[Top Ansible Courses Online from Udemy](https://www.udemy.com/topic/ansible/)

[Introduction to Ansible: The Fundamentals on Coursera](https://www.coursera.org/projects/ansible-fundamentals)

[Learning Ansible Fundamentals on Pluralsight](https://www.pluralsight.com/courses/ansible-fundamentals)

[Introducing Red Hat Ansible Automation Platform 2.1](https://www.ansible.com/blog/introducing-red-hat-ansible-automation-platform-2.1)

[Ansible Documentation](https://docs.ansible.com/ansible/latest/index.html)

[Ansible Galaxy User Guide](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)

[Ansible Use Cases](https://www.ansible.com/use-cases?hsLang=en-us)

[Ansible Integrations](https://www.ansible.com/integrations?hsLang=en-us)

[Ansible Collections Overview](https://github.com/ansible-collections/overview/blob/main/README.rst)

[Working with playbooks](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html)

[Ansible for DevOps Examples by Jeff Geerling](https://github.com/geerlingguy/ansible-for-devops)

[Getting Started: Writing Your First Playbook - Ansible](https://www.ansible.com/blog/getting-started-writing-your-first-playbook)

[Working With Modules in Ansible](https://docs.ansible.com/ansible/latest/user_guide/modules.html)

[Ansible Best Practices: Roles & Modules](https://www.ansible.com/resources/webinars-training/ansible-best-practices-roles-modules)

[Working with command line tools for Ansible](https://docs.ansible.com/ansible/latest/user_guide/command_line_tools.html)

[Encrypting content with Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html)

[Using vault in playbooks with Ansible](https://docs.ansible.com/ansible/latest/user_guide/playbooks_vault.html)

[Using Ansible With Azure](https://docs.microsoft.com/en-us/azure/developer/ansible/overview)

[Configuring Ansible on an Azure VM](https://docs.microsoft.com/en-us/azure/developer/ansible/install-on-linux-vm)

[How to Use Ansible: An Ansible Cheat Sheet Guide from DigitalOcean](https://www.digitalocean.com/community/cheatsheets/how-to-use-ansible-cheat-sheet-guide)

[Intro to Ansible on Linode | Spatial Labs](https://spatial-labs.dev/posts/202101072328-intro-to-ansible-on-linode/)

## Ansible DevOps Tools Integration

[Ansible Automation Hub](https://www.ansible.com/products/automation-hub) is the official location to discover and download supported [collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html#collections), included as part of an Ansible Automation Platform subscription. These content collections contain modules, plugins, roles, and playbooks in a downloadable package.

[Collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html#collections) are a distribution format for Ansible content that can include playbooks, roles, modules, and plugins. As modules move from the core Ansible repository into collections, the module documentation will move to the [collections pages](https://docs.ansible.com/ansible/latest/collections/index.html#list-of-collections).

[Ansible Lint](https://ansible-lint.readthedocs.io/en/latest/) is a command-line tool for linting playbooks, roles and collections aimed towards any Ansible users. Its main goal is to promote proven practices, patterns and behaviors while avoiding common pitfalls that can easily lead to bugs or make code harder to maintain.

[Ansible cmdb](https://github.com/fboender/ansible-cmdb) is a tool that takes the output of Ansible’s fact gathering and converts it into a static HTML overview page containing system configuration information.

[Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher) visually displays inventory inheritance hierarchies and at what level a variable is defined in inventory.

[Ansible Playbook Grapher](https://github.com/haidaraM/ansible-playbook-grapher) is a  command line tool to create a graph representing your Ansible playbook tasks and roles.

[Ansible Shell](https://github.com/dominis/ansible-shell) is an interactive shell for Ansible with built-in tab completion for all the modules.

[Ansible Silo](https://github.com/groupon/ansible-silo) is a self-contained Ansible environment by [Docker](https://www.docker.com/).

[Ansigenome](https://github.com/nickjj/ansigenome) is a command line tool designed to help you manage your Ansible roles.

[ARA](https://github.com/openstack/ara) is a records Ansible playbook runs and makes the recorded data available and intuitive for users and systems by integrating with Ansible as a callback plugin.

[Capistrano](https://capistranorb.com/documentation/overview/what-is-capistrano/) is a remote server automation tool. It supports the scripting and execution of arbitrary tasks, and includes a set of sane-default deployment workflows.

[Fabric](https://www.fabfile.org) is a high level Python (2.7, 3.4+) library designed to execute shell commands remotely over SSH, yielding useful Python objects in return. It builds on top of [Invoke](https://www.pyinvoke.org) (subprocess command execution and command-line features) and [Paramiko](https://paramiko.org/) (SSH protocol implementation), extending their APIs to complement one another and provide additional functionality.

[ansible-role-wireguard](https://galaxy.ansible.com/githubixx/ansible_role_wireguard) is an Ansible role for installing WireGuard VPN. Supports Ubuntu, Debian, Archlinx, Fedora and CentOS Stream.

[wireguard_cloud_gateway](https://galaxy.ansible.com/consensus/wireguard_cloud_gateway) is an Ansible role for setting up Wireguard as a gateway VPN server for cloud networks.

[Red Hat OpenShift](https://www.openshift.com/) is focused on security at every level of the container stack and throughout the application lifecycle. It includes long-term, enterprise support from one of the leading Kubernetes contributors and open source software companies.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

# Running Linux on the Apple Silicon
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

### Linux Virtualization on Apple Silicon

 - [Running Intel Binaries in Linux VMs with Rosetta](https://developer.apple.com/documentation/virtualization/running_intel_binaries_in_linux_vms_with_rosetta?language=objc) - Running x86_64 Linux binaries under ARM Linux on Apple silicon.

 - [Virtualize Linux on a Mac](https://developer.apple.com/documentation/virtualization/virtualize_linux_on_a_mac?language=objc) - Configure and run Linux guests on Apple silicon and Intel-based Mac computers.
 

[Parallels Desktop for Mac](https://www.parallels.com/products/desktop/) is a program that let's you runs Windows side-by-side with macOS (no restarting required) on your MacBook, MacBook Pro, iMac, iMac Pro, Mac mini or Mac Pro. Share files and folders, copy and paste images and text & drag and drop files between Mac and Windows applications.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880057-df697a80-8292-11eb-8484-9bbc02592377.jpg">
<br />
Parallels Desktop for Mac
</p>


[UTM](https://getutm.app/) is a full featured system emulator and virtual machine host for iOS and macOS. It is based off of [QEMU](https://www.qemu.org/) that allows you to run Windows, Linux, and more on your Mac, iPhone, and iPad.

 - [UTM (SE) for iOS/iPadOS](https://getutm.app/install/)
 
 - [UTM for macOS](https://mac.getutm.app/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/164793036-c84684fb-be06-4452-bfc9-32f77fb8059f.png">
  <br />
 Ubuntu on UTM
</p>

[VMware Fusion 22H2](https://blogs.vmware.com/teamfusion/2022/07/just-released-vmware-fusion-22h2-tech-preview.html) is a software hypervisor developed by VMware for Mac computers.It creates a virtual machine and install an operating system (such as Windows or Linux) inside that virtual machine.

  * Windows 11 on Intel and Apple Silicon, with 2D graphics and networking support.
  * VMTools installation support for Windows 11 guest operating system on M1-based Macs.
  * Virtual TPM device with fast encryption support.
  * Improved Linux support on M1.
  * 3D Graphics HW Acceleration and OpenGL 4.3(Requires Linux 5.19+ & Mesa 22.1.3+) in Linux virtual machines.
  * Universal Binary for Apple Silicon and Intel Macs.
 
[Multipass](https://multipass.run/) is a tool to generate cloud-style Ubuntu VMs quickly on Linux, macOS, and Windows. It uses [KVM](https://www.redhat.com/en/topics/virtualization/what-is-KVM) on Linux, [Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/) on Windows, and [HyperKit](https://github.com/moby/hyperkit) on macOS.

### Asahi Linux Development

[Hector Martin](https://github.com/marcan) has merged the initial support for Apple M1 hardware into the Linux SOC (System On a Chip) tree for [Linux Kernel 5.13](https://git.kernel.org/pub/scm/linux/kernel/git/soc/soc.git/commit/?h=for-next&id=0d5fe4b31785b732b71e764b55cda5c8d6e3bbbf). Also credit to developers [Sven Peter](https://github.com/svenpeter42) and [Alyssa Rosenzweig](https://github.com/alyssarosenzweig).

The Linux kernel 6.2 offers mainline support for the Apple M1 Pro, Max, and Ultra chips as work done by Asahi Linux's developers was upstreamed. Though, that does not mean you can simply install a Linux distro like Fedora, Ubuntu, or Debian with the 6.2 kernel.

 * [Linux kernel 6.2 release notes](https://lkml.org/lkml/2023/2/19/309).

[Asahi Linux](https://asahilinux.org/) is a project and community with the goal of porting Linux to Apple Silicon Macs, starting with the 2020 M1 Mac Mini, MacBook Air, and MacBook Pro. Their goal is not just to make Linux run on these machines but to polish it to the point where it can be used as a daily OS.

  - [Asahi Linux Alpha Release is here!](https://asahilinux.org/2022/03/asahi-linux-alpha-release/)

  - [Asahi Linux installer on GitHub](https://github.com/AsahiLinux/asahi-installer)
  
  - [Asahi Linux Feature Support](https://github.com/AsahiLinux/docs/wiki/Feature-Support)
  
  - [Asahi Linux Wiki](https://github.com/AsahiLinux/docs/wiki)

[M1N1](https://github.com/AsahiLinux/m1n1) is a bootloader and experimentation playground for Apple Silicon.

[Apple Silicon to Apple Silicon VDM utility](https://github.com/AsahiLinux/macvdmtool) is a tool that lets you get a serial console on an Apple Silicon device and reboot it remotely, using only another Apple Silicon device running macOS and a standard Type C cable.

[Asahi GPU](https://github.com/AsahiLinux/gpu) is a repo that provides research for an open source graphics stack (3D acceleration) for Apple M1 chips.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110054441-f4349400-7d0f-11eb-8889-743009b33994.png">
  <br />
</h3>

The [AsahiLinux Apple GPU drivers](https://asahilinux.org/2022/12/gpu-drivers-now-in-asahi-linux/) features are a work-in-progress OpenGL 2.1 and OpenGL ES 2.0 support for all current Apple M-series systems. That’s enough for hardware acceleration with desktop environments, like GNOME and KDE. It’s also enough for older 3D games, like Quake3 and Neverball. 

Asahi Linux Graphics Team:

   * [Alyssa Rosenzweig](https://social.treehouse.systems/@alyssa) is writing the OpenGL driver and compiler.
   * [Asahi Lina](https://vt.social/@lina) is writing the kernel driver and helping with OpenGL.
   * [Dougall Johnson](https://mastodon.social/@dougall) is reverse-engineering the instruction set with Alyssa.
   * [Ella Stanforth](https://tech.lgbt/@ella) is working on a Vulkan driver, reusing the kernel driver, the compiler, and some code shared with the OpenGL driver.

**Installing the Apple GPU Drivers:**

To get the new drivers, you need to run the linux-asahi-edge kernel and also install the mesa-asahi-edge Mesa package.

```
$ sudo pacman -Syu
$ sudo pacman -S linux-asahi-edge mesa-asahi-edge
$ sudo update-grub
```

Since only one version of Mesa can be installed at a time, pacman will prompt you to replace mesa with mesa-asahi-edge. This is normal!

**Recommendation:** Run Wayland instead of Xorg at this point, so if you’re using the KDE Plasma environment, make sure to install the Wayland session:

```$ sudo pacman -S plasma-wayland-session```

Then reboot, pick the Wayland session at the top of the login screen (SDDM), and enjoy! You might want to adjust the screen scale factor in System Settings → Display and Monitor (Plasma Wayland defaults to 100% or 200%, while 150% is often nicer). If you have “Force font DPI” enabled under Appearance → Fonts, you should disable that (it is saved separately for Wayland and Xorg, and shouldn’t be necessary on Wayland sessions). Log out and back in for these changes to fully apply.

### Fedora Linux Development

**Most of the hard work, including the kernel and boot software, was done by the [Asahi Linux project](https://asahilinux.org/) and their development team.**

While you will end up with a fairly usable computer, the exact hardware features you want [may not be ready yet](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). Please look at the [Asahi Linux Feature Support page](https://github.com/AsahiLinux/docs/wiki/Feature-Support) for information. 

For more general information about Linux on Apple Silicon Macs, refer to the [Asahi Linux project](https://asahilinux.org/) and [alpha installer release](https://asahilinux.org/2022/03/asahi-linux-alpha-release/). 

* [Fedora Asahi Special Interest Group](https://fedoraproject.org/wiki/SIGs/Asahi)
 
[Asahi-Fedora-Builder](https://github.com/leifliddy/asahi-fedora-builder) is a script that builds a minimal Fedora image to run on Apple M1/M2 systems.

**Installing a Prebuilt Image**

Make sure to update your macOS to version 12.3 or later, then just pull up a Terminal in macOS and paste in this command:

```curl https://leifliddy.com/fedora.sh | sh```

**Fedora Package Install**

```dnf install mkosi arch-install-scripts systemd-container zip```

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/220301314-23dbffb5-5c08-4d6f-ae22-f5f6c9ab46d3.png">
  <br />
  Fedora Linux 
</h3>

### NixOS Linux Development 

* **[NixOS on Apple Silicon](https://github.com/tpwrules/nixos-m1)**

## UEFI Boot Standalone NixOS (February 2023)

**This build was tested with the following software:**

* **Asahi Linux kernel version 6.1.0-asahi2**
* **Asahi Linux's Mesa version 23.0.0_pre20221219-1**
* **m1n1 version v1.2.3**
* **Asahi Linux's U-Boot version 2022.10.asahi1-1**
* **Nixpkgs, as of 2023-02-21**
* **macOS stub 12.3 or later**

**NOTE:** For more general information about Linux on Apple Silicon Macs, refer to the [Asahi Linux project](https://asahilinux.org/) and [Asahi Linux Alpha installer release](https://asahilinux.org/2022/03/asahi-linux-alpha-release/).

## Intro

This section will explain how to install NixOS on the internal NVMe drive of an Apple Silicon Mac using a customized version of the official NixOS install ISO, then boot it without the help of another computer. Aside from the Apple Silicon support module and AArch64 CPU, the resulting installation can be configured and operated like any other NixOS system. Your macOS install will still work normally, and you can easily switch between booting both macOS and NixOS.

**Most of the hard work, including the kernel and boot software, was done by the [Asahi Linux project](https://asahilinux.org/) and their development team.**

**Quick NixOS Intro:**

 * [NixOS](https://nixos.org/) is a Linux distribution built on top of the [Nix package manager](https://nixos.wiki/wiki/Nix). It has tools dedicated to DevOps and deployment tasks.

 * [Nix Tour](https://nixcloud.io/tour/) is an interactive tour that uses the actual package manager to learn you the language by example, in the browser

* [Nix](https://nixos.wiki/wiki/Nix) is a package manager and build system that parses reproducible build instructions specified in the [Nix Expression Language](https://nixos.wiki/wiki/Nix_Expression_Language), is a pure functional language with lazy evaluation. Nix expressions are pure functions taking dependencies as arguments and producing derivation specifying a reproducible build environment for the package. Nix stores the results of the build in unique addresses specified by a hash of the complete dependency tree, creating an immutable package store that allows for atomic upgrades, rollbacks and concurrent installation of different versions of a package, essentially eliminating [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell).

* [Nix Expression Language](https://nixos.wiki/wiki/Nix_Expression_Language) is a pure, lazy, functional language. Purity means that operations in the language don't have side-effects (for instance, there is no variable assignment). The language is not a full-featured, general purpose language. Its main job is to describe packages, compositions of packages, and the variability within packages.

* [Nixpkgs](https://nixos.wiki/wiki/Nixpkgs) is the largest repository of [Nix](https://nixos.wiki/wiki/Nix) packages(over 60,000 packages) and [NixOS](https://nixos.wiki/wiki/NixOS) modules. The repository is [hosted on GitHub](https://github.com/nixos/nixpkgs) and maintained by the community, with official backing from the [NixOS Foundation](https://nixos.org/). Additionally, checkout [Language-specific package helpers](https://nixos.wiki/wiki/Language-specific_package_helpers) and [Alternative Package Sets](https://nixos.wiki/wiki/Alternative_Package_Sets).

 * [NixOS Packages Search](https://search.nixos.org/packages) is a tool for searching through NixOS packages.

### Warning

Damage to the macOS recovery partitions or the partition table could result in the Mac becoming unbootable and loss of all data on the internal NVMe drive. In this circumstance, a suitable USB cable and another computer which can run [idevicerestore](https://github.com/libimobiledevice/idevicerestore) will be required to perform a DFU upgrade and restore normal operation. Backups are always wise.

While you will end up with a fairly usable computer, the exact hardware features you want [may not be ready yet](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). Please look at the [Asahi Linux Feature Support page](https://github.com/AsahiLinux/docs/wiki/Feature-Support) for information. Any features marked with a kernel version or **`linux-asahi`** should be supported by NixOS too.

### Prerequisites

**The following items are required to get started:**

* Apple Silicon Mac [supported by Asahi Linux](https://github.com/AsahiLinux/docs/wiki/Feature-Support#table-of-contents) with macOS 12.3 or later and an admin account.
* For Mac mini users: tested and working HDMI monitor. Many do not work properly; if it shows the Asahi Linux logo and console when m1n1 is running, it's fine.
* USB flash drive which is at least 512MB and can be fully erased, and USB A to C adapter.
* Familiarity with the command line and installers without GUIs.
* **Optional:** x86_64 or aarch64 Linux PC or VM (any distro is fine).

### Overview

* [Software Preparation](#software-preparation): build the customized NixOS installer ISO and Asahi Linux components
* [UEFI Preparation](#uefi-preparation): use the Asahi Linux installer to set up a standard UEFI boot environment
* [Installation](#installation): boot the NixOS installer and use it to set up and install NixOS
* [Maintenance](#maintenance): repair and upgrade NixOS and the Asahi Linux components
* [Removal](#removal): restore the system to the stock state


## Software Preparation

#### Nix

This setup takes advantage of the Nix package manager, which handles downloading and compiling everything. You must first install it on your Linux host PC if it doesn't run NixOS. Most distros are compatible, and installation (and uninstallation) is simple. Instructions are available on the [NixOS website](https://nixos.org/download.html#nix-quick-install).

If you can't or do not wish to install Nix and/or build these components yourself, installation ISOs are automatically built and made available from the [GitHub Releases page](https://github.com/tpwrules/nixos-apple-silicon/releases). Download the latest one, use `dd` or similar to transfer it to your USB flash drive, then skip down to the section on [UEFI Preparation](#uefi-preparation). Programs like `unetbootin` are not supported. These ISOs are fully reproducible; that is, the ISO you download will be (or should be...) bit-identical to the one you will get by following these preparation instructions.

#### NixOS Apple Silicon

Clone this repository to a suitable location on the host PC. In the future, you can update this repository using `git pull` and re-run the `nix build` commands to update things.

```
$ git clone https://github.com/tpwrules/nixos-apple-silicon/
$ cd nixos-apple-silicon
```

#### m1n1

The Asahi Linux project has developed **m1n1** as a bridge between Apple's boot firmware and the Linux world. m1n1 is installed as a faux macOS kernel into a stub macOS installation. In addition to booting Linux (or U-Boot), m1n1 also sets up the hardware and allows remote control and debugging over USB.

**Change directories to the repository, then use Nix to build m1n1 and symlink the result to `m1n1`:**

```
nixos-apple-silicon$ nix build --extra-experimental-features 'nix-command flakes' .#m1n1 -o m1n1
```

m1n1 has been built and the build products are now in `m1n1/build/`. You can also run m1n1's scripts such as `chainload.py` using a command like `m1n1/bin/m1n1-chainload`.

#### U-Boot

In the default installation, m1n1 loads U-Boot and U-Boot is used to set up a standard UEFI environment from which GRUB or systemd-boot or whatever can be booted. Due to the limitations of the Apple boot picker, there must be one EFI system partition per installed OS.

**Use Nix to build U-Boot along with m1n1 and the device trees:**

```
nixos-apple-silicon$ nix build --extra-experimental-features 'nix-command flakes' .#uboot-asahi -o u-boot
```

The `.bin` file with m1n1, the device trees, and U-Boot joined together is now in `u-boot/`.

#### Kernel and Bootstrap Installer

The bootstrap NixOS installer ISO contains UEFI-compatible GRUB, the Asahi Linux kernel, its initrd, and enough packages and drivers to allow connection to the Internet in order to download and install a full NixOS system.

```
nixos-apple-silicon$ nix build --extra-experimental-features 'nix-command flakes' .#installer-bootstrap -o installer -j4 -L
```

The installer ISO is now available as `installer/iso/nixos-*.iso`. Use `dd` or similar to transfer it to your USB flash drive. Programs like `unetbootin` are not supported.

## UEFI Preparation

This setup uses the alpha Asahi Linux installer to install a stub macOS and standard UEFI boot environment from which the NixOS installer and installed OS will run. These steps must be run from Terminal.app in macOS. You must also be logged into an administrator account.

#### Asahi Linux Installation

**Download and run the alpha installer with the following command:**
```
% curl https://alx.sh | sh
```

**Choose the following options to get started:**
* Enter your administrator password
* Do not enable expert mode

**Resize your existing macOS install:**
* Resize an existing partition to make space for a new OS (`r`)
* Enter the new size of the macOS install. It should be at least 20GB less than its current size to make room for NixOS with a GUI (note that here 1GB = 1,000,000,000 bytes)
* Confirm the resize operation
* Wait patiently while the partition is resized; it will take several minutes. Do not attempt to use the machine while this is in progress.
* Press enter when finished

**Install UEFI environment:**
* Install an OS into free space (`f`)
* UEFI environment only
* Name it NixOS (this is what shows up in the firmware boot picker)
* Wait while the installation proceeds and enter your password when prompted
* Wait for the default boot volume to be set (this may take several seconds)
* Read the final advice, then press enter to shut down the machine

Boot into recovery mode by holding the power button down as directed and select the new NixOS option in the boot picker. Follow the prompts and enter your administrator password. The local policy update will take several seconds to complete. Once complete, select that you want to set a custom boot object and put your system to permissive security mode, enter your administrator username (the same one you put in the password for earlier) and password, then reboot when prompted.

If everything went well, you will restart into U-Boot with the Asahi Linux and U-Boot logos on-screen. Shut the system down by holding the power button, then proceed to the next step.

## Installation

#### Booting the Installer

Shut down the machine fully. Connect the flash drive with the installer ISO to a USB-C port through the USB A to C adapter. If on a Mac mini, you must use the USB-C ports as U-Boot does not support the USB-A ports at this time. If not using Wi-Fi, connect the Ethernet cable to the network port or adapter as well.

Start the Mac, and U-Boot should start booting from the USB drive automatically. If you've already installed something to the internal NVMe drive, U-Boot will try to boot it first. To instead boot from USB, hit a key to stop autoboot when prompted, then run the command `run bootcmd_usb0`.

GRUB will start, then the NixOS installer after a short delay (the default GRUB option is fine). You will get a console prompt once booting completes. Run the command `sudo su` to get a root prompt in the installer. If the console font is too small, run the command `setfont ter-v32n` to increase the size.


#### Partitioning and Formatting

**DANGER:** Damage to the GPT partition table, first partition (`iBootSystemContainer`), or the last partition (`RecoveryOSContainer`) could result in the loss of all data and render the Mac unbootable and unrecoverable without assistance from another computer! Do not use your distro's automated partitioner or partitioning instructions!

We will add a root partition to the remaining free space and format it as ext4. Alternative partition layouts and filesystems, including LUKS encryption, are possible, but not covered currently.

**Create the root partition to fill up the free space:**
```
nixos# sgdisk /dev/nvme0n1 -n 0:0 -s
[...]
The operation has completed successfully.
```

**Identify the number of the new root partition (type code 8300, typically second to last):**
```
nixos# sgdisk /dev/nvme0n1 -p
Disk /dev/nvme0n1: 244276265 sectors, 931.8 GiB
Model: APPLE SSD AP1024Q                       
Sector size (logical/physical): 4096/4096 bytes
Disk identifier (GUID): 27054D2E-307A-41AA-9A8C-3864D56FAF6B
Partition table holds up to 128 entries
Main partition table begins at sector 2 and ends at sector 5
First usable sector is 6, last usable sector is 244276259
Partitions will be aligned on 1-sector boundaries
Total free space is 0 sectors (0 bytes)

Number  Start (sector)    End (sector)  Size       Code  Name
   1               6          128005   500.0 MiB   FFFF  iBootSystemContainer
   2          128006       219854567   838.2 GiB   AF0A  Container
   3       219854568       220465127   2.3 GiB     AF0A  
   4       220465128       220590311   489.0 MiB   EF00  
   5       220590312       242965550   85.4 GiB    8300  
   6       242965551       244276259   5.0 GiB     FFFF  RecoveryOSContainer
```

**Format the new root partition:**
```
nixos# mkfs.ext4 -L nixos /dev/nvme0n1p5
```

#### NixOS Configuration

The subsequent steps in this section will help you install NixOS onto your new partitions. More information is available in the Installing section of the [NixOS manual](https://nixos.org/manual/nixos/stable/index.html#sec-installation-installing). Some changes to the configuration procedure as described in that manual are needed for NixOS on Apple Silicon to work properly.

**Mount the root partition, then the EFI system partition that was created by the Asahi Linux installer specifically for NixOS:**
```
nixos# mount /dev/disk/by-label/nixos /mnt
nixos# mkdir -p /mnt/boot
nixos# mount /dev/disk/by-partuuid/`cat /proc/device-tree/chosen/asahi,efi-system-partition` /mnt/boot
```

**Create a default configuration for the new system, then copy the Apple Silicon support module into it:**
```
nixos# nixos-generate-config --root /mnt
nixos# cp -r /etc/nixos/apple-silicon-support /mnt/etc/nixos/
nixos# chmod -R +w /mnt/etc/nixos/
```

Use vim (or any editor of your choice) to edit the configuration of the new system to include the Apple Silicon support module. Be aware that other editors and most documentation has been left out of the bootstrap installer to save space and time.
```
nixos# vim /mnt/etc/nixos/configuration.nix
```

Add the `./apple-silicon-support` directory to the imports list and switch off the `canTouchEfiVariables` option. That portion of the file should look like this:
```
  imports =
    [ # Include the results of the hardware scan.
      ./hardware-configuration.nix
      # Include the necessary packages and configuration for Apple Silicon support.
      ./apple-silicon-support
    ];

  # Use the systemd-boot EFI boot loader.
  boot.loader.systemd-boot.enable = true;
  boot.loader.efi.canTouchEfiVariables = false;
```

If you used the cross-compiled installer image, i.e. **you downloaded the ISO from GitHub or built it on an `x86_64-linux` machine, you may add the following line to re-use the cross-compiled Asahi packages**. If you don't, they will be rebuilt in the installer, which wastes time. When you update the system and they need to be rebuilt on the Mac itself, remove this line or you will get an error that an `x86_64-linux` builder is required.
```
  # Remove if you get an error that an x86_64-linux builder is required.
  hardware.asahi.pkgsSystem = "x86_64-linux";
```

The configuration above is the minimum required to produce a bootable system, but you can further edit the file as desired to perform additional configuration. Uncomment the relevant options and change their values as explained in the file. Note that some advertised features may not work properly at this time. Refer to the [NixOS installation manual](https://nixos.org/manual/nixos/stable/index.html#ch-configuration) for further guidance.

Various non-free non-redistributable peripheral firmware files are required to use system hardware like Wi-Fi. The Asahi Linux installer grabs these from macOS and stores them on the EFI system partition when it is created. The NixOS installer loads them from there while booting so that all hardware is available during installation. By default, the Apple Silicon support module will automatically reference the files in the EFI system partition and incorporate them into your configuration to be managed by the normal NixOS mechanisms.

Currently, the only supported way to update the peripheral firmware files is to destroy and re-create the EFI system partition, so they will not change unexpectedly. If you do not want the impurity of referencing them (or are using flakes where this is prohibited), copy them off the EFI system partition (e.g. on the installation ISO `mkdir -p /mnt/etc/nixos/firmware && cp /mnt/boot/asahi/{all_firmware.tar.gz,kernelcache*} /mnt/etc/nixos/firmware`) and specify this path in your configuration:
```
  # Specify path to peripheral firmware files.
  hardware.asahi.peripheralFirmwareDirectory = ./firmware;
  # Or disable extraction and management of them completely.
  # hardware.asahi.extractPeripheralFirmware = false;
```

You can choose to build the Asahi kernel with a 4K page size by enabling the appropriate option. This results in a reduction in raw compilation speed of 10-25%, but improves software compatibility in some cases (such as with Chromium/Electron and x86 emulation).
```
  # Build the kernel with 4K pages to improve software compatibility at
  # the cost of performance in some cases.
  hardware.asahi.use4KPages = true;
```

If you want to install a desktop environment, you will have to uncomment the option to enable X11 and NetworkManager, then add an option to include your favorite desktop environment. You may also wish to include graphical packages such as `firefox` in `environment.systemPackages`. For example, to install Xfce:
```
  # Enable the X11 windowing system.
  services.xserver.enable = true;
  services.xserver.desktopManager.xfce.enable = true;
```

Some keyboard layouts are not detected correctly. On some devices, the \` key is swapped with `<`, and `~` with `>`. The layout can be fixed by setting options in `boot.extraModprobeConfig`. Which option needs to be set depends on your hardware keyboard's layout (see: [Arch Wiki - Apple Keyboard](https://wiki.archlinux.org/title/Apple_Keyboard)).
 ```
 # For ` to < and ~ to > (for those with US keyboards)
 boot.extraModprobeConfig = ''
   options hid_apple iso_layout=0
 '';
 ```

#### NixOS Installation

Once you are happy with your initial configuration, you may install the system. This will have to download a large amount of data.

You can configure wireless networking in the installer using `wpa_supplicant` by following [the minimal installer directions](https://nixos.org/manual/nixos/stable/index.html#sec-installation-booting-networking) in the NixOS manual.

Once the network is set up, ensure the time is set correctly, then install the system. You will be asked to set a root password as the final step:
```
nixos# systemctl restart systemd-timesyncd
nixos# nixos-install
[...]
setting root password...
New password: ******
Retype new password: ******
passwd: password updated successfully
installation finished!
```

If there are any errors, or you mess up entering the root password, you can edit the configuration and safely re-run the command.

**Once complete, reboot the system:**
```
nixos# reboot
```

When the system reboots, the bootloader will come up and boot the default configuration after a short delay. Once NixOS boots, log in with the root password, and create your account, or set your user account password if you created your account in the configuration. To learn more about NixOS's configuration system, read the section in the manual on [changing the configuration](https://nixos.org/manual/nixos/stable/index.html#sec-changing-config).

#### Dual Booting

The machine is now set up to boot NixOS by default when turned on. To access the boot picker, turn off the machine, then hold the power button to turn the machine on instead of just pressing it. Let go once the options come up. To boot a particular OS once, click on it, then click Continue underneath it. To switch the default OS, click on the desired default, hold Option (Alt), then click Always Use underneath it.

#### Hypervisor Boot

By selecting the appropriate menu option in the Asahi Linux installer, you can also choose to install m1n1 without U-Boot and run U-Boot, the bootloader, and the OS under m1n1's hypervisor.

To run U-Boot under the hypervisor, start m1n1 and attach the Mac to the host PC using an appropriate USB cable, change directories to the repo, then run:

```
nixos-apple-silicon$ m1n1/bin/m1n1-run_guest --raw u-boot/m1n1-u-boot.bin
```

To access the serial console, in a separate terminal run:

```
$ nix-shell -p picocom --run 'picocom /dev/ttyACM1'
```

Downloading the kernel over USB using m1n1 is not supported.

## Maintenance

#### System Rescue

If something goes wrong and NixOS doesn't boot or is otherwise unusable, you can first try rolling back to a previous generation. Instead of selecting the default bootloader option, choose another configuration that worked previously.

If something is seriously wrong and the bootloader does not work (or you don't have any other generations), you will want to get back into the installer. To start the installer with a system installed on the internal disk, shut down the computer, re-insert the USB drive with the installer, start it up again, hit a key in U-Boot when prompted to stop autoboot, then run the command `run bootcmd_usb0`.

Once in the installer, you can re-mount your root partition and EFI system partition without reformatting them. Depending on what exactly went wrong, you might need to edit your configuration, copy over the latest Apple Silicon support module, or update U-Boot using the latest installer.

Rerunning the installer will create a new generation but not touch any user data. This means you can "undo" the installation by selecting a previous generation in the bootloader. To redo the installation without changing your root password or changing the version of Nixpkgs, run:
```
# nixos-install --no-root-password --no-channel-copy
```

In the extreme case, you can delete the EFI system partition and stub macOS install and rerun the Asahi Linux installer, then follow the steps above to reinstall NixOS's bootloader menu. You will need to regenerate the hardware configuration using `nixos-generate-config --root /mnt` because the EFI system partition's ID will change. This shouldn't modify your root partition or other NixOS configuration, but of course it's always smart to have a backup. You might also wish to re-copy the peripheral firmware files.

#### NixOS Updates

NixOS itself can be updated like any other NixOS system. In brief, this is as follows:
```
$ sudo nix-channel --update
$ sudo nixos-rebuild switch
```

You may have to reboot after updating in some cases. If something goes wrong, you can boot a previous generation and roll back the channel update. For more details, consult the [Upgrading section](https://nixos.org/manual/nixos/stable/index.html#sec-upgrading) of the NixOS manual.

#### Apple Silicon Support Updates

To update the Apple Silicon support module, including the Asahi kernel, U-Boot, and m1n1, you can simply download newer files from this repo under `apple-silicon-support` and place them under `/etc/nixos/apple-silicon-support`. Any changes will require a configuration rebuild and reboot to take effect. If you wish to customize your kernel, you can edit the kernel config in `/etc/nixos/apple-silicon-support/kernel/config`. Consult the comments in `/etc/nixos/apple-silicon-support/kernel/default.nix` and `/etc/nixos/apple-silicon-support/kernel/package.nix` for more details. **Note that if the kernel device trees change, U-Boot will need to be updated too.**

U-Boot and m1n1 are automatically managed by NixOS' bootloader system. If you roll back to a previous generation and things do not work properly due to a device tree incompatibility, you can run `/run/current-system/bin/switch-to-configuration switch` then reboot to force the bootloader and the correct version of U-Boot/m1n1 to be reinstalled and loaded.

If you want the Apple Silicon support module to be upgraded in tandem with NixOS instead of manually downloading new files, you can add it as a channel with the following command:
```
$ sudo nix-channel --add https://github.com/tpwrules/nixos-apple-silicon/archive/main.tar.gz apple-silicon-support
```

Modify your `/etc/nixos/configuration.nix` to reference the channel instead of the local files:
```
  imports =
    [ # Include the results of the hardware scan.
      ./hardware-configuration.nix
      # Include the necessary packages and configuration for Apple Silicon support.
      <apple-silicon-support/apple-silicon-support>
    ];
```

**You can now update NixOS as normal. Note that Apple Silicon support module updates will generally require reboots to load new kernels and other boot components:**
```
$ sudo nix-channel --update
$ sudo nixos-rebuild switch
$ sudo reboot
```

#### Recovering from Boot Failure with `idevicerestore`

In extremely extreme circumstances (i.e. something messed up the firmware partition, recovery partition, or partition table), your Mac may fail to boot. On the Mac mini (and presumably Mac Studio), this state is identifiable by a flashing orange power light indicating the Morse code for SOS. On a Mac laptop, this state is identifiable by an illustration of an exclamation point in a circle on the screen with a link to Apple's website.

To make the Mac bootable again, you can use [idevicerestore](https://github.com/libimobiledevice/idevicerestore) from another Mac or Linux x86_64 or aarch64 VM or computer that has an Internet connection. You will need a USB cable with at least one USB-C end. This procedure has been tested with Mac and Linux hosts restoring a Mac mini with macOS 12.4.

Please note that this procedure may require you to unrecoverably destroy all data on the Mac's internal drive. If erasing is necessary, you will be clearly warned and asked to confirm before it happens. The drive will end up zeroed and its encryption keys (probably) regenerated, so not even the NSA will be able to save you. If you haven't made backups, make peace with yourself now.

You'll need to build `idevicerestore` from source to get a version capable of restoring Apple Silicon Macs. If Nix is already installed on your second computer, an appropriate version is already packaged in recent `nixpkgs-unstable`. **Check out and build both `idevicerestore` and `usbmuxd` (if on Linux):**

```
# git clone https://github.com/NixOS/nixpkgs/
# cd nixpkgs
# nix-build -A pkgs.idevicerestore -o idevicerestore
# nix-build -A pkgs.usbmuxd -o usbmuxd # if on Linux
```

To start the procedure, hook up the appropriate port on your unbootable Mac to the second computer and invoke DFU mode. This process is covered by Steps 1 and 2 of [Apple's documentation](https://support.apple.com/guide/apple-configurator-mac/revive-or-restore-a-mac-with-apple-silicon-apdd5f3c75ad/mac). We will first try what Apple calls a "revive" where the disk is not erased, although both we and `idevicerestore` still call it a "restore".

If DFU mode was started correctly, the unbootable Mac will show up on your second computer as an `Apple, Inc. Mobile Device (DFU Mode)` in `lsusb` on Linux or System Information on macOS. If you see `Apple, Inc. Apple Mobile Device [Recovery Mode]` instead (or nothing), the procedure was not followed correctly and you need to try again.

Open a terminal on your second computer and, if you are on Linux and didn't install the udev rules (which Nix did not), start `usbmuxd` in the background by running it without any arguments. Then, ask `idevicerestore` to restore the firmware by using the `--latest` flag. If you wish to erase the disk either because the revive didn't work or because you want to start with a clean slate, use the `--erase` flag also.

```
# sudo usbmuxd/bin/usbmuxd # Linux only
# sudo idevicerestore/bin/idevicerestore --latest
idevicerestore 1.0.0-unstable-2022-05-22
Found device in DFU mode
Identified device as j274ap, Macmini9,1
The following firmwares are currently being signed for Macmini9,1:
[...]
Select the firmware you want to restore:
```

Once `idevicerestore` detects the unbootable Mac, select the desired firmware (usually number `1`) and wait patiently while the firmware is downloaded; it's about 13GiB. If `idevicerestore` doesn't detect the unbootable Mac, make sure that your cables are hooked up correctly, that you used `sudo`, and that you are using a suitably recent version.

The restore process will automatically start once the firmware is downloaded and verified. If `idevicerestore` fails with the message `ERROR: Device did not disconnect. Possibly invalid iBEC. Reset device and try again.`, the unbootable Mac is likely not in DFU mode, or there is something wrong with your system's udev related to hotplug events. Check that you followed Apple's procedure correctly and that the appropriate USB device is detected.

After 30 seconds of messages and status updates, you should see the Apple logo on the unbootable Mac's screen with a progress bar and `idevicerestore` will tell you that it is `Waiting for device to enter restore mode...`. If the unbootable Mac resets after a couple minutes and you get the message `ERROR: Device failed to enter restore mode. Please make sure that usbmuxd is running.`, then `usbmuxd` is likely not running. Start it and try again.

Once the restore process starts, the progress bar will start moving and `idevicerestore` will spam lots of information about the process. If it fails with `ERROR: Unable to restore device`, your only choice may be to restart the process, but this time pass the `--erase` flag to `idevicerestore` and destroy all data on the unbootable Mac's internal drive.

Otherwise, wait patiently while the restore proceeds. Expect it to take 20 or 30 minutes at least. Eventually `idevicerestore` will say `DONE` and the formerly-unbootable Mac will reboot and start recovery mode (if erasing was not necessary) or the out-of-the-box wizard (if the disk was erased) and you can use it again.

Finally, shut down `usbmuxd` if on Linux and you started it manually. To clean up your second computer, remove the downloaded firmware, the `idevicerestore` and `usbmuxd` GC roots, and run the Nix garbage collector:
```
# sudo killall usbmuxd # if on Linux
# sudo rm -rf *.ipsw* UniversalMac*
# rm -f result* usbmuxd idevicerestore
# nix-collect-garbage
```

## Removal

#### Host PC Cleanup

To recover the space on the host PC, change directories into the repo, remove the built symlinks (removing just the installer will recover almost all the space), then run the garbage collector:

```
nixos-apple-silicon$ rm m1n1 u-boot installer result
nixos-apple-silicon$ nix-collect-garbage
```

#### NixOS Uninstallation

NixOS can be completely uninstalled by deleting the stub partition, EFI system partition, and root partition off the disk.

Boot back into macOS by shutting down the machine fully, then pressing and holding the power button until the boot picker comes up. Select the macOS installation, then click Continue to boot it. Log into an administrator account and open Terminal.app.

Identify the partitions to remove. In this example, `disk0s3` is the stub because of its small size. `disk0s4` is the EFI system partition and `disk0s5` is the root partition:
```
% diskutil list disk0
/dev/disk0 (internal):
   #:                       TYPE NAME                    SIZE       IDENTIFIER
   0:      GUID_partition_scheme                         1.0 TB     disk0
   1:             Apple_APFS_ISC                         524.3 MB   disk0s1
   2:                 Apple_APFS Container disk4         900.0 GB   disk0s2
   3:                 Apple_APFS Container disk3         2.5 GB     disk0s3
   4:                        EFI EFI - NIXOS             512.8 MB   disk0s4
   5:           Linux Filesystem                         91.6 GB    disk0s5
   6:        Apple_APFS_Recovery                         5.4 GB     disk0s6
```

**WARNING:** Unlike Linux, on macOS each partition's identifier does not necessarily equal its partition index. Double check the identifiers of your own system!

**Remove the EFI system partition and root partition:**
```
% diskutil eraseVolume free free disk0s4
Started erase on disk0s4 (EFI - NIXOS)
Unmounting disk
Finished erase on disk0
% diskutil eraseVolume free free disk0s5
Started erase on disk0s5
Unmounting disk
Finished erase on disk0
```

**Remove the stub partition:**
```
% diskutil apfs deleteContainer disk0s3
Started APFS operation on disk3
Deleting APFS Container with all of its APFS Volumes
[...]
Removing disk0s3 from partition map
```

**Expand the main macOS partition to use the resulting free space. This command will take a few minutes to run; do not attempt to use the machine while it is in progress:**
```
% diskutil apfs resizeContainer disk0s2 0
Started APFS operation
Aligning grow delta to 94,662,586,368 bytes and targeting a new physical store size of 994,662,584,320 bytes
[...]
Finished APFS operation
```
To complete the uninstallation, open the Startup Disk pane of System Preferences and select your macOS installation as the startup disk. If this is not done, the next boot will fail, and you will be asked to select another OS to boot from.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128645111-b2a92dd2-f246-4df0-b05c-5b0ffce05448.png">
  <br />
  NixOS with the Plasma Desktop
</h3>

### Debian Linux Development

**Most of the hard work, including the kernel and boot software, was done by the [Asahi Linux project](https://asahilinux.org/) and their development team.**

While you will end up with a fairly usable computer, the exact hardware features you want [may not be ready yet](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). Please look at the [Asahi Linux Feature Support page](https://github.com/AsahiLinux/docs/wiki/Feature-Support) for information. 

For more general information about Linux on Apple Silicon Macs, refer to the [Asahi Linux project](https://asahilinux.org/) and [alpha installer release](https://asahilinux.org/2022/03/asahi-linux-alpha-release/). 

**Important Note:** Starting from mid-2022, the best advice for getting Debian installed is to be found here: **https://git.zerfleddert.de/cgi-bin/gitweb.cgi/m1-debian/.**

#### Artefacts

**If you don't want to use the prebuild artefacts, you can build them yourself using the following scripts:**

   - **prepare_rust.sh** - Prepares a rust installation suitable for kernel compilation
   - **m1n1_uboot_kernel.sh** - Builds m1n1, u-boot and the kernel including gpu support.
   - **mesa.sh** - Creates mesa packages
   - **bootstrap.sh** - Creates Debian root and live filesystem
   - **meta.sh** - Meta package which makes sure that we always get latest and gratest kernel.
    
    
#### Asahi installer

**[Video Recording](https://tg.st/u/debian_asahi_installer.mp4)**

   Poweroff your Mac. Hold and press the power button until you see a wheel chain and Options written below. **Approx 20 seconds**.

   In the boot picker, choose Options. Once loaded, open a Terminal under Utilities > Terminal

   **Run the asahi installer and select Debian:**

   ```curl -sL https://tg.st/d | sh```

  **Follow the installer instructions.**

  **Once Debian is booted log in as root without password and set a root password.**

   ```passwd```
   
   ```pwconv```

  **Configure wifi by editing the wpa_supplicant.conf, enabling the interface and remove the # before allow-hotplug to enable it during boot.**

   ```vi /etc/wpa_supplicant/wpa_supplicant.conf```
   
   ```ifup wlan0```
   
   ```vi /etc/network/interfaces```

   **Reboot to see if grub was correctly installed**

   ```reboot```

   **Install a desktop environment for example blackbox**

   ```apt-get update```
   
   ```apt-get install -y xinit blackbox xterm firefox-esr lightdm```

  **Create yourself an unprivileged user**

   ```useradd -m -c 'Firstname Lastname' -s /bin/bash <username>```
   
   ```passwd <username>```

   **Optional install sshd. You can not log in as root, but only with your unprivileged user**

   ```apt update```
   
   ```apt install -y openssh-server```

   Consult the  **[/root/quickstart.txt](https://git.zerfleddert.de/cgi-bin/gitweb.cgi/m1-debian/blob_plain/refs/heads/master:/files/quickstart.txt)** file to find out how to do other interesting things.
    
   <h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/222395704-be1d4f1b-498e-484e-9035-e7758f784aef.png">
  <br />
  Debian 
</h3>

Image Credit: [Alyssa Rosenzweig](https://social.treehouse.systems/@alyssa)

### Ubuntu Development

* **[Ubuntu Apple Silicon Image](https://github.com/tobhe/ubuntu-asahi)**

**Most of the hard work, including the kernel and boot software, was done by the [Asahi Linux project](https://asahilinux.org/) and their development team.**

While you will end up with a fairly usable computer, the exact hardware features you want [may not be ready yet](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). Please look at the [Asahi Linux Feature Support page](https://github.com/AsahiLinux/docs/wiki/Feature-Support) for information. 

For more general information about Linux on Apple Silicon Macs, refer to the [Asahi Linux project](https://asahilinux.org/) and [alpha installer release](https://asahilinux.org/2022/03/asahi-linux-alpha-release/). 

#### Installer

**To install a prebuilt image run:**

```
curl -sL https://tobhe.de/ubuntu/install > install.sh	# Download
less install.sh						# Review
sh install.sh						# Run
```

The installer offers a choice of different Ubuntu releases and build configurations.

**Currently supported are:**

  * Ubuntu 22.10 Desktop
  * Ubuntu 22.10 Server
  * Ubuntu 22.04 Desktop
  * Ubuntu 22.04 Server

The default **username and password are both ```ubuntu```.** Root access can be achieved via ```sudo```.


### Dual-booting macOS and Linux

Yes, The installer can automatically resize your macos partition according to your liking and install Ubuntu in the freed up space. Removing macOS is not supported at the moment since it is required to update the system firmware.

### Building

If you do not want to use the prebuilt disk image, you can build one yourself with the instructions below.

```
# Install dependencies
sudo apt-get install arch-install-scripts debootstrap mtools parted gnupg eatmydata rsync git squashfs-tools zip

# Install dependencies, if your builder system is NOT arm64
sudo apt-get install binfmt-support qemu qemu-user-static
````
#### Build

```
cd ubuntu-asahi
# Build the entire live image
sudo ./build-generic.sh
```
The live GPT image file will be output to ```build/ubuntu.live.img```, the zip archive for the Asahi Linux installer will be output to ```build/ubuntu.live.img.zip```.

#### Clean

The clean.sh script will clean up the build folder, except for the cache folder, which is used by debootstrap to cache debs.

```
cd ubuntu-asahi
# Clean the build folder
./clean.sh
```


# Running Windows 10/11 on the Apple Silicon
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Parallels Desktop for Mac](https://www.parallels.com/products/desktop/) is a program that let's you runs Windows side-by-side with macOS (no restarting required) on your MacBook, MacBook Pro, iMac, iMac Pro, Mac mini or Mac Pro. Share files and folders, copy and paste images and text & drag and drop files between Mac and Windows applications.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880057-df697a80-8292-11eb-8484-9bbc02592377.jpg">
<br />
Parallels Desktop for Mac
</p>

[UTM](https://getutm.app/) is a full featured system emulator and virtual machine host for iOS and macOS. It is based off of [QEMU](https://www.qemu.org/) that allows you to run Windows, Linux, and more on your Mac, iPhone, and iPad.

 - [UTM (SE) for iOS/iPadOS](https://getutm.app/install/)
 
 - [UTM for macOS](https://mac.getutm.app/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/164793030-07cba054-33e2-4251-9be6-1f1c71851df6.png">
  <br />
 Windows 11 on UTM
</p>
 
[VMware Fusion 22H2](https://blogs.vmware.com/teamfusion/2022/07/just-released-vmware-fusion-22h2-tech-preview.html) is a software hypervisor developed by VMware for Mac computers.It creates a virtual machine and install an operating system (such as Windows or Linux) inside that virtual machine.

  * Windows 11 on Intel and Apple Silicon, with 2D graphics and networking support.
  * VMTools installation support for Windows 11 guest operating system on M1-based Macs.
  * Virtual TPM device with fast encryption support.
  * Improved Linux support on M1.
  * 3D Graphics HW Acceleration and OpenGL 4.3(Requires Linux 5.19+ & Mesa 22.1.3+) in Linux virtual machines.
  * Universal Binary for Apple Silicon and Intel Macs.
  
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/182049352-b899b356-57c0-4ec0-8fb1-ff394a1f6403.png">
  <br />
 Windows 11 on VMware Fusion
</p>

[ARM64EC (“Emulation Compatible”)](https://docs.microsoft.com/en-us/windows/uwp/porting/arm64ec) is a new application binary interface (ABI) for Windows 11 on ARM that runs with native speed and is interoperable with x64 architecture. An app, process, or even a module can freely mix and match with ARM64EC and x64 as needed. The ARM64EC code in the app will run natively while any x64 code will run using Windows 11 on ARM’s built-in emulation. The ARM64EC ABI differs slightly from the current [ARM64 ABI](https://docs.microsoft.com/en-us/cpp/build/arm64-windows-abi-conventions?view=msvc-160) in ways that make it binary compatible with x64 code. Specifically, the ARM64EC ABI follows x64 software conventions including calling convention, stack usage, and data alignment, making ARM64EC and x64 interoperable. Apps built as ARM64EC may contain x64 code but do not have to, since ARM64EC is its own complete, first-class ABI for Windows.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124997795-20cf2400-e000-11eb-8954-4944286b8ea8.png">
  Windows 11 Desktop
</h3>

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/120387363-a9aabf80-c2de-11eb-84a5-8e4b422e7546.png">
  Windows 10 Desktop
</h3>

# Gaming
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

## Gaming on Apple Silicon Resources

 - **[Apple Game Porting Toolkit 1.0](https://github.com/apple/homebrew-apple/tree/main/Formula)**

 - **[PortJump](https://www.codeweavers.com/portjump)**

 - **[Apple Silicon Games](https://applesilicongames.com/games)** 
 
 - **[M1 Parallels Windows compatible games list | AppleGamingWiki](https://www.applegamingwiki.com/wiki/M1_Parallels_Windows_compatible_games_list)**

 - **[M1 compatible Games Master List | AppleGamingWiki ](https://www.applegamingwiki.com/wiki/M1_compatible_games_master_list)**

 - **[Games and Apps on Apple Silicon (Compatibility Sheet) by Thomas Schranz(@__tosh on Twitter) ](https://docs.google.com/spreadsheets/d/1er-NivvuIheDmIKBVRu3S_BzA_lZT5z3Z-CxQZ-uPVs)**
  
 - **[Porting Kit | Install Windows apps in Mac](https://www.portingkit.com/)**

 - **[MacGaming Subreddit](https://www.reddit.com/r/macgaming)**
 
 - **[iOS Gaming Subreddit](https://www.reddit.com/r/iosgaming/)**
 
 - **[Apple Arcade Subreddit](https://www.reddit.com/r/AppleArcade/)**
 
 
## MacOS Game Mode

[Back to the Top](#table-of-contents)

 
**[Game Mode](https://www.apple.com/newsroom/2023/06/macos-sonoma-brings-new-capabilities-for-elevating-productivity-and-creativity/)** is a tool enabled in **macOS 14**, it prioritizes CPU and GPU power for the game title you're running. Optimizing your gaming experience across the board with smoother and more consistent frame rates. For example, Game Mode makes gaming on Mac more immersive by lowering audio latency with AirPods, and significantly reducing input latency with popular game controllers like those for Xbox and PlayStation by doubling the Bluetooth sampling rate. 

<p align="center">
  <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/fa3f2a70-df44-4e94-99cd-93fd7de1adf7">
 <br />
 Game Mode. Image Credit: Apple
</p>

## Game Porting Toolkit

[Back to the Top](#table-of-contents)

[Game Porting Toolkit](https://github.com/apple/homebrew-apple/tree/main/Formula) is Apple's new translation layer which combines Wine with Apple's own D3DMetal which supports DirectX 9 through 12. Games that use anti-cheat or aggressive DRM generally don't work. Games that require AVX CPUs also do not work such as the Last of Us game.

<p align="center">
  <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/c04de75d-b1ad-4e8f-8f44-e750ca479081">
 <br />
 Game Porting Toolkit running Cyberpunk 2077 on a  M1 Macbook. Image Credit: Isaac Marovitz
</p>

**Working Games:**

 *  Cyberpunk 2077
 *  Elden Ring  
 *  Diablo IV 
 *  Hogwarts Legacy
 *  Deep Rock Galactic
 *  Sonic Omens
 *  Sonic P-06
 *  Scarlet Nexus
 *  Dyson Sphere Program (some objects and main character weren't visible before)
 *  Derail Valley (good performance, no missing manuals, and in-game objects for train operation like on CrossOver)
 *  Spider-Man (2018)
 *  Spider-Man Miles Morales - requires Windows version fix.
 *  Warframe - To get installer/launcher working add dwrite (disabled) to library overrides in winecfg.
 *  QUBE 2
 
### System Requirements
 
   * macOS Sonoma should be used, currently it is in beta. 
   * macOS Ventura causes large numbers of issues with steamwebhelper.exe crashing so it isn't recommended, use the macOS Sonoma beta.
   * [Visit Apple Developer Downloads site](https://developer.apple.com/downloads), these files are now free to download use for any logged in Apple account.
       - Search for Command Line Tools for Xcode 15 beta and download the dmg file, then install it.
       - If you have an old version Xcode installed, remove it.
       - Search for Game Porting Toolkit and download it. Open the dmg file and then run the pkg.
       
### Using Homebrew

**Note:** if you have ever installed Homebrew before, then it is advisable to remove arm64 Homebrew as this can interfere with this build process. Either use a Homebrew uninstall script or delete the folder ```/opt/homebrew/bin```.

Open Terminal (search in Spotlight on macOS).

**Install Rosetta:**

```softwareupdate --install-rosetta```

Enter an x86_64 shell to continue the following steps in a Rosetta environment. All subsequent commands should be run within this shell.

```arch -x86_64 zsh```

Install the x86_64 version of Homebrew if you don't already have it.

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

**Make sure the brew command is on your path:**

which brew

**If this command does not print ```/usr/local/bin/brew```, you should use this command:**

```export PATH=/usr/local/bin:${PATH}```

### Build 

**Run this command to download Apple tap:**

```brew tap apple/apple http://github.com/apple/homebrew-apple```

Install the game-porting-toolkit formula. This formula downloads and compiles several large software projects. How long this takes will depend on the speed of your computer. It can take over 1 hour to complete depending on the speed of your Mac.

```brew -v install apple/apple/game-porting-toolkit```

If during installation you see an error such as “Error: game-porting-toolkit: unknown or unsupported macOS version: :dunno”, your version of Homebrew doesn’t have macOS Sonoma support. Update to the latest version of Homebrew and try again.

```brew update brew -v install apple/apple/game-porting-toolkit```

### Wine prefix 

A Wine prefix contains a virtual C: drive. You will install the toolkit and your game into this virtual C: drive. Run the following command to create a new Wine prefix named my-game-prefix in your home directory.

```WINEPREFIX=~/my-game-prefix `brew --prefix game-porting-toolkit`/bin/wine64 winecfg```

   * A “Wine configuration” window should appear on your screen.
   * Change the version of Windows to Windows 10.
   * Choose Apply and then OK to exit winecfg.

If the “Wine configuration” window does not appear, and no new icon appears in the Dock, verify that you have correctly installed the x86_64 version of Homebrew as well as the game-porting-toolkit formula.

**Preparing the toolkit**

Make sure the Game Porting Toolkit dmg downloaded earlier is mounted at ```/Volumes/Game Porting Toolkit-1.0```. Use this script to copy the Game Porting Toolkit library directory into Wine’s library directory.

```ditto /Volumes/Game\ Porting\ Toolkit-1.0/lib/ `brew --prefix game-porting-toolkit`/lib/```

**Put the 3 scripts from the Game Porting Toolkit DMG into here /usr/local/bin using this command:**

```cp /Volumes/Game\ Porting\ Toolkit*/gameportingtoolkit* /usr/local/bin```

### Steam install

Go to Steam website and download the Windows version of Steam: https://cdn.cloudflare.steamstatic.com/client/installer/SteamSetup.exe and place in your Downloads folder.

**Install Steam**

```gameportingtoolkit ~/my-game-prefix ~/Downloads/SteamSetup.exe```

**Run Steam**

```gameportingtoolkit ~/my-game-prefix 'C:\Program Files (x86)/Steam/steam.exe'```

Log into Steam A common issue is that Steam will present with a blank black window.

Alternate way of launching Steam (after installing):

```MTL_HUD_ENABLED=1 WINEESYNC=1 WINEPREFIX=~/my-game-prefix /usr/local/Cellar/game-porting-toolkit/1.0/bin/wine64 'C:\Program Files (x86)/Steam/steam.exe'```

If this continues then close the Terminal window and then re-open and try again, repeat until the login screen opens. Now you should be able to download and launch Windows games through Steam.

### Launching individual game

Open your Wine prefix’s virtual C: drive in Finder ```(open ~/my-game-prefix/drive_c)``` and copy your game into an appropriate subdirectory.

**A. Standard launching**

```gameportingtoolkit ~/my-game-prefix 'C:\Program Files\MyGame\MyGame.exe'```

This launches the given Windows game binary with a visible extended Metal Performance HUD and filters logging to output from the Game Porting Toolkit.

**B. Launching without a HUD**

```gameportingtoolkit-no-hud ~/my-game-prefix 'C:\Program Files\MyGame\MyGame.exe'```

**C. Launching with Wine ESYNC disable**

```gameportingtoolkit-no-esync ~/my-game-prefix 'C:\Program Files\MyGame\MyGame.exe'```

## Whisky

[Back to the Top](#table-of-contents)

[Whisky](https://github.com/IsaacMarovitz/Whisky) is a modern Wine wrapper for macOS built with SwiftUI developed by [Isaac Marovitz](https://twitter.com/isaacmarovitz).

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/d1f60a22-6b30-4406-a837-6e37ea72f22d">
<br />
</p>
 
## Manage Temps/Fans (CPU and GPU)

[Back to the Top](#table-of-contents)

[Stats](https://github.com/exelban/stats) is a tool that allows you to monitor your macOS system in the menubar.

 * Battery level
 * Bluetooth devices
 * CPU utilization
 * Disk utilization
 * Fan's control
 * GPU utilization
 * Memory usage
 * Network usage
 * Sensors information (Temperature/Voltage/Power)
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/224650106-1be2ae52-e54d-48b1-acbd-a71a9fc1d1d1.png">
</p>


[iStat Menus](https://bjango.com/mac/istatmenus/)  is highly configurable tool, with full support for macOS light and dark menubar modes. It covers a huge range of stats, including a CPU monitor, GPU, memory, network usage, disk usage, disk activity, date & time, battery and more.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208856211-94234e2c-35c0-41e1-9d9e-a0ecaa844c6a.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208857140-af14f17a-3f18-49a3-a413-ca692b88e745.png">
</p>

 
## Gaming Peripherals

### RGB Devices

[Back to the Top](#table-of-contents)

[Logitech G Hub](https://www.logitechg.com/en-us/innovation/g-hub.html) is software tool that lets you customize Logitech G gaming mice, keyboards, headsets, speakers, and other devices.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208275997-2b60eac7-0fa3-43d0-a5c6-d49ae2447d61.png">
</p>

[Corsair iCUE](https://www.corsair.com/us/en/icue-mac) is a tool that enables gaming peripherals and personal computer components including computer case fans, RGB lighting, gaming headsets, gaming keyboards, gaming mouse, remap buttons and switches, RAM DIMMS and AIO CPU cooler together.
<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208275999-4904fece-56c6-4a04-a2de-04bb587d7c1b.png">
</p>
 
### Game Controllers

[Back to the Top](#table-of-contents)
 
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/196628394-d6bd6113-ee45-4e68-a035-678bcec4cdfd.png">
<br />
MacOS Ventura Settings for Game Controllers
</p>

[Xbox Wireless Controller + USB-C® Cable](https://www.xbox.com/en-us/accessories/controllers/xbox-wireless-controller-usb-c)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187094245-3c406751-4e4b-42fd-bd2c-a72181722fad.png">
<br />
Xbox Controller
</p>

[PlayStation 5 DualSense™ Wireless Controller](https://www.playstation.com/en-us/accessories/dualsense-wireless-controller/)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187094347-109c80cd-5cc3-4a97-8a8f-0181687ab0d4.png">
<br />
PS 5  DualSense™ Controller
</p>

[Nintendo Switch Pro Controller](https://www.amazon.com/Nintendo-Switch-Pro-Controller/dp/B01NAWKYZ0)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/194023448-09e74efa-67f8-4503-87f5-5b7e59289608.png">
<br />
Nintendo Switch Pro Controller
</p>

[8BitDo SN30 Pro+ Controller](https://www.8bitdo.com/sn30-pro-plus/)

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/226544985-d0c0301c-e927-4845-abf8-5d728943e674.png">
</br>
8BitDo SN30 Pro+ Controller
</p>

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/226544994-7628f14d-f558-48f6-92b5-940905ab3fd9.png">
 </br>
 8BitDo SN30 Pro+ Controller Button Mapping
</p>

[Google Stadia Controller on ebay](https://www.ebay.com/sch/i.html?_nkw=google+stadia+controller&_sop=12&mkevt=1&mkcid=1&mkrid=711-53200-19255-0&campid=5336728181&customid=&toolid=10001)
 
 **Switch your Stadia Controller to [Bluetooth mode](https://stadia.google.com/controller/)** to keep gaming wirelessly on your favorite devices and services after Stadia shuts down.
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/218290131-3346f2d5-ee93-4dba-b8ed-e28f05c9055f.png">
</p>

[Steam Contoller](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=steam+controller&_sacat=0)

 * **Note:** Steam Controllers were discontinued on November 26, 2019, though, you can still buy them on ebay.

 * [Steam Controller Setup](https://help.steampowered.com/en/faqs/view/41C5-7D8C-1671-411E)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/211141385-fe44e2a3-ebc2-41d7-acc1-4d14957ef9aa.png">

</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/211141386-8054ef27-e7de-4ecc-96e9-b8a46e45a9ea.png">

</p>


[Amazon Luna Controller](https://www.amazon.com/luna/getting-started)

* **The Luna Controller** is made for Amazon's cloud gaming service. Powered by Cloud Direct technology Connect directly to Amazon's custom game servers when playing on Luna, reducing roundtrip latency by 17 to 30 milliseconds vs. a local Bluetooth connection among Windows PC, Mac, and Fire TV. 

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/218290132-7a548dea-8c9b-4c96-8efb-24b9d8c7f74c.png">
</p>

 
## Setting up OBS Studio

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185703842-0926e10a-467a-471c-b5f6-b74df4e460d9.png">
  <br />
</p>

[OBS (Open Broadcaster Software)](https://obsproject.com/) is free and open source software for video recording and live streaming. Stream to Twitch, YouTube and many other providers or record your own videos with high quality H264 / AAC encoding. Starting with [OBS Studio version 28](https://projectobs.com/en/news/obs-studio-28-0/) it features 10-bit and HDR video encode support for [AV1](https://aomedia.org/av1-features/) and [HEVC](https://apps.apple.com/us/app/hevc/id768692338), and **native Apple Silicon support on macOS**.

**OBS Studio 29 new macOS features:**

 * Added an upward compressor filter.
 * Added a 3-band equalizer filter.
 * Added support for native HEVC and ProRes encoders on macOS, including [P010](https://learn.microsoft.com/en-us/windows/win32/medfound/10-bit-and-16-bit-yuv-video-formats) and [HDR](https://www.adobe.com/creativecloud/photography/discover/hdr.html). 
 * Added support for macOS Desk View.
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185704748-217443ac-57e3-4ab3-ba74-6d09c2fe62fb.png">
  <br />
  OBS Studio
</p>

 
 ### Useful OBS Studio 3rd party plugins and themes.
 
  * **[OBS Studio Themes](https://obsproject.com/forum/resources/categories/themes.10/)**
 
  * **[touch portal icon packs](https://www.touch-portal.com/assetsdb/show-all.php?cat=i)**
 
  * **[Streamlink](https://streamlink.github.io/)** is a CLI utility which pipes video streams from various services into a video player, such as VLC.  

  * **[Advanced Scene Switcher](https://github.com/WarmUpTill/SceneSwitcher)** plugin; an automated scene switcher.
  * **[Audio Pan](https://github.com/norihiro/obs-audio-pan-filter)** plugin; control stereo pan of audio source.
  * **[Browser](https://github.com/obsproject/obs-browser)** plugin; CEF-based OBS Studio browser plugin.
  * **[Directory Watch Media](https://github.com/exeldro/obs-dir-watch-media)** plugin; filter you can add to media source to load the oldest or newest file in a directory.
  * **[Downstream Keyer](https://github.com/exeldro/obs-downstream-keyer)** plugin; add a Downstream Keyer dock.
  * **[Dynamic Delay](https://github.com/exeldro/obs-dynamic-delay)** plugin; filter for dynamic delaying a video source.
  * **[Freeze Filter](https://github.com/exeldro/obs-freeze-filter)** plugin; freeze a source using a filter.
  * **[Gradient Source](https://github.com/exeldro/obs-gradient-source)** plugin; adding gradients as a Source.
  * **[GStreamer](https://github.com/fzwoch/obs-gstreamer)** plugins; feed GStreamer launch pipelines into OBS Studio and use GStreamer encoder elements.
  * **[Move Transition](https://github.com/exeldro/obs-move-transition)** plugin; move source to a new position during scene transition.
  * **[Multi Source Effect](https://github.com/norihiro/obs-multisource-effect)** plugin; provides a custom effect to render multiple sources.
  * **[NDI](https://github.com/Palakis/obs-ndi)** plugin; Network A/V via NewTek's NDI.
  * **[NvFBC](https://gitlab.com/fzwoch/obs-nvfbc)** plugin; screen capture via NVIDIA FBC API. Requires [NvFBC patches for Nvidia drivers](https://github.com/keylase/nvidia-patch) for consumer grade GPUs.
  * **[Soundboard](https://github.com/cg2121/obs-soundboard)** plugin; adds a soundboard dock.
  * **[Source Copy](https://github.com/exeldro/obs-source-copy)** plugin; adds copy and paste options to the tools menu.
  * **[Source Dock](https://github.com/exeldro/obs-source-dock)** plugin; create a Dock for a source, which lets you see audio levels, change volume and control media. 
  * **[Recursion Effect](https://github.com/exeldro/obs-recursion-effect)** plugin; recursion effect filter.
  * **[Replay Source](https://github.com/exeldro/obs-replay-source)** plugin; slow motion replay async sources from memory.
  * **[RGB Levels](https://github.com/petrifiedpenguin/obs-rgb-levels-filter)** plugin; simple filter to adjust RGB levels.
  * **[RTSPServer](https://github.com/iamscottxu/obs-rtspserver/)** plugin; encode and publish to a RTSP stream.
  * **[Scale to Sound](https://github.com/Qufyy/obs-scale-to-sound)** plugin; adds a filter which makes a source scale based on the audio levels of any audio source you choose
  * **[Scene Collection Manager](https://github.com/exeldro/obs-scene-collection-manager)** plugin; filter, backup and restore Scene Collections.
  * **[Scene Notes Dock](https://github.com/exeldro/obs-scene-notes-dock)** plugin; create a Dock for showing and editing notes for the current active scene.
  * **[Source Record](https://github.com/exeldro/obs-source-record)** plugin; make sources available to record via a filter.
  * **[Source Switcher](https://github.com/exeldro/obs-source-switcher)** plugin; to switch between a list of sources.
  * **[Spectralizer](https://github.com/univrsal/spectralizer)** plugin; audio visualization using fftw.
  * **[StreamFX](https://github.com/Xaymar/obs-StreamFX)** plugin; collection modern effects filters and transitions.
  * **[Teleport](https://github.com/fzwoch/obs-teleport)** plugin; open NDI-like replacement.
  * **[Text Pango](https://github.com/kkartaltepe/obs-text-pango)** plugin; Provides a text source rendered using Pango with multi-language support, emoji support, vertical rendering and RTL support.
  * **[Text PThread](https://github.com/norihiro/obs-text-pthread)** plugin; Rich text source plugin with many advanced features.
  * **[Time Warp Scan](https://github.com/exeldro/obs-time-warp-scan)** plugin; a time warp scan filter.
  * **[Transition Table](https://github.com/exeldro/obs-transition-table)** plugin; customize scene transitions.
  * **[Virtual Cam Filter](https://github.com/exeldro/obs-virtual-cam-filter)** plugin; make sources available to the virtual camera via a filter
  * **[VNC Source](https://github.com/norihiro/obs-vnc)** plugin; VNC viewer that works as a source.
  * **[Websockets](https://github.com/Palakis/obs-websocket)** plugin; remote-control OBS Studio through WebSockets, compatible with [StreamControl](https://play.google.com/store/apps/details?id=dev.t4ils.obs_remote&hl=en).

## Discord

[Back to the Top](#table-of-contents)

[Discord](https://discord.com/) is an application with modern voice & text chat app. It provides clear voice, multiple server and channel support, mobile apps, and more. It's available on Linux, macOS, Windows, iOS, Android, and your web browser.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/203752975-d489f776-2039-474d-82ce-1cdd3dcdeff7.png">
</p>

## Twitch

[Back to the Top](#table-of-contents)

[Twitch for MacOS/iOS](https://apps.apple.com/us/app/twitch-live-game-streaming/id460177396)is an application where thousands of communities come together for our favorite streamers join millions enjoying live games, music, sports, esports, podcasts, cooking shows, IRL streams, etc..

  * [Running your iOS apps/games in macOS](https://developer.apple.com/documentation/apple-silicon/running-your-ios-apps-in-macos)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/203753175-0aaea65d-013e-4a4e-b67d-19a6ca52ff56.png">
</p>


## Game Stores & Launchers

### Apple Arcade
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Apple Arcade](https://www.apple.com/apple-arcade/) is a game subscription service that gives up to six family members unlimited access to 100+ incredibly fun games, all with no ads and no in-app purchases.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112693074-377cb100-8e3d-11eb-910c-1095c91da6d5.png">
</p>

### CrossOver for MacOS

[Back to the Top](#table-of-contents)

[CrossOver for MacOS](https://www.codeweavers.com/store) is a tool that let's you run many popular Windows games on your MacOS system. It comes with an easy to use, single click interface, which makes installing your games simple and fast. CrossOver is built on the latest versions of Wine, based on contributions from both CodeWeavers and the open-source Wine community.

 * [CrossOver Apps Compatibility Database](https://www.codeweavers.com/compatibility?browse=&app_desc=&company=&rating=&platform=&date_start=&date_end=&name=ea&search=app#results)
 
  * **Recommended:** [Microsoft Visual C++ Redistributable ARM64 Version](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

<img src="https://user-images.githubusercontent.com/45159366/206895903-e4ba0fc7-9df7-43b2-90f1-6e096c2e4c44.png">

### Steam
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Installing Steam through CrossOver](https://www.codeweavers.com/compatibility/crossover/steam)

 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">

 [Steam Link app](https://store.steampowered.com/steamlink/about) is available free of charge, streaming your Steam PC games to phones, tablets, and TV.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692999-14ea9800-8e3d-11eb-964a-6bee4e665900.png">
</p>

 ### Epic Games Store
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Heroic Game Launcher](https://heroicgameslauncher.com/) is an Open Source Game Launcher for Linux, Windows and MacOS (for both Native and Windows Games using Crossover). It supports launching games from the Epic Games Store using Legendary, a CLI alternative to the Epic Games Launcher. 

[Epic Games Store](https://www.epicgames.com/store/) is a digital video game storefront for Microsoft Windows and macOS, operated by Epic Games.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/111918016-3fed7a00-8a40-11eb-964e-930c801c1c72.png">
</p>

### Blizzard Battle.net 
[Back to the Top](#table-of-contents)

[Blizzard Battle.net](https://www.blizzard.com/apps/battle.net/desktop) is an internet-based online gaming, digital distribution, and digital rights management platform developed by Activision and Blizzard Entertainment. Battle.net is the launcher for World of Warcraft, Diablo III, StarCraft II, Hearthstone, Heroes of the Storm, Overwatch and Call of Duty.

<img src="https://user-images.githubusercontent.com/45159366/189614458-d51a15cb-d02d-4b1f-9e77-e712dcdb1d73.png">

### Origin 
[Back to the Top](#table-of-contents)
 
[Origin for MacOS](https://www.ea.com/origin-for-mac#) is an online gaming, digital distribution and digital rights management (DRM) platform developed by Electronic Arts that allows users to purchase games on the internet for PC and mobile platforms, and download them with the Origin client (formerly EA Download Manager, EA Downloader and EA Link).

 * [Origin installer through CrossOver](https://www.codeweavers.com/compatibility/crossover/origin)

<img src="https://user-images.githubusercontent.com/45159366/189614468-49c4a05c-d6ca-4988-b3e6-10f0c71463d6.png">

### EA Play 

[Back to the Top](#table-of-contents)

[EA Play](https://www.ea.com/ea-play) is a subscription-based video game service from Electronic Arts for the Xbox One, Xbox Series X/S, PlayStation 4, PlayStation 5 and Microsoft Windows platforms, offering access to selected games published by Electronic Arts along with additional incentives.

 * **Note:** you will need to install [Origin](https://www.ea.com/origin-for-mac#) to access all EA game titles for EA Play even if you use **EA Play on Steam**.
 
 **Ways to Play EA Play on macOS Apple Silicon:**
 
 * [Windows on Mac with Parallels Desktop](https://www.parallels.com/products/desktop/)
 * [EA Play through Xbox Game Pass](https://www.xbox.com/en-US/xbox-game-pass/games?xr=shellnav#)
 * [EA Play through Steam](https://store.steampowered.com/subscriptions/ea)

<img src="https://user-images.githubusercontent.com/45159366/189614466-476e0c4e-bab9-44bd-86c4-8aeadd739b63.png">

### Ubisoft Connect

[Back to the Top](#table-of-contents)

[Ubisoft Connect](https://itunes.apple.com/us/app/ubisoft-club/id405228226/) is a digital distribution, digital rights management, multiplayer and communications service created by Ubisoft to provide an experience similar to the achievements/trophies offered by various other game companies.

**Ways to Play Ubisoft Connect on macOS Apple Silicon:**
 
 * [Ubisoft Connect Installer (UPlay) through CrossOver](https://www.codeweavers.com/compatibility/crossover/Ubisoft-Connect-Installer)
 * [Windows on Mac with Parallels Desktop](https://www.parallels.com/products/desktop/)
 * [Ubisoft Connect through Xbox Game Pass](https://www.xbox.com/en-US/xbox-game-pass/games?xr=shellnav#)
 * [Using iPhone and iPad apps on Mac with Apple silicon](https://support.apple.com/guide/app-store/iphone-ipad-apps-mac-apple-silicon-fird2c7092da/3.0/mac/13.0)

<img src="https://user-images.githubusercontent.com/45159366/189614471-422cbad8-1ae7-4f06-ad81-7f3b68550569.png">

### GOG Galaxy

[Back to the Top](#table-of-contents)

[GOG Galaxy](https://www.gog.com/galaxy) is an application that lets you combine multiple game libraries into one place and connect with your friends across all gaming platforms, consoles included.

 * [GOG Galaxy installer through CrossOver](https://www.codeweavers.com/compatibility/crossover/gog-galaxy)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/200258282-da3cd773-c1c9-46d9-af12-aa54428be4ec.png">
</p>

### Itch.io Store

[Back to the Top](#table-of-contents)

[Itch.io Store](https://itch.io/app) is an app that lets you effortlessly download and run games and software from itch.io. All of your downloads are kept in a single place and are automatically updated.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/199429576-278a8604-7f76-4a41-abeb-84d03865daeb.png">
</p>

### Prism

[Back to the Top](#table-of-contents)

[Prism Launcher for Minecraft](https://prismlauncher.org/) is an Open Source Minecraft launcher with the ability to manage multiple instances, accounts and mods. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/209223630-4ae7df57-9561-411c-9be8-ea7cd76f266a.png">
</p>

### XIV on Mac

[Back to the Top](#table-of-contents)

[XIVONMAC](https://www.xivmac.com/) is a modern, open-source Final Fantasy XIV client for macOS.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/209292818-12684fdc-c160-4e7d-828f-1f6370b6b3a0.gif">
</p>


## Game Streaming

[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

### Cloud Game Streaming

[Back to the Top](#table-of-contents)

[Xbox Cloud Gaming](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming) is Microsoft's cloud-based Xbox game-streaming technology **(currently in Beta)**. **Play games like Forza Horizon 4, Halo 5: Guardians, Gears of War 4, Sea of Thieves, Cuphead, Red Dead Redemption 2, and 100+ other games on your mobile device or Chrome web browser**. Xbox Cloud Gaming does require an **[Xbox Game Pass Ultimate](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming)** subscription.

<img src="https://user-images.githubusercontent.com/45159366/108111388-74d56e00-7049-11eb-8aeb-3e5d65f9e832.png">

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/) is NVIDIA's Cloud Gaming Service.

<img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Amazon Luna](https://www.amazon.com/luna/landing-page) is Amazon's Cloud Gaming Service. Amazon Luna is Compatible/Supported on a variety of [Devices and Browsers](https://www.amazon.com/gp/help/customer/display.html?nodeId=GUFHUSX8X324T4XE).

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/112693072-364b8400-8e3d-11eb-9df0-d58af7ac9c9c.png">
</p>

[Shadow](https://shadow.tech/) is a fully-featured, cloud-based, high-end computer. It is the only remote service that offers performance capable of competing with a local PC. Available on Windows, macOS, Linux, Android/AndroidTV, and iOS/tvOS.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/200110962-dd631248-7a13-48bb-9b5a-acbbf8550e16.png">
</p>

### Local Game Streaming

[Back to the Top](#table-of-contents)

[Steam Remote Play Together](https://store.steampowered.com/remoteplay/#together) is a steam service that let's you share your Steam local multi-player games with friends over the internet, for free. Using Remote Play Together, one player owns and runs the game, then up to four players can join.

[Steam Link app](https://store.steampowered.com/steamlink/about) is available free of charge, streaming your Steam PC games to phones, tablets, and TV.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/112692999-14ea9800-8e3d-11eb-964a-6bee4e665900.png">
</p>


[PlayStation Remote Play](https://www.playstation.com/en-us/support/games/playstation-remote-play-on-pc-and-mac/) is a feature available on all PS4 and PS5 consoles that let's you control your PlayStation® console remotely wherever you have a high-speed internet connection. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172946885-27f83bdf-ab1a-4eaa-ad33-0e108f92a981.png">
</p>


[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) is a Free and Open Source Software Client for **PlayStation 4 and PlayStation 5 Remote Play** for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/208854787-3442b9df-60bc-4ed2-87e3-efaa159a6b7f.png">
</p>

[Parsec](https://parsec.app/cloud-gaming) is a video game streaming platform, which offers a wide variety of games and genres to choose from and provides a high-quality and smooth gameplay. SParsec is developed in order to provide a high-quality smooth gameplay, same time to be free of all ads and in-game purchases.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/166166858-e70ca081-8931-46f3-9dc3-fe9c719d76f8.png">
</p>

[Moonlight Game Streaming](https://moonlight-stream.org/) is a program that let you stream from your PC games over the Internet with no configuration required. Stream from almost any device, whether you're in another room or miles away from your gaming rig. [Sunshine](https://github.com/LizardByte/Sunshine) is a **Game stream host for Moonlight** that is a self-hosted, low latency, cloud gaming solution with support for AMD, Intel, and NVIDIA GPUs.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">
</p>

[Greenlight](https://github.com/unknownskl/xbox-xcloud-client) is an open-source client for xCloud and xHome streaming made in Javascript and Typescript. The client is an application wrapper around [xbox-xcloud-player](https://github.com/unknownskl/xbox-xcloud-player). It runs on Linux, MacOS, Windows, and Steam Deck.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/231686736-94adf5e6-1320-4f23-bea4-4fd05fe40da5.png">
</br>
Greenlight
</p>

## Android Games

[Back to the Top](#table-of-contents)

### BlueStacks
[BlueStacks](https://www.bluestacks.com/download.html) is a the Fastest & Lightest Android App Player for Windows and macOS.

 * [Getting Started with BlueStacks 4](https://support.bluestacks.com/hc/en-us/sections/360001186891-Getting-Started-with-BlueStacks-4)
 
<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210217487-269ce62d-49bb-4efc-ab26-61f5e2c41f72.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210217491-68aabb0d-a3f0-4a77-ae7b-de66937a25b5.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210217865-0fae0dc3-f229-49dd-9a88-14d75d154367.png">
</p>

## Game Emulators
[Back to the Top](#table-of-contents)

**Also checkout these subreddits for more great Game Emulators recommendations**
  
   - [r/emulation](https://www.reddit.com/r/emulation/)
   - [r/emulations](https://www.reddit.com/r/emulators/)
   - [r/RetroArch](https://www.reddit.com/r/RetroArch/)
   - [r/DolphinEmulator](https://www.reddit.com/r/DolphinEmulator/)
   - [r/Citra](https://www.reddit.com/r/Citra/)
   - [r/cemu](https://www.reddit.com/r/cemu/)
   - [r/yuzu](https://www.reddit.com/r/yuzu/)
   - [r/OpenEmu](https://www.reddit.com/r/OpenEmu/)
   - [r/MAME](https://www.reddit.com/r/MAME/)
   - [r/EmuDev](https://www.reddit.com/r/EmuDev/)
   - [r/Roms](https://www.reddit.com/r/Roms/)
   
### Frontends

[EmulationStation Desktop Edition (ES-DE)](https://www.es-de.org/) is a frontend application for browsing and launching games from your multi-platform game collection. It's  available for Unix/Linux, macOS(M1 & Intel) and Windows.

[RetroArch](https://www.retroarch.com/) is a frontend for emulators, game engines and media players. It enables you to run classic games on a wide range of computers and consoles through its slick graphical interface. Settings are also unified so configuration is done once and for all.

[OpenEmu](https://openemu.org/) is an open-source project whose purpose is to bring macOS game emulation into the realm of first-class citizenship. The project leverages modern macOS technologies, such as Cocoa, Core Animation, and other third-party libraries.

**Currently, OpenEmu can load the following game engines as plugins:**

  * Atari 2600 ([Stella](https://stella-emu.github.io/))
  * Atari 5200 ([Atari800](https://atari800.github.io/))
  * Atari 7800 ([ProSystem](https://github.com/raz0red/wii7800))
  * Atari Lynx ([Mednafen](https://mednafen.github.io/))
  * ColecoVision ([CrabEmu](http://crabemu.sourceforge.net/))
  * Famicom Disk System ([Nestopia](https://github.com/0ldsk00l/nestopia))
  * Game Boy / Game Boy Color ([Gambatte](https://github.com/sinamas/gambatte))
  * Game Boy Advance ([mGBA](https://mgba.io/))
  * Game Gear ([Genesis Plus](https://github.com/ekeeke/Genesis-Plus-GX))
  * Intellivision ([Bliss](https://github.com/jeremiah-sypult/BlissEmu))
  * NeoGeo Pocket ([Mednafen](https://mednafen.github.io/))
  * Nintendo (NES) / Famicom ([FCEUX](https://github.com/TASVideos/fceux), [Nestopia](https://github.com/0ldsk00l/nestopia))
  * Nintendo 64 ([Mupen64Plus](http://www.mupen64plus.org/))
  * Nintendo DS ([DeSmuME](http://desmume.org/))
  * Nintendo GameCube ([Dolphin](https://dolphin-emu.org/))
  * Odyssey² / Videopac+ ([O2EM](https://sourceforge.net/projects/o2em/))
  * PC-FX ([Mednafen](https://mednafen.github.io/))
  * SG-1000 ([Genesis Plus](https://github.com/ekeeke/Genesis-Plus-GX))
  * Sega 32X ([picodrive](https://github.com/notaz/picodrive))
  * Sega CD / Mega CD ([Genesis Plus](https://github.com/ekeeke/Genesis-Plus-GX))
  * Sega Genesis / Mega Drive ([Genesis Plus](https://github.com/ekeeke/Genesis-Plus-GX))
  * Sega Master System ([Genesis Plus](https://github.com/ekeeke/Genesis-Plus-GX))
  * Sega Saturn ([Mednafen](https://mednafen.github.io/))
  * Sony PSP ([PPSSPP](https://github.com/hrydgard/ppsspp))
  * Sony PlayStation ([Mednafen](https://mednafen.github.io/))
  * Super Nintendo (SNES) ([BSNES](https://bsnes.dev/), [Snes9x](https://github.com/snes9xgit/snes9x))
  * TurboGrafx-16 / PC Engine ([Mednafen](https://mednafen.github.io/))
  * TurboGrafx-CD / PCE-CD ([Mednafen](https://mednafen.github.io/))
  * Vectrex ([VecXGL](https://github.com/james7780/VecXGL))
  * Virtual Boy ([Mednafen](https://mednafen.github.io/))
  * WonderSwan ([Mednafen](https://mednafen.github.io/))

[Pegasus](https://pegasus-frontend.org/) is a cross platform, customizable graphical frontend for launching emulators and managing your game library (especially retro games) and launching them from one place. It's focused on customizability, cross platform support (including embedded devices) and high performance.

[Boxer](https://boxer.thec0de.com/) is a DOSBox game emulator frontend that's fit for your Mac. 

[Cartridge](https://github.com/unclebacon-live/cartridge) is a self-hosted game library made with Laravel + Vue.js.

Cartridge Features

- Scan for ROM files and match with IGDB game information
- Serve ROM download links alongside game details
- Manage access to library with user creation and permissions (WIP)
- Allow users to request games (Planned)
- Play select ROMs in-browser using JS emulators (Planned)
- Track played and favorite games (even ones that aren't available for download) (Planned)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/172274231-d691a850-1879-44fb-8fa0-08e549d7bb29.png">
    <br />
      Cartridge UI
</p>

### Nintendo GameCube & Wii

[Dolphin](https://dolphin-emu.org) is an emulator for two recent Nintendo video game consoles: the GameCube and the Wii. It allows PC gamers to enjoy games for these two consoles in full HD (1080p) with several enhancements: compatibility with all PC controllers, turbo speed, networked multiplayer, and even more.

[PrimeHack](https://github.com/shiiion/dolphin) is a fork of **Dolphin Emulator** to bring modern Mouse and Keyboard controls, as well as Dual-Stick gamepad controls to the Metroid Prime Trilogy. It also offers many other features such as increased FoV and various new cheats. [Versions of Metroid Prime that are currently supported.](https://github.com/shiiion/dolphin/wiki/Frequently-Asked-Questions#what-versions-of-metroid-prime-are-supported)

### Nintendo Switch 

[Ryujinx](https://ryujinx.org/) is an open-source Nintendo Switch emulator created by gdkchan and written in C#. This emulator aims at providing excellent accuracy and performance, a user-friendly interface, and consistent builds. 

[yuzu](https://yuzu-emu.org) is an experimental open-source emulator for the Nintendo Switch from the creators of Citra. 

### Nintendo 64

[m64p](https://m64p.github.io/) is a Nintendo 64 Emulator. It uses mupen64plus-gui, a brand new mupen64plus frontend written in Qt5. It supports all of the things you’d expect from a frontend (savestate management, pausing, screenshots). 

Nintendo 3DS

[Citra](https://citra-emu.org/) is an open-source emulator for the Nintendo 3DS capable of playing many of your favorite games.

### Nintendo DS

[DeSmuME](https://desmume.org/) is a Nintendo DS emulator.

[melonDS](https://github.com/melonDS-emu/melonDS) is a tool that aims at providing fast and accurate Nintendo DS emulation. While it is still a work in progress, it has a pretty solid set of features.

**Features:**

    * Nearly complete core (CPU, video, audio, etc...)
    * OpenGL renderer, 3D upscaling
    * RTC, microphone, lid close/open
    * Joystick support
    * Savestates
    * Various display position/sizing/rotations modes
    * Work-in-progress Wi-Fi emulation for online connectivity and local multiplayer
    * Experimental emulation of the Nintendo DSi

### Super Nintendo Entertainment System (SNES)

[Snes9x](https://www.snes9x.com/) is a portable, freeware Super Nintendo Entertainment System (SNES) emulator. 

[bsnes](https://github.com/bsnes-emu/bsnes) is a Super Nintendo (SNES) emulator focused on performance, features, and ease of use.

### Game Boy Advance

[mGBA](https://mgba.io/) is a new emulator for running Game Boy Advance games. It aims to be faster and more accurate than many existing Game Boy Advance emulators, as well as adding features that other emulators lack.

### DOS 

[Boxer](https://boxer.thec0de.com/) is a DOSBox game emulator frontend that's fit for your Mac. 

[DOSBox](https://www.dosbox.com/) is an open-source DOS emulator which primarily focuses on running DOS Games.

[DOSBox Staging](https://github.com/dosbox-staging/dosbox-staging) is a full x86 CPU emulator (independent of host architecture), capable of running DOS programs that require real or protected mode.

### Atari

[Stella](https://stella-emu.github.io/) is a multi-platform Atari 2600 VCS emulator released under the GNU General Public License (GPL). Stella is available on Windows MacOS, Linux, and FreeBSD.

[Hatari](https://hatari.tuxfamily.org/) is an Atari ST/STE/TT/Falcon emulator for Linux, BSD, MacOS, Windows and other systems which are supported by the SDL library. The Atari ST was a 16/32 bit computer system which was first released by Atari in 1985. 

### Sega Dreamcast

[Flycast](https://github.com/flyinghead/flycast) is a multi-platform Sega Dreamcast, Naomi and Atomiswave emulator derived from reicast.


[Redream](https://redream.io/) is a Dreamcast emulator, enabling you to play your favorite Dreamcast games in high-definition(1080p or 4k).

### PlayStation Portable

[PPSSPP](https://www.ppsspp.org/) is a PSP emulator that can run games in full HD resolution. It can even upscale textures that would otherwise be too blurry as they were made for the small screen of the original PSP.

### PlayStation 1

[DuckStation](https://www.duckstation.org/) is an simulator/emulator of the Sony PlayStation 1 console, focusing on playability, speed, and long-term maintainability.

[Avocado](https://github.com/JaCzekanski/Avocado) is a Modern PlayStation 1 emulator.

### PlayStation 2

[AetherSX2](https://www.aethersx2.com/) is a free (no ads) emulator of the PlayStation 2 (PS2) console for ARM-based devices. This enables you to play games which you have dumped from disc on your smartphone. 

[PCSX2](https://pcsx2.net/) is a Playstation 2 'emulator', a free program that tries to replicate the Playstation 2 console to enable you to play PS2 games on your PC.

[Play!](https://github.com/jpd002/Play-) is a PlayStation2 emulator for Windows, macOS, UNIX, Android, iOS and web browser platforms.

### PlayStation 3

[RPCS3](https://rpcs3.net/) is an experimental open-source Sony PlayStation 3 emulator and debugger written in C++ for Windows and Linux. RPCS3 started development in May of 2011 by its founders DH and Hykem. The emulator is currently capable of running over 1800 commercial titles powered by Vulkan and OpenGL.

### Xbox

[xemu](https://xemu.app/) is an original Xbox emulator.

[Xenia](https://github.com/xenia-project/xenia) is an Xbox 360 Emulator.

### MAME

[MAME](https://www.mamedev.org/) is a Arcade Machine Emulator.

## Performance Benchmarks
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Geekbench 6](https://www.geekbench.com/download/) is a cross-platform benchmark that measures your system's performance with the press of a button.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/220055002-0f99a8bf-6a3f-4511-9157-7bd398f623f4.png">
</p>

[GFXBench 5.0](https://gfxbench.com/result.jsp) is a high-end graphics benchmark that measures mobile and desktop performance with next-gen graphics features across all platforms. As a true cross-API benchmark, GFXBench supports all the industry-standard and vendor-specific APIs including OpenGL, OpenGL ES, Vulkan, Metal, DirectX/Direct3D and DX12. 

[PugetBench Benchmarks](https://www.pugetsystems.com/benchmarks/) is an application that has a number of benchmarks that are designed to test many popular professional applications using real-world projects and workflows. 

[Phoronix Test Suite](https://www.phoronix-test-suite.com/)

[UNIGINE Superposition](https://benchmark.unigine.com/superposition) is an extreme performance and stability test for PC hardware: video card, power supply, cooling system.

<img src="https://user-images.githubusercontent.com/45159366/107092007-8f8d2480-67b7-11eb-9c3f-a0cb02e6dfcd.png">

[asitop](https://github.com/tlkh/asitop) is a Performance monitoring CLI tool for Apple Silicon. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/176965986-3a2b1f88-93d6-4d1b-aa2d-545a86e5e667.png">
  <br />
</p>

# Game Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97361059-45151700-185c-11eb-9d12-dae51c79eb8a.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279021-ea6b5000-bbdd-11eb-9f59-5251fc3ac751.png">
  <br />
</p>

## Game Engines

**[Checkout the Unity Engine](https://unity.com/)**

<img src="https://user-images.githubusercontent.com/45159366/104788113-3432be00-5746-11eb-99b1-49360669f327.png">

**[Checkout the Unreal Engine](https://www.unrealengine.com/)**

<img src="https://user-images.githubusercontent.com/45159366/104788122-37c64500-5746-11eb-8f61-48a69b94582d.png">


**[Checkout the Godot Engine](https://godotengine.org/)**

[If you would like to Donate to the Godot Project](https://www.patreon.com/godotengine)

<img src="https://user-images.githubusercontent.com/45159366/104788134-3f85e980-5746-11eb-94c4-d97165ee888b.jpeg">


**[Checkout Blender](https://www.blender.org/)**

[If you would like to Donate to the Blender Project](https://fund.blender.org/)

<img src="https://user-images.githubusercontent.com/45159366/104788139-401e8000-5746-11eb-9647-058dee01a00e.png">


**[Checkout Game Maker Studio 2](https://www.yoyogames.com/gamemaker)**

<img src="https://user-images.githubusercontent.com/45159366/104788147-44e33400-5746-11eb-879a-bc6239c98ce4.jpg">


## Game Development Learning Resources

[Unreal Online Learning](https://www.unrealengine.com/en-US/onlinelearning-courses) is a free learning platform that offers hands-on video courses and guided learning paths.

[Unreal Engine Authorized Training Program](https://www.unrealengine.com/en-US/training-partners)

[Unreal Engine for education](https://www.unrealengine.com/en-US/education/)

[Unreal Engine Training & Simulation](https://www.unrealengine.com/en-US/industry/training-simulation)

[Unity Certifications](https://unity.com/products/unity-certifications)

[Autodesk for Games](https://www.autodesk.com/campaigns/autodesk-for-games)

[Getting Started with DirectX 12 Ultimate](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

[Getting Started with Vulkan](https://www.khronos.org/vulkan/)

[Getting Started with Apple Metal](https://developer.apple.com/metal/)

[Game Design Online Courses from Udemy](https://www.udemy.com/courses/Design/Game-Design/)

[Game Design Online Courses from Skillshare](https://www.skillshare.com/browse/game-design)

[Learn Game Design with Online Courses and Classes from edX](https://www.edx.org/learn/game-design)

[Game Design Courses from Coursera](https://www.coursera.org/courses?query=game%20design)

[Game Design and Development Specialization Course from Coursera](https://www.coursera.org/specializations/game-development)

## Game Development Tools

[Unreal Engine](https://www.unrealengine.com) is a game engine developed by Epic Games with the world's most open and advanced real-time 3D creation tool. Continuously evolving to serve not only its original purpose as a state-of-the-art game engine, today it gives creators across industries the freedom and control to deliver cutting-edge content, interactive experiences, and immersive virtual worlds.

[Unity](https://unity.com) is a cross-platform game development platform. Use Unity to build high-quality 3D and 2D games, deploy them across mobile, desktop, VR/AR, consoles or the Web, and connect with loyal and enthusiastic players and customers.

[Unigine](https://unigine.com) is a cross-platform game engine designed for development teams (C++/C# programmers, 3D artists) working on interactive 3D apps.

[Panda3D](https://www.panda3d.org/) is a game engine, a framework for 3D rendering and game development for Python and C++ programs, developed by Disney and CMU. Panda3D is open-source and free for any purpose, including commercial ventures.

[Havok](https://www.havok.com/) is a middleware software suite that provides a realistic physics engine component and related functions to video games. It is supported  and optimized across all major platforms, including Nintendo Switch, PlayStation®, Stadia, and Xbox. Along with integrations for Unity and Unreal Engine and are used in countless proprietary game engines.

[AutoDesk 3ds Max](https://www.autodesk.com/products/3ds-max/overview) is a professional software program for 3D modeling, animation, rendering, and visualization. 3ds Max allows you to create stunning game environments, design visualizations, and virtual reality experiences.

[Houdini](https://www.sidefx.com/) is a 3D procedural software for modeling, rigging, animation, VFX, look development, lighting and rendering in film, TV, advertising and video game pipelines.

[A-Frame](https://aframe.io) is a web framework for building virtual reality experiences in WebVR with HTML and Entity-Component. A-Frame works on Vive, Rift, desktop, mobile platforms.

[AppGameKit](https://www.appgamekit.com) is a powerful game development engine, ideal for Hobbyist and Indie developers. Where you can start coding in the easy to learn AppGameKit BASIC or use the libraries in C++ & Xcode.

[Blender](https://www.blender.org) is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline—modeling, rigging, animation, simulation, rendering, compositing and motion tracking, video editing and 2D animation pipeline.

[GameMaker Studio 2](https://www.yoyogames.com/gamemaker) is the latest and greatest incarnation of GameMaker. It has everything you need to take your idea from concept to finished game. With no barriers to entry and powerful functionality, GameMaker Studio 2 is the ultimate 2D development environment.

[Godot](https://godotengine.org) is a feature-packed, cross-platform game engine to create 2D and 3D games from a unified interface. It provides a comprehensive set of common tools, so that users can focus on making games without having to reinvent the wheel. Games can be exported in one click to a number of platforms, including the major desktop platforms (Linux, macOS, Windows) as well as mobile (Android, iOS) and web-based (HTML5) platforms.

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[OpenGL Shading Language(GLSL)](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL)) is a High Level Shading Language based on the C-style language, so it covers most of the features a user would expect with such a language.  Such as control structures (for-loops, if-else statements, etc) exist in GLSL, including the switch statement.

[High Level Shading Language(HLSL)](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl) is the High Level Shading Language for DirectX. Using HLSL, the user can create C-like programmable shaders for the Direct3D pipeline. HLSL was first created with DirectX 9 to set up the programmable 3D pipeline.

[Vulkan](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Metal](https://developer.apple.com/metal/) is a low-level GPU programming framework used for rendering 2D and 3D graphics on Apple platforms such as iOS, iPadOS, macOS, watchOS and tvOS.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

[OpenCL](https://www.khronos.org/opencl/) is a framework for writing programs that execute across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs and other processors or hardware accelerators.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/) is the Video Decode and Presentation API for UNIX. It provides an interface to video decode acceleration and presentation hardware present in modern GPUs.

[VA API](https://freedesktop.org/wiki/Software/vaapi/) is an open-source library and API specification, which provides access to graphics hardware acceleration capabilities for video processing.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation) is an extension of the X video extension (Xv) for the X Window System. The XvMC API allows video programs to offload portions of the video decoding process to the GPU hardware.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[LibGDX](https://github.com/libgdx/libgdx) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

[cocos2d-x](https://github.com/cocos2d/cocos2d-x) is a multi-platform framework for building 2d games, interactive books, demos and other graphical applications. It is based on cocos2d-iphone, but instead of using Objective-C, it uses C++. It works on iOS, Android, macOS, Windows and Linux.

[MonoGame](https://github.com/MonoGame/MonoGame) is a framework for creating powerful cross-platform games. The spiritual successor to XNA with thousands of titles shipped across desktop, mobile, and console platforms. MonoGame is a fully managed .NET open source game framework without any black boxes.

[Three.js](https://threejs.org) is a cross-browser JavaScript library and application programming interface used to create and display animated 3D computer graphics in a web browser using WebGL.

[Superpowers](http://superpowers-html5.com/) is a downloadable HTML5 app for real-time collaborative projects . You can use it solo like a regular offline game maker, or setup a password and let friends join in on your project through their Web browser.

[URHO3D](https://urho3d.github.io/) is a free lightweight, cross-platform 2D and 3D game engine implemented in C++ and released under the MIT license. Greatly inspired by OGRE and Horde3D.

[Vivox](https://www.vivox.com/) is a voice & text chat platform that's trusted by the world's biggest gaming brands and titles such as Fortnite, PUBG, League of Legends, and Rainbow Six Siege.

[HGIG](https://www.hgig.org/) is a volunteer group of companies from the game and TV display industries that meet to specify and make available for the public guidelines to improve consumer gaming experiences in HDR.

[GameBlocks](https://www.gameblocks.com/) is a Server Side Anti-Cheat & Middleware software.

## Augmented Reality (AR) & Virtual Reality (VR)

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[ARCore](https://developers.google.com/ar/) is a software development kit developed by Google that allows for augmented reality applications in the real world. These tools include environmental understanding, which allows devices to detect horizontal and vertical surfaces and planes. It also includes motion tracking, which lets phones understand and track their positions relative to the world. Also ARCore’s Light Estimation API lets your digital objects appear realistically as if they’re actually part of the physical world.

[OpenVR](https://github.com/ValveSoftware/openvr) is an API and runtime that allows access to VR hardware(Steam Index, HTC Vive, and Oculus Rift) from multiple vendors without requiring that applications have specific knowledge of the hardware they are targeting.

[OpenVR Benchmark on Steam](https://store.steampowered.com/app/955610/OpenVR_Benchmark/) is the first benchmark tool for reproducibly testing your real VR performance, rendering inside of your VR headset.

[OpenHMD](http://www.openhmd.net/) is open source API and drivers that supports a wide range of HMD(head-mounted display) devices such as Oculus Rift, HTC Vive, Sony PSVR, and others.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR—platforms and devices.

[Monado](https://monado.dev/) is the first OpenXR™ runtime for GNU/Linux. Monado aims to jump-start development of an open source XR ecosystem and provide the fundamental building blocks for device vendors to target the GNU/Linux platform.

[Libsurvive](https://github.com/cntools/libsurvive) is a set of tools and libraries that enable 6 dof tracking on lighthouse and vive based systems that is completely open source and can run on any device. It currently supports both SteamVR 1.0 and SteamVR 2.0 generation of devices and should support any tracked object commercially available.

[Simula](https://github.com/SimulaVR/Simula) is a VR window manager for Linux that runs on top of Godot. It takes less than 1 minute to install. Simula is officially compatible with SteamVR headsets equipped with Linux drivers (e.g. HTC Vive, HTC Vive Pro, & Valve Index). We have also added experimental support to OpenXR headsets that have Monado drivers (e.g. North Star, OSVR HDK, and PSVR). Some people have gotten the Oculus Rift S to run Simula via OpenHMD ([see here](https://github.com/OpenHMD/OpenHMD/issues/225#issuecomment-638454156)).

# Professional Audio/Video Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/100922475-caf73400-3492-11eb-88ac-d0976f3057d3.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119560582-f62f5180-bd58-11eb-842b-fcf4330f3e2f.png">
  <br />
</p>

## Audio/Video Learning Resources

[10 Video Production Tools That Make the Difference Between a Good Video and a Bad One by Dann Albright ](https://www.uscreen.tv/blog/video-production-equipment/)

[Online Audio Editing Classes from Skillshare](https://www.skillshare.com/browse/audio-editing)

[Online Video Editing Classes Skillshare](https://www.skillshare.com/search?query=Video-Editing)

[Video Editing Courses from Udemy](https://www.udemy.com/topic/video-editing/)

[Audio Editing Courses from udemy](https://www.udemy.com/topic/audio-editing/)

[Video Editing Courses from Coursera](https://www.coursera.org/courses?query=video%20editing)

[The Basics of Audio Editing from Coursera](https://www.coursera.org/lecture/vocal-production/basic-audio-editing-6JLBJ)

[Audacity Podcast Production Course: Audio Editing for Podcasters](https://www.thepodcasthost.com/academy/course-library/audacity-course/)

[Video Editing Online Training Courses from LinkedIn Learning](https://www.linkedin.com/learning/topics/video-editing)

[Audio Editing Online Training Courses from LinkedIn Learning](https://www.linkedin.com/learning/topics/audio-editing)

## Audio/Video Tools and Equipment

[H.264(AVC)](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC) is a video compression standard based on block-oriented and motion-compensated integer-DCT coding that defines multiple profiles (tools) and levels (max bitrates and resolutions) with support up to 8K.

[H.265(HEVC)](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding) is a video compression standard that is the successor to H.264(AVC). It offers a 25% to 50% better data compression at the same level of video quality, or improved video quality at the same bit-rate.

[FFmpeg](https://ffmpeg.org) is a leading multimedia framework that can decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge ones on multiple platforms such as Windows, macOS, and Linux.

[HandBrake](https://handbrake.fr/) is a tool for transcoding video from almost any format with a selection of widely supported codecs. It is supported on Window, macOS, and Linux.

[HTTP Live Streaming (HLS)](https://developer.apple.com/streaming/) is a communications protocol developed by Apple that sends live and on‐demand audio and video to iPhone, iPad, Mac, Apple Watch, Apple TV, and PC.

[Dynamic Adaptive Streaming over HTTP (DASH)](https://developer.mozilla.org/en-US/docs/Web/HTML/DASH_Adaptive_Streaming_for_HTML_5_Video) is an adaptive streaming protocol that allows for a video stream to switch between bit rates on the basis of network performance, in order to keep a video playing.

[OpenMAX™](https://www.khronos.org/openmax/) is a cross-platform API that provides comprehensive streaming media codec and application portability by enabling accelerated multimedia components to be developed, integrated and programmed across multiple operating systems and silicon platforms.

[GStreamer](https://gstreamer.freedesktop.org/) is a library for constructing graphs of media-handling components. The applications it supports range from simple Ogg/Vorbis playback, audio/video streaming to complex audio (mixing) and video (non-linear editing) processing. Applications can take advantage of advances in codec and filter technology transparently.

[Media Source Extensions (MSE)](https://www.w3.org/TR/media-source/) is a [W3C specification](https://github.com/w3c/media-source) that allows JavaScript to send byte streams to media codecs within Web browsers that support HTML5 video and audio. Also, this allows the implementation of client-side prefetching and buffering code for streaming media entirely in JavaScript.

[WebRTC](https://webrtc.org/) is an open-source project that adds real-time communication capabilities to your application that works on top of an open standard. It supports video, voice, and generic data to be sent between peers, allowing developers to build powerful voice- and video-communication solutions.

[Apple ProRes](https://support.apple.com/en-us/HT200321) is a codec technology developed by Apple for high-quality & high-performance editing in Final Cut Pro that supports up to 8K.

[Premiere Pro](https://www.adobe.com/products/premiere.html) is the industry-leading video editing software for film, TV, and the web. Creative tools, integration with other apps and services, and the power of Adobe Sensei help you craft footage into polished films and videos. With [Premiere Rush](https://www.adobe.com/products/premiere-rush.html) you can create and edit new projects from any device.

[Final Cut Pro](https://www.apple.com/final-cut-pro/) is Apple's professional grade video editing software.

[Kdenlive](https://kdenlive.org/en/) is an open source video editing tool that supports unlimited multimedia files. It's based on the MLT Framework, KDE and Qt. People who are looking for a very versatile video editing tool that comes packed with features. The latest 20.08 release is out with nifty features like Interface Layouts, Multiple Audio Stream support, Cached data management and Zoombars in the Clip Monitor and Effects Panel but one may argue that the highlights of this release are stability and interface improvements.

[OpenShot](https://www.openshot.org/) is an open-source video editing tool that's designed for users new in the editing environment. It has simple features such as a simple drag-and-drop function, it provides an easy-to-use and quick-to-learn user interface. The powerful video editor offers tons of efficient ways to cut and trim down your videos. You can freely utilize the unlimited tracks, video effects engine, title editor, 3D animations, slow motion, and time effects. It supports commonly used video codecs that are supported by FFmpeg like WebM (VP9), AVCHD (libx264), HEVC (libx265) and audio codecs like mp3 (libmp3lame) and aac (libfaac). The program can render MPEG4, ogv, Blu-ray and DVD video, and Full HD videos for uploading to the internet video websites like YouTube.

[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/) is the world’s only solution that combines professional 8K editing, color correction, visual effects and audio post production all in one software tool! You can instantly move between editing, color, effects, and audio with a single click. DaVinci Resolve Studio is also the only solution designed for multi user collaboration so editors, assistants, colorists, VFX artists and sound designers can all work live on the same project at the same time.

[Blender](https://www.blender.org/features/video-editing/) comes with a built-in video sequence editor allows you to perform basic actions like video cuts and splicing, as well as more complex tasks like video masking or color grading. The Video Editor includes: Live preview, luma waveform, chroma vectorscope and histogram displays. Audio mixing, syncing, scrubbing and waveform visualization.

[Lightworks](https://www.lwks.com/) is a non-linear video editing application for editing and mastering digital video used by the film industry. Its professional edition has been used for box office hits, such as Shutter Island, Pulp Fiction, and Mission Impossible. Intimidating user interface. Like professional video editors, such as Adobe Premiere Pro, Lightworks is rather complicated to use for new users.

[Shotcut](https://www.shotcut.org/) is an open source multi-platform video editor. You can perform various actions such as video editing (including 4K video quality), add effects, create new movies, import most image files formats, export to almost any file format and much more.

[Olive](https://www.olivevideoeditor.org) is a free non-linear video editor aiming to provide a fully-featured alternative to high-end professional video editing software.

[OBS (Open Broadcaster Software)](https://obsproject.com/) is free and open source software for video recording and live streaming. Stream to Twitch, YouTube and many other providers or record your own videos with high quality H264 / AAC encoding.

[REAPER](https://www.reaper.fm/) is a complete digital audio production application for computers, offering a full multitrack audio and MIDI recording, editing, processing, mixing and mastering toolset.REAPER supports a vast range of hardware, digital formats and plugins, and can be comprehensively extended, scripted and modified.

[Logic Pro](https://www.apple.com/logic-pro/) is a digital audio workstation (DAW) and MIDI sequencer software application for macOS.

[Ableton Live](https://www.ableton.com/live) is a digital audio workstation application. It's designed to be an instrument for live performances as well as a tool for composing, recording, arranging, mixing, and mastering.

[Bitwig Studio](https://www.bitwig.com) is a digital audio workstation that has linear and non-linear workflows for sound design, recording, live performance, and more. Along with 90+ instruments, effects, and other creative tools. It is supported Windows, macOS, and Linux.

[SonoBus](https://sonobus.net) is an easy to use application for streaming high-quality, low-latency peer-to-peer audio between devices over the internet or a local network.

[Avid Pro Tools](https://www.avid.com/pro-tools) is a digital audio workstation for mixing Dolby Atmos or other 3D audio for film or TV, working in a large mixing stage or a small editing suite.

[Adobe Audition](https://www.adobe.com/products/audition.html) is a digital audio workstation with tools for color, audio, and graphics, Premiere Pro works seamlessly with other apps and services, including After Effects, Adobe Audition, and Adobe Stock.

[JACK Audio Connection Kit AKA JACK](https://jackaudio.org/) is a professional sound server daemon that provides real-time, low-latency connections for both audio and MIDI data between applications that implement its API. JACK can be configured to send audio data over a network to a main machine, which then outputs the audio to a physical device. This can be useful to mix audio from a number of linked computers without requiring additional cables or hardware mixers, and keeping the audio path digital for as long as possible.

[JACK2](https://github.com/jackaudio/jack2) is a C++ version of the JACK low-latency audio server for multi-processor machines. It is a new implementation of the JACK server core features that aims at removing some limitations of the JACK1 design. The activation system has been changed for a data flow model and lock-free programming techniques for graph access have been used to have a more dynamic and robust system.

[Image-Line FL Studio](https://www.image-line.com/fl-studio/) is a digital audio workstation for mixing audio and music sequencing developed by Image-Line.

[Propellerhead Reason](https://www.reasonstudios.com/) is a digital audio workstation with tools you need for creative music production, recording, sequencing and mixing.

[Cockos Reaper](https://www.cockos.com/reaper/) is a full, flexible feature set digital audio workstation with tools used for commercial/home studios, broadcast, location recording, education, science/research, sound design, game development, and more.

[PreSonus Studio One](https://www.presonus.com/products/studio-one) is a digital audio workstation application, used to create, record, mix and master music and other audio.

[Steinberg Cubase](https://new.steinberg.net/cubase/) is a digital audio workstation developed by Steinberg for music/MIDI recording and arranging/editing of audio.

[Digital Performer](https://motu.com/products/software/dp/) is a digital audio workstation and music sequencer software package. It's can recording, editing, arranging, mixing, mastering, MIDI, and more. Digital Performer will take your music to its highest level, thanks to sophisticated features like Stretch Audio (powered by Zynaptiq’s ZTX PRO technology), live triggering and looping.

[Sonic Visualiser](https://www.sonicvisualiser.org) is a free, open-source application for Windows, Linux, and Mac, designed to be the first program you reach for when want to study a music recording closely.

[PipeWire](https://pipewire.org) is a server and user space API to deal with multimedia pipelines.It provides a low-latency, graph based processing engine on top of audio and video devices that can be used to support the use cases currently handled by both pulseaudio and JACK. PipeWire was designed with a powerful security model that makes interacting with audio and video devices from containerized applications easy. Nodes in the graph can be implemented as separate processes, communicating with sockets and exchanging multimedia content using fd passing.

[LMMS](https://lmms.io/) is an open source digital audio workstation application program. When LMMS is pairedr with appropriate computer hardware, it allows music to be produced by arranging samples, synthesizing sounds, playing on a MIDI keyboard, and combining the features of trackers and sequencers. Developed by Paul Giblock and Tobias Junghans, this program stands for "Linux MultiMedia Studio" and supports handy plugins that enables it to work on different operating systems.

[Ardour](http://ardour.org/) is an open source, collaborative effort of a worldwide team including musicians, programmers, and professional recording engineers. Development is transparent — anyone can watch our work as it happens. Like a good piece of vintage hardware, you can open the box and look inside.

[Audacity](https://www.audacityteam.org/) is an easy-to-use, multi-track audio editor and recorder for Windows, Mac OS X, GNU/Linux and other operating systems. Developed by a group of volunteers as open source and offered free of charge. Amazing support community.

# 3D Graphics and Design
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97116104-27a74800-16b8-11eb-9556-bdb90ba45ce7.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126396094-16e1b14c-e1a2-4086-803d-5a8d99edeade.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338215-6ec91f00-b4ca-11eb-9c9e-f5cf377ca3c4.png">
  <br />
</p>

 **Blender's Cycles Render Engine. Source: [Blender](https://www.blender.org)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338217-6ffa4c00-b4ca-11eb-92d0-9aa30230495d.png">
  <br />
</p>

 **Blender VFX(Visual Effects). Source: [Blender](https://www.blender.org)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338223-72f53c80-b4ca-11eb-8100-2e2abd98c910.png">
  <br />
</p>

**Designing a simple UI/UX for an application in Adobe XD. Source: [Adobe](https://www.adobe.com/products/xd.html)**

## 3D Graphics and Design Learning Resources

[Introduction to Pixar's Universal Scene Description (USD)](https://graphics.pixar.com/usd/docs/index.html)

[Intro to using Universal Scene Description with NVIDIA](https://developer.nvidia.com/usd)

[First steps with Universal Scene Description in Blender](https://code.blender.org/2019/07/first-steps-with-universal-scene-description/)

[AMD Radeon ProRender Developer Suite](https://gpuopen.com/radeon-prorender-suite/)

[Blender Foundation](https://www.blender.org/foundation/)

[Blender Foundation Certification Training](https://www.blender.org/certification/)

[Blender Cloud Courses](https://cloud.blender.org/courses)

[Blender Institute](https://www.blender.org/institute/)

[Blender Education](https://www.blender.org/get-involved/)

[Blender Network](https://www.blendernetwork.org/)

[Blender Courses from Udemy](https://www.udemy.com/topic/blender/)

[AutoDesk Learning, Training & Certification](https://www.autodesk.com/training)

[AutoDesk Design Academy](https://academy.autodesk.com)

[AutoDesk Courses and Specializations from Coursera](https://www.coursera.org/autodesk)

[Cinema 4D Quick Tips](https://www.cineversity.com/vidplaylist/cinema_4d_quick_tips)

[Getting Started with Cinema 4D](https://www.cineversity.com/vidplaylist/getting_started_with_cinema_4d_r20)

[Graphic Design Masterclass(Photoshop, Illustrator, InDesign) from Udemy](https://www.udemy.com/course/graphic-design-masterclass-everything-you-need-to-know/)

[Vectr: Beginner's Guide To Graphic Design from udemy](https://www.udemy.com/course/vectr-beginners-guide-to-graphic-design/)

[Canva MasterClass: Design For EveryDay Use from Udemy](https://www.udemy.com/course/canva-masterclass-design-for-everyday-use/)


## 3D Graphics and Design Tools

[Adobe Creative Cloud](https://www.adobe.com/creativecloud.html) is a collection of 20+ desktop and mobile apps(Lightroom, Photoshop, Illustrator, InDesign, Rush, Etc.) and services for photography, design, video, web, UX, and more.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126396097-921982e9-5b6b-4f1e-90f3-9b7033eeb9ca.png">
  <br />
</p>

[Autodesk®](https://www.autodesk.com/) is a collection of professional software products and services used in 3D design, architecture, engineering, manufacturing, and high production entertainment companies.

[Maya®](https://www.autodesk.com/products/maya/overview) is a 3D computer animation, modeling, simulation, and rendering software that can create realistic effects from explosions to cloth simulation.

[Maya LT™](https://www.autodesk.com/products/maya-lt/overview) is a game design software for indie game makers that can create and animate realistic-looking characters, props, and environments using the sophisticated 3D modeling and animation tools.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687226-2a682780-d1ca-11eb-9408-4b32ddc7d493.png">
  <br />
</p>

**Autodesk® Maya. Source:[Autodesk](https://www.autodesk.com/products/maya/overview)**

[3DS Max®](https://www.autodesk.com/products/3ds-max/overview) is a 3D modeling and rendering software for design visualization, games, and animation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687233-3358f900-d1ca-11eb-8e9c-0cb68b16db0e.png">
  <br />
</p>

**Autodesk® 3DS Max. Source:[Autodesk](https://www.autodesk.com/products/3ds-max/overview)**

[Arnold](https://www.autodesk.com/products/arnold/overview) is an advanced Monte Carlo ray tracing(Global illumination) renderer that helps you work more efficiently.

[ReCap™](https://www.autodesk.com/products/recap/overview) is a Pro 3D scanning software to transform the physical world into a digital asset. With reality capture data you can better understand and verify existing and as-built conditions to gain insights and make better decisions.

[Flame®](https://www.autodesk.com/products/flame/overview) is a 3D VFX and finishing software provides powerful tools for 3D compositing, visual effects, and editorial finishing. An integrated, creative environment means faster compositing, advanced graphics, color correction, and more.

[Mudbox®](https://www.autodesk.com/products/mudbox/overview) is a 3D digital painting and sculpting software that let's you sculpt and paint highly detailed 3D geometry and textures.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687228-2e944500-d1ca-11eb-894e-b55e15c35620.png">
  <br />
</p>

**Autodesk® Mudbox. Source:[Autodesk](https://www.autodesk.com/products/mudbox/overview)**

[Blender](https://www.blender.org) is a professional, free and open-source 3D computer graphics software toolset used for creating animated films, visual effects, art, 3D printed models, interactive 3D applications and video games.

[Cinema 4D](https://www.maxon.net/en-us/products/cinema-4d/overview/) is a professional 3D and VFX software suite that is capable of doing procedural and polygonal modeling, animation, lighting, texturing, motion graphic and rendering.

[Houdini](https://www.sidefx.com/) is a 3D procedural software for modeling, rigging, animation, VFX, look development, lighting and rendering in film, TV, advertising and video game pipelines.

[Open Graphics Library(OpenGL)](https://www.opengl.org/) is an API used across multiple  programming languages and platforms for hardware-accelerated rendering of 2D/3D vector graphics currently developed by the [Khronos Group](https://www.khronos.org/).

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[Vulkan](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Metal](https://developer.apple.com/metal/) is a low-level GPU programming framework used for rendering 2D and 3D graphics on Apple platforms such as iOS, iPadOS, macOS, watchOS and tvOS.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

[OpenGL ES](https://www.khronos.org/opengles/) is the mobile subset of OpenGL. It's supported on all major mobile platforms, and is also the base for WebGL.

[OpenCL](https://www.khronos.org/opencl/) is a framework for writing programs that execute across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs and other processors or hardware accelerators.

[Vuforia](https://developer.vuforia.com/) is a comprehensive, scalable enterprise AR platform. Our wide-ranging solution suite ensures that we can provide the right AR technology to every customer based on their business needs.

[Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio) is a tool that allows anyone to create beautiful 3D augmented reality (AR) experiences in a matter of minutes with no coding required.

[OpenVX™](https://www.khronos.org/openvx/) is an open-source, royalty-free standard for cross platform acceleration of computer vision applications. OpenVX enables performance and power-optimized computer vision processing, especially important in embedded and real-time use cases such as face, body and gesture tracking, smart video surveillance, advanced driver assistance systems (ADAS), object and scene reconstruction, augmented reality, visual inspection, robotics and more.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR—platforms and devices.

[GPUImage framework](https://github.com/BradLarson/GPUImage) is a BSD-licensed iOS library that lets you apply GPU-accelerated filters and other effects to images, live camera video, and movies. In comparison to Core Image (part of iOS 5.0), GPUImage allows you to write your own custom filters, supports deployment to iOS 4.0, and has a simpler interface. However, it currently lacks some of the more advanced features of Core Image, such as facial detection.

[GPUImage3](https://github.com/BradLarson/GPUImage3) is the third generation of the [GPUImage framework](https://github.com/BradLarson/GPUImage), an open source project for performing GPU-accelerated image and video processing on Mac and iOS. The original GPUImage framework was written in Objective-C and targeted Mac and iOS, the second iteration rewritten in Swift using OpenGL to target Mac, iOS, and Linux, and now this third generation is redesigned to use Metal in place of OpenGL.

[EGL](https://www.khronos.org/egl/) is an interface between Khronos rendering APIs such as OpenGL or OpenVG and the underlying native platform window system.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/) is the Video Decode and Presentation API for UNIX. It provides an interface to video decode acceleration and presentation hardware present in modern GPUs.

[VA API](https://freedesktop.org/wiki/Software/vaapi/) is an open-source library and API specification, which provides access to graphics hardware acceleration capabilities for video processing.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation) is an extension of the X video extension (Xv) for the X Window System. The XvMC API allows video programs to offload portions of the video decoding process to the GPU hardware.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[Universal Scene Description](https://github.com/PixarAnimationStudios/USD) is an efficient, scalable system for authoring, reading, and streaming time-sampled scene description for interchange between graphics applications.

[OpenTimelineIO](https://github.com/PixarAnimationStudios/OpenTimelineIO) is an interchange format and API for editorial cut information. OTIO is not a container format for media, rather it contains information about the order and length of cuts and references to external media. OTIO includes both a file format and an API for manipulating that format. It also includes a plugin architecture for writing adapters to convert from/to existing editorial timeline formats. It also implements a dependency- less library for dealing strictly with time, opentime.

[OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) is a set of open source libraries that implement high performance subdivision surface (subdiv) evaluation on massively parallel CPU and GPU architectures. This codepath is optimized for drawing deforming subdivs with static topology at interactive framerates. The resulting limit surface matches Pixar's Renderman to numerical precision.

[Affinity Designer](https://affinity.serif.com/en-gb/designer/) is a professional vector graphics editor used by many industry leading illustrators, designers, and other creatives looking to create high-quality concept art.

[Sketch](https://www.sketch.com) is a professional vector graphics app with a beautiful UI and powerful toolset.

[Krita](https://krita.org/) is an open source professional painting program for digital painting and 2D animation.

[Vectr](https://vectr.com/) is a free graphics software used to create vector graphics easily and intuitively.

[Glimpse](https://glimpse-editor.github.io/) is a cross-platform raster graphics editor based on the GNU Image Manipulation Program available for Linux, macOS, and Windows. A great tool for making YouTube video thumbnails.

[GNU Image Manipulation Program(GIMP)](https://www.gimp.org/) is a cross-platform raster graphics editor based on the GNU Image Manipulation Program(GIMP) available for Linux, macOS, and Windows. A great free alternative for Photoshop.

[PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) is a simple Patch for [GIMP 2.10+](https://www.gimp.org/) to help all Adobe Photoshop Users feel at home.

[Photopea](https://www.photopea.com/) is an advanced online photo editor supporting Adobe Photoshop(PSD), GIMP(XCF), Sketch App(Sketch), Adobe XD(XD) and CorelDRAW(CDR) formats.

[Inkscape](https://inkscape.org/) is an open-source vector graphics editor; it can be used to create or edit vector graphics such as illustrations, diagrams, line arts, charts, logos and complex paintings.

[Gthree](https://github.com/alexlarsson/gthree) is a GObject/Gtk+ port of three.js.

[FreeCAD](https://www.freecadweb.org/) is a free and open-source general-purpose parametric 3D CAD modeler and a building information modeling software with finite-element-method support.

[Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura) is the world’s most popular 3D printing software. Prepare prints with a few clicks, integrate with CAD software for an easier workflow, or dive into custom settings for in-depth control.

[Dust3D](https://dust3d.org/) is a cross-platform open-source modeling software. It helps you create a 3D watertight model in seconds. Use it to speed up your character modeling in game making, 3D printing, and so on.

[Goxel](https://github.com/guillaumechereau/goxel) is a free and Open Source 3D Voxel Editor.

[Sketchfab](https://sketchfab.com/tags/open-source) gives you open-source 3D models ready to view, buy, and download for free.

# Swift Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719675-03949c00-fb39-11ea-8f81-bf4cd544c17f.png">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880054-dd9fb700-8292-11eb-9478-a5d62dc76f9d.png">
<br />
Developing with SwiftUI in Xcode 12
</p>

## Swift Learning Resources

[Swift](https://developer.apple.com/swift/) is Apple's main programming language for iOS, macOS, watchOS, and tvOS app development. Though, many parts of Swift will be familiar to developers from their experience of developing in C and Objective-C.

[Swift Evolution](https://github.com/apple/swift-evolution) maintains proposals for changes and user-visible enhancements to the Swift Programming Language.

[Xcode + Swift](https://developer.apple.com/swift/resources/) makes developing applications for MacOS and iOS fast and fun.

[Swift 5.3 Basics](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)

[Start Developing iOS Apps with Swift](https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/)

[Apple Developer Documentation](https://developer.apple.com/documentation)

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation)

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore)

[Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)

[Virtualization Framework](https://developer.apple.com/documentation/virtualization)

[Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics)

[Getting Started with LLDB](https://developer.apple.com/library/archive/documentation/IDEs/Conceptual/gdb_to_lldb_transition_guide/document/lldb-basics.html)

[Mac Catalyst - iOS - Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/ios/overview/mac-catalyst/)

[Amazon EC2 Mac Instances](https://aws.amazon.com/ec2/instance-types/mac/)

[Swift GitHub](https://github.com/apple/swift)

[Apple Developer Forums](https://developer.apple.com/forums/)

[Swift Forums](https://forums.swift.org/)

[Google's Swift Style Guide](https://google.github.io/swift/)

[Swift Courses Online from Coursera](https://www.coursera.org/courses?query=swift)

[Swift Courses Online from Udemy](https://www.udemy.com/topic/swift/)

[Learning Swift course from Codecademy](https://www.codecademy.com/learn/learn-swift)

## Swift Tools, Libraries, and Frameworks

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/) is a set of Apple APIs that developers can use to rapidly port their iOS apps to [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/) and take full advantage of the new capabilities on the new Apple hardware.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[CocoaPods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[Vapor](https://github.com/vapor/vapor) is a web framework for Swift. It provides a beautifully expressive and easy to use foundation for your next website, API, or cloud project.

[Hero](https://github.com/HeroTransitions/Hero) is a library for building iOS view controller transitions. It provides a declarative layer on top of the UIKit's cumbersome transition APIs—making custom transitions an easy task for developers.

[Kingfisher](https://github.com/onevcat/Kingfisher) is a powerful, pure-Swift library for downloading and caching images from the web. It provides you a chance to use a pure-Swift way to work with remote images in your next app.

[Realm](https://github.com/realm/realm-cocoa) is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the iOS, macOS, tvOS & watchOS versions of Realm Swift & Realm Objective-C.

[Perfect](https://github.com/PerfectlySoft/Perfect) is a complete and powerful toolbox, framework, and application server for Linux, iOS, and macOS (OS X). It provides everything a Swift engineer needs for developing lightweight, maintainable, and scalable apps and other REST services entirely in the Swift programming language for both client-facing and server-side applications.

[Alamofire](https://github.com/Alamofire/Alamofire) is an HTTP networking library written in Swift.

[Eureka](https://github.com/xmartlabs/Eureka) is an elegant iOS form builder in Swift

[Carthage](https://github.com/Carthage/Carthage) is intended to be the simplest way to add frameworks to your Cocoa application. Carthage builds your dependencies and provides you with binary frameworks, but you retain full control over your project structure and setup. Carthage does not automatically modify your project files or your build settings.

[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) is reactive extensions to Cocoa frameworks, built on top of ReactiveSwift.

# Objective-C Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121821278-e6ff3d80-cc4c-11eb-9a57-c7aa13b88b30.png">
</p>


## Objective-C Learning Resources

[Objective-C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html) was the primary programming language used for writing software for macOS and iOS until [Swift](https://developer.apple.com/swift/) was introduced in 2014. It is a superset of the C programming language and provides object-oriented capabilities and a dynamic runtime.

[Apple Developer Forums](https://developer.apple.com/forums/)

[Google's Objective-C Style Guide](https://google.github.io/styleguide/objcguide.html)

[Objective C Courses on Coursera](https://www.coursera.org/courses?query=objective%20c)

[Objective-C online course on Udemy](https://www.udemy.com/topic/objective-c/)

[Objective-C for Swift Developers course by David Nutter](https://www.pluralsight.com/courses/objective-c-swift-developers)

[Objective-C Essential Training on LinkedIn Learning](https://www.linkedin.com/learning/objective-c-essential-training/)

[Objective-C for Swift Developers on Udacity](https://www.udacity.com/course/objective-c-for-swift-developers--ud1009)

## Objective-C Tools, Libraries, and Frameworks

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[CocoaPods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C in your Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[Realm](https://github.com/realm/realm-cocoa) is a mobile database(replaces Core Data & SQLite) that runs directly inside phones, tablets or wearables.

[Infer](https://github.com/facebook/infer) is a static analysis tool for Java, C++, Objective-C, and C.

[Mantle](https://github.com/Mantle/Mantle) is a model framework that makes it easy to write a simple model layer for your Cocoa or Cocoa Touch application.

[Quick](https://github.com/Quick/Quick) is a behavior-driven development framework for Swift and Objective-C.

[Aspects](https://github.com/steipete/Aspects) is a simple library for aspect oriented programming in Objective-C and Swift.

[Hammerspoon](https://github.com/Hammerspoon/hammerspoon) is a tool for powerful automation for macOS that acts as a bridge between the operating system and a Lua scripting engine.

[Nimbus](https://github.com/jverkoey/nimbus) is an iOS framework whose feature set grows only as fast as its documentation.

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>

## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools and Frameworks

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Apple-Silicon-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
