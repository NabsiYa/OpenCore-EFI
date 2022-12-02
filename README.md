<h1 align="center">Hackintosh build for the Lenovo Legion T5 26AMR5</h1>

<p align="center">
	<img src="https://img.shields.io/badge/Ventura-13.0.1-sucess">
	<img src="https://img.shields.io/badge/Monterey-12.6-sucess">
	<img src="https://img.shields.io/badge/Lenovo%20Legion%20T5-26AMR5-informational">
	<img src="https://img.shields.io/badge/OpenCore-0.8.6-informational">
</p>

> ### What's working?

| Feature                              | Status | Dependency          |
| :----------------------------------- | ------ | ------------------- |
| GPU Acceleration (RX 6800 XT)        | ✅ Working | No dependencies works natively. |
| CPU (Ryzen 7 5800)                   | ✅ Working | Requires [AMD Vanilla Patches](https://github.com/AMD-OSX/AMD_Vanilla)  |
| Audio (ALC897)                       | ✅ Working | `AppleALC.kext` (Layout-id: 11) | 
| WiFi (AC1300)                        | ✅ Working | Works using `RtWlan.kext` and `RtWlanU1827.kext` (Requires [Wireless USB Big Sur Adapter](https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter/releases/tag/V15)) |
| Ethernet (RTL8111)                   | ✅ Working | `RealtekRTL8111.kext` |
| Bluetooth                            | ❌ Not Working | N/A |

| Feature                              | Status | Info          |
| :----------------------------------- | ------ | ------------------- |
| iCloud, iMessage, FaceTime           | ✅ Working | Requires proper SMBIOS (MacPro 7,1) |
| AirDrop                              | ✅ Working | N/A  |
| Time Machine                         | ✅ Working | Works Natively | 