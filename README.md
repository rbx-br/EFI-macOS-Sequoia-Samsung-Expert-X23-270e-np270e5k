# Samsung Expert X23 (270E - NP270E5K)
## macOS Sequioa 15 / OpenCore 1.0.1
### OLCP 2.0.2 to patch Graphics and Wireless card

![Samsung](https://github.com/user-attachments/assets/6a9dceed-8151-4875-a01a-4ed64c895c4a)

### SMBIOS: MacBookPro16,3 for boot macOS Sequoia

## Basic description:
Intel® Core™ i7-5500U - Broadwell

RAM 8GB LPDDR3 *(soldered on the motherboard)*

Intel® HD Graphics 5500 - 2GB

Nvidia GeForce 920M 2GB - ***Disabled***

Qualcomm Atheros AR9565 *(soldered on the motherboard)*

Realtek RTL8105E

Wildcat Point-LP High Definition Audio Controller - based on Realtek ALC282

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

Internal Bluetooth ***(Works on Big Sur with the indicated kexts)***

![System](https://github.com/user-attachments/assets/8e53f126-d138-4b55-a684-74f76a46c0b8)
