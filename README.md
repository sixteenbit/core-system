# Gameboy Zero

1. Download the latest pre-made image (https://github.com/sixteenbit/gameboy-zero/releases)
1. Unzip so that you have an .img file
1. Use [Etcher](https://etcher.io/) or [Apple Pi Baker](https://www.tweaking4all.com/software/macosx-software/macosx-apple-pi-baker/) to copy img to SD card
1. Create a blank file named `ssh` on the root of the card which enables ssh (optional)
1. Create a file named `wpa_supplicant.conf` on the root of the card with your WiFi credentials. Sample below. (optional)

## wpa_supplicant.conf Example

```
country=US
update_config=1
ctrl_interface=/var/run/wpa_supplicant

network={
	ssid="NETWORK_NAME"
	psk="NETWORK_PASSWORD"
	scan_ssid=1
}
````
