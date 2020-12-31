[![License](https://img.shields.io/badge/license-MIT-_red.svg)](https://opensource.org/licenses/MIT)

<a href="https://www.buymeacoffee.com/medheeraj"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a beer&emoji=🍺&slug=medheeraj&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"></a>

## Introduction
Last updated on 2020/12/31
**SubzzZ**
can find possible subdomains using passive recon. Tool also support Permutations, Mutations, Alterations.

## Passive Recon via:

[✔] Crt.sh 


[✔] Web.Archive.org 


[✔] Dns.bufferover.run 


[✔] Threatcrowd.org 


[✔] Hackertarget.com 


[✔] Certspotter.com 


[✔] Anubis-DB(jonlu.ca) 


[✔] Virustotal  


[✔] Alienvault(otx) 


[✔] Urlscan.io  


[✔] Threatminer  


[✔] Entrust.com  


[✔] Riddler.io  


[✔] Dnsdumpster 


[✔] Rapiddns 


[✔] Choas 


[✔] Permutations, Mutations, Alterations  



## Usage
```
root@me_dheeraj:$ bash subzzZ
[-] Usage: ./subzzZ [-d/--domain] target.com

Output will be saved in scans/target.com-YYYY-MM-DD directory
```
##### Prerequisites
- python3 
- jq
- shuffledns [@projectdiscovery](https://github.com/projectdiscovery/shuffledns)
- massdns [@blechschmidt](https://github.com/blechschmidt/massdns)
- httpx [@pdiscoveryio](https://github.com/projectdiscovery/httpx)
