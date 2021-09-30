# Hackintosh - MSI MAG B550M MORTAR WIFI


Hello, 

This repository is meant to share the tweaks and adjustments I achieved - with help from others, of course!

My setup:

- MSI B550M MAG MORTAR WIFI
- AMD Ryzen 3600 (Stock)
- 2x8GB DDR4 3200MHz Corsair Vengeance
- XFX RX 580 8GB (UV -50mv + Memory Timmings)
- SSD Kingston 256 GB 

Pre-requisites:

- Downgrade Bios Version to '7C94v12' (otherwise the installation will mostly render unsuccessful) (notice that, this means you cannot have and 5000 series processor, since they need a newer bios version to work)
- Latest OS (As of today that is: BigSur 11.6 and Monterey Beta 8. Both are working fine)
- Latest OpenCore Bootloader (as of today that is 0.7.4, never copy the contents of the EFI folder and use it strait away, always use the latest kexts and opencore files)
- AMD Kernel Patches (https://github.com/AMD-OSX/AMD_Vanilla)


Bios Settings:

- Wake on Lan --> OFF
- Above 4G Decoding --> OFF
- TPM --> OFF
- Secureboot --> OFF

What's Working: 

- iMessage
- Facetime
- Updates
- Netflix, Prime Video, Apple TV... so on.
- Photoshop and other adobe apps.
- Handoff, continuity, mirroring.
- Sleep
- USB ports
- Audio, HDMI audio..
- Wifi
- Bluetooth
- Ethernet
- Display Port and HDMI
- Location Services
- Fans sensors
- GPU Sensors

What's not working:

- Onboard Mic
- Sidecar
- Airdrop

Websites and people that have helped me: (thanks to you all)

https://forum.amd-osx.com/index.php?threads/macos-monterey-patches-released.1892/

https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html

https://github.com/AMD-OSX/AMD_Vanilla


