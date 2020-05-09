# Mac 系统命令行修改屏幕分辨率

# 查询分辨率
```shell
system_profiler SPDisplaysDataType | grep Resolution
```

```bash
Display List:
    0 : 1552
Choose a display:0

 Mode List:
      0 : 2880* 1800*33554435@  0
      1 : 1440*  900* 3@  0
 *    2 : 3360* 2100* 3@  0
      3 : 2560* 1600* 3@  0
      4 : 2048* 1280* 3@  0
      5 : 1650* 1050* 3@  0
      6 : 1280*  800* 3@  0
      7 : 1152*  720* 3@  0
      8 : 1024*  768*515@  0
      9 :  840*  524* 3@  0
     10 :  800*  600*515@  0
     11 :  640*  480*515@  0
choose a mode :
```

参考：https://github.com/playerC/mrandr.git