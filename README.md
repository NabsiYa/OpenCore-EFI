<h1 align="center">Hackintosh build for the Lenovo Legion T5 26AMR5</h1>

<img src="/images/desktop.png">

<p align="center">
	<img src="https://img.shields.io/badge/Ventura-13.0.1-sucess">
	<img src="https://img.shields.io/badge/Monterey-12.6-sucess">
	<img src="https://img.shields.io/badge/Lenovo%20Legion%20T5-26AMR5-informational">
	<img src="https://img.shields.io/badge/OpenCore-0.8.6-informational">
</p>

# DISCLAIMER

> I am not responsible for any damage you cause to your computer by using this project.

<br>

<details>
<summary><strong>System Specifications</strong></summary>
<br>

| Part       | Name         | Supported.     |
| :--------- | ------------ | -------------- |
| CPU        | Ryzen 7 5800 | ✅ |
| GPU        | RX 6800 XT   | ✅ |
| MOBO       | MSI B550 (?) | ✅ | 
| RAM        | Hynix (16GB) | ✅ |
| NVMe Drive | Samsung SSD  | ❌ |
| SATA Drive | Kingston SSD | ✅ |
| WLAN       | Realtek WLAN | ❌ |
| Bluetooth  | N/A          | ❌ |

</details>

<details>
<summary><strong>What's working?</strong></summary>
<br>

> ### Functionality

| Feature                              | Status | Dependency          |
| :----------------------------------- | ------ | ------------------- |
| GPU Acceleration                     | ✅ Working | No dependencies works natively. |
| CPU                                  | ✅ Working | Requires [AMD Vanilla Patches](https://github.com/AMD-OSX/AMD_Vanilla)  |
| Audio                                | ✅ Working | `AppleALC.kext` (Layout-id: 11) | 
| WiFi (Archer T3U)                    | ✅ Working | Works using `RtWlan.kext` and `RtWlanU1827.kext` (Requires [Wireless USB Big Sur Adapter](https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter/releases/tag/V15)) |
| Ethernet                             | ✅ Working | `RealtekRTL8111.kext` |
| Bluetooth                            | ❌ Not Working | N/A |

> ### Extra

| Feature                              | Status         | Info                                |
| :----------------------------------- | -------------- | ----------------------------------- |
| iCloud, iMessage, FaceTime           | ✅ Working     | Requires proper SMBIOS (MacPro 7,1) |
| AirDrop                              | ❌ Not Working | Requires Bluetooth to function.     |
| Time Machine                         | ✅ Working     | Works Natively                      | 

</details>

## You can contact me at discord `Lupia#4123`
