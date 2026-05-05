# HP-500B-MT-Hackintosh


This one actually took me a sh*t ton of time to make since High Sierra refused to initialize my RX 560 properly. 


# This EFI is confirmed to boot Catalina 10.15.7, however I have not tested higher versions due to having low RAM on my build.
<img width="2425" height="1364" alt="image" src="https://github.com/user-attachments/assets/a377fe9b-7762-46fc-8bc8-5e4a71fd1c1c" />

## Specs:
OpenCore Version: 1.0.6

RAM: 1x2GB 1066MHz DDR3

SSD: KIOXIA Exceria Sata 240GB

WiFi: Intel Centrino Advanced-N 6205

CPU: Intel Core 2 Quad Q8400

GPU: Asus Dual Radeon RX 560

Ethernet controller: Realtek RTL8100

## WHAT'S BROKEN
For some reason when you shutdown or restart the system, it hangs on a black screen which from there you have to manually shutdown/restart the system.
Sleep mode hibernates the PC and resets the CMOS every time.

## PRE-INSTALL DEPLOYMENT

Grab [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) and generate a serial with the SMBIOS "MacPro6,1" (without quotes)

## My sincere thanks to:
- [Acidanthera](https://github.com/acidanthera)
- [Dortania's OC guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [CorpNewt's tools](https://github.com/corpnewt)
