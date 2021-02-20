# HP Pavilion au624tx Hackintosh

| Part       | Info                                                         |
| ---------- | ------------------------------------------------------------ |
| Model      | HP Pavilion au624tx                                          |
| CPU        | Intel Core i5-7200U                                          |
| Mem        | 8GB DDR4 2400 MHz                                            |
| HDD        | Toshiba  1TB                                     |
| IGPU       | Intel HD Graphics 620                                        |
| DGPU       | Nvidia GeForce 940MX                                         |
| Sound Card | Realtek ALC295 (Layout ID = 13, 28 or 77)                    |
| WIFI / BT  | Intel Corporation Dual Band Wireless-AC 3168NGW              |
| Ethernet   | RTL8100/8169 PCI Express Gigabit Ethernet Controller         |
| CardReader | Realtek PCIE Card Reader                                     |    



## Usage
This EFI is for HP Pavillion 15-AU624TX, you can use this efi in near-by specs/model to boot hackintosh

# Notes
-You need to disable Secure boot. <br>
-Before installing use TOOLS/gensmbios for generatiing a serial key, mld and uuid of MacBookPro14,1 for your hackBook. <br>
-dGPU ( 940mx ) is disabled via ssdt, you may have to modify it according to your bios device name !! <br>
-All the necssary kexts and aml are already inside the EFI and every inbuilt hardware is working !! <br>
-However this EFI is suitable for Catalina but with this EFI you can boot BigSur too (you may need to replace wifi kext of bigsur to make wifi work) ! (tested) <br>

## Not Working

1. Nvidia DGPU ( As you know, Optimus is not supported at the moment )
2. You can face Fairplay4.0 issues

## Working

1. Intel iGPU
2. Sound
3. USB
4. Ethernet
5. WiFi
6. Bluetooth
7. Battery percentage
8. Trackpad
9. Sleep
10. CPU power management
11. Brightness keys
12. Media keys
13. Card reader
14. HDMI-output (audio and video)


## Credits

-Apple ( For macOS ) <br>
-github.com/the-erik-kwok ( For helping me in patching battery ) <br> 
-Hackintosh Community ( For thier guides ) <br>
-github.com/Greasy-Monkey ( For help and Support ) <br>
