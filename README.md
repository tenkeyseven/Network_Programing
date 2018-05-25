# :star: Network Programming

This is a repository for Tenkey to upload some codes during the experiment by [SongTian](http://cs.bit.edu.cn/szdw/jsml/fjs/st/index.htm).

Tenkey will update it occasionally.


## No.1 Simple & Lovely Network-Packet-Capturing Tool

This tool aims to capture network packets and unpack them, to show you on your screen and finally save those packets in a `.pcap` file which can be opened by network-packet-capture tools like Wireshark.

### Some Basic Functionalities

+ You choose which network interface yoo want to capture.
+ You can set filter to get packets by conforming the Berkeley Packet Filter(BPF) syntax.
+ Also you can name your `.pcap` files or it will be automatically named by the timestamp.

### Program Running Screenshots

![setting](https://github.com/tenkeyseven/Network_Programing/blob/master/pictures/setting_and_packetcap.png)

In the beginning of this program,you can choose different Network interface to capture packets (if not, the default Network interface will be `ens33`,which you can change in the codes),and afterwards you can set BPF syntax to filter the enormous packets.
Striping packets through [DPKT](http://dpkt.readthedocs.io/en/latest/), packets structure is like that. 


![name](https://github.com/tenkeyseven/Network_Programing/blob/master/pictures/name.png)

you can just save by youself, it is up to you.

### Codes are below
Codes:  [tk_cap.py](https://github.com/tenkeyseven/Network_Programing/blob/master/tk_cap.py)
