# Network 网络篇

## OSI开放式互联参考类型

如图:

1. 物理层: 两台物理机通信 比特流 传输类型 电流强弱
2. 数据链路层: 错误检测，数据传输可靠性(交换机，帧解码等)
3. 网络层: 网络地址 -> 数据地址(路由器，数据包，IP) 如何切分段落
4. 传输层: 解决传输质量，最重要一层，分割数据 TCP/UDP
5. 会话层: 不同机器建立会话
6. 表示层: 信息的语法语义，加密解密，转换翻译
7. 应用层: HTTP

进程间通信概念框架

## TCP/IP(真正实现)

1. 应用层: TFTP、HTTP、SNMP、FTP、SMTP、DNNS、Telnet
2. 传输层: TCP、UDP
3. 网络层: IP、ICMP、RIP、OSFF、BGP、IGMP
4. 链路层: (以太网) SLTP、CSLIP、PPP、ARP、RARP、MTU、ISO02110、IEEE802、IEEE802.2

TCP三次握手

## TCP报文头

如图 

seq number 4字节


