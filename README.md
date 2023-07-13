# Cloudflare Captcha Bypass
> ⚠️ **This cloudflare captcha bypass is no longer stable and no longer updated**

### Additional Informations
 - The proxies type are `http,https` ...
 - You need fast proxies without this, the script will be **unstable**
 - This script does not depending on captcha solving API

### Installation
Install the app on the server
```sh
user@domain:~# git clone https://github.com/inplex-sys/cloudflare-uam-bypass.git
user@domain:~# cd ./cloudflare-captcha-bypass/
user@domain:~# pip3 install Pysocks colored undetected_chromedriver
user@domain:~# python3 ./main.py <target> <threads> <proxies-file>
```
