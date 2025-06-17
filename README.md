# Samsung Expert X40 ***UPDATING SOON***
## macOS Sequioa 15 / OpenCore 1.0.1
### OLCP 2.0.2 to patch Graphics and Wireless card

![Samsung](https://github.com/user-attachments/assets/6a9dceed-8151-4875-a01a-4ed64c895c4a)

### SMBIOS: MacBookPro16,3 for boot macOS Sequoia

*For some reason the macOS installer would not load even using "-no-compat-check" in boot-args*

## Basic description:
Intel® Core™ i7-5500U - Broadwell

RAM 8GB LPDDR3 *(soldered on the motherboard)*

Intel® HD Graphics 5500 - 2GB

Nvidia GeForce 920M 2GB - ***Disabled***

Qualcomm Atheros AR9565 _Wi-FI_ + AR3012 _Bluetooth_ *(soldered on the motherboard)*

Realtek RTL8105E

Wildcat Point-LP High Definition Audio Controller - based on Realtek ALC282

## This EFI can boot
![11](https://github.com/user-attachments/assets/add96347-e7e3-46ac-ac8d-1c72434e7a44) ***macOS Big Sur 11.7.10***


![12](https://github.com/user-attachments/assets/60c761ef-7e99-4b7f-a6da-b11ddf1c8af3) ***macOS Monterey 12.7.6***


![13](https://github.com/user-attachments/assets/3b7f23da-3c5d-4906-b9cb-5228d66f1ad0) ***macOS Ventura 13.7***


![14](https://github.com/user-attachments/assets/83a3c216-8af2-400c-8914-d9f9bd1fb7df) ***macOS Sonoma 14.7***


![15](https://github.com/user-attachments/assets/432a5c91-6c1b-4098-b58f-90c6f2ed9dc5) ***macOS Sequoia 15.0.1***

### It may work on older versions of macOS with another SMBIOS, but has not been tested.


# ✅ Working

Battery life indicator

Intel Graphics HD 5500 ***(Needs OCLP to work)***

Sound internal and external

Keyboard

Touchpad ***(up to 3 fingers gestures. IDK if it's a bug, hardware issue or limitation)***

Webcam

SD Card reader

Screen brightness control

Ethernet

HDMI / VGA

iCloud

WiFi ***(Needs OCLP to work)*** ***(~15Mbps on 802.11b / ~25Mbps on 802.11g / ~1Mbps on 802.11n)***
Unfortunately, this board has extremely limited support from Mojave onwards and since it is soldered there is not much that can be done. It is necessary to change the PHY mode on the router.

# ❌ Not working

Internal Bluetooth 
(***<img width="20" alt="20" src="https://github.com/user-attachments/assets/add96347-e7e3-46ac-ac8d-1c72434e7a44"> Works on Big Sur with the indicated kexts***)

NVIDIA GeForce 920M ***(Despite being a Kepler variant I was unable to get the system to activate, even disabling the integrated graphics.)***

![System](https://github.com/user-attachments/assets/8e53f126-d138-4b55-a684-74f76a46c0b8)
