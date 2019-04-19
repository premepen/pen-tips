## Nmap 使用教程
- 基础略

- [nmap-vulners](https://github.com/vulnersCom/nmap-vulners)
```bash
nmap -sV -p 80 --unprivileged \
--script vulners \
--script-args mincvss=1.0 \
 192.168.2.73
```


- [vulscan](https://github.com/scipag/vulscan)
  - 暂时用了下, 没看出来厉害的地方。

### Namp 自定义NSE脚本编写
- 比如可以捕捉扫描的内容和自定义
- 可以将获取的数据进行格式化再输出
- 可以将数据联立 `mysql/lua` 进行统计入库




