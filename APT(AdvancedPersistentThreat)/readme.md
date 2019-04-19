
## NampÐáÌ½Ö÷»ú´æ»î

```bash 
nmap -sn -PR 192.168.3.1/24
```

## Msf 
```bash
use auxiliary/scanner/discovery/arp_sweep
set RHOSTS 192.168.3.0/24
set THREADS 10

```

## netdiscover 
```bash
netdiscover -r 192.168.1.0/24 -i wlan0
```


## Powershell 
```bash
powershell.exe -exec bypass -Command "Import-Module .\arpscan.ps1;Invoke-ARPScan -CIDR 192.168.2.0/24"
```