### Computer Spec:
| Component        | Brank                              |
| ---------------- | ---------------------------------- |
| Scheda Madre     | GA Z490M Gaming X (BIOS F6b)       | 
| CPU              | Intel i5 10600                     | 
| IGPU             | Intel® UHD Graphics 630            |
| GPU              | Sapphire RX 590 Nitro+             |
| Audio            | Realtek ALC1200A                   |
| Ram              | 32 Gb DDR4 3200 Mhz                |
| Wifi + Bluetooth | Fenvi FV - T919                    |
| NVMe             | Samsung 970 Pro 512Gb              |
| SmBios           | IMac 20.1                          |
| BootLoader       | OpenCore                           |

## Device Screenshot
![infodp1](./Screenshot/3.png)
![infodp2](./Screenshot/4.png)

## Patch IGPU HDMI\DP Output
![infodp2](./Screenshot/8.png)
![infodp2](./Screenshot/9.png)
![infodp2](./Screenshot/10.png)

### What works and What doesn't or WIP:
- [x] Intel UHD 630 iGPU
- [x] ALC1200 Internal Speakers
- [x] ALC1200 HDMI Audio Output
- [x] All USB Ports 
- [x] Wi-Fi and Bluetooth BCM94360CS2 Module
- [x] Intel (11)I219-V LAN
- [x] NVRAM
- [x] Windows boot from OpenCore

## USB Map by Hackintool
- Usb port mapping performed

![infobigsur](./Screenshot/5.png)
- Disabled unused device
- Cosmetics DSM in Configplist
![PCI](./Screenshot/7.png)

## Info Section SSDT GA Z490M Gaming X

![SSDT](./Screenshot/6.png)

https://www.msi.com/Motherboard/MAG-Z490-TOMAHAWK

