# Razer Blade 15 Advanced 2020 Hackintosh
First of all, note that there will not be any tutorials here, but it will provide EFI and what I noticed when installing Hackintosh using OpenCore. Please refer to the configuration table below to make sure your Razer Blade configuration is the same as mine. Before using my EFI, be careful not to copy and paste directly, edit your own config.plist in advance. Back up your important data and check it step by step according to the official __[OpenCore](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites)__  tutorial. good luck.

## Hardware
**Razer Blade 15 Advanced Model (Early 2020)**
|             | Description | macOS 11.6 Compatibility    |
| :---        | :---        | :---          |
| CPU     | Intel Core i7-10875H @ 2.30GHz 8 Cores| OK   |
| Memory   | 16GB Samsung DDR4 3200MHz        | OK     |
| GPU   | NVIDIA GeForce RTX 2070 Super with Max-Q Desgin (8GB / Razer USA) / Intel UHD 630        | RTX not woring, UHD630 works fine. ACPI to disable dGPU.     |
| MB   | Razer CH551 (LPC Controller - 068D)        | OK     |
| Screen   | SHARP SHP14FD LQ156M1JW18 15.6" 1920 x 1080 300Hz        | OK     |
| Storge   | Samsung SSD 970 EVO Plus 2TB        | OK     |
| Internet   | Inetl Wi-Fi 6 AX201 160MHz        | OK - Thanks to OpenIntelWireless supporting it!     |
| Sound | Realtek ALC298 | OK - Please read below |
| Webcam | Windows Hellow Built-in IR HD webcam(1MP/720P) | OK - But not support windows hello (Yup, no face ID lmao)|
| TouchPad | Precision Glass | OK |
| Keyboard | Per-key RGB Powered by Razer Chroma N-Key rollover backlit | OK - But no razer software for macOS - Backlit control works good) |
| Port | USB 3.1 | OK |
| | Thunderbolt 3 (USB-C) | OK |
| | HDMI |NO - HDMI connected directly to Nvidia GPU and will not work in macOS |
| Power | 230W Power Adapter | OK |
