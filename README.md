# Asus-X550L-Hackintosh
![Logo](https://www.podfeet.com/blog/wp-content/uploads/2022/02/OpenCore-Logo-bg.png)

This repository provides the basic EFI folder to run macOS BigSur on an Asus X550L laptop. This EFI has not been tested on macOS Monterey
## Setup
### Asus X550L

[![OpenCore](https://img.shields.io/badge/OpenCore-v0.8.3-blue?style=flat&logo=okta)](https://github.com/acidanthera/OpenCorePkg)

| **Category**   | **Component**                 		
|----------------|--------------------------------------|
|**CPU**		       |1.7GHz Intel Core i3-4010U	 		            |										      
|**GPU**		       |Intel HD 4400				     		 										       |
|**RAM**         |4GB 1600 MHz DDR3               		   |
|**SDD**         |120 GB SATA	 		                |
|**Screen**       |15,6 Inch HD	1366x768	 		               |										      
|**Wi-Fi/BT**    |Built In (Atheros) 			     		                |	     
|**Ethernet**    |Realtek RTL8111				 		                    |										      								      

### Versions
- **OpenCore:** 0.8.3
- **macOS:** 11.7.1 

### BIOS configuration
- Fast Boot: Disabled
- Secure Boot : Disabled
- VT-d: Enabled
- VT-x: Enabled
- SATA Mode: AHCI
- DVMT Pre-Allocated(iGPU Memory): 64MB or higher

### What is working:
- Wifi & Bluetooth
- Battery percentage indicator
- Backlight	
- Ethernet
- Receiving and sending calls
- Webcam
- Apple services (See https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)


### Known issues:
- Bluetooth is unstable
- Wifi signal is indicated as weak
- Airdrop, Handoff and most continuity functions do not work.

![Desktop](https://cdn.discordapp.com/attachments/489435134253203456/1035873972669120533/Capture_decran_2022-10-29_a_13.06.33.png)
